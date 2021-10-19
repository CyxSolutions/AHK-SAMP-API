# AHK-SAMP-API
Modified UDF v18 Autohotkey API for SA:MP 0.3.7 R1 (SAMP:CAC)

*! For use with SAMP:CAC include after initializing global sampdll_base_address with SAMP:CAC Offset. !*

*! You may use the Offsetloader.asi in Combination with this API. !*

*! Use a function like the following before including API.ahk to determine GTA Folder. !*

```
RegRead, gta_folder, HKCU, Software\SAMP, gta_sa_exe
gta_folder := StrReplace(gta_folder, "gta_sa.exe")
```
