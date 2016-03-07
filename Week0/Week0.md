# Hctfgame writeup week0

### WEB ###
> 
 - WEB 从 0 开始之 0  
   题目ID： 26  
   题目描述： WEB页面的HTML，CSS，JS客户端是可以查看的哦～你能在平台源码中找到FLAG么？  
   Hint: 不知你有没有发现，通过右键看到的源码中没有题目，没有排名信息。  
   推荐：chrome -> F12; firefox -> firebug  
   
   chrome --> F12 --> ctrl+F 在源码中查找 hctf  
> 
 - WEB 从 0 开始之 0.1  
   题目ID： 27  
   题目描述： 你知道一个网页从输入URL到显示出页面，都经历了啥么？  
   http://ctf.lazysheep.cc:8080/  
   Hint: Do you know HTTP headers?  
   
   chrome --> F12 --> 转到网址（注意原网址和跳转的不同） --> Network 里面的 Headers
> 
 - WEB 从 0 开始之 0.2  
   题目ID： 35  
   题目描述： 你知道啥是cookie吗？  
   那么你会修改它吗？  
   http://ctf.lazysheep.cc:8080/web0-2.php  
   
   Firefox --> Firebug 查看 cookie --> givemeflag 的内容 fault 改为 true --> F5

### MISC ###
> 
 - MISC 从 0 开始之编码 0  
   题目ID： 25  
   题目描述： SENURntUSElTSVNCQVNFNjRFTkNPREV9  
   Hint: base系列编码  
   
   Bash64 解密  
> 
 - CTF coding step0  
   题目ID： 30
   题目描述： 打CTF就是拿工具？不不不，也要写很多代码的。     这个系列就是让你熟悉CTF风格的编程题目，具体的要求见题目吧のの           就是让你们多看点英文：
   nc 115.29.77.78 9999
   Hint: 用telnet或者nc连接如上地址和端口，  
   windows下没有的请自行寻找ssh/telnet工具  
   
   Windows XP 虚拟机 --> 开始运行 command --> 输入 telnet 115.29.77.78 9999 -->  
   goal : write a automatic script to communicate with the server  
   need to do : keep sending character 'A' (1 'A' per line)  
   get the complete flag : 300 to 500 round  
--> 目标达不到（自动脚本不会写），一直输入 A+enter，输300-500次
> 
 - MISC 从 0 开始之 Steganography 0 
   题目ID： 32  
   题目描述： AK菊苣的小姐姐们之0～  
   http://ctf.lazysheep.cc:8080/steg0.html  
   
   图片下载 -->  
   （一） 记事本打开 --> 查找 ctf  
   （二） 右键属性 --> 详细信息，什么也没有 --> 用 StegSolve 打开 --> Analyse 的 File Format 中 Ascii: 里面有 flag  
> 
 - MISC 从 0 开始之流量分析 0  
   题目ID： 33  
   题目描述： http://ctf.lazysheep.cc:8080/net0.pcap  
   Hint: PS: FLAG打错了。。格式变成flag{}..懒得改了  
   
   图片下载 --> 记事本打开 --> 查找 flag --> 猜想 %7B 和 %7D 分别为 { }  
   
### CRYPTO ###
> 
 - 密码学从 0 开始之 0  
   题目ID： 23  
   题目描述： ojam{AopzpzJhlzhyWhzzdvyk}  
   Hint: Caesar's code  
   
   Hint : Caesar's code --> ojam 对应 hctf  
   abcdefghijklmnopqrstuvwxyz  
   tuvwxyzabcdefghijklmnopqrs