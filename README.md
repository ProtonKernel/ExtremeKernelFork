Proton+ based on ExtremeKernel for Exynos 9820 devices
Forked from [ExtremeKernel](https://github.com/Ocin4ever/ExtremeKernel.git) by Ocin4ever. All credits go to the original author.

Build Instructions
1. Set up the build environment
Follow Google's official documentation:
🔗 Android Build Requirements
https://source.android.com/docs/setup/start/requirements

2. Properly clone the repository with submodules
   
git clone --recurse-submodules https://github.com/ProtonKernel/ExtremeKernelFork.git

3. Build for your device

./build.sh -m beyond2lte

4. Fetch the flashable kernel zip
   
build/out/[your_device]/Proton+...zip

5. Flash the kernel
Use a supported custom recovery like TWRP to flash the zip.

Enjoy! 🚀


