# Datasets

This directory contains all datasets used for Task 1 and Task 4.

## Task 1: Graph Datasets
Located in `graph/` directory:
1. Epinions social network
   - Source: https://snap.stanford.edu/data/soc-Epinions1.html
   - Download: `wget https://snap.stanford.edu/data/soc-Epinions1.txt.gz`

2. Youtube Social Network
   - Source: https://snap.stanford.edu/data/com-Youtube.html
   - Download: `wget https://snap.stanford.edu/data/bigdata/communities/com-youtube.ungraph.txt.gz`

3. Google Web Graph
   - Source: https://snap.stanford.edu/data/web-Google.html
   - Download: `wget https://snap.stanford.edu/data/web-Google.txt.gz`

4. LiveJournal social network
   - Source: https://snap.stanford.edu/data/soc-LiveJournal1.html
   - Download: `wget https://snap.stanford.edu/data/soc-LiveJournal1.txt.gz`

After downloading, extract using: `gunzip *.gz`

## Task 4: EDGAR Datasets
1. Small datasets (in `edgar_small/`)
   - Source: https://github.com/miyurud/lectures/tree/main/2024/nibm/bt/course-work/datasets/task4
   - Download using git clone and copy relevant files

2. Large dataset generation (in `edgar_large/`)
   - Uses OOSimulator: https://github.com/miyurud/OOSimulator
   - Clone repository and follow instructions to generate 1M records
