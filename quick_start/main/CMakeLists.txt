idf_component_register(SRCS
"quick_start.c"
INCLUDE_DIRS "."
REQUIRES mbedtls REQUIRES srtp REQUIRES json REQUIRES esp_netif REQUIRES fatfs REQUIRES vfs REQUIRES esp_common REQUIRES esp_timer REQUIRES esp_lcd REQUIRES nvs_flash
)