# stm32_rpm_sensor
Programming MCU STM32 RPM Sensor

## Setting Compiler
- Buka file c_cpp_properties.json
- Ubah compilerPath jadi /usr/bin/arm-none-eabi-gcc
- Sesuaikan IncludePath
- Test compile program dengan make

## Mengatasi Error core_cm3.h
- Jika ada error: core_cm3.h: No such file or directory
- Download firmware CMSIS_4 >> [**Download CMSIS_4**](https://github.com/ARM-software/CMSIS_4)
- Copy File core_cm3.h atau semua file dari CMSIS_4 "CMSIS_4/CMSIS/Include"
- Paste file yang dicopy ke "Drivers/CMSIS/Device/ST/STM32F1xx/Include"
- Test compile program dengan make
- Pastikan tidak ada error

## Referensi Link
[**STM32 Blue Pill Timer Input Capture Mode with Frequency Measurement Example**](https://microcontrollerslab.com/stm32-blue-pill-timer-input-capture-mode-frequency-measurement/)