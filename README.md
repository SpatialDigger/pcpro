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

## 0.4.x
### To do
+ Crashes if 'set' button is pressed before Between distance **BUG**
+ Crashes if statistical filter is pressed when values are zero **BUG**
+ Enable radius filter **FEATURE**
+ Enable concave prefilter **FEATURE**
+ Automatically check for updates **FEATURE**
+ User preferences, css theme **FEATURE**
+ Enable multiple files **FEATURE**
+ Add support for other files import/export **FEATURE**
+ Reset stats when new files are added **BUG**
+ Documentation **FEATURE**
+ Improve Between Distance visualisation, including colour maps **IMPROVEMENT**
+ Enable multithreading **IMPROVEMENT**
+ loading bars **IMPROVEMENT**
+ Licensing support **FEATURE**

## 0.4.1
Status: in development

**NEW FEATURES** 
+ **Data** 
  + Enable multiple pointcloud files (import only)
  
 **BUG FIXES** 
 
 **IMPROVEMENTS**

## 0.4.0
Status: user testing
**NEW FEATURES** 
+ None

 **BUG FIXES** 
 + None
 
 **IMPROVEMENTS**
+ Distributed as a MSI installer
+ Speed enhancements by restructuring the underlying class DataFames
+ Updated to 2024 release

## 0.3.1

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
