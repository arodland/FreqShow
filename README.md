# Freqshow

An improved version of FreqShow (https://github.com/adafruit/FreqShow) including
improvements from WQ7TPanadapter (https://github.com/Banjopkr/WQ7Tpanadapter)

# Features

* Layout optimized for larger screens (tested on the raspi 7" LCD)
* Touchpad driver for the raspi GPU touchscreen device (FT5406)
* Uses SoapySDR instead of pyrtlsdr, supporting many more SDR devices
* Supports decimation, allowing higher-sample-rate devices to work without
  overloading the CPU.
    * TODO: Add decimation to the GUI
* Optimized windowing and waterfall rendering to reduce CPU usage.
