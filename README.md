# Klipper_KP3S
![alt text](https://github.com/nehilo/klipper_KP3S/blob/main/klipper%20kp3s.png?raw=true)

PID Calibration console EXTRUDER
```bash
PID_CALIBRATE HEATER=extruder TARGET=240
```
PID Calibration console BED
```bash
PID_CALIBRATE HEATER=heater_bed TARGET=80
```

Firmware

```bash
cd ~/klipper
```
```bash
make menuconfig
```

![alt text](https://github.com/nehilo/klipper_KP3S/blob/main/make.png?raw=true)

```bash
make 
```

```bash
./scripts/update_mks_robin.py out/klipper.bin out/Robin_nano.bin
```

You question and main information you can checked https://cutt.ly/Cgow7vL
