if (CONFIG_BCM2835_I2C_DRIVER)
	zephyr_include_directories(include)
	zephyr_include_sources(libbcm2835_i2c_driver.c)
endif()
