# Main code build rules

src-y += sched.c command.c basecmd.c debugcmds.c
src-$(CONFIG_HAVE_GPIO) += initial_pins.c gpiocmds.c stepper.c endstop.c \
    trsync.c
src-$(CONFIG_WANT_GPIO_ADC) += adccmds.c
src-$(CONFIG_WANT_GPIO_SPI) += spicmds.c
src-$(CONFIG_HAVE_GPIO_SDIO) += sdiocmds.c
src-$(CONFIG_WANT_GPIO_I2C) += i2ccmds.c
src-$(CONFIG_HAVE_GPIO_HARD_PWM) += pwmcmds.c

src-$(CONFIG_WANT_GPIO_BITBANGING) += buttons.c tmcuart.c neopixel.c \
    pulse_counter.c
src-$(CONFIG_WANT_DISPLAYS) += lcd_st7920.c lcd_hd44780.c
src-$(CONFIG_WANT_SOFTWARE_SPI) += spi_software.c
src-$(CONFIG_WANT_SOFTWARE_I2C) += i2c_software.c
src-$(CONFIG_WANT_THERMOCOUPLE) += thermocouple.c
src-$(CONFIG_WANT_ADXL345) += sensor_adxl345.c
src-$(CONFIG_WANT_LIS2DW) += sensor_lis2dw.c
src-$(CONFIG_WANT_LDC1612) += sensor_ldc1612.c
src-$(CONFIG_WANT_MPU9250) += sensor_mpu9250.c
src-$(CONFIG_WANT_HX71X) += sensor_hx71x.c
src-$(CONFIG_WANT_ADS1220) += sensor_ads1220.c
src-$(CONFIG_WANT_SENSOR_ANGLE) += sensor_angle.c
src-$(CONFIG_NEED_SENSOR_BULK) += sensor_bulk.c
