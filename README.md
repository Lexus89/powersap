# PowerSAP 
PowerSAP is a simple powershell re-implementation of popular & effective
techniques of all public tools *such as* Bizploit, Metasploit auxiliary modules, or 
python scripts available on the Internet. This re-implementation does not
contain any new or undisclosed vulnerability.

PowerSAP allows to reach SAP RFC with .Net connector 'NCo'.

## Credit
All credit goes to:

* Onapsis - Mariano, Jordan…
* ERPScan (@_chipik)
* ERPSEC - Joris van De Vis (@jvis)
* Chris John Riley  (@ChrisJohnRiley)
* Agnivesh Sathasivam and Dave Hartley (@nmonkee)
* Martin Gallo (@MartinGalloAr)
* Yvan GENUER (@_1ggy)

### What is this repository for? 

* Quick summary: Powershell SAP assessment tool 

* Version: 1.1

* Dependencies: 

.Net connector "NCo" - https://websmp201.sap-ag.de/public/connectors (x64 versions already included)
Powershell 3.0
.NET framework 4

* Configuration: Copy sapnco.dll & sapnco_utils.dll in NCo_x86/NCo_x64 folders. 

## Examples

* Test your .Net Connector 'NCo':

PS C:\PowerSAP\Standalone> .\Get-NCoVersion.ps1

NCo Version: 3.0.13.0
Patch Level: 525
SAP Release: 720

* How to run testis:

Invoke PS scripts in the Standalone folder.

### Contributions
Feel free to contribute and add features.

### Screenshots
Simple bruteforce attack on SAP RFC

![PowerSAP2](https://airbus-seclab.github.io/powersap/RFC-BF.png)

READ_TABLE RFC function module call through SOAP request

![PowerSAP3](https://airbus-seclab.github.io/powersap/SOAP-read-TABLE.png)

