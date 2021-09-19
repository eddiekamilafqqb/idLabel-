# idLabel-
#include &lt;GUIConstantsEx.au3> #include &lt;MsgBoxConstants.au3> #include "GuiFlatButton.au3"  Example()  ;GUI with one button Func Example()      Local $hGUI, $mybutton1      $hGUI = GUICreate("GuiFlatButton Ex0", 275, 120)     GUISetBkColor(0x333333)      $idLabel = GUICtrlCreateLabel("Click the button", 10, 100, 150, 30)     GUICtrlSetColor(-1, 0xFFFFFF)
