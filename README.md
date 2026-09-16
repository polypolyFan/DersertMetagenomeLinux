
GTDB

gtdbtk-2.4.1             /home/lab/miniconda3/envs/gtdbtk-2.4.1

Using GTDB-Tk reference data version r226: /home/lab/database/gtdbtk/release226

gtdbtk classify_wf \
    --genome_dir test_gtdb \
    --out_dir test_gtdb_result \
    --extension fa \
    --cpus 8 \
    --skip_ani_screen
