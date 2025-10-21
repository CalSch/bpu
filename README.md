# Blender Processing Unit

uh im making a cpu in blender geo nodes

i'll update this file when i make progress

## how it works

- memory is a bunch of points with an integer `mem_value` named attribute
    - memory is initially loaded from a string in the file `cpu_mem` where each byte is two hex digits and separated by a newline
- theres a simulation zone with all the stuff in it and each frame one instruction happens
- instructions are defined as closures (im using blender 5.0 which is in beta rn)
    - each closure gets the current state and outputs the new state
    - if they use arguments (eg. LDA #$67 might be stored as 01 67 where $67 is the first argument) then they have to add to the PC

## progress

nvm just look at manual.txt

## misc things

### hex digit to int

![lotta noodles](https://raw.githubusercontent.com/CalSch/bpu/refs/heads/main/stuff/manynoodles.png)


