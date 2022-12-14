# Stegcurity

**Version:** 1.0

**Authors:** Thushi

## Introduction 

Stegcurity is a Least Significant Bit Steganography tool created to hide messages in to the images. Stegcurity has two main functions and a sub function. Stenographic LSB encoding and decoding. Encoding embeds a secret image in the last significant bits of a cover image. Decoding extracts a secret image from an steganographic image using LSB. The other sub function is List the PNG images. 

## Screenshots

![Sublist3r](Screenshot/interface.png "Sublist3r in action")


## Installation

```
git clone https://gitlab.com/thushi99/isp-stegnography-tool.git
```

## Recommended Python Version:

Stegcurity currently supports **Python 2** and **Python 3**.

* The recommended version for Python 2 is **2.7.x**
* The recommended version for Python 3 is **3.4.x**

## Dependencies:

Sublist3r depends on the `cv2`, `numpy`, `pyfiglet`, `termcolors`, `os`, `base64` and `platform` python modules.

These dependencies can be installed using the requirements file:

- Installation on Windows:
```
pip install -r requirements.txt
```
- Installation on Linux
```
sudo pip install -r requirements.txt
```

Alternatively, each module can be installed independently as shown below.

#### cv2 Module (https://pypi.org/project/opencv-python/)

- Install for Windows:
```
pip install opencv-python
```

- Install using pip on Linux:
```
sudo pip install opencv-python
```

#### numpy Module (https://numpy.org/install/)

- Install for Windows:
```
pip install numpy
```

- Install using pip on Linux:
```
sudo pip install numpy
```

#### termcolor Module (https://pypi.org/project/termcolor/)

- Install for Windows:
```
pip install termcolor
```

- Install using pip on Linux:
```
sudo pip install termcolor
```

#### pyfiglet Module (https://pypi.org/project/pyfiglet/)

- Install for Windows:
```
pip install pyfiglet
```

- Install using pip on Linux:
```
sudo pip install pyfiglet
```

## How to Run
- Windows:
```
python stegcurity.py
```

- Linux:
```
python stegcurity.py
```
or
```
python3 stegcurity.py
```

## Restrictions
* Currently this version support for hiding messages only within `.png` format Images
