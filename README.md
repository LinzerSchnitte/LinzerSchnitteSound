# LinzerSchnitteMidi

LinzerSchnitteMidi generate pure tones using a MIDI interface for controlling LinzerSchnitte Receivers

## Install from source code


```bash
git clone https://github.com/NeuralSpaz/LinzerSchnitteSound.git
cd LinzerSchnitteSound/
```

### Compile / Install

The following packages are required to build LinzerSchnitteSound:

```bash
sudo apt-get install libasound2-dev
```

Compile LinzerSchnitteMidi as follows:

```bash
gcc LinzerSchnitteMidibeta0.5.c -o LinzerSchnitteMidi -lm -lasound
```

## Run LinzerSchnitteMidi on raspPi

 * ``` $ ./LinzerSchnitteMidi  LinzerSchnitteMIDI <hw:0,0,1> 0.001 0.001 1 0 ```



