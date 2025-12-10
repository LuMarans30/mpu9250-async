# `mpu6050-async`

> async no_std driver for the MPU6050 6-axis IMU, based on the [`mpu6050`](https://crates.io/crates/mpu6050) crate by Julian Gaal.

## What Works

* Reading the accelerometer, gyroscope, temperature sensor
    * raw
    * scaled
    * roll/pitch estimation
* Motion Detection
* Setting Accel/Gyro Ranges/Sensitivity
* Setting Accel HPF/LPF

## Basic usage

To use this driver you must provide a concrete `embedded_hal_async` implementation.

Refer to the original [`mpu6050`](https://crates.io/crates/mpu6050) crate for usage examples. This crate is identical to `mpu6050`, but some functions are `async`.
