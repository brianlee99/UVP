# UVP

UVP is a suite of bioinformatics programs and scripts for the analysis of NGS (next generation sequencing) data.

## Software dependencies:
| Name            | Version |
|-----------------|---------|
| BEDtools        | 2.17.0  |
| Bcftools        | 1.2     |
| BWA             | 0.7.12  |
| FastQC          | 0.11.5  |
| Fastqvalidator  | 1.0.5   |
| GATK            | 3.4.0   |
| Kraken          | 0.10.5  |
| Picard          | 1.134   |
| Prinseq-lite.pl | 0.204   |
| Pigz            | 2.3.3   |
| Qualimap        | 2.1.1   |
| Samtools        | 1.2     |
| SnpEff          | 4.1     |
| Vcftools        | 0.1.126 |

## Installation

The UVP requires at least 100GB RAM and up to 100GB storage space to run locally. Installing the UVP on your local machine is straight forward. Clone the entire repository, and download the specific versions of each of the third party tools listed above into the 'Local Directory Path'/uvp/bin folder. You will need to edit the config.yml file in the 'Local Directory Path'/uvp/bin folder to point to the correct directory and file paths of all the scripts and tools listed.

Run the UVP using command line prompts by invoking the UVP module in the 'Local Directory Path'/uvp/scripts directory:

```'Local Directory Path'/uvp/scripts/UVP -q 'input fastq' -r 'path to H37Rv reference genome fasta file' -n 'sample name' -q2 'paired fastq file' -a -v ```




