O = optional
V = must

# Song
- id V
- english O
- indonesian V
- verse V : []
- chorus O : []
- author O : []
- musicDefinitions V : [
    measure //
    tempo //
    bpm //
    key //
    ks //
    btb //
    sf //
    ...
]
- accompaniment O : C :: [
    = title
    = youtube
    = tags ::: Arr
]

# Window of the World
- title : [
    en,
    kr,
    ..
]
- corps O
- form V : showcase // performance // solo
- origin V
- tags : [
    timbrel //
    brass //
    carol //
    youth //
    vlog //
    sing //
    concert
]
- song O : [ ]
- youtube V