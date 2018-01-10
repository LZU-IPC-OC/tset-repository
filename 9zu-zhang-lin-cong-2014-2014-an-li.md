  
@font-face{  
font-family:"Times New Roman";  
}  
  
@font-face{  
font-family:"宋体";  
}  
  
@font-face{  
font-family:"Calibri";  
}  
  
p.MsoNormal{  
mso-style-name:正文;  
mso-style-parent:"";  
margin:0pt;  
margin-bottom:.0001pt;  
mso-pagination:none;  
text-align:justify;  
text-justify:inter-ideograph;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
font-size:10.5000pt;  
mso-font-kerning:1.0000pt;  
}  
  
span.msoIns{  
mso-style-type:export-only;  
mso-style-name:"";  
text-decoration:underline;  
text-underline:single;  
color:blue;  
}  
  
span.msoDel{  
mso-style-type:export-only;  
mso-style-name:"";  
text-decoration:line-through;  
color:red;  
}  
@page{mso-page-border-surround-header:no;  
	mso-page-border-surround-footer:no;}@page Section0{  
}  
div.Section0{page:Section0;}

此程序可以求任意三数的最大公约数

图为738、900、918最小公约数为18

图为298、344、680最小公约数为2![](/assets/剪贴板02.jpg)&lt;xml xmlns="http://www.w3.org/1999/xhtml"&gt;

  &lt;variables&gt;

    &lt;variable type="" id="jLxFcGF\[.i+1AA+vJog\["&gt;a&lt;/variable&gt;

    &lt;variable type="" id="^H\#3V\)8g\*R}L{T$Om5$N"&gt;b&lt;/variable&gt;

    &lt;variable type="" id="fVCuK8nqqvW\`lzeizG3~"&gt;c&lt;/variable&gt;

    &lt;variable type="" id="IMt0\`dmcJVk6v9,+l\[,\("&gt;n&lt;/variable&gt;

  &lt;/variables&gt;

  &lt;block type="variables\_set" id="leBZ\_d8Y\)-x@t%?ujM?D" x="-38" y="37"&gt;

    &lt;field name="VAR" id="jLxFcGF\[.i+1AA+vJog\[" variabletype=""&gt;a&lt;/field&gt;

    &lt;value name="VALUE"&gt;

      &lt;block type="text\_prompt\_ext" id=",\]n28o\#\*iN\[KU0vX/EZH"&gt;

        &lt;mutation type="TEXT"&gt;&lt;/mutation&gt;

        &lt;field name="TYPE"&gt;TEXT&lt;/field&gt;

        &lt;value name="TEXT"&gt;

          &lt;shadow type="text" id="Q{fY\*v7u^$J}Fq@s\*O^="&gt;

            &lt;field name="TEXT"&gt;abc&lt;/field&gt;

          &lt;/shadow&gt;

        &lt;/value&gt;

      &lt;/block&gt;

    &lt;/value&gt;

    &lt;next&gt;

      &lt;block type="variables\_set" id="@a43o^JRVGNnN\|dSMCZJ"&gt;

        &lt;field name="VAR" id="^H\#3V\)8g\*R}L{T$Om5$N" variabletype=""&gt;b&lt;/field&gt;

        &lt;value name="VALUE"&gt;

          &lt;block type="text\_prompt\_ext" id="gK;,e\#hdU\)?DHKUIn@@9"&gt;

            &lt;mutation type="TEXT"&gt;&lt;/mutation&gt;

            &lt;field name="TYPE"&gt;TEXT&lt;/field&gt;

            &lt;value name="TEXT"&gt;

              &lt;shadow type="text" id="TFsDtz2Ku/9wPN\*N\|\*5S"&gt;

                &lt;field name="TEXT"&gt;abc&lt;/field&gt;

              &lt;/shadow&gt;

            &lt;/value&gt;

          &lt;/block&gt;

        &lt;/value&gt;

        &lt;next&gt;

          &lt;block type="variables\_set" id=";Q\[IhB~yWc1x\[uoVl2E{"&gt;

            &lt;field name="VAR" id="fVCuK8nqqvW\`lzeizG3~" variabletype=""&gt;c&lt;/field&gt;

            &lt;value name="VALUE"&gt;

              &lt;block type="text\_prompt\_ext" id="W+huc1\#r;Ff0,2GKqh^P"&gt;

                &lt;mutation type="TEXT"&gt;&lt;/mutation&gt;

                &lt;field name="TYPE"&gt;TEXT&lt;/field&gt;

                &lt;value name="TEXT"&gt;

                  &lt;shadow type="text" id="\)IA4LnCLD\#72BR9LUpe%"&gt;

                    &lt;field name="TEXT"&gt;abc&lt;/field&gt;

                  &lt;/shadow&gt;

                &lt;/value&gt;

              &lt;/block&gt;

            &lt;/value&gt;

            &lt;next&gt;

              &lt;block type="variables\_set" id="c/n\|kex\[J\*a9^.3XI\]kj"&gt;

                &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                &lt;value name="VALUE"&gt;

                  &lt;block type="variables\_get" id="F\|Y.+\]A/-Jxr\(oa2RAqL"&gt;

                    &lt;field name="VAR" id="jLxFcGF\[.i+1AA+vJog\[" variabletype=""&gt;a&lt;/field&gt;

                  &lt;/block&gt;

                &lt;/value&gt;

                &lt;next&gt;

                  &lt;block type="controls\_whileUntil" id="FkVrE~Ji5u,;VDX4=$D@"&gt;

                    &lt;field name="MODE"&gt;UNTIL&lt;/field&gt;

                    &lt;value name="BOOL"&gt;

                      &lt;block type="logic\_operation" id="2{2\_I\(U9@.he\*z\`d\)\*YY"&gt;

                        &lt;field name="OP"&gt;AND&lt;/field&gt;

                        &lt;value name="A"&gt;

                          &lt;block type="logic\_compare" id="W@9::3D3\`fs:TjTYgM!s"&gt;

                            &lt;field name="OP"&gt;EQ&lt;/field&gt;

                            &lt;value name="A"&gt;

                              &lt;block type="math\_modulo" id="2BHLvq!}dz^ckcdkUU9x"&gt;

                                &lt;value name="DIVIDEND"&gt;

                                  &lt;shadow type="math\_number" id="-:5\[j\#\]3~jjI\_\(\#:Hs%^"&gt;

                                    &lt;field name="NUM"&gt;64&lt;/field&gt;

                                  &lt;/shadow&gt;

                                  &lt;block type="variables\_get" id="2my^.9iY%x61cLtBB={m"&gt;

                                    &lt;field name="VAR" id="^H\#3V\)8g\*R}L{T$Om5$N" variabletype=""&gt;b&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                                &lt;value name="DIVISOR"&gt;

                                  &lt;shadow type="math\_number" id="XT%ER\_\(S$E={\[xLX\`zh@"&gt;

                                    &lt;field name="NUM"&gt;10&lt;/field&gt;

                                  &lt;/shadow&gt;

                                  &lt;block type="variables\_get" id="KPqr\[\]jE9ud4SYZ\`}p.U"&gt;

                                    &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;value name="B"&gt;

                              &lt;block type="math\_number" id="CXEqGB/vWn6\(S,%ODDS\_"&gt;

                                &lt;field name="NUM"&gt;0&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                        &lt;value name="B"&gt;

                          &lt;block type="logic\_compare" id="=~\#F{s!;~cQX:\|hi63ai"&gt;

                            &lt;field name="OP"&gt;EQ&lt;/field&gt;

                            &lt;value name="A"&gt;

                              &lt;block type="math\_modulo" id="HX\|OGZuS9G\)MEU?b\];Ii"&gt;

                                &lt;value name="DIVIDEND"&gt;

                                  &lt;shadow type="math\_number" id="-:5\[j\#\]3~jjI\_\(\#:Hs%^"&gt;

                                    &lt;field name="NUM"&gt;64&lt;/field&gt;

                                  &lt;/shadow&gt;

                                  &lt;block type="variables\_get" id="LIjJi^YPkRzJXFPkH2LF"&gt;

                                    &lt;field name="VAR" id="fVCuK8nqqvW\`lzeizG3~" variabletype=""&gt;c&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                                &lt;value name="DIVISOR"&gt;

                                  &lt;shadow type="math\_number" id="XT%ER\_\(S$E={\[xLX\`zh@"&gt;

                                    &lt;field name="NUM"&gt;10&lt;/field&gt;

                                  &lt;/shadow&gt;

                                  &lt;block type="variables\_get" id="As{^u7Oq}n{\*xNM6g:P\("&gt;

                                    &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;value name="B"&gt;

                              &lt;block type="math\_number" id="Ae\*;5s\`:;ASN=K\]cik\]I"&gt;

                                &lt;field name="NUM"&gt;0&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                      &lt;/block&gt;

                    &lt;/value&gt;

                    &lt;statement name="DO"&gt;

                      &lt;block type="variables\_set" id="MPZV^CkvuIJb\#sp1%AhU"&gt;

                        &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                        &lt;value name="VALUE"&gt;

                          &lt;block type="math\_arithmetic" id="NeNb;CB%6gW.O.@wOrQg"&gt;

                            &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                            &lt;value name="A"&gt;

                              &lt;shadow type="math\_number" id="$\`r2B3\[Acw^\[KL\(voa+F"&gt;

                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                              &lt;/shadow&gt;

                              &lt;block type="variables\_get" id="2=RaXX=\]e6E~BprS{;7/"&gt;

                                &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;value name="B"&gt;

                              &lt;shadow type="math\_number" id="U\#Q;S{iG}=!vJmNWx\]X$"&gt;

                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                              &lt;/shadow&gt;

                            &lt;/value&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                        &lt;next&gt;

                          &lt;block type="controls\_whileUntil" id=";LXL6+\(j,\(\_B\_1@/^gB2"&gt;

                            &lt;field name="MODE"&gt;UNTIL&lt;/field&gt;

                            &lt;value name="BOOL"&gt;

                              &lt;block type="logic\_compare" id=":jYXL}U\)mZ}Z^$.\*DEZa"&gt;

                                &lt;field name="OP"&gt;EQ&lt;/field&gt;

                                &lt;value name="A"&gt;

                                  &lt;block type="math\_modulo" id="\[Mq69\)qdV6t\[jBS%bLJV"&gt;

                                    &lt;value name="DIVIDEND"&gt;

                                      &lt;shadow type="math\_number" id="-:5\[j\#\]3~jjI\_\(\#:Hs%^"&gt;

                                        &lt;field name="NUM"&gt;64&lt;/field&gt;

                                      &lt;/shadow&gt;

                                      &lt;block type="variables\_get" id="U{7?ZkbF/D/Vql=\_6ePU"&gt;

                                        &lt;field name="VAR" id="jLxFcGF\[.i+1AA+vJog\[" variabletype=""&gt;a&lt;/field&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                    &lt;value name="DIVISOR"&gt;

                                      &lt;shadow type="math\_number" id="XT%ER\_\(S$E={\[xLX\`zh@"&gt;

                                        &lt;field name="NUM"&gt;10&lt;/field&gt;

                                      &lt;/shadow&gt;

                                      &lt;block type="variables\_get" id="{lb,,R=\(fRB6^$$\_9v6h"&gt;

                                        &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                                &lt;value name="B"&gt;

                                  &lt;block type="math\_number" id=";.fh{FR{bQcw\|mZqRrUP"&gt;

                                    &lt;field name="NUM"&gt;0&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;statement name="DO"&gt;

                              &lt;block type="variables\_set" id="rhgJh%?~P\)RNUcr\_qL\*E"&gt;

                                &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                                &lt;value name="VALUE"&gt;

                                  &lt;block type="math\_arithmetic" id="S0yE\[\]\(\]%\(\(p%1E@/BSP"&gt;

                                    &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                                    &lt;value name="A"&gt;

                                      &lt;shadow type="math\_number" id="@nB\(tz0u/!q\)5IF4ifN0"&gt;

                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                      &lt;/shadow&gt;

                                      &lt;block type="variables\_get" id="uSKbNWm6IRh\)m\]boJ{vw"&gt;

                                        &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                    &lt;value name="B"&gt;

                                      &lt;shadow type="math\_number" id="7@KB:!u!\_x~McX\*lC\#0X"&gt;

                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                      &lt;/shadow&gt;

                                    &lt;/value&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/statement&gt;

                          &lt;/block&gt;

                        &lt;/next&gt;

                      &lt;/block&gt;

                    &lt;/statement&gt;

                    &lt;next&gt;

                      &lt;block type="text\_print" id="\[AVDTi$\]T,CL\(BRre=^4"&gt;

                        &lt;value name="TEXT"&gt;

                          &lt;shadow type="text" id="IVUzd6cas2Id\#b5kuaHi"&gt;

                            &lt;field name="TEXT"&gt;abc&lt;/field&gt;

                          &lt;/shadow&gt;

                          &lt;block type="variables\_get" id="lwqpev?wUO7OJ~yD60?}"&gt;

                            &lt;field name="VAR" id="IMt0\`dmcJVk6v9,+l\[,\(" variabletype=""&gt;n&lt;/field&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                      &lt;/block&gt;

                    &lt;/next&gt;

                  &lt;/block&gt;

                &lt;/next&gt;

              &lt;/block&gt;

            &lt;/next&gt;

          &lt;/block&gt;

        &lt;/next&gt;

      &lt;/block&gt;

    &lt;/next&gt;

  &lt;/block&gt;

&lt;/xml&gt;

