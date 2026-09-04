
Windows SandBox requires >Windows 11. this forces SandBox installation on Windows 11 Home PCs.


while microsoft blocks Windows Sandbox on Windows Home by default, the underlying files (specifically the Containers packages) are still present in the Windows components repository (%SystemRoot%\servicing\Packages\). this script acts as a loophole by telling the Deployment Image Servicing and Management (DISM) tool to manually install those hidden packages and turn the feature on.


nothing glorious, really. it simply enables sandbox packages that are already dormant in your system files

save as bat and run elevated, wait, reboot
