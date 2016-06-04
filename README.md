Huawei Angler (Nexus6p) Device Configuration for Broken OS
==========================================================

`./repo/local_manifests/broken_manifest.xml`
```
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="BrokenROM/device_huawei_angler" path="device/huawei/angler" remote="github" revision="m6.0.1" />
  <project name="drgroovestarr/kylo_kernel_angler" path="kernel/huawei/angler" remote="github" revision="m6.0.1" />
  <project name="drgroovestarr/vendor_huawei" path="vendor/huawei" remote="github" revision="m6.0.1" />
  <project name="Cyanogenmod/android_vendor_qcom_opensource_dataservices" path="vendor/qcom/opensource/dataservices" remote="github" revision="cm-13.0" />
  <project name="sultanxda/android_external_sony_boringssl-compat" path="external/sony/boringssl-compat" remote="github" revision="cm-13.0" />
  <project name="BrokenROM/packages_apps_SnapdragonCamera" path="packages/apps/SnapdragonCamera" remote="github" revision="m6.0.1" />
  <project name="drgroovestarr/aarch64-linux-android-5.x-kernel" path="prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-5.x-kernel" remote="bb" revision="master" />
</manifest>
```
