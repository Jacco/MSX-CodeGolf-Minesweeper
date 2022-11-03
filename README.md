# MSX-CodeGolf-Minesweeper

To see how it works you can [run it on WebMSX](https://webmsx.org/?disk=https://github.com/Jacco/MSX-Minesweeper-Codegolf/blob/master/Minesweeper.dsk?raw=true)

MCCM 72 TODO

1 RND(-TlME) :B~B+5:SCREEN1:PRINT"L:
I "B\5 :FORT~lTOB: X~RND (l) *9+1 :Y~RND (1) *
9+1:T~T+(Z(X,Y)~9) :Z(X,Y)~9:NEXT:FORX ~lT09:FORY~lT09:T~0:FORI~-lT01:FORJ~- 1T01:T~T-(Z(X+I,Y+J)~9) :NEXTJ,I:Z(X,Y
i )~9+(9-T) * (Z(X, Y) <>9) :LOCATE7+X,5+Y:P RINT" H" :NEXTY ,X:X~l: Y~l: TIME~0: 26 2 LOCA TEll,4,0:PRINT"T:"TIME\50:LOCA T E7+X,5+Y,l:A$~INKEY$:A~ASC(A$+"0") :X~ X+(A~29ANDX>1)-(A~28ANDX<9) :Y~Y+(A~30 ANDY>1)-(A~31ANDY<9) :D~Z(X,Y) :E~D<>9: F~A~32:Q~Q-(F(X,Y)~0)*E*F:F(X,Y)~E*F: A$~CHR$«48+D)*E*F-42*(A~66)) :PRINT A$
I :IF«D~9)*F)OR(Q~81-B)THEN3ELSE2 2 13 S(B\5)~TIME\50:LOCATE0,0,0:B$~". <R ET>":A$(l)~"Tijd: " + S T R $ ( S ( B \ 5 ) ) + B $ : A
$ (0) ~"Helaas. "+B$ :PRINTA$ (- (Q~81-B)) : FORY~lT09:FORX~lT09:LOCATE7+X,5+Y:D~Z (X,Y):A$~CHR$(42-(6+D)*(D<>9)):PRINTA $; :Z(X,Y)~0:NEXT:PRINTY":"S(Y) :NEXT:B
~B+5*(Q<>81-B) :INPUTA$:Q~0:GOT01 18
