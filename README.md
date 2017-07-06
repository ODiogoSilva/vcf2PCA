## vcf2PCA

Principal component analysis of SNP data with the creation of an interactive plot

## Requirements

vcf2PCA requires R and the following libraries:

- SNPRelate
- plotly

## Usage

```
vcf2PCA <vcf_file> <output_name> <pop_file (optional)>
```

The optional <pop_file> is a comma separated file with the name of the taxon in the first column and the corresponding group in the second column. Example:

```
TaxonA, Group1
TaxonB, Group1
TaxonC, Group2
.
.
.
```

## Output example:
