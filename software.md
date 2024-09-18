# Software that will be used in the course

Several software packages for general sequence handling, alignment, genome assembly, assembly quality assessment, and variant calling will be used during the course. They will be made available on Fox.

Individual packages may be loaded with the following command (replace `BWA/0.7.17-GCCcore-12.2.0` with the name of the required module):

```sh
module load BWA/0.7.17-GCCcore-12.2.0
```

All of these packages will be part of meta-package that may be loaded with a similar command.

Below is a list of the packages that will be used (not updated yet):

Fox | Package | Version | Kind | Module | Documentation | Source code repository
----|---------|---------|------|--------|---------------|-----------------------
No  | assembly-stats | 0.1.4 | Python library | assembly-stats/0.1.4-foss-2021b-Python-3.9.6 | [https://pypi.org/project/assembly-stats](https://pypi.org/project/assembly-stats) | [https://github.com/MikeTrizna/assembly_stats](https://github.com/MikeTrizna/assembly_stats)
No  | BEDTools | 2.30.0 | Binary | - | [https://bedtools.readthedocs.io/en/latest](https://bedtools.readthedocs.io/en/latest) | [https://github.com/arq5x/bedtools2](https://github.com/arq5x/bedtools2)
Yes | BWA | 0.7.17 | Binary | BWA/0.7.17-GCCcore-12.2.0 | [https://github.com/lh3/bwa](https://github.com/lh3/bwa) | [https://github.com/lh3/bwa](https://github.com/lh3/bwa)
No  | bwa-mem2 | 2.2.1 | Binary | - | [https://github.com/bwa-mem2/bwa-mem2](https://github.com/bwa-mem2/bwa-mem2) | [https://github.com/bwa-mem2/bwa-mem2](https://github.com/bwa-mem2/bwa-mem2)
Yes | EIGENSOFT | 7.2.1 | Binary | EIGENSOFT/7.2.1-foss-2022a | [https://github.com/DReichLab/EIG](https://github.com/DReichLab/EIG) |  [https://github.com/DReichLab/EIG](https://github.com/DReichLab/EIG)
Yes | FastQC | 0.11.9 | Java | FastQC/0.11.9-Java-11 | [https://www.bioinformatics.babraham.ac.uk/projects/fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc) | [https://github.com/s-andrews/FastQC](https://github.com/s-andrews/FastQC)
No  | FASTX-Toolkit | 0.0.14 | Binary | - | [https://github.com/agordon/fastx_toolkit](https://github.com/agordon/fastx_toolkit) | [https://github.com/agordon/fastx_toolkit](https://github.com/agordon/fastx_toolkit)
Yes | Flye | 2.9.1 | Binary | Flye/2.9.1-GCC-11.2.0 | [https://github.com/fenderglass/Flye](https://github.com/fenderglass/Flye) | [https://github.com/fenderglass/Flye](https://github.com/fenderglass/Flye)
Yes | GATK | 4.3.0.0 | Java | GATK/4.3.0.0-GCCcore-11.3.0-Java-11 | [https://gatk.broadinstitute.org/hc/en-us](https://gatk.broadinstitute.org/hc/en-us) | [https://github.com/broadinstitute/gatk](https://github.com/broadinstitute/gatk)
No  | MultiQC | 1.12 | Binary | - | [https://multiqc.info](https://multiqc.info) | [https://github.com/ewels/MultiQC](https://github.com/ewels/MultiQC)
No  | Pilon | 1.24 | Java | - | [https://github.com/broadinstitute/pilon/wiki](https://github.com/broadinstitute/pilon/wiki) | [https://github.com/broadinstitute/pilon](https://github.com/broadinstitute/pilon)
Yes | PLINK | 2.00a3.7 | Binary | PLINK/2.00a3.7-foss-2022a | [https://www.cog-genomics.org/plink/2.0](https://www.cog-genomics.org/plink/2.0) | [https://www.cog-genomics.org/plink/2.0/dev](https://www.cog-genomics.org/plink/2.0)
No  | QUAST | 5.2.0 | Binary | - | [https://quast.sourceforge.net/docs/manual.html](https://quast.sourceforge.net/docs/manual.html) | [https://github.com/ablab/quast](https://github.com/ablab/quast)
Yes | SAMtools | 1.17 | Binary | SAMtools/1.17-GCC-12.2.0 | [https://www.htslib.org](https://www.htslib.org) | [https://github.com/samtools/samtools](https://github.com/samtools/samtools)
Yes | SPAdes | 3.15.5 | Binary | SPAdes/3.15.5-GCC-11.3.0 | [https://ablab.github.io/spades/](https://ablab.github.io/spades/) | [https://github.com/ablab/spades](https://github.com/ablab/spades)
Yes | Trimmomatic | 0.39 | Java | Trimmomatic/0.39-Java-11 | [http://www.usadellab.org/cms/?page=trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic) | [https://github.com/usadellab/Trimmomatic](https://github.com/usadellab/Trimmomatic)
No  | Unicycler | 0.5.0 | Binary | - | [https://github.com/rrwick/Unicycler](https://github.com/rrwick/Unicycler) | [https://github.com/rrwick/Unicycler](https://github.com/rrwick/Unicycler)
Yes | VCFtools | 0.1.16 | Binary | VCFtools/0.1.16-GCC-11.3.0 | [https://vcftools.github.io/index.html](https://vcftools.github.io/index.html) | [https://github.com/vcftools/vcftools](https://github.com/vcftools/vcftools)
No  | Velvet | 1.2.10 | Binary | - | [https://github.com/dzerbino/velvet](https://github.com/dzerbino/velvet) | [https://github.com/dzerbino/velvet](https://github.com/dzerbino/velvet)
