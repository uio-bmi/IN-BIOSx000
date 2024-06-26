# Software that will be used in the course

Several software packages for general sequence handling, alignment, genome assembly, assembly quality assessment, and variant calling will be used during the course. They will be made available on Fox.

Individual packages may be loaded with the following command (replace `BWA/0.7.17-GCCcore-12.2.0` with the name of the required module):

```sh
module load BWA/0.7.17-GCCcore-12.2.0
```

All of these packages will be part of meta-package that may be loaded with a similar command.

Below is a list of the packages that will be used (not updated yet):

Package | Version | Kind | Module | Documentation | Source code repository
--------|---------|------|--------|---------------|-----------------------
assembly-stats | 0.1.4 | Python library | assembly-stats/0.1.4-foss-2021b-Python-3.9.6 | [https://pypi.org/project/assembly-stats](https://pypi.org/project/assembly-stats) | [https://github.com/MikeTrizna/assembly_stats](https://github.com/MikeTrizna/assembly_stats)
BEDTools | 2.30.0 | Binary | BEDTools/2.30.0-GCC-11.2.0 | [https://bedtools.readthedocs.io/en/latest](https://bedtools.readthedocs.io/en/latest) | [https://github.com/arq5x/bedtools2](https://github.com/arq5x/bedtools2)
BWA | 0.7.17 | Binary | BWA/0.7.17-GCCcore-12.2.0 | [https://github.com/lh3/bwa](https://github.com/lh3/bwa) | [https://github.com/lh3/bwa](https://github.com/lh3/bwa)
bwa-mem2 | 2.2.1 | Binary | bwa-mem2/2.2.1 | [https://github.com/bwa-mem2/bwa-mem2](https://github.com/bwa-mem2/bwa-mem2) | [https://github.com/bwa-mem2/bwa-mem2](https://github.com/bwa-mem2/bwa-mem2)
EIGENSOFT | 7.2.1 | Binary | EIGENSOFT/7.2.1-foss-2021b | [https://github.com/DReichLab/EIG](https://github.com/DReichLab/EIG) |  [https://github.com/DReichLab/EIG](https://github.com/DReichLab/EIG)
FastQC | 0.11.9 | Java | FastQC/0.11.9-Java-11 | [https://www.bioinformatics.babraham.ac.uk/projects/fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc) | [https://github.com/s-andrews/FastQC](https://github.com/s-andrews/FastQC)
FASTX-Toolkit | 0.0.14 | Binary | FASTX-Toolkit/0.0.14-GCC-11.2.0 | [http://hannonlab.cshl.edu/fastx_toolkit](http://hannonlab.cshl.edu/fastx_toolkit) | [https://github.com/agordon/fastx_toolkit](https://github.com/agordon/fastx_toolkit)
Flye | 2.9.1 | Binary | Flye/2.9.1-GCC-11.2.0 | [https://github.com/fenderglass/Flye](https://github.com/fenderglass/Flye) | [https://github.com/fenderglass/Flye](https://github.com/fenderglass/Flye)
GATK | 4.2.6.1 | Java | GATK/4.2.6.1-GCCcore-11.2.0-Java-11 | [https://gatk.broadinstitute.org/hc/en-us](https://gatk.broadinstitute.org/hc/en-us) | [https://github.com/broadinstitute/gatk](https://github.com/broadinstitute/gatk)
MultiQC | 1.12 | Binary | MultiQC/1.12-foss-2021b | [https://multiqc.info](https://multiqc.info) | [https://github.com/ewels/MultiQC](https://github.com/ewels/MultiQC)
Pilon | 1.24 | Java | Pilon/1.24-Java-11 | [http://software.broadinstitute.org/software/pilon](http://software.broadinstitute.org/software/pilon) | [https://github.com/broadinstitute/pilon](https://github.com/broadinstitute/pilon)
PLINK | 1.9b6 | Binary | PLINK/1.9b_6.21-x86_64 | [https://www.cog-genomics.org/plink/1.9](https://www.cog-genomics.org/plink/1.9) | [https://www.cog-genomics.org/plink/1.9/dev](https://www.cog-genomics.org/plink/1.9/dev)
QUAST | 5.2.0 | Binary | QUAST/5.2.0-foss-2021b | [http://cab.spbu.ru/software/quast](http://cab.spbu.ru/software/quast) | [https://github.com/ablab/quast](https://github.com/ablab/quast)
SAMtools | 1.15 | Binary | SAMtools/1.15-GCC-11.2.0 | [https://www.htslib.org](https://www.htslib.org) | [https://github.com/samtools/samtools](https://github.com/samtools/samtools)
SPAdes | 3.15.5 | Binary | SPAdes/3.15.5-GCC-11.2.0 | [http://cab.spbu.ru/software/spades](http://cab.spbu.ru/software/spades) | [https://github.com/ablab/spades](https://github.com/ablab/spades)
Trimmomatic | 0.39 | Java | Trimmomatic/0.39-Java-11 | [http://www.usadellab.org/cms/?page=trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic) | [https://github.com/usadellab/Trimmomatic](https://github.com/usadellab/Trimmomatic)
Unicycler | 0.5.0 | Binary | Unicycler/0.5.0-gompi-2021b | [https://github.com/rrwick/Unicycler](https://github.com/rrwick/Unicycler) | [https://github.com/rrwick/Unicycler](https://github.com/rrwick/Unicycler)
VCFtools | 0.1.16 | Binary | VCFtools/0.1.16-GCC-11.2.0 | [https://vcftools.github.io/index.html](https://vcftools.github.io/index.html) | [https://github.com/vcftools/vcftools](https://github.com/vcftools/vcftools)
Velvet | 1.2.10 | Binary | Velvet/1.2.10-GCC-11.2.0-mt-kmer_191 | [https://github.com/dzerbino/velvet](https://github.com/dzerbino/velvet) | [https://github.com/dzerbino/velvet](https://github.com/dzerbino/velvet)
