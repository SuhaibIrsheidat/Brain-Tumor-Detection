# Brain Tumor Detection Using _TensorFlow CNN_  
  
### - You can download the dataset from *[Google Drive](https://drive.google.com/drive/folders/1PZhotdQ5HCgDg1rSfcJCDsB-EkE3biCf?usp=sharing).*  
  
  
### - Dataset consist of:  
```
- [data]
  - [yes]
    - Y1.jpg
    - Y2.jpg ...
  - [no]
    - 1 no.jpg
    - 2 no.jpg ...
```

### - Instructions:  
*- Libraries must be installed:*
   - Tensorflow >= 1.4
   - Tflearn
   - OpenCV
   - Pandas 
   - Matplotlib
   - Numpy
   - *_Or you can simply install Anaconda_*
  
*- You can import the ```code.ipynb``` to Colab or Jupyter Notebook.*  
*- Make sure to change the ```data``` directory to the appropriate path.*  
*- Labels:*
   - `[1,0]` Tumor.
   - `[0,1]` No Tumor.
      - NN will predict a probability `in range [0,1]`; Whenever it closer to `[1]` then there is Tumor.
  
  
*_Regards._*  
> Suhaib Irsheidat
