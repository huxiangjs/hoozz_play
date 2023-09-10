# Hoozz Play

## What is Hoozz Play?

Hoozz Play is an open source project based on the MIT license, and all supported hardware can interact and be used through it.

## Which hardware is supported?

1. MLX90640: Thermal imaging capabilities with 32x24 resolution.
2. (tell you later)

## Quick try

### MLX90640

The final files required for all projects have been provided, so compiling the source code is not necessary. You only need to follow the following steps to have your own thermal imager:

1. Download the [MLX90640_PCB.PcbDoc](https://github.com/huxiangjs/hoozz_play_mlx90640/blob/master/PCB/MLX90640_PCB.PcbDoc) file and send it to the factory for processing, you will get a circuit board.
2. Download the [MLX90640_Sheet.SchDoc](https://github.com/huxiangjs/hoozz_play_mlx90640/blob/master/PCB/MLX90640_Sheet.SchDoc) file and solder your circuit board according to this schematic.
3. Download the [GD32F350G8U6TR_MLX90640_V1.0.hex](https://github.com/huxiangjs/hoozz_play_mlx90640/releases/download/v1.0/GD32F350G8U6TR_MLX90640_V1.0.hex) file and use the official burning tool to burn the firmware into the MCU.
4. You need an Android phone, which needs a typc-c interface.
5. Download the [hoozz_play_release_v1.0.apk](https://github.com/huxiangjs/hoozz_play_android/releases/download/v1.0/hoozz_play_release_v1.0.apk) file and install the apk to your phone.

Okay, you're ready to start playing

## How to compile source code?

First you need to get the source code, you need to do this:
```shell
git clone https://github.com/huxiangjs/hoozz_play.git
cd hoozz_play/
git submodule init
git submodule update
```

After pulling the source code through the above steps, the Android source code is located in the hoozz_play_android/ directory of the current directory, and the MCU source code and hardware information are located in the hoozz_play_mlx90640/ subdirectory of the current directory.

Now, you can use the respective tools to compile them.

## Demo video

(tell you later)

:)
