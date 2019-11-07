# grvc-ual
[![Releases](https://img.shields.io/github/release/grvcTeam/grvc-ual.svg)](https://github.com/grvcTeam/grvc-ual/releases)

A repository for the GRVC UAV abstraction layer.

## Installation and use

Download the latest stable version from [here](https://github.com/grvcTeam/grvc-ual/releases).

You can find the instructions for installation and how to use the UAL in the [Wiki](https://github.com/grvcTeam/grvc-ual/wiki).

## Compatibile autopilots

### [PX4](https://github.com/PX4/Firmware)

 * Via [ual_backend_mavros]() and [ual_backend_mavlink]()
 * In simulation (SITL): version [v1.7.3](https://github.com/PX4/Firmware/tree/v1.7.3)
 * Flying: versions from [v1.7.3](https://github.com/PX4/Firmware/tree/v1.7.3) to [v1.9.2](https://github.com/PX4/Firmware/tree/v1.9.2)

### [Ardupilot](http://ardupilot.org/) (beta)

 * Via [ual_backend_mavros]()
 * Last tested version [v3.6.9](http://firmware.ardupilot.org/Copter/stable-3.6.9)

### DJI A3/N3

 * Via [ual_backend_dji_ros]()
 * ROS dji_sdk version [TBD]()
 * DJI Onboard SDK version [TBD]()

## Citation
If you find UAL useful in your research, please consider citing:

```
@inproceedings{real2018ual,
    Author = {Fran Real, Arturo Torres-González, Pablo Ramón Soria, Jesús Capitán and Aníbal Ollero},
    Title = {UAL: an abstraction layer for unmanned vehicles},
    Booktitle= {2nd International Symposium on Aerial Robotics (ISAR)},
    Year = {2018}
}
```
