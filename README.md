# Detecting and Tracking Moving Objects on a Convey Belt

In this project I have implemented an object detecting and tracking algorithm using computer vision techniques. Algorithm is able to count nuts on a moving convey belt.

#### Convey Belt Video Stream

![convey belt](https://github.com/OshanJayawardana/object-detection-tracking-on-convey-belt/blob/main/resources/convey%20belt.gif)
---

I have used *Contour Analysis* to detect and track nuts on the convey belt. Additionaly I have also discussed about the *Connected Component Analysis*. You can experiment with code by running the Jupyter Notebook cells in `main.ipynb`.
When video stream of the convey belt is fed, algorithm is able to detect each nut on the convey belt, number each nut, and display the nut number and its' coordinates on the screen.

#### Dependencies

* `python 3.8`
* `opencv`
* `numpy`
* `matplotlib`

#### Output

![object detected video](https://github.com/OshanJayawardana/object-detection-tracking-on-convey-belt/blob/main/resources/object%20detected.gif)
