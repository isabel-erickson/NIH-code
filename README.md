# NIH-code

This repository contains code that I wrote while at the Segre lab at the NIH. My work there focused on improving reference-based methods for classifying metagenomic DNA sequences. Most of this code is aimed at data processing, cleaning, and analysis.

## kraken2_processing.Rmd

This file is a Rmarkdown tutorial that I made to help my labmates process standard kraken2 output into phyloseq object containing a taxa table built with taxonomizr and an OTU table. I wrote an R function that processes a directory of kraken2 output files into a phyloseq object.

## database_comparisons.Rmd

Preliminary analysis comparing how three kraken2 databases classified the same fastqs of metagenomic reads from several sites on the human skin.

## unmappedreads_processing.Rmd

Code I wrote and used while working on my project to classify metagenomic reads that did not map to reference genomes in the lab's Clinical Pathoscope database. I used BLASTn to align reads that were unmapped by Clinical Pathoscope to public databases of reference genomes. I processed the output of the BLAST searches and the Clinpath alignments into phyloseq objects. 

## figuremaking.Rmd

Code to replicate figures from my talk - You find what you look for: Improving reference-based methods of classifying metagenomic sequences. 
