# Software that will be used in the course

Several software packages for general sequence handling, alignment, genome assembly, assembly quality assessment, and variant calling will be used during the course. They are available as software modules on Fox. The table below shows the packages that will be used.

Individual packages may be loaded with the following command (replace `BWA/0.7.17-GCCcore-12.2.0` with the name of the required module):

```sh
module load BWA/0.7.17-GCCcore-12.2.0
```

The packages indicated with a 'Yes' in the first column in the table below are part of large meta module that may be loaded all together with this command:

```sh
module load IN-BIOS5000/HT-2024
```

The BWA and SAMtools modules can be loaded together simultaneously, but not at the same time as the other modules.

The Flye, Velvet, MultiQC, and Unicycler modules can also be loaded together simultaneously, but not at the same time as the other modules.

The nf-core module can not be loaded at the same time as the other modules.

You may need to unload all or some modules in order to load other modules. All modules may be unloaded with the `module purge` command, and individual modules may be unloaded with the `module unload` command.


Meta | Package | Version | Kind | Module | Documentation | Source code repository
----|---------|---------|------|--------|---------------|-----------------------
Yes | assembly-stats | 0.1.4 | Python library | assembly-stats/0.1.4-foss-2022a | [https://pypi.org/project/assembly-stats](https://pypi.org/project/assembly-stats) | [https://github.com/MikeTrizna/assembly_stats](https://github.com/MikeTrizna/assembly_stats)
Yes | BEDTools | 2.30.0 | Binary | BEDTools/2.30.0-GCC-11.3.0 | [https://bedtools.readthedocs.io/en/latest](https://bedtools.readthedocs.io/en/latest) | [https://github.com/arq5x/bedtools2](https://github.com/arq5x/bedtools2)
No  | BWA | 0.7.17 | Binary | BWA/0.7.17-GCCcore-12.2.0 | [https://github.com/lh3/bwa](https://github.com/lh3/bwa) | [https://github.com/lh3/bwa](https://github.com/lh3/bwa)
Yes | EIGENSOFT | 7.2.1 | Binary | EIGENSOFT/7.2.1-foss-2022a | [https://github.com/DReichLab/EIG](https://github.com/DReichLab/EIG) |  [https://github.com/DReichLab/EIG](https://github.com/DReichLab/EIG)
Yes | FastQC | 0.11.9 | Java | FastQC/0.11.9-Java-11 | [https://www.bioinformatics.babraham.ac.uk/projects/fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc) | [https://github.com/s-andrews/FastQC](https://github.com/s-andrews/FastQC)
Yes | FASTX-Toolkit | 0.0.14 | Binary | FASTX-Toolkit/0.0.14-GCC-11.3.0 | [https://github.com/agordon/fastx_toolkit](https://github.com/agordon/fastx_toolkit) | [https://github.com/agordon/fastx_toolkit](https://github.com/agordon/fastx_toolkit)
No  | Flye | 2.9.1 | Binary | Flye/2.9.1-GCC-11.2.0 | [https://github.com/fenderglass/Flye](https://github.com/fenderglass/Flye) | [https://github.com/fenderglass/Flye](https://github.com/fenderglass/Flye)
Yes | GATK | 4.3.0.0 | Java | GATK/4.3.0.0-GCCcore-11.3.0-Java-11 | [https://gatk.broadinstitute.org/hc/en-us](https://gatk.broadinstitute.org/hc/en-us) | [https://github.com/broadinstitute/gatk](https://github.com/broadinstitute/gatk)
No  | MultiQC | 1.12 | Binary | MultiQC/1.12-foss-2021b | [https://multiqc.info](https://multiqc.info) | [https://github.com/ewels/MultiQC](https://github.com/ewels/MultiQC)
Yes | Nextflow | 24.04.2 | Java | Nextflow/24.04.2 | [https://www.nextflow.io/docs/latest/index.html](https://www.nextflow.io/docs/latest/index.html) | [https://www.nextflow.io/docs/latest/install.html](https://www.nextflow.io/docs/latest/install.html)
No  | nf-core | 2.13.1 | - | nf-core/2.13.1-foss-2023b | [https://nf-co.re/docs](https://nf-co.re/docs) | [https://nf-co.re/docs/nf-core-tools/installation](https://nf-co.re/docs/nf-core-tools/installation)
Yes | Pilon | 1.24 | Java | Pilon/1.24-Java-11 | [https://github.com/broadinstitute/pilon/wiki](https://github.com/broadinstitute/pilon/wiki) | [https://github.com/broadinstitute/pilon](https://github.com/broadinstitute/pilon)
Yes | PLINK | 2.00a3.7 | Binary | PLINK/2.00a3.7-foss-2022a | [https://www.cog-genomics.org/plink/2.0](https://www.cog-genomics.org/plink/2.0) | [https://www.cog-genomics.org/plink/2.0](https://www.cog-genomics.org/plink/2.0)
Yes | QUAST | 5.2.0 | Binary | QUAST/5.2.0-foss-2022a | [https://quast.sourceforge.net/docs/manual.html](https://quast.sourceforge.net/docs/manual.html) | [https://github.com/ablab/quast](https://github.com/ablab/quast)
No  | SAMtools | 1.17 | Binary | SAMtools/1.17-GCC-12.2.0 | [https://www.htslib.org](https://www.htslib.org) | [https://github.com/samtools/samtools](https://github.com/samtools/samtools)
Yes | SPAdes | 3.15.5 | Binary | SPAdes/3.15.5-GCC-11.3.0 | [https://ablab.github.io/spades/](https://ablab.github.io/spades/) | [https://github.com/ablab/spades](https://github.com/ablab/spades)
Yes | Trimmomatic | 0.39 | Java | Trimmomatic/0.39-Java-11 | [http://www.usadellab.org/cms/?page=trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic) | [https://github.com/usadellab/Trimmomatic](https://github.com/usadellab/Trimmomatic)
No  | Unicycler | 0.5.0 | Binary | Unicycler/0.5.0-gompi-2021b | [https://github.com/rrwick/Unicycler](https://github.com/rrwick/Unicycler) | [https://github.com/rrwick/Unicycler](https://github.com/rrwick/Unicycler)
Yes | VCFtools | 0.1.16 | Binary | VCFtools/0.1.16-GCC-11.3.0 | [https://vcftools.github.io/index.html](https://vcftools.github.io/index.html) | [https://github.com/vcftools/vcftools](https://github.com/vcftools/vcftools)
No  | Velvet | 1.2.10 | Binary | Velvet/1.2.10-GCC-11.2.0-mt-kmer_191 | [https://github.com/dzerbino/velvet](https://github.com/dzerbino/velvet) | [https://github.com/dzerbino/velvet](https://github.com/dzerbino/velvet)
