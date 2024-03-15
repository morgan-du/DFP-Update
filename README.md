# DFP Update Procedure

Mbed Studio is a valuable tool for developing code on Mbed OS and supported boards. Nuvoton's NuMaker boards equipped with Nu-Link2-ME support the debug feature in Mbed Studio. However, the current version of Mbed Studio (v1.4.5) does not yet include updates to support Nu-Link2-ME. Please follow the steps below to enable this feature:

## Update Procedure

- Ensure Mbed Studio is closed before proceeding.
- Download both the Nuvoton.NuMicro_DFP...pack and cmsis_pack.json files required for this update.
- Copy these two downloaded files to the designated directory on your system:

__For Windows Users__
C:\Users\YOUR-ACCOUNT\AppData\Local\Mbed Studio\mbed-studio-tools\cmsis-packs

__For Linux Users__
~/.config/Mbed Studio/mbed-studio-tools/cmsis-packs

Once the files are copied, launch Mbed Studio to apply the updates and enable the Nu-Link2-ME support feature.

