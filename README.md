# pcb-art
This repository explains how to do some beautiful PCB-based art and shows an example of one picture I did for my girlfriend.

## What will you need?
1. Altium Designer (script works only there)
2. PCB Logo Generator script (attached in the repository)
3. Picture generated in BMP

## Pre-requisites:
Assuming that you already have Altium installed and script ready-to-go, you need to make sure you have a picture. Picture requirements are the following:
1. BMP format in metric scale (mm or cm)
2. 300 dpi
3. Each part of the picture (main gradient, shadows etc) must be their own layer
4. Picture must have MAXIMUM of 3 layers: main background (PCB color), main picture (applied with PCB's top overlay), shadows/gradient (applied ising copper)
5. Each layer must contain the desired part of the picture with transparent (in BMP it is gonna be white)
