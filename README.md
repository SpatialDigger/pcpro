![pcpro_logo-01](https://user-images.githubusercontent.com/17065805/211750218-ff6902a9-e405-4bef-861d-1a275e3f906a.jpg)

# Contents
+ About
+ Documentation
+ Change log

# ABOUT
Welcome to Point Cloud Processor, this program helps clean overlapping point clouds so they can be combined and turned into a solid mesh.

# DOCUMENTATION
In progress...

# CHANGE LOG

## 0.3.2
### To do
+ Crashes if 'set' button is pressed before Between distance
+ Enable radius filter
+ Enable concave prefilter
+ Automatically check for updates
+ User preferences, css theme
+ Enable multiple files
+ Add support for other files import/export
+ Reset stats when new files are added
+ Documentation
+ Improve Between Distance visualisation, including colour maps

## 0.3.1

Status: awaiting release (expected 2023)

**NEW FEATURES** 

+ **Point cloud attributes** 
  + Switch between colours
  + Real colours
  + Pseudo colours
  + Elevation colours
  + Between distance

+ **Splashscreen**
  + Splashscreen added

**BUG FIXES** 
+ Crashing when loading new files
+ z-coordinate included in distance calculation

**IMPROVEMENTS**
+ Compliling to exe file 
+ Dark theme adopted
+ Log file, top/base file list added
+ Min/Max distance filter added to Summary
+ Standardised filtering for display and export

## 0.3.0

Complete rewrite of the software in Python 3.9, dropping pptk for Open3D's viewer, vast time improvewments by adopting Numpy arrays
Alpha testing only.
