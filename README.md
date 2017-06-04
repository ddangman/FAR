## Fix (NieR) Automata Resolution - Pirate-Friendly Version

A patched version of the FAR; with auto-updates proxied, you can update without worry with builds from this git.

### FAQ
- Why no sources?

```
I don't rebuild the FAR, i have patched with the x64dbg/ida pro, so... i don't have the patched source.
```

- No plans to start publish rebuild dll's?
```
Maybe, but for now, not necessary.
```

- The game close with Snake Sound (lol)
```
This isn´t a crash caused by the detection of the crack in the nier, Otherwise, this would have occurred to me.

Okay, and how to fix it?
- Download again the crack to have sure you have the lastest version of the baldman crack.
- if you think this alert sound it´s because the detected crack, isn´t this, you can try a outated version from the FAR.
- MSI Nahimic and Razer (Insert Any Product Name Here) are known to interfere with Special K (dxgi.dll), you may need to disable that software to use the mod
- Nothing Works?! Try the lastest version from the crack, my tests use the v3 baldman version.
- Nothing Again? You have any program that try hook/inject into the game? like the discord overlay? try disable anything like this.
- try set at [Steam.Log] the Silent=true
- Nothing... So... I can lend my shoulders to you cry if you need.

```

- I Don´t trust in you, but i need the mod.
```
No problem, You can manually patch. Using the x64dbg or IDA PRO, search by the function SK_Steam_PiratesAhoy
Print: https://u.nya.is/okncrm.png (if you don´t found, try run the debugger and pause before close)
Right Click -> Follow in the disassembler: https://u.nya.is/rmilgm.png
The Patched version, looks like this: https://u.nya.is/oedypx.png
to patch is simple, press space and in the window, Check "Fill With Nop´s" and Write:
MOV EAX, 0 (https://u.nya.is/wetkvn.png) (0 = Allways Original, 1 = Allways Pirate)
Press Enter or OK, and write:
Ret (https://u.nya.is/qmhpfj.png)
Press Enter again and Cancel now.
Click in "View" => Patch File (https://u.nya.is/staaek.png)
Click in Patch File, and save it.
(you can play now, but have more one optional step)
Open the patched Dll with a Hex editor, i have 010Editor.
Find the unicode string, "/master/" and corrupt this part to prevent the FAR Auto-Update. (https://u.nya.is/beplaa.png)
Save and Put into the nier directory, now just use!
```
