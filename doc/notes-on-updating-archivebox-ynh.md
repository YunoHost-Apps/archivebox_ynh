this is documentation for developers working on archivebox_ynh package (or myself in the future),
for how to keep this package up to date with the upstream archivebox package on GitHub
as it is updated.

## 1. Modify the Manifest.toml
Replace the following fields:
replace "version"
(under "resources.sources.main") replace "url", "sha256"



## 2. Modify conf/requirements.txt
requirements.txt contains a single line, which correlates to the archivebox upstream pip install script;
e.g. in requirements.txt `archivebox==0.7.2;` from `pip install --upgrade 'archivebox==0.7.2'`
