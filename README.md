# VFP (Visual FoxPro) for Notepad++
## User Defined Language (userDefineLang.xml)
Description: text syntax highlighting.
* Import the userDefineLang.xml as UDF into notepad++ under Language -> Define your language...

## FunctionList (functionList.xml)
Description: display the classes and functions/procedures in Function List panel.

* first you must import the user defined language
* to use the Function List panel with VFP you must expend the functionList.xml in your notepad++ directory on your userprofile.<br>Path: c:\users\username\appdata\roaming\notepad++\functionList.xml
 
## Sample

```foxpro
Define Class kaVfpRocksCst as Custom

	procedure DoSomeProc
		*!* BlaBla
	endproc

	Function fnDoSomething() as Long

	endfunc

ENDDEFINE

Define Class kaVfpRocksFrm as Form

	procedure init
		*!* BlaBla
	endproc

	Function fnSayHello()
		=Messagebox("Hello")
	endfunc

ENDDEFINE
```

![function list panel](sample.png)