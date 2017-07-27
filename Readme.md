### A tool that shows verbose volume information on Windows

#### Usage
   ```powershell
   # From PowerShell/cmd execute:
   ./storage-info.exe
   
   ```

### Example output
   ```powershell
PS C:\Users\Administrator> .\storage-info.exe
Provider #: 1 name: Microsoft Virtual Disk Service Dynamic Provider
Pack #: 1
Provider #: 2 name: Microsoft Virtual Disk Service Basic Provider
Pack #: 1
Volume #: 1
                Volume Id: {1F81B02F-78A6-4712-9C33-A7DB298F7A0D}
                Type: SIMPLE
                Status: ONLINE
                Health: HEALTHY
                TransitionState: STABLE
                Size: 372736
                Flags: 81c000
                Recommended file system: UDF
                Win32 name: \\?\GLOBALROOT\Device\CdRom0
Pack #: 2
Volume #: 1
                Volume Id: {40D3FD48-4BC2-4D55-B95B-7E16F16AD194}
                Type: SIMPLE
                Status: ONLINE
                Health: HEALTHY
                TransitionState: STABLE
                Size: 12989759488
                Flags: 906e7
                Recommended file system: NTFS
                Win32 name: \\?\GLOBALROOT\Device\HarddiskVolume1
   ```
#### There are executables statically compiled in the Binaries folder, all tested on Win10 and Win2012R2.
