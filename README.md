# QMK Firmware for Space65 R3 Wired ANSI PCB

My QMK firmware repo for Space65 R3 Cute Assassin.

## Flash Guide

1. Hold `ESC` and plug the board in
2. Flash the firmware using QMK Toolbox

### Or use QMK CLI to flash
`qmk compile -kb gray_studio/space65r3 -km shigure -j 32`

`qmk flash -kb gray_studio/space65r3 -km shigure -j 32`

## Overview
- QWERTY layout with navigation layer for left hand
- Layer indicator LEDs
- Adv Tap-Dance and One-shot layer/mod
- Key Override
- Win Lock
- RGB Timeout

## To-Do
- [ ] Win Lock indicator

## Known Issue
Deadlock on system reboot.