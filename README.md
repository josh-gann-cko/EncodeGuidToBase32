# EncodeGuidToBase32

Encode GUID to Base32 and vice versa. 

How to run: 
```
dotnet run
```

How to see usage information: 
```
dotnet run -help
```

Usage information:
```
  <no arguments> - Generates a single GUID and converts it to Base32.
  <int>    - If an integer is supplied, that many pairs of new GUIDs and Base32 values will be created.
  <GUID>   - If the argument is in GUID format, e.g. 26d8031a-b60a-454e-a2af-110933725893, it is converted to Base32.
  <Base32> - If the argument cannot be parsed as GUID, then it is treated as Base32 format, i.e. it is converted to GUID.
  -help    - Display usage info.
  
  Note:
    Multiple GUIDs or Base32 values can be encoded at once. Just separate each with a space.
```