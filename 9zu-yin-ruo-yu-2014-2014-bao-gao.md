&lt;!--  
 /\* Font Definitions \*/  
 @font-face  
    {font-family:"Cambria Math";  
    panose-1:2 4 5 3 5 4 6 3 2 4;  
    mso-font-charset:0;  
    mso-generic-font-family:roman;  
    mso-font-pitch:variable;  
    mso-font-signature:3 0 0 0 1 0;}  
@font-face  
    {font-family:等线;  
    panose-1:2 1 6 0 3 1 1 1 1 1;  
    mso-font-alt:DengXian;  
    mso-font-charset:134;  
    mso-generic-font-family:auto;  
    mso-font-pitch:variable;  
    mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
    {font-family:"等线 Light";  
    panose-1:2 1 6 0 3 1 1 1 1 1;  
    mso-font-charset:134;  
    mso-generic-font-family:auto;  
    mso-font-pitch:variable;  
    mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
    {font-family:"\@等线 Light";  
    mso-font-charset:134;  
    mso-generic-font-family:auto;  
    mso-font-pitch:variable;  
    mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
    {font-family:"\@等线";  
    panose-1:2 1 6 0 3 1 1 1 1 1;  
    mso-font-charset:134;  
    mso-generic-font-family:auto;  
    mso-font-pitch:variable;  
    mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
 /\* Style Definitions \*/  
 p.MsoNormal, li.MsoNormal, div.MsoNormal  
    {mso-style-unhide:no;  
    mso-style-qformat:yes;  
    mso-style-parent:"";  
    margin:0cm;  
    margin-bottom:.0001pt;  
    text-align:justify;  
    text-justify:inter-ideograph;  
    mso-pagination:none;  
    font-size:10.5pt;  
    mso-bidi-font-size:11.0pt;  
    font-family:等线;  
    mso-ascii-font-family:等线;  
    mso-ascii-theme-font:minor-latin;  
    mso-fareast-font-family:等线;  
    mso-fareast-theme-font:minor-fareast;  
    mso-hansi-font-family:等线;  
    mso-hansi-theme-font:minor-latin;  
    mso-bidi-font-family:"Times New Roman";  
    mso-bidi-theme-font:minor-bidi;  
    mso-font-kerning:1.0pt;}  
p.MsoTitle, li.MsoTitle, div.MsoTitle  
    {mso-style-priority:10;  
    mso-style-unhide:no;  
    mso-style-qformat:yes;  
    mso-style-link:"标题 字符";  
    mso-style-next:正文;  
    margin-top:12.0pt;  
    margin-right:0cm;  
    margin-bottom:3.0pt;  
    margin-left:0cm;  
    text-align:center;  
    mso-pagination:none;  
    mso-outline-level:1;  
    font-size:16.0pt;  
    font-family:"等线 Light";  
    mso-ascii-font-family:"等线 Light";  
    mso-ascii-theme-font:major-latin;  
    mso-fareast-font-family:"等线 Light";  
    mso-fareast-theme-font:major-fareast;  
    mso-hansi-font-family:"等线 Light";  
    mso-hansi-theme-font:major-latin;  
    mso-bidi-font-family:"Times New Roman";  
    mso-bidi-theme-font:major-bidi;  
    mso-font-kerning:1.0pt;  
    font-weight:bold;}  
span.a  
    {mso-style-name:"标题 字符";  
    mso-style-priority:10;  
    mso-style-unhide:no;  
    mso-style-locked:yes;  
    mso-style-link:标题;  
    mso-ansi-font-size:16.0pt;  
    mso-bidi-font-size:16.0pt;  
    font-family:"等线 Light";  
    mso-ascii-font-family:"等线 Light";  
    mso-ascii-theme-font:major-latin;  
    mso-fareast-font-family:"等线 Light";  
    mso-fareast-theme-font:major-fareast;  
    mso-hansi-font-family:"等线 Light";  
    mso-hansi-theme-font:major-latin;  
    mso-bidi-font-family:"Times New Roman";  
    mso-bidi-theme-font:major-bidi;  
    font-weight:bold;}  
.MsoChpDefault  
    {mso-style-type:export-only;  
    mso-default-props:yes;  
    font-family:等线;  
    mso-bidi-font-family:"Times New Roman";  
    mso-bidi-theme-font:minor-bidi;}  
 /\* Page Definitions \*/  
 @page  
    {mso-page-border-surround-header:no;  
    mso-page-border-surround-footer:no;}  
@page WordSection1  
    {size:595.3pt 841.9pt;  
    margin:72.0pt 90.0pt 72.0pt 90.0pt;  
    mso-header-margin:42.55pt;  
    mso-footer-margin:49.6pt;  
    mso-paper-source:0;  
    layout-grid:15.6pt;}  
div.WordSection1  
    {page:WordSection1;}  
--&gt;

对blockly的认识——by9组尹若宇320170936941

在大一的上半学期，我选择了关于机器人的一门选修课程。本人也是物理科学与技术学院的一员。由于我们学院的招生政策，这使得我可以在大二在对自己以后想从事的专业再一次地进行选择，而我以后的志愿去从事微电子行业。这样，这个关于机器人的编程与连线的课程深深的吸引了我。而在这我将分享我的关于这门课程的自己的理解和自己的一个实例。

刚开始我是十分的不理解这门课程为什么要开展blockly编程的教育。因为这看起来是给小孩子玩的东西。但是随着课程的推进，这个看似简单但是内涵的复杂程度使我又对其刮目相看。突然发现对于我自己这给小小的东西又显得那么困难。每一个执行，完成，都显得那么新鲜，但是都是进过无数的思考而完成的思想结晶。

最体现无遗的就是课程的最后的组队拼装机器人，来编程完成小车行走迷宫。刚开始的拼接都充满着无数的麻烦，我在小组中的工作是有关小车的线路拼接和测试时的跟随与调整。刚开始那传感器的接口顺序就把我们整的头晕乱转，在我以后的微电子专业中比这难上加难的线路估计多只又多，但是在现在我显得是那么苍白与无力。课程的时间限制有将近6个小时，但是和对我们线路拼接的时间是所有组中耗时最长的。中间期间我们的零件也出现了些小的问题，这对我们更是雪上加霜，但是我们凭借着顽强的毅力和虚心请教的老师的帮助下最终完成了小车的组装。

正所谓卧薪尝胆，在小车拼接的环节表现不济后，我们发誓要后发居上，我们希望做出编程简洁而又能通过迷宫的完美程序。在其他组的失败中我们吸取了教训，总结了经验。在不断的调试数据，无数次尝试之后，我们几近完美的小车完成了第一个迷宫的任务，成为了第一个完成第一个迷宫的组。虽然我们在第二个迷宫中折戟沉沙，没有成为唯一的完成者非常可惜，但是我们完成了自己的工作，这是我们高兴的地方。

而对于我们个人的认识，我发现做成一件事有时候还是非常困难的，你会遇到各种各样的情况，有时候是积极的，但大多数时候是负面的，这时候就要我们调整好自己的情绪，不能被一些琐碎的小事而丢失了自己的方向，就正如我们组装的小车一样，有时会因为传感器的不灵敏而至于东倒西歪，这是我们没有调整好自己的缘故。对于blockly，困难时有时让你无从下手，而灵光一闪成功的大门就向你敞开了，这时候就要发扬自己的艰苦奋斗的精神，永不服输就是成功了。

在这个课程中我收获了友情和知识，同时为自己以后的专业有了一个小小的基础，可谓是收获很丰富吧，如果以后会开展类似的课程，我会继续参加的，也希望我们小组的成员能是和我一样的想法吧。

###### ![](/assets/1.png)&lt;!--  /\* Font Definitions \*/  @font-face     {font-family:"Cambria Math";     panose-1:2 4 5 3 5 4 6 3 2 4;     mso-font-charset:0;     mso-generic-font-family:roman;     mso-font-pitch:variable;     mso-font-signature:3 0 0 0 1 0;} @font-face     {font-family:等线;     panose-1:2 1 6 0 3 1 1 1 1 1;     mso-font-alt:DengXian;     mso-font-charset:134;     mso-generic-font-family:auto;     mso-font-pitch:variable;     mso-font-signature:-1610612033 953122042 22 0 262159 0;} @font-face     {font-family:"Microsoft JhengHei";     panose-1:2 11 6 4 3 5 4 4 2 4;     mso-font-charset:136;     mso-generic-font-family:swiss;     mso-font-pitch:variable;     mso-font-signature:679 684672000 22 0 1048585 0;} @font-face     {font-family:"\@等线";     panose-1:2 1 6 0 3 1 1 1 1 1;     mso-font-charset:134;     mso-generic-font-family:auto;     mso-font-pitch:variable;     mso-font-signature:-1610612033 953122042 22 0 262159 0;} @font-face     {font-family:"\@Microsoft JhengHei";     mso-font-charset:136;     mso-generic-font-family:swiss;     mso-font-pitch:variable;     mso-font-signature:679 684672000 22 0 1048585 0;}  /\* Style Definitions \*/  p.MsoNormal, li.MsoNormal, div.MsoNormal     {mso-style-unhide:no;     mso-style-qformat:yes;     mso-style-parent:"";     margin:0cm;     margin-bottom:.0001pt;     text-align:justify;     text-justify:inter-ideograph;     mso-pagination:none;     font-size:10.5pt;     mso-bidi-font-size:11.0pt;     font-family:等线;     mso-ascii-font-family:等线;     mso-ascii-theme-font:minor-latin;     mso-fareast-font-family:等线;     mso-fareast-theme-font:minor-fareast;     mso-hansi-font-family:等线;     mso-hansi-theme-font:minor-latin;     mso-bidi-font-family:"Times New Roman";     mso-bidi-theme-font:minor-bidi;     mso-font-kerning:1.0pt;} p.MsoHeader, li.MsoHeader, div.MsoHeader     {mso-style-priority:99;     mso-style-link:"页眉 字符";     margin:0cm;     margin-bottom:.0001pt;     text-align:center;     mso-pagination:none;     tab-stops:center 207.65pt right 415.3pt;     layout-grid-mode:char;     border:none;     mso-border-bottom-alt:solid windowtext .75pt;     padding:0cm;     mso-padding-alt:0cm 0cm 1.0pt 0cm;     font-size:9.0pt;     font-family:等线;     mso-ascii-font-family:等线;     mso-ascii-theme-font:minor-latin;     mso-fareast-font-family:等线;     mso-fareast-theme-font:minor-fareast;     mso-hansi-font-family:等线;     mso-hansi-theme-font:minor-latin;     mso-bidi-font-family:"Times New Roman";     mso-bidi-theme-font:minor-bidi;     mso-font-kerning:1.0pt;} span.a     {mso-style-name:"页眉 字符";     mso-style-priority:99;     mso-style-unhide:no;     mso-style-locked:yes;     mso-style-link:页眉;     mso-ansi-font-size:9.0pt;     mso-bidi-font-size:9.0pt;} .MsoChpDefault     {mso-style-type:export-only;     mso-default-props:yes;     font-family:等线;     mso-bidi-font-family:"Times New Roman";     mso-bidi-theme-font:minor-bidi;}  /\* Page Definitions \*/  @page     {mso-page-border-surround-header:no;     mso-page-border-surround-footer:no;} @page WordSection1     {size:595.3pt 841.9pt;     margin:72.0pt 90.0pt 72.0pt 90.0pt;     mso-header-margin:42.55pt;     mso-footer-margin:49.6pt;     mso-paper-source:0;     layout-grid:15.6pt;} div.WordSection1     {page:WordSection1;} --&gt;

XML：&lt;xml xmlns="[http://www.w3.org/1999/xhtml"&gt](http://www.w3.org/1999/xhtml"&gt);

&lt;variables&gt;

&lt;variable type="" id="y+\]\|\*,U4W?U\#nQwJre\|T"&gt;x&lt;/variable&gt;

&lt;variable type="" id=":?\|mRgh\){D^iIAirs2oU"&gt;i&lt;/variable&gt;

&lt;/variables&gt;

&lt;block type="variables\_set" id="bVrtb2z7,BA52Y$zrg4B" x="262" y="112"&gt;

&lt;field name="VAR" id="y+\]\|\*,U4W?U\#nQwJre\|T" variabletype=""&gt;x&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="text\_prompt\_ext" id="6rxu;A}pK\_5lvKQR0pM!"&gt;

&lt;mutation type="TEXT"&gt;&lt;/mutation&gt;

&lt;field name="TYPE"&gt;TEXT&lt;/field&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="FhSwx+-zN@Fv5-4LR@v+"&gt;

&lt;field name="TEXT"&gt;abc&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="\(k%FQFzN\($m\#4C^m,\`zo"&gt;

&lt;field name="VAR" id=":?\|mRgh\){D^iIAirs2oU" variabletype=""&gt;i&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="!\`F\*6,6M42kK\[,\#Jek\)x"&gt;

&lt;field name="NUM"&gt;2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="controls\_whileUntil" id="^bS5d7%Z7vV5hlTr\[7zx"&gt;

&lt;field name="MODE"&gt;UNTIL&lt;/field&gt;

&lt;value name="BOOL"&gt;

&lt;block type="logic\_operation" id="8p19dQ.?W\`5?z\]g\]\)v;3"&gt;

&lt;field name="OP"&gt;OR&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="logic\_compare" id="3Ih,Hm?\)UHc!A\|:;n?h!"&gt;

&lt;field name="OP"&gt;EQ&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_modulo" id="\`h3ehcVH\]Np\_Z1@Z8MXJ"&gt;

&lt;value name="DIVIDEND"&gt;

&lt;shadow type="math\_number" id="iK70tJ\(;x+qwlp\_m:z/l"&gt;

&lt;field name="NUM"&gt;64&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id=",z\)r=zK!BOWa0\_5wCn!X"&gt;

&lt;field name="VAR" id="y+\]\|\*,U4W?U\#nQwJre\|T" variabletype=""&gt;x&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="DIVISOR"&gt;

&lt;shadow type="math\_number" id="E\]pNoPT@u7{gPE33eSxb"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="kRK\*}4e7\|^r6.nx@RnuB"&gt;

&lt;field name="VAR" id=":?\|mRgh\){D^iIAirs2oU" variabletype=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id="2gTkKW6\)bUo-\_u\#M\)V:O"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="logic\_compare" id="D2r+65/SVFK{m\|Io?eT\_"&gt;

&lt;field name="OP"&gt;EQ&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="variables\_get" id="R1@Q,o?UE;t%=Eg./dHk"&gt;

&lt;field name="VAR" id=":?\|mRgh\){D^iIAirs2oU" variabletype=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_arithmetic" id="\`;LoO$RB\#\#cN.9Cah4x}"&gt;

&lt;field name="OP"&gt;MINUS&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="PT40zzWL,VOo$YVVH}}}"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="\_:Xfs\`alR1~Og9\)-E4T."&gt;

&lt;field name="VAR" id="y+\]\|\*,U4W?U\#nQwJre\|T" variabletype=""&gt;x&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="\)B\[\#$~\[5Zc65L7OVIWbw"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO"&gt;

&lt;block type="variables\_set" id="pJhtN\*ue:/dEIXw:tsUA"&gt;

&lt;field name="VAR" id=":?\|mRgh\){D^iIAirs2oU" variabletype=""&gt;i&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_arithmetic" id="p9Sw2L{AP^m{As^RAoQL"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="IyzW\#h+2f,QSD=sbF-dq"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="\(i5PbxlP2ERT5\(S9ekpl"&gt;

&lt;field name="VAR" id=":?\|mRgh\){D^iIAirs2oU" variabletype=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="~g{knRU@zBg\*3u\`k-6ke"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block type="controls\_if" id="-\(=\)d7v\|ZXBb~7p1iOVT"&gt;

&lt;mutation else="1"&gt;&lt;/mutation&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="phv^gzdE$@5hd/pcrNlE"&gt;

&lt;field name="OP"&gt;EQ&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_modulo" id="Jv,DKNjtM2\*D;.QDdy6n"&gt;

&lt;value name="DIVIDEND"&gt;

&lt;shadow type="math\_number" id="iK70tJ\(;x+qwlp\_m:z/l"&gt;

&lt;field name="NUM"&gt;64&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="/\#iMO\`S=f5L47Xp?F,OE"&gt;

&lt;field name="VAR" id="y+\]\|\*,U4W?U\#nQwJre\|T" variabletype=""&gt;x&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="DIVISOR"&gt;

&lt;shadow type="math\_number" id="E\]pNoPT@u7{gPE33eSxb"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="lli\(l4Y!ZgT6jr%duEy+"&gt;

&lt;field name="VAR" id=":?\|mRgh\){D^iIAirs2oU" variabletype=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id="wR+heqHS\_\_TcCa\)S+2iQ"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="text\_print" id="PXXi.\)tWheJq76LBI?^X"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="5diS!\*9@4M\*L}\)L2x?T\`"&gt;

&lt;field name="TEXT"&gt;不是质数&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;statement name="ELSE"&gt;

&lt;block type="text\_print" id="LvEiJeRlI.W4z\]RfldeZ"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="8wJ2~K\`RNg,U^qQ721@,"&gt;

&lt;field name="TEXT"&gt;是质数&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/xml&gt;

