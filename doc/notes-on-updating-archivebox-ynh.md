This is intended to be documentation for developers working on the archivebox_ynh package

## 1. Modify the Manifest.toml
Replace the following fields:
replace "version"
(under "resources.sources.main") replace "url", "sha256"



## 2. Modify conf/requirements.txt
requirements.txt contains a single line, which correlates to the archivebox upstream pip install script;
e.g. in requirements.txt `archivebox==0.7.2;` `from pip install --upgrade 'archivebox==0.7.2'`
