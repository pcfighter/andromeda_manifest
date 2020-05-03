# andromeda_manifest
Local manifest file for building LineageOS 17.1 for Xiaomi Mi Mix 3 5G

Steps to build:

### Initialize the LineageOS source repository

Enter the following to initialize the repository:
```
cd ~/android/system/
repo init -u git://github.com/LineageOS/android.git -b lineage-17.1
```
### Get the required local manifest

```
mkdir -p ~/android/system/.repo/local_manifests
curl https://raw.githubusercontent.com/pcfighter/andromeda_manifest/lineage-17.1/local_manifest.xml > .repo/local_manifests/local_manifest.xml
```