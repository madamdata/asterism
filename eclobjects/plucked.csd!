<CsoundSynthesizer>
<CsOptions>
; Select audio/midi flags here according to platform 
-odac     ;;;realtime audio out 
-+rtmidi=null -M0
;-iadc    ;;;uncomment -iadc if realtime audio input is needed too 
; For Non-realtime ouput leave only the line below: 
; -o grain.wav -W ;;; for file output any platform 
</CsOptions>
<CsInstruments>
 

sr = 44100 
ksmps = 32 
nchnls = 2 
0dbfs  = 1 

instr 1 
kcps = p4
kamp = p5
icps = p4
ifn = p9
imeth = p6
ipar1 = p7
ipar2 = p8

asig pluck kamp, kcps, icps, ifn, imeth, ipar1, ipar2
	outs asig, asig

endin 
</CsInstruments>
<CsScore>
f 0 360000; 
f 1 0 8192 10 1
f 2 0 129 5 1 100 0.0001 29
e 
</CsScore>
</CsoundSynthesizer>
