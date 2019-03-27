# citypersons2voc
A tool that converts CityPersons dataset into PASCAL VOC format.  
* CityPerson Images: https://www.cityscapes-dataset.com/  
* CityPerson Annoations: https://bitbucket.org/shanshanzhang/citypersons/overview  

Some of the images in training set contain no instances, the script will filter them out.
```
Expected number of images:
  train: 2778 (filtered)
  val  : 500  (full set)
```


## Usage
1. Modify the paths in the `main.py`.
2. Modify the `lbl_map` in `main.py`. (I only need ped so ignored other classes)
3. Execute `python3 main.py`

