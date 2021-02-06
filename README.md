# Blur Blockchain Database for Full Node Bootstrapping

A compressed archive of data directory for the blur blockchain.  Just a copy of LMDB database.

## Instructions For Use

- Clone this repository with `git clone https://github.com/blur-network/blur-bootstrap.git`
- `cd` into `blur-bootstrap` directory
- If you have a partially synced blockchain in your data directory, back up your old data directory with:
  - `mv ~/.blurnetwork ~/.blurnetwork-old`
- Unzip the archive: `tar xvzf bootstrap-data-dir.ar.gz`
- Move uncompressed data directory to proper location: `mv ./.blurnetwork ~/`
- Launch `blurd` and sync remainder of blockchain.