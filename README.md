# SORT Object Tracking

This project is my implementation/exploration of the **SORT (Simple Online and Realtime Tracking)** 
algorithm, based on the original work by **Alex Bewley** and the paper:

> Bewley, A., Ge, Z., Ott, L., Ramos, F., & Upcroft, B. (2016). 
> Simple Online and Realtime Tracking. *2016 IEEE International Conference on Image Processing (ICIP)*.
> [Paper link](http://arxiv.org/abs/1602.00763)

Original repository: https://github.com/abewley/sort

## About this project
I used Alex Bewley's SORT algorithm and reference implementation as the basis for this project 
to learn about multi-object tracking. [Add a line or two here about what you personally did — 
e.g. "I adapted it to run on my own video input," "I tested it with a custom detector," 
"I modified X to do Y," etc.]

### Introduction
SORT is a barebones implementation of a visual multiple object tracking framework based on 
rudimentary data association and state estimation techniques. It is designed for online tracking 
applications where only past and current frames are available and the method produces object 
identities on the fly.

### Dependencies
```
pip install -r requirements.txt
```

### Demo
```
python sort.py
```

### Citing SORT
If you use this in your own work, please cite the original paper:
```
@inproceedings{Bewley2016_sort,
  author={Bewley, Alex and Ge, Zongyuan and Ott, Lionel and Ramos, Fabio and Upcroft, Ben},
  booktitle={2016 IEEE International Conference on Image Processing (ICIP)},
  title={Simple online and realtime tracking},
  year={2016},
  pages={3464-3468},
  doi={10.1109/ICIP.2016.7533003}
}
```

### License
This project is released under the GPL-3.0 License, same as the original SORT repository, 
in the LICENSE file.
