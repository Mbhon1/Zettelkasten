
> Note: Make sure the software installers are downloaded before running the script
# PowerShell

$softwarePath = “C:\Software”

### Install Google Chrome

Start-Process “$softwarePath\ChromeStandaloneSetup.exe” -ArgumentList “/silent /install” -Wait 

### Install Microsoft Office

Start-Process “$softwarePath\OfficeSetup.exe” -ArgumentList “/configure configuration.xml” -Wait 

### Install Adobe Acrobat Reader DC

Start-Process “$softwarePath\AcroReadDC.exe” -ArgumentList “/sAll /rs” -Wait

## Reference

[Install Script](https://anakage.com/blog/how-to-automate-software-installation-with-a-script-a-step-by-step-guide/)
[Install Script 2](https://www.techwalla.com/articles/how-to-write-a-simple-script-to-install-a-program)
