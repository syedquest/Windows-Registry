# Windows-Registry
- Stores configurations of the operating systems and users

## How to access/parse the registry
- Start the "Run" dialog box and enter "regedit"
- Use Registry Explorer/RECmd by Eric Zimmmerman (https://ericzimmerman.github.io/#!index.md)
- RegRipper

## Windows Registry Hives
- HKEY_CLASSES_ROOT (HKCR)
  - contains information about how the operating system should work when certain action is performed
- HKEY_CURRENT_USER (HKCU)
  - records information related to the user account such as user personalization settings, folder settings etc
- HKEY_LOCAL_MACHINE (HKLM)
  - details about hardware for the operating system
- HKEY_USERS (HKU)
  - contains user configuration data. Each user will have it's own security identifier (SID)
- HKEY_CURRENT_CONFIG (HKCC)
  - It is a pointer to a registry key. 

## Registry Locations
- Default, SAM, Seucirity, Software and System --> Located at C:\Windows\System32\config
- NTUSER.DAT --> Located at C:\Users\<username>
- UsrClass.dat --> Located at C:\Users\<username>\AppData\Local\Microsoft\Windows
