# Opencv Image Transformations

## Usage

```
usage: opencv-transform.py [-h] --source SOURCE --destination DESTINATION
    [--resize] [--blur] [--gaussian] [--median]
    [--bilateral] [--erode] [--dilate]
    [--morphology {MORPH_OPEN,MORPH_CLOSE,MORPH_GRADIENT,MORPH_TOPHAT,MORPH_BLACKHAT}]
    [--threshold {THRESH_BINARY,THRESH_BINARY_INV,THRESH_TRUNC,THRESH_TOZERO,THRESH_TOZERO_INV,THRESH_BINARY+THRESH_OTSU}]
    [--adaptive {ADAPTIVE_THRESH_MEAN_C,ADAPTIVE_THRESH_GAUSSIAN_C}]
```

## Code Structure

    ├── bin
    │   └── opencv-transform
    ├── .editorconfig
    ├── .gitattributes
    ├── .gitignore
    ├── LICENSE.txt
    └── README.md

## License

This package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
