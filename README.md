# conda-sync

Synchronizes a conda package repository such as `https://repo.continuum.io/pkgs/free/linux-64/` with a local directory. Only updates packages whose MD5 checksums don't match with the online repo.

Usage: `./conda-sync /path/to/local/repo` or just `./conda-sync` to download to `/var/tmp/conda/linux-64`.

See also http://conda.pydata.org/docs/custom-channels.html.
