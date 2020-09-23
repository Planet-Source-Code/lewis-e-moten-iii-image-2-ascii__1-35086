<div align="center">

## Image 2 Ascii

<img src="PIC20025251122551299.gif">
</div>

### Description

The Image 2 Ascii converter allows you to load a photograph, and then generate an ascii image that looks simular to it. You can use this ascii version to post a picture of your self on news groups, message boards, email signatures, and more. No longer is text-only formatting a constraint for displaying photographs!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2002-05-26 11:20:40
**By**             |[Lewis E\. Moten III](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/lewis-e-moten-iii.md)
**Level**          |Intermediate
**User Rating**    |4.8 (76 globes from 16 users)
**Compatibility**  |VB 6\.0
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__1-46.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[Image\_2\_As868625252002\.zip](https://github.com/Planet-Source-Code/lewis-e-moten-iii-image-2-ascii__1-35086/archive/master.zip)





### Source Code

<P>
The Image 2 Ascii converter allows you to load a photograph, and then generate
an ascii image that looks simular to it. You can use this ascii version to post
a picture of your self on news groups, message boards, email signatures, and more.
No longer is text-only formatting a constraint for displaying photographs!
</P>
<P>
Results are based on the Courier New font in 10 points. They can be displayed
with other font families as long as they are also a fixed width font such as "Lucidia Console".
This program has not been designed
around other font-families luminancy and may not appear with accurate results.
</P>
<P>
Works best on small black & white images. However, it will work with color
images by getting the average lumanancy from each hue like so:
</P>
<CENTER>
(red + green + blue) / 3 = Average Lumanancy
</CENTER>
<P>
Due to the odd shapes of the characters used, larger images will appear
better. However, these larger images will take more time to convert.
I suggest sticking around a size of 100x100 pixels and then working
from there. You may also notice that the final result appears ... tall
and skinny. This is because the ratio of the characters used in the font
are not the same as an individual pixel. To solve this problem, you may
want to streatch your image to be wider with a graphics editing program,
or shorten the height.
</P>
<B>Sample of results you may achieve</B>
<PRE style="Font-Family:Courier New;Font-size:6pt;text-align:center;">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`^{x$y00DyZ3&amp;.`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.?oPQRRmkQQQQRNqAy2]{~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{JRN#HHRRdq@NNH#NH#NNHkLi^`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/mXN#NHNqR@N@HNHNH##NNNHNHqc}``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-4Xq##NHHHH#@NHRNN@NHH@N##M#Nq?~''&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`ZqQH###HH####@@HNNHN#HH##MM###H8u(`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``&nbsp;&nbsp;&nbsp;&nbsp;:dqNNN#MNNM#M#N#NHNHMNNH##MMM#M#NRVl`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`.-'''.$mQHH#####M#M####N@#MHNHNH##NHNHNHQX1`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`-&amp;?IdT3Jbq###M####M#MMMMMMHMMNN#HMMHqRH@HNNN@O{`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&amp;+j6eP@@XkRN#N#M#M#M##MMMMM#MMM#NNNMHQR8k@N##M#N@z`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;':tnkqXdRNH@H##H#M####M##MM#M#MM###HM#N@qqQ#M##MMM##L.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.{1Obqqm8RHNHHM####H##M########MM#NH####HNHNMMM#M#MMM#b.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;`&nbsp;&nbsp;.';$8QNRdQq@##MMN##NH#####N##MNNMM#H#M####M##M#MMMMMM#M#:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;'?1JXN@NNQNQN####HNHNH##NHHHNNH@@N##NHM#M#MMMMMMMMMMMMMM#A_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;`:xu8NHN@@q@HN##HHkAAq@QHHNqqqQkbmQHHNN##M##M#MMMMMMMMMMMM#L&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;'}20HHQ@HqR@#HHQf$i*+3TGXqk0wsJ2jI6ekXQNNHHNHN##MMMMMMM#M##m.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;.{vbN@NNNq8NH##@O?:-,&amp;:+2ZsIo[?:;};*C$6VAb8kkRqq@###MMMMMMM#Ht&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;!*DR@QNN@RQN##NF/'``'`'~_};&amp;_^.`''.^:{)%?l[3L6sbmmN#MMMMMMM#NN&amp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;:IH@RN#NHqHH##A+''`````````.`&nbsp;&nbsp;&nbsp;````''.-^^_;&gt;?CuTV8m@#MMMM##NHJ&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;`*kNN@##NHQH##R%!````&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`&nbsp;```..&amp;%2LZVqNMMMMMM#HR`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;`xHHHH##H@NHMHo&amp;``&nbsp;`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`.:%3JVR#MMMM##HHz`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;O#NN#MM#QQNHXl..```&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``',:ljFH#MMMHQHRHi&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;'d#N##MM#RqNHn&lt;.'.`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`..'^)$8HMMMNQqq#J&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;+RNHMM###HRHqx~..'``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`.``.)6Q##M#@QRH6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;x@NN##MM#HRQXJ,''''`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;```''&amp;%5HMM#HNRRD`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;O@@#MMMM#HQQP1&amp;''````&nbsp;``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;````',&lt;uRH##@QNRX&amp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;yqHMMMMM#RQRel;!.'..``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``.^:7FQNN@qN@QZ&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;bNNMM##MMHRfGj)&amp;..''```&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``.^{7ydR@N@H@QX'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;mH#M#MM##NkFT1*&amp;''.````&nbsp;````&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``',}]08QRHNN@RQ^&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;qN#MM#MM#@RXZol&amp;!'`'`&nbsp;&nbsp;&nbsp;`&nbsp;``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``.~;t0qHHHHHQQQ/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;HNH###M#M@RXOxi}~'.'```&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;```'.:+5qHNHHNNQqv&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;qHN#M##M#HQdnJ7?&amp;~'!.``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;```':*6qHNN#NHNQJ&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;@H###M#M#HR8O6o*&amp;~!-'``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`.''{%xXH#H#HHH85&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;HHH#M#M##N@ddVx/_!-''`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;```'{?zRN####NHRw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;@#N##M##NNRmQDz;&amp;^'.``&nbsp;&nbsp;&nbsp;```&nbsp;&nbsp;`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``````````'.:iumN####NHQ4`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;d##HMM##NNqQQst}:&amp;.`&nbsp;&nbsp;&nbsp;``.`.``'.```&nbsp;&nbsp;&nbsp;&nbsp;````.`'''''.~~''&amp;ioPHM##HNNQf`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;m##NH###HNH@kZi\}&amp;,'`.-,^_:}::--,'.`&nbsp;```..~&amp;:(+%i?%i[*?+lvONMM#HN#@Y.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;b##M##MHNNHN8I*}:{;{/?l*[JTYuVu3?&amp;^.'.'.&amp;:*7Luo$sb4y6esy$2od##M#NHNx&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;nMM#M######Hy+&lt;%l13CJzL4DkNHRRqfL&gt;&amp;-`'._(iLfd8d8qRRd8f4f0u7wH#M#NNqO`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;3##########@$??tCx6nsPbmQRHHNNQR5o%_''~{tL0qqR8qQXdAP6ZnALrI@#NH@@me.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;\#####N###HQJ??tJ$edPF0XXXQRqqRqm6t&amp;,'^}c68RqXdd8DwwOTuGYLx2RNM#H@kV'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;_NH###N#M#Hd](*uOOFDDXkAmmQQH@QRkTl&amp;''.:j4kqQR@@@RkfsZ2Z$J1vfN##NNR$&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;.R##M####HNw*&gt;%uf0bbdQRQ@RQHdRqRRP?.`&nbsp;`~CFkqQXHHH8emQkeL$3++6N##@RRz&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;XMN####HHqY?&lt;?Lf88dQRQRH@HqGk@Rqf*'&nbsp;&nbsp;&nbsp;.jAdddFmq@w28QQdVZ2+*IQ##@kRI&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;C#HNH#HHNRv&lt;;*LdmqQQqQRRRq808qmm5{.&nbsp;&nbsp;&nbsp;.[e8ddAfX84GD08bZLj?{rQNN@qNv&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;.X#HNHHNNml{{*jL8QqQqddFDyefPkdbo&amp;.&nbsp;&nbsp;&nbsp;`/ufAd8FAVZnTebs6o+;:iDHNqQH{&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;lMHH@HHNk*&amp;&amp;:\%2sb8XPyYTZTOynbo}&amp;.`&nbsp;&nbsp;`&amp;[TAADP4TLLZwVOzc*:::GHNQRq.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&amp;NNH@q@Hwi:_-!&amp;:+12Zu$x][++]tl;_,'`&nbsp;&nbsp;`_;*cCvr[[[jrzC%?;}_::uQ@qP3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;~NNNHHNqT]:~''..-~&amp;:}:&amp;-'..''''.'.`&nbsp;&nbsp;`^_.&amp;::;}::_&amp;&amp;_&amp;!'',_:7fXmO_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;`RHNNqRmL%;,.''`''`'```.`'``.'..'``&nbsp;&nbsp;`^&amp;!'.'.,!''``.'''.!&amp;:+ym$c:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;`yqQRRQRo?&gt;:.''`.'.````````'.''.'.&nbsp;&nbsp;&nbsp;`._-.'.````'.```..'~_:*uT3v_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;]kdmkQbvl}:&amp;^.'.`'```&nbsp;&nbsp;&nbsp;``'.,-,''`&nbsp;&nbsp;&nbsp;'~,-..`'``..`.''!-_{}?vrCr`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;_FyPkX6v%*/:,~''.'.`````&nbsp;`.'_&amp;~.`&nbsp;&nbsp;&nbsp;&nbsp;`.&amp;:..'`.'.``..',&amp;:\?*+rI%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;'$Gemkut]??{:__.'''''.``.``&amp;}&amp;'`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``~}_''``'..'.'.~:{\*&gt;*+r:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?wuPbo7[+*\;}:!,!'`.'..'.,}}~'.```&nbsp;`'^,^:!..`.''''^^-{}?*?*?i'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_T$ZPu[7l[?\}{&amp;!.''`'`'..&amp;|_^{?;&amp;'':}{&amp;~&amp;&amp;,'..'`.!^^_:\*?***;.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.uu5s$[[tv+?){_,''''.''~~:&gt;{}3uYx**icJ1&gt;&gt;:_,.-''-!,_&amp;{*%((*}'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`xuu$Iouxvit[;}&amp;,'^'''~~&amp;:*vLXRQFLzJfqPJ?&amp;~_^~~--__&amp;:/?*/)?:`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;;2vTOJJc]]+%*;&amp;-~-!-^!&amp;&amp;&amp;|OFkQQAZLz0d0O]-.~~-!!,&amp;:::((|&gt;?({&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![7$TIzo7]*??/:_~-^-&amp;_&amp;_'&amp;6Fmk8fVuI08An['.'!&amp;&amp;&amp;:&amp;&amp;}{;/??*\:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`\?COo$u2j[1&gt;/;:_&amp;&amp;&amp;&amp;&amp;!.`'Jk88FnGLx$sGGC-`..-&amp;::{{{;\???i?~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&amp;&lt;oZ$x$JJr[&gt;|?}:&amp;_:&amp;,'``'*DAXfT$L22$L$7&amp;`.'-_{:{(;}**???;`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`{ufZuLLJcjt+*?;;::&amp;-...'{CxJTu$LoI$oz]},''-^{}{}\/*??&lt;:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~wmyuLLI2jr]l?&gt;&gt;\:-'.,-.&amp;_{\*r$u2xIv]*:&amp;!_,&amp;{}}()&gt;?***_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'8NPxLLxIoC7+*?&gt;&gt;:&amp;&amp;-:&amp;~^..'!}tzJxcl?;:{{{:&amp;;;??(%****!&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-mNquzLuJox21**%\{|;:}}:,--;(?%]jxx3t{;|%?{;;{/?*l?*;?'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'0NHeuZ$$TYuj7+i*?*(*l**?t$uJuyTTwwTuCt7v]*+*;{?***?}/'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NHP$uuY6uICv7+?%++[xun5AdfD8dm8mkPffDsw$v+*)&lt;?+l+?&gt;}`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.dN8YYL$Y2Lotl*l[7jTym@R0GL**xICTYn5Dk8dTI%+???%l%*\&amp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{mqZOOY6TTLj[+1CJ$ydd0Toxl&amp;&amp;{:{[337vzIccC7+?|itl*(|'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;zHAuZnY66$oc111CLuzcc71jc%i?&gt;7crj1%?|:{i[?i%+?*l?*'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_]$YO4VVTOuIv11Coc*|%1cI$Lz2J$L2C%*{::}+c[+++**??;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`:xZ6nwnOZLLrcxc*/}&lt;l3zTwV54LY$C+*}};*[ICci[+++?'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.cZ64V5TLLTLozi))\?+1jLOsysOOI2C+?(*]3L2C]j]%r:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.%6T5sZYY6O6uo1*****[c2LTneZ$jCC+*(/ijICv7tl?+^&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`|O6Gb04VeTOZ$v7*)&lt;)|&lt;&gt;*\)/*+?*(*(*?*71rrt73[[.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`}ZOwy50P4ee$IJ[i?):-___-.',---~:;(*l[[J1]]17l.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&amp;ZOsysFFbbGz2C+*\}_.-_~.'.,'''.^:;&gt;l17Irl[[%?'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:Z5TnPfbDP6Juul?(::&amp;,^,'...'-,!^:)?]1]Icj3t+?~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:YsYs0GefAOTYoc+*;&lt;:~^~~^^~!&amp;:__;?+r2cv1r7+l/!&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:oLOyY4ysy0bD63l%+l&gt;|;{}){{::&gt;\;?[3cJ[v2jt%?}_.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_2LYVYenfwPPfyOxIJC*1%tic7l+l?tj1tv23v2xj[i*};,`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_uLDPyGPeY6ydd0FswYILTLLZ$Ix2zLLLCr2vjICrt**}{|.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`\2I6YTTenVDnyDDPFFVZe44YLZYTuL$$$zJoxcxI[+*?;;*&amp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;;tcLOYOynFAkeTPbFFXfn4GnGTOOZYuLZx2Y$22IJ7+?*{{+{`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`(jvoTyVVynyPPGPfw58F4DAADw4eGeywOO$LLjc3Ctti?&lt;?l}.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'?x3u6Z655Asf05GPsGAb4DFAywwwynwyGsuzuzrCrCt?\/[7;-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'?xIoLLYyPAAGGAfb8F0b0AA0n0seO5TL$LuLL2xC7]t+*?]*{-``&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'{c$ILTnPDyA0bDFbeFb4VPD0P54YVsLLZLuozzIrt]+**[C+/&amp;~,,..`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.:[$22uY55Fb8FydfOwDnebeynwyZ4VYwZ6JJzzor3t+*|7o*&amp;~!;:&amp;_~''`&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.-\zxuo$ZGf0AADbbAADyF4V45ese4ZZZ4ujxCxozv+?*?ct?:-,:{&amp;_,^~.''`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'^,:uZz$TY5eybF0DDAe5f0PyfAVDOY4ZuOOxIIort1t+*v$*/:,-:({:&amp;&amp;,'.'`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``.&amp;:_:cZz$u$yGGA0Pfwe50F5AeD0VZZLnYOuOu2o2IC1ilioj*}_~}:}{:__-'.``
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`'-_:_:|LwuLYyTeAAwyGk0PAnwneOYu6u6$$Luu$2Cjt[+%zL1*;__?;}{}&amp;_~.'``
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`''_)::&amp;rnu6Z$w54eyVFDsPmDenwYGneZO$$Tuxxxccc]*tux\};-:?}:;:&amp;^.''`&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;```!t/;:*$O6OYT56ZGVFVf0005FwZTYY66$$LxoCvv1[]tIv+}::-}?::};&amp;...``&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``-x&lt;}:&amp;(2O66OT66TOG5n0PsV5eV6LYOL$$uxzcvcvt1IL]*)}&amp;_%&lt;_:{}_.``&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`~j\{:&amp;:rYTZYTuZYYT5s6OnGnOVZuYLxuLo2I]ccr32$2]*&lt;{&amp;;z*:::&amp;''.&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;``j*;|_:*2eOLuLTOYs5n4yw6TY6Z$TJzzoz2C37[rxZJcl(){_[Z}&amp;::_.'.``&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'3[(?;:{lu6OLL$uLO46TsT6ZZZ$u$6Lux2zzrtvcT6zC?;;:_$x_:{_-'`'`&nbsp;&nbsp;&nbsp;
</PRE>

