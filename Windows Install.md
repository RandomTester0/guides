# Windows 11 Installation Guide

This guide walks you through the process of installing Windows 11 on your computer. Follow the steps below for a clean installation.

## Step 1: Download and Create a Windows Installation USB Drive

1. **Download Windows 11**  
   Go to the official [Microsoft Download Page for Windows 11](https://www.microsoft.com/en-gb/software-download/windows11/).

2. **Choose Media Creation Tool**  
   Scroll down and click **Download Now** to get the **Media Creation Tool**. This tool will help you create a bootable USB drive for Windows 11 installation.

3. **Prepare a USB Drive**  
   Insert a USB drive (minimum 8GB in size) into your computer. Make sure the USB drive has no important data, as it will be wiped during this process.

4. **Run the Media Creation Tool**  
   Once the tool is downloaded, run it. Accept the terms and conditions, and choose the option to create installation media for another PC.

5. **Select Language, Edition, and Architecture**  
   Choose your preferred language, Windows edition, and architecture (64-bit is the most common). If you're unsure, leave the default settings selected.

6. **Select USB Flash Drive**  
   Choose "USB flash drive" when prompted. The tool will automatically detect available USB drives. Select your USB drive and click **Next**.

7. **Wait for the Creation Process to Finish**  
   The Media Creation Tool will download Windows 11 and create a bootable USB drive. This may take some time, depending on your internet speed.

---

## Step 2: Boot from the USB Drive

1. **Plug the USB into Your Computer**  
   Insert the USB drive with the Windows 11 installer into the target computer.

2. **Start the Computer**  
   Power on or restart the computer.

3. **Access the Boot Menu**  
   If the computer doesn't automatically boot from the USB, you'll need to access the boot menu. This is usually done by pressing a key such as **F2**, **F12**, **ESC**, or **DEL** immediately after turning on the computer. The exact key may vary, so refer to your computer’s manual or look for a prompt on the screen during boot.

4. **Select USB Device**  
   From the boot menu, select your USB drive as the boot device and press **Enter**.

---

## Step 3: Install Windows 11

1. **Start the Installation**  
   The Windows 11 installation process should begin. The first screen will ask you to select your region and language. Choose your preferences and click **Next**.

2. **Install Windows**  
   Click **Install Now**. If prompted for a product key, either enter it if you have one or choose the **I don’t have a product key** option to skip this step.

3. **Accept the License Agreement**  
   Read the terms and conditions, then click **Accept** to continue.

4. **Select Installation Type**  
   Choose **Custom: Install Windows only (advanced)** for a fresh installation.

5. **Partition Your Drive**  
   The installer will show a list of available disks, labeled as **Disk 0**, **Disk 1**, etc. To ensure you're selecting the correct disk:
   
   - Look at the **Total Size** of each disk to identify the main storage drive (it will usually be the largest disk).
   - Be cautious not to select any smaller drives or external drives (if applicable).
   - If you're installing on a new system or reformatting, you’ll need to delete any existing partitions on the selected disk. You can do this by selecting the partition, clicking **Delete**, and confirming the deletion.
   - Once the drive shows as **Unallocated Space**, select it and click **Next** to proceed with the installation.

   > **Note:** Deleting partitions will erase all data on that drive, so double-check before proceeding.

---

## [Optional] SSD Not Showing Up?

1. **Install Chipset Drivers**  
   If your SSDs do not show up during the installation, it's likely due to missing chipset drivers for your motherboard. To resolve this, you’ll need to load the drivers from your motherboard's manufacturer.

2. **Download Chipset Drivers**  
   Go to the manufacturer’s website (e.g., ASUS, MSI, Gigabyte, etc.) and download the latest chipset drivers. Transfer these drivers to a USB drive.

3. **Load the Drivers During Installation**  
   While on the disk selection screen, click **Load Driver**. Insert the USB drive containing the chipset drivers and browse to the location of the drivers. Select them and continue.

4. **Continue Installation**  
   Once the drivers are loaded, your SSD should now appear as a selectable drive. Select it and click **Next** to proceed with the installation.

---

## Step 4: Out-Of-Box Experience (OOBE) Setup

1. **Complete OOBE**  
   Once the installation is complete, the computer will reboot and enter the **Out-of-Box Experience (OOBE)**. This is the process where you’ll set up your account, preferences, and other settings.

2. **Skip Microsoft Account (Optional)**  
   By default, Windows 11 prompts you to sign in with a Microsoft account. If you'd prefer to set up a local account instead, you can bypass this screen:
   
   - When you reach the Microsoft account sign-in screen, press **Shift + F10** to open a Command Prompt window.
   - In the command prompt, type the following command and press **Enter**:
     ```bash
     start ms-cxh:localonly
     ```
     This will take you to the option to create a local account.

3. **Create a Local Account**  
   Follow the on-screen instructions to create a local user account instead of a Microsoft account. You will still have access to all features, and this method helps to avoid unnecessary Microsoft account integration.

---

## Step 5: Finalizing Setup

1. **Customization**  
   Once you’ve set up your account (local or Microsoft), follow the prompts to complete the setup. You’ll be asked to choose privacy settings, connect to Wi-Fi, and configure Cortana (if applicable).

2. **Install Windows Updates**  
   Once the setup is complete, go to **Settings** > **Update & Security** > **Windows Update** and check for any available updates. It’s important to install these updates for optimal performance and security.

3. **Install Device Drivers**  
   After Windows is fully set up, it’s a good idea to install any missing drivers (especially graphics, sound, and network drivers). You can download these from the manufacturer's website or use Windows Update to automatically detect and install drivers.

4. **Restore Your Files**  
   If you backed up your files, now is the time to restore them to your new Windows installation.

---

By following these steps, you should have a clean installation of Windows 11 on your computer. If you run into any issues, feel free to ask for further assistance!
