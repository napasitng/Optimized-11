# Optimized 11

The custom Windows 11 ISO using an automated installation configuration using an `Autounattend.xml` file.

---

## Features
- Automated installation of Windows 11.
- Pre-configured settings, including language, time zone, disk partitioning, and user account creation.
- Customizations as defined by the `Autounattend.xml` file.

---

## Methods
#### Method 1
- Download official Windows 11 ISO from [this link](https://www.microsoft.com/windows/windows-11).
#### Method 2
- Create a Bootable USB
- You can use tool like [Windows 11 Installation Media
](https://go.microsoft.com/fwlink/?linkid=2156295), [Rufus](https://rufus.ie/), [Etcher Balena](https://etcher.balena.io/), etc.
#### Method 3
- Download Autounattend.xml from [this link](https://schneegans.de/windows/unattend-generator/?LanguageMode=Interactive&ProcessorArchitecture=amd64&BypassRequirementsCheck=true&BypassNetworkCheck=true&UseConfigurationSet=true&ComputerNameMode=Random&CompactOsMode=Default&TimeZoneMode=Implicit&PartitionMode=Interactive&WindowsEditionMode=Unattended&WindowsEdition=pro&UserAccountMode=InteractiveLocal&PasswordExpirationMode=Unlimited&LockoutMode=Default&HideFiles=HiddenSystem&TaskbarSearch=Box&ShowFileExtensions=true&DisableWidgets=true&DisableBingResults=true&DisableSac=true&DisableSmartScreen=true&EnableLongPaths=true&AllowPowerShellScripts=true&DisableAppSuggestions=true&PreventDeviceEncryption=true&HideEdgeFre=true&MakeEdgeUninstallable=true&DisablePointerPrecision=true&WifiMode=Interactive&ExpressSettings=DisableAll&KeysMode=Skip&ColorMode=Default&WallpaperMode=Default&Remove3DViewer=true&RemoveBingSearch=true&RemoveCalculator=true&RemoveCamera=true&RemoveClipchamp=true&RemoveClock=true&RemoveCopilot=true&RemoveCortana=true&RemoveDevHome=true&RemoveFamily=true&RemoveFeedbackHub=true&RemoveGetHelp=true&RemoveHandwriting=true&RemoveInternetExplorer=true&RemoveMailCalendar=true&RemoveMaps=true&RemoveMathInputPanel=true&RemoveMixedReality=true&RemoveZuneVideo=true&RemoveNews=true&RemoveNotepadClassic=true&RemoveOffice365=true&RemoveOneDrive=true&RemoveOneNote=true&RemoveOneSync=true&RemoveOpenSSHClient=true&RemoveOutlook=true&RemovePaint=true&RemovePaint3D=true&RemovePeople=true&RemovePhotos=true&RemovePowerAutomate=true&RemovePowerShellISE=true&RemoveQuickAssist=true&RemoveRecall=true&RemoveRdpClient=true&RemoveSkype=true&RemoveSolitaire=true&RemoveSpeech=true&RemoveStepsRecorder=true&RemoveStickyNotes=true&RemoveTeams=true&RemoveGetStarted=true&RemoveToDo=true&RemoveVoiceRecorder=true&RemoveWallet=true&RemoveWeather=true&RemoveFaxAndScan=true&RemoveWindowsMediaPlayer=true&RemoveZuneMusic=true&RemoveWordPad=true&RemoveXboxApps=true&RemoveYourPhone=true&StartTilesMode=Empty&StartPinsMode=Empty&FirstLogonScript1=Get-AppxPackage+-AllUsers+*edge*+%7C+Remove-AppxPackage&FirstLogonScriptType1=Ps1&WdacMode=Skip) or [release page](https://github.com/napasitng/Optimized-11/releases/tag/v1.0.0).
- Copy Autounattend.xml file to Bootable USB.
#### Method 4
- Boot from the Windows Installation USB, and install Windows normaly.

---

## Credits
- [Windows Unattend Generator](https://schneegans.de/windows/unattend-generator/)
