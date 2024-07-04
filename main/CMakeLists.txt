idf_component_register(SRCS "main.cpp"
                    INCLUDE_DIRS "."
                    REQUIRES wifi_provisioning espressif__qrcode nvs_flash)