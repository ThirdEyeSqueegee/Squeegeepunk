# Preinstallation

1. Clean install Cyberpunk 2077 to a location _outside_ `Program Files`.
2. Install the [Visual C++ Redistributables](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/)
   - Extract the downloaded archive and run `install_all.bat`

# Installation

1. Download [Wabbajack](https://www.wabbajack.org) and place it in a folder away from your Cyberpunk 2077 installation and outside of any protected folders, something like `D:\Wabbajack`
2. Launch Wabbajack and go to "Browse Modlists"
3. Click the download button for Squeegeepunk
4. Click the run button
5. Set the installation directory to something like `D:\Squeegeepunk`, again, away from your Cyberpunk 2077 installation and outside of any protected folders. Make sure that the installation directory is on the same drive as Cyberpunk 2077.
6. Click the run button and wait for Wabbajack to complete the installation process

# Post-installation

1. If you have an AMD GPU, run the `DisableNvidiaSignatureChecks.reg` file found in `FSR3 Frame Gen for Cyberpunk 2077 (AMD)`
2. If you have an NVIDIA GPU that supports DLSS-FG, disable `FSR3 Frame Gen for Cyberpunk 2077 (AMD)`
3. If you have an NVIDIA GPU that doesn't support DLSS-FG, disable the `FSR3 Frame Gen for Cyberpunk 2077 (AMD)` mod and enable `FSR3 Frame Gen for Cyberpunk 2077 (NVIDIA)` instead
4. Find `ModOrganizer.exe` in the folder you installed the modlist to
5. Click the "Run" button on the top right in MO2 to launch Squeegeepunk
6. Enable frame generation in the graphics section of the in-game settings menu

# Updating

- Follow steps 2-4 from the Installation section above **with the addition of checking the `Overwrite` box before starting installation**.

## Reinstallation

In case something goes wrong during installation, reinstall the list by exiting Wabbajack, launching it again, and starting the installation again **with the addition of checking the `Overwrite` box**.
