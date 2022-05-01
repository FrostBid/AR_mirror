# AR mirror
## Credits

* Forked and modified from https://github.com/charlielito/snapchat-filters-opencv


## Requirements
* OpenCV 3.0+ <4.0 with python bindings
* Python 3.8+
     * pillow
     * numpy
     * imutils
     * tkinter
      * dlib

```
pip install -r requirements.txt
```

### How it works

#### Dlib face and landmarks detection
Dlib and OpenCV libraries are adopted instead of the HarrCascades technique as it is able to estimate the inclination of the head and detection of face characteristics is easier. 


## Running the code
In Windows just double click the file `main_dlib.py` or execute in the console using the following. 


```
python main_dlib.py
```
