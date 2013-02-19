rotate
======

Screen rotation script with wacom tablet rotation and font rendering adjustment.

## Installation
    mkdir -p ~/bin
    wget https://raw.github.com/fdietze/rotate/master/rotate -O ~/bin/rotate
    chmod +x ~/bin/rotate

## Usage
    Usage:
        rotate <target> [output]
    
    Targets:
        normal      landscape
        inverted    inverted landscape
        left        portrait left
        right       portrait right
        cw          clockwise
        ccw         counterclockwise
        180         180 degrees
        horizontal  flip between normal/inverted
        vertical    flip between left/right
