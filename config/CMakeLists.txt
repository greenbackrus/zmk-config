# CMakeLists.txt в корне (config/)
zephyr_library()

# Важно: добавь этот путь, если используешь zmk-nice-oled
zephyr_include_directories(app/lib/zmk-nice-oled)