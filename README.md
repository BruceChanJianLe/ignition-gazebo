# Ignition Gazebo

This repository demonstrate how to get around with Ignition Gazebo.

## Introduction

[link](https://www.youtube.com/watch?v=KIcFbCiK0QU)

## Installation

1.Configure package repositories.
```bash
sudo sh -c 'echo "deb http://packages.osrfoundation.org/gazebo/ubuntu-stable `lsb_release -cs` main" > /etc/apt/sources.list.d/gazebo-stable.list'
wget http://packages.osrfoundation.org/gazebo.key -O - | sudo apt-key add -
sudo apt-get update
```

2. Install Ignition Gazebo
```bash
sudo apt-get install libignition-gazebo<#>-dev
# Use tab tab to auto complete and select from list
```
[link](https://ignitionrobotics.org/api/gazebo/6.1/install.html)

## Usage

```bash
ign gazebo
```
[link](https://ignitionrobotics.org/libs/gazebo)

## Models

This is where you can view/share/download models files from the community. 
