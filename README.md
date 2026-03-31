# Server_driver_patch
Server BIOS driver patch

## SuperMicro
### [SuperMicro_4028GR-TR2 | Insuper_NF5588M4S](https://www.supermicro.com/en/products/system/4U/4028/SYS-4028GR-TR2.php)
- Add support for booting the system from NVMe, use the AMI Aptio MMTool to insert the NVME BIOS module (NVMeExpressDxE.ffs) in the CSMCore or CSMDxe Insert section of the BIOS file.
