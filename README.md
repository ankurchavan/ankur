#define BitsPassed Q100 ; Var for checking passed args
#define Parg Q116 ; Var for P argument
#define Pval 32768 ; Val for checking if P passed
#define CutterOn M1 ; Discrete cutter output
CutterOn->Y:$078802,8,1 ; Machine Output 1
&1 ; Address CS 1
#1->2000X
#2->2000Y
#3->2000Z 

