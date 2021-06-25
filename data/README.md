# data

## crypto_wake_up_sample_sheet.tsv

Text file in tsv format that contains the codified metadata for the samples found in the project.
    
## CW_kallisto_abundance_fold_change_long_by_gene.tsv

Text file in tsv format that contains the read counts on transcripts of all *nuclear* coding genes in all conditions. 
Created by the` normalise_crypto_wake_up.Rmd` file using the `CW_kallisto1_abundance_long_by_sample_by_isoform.tsv` file. 
Uses the codification of temperature and time described in `crypto_wake_up_sample_sheet.tsv`.

*Warning:* genes that begin `CNAG_09` are encoded in the mitochondrial genome, and were not included in this analysis although they are present in the other files.
    
## H99_all_genes_promoter_500nt.fasta
    
Raw promoter sequences for all gene in Cryptococcus genome. 
Downloaded from FungiDB (release 52, June 2021) with the approximation that the promoter for each is gene is the first 500nt upstream of start codon.

## H99_all_genes_promoter_500nt_5mer_counts.tsv.gz

Compressed tsv file of kmer counts. Contains counts for every possible 5-mer in every Cryptococcus gene promoter, as defined in H99_all_genes_promoter_500nt.fasta. Created by the count_kmers.Rmd file.
    
## H99_all_genes_promoter_500nt_4mer_counts.tsv.gz

Compressed tsv file of kmer counts. Contains counts for every possible 4-mer in every Cryptococcus gene promoter, as defined in H99_all_genes_promoter_500nt.fasta. Created by the count_kmers.Rmd file.
    
## H99_all_genes_promoter_500nt_3mer_counts.tsv.gz

Compressed tsv file of kmer counts. Contains counts for every possible 3-mer in every Cryptococcus gene promoter, as defined in H99_all_genes_promoter_500nt.fasta. Created by the count_kmers.Rmd file.
    
## H99_all_genes_promoter_500nt_2mer_counts.tsv.gz

Compressed tsv file of kmer counts. Contains counts for every possible 2-mer in every Cryptococcus gene promoter, as defined in H99_all_genes_promoter_500nt.fasta. Created by the count_kmers.Rmd file.
    
## H99_all_genes_promoter_500nt_1mer_counts.tsv.gz

Compressed tsv file of kmer counts. Contains counts for every possible 1-mer in every Cryptococcus gene promoter, as defined in H99_all_genes_promoter_500nt.fasta. Created by the count_kmers.Rmd file.

## H99_all_gene_ids.tsv
    
Text file in tsv format that contains a list of all annotated gene IDs in the Cryptococcus H99 genome.
Downloaded from FungiDB release 52, June 2021.
