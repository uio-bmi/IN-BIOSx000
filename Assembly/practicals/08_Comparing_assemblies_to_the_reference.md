Comparing assemblies to the reference
=====================================

The Quast program can be used to generate similar metrics as the
assemblathon_stat.pl script, plus some more and some visualisations.
QUAST works with or without a genome to compare it to. We will use it to
compare our assemblies to a reference. Thus, we need to give it a
reference genome and a reference annotation. When running QUAST, we can
look at one or more assemblies at the time.

`Quast` options:

* `-o`: name of output folder
* `-R`: Reference genome
* `-G`: File with positions of genes in the reference (see manual)
* `-T`: number of threads (cpu's) to use
* `sequence.fasta`: one or more files with assembled sequences
* `-l`:  comma-separated list of names for the assemblies, e.g. `"assembly 1,
assembly 2"` (in the same order as the sequence files)
* `--scaffolds`: input sequences are scaffolds, not contigs. They will be split
at 10 N's or more to analyse contigs ('broken' assembly)
* `--est-ref-size`:  estimated reference genome size (when genome not provided)
* `--gene-finding`: apply `GenemarkS` for gene finding

See the manual for information on the output of Quast:
[http://quast.bioinf.spbau.ru/manual.html#sec3](http://quast.bioinf.spbau.ru/manual.html#sec3)


### Running Quast

Go to the `assembly` folder, make a folder called `quast` and move into it.
Run this command (this is for one assembly, for examining more, add the assembly
fasta files).

Run this on the velvet paired end and mate pair assembly. Choose a sensible
output file name, and remember to type in the right path to the assembly.

```
quast.py -t 3 \
-o OUT_FOLDER_NAME \
-R /share/inf-biox121/data/assembly/GCF_000005845.2_ASM584v2_genomic.fna \
-G /share/inf-biox121/data/assembly/GCF_000005845.2_ASM584v2_genomic.gff \
../path/to/velvet_pe_mp \
-l "Velvet PE+MP"
```

Note that the `--scaffold` option is not used here for simplification. Also,
if there are multiple assemblies being compared, make sure you name the
assemblies (`-l`) in the same order as you give them to quast!

Note, it may give a warning regarding matplotlib, this is fine.


### Quast output
Quast will produce a html report file `report.html`. Use the file browser
(Places) to find the file in the Explorer, and double-click on it. It will
open the file in your browser. Hover over the row names to get a description.
Also have a look  at the 'Extended report'.

Questions:
  * What is the N50 for this assembly?
  * What is the NA50 for this genome?
  * How many whole genes have been found? How many partial genes?
  * How many misassmblies are there?
  * How much of the genome is unaligned?
  * How many mismatches and indels do we have?

Click on the "Icarus contig browser"
  * Can you figure out what contig (NODE) which is the long one?
  * Does the long contig seem to be correctly assembled?
  * Is this a good assembly in your eyes?