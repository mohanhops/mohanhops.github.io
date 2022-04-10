## What is Linux?

Linux is an open sourced OS, written 98% of the code in `C Prgogramming Language` invented by **Linus Torvalds**.
Linux source code is available [here](https://github.com/torvalds/linux)

The structure of the linux code
![Linux][logo]

[logo]: /img/linux/linux_filestrucure.png "Linux File Hierarchy"

Will discuss about key things in Linux from the above image further in our discussion. 

### Why Linux?
There are many reasons for Linux to be extreamly popular, will try to list key factors here:
1. Linux has less security flaws

..1. As Linux is Open Source code, huge number of developers will review the code constantly⋅⋅  
..1. Linux has password authentication, file system discretionary access control, and security auditing, these 3 fundamental security features are essential  

2. Linux is Free OS

..2. Linux has no licence cost to use it unlike other OS like Windows it is free  

3. Performance

..3. Linux doesn't have bloat UI features which makes it light weight  
..3. Linux can run on almost any architecture (`x86`, `ARM`, `RISC-V` .. etc)  
..3. Linux has organized file system hence it is easy to perform file operatins quickly  

4. Task Austomation

..4. Becasue of default shell (`bash`, `zsh`, `sh` .. etc) support in Linux, users can automate most of the regular stuff efficiently on Linux  

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
