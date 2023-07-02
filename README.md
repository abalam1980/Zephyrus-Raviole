# Zephyrus-Raviole
Info About the Project
Project-Zephyrus- Minimal Android Fork Focused on Design and Performance!

Fast and Smooth: Project-Zephyrus is more smooth (i.e. less jank) and responds faster than stock.

Clean UI design: We Pay Attention to details in the User Interface.

Privacy: Project-Zephyrus helps keep your Data Private with Camera & Microphone Indicators, Internet & Sensor Permissions.


Install Instructions

-Make sure your Bootloader is unlocked and You are coming from latest stock firmware.

-Connect phone to pc and boot to bootloader.

-Type fastboot -w in cmd prompt/terminal(Not required if you are dirty flashing).

-Download provided rom.zip, boot.img and vendor_boot.img from release

-flash vendor_boot.img (fastboot flash vendor_boot vendor_boot.img)

-flash boot.img (fastboot flash boot boot.img)

-Flash dtbo.img (fastboot flash dtbo dtbo.img)

-Boot to recovery.

-Navigate to Adb sideload option and press sideload.

-Now from pc type adb sideload rom.zip.

-After sideloading is complete, format storage(Not required if you are dirty flashing) and reboot to system.

