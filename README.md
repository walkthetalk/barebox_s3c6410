barebox_s3c6410
===============

barebox support s3c6410 nand / mmc, both driver and boot support, and display driver, and can auto detect boot source

nand driver: ported from linux kernel

mmc driver: ported from uboot

boot from nand: use s3c2440 nand boot code as reference

boot from mmc: use function provided by IROM (samsung)

display driver: use s3c2440 as refrence

it can autodetect the boot source, nand or mmc, the arch of lowlevel code is based on s3c2440
