Build tested with ESP IDF v4.4.8 

https://docs.espressif.com/projects/esp-idf/en/v4.4.8/esp32/get-started/index.html#setting-up-development-environment

Not guaranteed to work with other versions!

Certain build cache errors can be fixed by deleting build and managed_components folders in the project.
```
export ARDUINO_SKIP_TICK_CHECK=1
rm -rf managed_components && idf.py build
```
