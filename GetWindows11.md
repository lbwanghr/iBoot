# How to get Windows 11 on your Mac?

It's recommended to get Windows 11 by upgrading from Windows 10.

1. You should install Windows 10 through BootCamp on your Mac.

2. You should download a Windows 11 image, the file extension may be ".iso".

3. Download the script named "[BypassTPM.cmd](BypassTPM.cmd)" in this repository.

4. Run the CMD script with administrator privileges before running Windows 11 image on Windows 10.

# Why you should run the script before installing Windows 11?

If you check upgrade on Windows 10, it may prompt you that you can't upgrade to Windows 11 because you don't have the TPM module.

But don't give up here, you just need to run the script to bypass the TPM check. 

Thanks to the author of this script, it saves our time and gives us hope, you can visit the author's [repository](https://github.com/Games234/AveYo) to learn more.

---

*I've inspected the code in the script and I think it's safe to execute it.*
