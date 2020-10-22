# N9005_Kali (WIP)
![Kali NetHunter](https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/raw/master/images/nethunter-git-logo.png)
Galaxy Note 3 (N9005), with magic.

This is based on LineageOS 17.1/Android 10. The ROM used for this is here: https://mirrorbits.lineageos.org/full/hlte/20201017/lineage-17.1-20201017-nightly-hlte-signed.zip

This is a work-in-progress project.

# Kernel sources.

Source code for the modified kernel(s) can be found [here](https://github.com/lavanoid/android_kernel_samsung_msm8974.git)

# Compiling.

I've only managed to get this to compile on Manjaro Linux/Arch. Just run the build script and you should soon have a Kali Nethunter installer.

    bash ./build.sh
  
If the script is ran successfully, you should have an installer zip file that will allow you to flash Kali Nethunter onto your device through the recovery menu (TWRP is recommended). To find out where the installer is located, use your eyes and the terminal output should tell you where it is.

 I DO NOT take responsibility for whatever the outcome that may occur when you fiddle around with this and your device.

# My other projects
- Kali Nethunter for the One M9: https://github.com/lavanoid/M9Sense_Kali
- Kali Nethunter for the One M8: https://github.com/lavanoid/M8GPE_Kali
- Kali Nethunter for the One M7: https://github.com/lavanoid/M7GPE_Kali
