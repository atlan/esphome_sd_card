idf_component_register(
  SRCS "__init__.py" "sd_mmc_card.cpp" "sd_mmc_card_esp32_arduino.cpp" "sd_mmc_card_esp_idf.cpp" "sensor.py" "text_sensor.py"
  INCLUDE_DIRS "."
)

include_builtin_idf_component(fatfs)
