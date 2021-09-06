this is documentation for developers working on archivebox_ynh package (or myself in the future),
for how to keep this package up to date with the upstream archivebox package on github
as it is updated.

## 1. apt-get dependencies

Look at Dockerfile in https://github.com/ArchiveBox/ArchiveBox to determine which dependencies 
need to be specified in scripts/_common.sh

## 2. node dependencies
Copy package.json and package-lock.json from https://github.com/ArchiveBox/ArchiveBox to 
conf/package.json and conf/package-lock.json respectively. 