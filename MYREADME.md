# PARSeq

#### _PREDICT ONE IMAGE_
```
python3 ./read.py pretrained=parseq refine_iters:int=2 decode_ar:bool=false \ 
--images <image_path>
```

#### _INFERENCE IMAGES_
```
python3 ./read.py pretrained=parseq refine_iters:int=2 decode_ar:bool=false \ 
--data_root <path/to/lmdb_dataset>
```