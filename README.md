#  Rock Paper Scissors Image Recognition Project

## Introduction
This project is a image recognition tool for the game 'Rock paper scissors'.

This AI is able to classify "rock", "paper", and "scissors" in the game 'Rock paper scissors'. It has been tested on different angles and rotations of the hand.

## Equipment
- NVIDIA Jetson Nano Developer Kit
- An USB Camera

## Setup Guide
Manual Setup
~~~
sudo apt update
sudo apt -y upgrade

sudo apt install python3-pip python3-dev

sudo -H pip3 install --upgrade pip
sudo -H pip3 install virtualenv

mkdir jupyter-notebook
cd jupyter-notebook

virtualenv jupyterenv
source jupyterenv/bin/activate

pip install jupyter

git clone https://github.com/MysticalWizard/jetson-nano-rock-paper-scissors

jupyter notebook
~~~

## Current Limitations
Currently, the AI performs worse in low light environments. However, I belive that this issue can be resolved by training the AI with more low lit images and with various backgrounds.

## Extensions
To take this project further, I could add commonly used sign languages to the list to make this project more applicable to the real world scenario.

## Demo Video
https://youtu.be/kACVNQiI3tk
