# Ridgeback Description
In order to faciliate editing structures, payloads, and edit other features on the Ridgeback, we use the following environment variables.

## Lasers
Select one front and one rear laser.
#### Front Hokuyo Laser
```bash
export RIDGEBACK_FRONT_HOKUYO_LASER=1
```
#### Rear Hokuyo Laser
```bash
export RIDGEBACK_REAR_HOKUYO_LASER=1
```
#### Front Sick Laser
```bash
export RIDGEBACK_FRONT_SICK_LASER=1
```
#### Rear Sick Laser
```bash
export RIDGEBACK_REAR_SICK_LASER=1
```
#### Front S300 Laser
```bash
export RIDGEBACK_FRONT_S300_LASER=1
```
#### Rear S300 Laser
```bash
export RIDGEBACK_REAR_S300_LASER=1
```

## Microstrain GX3, GX5, GX25
```bash
export RIDGEBACK_IMU_MICROSTRAIN=1
export RIDGEBACK_IMU_MICROSTRAIN_LINK="microstrain_link"
export RIDGEBACK_IMU_MICROSTRAIN_PARENT="base_link"
export RIDGEBACK_IMU_MICROSTRAIN_OFFSET="-0.139 0.096 0.100"
export RIDGEBACK_IMU_MICROSTRAIN_RPY="3.14159 0 -1.5707"
```

## Microstrain  GX2 Legacy
```bash
export RIDGEBACK_MICROSTRAIN_IMU=1
export RIDGEBACK_MICROSTRAIN_IMU_PREFIX="upgraded"
export RIDGEBACK_MICROSTRAIN_IMU_MOUNT="mid"
export RIDGEBACK_MICROSTRAIN_IMU_OFFSET="0 0 0"
export RIDGEBACK_MICROSTRAIN_IMU_RPY="0 0 0"
```