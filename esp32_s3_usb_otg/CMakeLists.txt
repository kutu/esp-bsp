idf_component_register(
    SRCS "esp32_s3_usb_otg.c"
    INCLUDE_DIRS "include"
    PRIV_INCLUDE_DIRS "priv_include"
    REQUIRES driver
    PRIV_REQUIRES fatfs esp_lcd esp_timer usb esp_adc
)
