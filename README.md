# Device Tree for Lumia 650 (saana)

The Lumia 650 (codenamed _"saana"_) is a low-end smartphone from Microsoft.
It was released in February 2016.

| Basic                   | Spec Sheet                                       |
| -----------------------:|:------------------------------------------------ |
| CPU                     | Quad-core 1.3 GHz Cortex-A7                      |
| Chipset                 | Qualcomm MSM8909v2 Snapdragon 212 (28 nm)        |
| GPU                     | Adreno 304                                       |
| Memory                  | 1 GB RAM                                         |
| Shipped Android Version | NONE                                             |
| Storage                 | 16 GB                                            |
| Battery                 | removable Li-Ion 2000 mAh battery                |
| Display                 | 720 x 1280 pixels, 16:9 ratio (~297 ppi density) |
| Camera (Back)           | 8 MP, AF, LED flash, 720p@30fps                  |
| Camera (Front)          | 5 MP                                             |


![Lumia 650](https://fdn2.gsmarena.com/vv/pics/microsoft/lumia-650-01.jpg)


## Build instructions

```
# Compiling
$ . build/envsetup.sh
$ lunch omni_saana-eng
$ make -jx recoveryimage

```

**Kernel Source**: https://github.com/sonic011gamer/android_kernel_microsoft_saana
