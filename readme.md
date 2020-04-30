## Circos


### Input files

1. RepeatMasker GFF3 file.

2. Genome annotation file

3. Chromosome Length file.


wyim @ login-0 10:20:48 ~/scratch/Share/bca_circos_data/Circos
```bash
 perl scripts/PreDraw.pl  --repeat_gff ../ Bca.repeat.gff  --gene_gff ../Bca.gff3 --chrlen ../circos.chrlen
 ```
