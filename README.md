Epic 4G Temporary Samsung Boot from SDCard
==========================================
* busybox copied from CM7.

```
cd initramfs
find . |cpio -R 0:0 -H newc -o --quiet| gzip > ../initramfs.cpio.gz
cd -
```
