# -LogIt
LogIt("sometimes literal strings") ; WORKS  $sVar1="sometimes variables" LogIt($sVar1) ; WORKS  LogIt($sVar1 &amp; "sometimes both concatenated")  ; ERROR   LogIt("" &amp; $sVar1 &amp; "leading empty string")  ; WORKS BUT UGLY   ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; Func LogIt(Const ByRef $sLogLine) ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;  ConsoleWrite($slogline &amp;@CRLF)  EndFunc
