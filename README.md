# The-Windows
$sFile = ("C:\WINDOWS\system32\SnippingTool.exe") If FileExists($sFile) Then    Run($sFile) Else    MsgBox(0,'File Error', "The Windows snipping tool was not found") EndIf
