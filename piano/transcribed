setCpm(160 / 4)

$drums: stack(
  s("bd")
    .beat("0, 4, 8, 11, 14", 16)
    .bank("RolandTR909")
    .gain(1),

  s("[hh*2 hh hh*2 hh*2]")
    .bank("RolandTR808")
    .gain(1),
)
.orbit(2)
.lpf(5000)
._scope()

$bass: stack(
  s("supersaw!8")
    .note("<c#3 g#2 c#3 [f2 d#2]>")
    .orbit(7),

  s("supersaw!16")
    .note("<c#2 g#1 c#2 [f1 d#1]>")
    .gain(1),
)
.lpf(slider(1693, 100, 2000, 1))
._pianoroll()

$mel: stack(
  note("<[[d#4 c4] [a#4 c4] [d#4 c4] [g4 g#4]]>")
    .s("piano")
    .lpf(2500),
)
.room("<0 .2 .4 .6 .8 1>")
._pianoroll()

$mel2: stack(
  note("<[[d#4 c4] [a#4 c4] [d#4 c4] [g4 f5]*2]*2>")
    .s("saw")
    .lpf(2500),
)
.room("<0 .2 .4 .6 .8 1>")
._pianoroll()
