# RetinaNet
-----------------

### Training
Put the data to `/data/VOCDevkit/VOC0712`,make sure the data is like:`/data/VOCDevkit/VOC0712/ImageSets`  
```
cd lib
make
```
run `./experiments/scripts/RetinaNet_end2end.sh 0 RetinaNet pascal_voc0712 --set RNG_SEED 43 TRAIN.SCALES "[640]"`

#Before commit
Plz clean all `*.pyc` and `*.so` file using this command:
```
find ./step1 -name "*.so" | xargs rm -rf
find ./step1 -name "*.pyc" | xargs rm -rf
```

