# Blur Blockchain Database for Full Node Bootstrapping

For use with **v0.1.9.9.5**

A compressed archive of data directory for the blur blockchain.  Just a copy of LMDB database.

## Instructions For Use

- Create a directory `mkdir ~/blur-bootstrap`
- Move into directory: `cd ~/blur-bootstrap`
- Download bootstrap with: `wget https://github.com/blur-network/blur-bootstrap/raw/main/bootstrap-data-dir.tar.gz`
- If you have a partially synced blockchain in your data directory, back up your old data directory with:
  - `mv ~/.blurnetwork ~/.blurnetwork-old`
- Unzip the archive: `tar xvzf bootstrap-data-dir.tar.gz`
- Move uncompressed data directory to proper location: `mv ./.blurnetwork ~/`
- Launch `blurd` and sync remainder of blockchain.