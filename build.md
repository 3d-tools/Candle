# Build last version (Linux):

Ref.: https://github.com/Denvi/Candle/issues/147#issuecomment-350221474

## Install QT5 & requirements

```shell
sudo apt-get install g++ qt5-default qttools5-dev-tools libqt5serialport5-dev libqt5opengl5-dev
```
## Clone Candle and switch to GRBL 1.1 branch

```shell
git clone https://github.com/Denvi/Candle.git
cd Candle
git checkout grbl_1_1
```

## Run Qmake

```shell
cd src
qmake
```

## Build with the generated Makefile

```shell
make
./Candle
```
