# NVIDIA Drivers Debloated
A collection of NVIDIA drivers debloated and modded to increase peformance and privacy.

## CHANGES 📋

★ Debloated the drivers\
★ Added Support for unsupported cards\
★ Removed NVIDIA Telementry\
★ Removed Geforce Experience (It decreases peformance by alot as it is always recording your game)

## Removing your current driver

You can skip this step if you are on a clean install of windows with no graphics driver or if you are installing a new graphics card.

Enter safe mode by clicking win + r and typing msconfig then tick the safe mode box and reboot into safe mode and when you are booted into safe mode repeat this process but untick safe mode.

Open [DDU](https://www.guru3d.com/files-details/display-driver-uninstaller-download.html) and Select GPU on the right hand side of the program and then click Clean and restart.

![Screenshot_1](https://user-images.githubusercontent.com/97028842/147969626-ae18dc13-6352-46ce-80d0-01a79d825c5a.png)


Once your computer is restarted your current driver has been removed and you can move onto installing the custom driver.



## How to install the drivers

Unzip the driver with a program like 7zip or winrar.

![Screenshot_2](https://user-images.githubusercontent.com/97028842/147942443-bff03397-44d4-47ef-9862-e4152b7dba2c.png)

Open the folder you just unzipped and run setup.exe then click "AGREE AND CONTINUE".


![Screenshot_3](https://user-images.githubusercontent.com/97028842/147943303-a0efee2c-e344-4996-a636-6db666a73f1a.png)

Select "Custom (Advanced)" and click on Next.

![Screenshot_4](https://user-images.githubusercontent.com/97028842/147943815-23b71096-0e1c-4335-b84a-1ec5880849ba.png)

Select "Peform a clean installation" and click on Next and the installation will begin.

![Screenshot_5](https://user-images.githubusercontent.com/97028842/147944170-e8cf729f-42bb-4f1f-9229-51809d972869.png)

Your screen may flash and turn off during the installation, when the installation has completed you can close out of the installer.

Open [Everything Search](https://www.voidtools.com/) and search for "NvTelemetry64.dll" and delete all results that appear.

![Screenshot_8](https://user-images.githubusercontent.com/97028842/147944965-c2c28b76-9df9-43f5-b9bc-2d05e2932894.png)

The installation process is now finished, you can tweak the driver with tools such as NvProfileInspector or just change your NVIDIA Control Panel Settings.

The Driver can also be installed via NVCleanInstall but I am not currently offering a guide on how to do so.
