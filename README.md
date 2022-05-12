# STARlight
RNA-seq STAR Pipeline

module load snakemake-6.0.2 STAR-2.7.6a subread-2.0.1 picard-2.23.8 fastqc-0.11.9 R-4.0.3 multiqc-1.9 cutadapt-3.3 samtools-1.11 deeptools-3.5.0
snakemake -p --cores 12 -s /home/massi/Documents/repo/STARlight/STARlight.smk --configfile /mnt/WD2/BIN22P008_SK/config.json
