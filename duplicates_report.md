# Bug Issue Analysis Report

## Identified Duplicates

### Duplicate Pair 1: Arduino IDE Version Mismatch
*   **Original Issue:** [#178 Slightly outdated Board URL for Arduino IDE](https://github.com/ricardoquesada/bluepad32/issues/178) (Opened Sep 3, 2025)
*   **Duplicate Issue:** [#190 4.2.0 doesn't appears on arduino IDE](https://github.com/ricardoquesada/bluepad32/issues/190) (Opened Nov 9, 2025)
*   **Analysis:** Both issues describe the discrepancy between the latest Bluepad32 version available on GitHub (4.2.0) and the version available in the Arduino IDE (4.1.0). Issue #190 is a direct duplicate of #178.

## Analyzed but Not Duplicates

### Connection/Disconnection Issues
*   **Issue:** [#194 DualShock 4 connects, virtual device is created, then L2CAP PSM 0x13 closes](https://github.com/ricardoquesada/bluepad32/issues/194)
*   **Issue:** [#193 Dualshock 3 (Sixaxis) disconnecting](https://github.com/ricardoquesada/bluepad32/issues/193)
*   **Analysis:** While both involve disconnection, they involve different hardware (DualShock 4 on ESP32 vs DualShock 3 on Pico W) and different failure modes. #194 involves a specific crash/disconnect after virtual device creation, whereas #193 involves a disconnection after a short period. They are likely distinct issues.
