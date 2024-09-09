
```bash
# path-prepend /exp/dune/app/users/yuhw/wct/cfg WIRECELL_PATH
# path-prepend /exp/dune/app/users/yuhw/opt/lib64/ LD_LIBRARY_PATH
source /exp/dune/app/users/yuhw/dunefd/test-BlobDepoFill/setup.sh
wire-cell -l stdout -L debug -c wct-sim-fans.jsonnet
```


 - I was not able to install wire-cell-python on gpvms yet for the newer gpvms with AlmaLinux9
 - Currently I am copying the files back to a local machine with wire-cell-python installed
 - I remember this used to work
```bash
source /exp/dune/app/users/yuhw/wire-cell-python/wcpy/bin/activate
python wct-img-2-bee.py clusters-apa-reco-6.tar.gz clusters-apa-bdf-6.tar.gz
./zip-upload.sh
```
