# Hayday-Plan

Hey this is a file with some updates for you,
Looking for updated code? 
Okay here it is for task 1
.
.
import argparse

import numpy as np
import cv2 as cv

def str2bool(v: str) -> bool:
    if v.lower() in ['true', 'yes', 'on', 'y', 't']:
        return True
    elif v.lower() in ['false', 'no', 'off', 'n', 'f']:
        return False
    else:
        raise NotImplementedError
