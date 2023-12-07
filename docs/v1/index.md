# tfsites.VisualizePhenotypicGenotypes v1

**Author(s):** Joe Solvason  

**Contact:** Joe Solvason (solvason@eng.ucsd.edu)

**Adapted as a GenePattern Module by:** Ted Liefeld (jliefeld@cloud.ucsd.edu)

**Task Type:** Transciption factor analysis

**LSID:**  urn:lsid:genepattern.org:module.analysis:00442


## Introduction

tfsites.VisualizePhenotypicGenotypes  creates a visualization showing all SNV effects that overlap with genotypes

## Functionality

TBD

## Methodology

TBD

## Parameters

<span style="color: red;">*</span> indicates required parameter

- **input data**<span style="color: red;">*</span>
    - This is a [ state what the format and content is supposed to be] file containing DNA sequences to be analyzed.
- **zoom**<span style="color: red;">*</span>
    - Zoom location for plot 
- **out filename**<span style="color: red;">*</span>
    - Out file name for the annotated PBM data
- **beta**
    - Run in beta mode if TRUE.
- **bed.files**<span style="color: red;">*</span>
    - Zero or more BED files.
- **gff.files**<span style="color: red;">*</span>
    - Zero or more gff3 files
- **gff.command.file**<span style="color: red;">*</span>
    - This is a test file containing details how to parse the gff file with one file per line in the format <filename>=<commands>  e.g. "input_gff_file.gff3=feature_col:2,chr_col:0,start_col:3,end_col:4,skiplines:0" .



## Input Files

1.  input data.  Tab delimited file [ define format and contents in detail ] 
    
2. bed files. Zero or more bed files. [ define format and contents in detail  ]

2. gff files. Zero or more gff files. [ define format and contents in detail  ]

2. gff commad file. 



## Creating Input Files from User Data

TBD Describe how to get common data formats into the format needed here
       
## Output Files

  1.PBM: <output prefix>.pbm.tsv.  Tab-separated text file TBD.
    e.g. 
```
seq     rel_aff
AAAAAAAA        0.147
AAAAAAAC        0.107
AAAAAAAG        0.13
AAAAAAAT        0.125
AAAAAACA        0.123

```
    
  
## Example Data

[Example input data is available on github](https://github.com/genepattern/tfsites.inSilicoSnvAnalysis/data)
    
## References

Cancer Genome Atlas Network. Comprehensive genomic characterization of head and neck squamous cell carcinomas. Nature. 2015 Jan 29;517(7536):576-82. doi: 10.1038/nature14129. PMID: 25631445; PMCID: PMC4311405.
    
## Version Comments

- **1.0.0** (2023-01-12): Initial draft of document scaffold.
