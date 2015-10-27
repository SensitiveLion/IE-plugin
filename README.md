## Regestry
1. Run &Central Lookup.reg
2. Verify regestry key was created in C:\Program Files\Internet Explorer\

#### If that doesnt work

1. Create a new registry key under HKCU\Software\Microsoft\Internet Explorer\MenuExt.
2. Name this new key &Central Lookup
3. Set the default value (on the right side of the regedit window) for this new key to point to a local Web page that will include the script for the context menu item. Use C:\Program Files\Internet Explorer\centrallookup.htm
4. Add a new DWORD value to the context menu item. Name this new value Contexts.
5. Set the value of the Contexts value to 0x10. This enables this context menu for selected text only.

## Central Lookup

Move the included centrallookup.htm file into your C:\Program Files\Internet Explorer\ folder.

## Test

* Now open up Internet explorer and highlight something you want to search for on Central Lookup.
* Right click the highlighted word and select Central Lookup.
* Another window should open up with the search in Central Lookup

