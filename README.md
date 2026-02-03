# MotionMatics Manifest for Compulab IMX8M Plus Yocto SDK
This manifest pulls meta-motionmatics into yocto build for compulab MCM IMX8M Plus SOM SDK.

**Steps to pull meta-motionmatics**
1. Repo init NXP & Compualab layers - Follow instructions given in README of https://github.com/compulab-yokneam/meta-bsp-imx8mp
2. wget -P .repo/local_manifests https://raw.githubusercontent.com/MotionMatics/motionmatics-manifest/master/meta-mm-bsp.xml
3. repo sync -j NUMBER_OF_CORES
