# jQuery-
#include &lt;ie.au3>  Example()  Func Example()     Local $oIE = _IECreate("www.google.com")     Local $jQuery = _jQuerify($oIE)      MsgBox(0, "Version", "jQuery version: " &amp; $jQuery.fn.jquery)     MsgBox(0, "Example", "click ok to exit." &amp; @CRLF &amp; "Google logo will fade out by jQuery...")      $jQuery('#hplogo').fadeOut(3000) ; jQuery will fade out the google logo EndFunc   ;==>Example   ; #FUNCTION# ==================================================================================================================== ; Name ..........: _jQuerify ; Description ...: ; Syntax ........: _jQuerify(Byref $oIE) ; Parameters ....: $oIE                 - Object variable of an InternetExplorer.Application. ; Return values .: an object variable pointing to the jQuery library ; Author ........: Chimp ; Modified ......: ; Remarks .......: ; Related .......: ; Link ..........: ; Example .......:
