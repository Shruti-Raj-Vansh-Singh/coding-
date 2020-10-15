#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
Created on Thu Oct 15 19:29:19 2020

@author: shruti
"""

#CUT OFF RANK

#inputs
scores = [100,20,50,50]
cutOff = 3
num = 4
count=0
#actual program
d = {}
rank = 0
n = len(scores)
for i in range(0,n):
    m = max(scores)
    if m not in d.keys():
        rank+=1
        d[m]=rank
    elif m in d.keys():
        if rank<= cutOff:
            count+=1
            d[m]=rank
            rank+=1
    scores.remove(m)

print(d)
#counting the occurence of people who quallify

for val in d.values():
    if (val<=cutOff):
        count+=1
print("Output = ", count)
        