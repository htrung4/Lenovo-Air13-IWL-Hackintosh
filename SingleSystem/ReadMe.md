# Air13IWL OpenCore 单系统建议

- EFI - OC -ACPI
  - 移除 SSDT-OSYS.aml
  - 移除 SSDT-BKEY.aml
  - 添加 [SSDT-TPXX.aml](SSDT-TPXX.aml)
  - 替换 [SSDT-RMCF.aml](SSDT-RMCF.aml)
- EFI - OC - Config.plist 
  - ACPI - Add
    - 移除 OSYS
    - 移除 BKEY
    - 添加 TPXX
  - ACPI - Patch
    - 移除 Windows to Xindows 更名
    - 移除 _Q11 to XQ11 更名
    - 移除 _Q12 to XQ12 更名