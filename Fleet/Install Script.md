
> Note: Make sure the software installers are downloaded before running the script
# PowerShell

$softwarePath = “C:\Software”

### Install Google Chrome

Start-Process “$softwarePath\ChromeStandaloneSetup.exe” -ArgumentList “/silent /install” -Wait 

### Install Microsoft Office

Start-Process “$softwarePath\OfficeSetup.exe” -ArgumentList “/configure configuration.xml” -Wait 

### Install Adobe Acrobat Reader DC

Start-Process “$softwarePath\AcroReadDC.exe” -ArgumentList “/sAll /rs” -Wait