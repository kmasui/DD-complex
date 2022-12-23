# DD-complex
dd-complex library


混合精度演算やベクトル演算など全ての種類の演算はまだ実装していませんが，普通の四則演算であれば大体対応しています．<br>
CやC++からインクルードして使用してください．

構造体で書いているので，dd_compを宣言して.reと.imで実部と虚部，<br>
さらにそれぞれに対して.hiと.loで上位ビット下位ビットにアクセスできます．<br>
.hiと.loの型は普通のdoubleです．

aa.re.hi = hogehoge; <br>
b[i].im.lo = 0.0;
