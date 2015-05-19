# pyblish-fusion
Pyblish for Blackmagic Design Fusion


# Research

Some testing / paperwork so far

### Fusion documentation reference

http://www.steakunderwater.com/VFXPedia/96.0.243.189/

### References

http://www.steakunderwater.com/VFXPedia/96.0.243.189/indexb20a.html?title=Eyeon:Script/Reference/Applications/eyeonScript
http://www.steakunderwater.com/VFXPedia/96.0.243.189/indexfdff.html?title=Eyeon:Script/Reference/Applications/eyeonScript/Installing
http://www.steakunderwater.com/VFXPedia/96.0.243.189/index5522.html?title=Eyeon:Script/Reference/Applications/Fusion/Classes/Fusion
http://www.steakunderwater.com/VFXPedia/96.0.243.189/index0ac6.html?title=Eyeon:Script/Tutorials/Command_Line
http://www.steakunderwater.com/VFXPedia/96.0.243.189/index8c76.html?title=Eyeon:Script/Reference/Applications/Fusion/Classes

---

#### Test: Connecting with eyeonScript.exe

*Trying to connect from eyeonScript.exe seems to work with Fusion 6 but does nothing with Fusion 7*

```Lua
fu = eyeon.scriptapp("Fusion", "localhost")
```

is the same as:

```Lua
Fusion("localhost")
```