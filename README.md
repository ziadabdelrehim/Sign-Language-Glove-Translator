# Sign Language Glove Translator

This Arduino project implements a sign language glove translator using an accelerometer, 5 flex sensors, a speaker, and an SD module. The glove recognizes specific hand gestures and plays corresponding audio phrases to facilitate communication in sign language.

## Demo Video
Watch the [demo video](https://github.com/ziadabdelrehim/Sign-Language-Glove-Translator/issues/1#issue-1994216548) to see the sign language glove translator in action.

## Problem
- Deaf people have a primary way of communicating with others, which is sign language.
- Most people don't understand sign language.
- We need a translating tool to make communication easier between deaf individuals and others.

## Objective
The idea is to create a translating tool that can convert sign language into understandable words for everyone. The tool is a glove equipped with sensors on each finger capable of detecting changes in finger positions. By recognizing the symbols formed by hand gestures (sign language), the glove translates them into speech.

## Components Used
- MMA8453 Accelerometer
- 5 Flex Sensors (connected to analog pins A0 to A7)
- Speaker
- SD module for storing audio files
- Arduino Nano board

## Wiring
- Connect the MMA8453 Accelerometer to the I2C pins.
- Connect the 5 flex sensors to analog pins A0 to A7.
- Connect the speaker to digital pin 9.
- Connect the SD module to digital pin 10.

## Libraries
Make sure to install the necessary libraries in the Arduino IDE:
- Wire.h
- MMA8453_n0m1 (for accelerometer)
- TMRpcm (for audio playback)
- SD (for SD module)
- SPI (for SD module)
- PCM (for audio quality)



Feel free to modify the code to enhance or customize the project based on your requirements.
