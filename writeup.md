Jupyter Notebook
writeup.md
21時間前
Markdown
File
Edit
View
Language

1
# **Finding Lane Lines on the Road** 
2
​
3
## Writeup Template
4
​
5
### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.
6
​
7
---
8
​
9
**Finding Lane Lines on the Road**
10
​
11
The goals / steps of this project are the following:
12
* Make a pipeline that finds lane lines on the road
13
* Reflect on your work in a written report
14
​
15
​
16
[//]: # (Image References)
17
​
18
[image1]: ./examples/grayscale.jpg "Grayscale"
19
​
20
---
21
​
22
### Reflection
23
​
24
### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.
25
​
26
My pipeline consists of five steps.
27
① I picked the lane in color.
28
② I converted it to grayscale.
29
③ I determined the size of the kernel and blurred the image by Garcia smoothing.
30
④ I performed edge detection by the Canny method.
31
⑤ I made ROI.
32
⑥ I merged the color selection image with the edge detection image.
33
⑦ The region of interest was applied.
34
⑧ I ran Hough transform to detect line.
35
⑨ I extrapolated and averaged to extend of the straight line
36
⑩ I merged Input image and straight line image. 
37
​
38
![alt text][image1]
