# AnnotationTool

## Dependencies
### Requirements
- Python 3.8+
- numpy 1.24.1
- opencv-contrib-python 4.8.0.74

### It was ran and tested under the following OSs:
- Windows 10 Home

## Preparing Data
You need to prepare data with the **.png** extension.

### Usage
    python main.py -i path/to/png/file

### For more help in details
    python main.py --help

### Keyboard usage
#### Press '**s**'
    Save the binary mask of the input image, the binary mask's filename will be saved as input/file/name_bainary_mask.png in the image_gt directory.
#### Press '**c**'
    Remove all the annotations of the input image

### Demo
![2023-08-07 03-09-10](https://github.com/KevinTsaiCodes/AnnotationTool/assets/53148219/f93d5958-8133-454a-8d89-f557bbe85179)