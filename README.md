# AHKFunctionKeysSolution
A simple code allowing someone using a keyboard without the FN keys to use AHK in order to fix it.

;simple code allowing the usage of ahk and binds to fix keyboards without the FN keys (like the one I use at work)
;made by lucas holanda.
;by AHK standards: the key that emulates FN in this code is CTRL, but feel free to change it.

;here the end key plays and pauses media.
^End::
Send {Media_Play_Pause}
return
;here the up key increases the volume (2% each press).
^Up::
Send {Volume_Up}
return
;the down key decreases the volume (2% each press).
^Down::
Send {Volume_Down}
return
;right key play the next song.
^Right::
Send {Media_Next}
return
;left key repeats or reverses it to other song.
^Left::
Send {Media_Prev}
return




