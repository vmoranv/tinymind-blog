---
title: DISM三板斧
date: 2024-10-22T10:58:51.480Z
---

Powershell:

1. ```power
   DISM.exe /Online /Cleanup-Image /ScanHealth
   ```

2. ```powershell
   DISM.exe /Online /Cleanup-Image /CheckHealth
   ```

3. ```powershell
   DISM.exe /Online /Cleanup-Image /RestoreHealth
   ```

4. ```powershell
   SFC /SCANNOW
   ```