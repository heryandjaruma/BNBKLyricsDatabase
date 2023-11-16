O = optional
V = must

Main Tabs : Beranda, BNBK, Bala, Lainnya

Tab Beranda:
- Today recommendation song
- News : What's happening in BK (Events, TGIF, etc)
- From Nusantara
- Internasional

Tab BNBK:
- Search lagu
- Recent (nanti)
- nyanyian
- koor
- variasi

Tab Bala Ku:
- promosi : upload videomu ke sini
- recommendation
- tamburin, brass band, dance, paduan suara, etc menu
- brass band
- random

Lainnya:
- Profile : nama, email, korps asal
- saved song
- saved video

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
- variasi O : []

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
