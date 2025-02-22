 ****** Share DLL  ITaskbarList3::SetOverlayIcon ******
_Dll Custom for using on Powerbuilder 12.6 32-bit
_Connect to ITaskbarList3::SetOverlayIcon through Window Api
_Connect my email quangvinhlai123@gmail.com to get src C++

****** Local External Function ******
Function Long SetTaskbarOverlayIconV4(Long hWnd, int number) LIBRARy "TestSetOverlayIconV4.dll" Alias For "SetTaskbarOverlayIcon"

****** Event ******
ulong hWnd
int number 

number = 1
hWnd = Handle(parent)
//number <> 0 : Turn On | number = 0 : Turn Off
SetTaskbarOverlayIconV4(hWnd, number)
