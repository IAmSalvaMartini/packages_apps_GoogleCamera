# Google Camera For Vince

Reworked Google Camera for Vince

## How To Build

* Clone This Repository to "ROM_DIR/packages/apps/GoogleCamera"
* Add following defination in your device makefile
``` 
# GoogleCamera
$(call inherit-product-if-exists, packages/apps/GoogleCamera/gcam.mk)
```
* Now you can build normally.
