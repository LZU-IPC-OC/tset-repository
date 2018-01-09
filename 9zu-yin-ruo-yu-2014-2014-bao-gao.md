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

对blockly的认识                                          ——by尹若宇320170936941

在大一的上半学期，我选择了关于机器人的一门选修课程。本人也是物理科学与技术学院的一员。由于我们学院的招生政策，这使得我可以在大二在对自己以后想从事的专业再一次地进行选择，而我以后的志愿去从事微电子行业。这样，这个关于机器人的编程与连线的课程深深的吸引了我。而在这我将分享我的关于这门课程的自己的理解和自己的一个实例。

刚开始我是十分的不理解这门课程为什么要开展blockly编程的教育。因为这看起来是给小孩子玩的东西。但是随着课程的推进，这个看似简单但是内涵的复杂程度使我又对其刮目相看。突然发现对于我自己这给小小的东西又显得那么困难。每一个执行，完成，都显得那么新鲜，但是都是进过无数的思考而完成的思想结晶。

最体现无遗的就是课程的最后的组队拼装机器人，来编程完成小车行走迷宫。刚开始的拼接都充满着无数的麻烦，我在小组中的工作是有关小车的线路拼接和测试时的跟随与调整。刚开始那传感器的接口顺序就把我们整的头晕乱转，在我以后的微电子专业中比这难上加难的线路估计多只又多，但是在现在我显得是那么苍白与无力。课程的时间限制有将近6个小时，但是和对我们线路拼接的时间是所有组中耗时最长的。中间期间我们的零件也出现了些小的问题，这对我们更是雪上加霜，但是我们凭借着顽强的毅力和虚心请教的老师的帮助下最终完成了小车的组装。

正所谓卧薪尝胆，在小车拼接的环节表现不济后，我们发誓要后发居上，我们希望做出编程简洁而又能通过迷宫的完美程序。在其他组的失败中我们吸取了教训，总结了经验。在不断的调试数据，无数次尝试之后，我们几近完美的小车完成了第一个迷宫的任务，成为了第一个完成第一个迷宫的组。虽然我们在第二个迷宫中折戟沉沙，没有成为唯一的完成者非常可惜，但是我们完成了自己的工作，这是我们高兴的地方。

而对于我们个人的认识，我发现做成一件事有时候还是非常困难的，你会遇到各种各样的情况，有时候是积极的，但大多数时候是负面的，这时候就要我们调整好自己的情绪，不能被一些琐碎的小事而丢失了自己的方向，就正如我们组装的小车一样，有时会因为传感器的不灵敏而至于东倒西歪，这是我们没有调整好自己的缘故。对于blockly，困难时有时让你无从下手，而灵光一闪成功的大门就向你敞开了，这时候就要发扬自己的艰苦奋斗的精神，永不服输就是成功了。

在这个课程中我收获了友情和知识，同时为自己以后的专业有了一个小小的基础，可谓是收获很丰富吧，如果以后会开展类似的课程，我会继续参加的，也希望我们小组的成员能是和我一样的想法吧。



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
p.MsoHeader, li.MsoHeader, div.MsoHeader  
	{mso-style-priority:99;  
	mso-style-link:"页眉 字符";  
	margin:0cm;  
	margin-bottom:.0001pt;  
	text-align:center;  
	mso-pagination:none;  
	tab-stops:center 207.65pt right 415.3pt;  
	layout-grid-mode:char;  
	border:none;  
	mso-border-bottom-alt:solid windowtext .75pt;  
	padding:0cm;  
	mso-padding-alt:0cm 0cm 1.0pt 0cm;  
	font-size:9.0pt;  
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
span.a  
	{mso-style-name:"页眉 字符";  
	mso-style-priority:99;  
	mso-style-unhide:no;  
	mso-style-locked:yes;  
	mso-style-link:页眉;  
	mso-ansi-font-size:9.0pt;  
	mso-bidi-font-size:9.0pt;}  
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


![](file:///C:/Users/WUYIWA~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)而对于我们个人的认识，我制作了一个可以检验数字是否是指数的程序。当X取1-1000时，从我写的程序来看，要进行500000次的除以I的循环。而i是趋于2-x-1的任意整数，当有整数被其整除是就发现其有与其自身和1不同的因数，从而这个数就是非质数了。当然者的前提还是循环的次数足够多这样才满足条件，所以我把循环次数调到了500000次这一较大的次数，且x的范围也是比较小的。这样就近似的完成了我们想要的任务。

![](/assets/IMG_20180107_154749.jpg)

