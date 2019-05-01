# ECG baseline: filtering examples using C++

ECG signal baseline filtering using Savitzky-Golay, Zero-phase Butterworth and Wavelets filters

## Dependencies

- QT5Core
- Eigen3


## Compiling (OS X)

1. Clone this repo
2. Run inside the repo:
```bash
cmake ./
```
3. Then run:
```bash
make
```

## Running

After following the compiling steps above, you can run the code by executing
```bash
./ecg-baseline
```

The code will read the ECG sample data from ecgdata.cpp and output 4 files:
- **signal_base.txt**: the original ECG data
- **wavelet.txt**: wavelet filtering
- **butterworth.txt**: butterworth filtering
- **savitzkygolay.txt**: Savitzky-Golay filtering