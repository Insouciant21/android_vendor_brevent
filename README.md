In `vendor/lineage/config/common.mk` file, towards the end, add:
```makefile
$(call inherit-product, vendor/thirdparty/config.mk)
```
