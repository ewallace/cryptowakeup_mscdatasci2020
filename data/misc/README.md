# misc

## crypto_wake_up_sample_sheet_plus_tags.txt

NOT USED IN SWS PROJECT. Text file in tsv format that contains the original project sample sheet. Contains surplus information such as the DNA tags to separate reads from different samples. Also uses the old codification of temperature and time.
    
## CW_kallisto1_abundance_long_by_sample_by_isoform.tsv
    
NOT USED IN SWS PROJECT. Text file in tsv format that contains the read counts for all isoforms of all genes in all conditions. Used to create the  CW_kallisto_abundance_fold_change_long_by_gene.tsv file which is required for the project. Uses the codification of temperature and time described in crypto_wake_up_sample_sheet.tsv
    
## H99_all_genes_terminator_250nt.fasta
    
NOT USED IN SWS PROJECT. Raw terminator sequences for all gene in Cryptococcus genome. Downloaded from fungiDB with the assumption that the terminator for each is gene is simply the first 250nt downstream of stop codon.
    
## H99_all_genes_terminator_250nt_5mer_counts.tsv.gz

NOT USED IN SWS PROJECT. Compressed tsv file of kmer counts. Contains counts for every possible 5-mer in every Cryptococcus gene terminator, as defined in H99_all_genes_terminator_250nt.fasta. Created by the count_kmers.Rmd file.
