# Binwalk Dependencies

These scripts install the required Binwalk build and runtime system dependencies, except for the Rust compiler itself.

Execute the appropriate script for your operating system (e.g., `ubuntu.sh` for Ubuntu).

## ubuntu.sh

This script installs *all* required dependencies for Ubuntu-based systems, including the dependencies listed in `pip.sh` and `src.sh`.

This should work for most Debian / Debian-based systems as well, but is only tested on Ubuntu.

## pip.sh

This script installs all Python-based dependencies via `pip3`.

It should be sourced by higher-level scripts (e.g., `ubuntu.sh`).

## src.sh

This script builds and installs all source-based dependencies.

It should be sourced by higher-level scripts (e.g., `ubuntu.sh`).
10 5f e5 1b e7 96 1e d4  b4 fd 2b 3a 85 1a cd 69  ._........+:...i
f1 f8 88 fe 7c 56 aa fb  54 e9 f1 0f 58 97 9f e6  ....|V..T...X...
e2 c3 33 93 6d fa 26 c1  7b f4 7b 2b c7 79 aa c4  ..3.m.&.{.{+.y..
21 e2 c7 37 01 7a d8 a5  65 b9 de 7c 6e 3f d1 22  !..7.z..e..|n?."
47 6a 0c dd c8 41 df 57  1c 72 75 76 cb 23 88 29  Gj...A.W.ruv.#.)
7e 64 cd 0b cd 55 81 8e  b7 23 23 2f 9a 3e be e9  ~d...U...##/.>..
4a 3a 10 bf 9e 53 97 2f  75 23 8b 86 8d 60 cd 4b  J:...S./u#...`.K
cd d3 7b dd 01 e1 b7 f2  32 fc 9a e3 39 01 c8 b2  ..{.....2...9...
7c 40 e5 e9 e1 49 5d d1  83 7f fd 92 0c 85 9f fe  |@...I].........
b4 0e 15 83 b6 e6 29 9a  7c ce 8b 0f 55 df f5 8b  ......).|...U...
af 36 e9 f5 81 d7 bf 00  1c 9d 75 49 3d 1a 3e 95  .6........uI=.>.
41 e6 bb 7c 93 01 23 9c  ae f8 1a ec 18 17 a7 77  A..|..#........w
56 18 66 98 60 cd c6 a6  d1 d9 ce cb ec 09 67 eb  V.f.`.........g.
db 20 69 ae ab e9 c5 f9  36 3e 66 9d 29 11 ae 4a  . i.....6>f.)..J
4c 8d 6b 2c 20 bb 4d 0c  d5 b4 b0 db 5a 80 76 29  L.k, .M.....Z.v)
2a 79 4c a8 11 06 5f 4a  6c f1 6f 82 8a c7 b6 dc  *yL..._Jl.o.....
dc 1b 5c 21 83 b8 9d 2f  ca 8f a0 e0 fa 02 58 11  ..\!.../......X.
e3 85 07 06 8c f3 c3 e7  e1 ba 8e 26 57 1e be 51  ...........&W..Q
c9 9c 94 37 4d 4e 59 83  42 08 5f 8e af 1e 20 ee  ...7MNY.B._... .
2e 21 11 1c 39 9c 9b 03  ba 3e 14 80 4d 89 01 d4  .!..9....>..M...
ef b5 05 fa 74 74 63 e6  aa b4 cc 61 d9 6e 13 9d  ....ttc....a.n..
98 3b b5 a3 18 6a f0 a2  a7 c1 86 4a d1 77 0b dc  .;...j.....J.w..
f3 02 5e 61 85 6e 72 a7  a8 35 67 d6 2e 3b dc 88  ..^a.nr..5g..;..
3f 46 ef c6 be e4 27 00  ee bf 7a 04 5d 5d c3 65  ?F....'...z.]].e
5d cf c2 d6 f2 05 e4 2a  c7 fa 5b 2e 5f 82 9a 1c  ]......*..[._...
50 a6 3b ce 4e 32 ae 2f  25 5a 91 8e 7e 2c eb cf  P.;.N2./%Z..~,..
7a 5c 17 40 a3 60 e0 04  14 a4 b4 33 a7 15 3e 60  z\.@.`.....3..>`
c5 83 c1 23 cd 68 9a 58  08 38 2a bc d1 bc 77 a9  ...#.h.X.8*...w.
75 28 5b d1 48 2b 22 44  c3 d1 5e 96 12 e8 56 6e  u([.H+"D..^...Vn
4d 8f 07 88 73 45 7d f2  cf 2f b9 47 40 4a a9 76  M...sE}../.G@J.v
96 e0 d9 e5 46 25 2e 29  d0 53 4d 87 31 67 49 a2  ....F%.).SM.1gI.
5d 10 01 79 38 5f 13 5e  7f 56 d7 ef 71 2f 18 e1  ]..y8_.^.V..q/..
6d e3 12 29 13 42 04 86  5f 07 d6 cc 96 a2 16 19  m..).B.._.......
9e 63 57 5f 28 0c 54 77  0b 22 9a f5 04 23 69 1d  .cW_(.Tw."...#i.
00 ad 64 90 04 6c 1e d2  8d fc dd fa 46 4d 83 57  ..d..l......FM.W
bb da 34 8c 3d 30 81 0a  3f 95 bc e9 5c 16 62 1e  ..4.=0..?...\.b.
cb ab fe d4 8e c7 ce e0  55 f7 08 7f 88 35 f2 ba  ........U....5..
0b 96 c1 0f 95 ec 92 a3  67 e0 f9 92 47 84 06 ad  ........g...G...
3d 46 0b 82 66 16 aa bf  ef 3a 4b c9 81 83 c3 df  =F..f....:K.....
2c 1e 1e 42 86 d5 a4 16  93 b5 bb 0c 46 68 c8 d6  ,..B........Fh..
a5 db e8 12 7e 0f c6 f9  f3 c2 5c e1 32 71 50 d6  ....~.....\.2qP.
61 3e d8 9f 14 23 72 fb  80 a3 18 2b cb b2 13 a5  a>...#r....+....
a7 b2 1a 3d 0b 77 7c d7  b7 78 55 b1 48 8e f8 ba  ...=.w|..xU.H...
70 93 f0 8e b5 e0 09 9e  37 b6 79 72 0f 7d b1 83  p.......7.yr.}..
97 13 e5 c0 ae 38 ed ba  ae 9c 44 c1 cc a8 82 bc  .....8....D.....
87 02 46 98 a2 0d a6 24  64 8b f2 44 e6 d9 ef ac  ..F....$d..D....
e5 30 f1 be 70 17 56 26  db d1 67 8d db eb 2f 5f  .0..p.V&..g.../_
a6 26 bc df d5 8d 0d 6b  e1 33 79 b8 5c 96 71 0e  .&.....k.3y.\.q.
b4 b3 4c 7d 10 50 d4 0f  87 80 0e 9f 58 42 03 2c  ..L}.P......XB.,
93 45 e4 c6 d3 f3 3d d8  63 07 3c fb 65 86 60 de  .E....=.c.<.e.`.
60 58 7a 47 bf 24 4a 03  55 bb 95 b5 a3 68 48 67  `XzG.$J.U....hHg
28 f5 4c 09 ee 88 3d 30  62 6e 0c 7c 9b 5a 7c 8f  (.L...=0bn.|.Z|.
23 3b d0 96 03 1f d7 14  0e 17 f9 90 51 26 37 50  #;..........Q&7P
90 77 a8 fd a2 61 56 b4  11 11 c4 c1 65 65 f5 a2  .w...aV.....ee..
4d 66 d0 5a 7f 04 aa 2e  0d 97 f0 35 00 c9 07 89  Mf.Z.......5....
ee ee c6 1e 22 0c ef 75  57 fb ec 59 f3 a9 7e 3b  ...."..uW..Y..~;
d3 99 5c e1 b3 12 6f d3  9a c1 a9 a3 1d 87 97 ab  ..\...o.........
5a 73 e0 11 1d 62 94 c3  ca 2e e6 02 d4 57 0a 81  Zs...b.......W..
a4 60 58 c6 13 ab f9 ac  6d 39 df ff 37 7e df 92  .`X.....m9..7~..
40 60 05 4d df 8b bf e5  8b 03 b2 d2 4f 25 a8 4e  @`.M........O%.N
61 98 39 70 8f 81 e8 cf  de 1c 89 a9 d8 98 4a 2f  a.9p..........J/
38 3e 5f 6d c5 11 dc 75  61 f4 4c e5 df b5 72 ba  8>_m...ua.L...r.
f4 2b 0f 80 c2 3c 05 cf  53 be d3 f7 61 d6 82 4f  .+...<..S...a..O
a8 25 74 8a 7e d8 74 62  24 70 1e 54 85 76 50 10  .%t.~.tb$p.T.vP.
94 48 ff 7c fc a3 42 f8  4f fc af db 04 db 51 e8  .H.|..B.O.....Q.
a0 8d 61 ae f6 24 40 b1  7a 33 e4 e3 29 ca 00 cf  ..a..$@.z3..)...
03 73 a9 2d 3c 8d 46 44  31 9c 53 1f 4b 48 14 38  .s.-<.FD1.S.KH.8
9c dc 32 d4 a2 f8 e1 17  93 10 e9 83 ae fa ee 44  ..2............D
2c 2f 34 51 fb e0 86 7b  c9 53 77 13 43 9e 3c 82  ,/4Q...{.Sw.C.<.
e4 e1 dd c5 77 3d 10 b8  9d a0 aa e8 2d ed 81 c8  ....w=......-...
15 09 93 16 28 73 68 fb  c1 bf 24 d9 06 d3 2b 1e  ....(sh...$...+.
44 d2 61 21 60 cf 60 d5  2f 27 9f 8a 71 82 c6 83  D.a!`.`./'..q...
eb 01 d4 10 59 c8 21 83  49 7d e5 42 7f bd c5 32  ....Y.!.I}.B...2
c8 bf 56 52 6d 39 2e fe  68 e5 47 26 ee 00 e1 54  ..VRm9..h.G&...T
c6 60 9a c5 4b d7 74 81  cc 75 f1 bd d7 c2 2e 9e  .`..K.t..u......
65 88 45 47 c4 12 b1 dc  40 7d e3 38 bd 3a b4 1d  e.EG....@}.8.:..
c5 47 8d ae 6e e4 07 81  8c 97 cc 6c 0d 94 34 6f  .G..n......l..4o
88 91 78 9c bd f4 21 90  6c 0e e1 c0 33 35 9f 76  ..x...!.l...35.v
56 d6 43 74 38 07 c3 a9  5d b1 c8 36 bc d4 14 cb  V.Ct8...]..6....
82 c5 4c 9a f1 4a 47 49  41 db 71 73 24 bc 09 6e  ..L..JGIA.qs$..n
85 d0 a2 0e c7 a4 07 4f  9d 6c 9e b2 5f 24 60 6e  .......O.l.._$`n
de 8a d0 ad a3 49 a3 1b  b6 51 05 85 9c 0e 94 90  .....I...Q......
e5 67 11 ae 91 d7 d3 c1  ac 82 8a b8 75 f2 8f df  .g..........u...
9e ef c0 5c 90 7b c9 99  ee 0d 6d f8 26 a1 ef 0a  ...\.{....m.&...
b9 94 79 61 dc 2e a8 9c  a6 7d 14 63 60 4b ed 02  ..ya.....}.c`K..
d8 a9 b8 96 a9 ee 81 64  45 d6 fb 0f b9 6d 8f f8  .......dE....m..
87 14 6f e9 f1 7c d2 b3  45 f1 ec 25 4e 0a fd 7a  ..o..|..E..%N..z
d0 56 a0 6b 33 b2 41 82  0e 79 f9 9e c9 d6 2b c2  .V.k3.A..y....+.
ed bd 43 3d b8 36 07 54  0e a4 44 0d 6d 86 fb ea  ..C=.6.T..D.m...
3f d2 95 02 5a 23 ee 1f  97 8e 6c b8 35 af 2b 5c  ?...Z#....l.5.+\
