<!DOCTYPE html>
<!-- saved from url=(0052)https://wiki.osdev.org/Parallel_port#Status_Register -->
<html lang="en" dir="ltr" class="client-js"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Parallel port - OSDev Wiki</title>

<meta name="generator" content="MediaWiki 1.18.0">
<link rel="shortcut icon" href="https://wiki.osdev.org/favicon.ico">
<link rel="search" type="application/opensearchdescription+xml" href="https://wiki.osdev.org/opensearch_desc.php" title="OSDev Wiki (en)">
<link rel="EditURI" type="application/rsd+xml" href="https://wiki.osdev.org/api.php?action=rsd">
<link rel="alternate" type="application/atom+xml" title="OSDev Wiki Atom feed" href="https://wiki.osdev.org/index.php?title=Special:RecentChanges&amp;feed=atom">
<link rel="stylesheet" href="./Parallel port - OSDev Wiki_files/load.php">
<style type="text/css" media="all">.mw-collapsible-toggle{float:right} li .mw-collapsible-toggle{float:none} .mw-collapsible-toggle-li{list-style:none}

/* cache key: wikidb:resourceloader:filter:minify-css:4:4250852ed2349a0d4d0fc6509a3e7d4c */
</style><style type="text/css" media="all">.js-messagebox{margin:1em 5%;padding:0.5em 2.5%;border:1px solid #ccc;background-color:#fcfcfc;font-size:0.8em}.js-messagebox .js-messagebox-group{margin:1px;padding:0.5em 2.5%;border-bottom:1px solid #ddd}.js-messagebox .js-messagebox-group:last-child{border-bottom:thin none transparent}

/* cache key: wikidb:resourceloader:filter:minify-css:4:8b08bdc91c52a9ffba396dccfb5b473c */
</style><meta name="ResourceLoaderDynamicStyles" content="">
<link rel="stylesheet" href="./Parallel port - OSDev Wiki_files/load(1).php">
<style>a:lang(ar),a:lang(ckb),a:lang(fa),a:lang(kk-arab),a:lang(mzn),a:lang(ps),a:lang(ur){text-decoration:none}a.new,#quickbar a.new{color:#ba0000}

/* cache key: wikidb:resourceloader:filter:minify-css:4:c88e2bcd56513749bec09a7e29cb3ffa */
</style>
<script src="./Parallel port - OSDev Wiki_files/load(2).php"></script><script src="./Parallel port - OSDev Wiki_files/load(3).php"></script>
<script>if(window.mw){
	mw.config.set({"wgCanonicalNamespace": "", "wgCanonicalSpecialPageName": false, "wgNamespaceNumber": 0, "wgPageName": "Parallel_port", "wgTitle": "Parallel port", "wgCurRevisionId": 27934, "wgArticleId": 2094, "wgIsArticle": true, "wgAction": "view", "wgUserName": null, "wgUserGroups": ["*"], "wgCategories": ["Stubs", "Common Devices", "Hardware Interfaces"], "wgBreakFrames": false, "wgRestrictionEdit": [], "wgRestrictionMove": []});
}
</script><script>if(window.mw){
	mw.loader.load(["mediawiki.page.startup"]);
}
</script><script type="text/javascript" src="./Parallel port - OSDev Wiki_files/load(4).php"></script>
<style type="text/css">/*<![CDATA[*/
.source-c {line-height: normal;}
.source-c li, .source-c pre {
	line-height: normal; border: 0px none white;
}
/**
 * GeSHi Dynamically Generated Stylesheet
 * --------------------------------------
 * Dynamically generated stylesheet for c
 * CSS class: source-c, CSS id: 
 * GeSHi (C) 2004 - 2007 Nigel McNie, 2007 - 2008 Benny Baumann
 * (http://qbnz.com/highlighter/ and http://geshi.org/)
 * --------------------------------------
 */
.c.source-c .de1, .c.source-c .de2 {font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;}
.c.source-c  {font-family:monospace;}
.c.source-c .imp {font-weight: bold; color: red;}
.c.source-c li, .c.source-c .li1 {font-weight: normal; vertical-align:top;}
.c.source-c .ln {width:1px;text-align:right;margin:0;padding:0 2px;vertical-align:top;}
.c.source-c .li2 {font-weight: bold; vertical-align:top;}
.c.source-c .kw1 {color: #b1b100;}
.c.source-c .kw2 {color: #000000; font-weight: bold;}
.c.source-c .kw3 {color: #000066;}
.c.source-c .kw4 {color: #993333;}
.c.source-c .co1 {color: #666666; font-style: italic;}
.c.source-c .co2 {color: #339933;}
.c.source-c .coMULTI {color: #808080; font-style: italic;}
.c.source-c .es0 {color: #000099; font-weight: bold;}
.c.source-c .es1 {color: #000099; font-weight: bold;}
.c.source-c .es2 {color: #660099; font-weight: bold;}
.c.source-c .es3 {color: #660099; font-weight: bold;}
.c.source-c .es4 {color: #660099; font-weight: bold;}
.c.source-c .es5 {color: #006699; font-weight: bold;}
.c.source-c .br0 {color: #009900;}
.c.source-c .sy0 {color: #339933;}
.c.source-c .st0 {color: #ff0000;}
.c.source-c .nu0 {color: #0000dd;}
.c.source-c .nu6 {color: #208080;}
.c.source-c .nu8 {color: #208080;}
.c.source-c .nu12 {color: #208080;}
.c.source-c .nu16 {color:#800080;}
.c.source-c .nu17 {color:#800080;}
.c.source-c .nu18 {color:#800080;}
.c.source-c .nu19 {color:#800080;}
.c.source-c .me1 {color: #202020;}
.c.source-c .me2 {color: #202020;}
.c.source-c .ln-xtra, .c.source-c li.ln-xtra, .c.source-c div.ln-xtra {background-color: #ffc;}
.c.source-c span.xtra { display:block; }

/*]]>*/
</style>
<style type="text/css">/*<![CDATA[*/
@import "/index.php?title=MediaWiki:Geshi.css&usemsgcache=yes&action=raw&ctype=text/css&smaxage=18000";
/*]]>*/
</style><!--[if lt IE 7]><style type="text/css">body{behavior:url("/skins/vector/csshover.min.htc")}</style><![endif]--></head>
<body class="mediawiki ltr sitedir-ltr ns-0 ns-subject page-Parallel_port action-view skin-vector">
		<div id="mw-page-base" class="noprint"></div>
		<div id="mw-head-base" class="noprint"></div>
		<!-- content -->
		<div id="content">
			<a id="top"></a>
			<div id="mw-js-message" style="display:none;" class="js-messagebox"></div>
						<!-- firstHeading -->
			<h1 id="firstHeading" class="firstHeading">Parallel port</h1>
			<!-- /firstHeading -->
			<!-- bodyContent -->
			<div id="bodyContent">
								<!-- tagline -->
				<div id="siteSub">From OSDev Wiki</div>
				<!-- /tagline -->
								<!-- subtitle -->
				<div id="contentSub"></div>
				<!-- /subtitle -->
																<!-- jumpto -->
				<div id="jump-to-nav">
					Jump to: <a href="https://wiki.osdev.org/Parallel_port#mw-head">navigation</a>,
					<a href="https://wiki.osdev.org/Parallel_port#p-search">search</a>
				</div>
				<!-- /jumpto -->
								<!-- bodycontent -->
				<div lang="en" dir="ltr" class="mw-content-ltr"><center>
<table style="border: 1px solid #cfcfbf; margin-top: 25px; margin-bottom: 25px; background-color: #f0f0ff; text-align: center;">
<tbody><tr>
<td>
<p><b>NOTE:</b> Before doing anything, make sure to set the parallel ports mode to Standard or Normal in the BIOS instead of ECP/EPP if anything fails from your programming efforts, preferably before exhausting your options
</p>
</td></tr></tbody></table>
</center>
<p><br>
The parallel port uses a sub-d 25 connector to provide a 8-bit data bus. It is commonly used by printers. There are 3 kinds of parallel ports: Standard Parallel Port (SPP), Enhanced Parallel Port (EPP) and Extended Capabilities Parallel Port (ECP). iirc they are all part of IEEE Standard 1284, or is it just the second two?
</p>
<table id="toc" class="toc"><tbody><tr><td><div id="toctitle"><h2>Contents</h2><span class="toctoggle">&nbsp;[<a href="https://wiki.osdev.org/Parallel_port#" class="internal" id="togglelink">hide</a>]&nbsp;</span></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="https://wiki.osdev.org/Parallel_port#Pin_types"><span class="tocnumber">1</span> <span class="toctext">Pin types</span></a></li>
<li class="toclevel-1 tocsection-2"><a href="https://wiki.osdev.org/Parallel_port#Registers_.26_Common_Address"><span class="tocnumber">2</span> <span class="toctext">Registers &amp; Common Address</span></a></li>
<li class="toclevel-1 tocsection-3"><a href="https://wiki.osdev.org/Parallel_port#Parallel_Port_Software_Interface"><span class="tocnumber">3</span> <span class="toctext">Parallel Port Software Interface</span></a>
<ul>
<li class="toclevel-2 tocsection-4"><a href="https://wiki.osdev.org/Parallel_port#Data_Register"><span class="tocnumber">3.1</span> <span class="toctext">Data Register</span></a></li>
<li class="toclevel-2 tocsection-5"><a href="https://wiki.osdev.org/Parallel_port#Status_Register"><span class="tocnumber">3.2</span> <span class="toctext">Status Register</span></a></li>
<li class="toclevel-2 tocsection-6"><a href="https://wiki.osdev.org/Parallel_port#Control_Register"><span class="tocnumber">3.3</span> <span class="toctext">Control Register</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-7"><a href="https://wiki.osdev.org/Parallel_port#Standard_Parallel_Port_Mode"><span class="tocnumber">4</span> <span class="toctext">Standard Parallel Port Mode</span></a>
<ul>
<li class="toclevel-2 tocsection-8"><a href="https://wiki.osdev.org/Parallel_port#Centronics_Handshaking"><span class="tocnumber">4.1</span> <span class="toctext">Centronics Handshaking</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-9"><a href="https://wiki.osdev.org/Parallel_port#See_Also"><span class="tocnumber">5</span> <span class="toctext">See Also</span></a>
<ul>
<li class="toclevel-2 tocsection-10"><a href="https://wiki.osdev.org/Parallel_port#Threads"><span class="tocnumber">5.1</span> <span class="toctext">Threads</span></a></li>
</ul>
</li>
</ul>
</td></tr></tbody></table>
<h2> <span class="mw-headline" id="Pin_types">Pin types</span></h2>
<p>Most parallel ports come in either 36 or 25 pin varieties. 25 being the most common.
</p>
<h2> <span class="mw-headline" id="Registers_.26_Common_Address">Registers &amp; Common Address</span></h2>
<p>Common base addresses are:
</p>
<ul><li> LPT1: 0x378 (or occasionally 0x3BC) (IRQ 7)
</li><li> LPT2: 0x278 (IRQ 6)
</li><li> LPT3: 0x3BC (IRQ 5)
</li></ul>
<p>The <a href="https://wiki.osdev.org/Memory_Map_(x86)#BIOS_Data_Area_.28BDA.29" title="Memory Map (x86)">BIOS Data Area</a> should contain the IO base addresses of any existing parallel ports
</p>
<h2> <span class="mw-headline" id="Parallel_Port_Software_Interface">Parallel Port Software Interface</span></h2>
<center>
<table style="border: 1px solid #cfcfbf; margin-top: 25px; margin-bottom: 25px; background-color: #f0f0ff; text-align: center;">
<tbody><tr>
<td>
<p><a href="https://wiki.osdev.org/File:Stub.png" class="image" title="This article is a stub!"><img alt="This article is a stub!" src="./Parallel port - OSDev Wiki_files/Stub.png" width="50" height="50"></a>
This page or section is a <a href="https://wiki.osdev.org/Category:Stubs" title="Category:Stubs">stub</a>. You can help the wiki by <i>accurately</i> <a rel="nofollow" class="external text" href="https://wiki.osdev.org/index.php?title=Parallel_port&amp;action=edit">contributing</a> to it.
</p>
</td>
<td>
</td></tr></tbody></table>
</center>
<p>Each parallel port has three IO port registers, Data, Status and Control.  Their addresses are relative to the base address of the parallel port in question.
</p>
<h3> <span class="mw-headline" id="Data_Register">Data Register</span></h3>
<p>Address = Base Address + 0
</p><p>Any byte writen to this register is put on pins 2 through 9 of the port.
Any read from this register reflects the state of the port.
</p>
<h3> <span class="mw-headline" id="Status_Register">Status Register</span></h3>
<p>Address = Base Address + 1
</p>
<table border="border" style="width: 100%">
<tbody><tr><td>Bit 0</td><td>Bit 1</td><td>Bit 2</td><td>Bit 3</td><td>Bit 4</td><td>Bit 5</td><td>Bit 6</td><td>Bit 7</td></tr>
<tr><td>Reserved</td><td>Reserved</td><td>IRQ</td><td>ERROR</td><td>SELECT_IN</td><td>PAPER_OUT</td><td>ACK</td><td>BUSY</td></tr>
</tbody></table>
<p>The ERROR, ACK and BUSY signals are active low  when reading from the IO port.
</p>
<h3> <span class="mw-headline" id="Control_Register">Control Register</span></h3>
<p>Address = Base Address + 2
</p>
<table border="border" style="width: 100%">
<tbody><tr><td>Bit 0</td><td>Bit 1</td><td>Bit 2</td><td>Bit 3</td><td>Bit 4</td><td>Bit 5</td><td>Bit 6</td><td>Bit 7</td></tr>
<tr><td>STROBE</td><td>AUTO_LF</td><td>INITIALISE</td><td>SELECT</td><td>IRQACK</td><td>BIDI</td><td>Unused</td><td>Unused</td></tr>
</tbody></table>
<p>The INITIALISE signal is active low when writing to the IO port.
</p><p>The STROBE signal is for handshaking and alerts the printer to data being ready at the data port.
</p><p>AUTO_LF is the Automatic Line-Feed signal.  If this is set and the printer receives a Carriage-Return character (0x0D), the printer will automatically perform a Line-Feed (character 0x0A) as well.
</p><p>INITIALISE, sometimes called PRIME, alerts the device that data that a data conversation is about to start.  This signal may result in a printer performing a reset and any buffers being flushed.
</p><p><br>
</p>
<h2> <span class="mw-headline" id="Standard_Parallel_Port_Mode">Standard Parallel Port Mode</span></h2>
<p>This is the most basic of the parallel modes.  The other modes are EPP and ECP.  All systems should support this mode and it may well be the default at boot time.  Some BIOSes also support setting the default mode of the parallel port.  In this mode, the Data register and the Control register are Write-Only and the Status register is Read-Only.
</p><p>In Standard (or Compatibility) mode, data is sent using a mechanism called Centronics Handshaking, described below.
</p><p>This mode requires communuication handshaking to be performed by software which limits the maximum data throughput of the port.  This means that a standard mode has a maximum transfer rate of around 1000 bytes per second, depending on the timings of the computer and receiving device.  The more advanced types (or modes) of parallel ports, EPP and ECP, reduce this by providing hardware-based handshaking.  Relieving software of this requirement reduces CPU load and increases the port's maximum potential speed.
</p><p>For a line printer, this method should be enough to get things going, simply sending characters using this method to the parallel port while the printer is online should get the print head moving, assuming no buffers are in the way to store the values.
</p><p>Depending on the connected device, you may have to raise the INITIALISE signal before data transmission to ready the device, and possibly again after in order to flush any buffers.
</p>
<h3> <span class="mw-headline" id="Centronics_Handshaking">Centronics Handshaking</span></h3>
<p>In Standard (or Compatibility) mode, data is sent to the connected device by writing the byte to the data port, then pulsing the STROBE signal.  This pulse informs the device that data is ready to be read.  The device will respond by raising its BUSY signal and then reading the data and performing some processing on it.  Once this processing is complete, the device will lower the Busy signal and may raise a brief ACK signal to indicate that it has finished.
</p>
<div dir="ltr" class="mw-geshi" style="text-align: left;"><div class="c source-c"><pre class="de1"> <span class="co1">// Sends a byte to the printer</span>
 <span class="kw4">void</span> Parallel_SendByte<span class="br0">(</span> <span class="kw4">unsigned</span> <span class="kw4">char</span> pData <span class="br0">)</span>
 <span class="br0">{</span>
 	<span class="kw4">unsigned</span> <span class="kw4">char</span> lControl<span class="sy0">;</span>
&nbsp;
 	<span class="co1">// Wait for the printer to be receptive</span>
 	<span class="kw1">while</span> <span class="br0">(</span> <span class="sy0">!</span> inb<span class="br0">(</span> <span class="nu12">0x379</span> <span class="br0">)</span> <span class="sy0">&amp;</span> <span class="nu12">0x80</span> <span class="br0">)</span>
 	<span class="br0">{</span>
 		Timer_Delay<span class="br0">(</span> <span class="nu0">10</span> <span class="br0">)</span><span class="sy0">;</span>
 	<span class="br0">}</span>
&nbsp;
 	<span class="co1">// Now put the data onto the data lines</span>
 	outb<span class="br0">(</span> <span class="nu12">0x378</span><span class="sy0">,</span> pData <span class="br0">)</span><span class="sy0">;</span>
&nbsp;
 	<span class="co1">// Now pulse the strobe line to tell the printer to read the data</span>
 	lControl <span class="sy0">=</span> Ports_In8<span class="br0">(</span> <span class="nu12">0x37A</span><span class="br0">)</span><span class="sy0">;</span>
 	outb<span class="br0">(</span> <span class="nu12">0x37A</span><span class="sy0">,</span> lControl <span class="sy0">|</span> <span class="nu0">1</span> <span class="br0">)</span><span class="sy0">;</span>
 	Timer_Delay<span class="br0">(</span> <span class="nu0">10</span> <span class="br0">)</span><span class="sy0">;</span>
 	outb<span class="br0">(</span> <span class="nu12">0x37A</span><span class="sy0">,</span> lControl <span class="br0">)</span><span class="sy0">;</span>
&nbsp;
&nbsp;
 	<span class="co1">// Now wait for the printer to finish processing</span>
 	<span class="kw1">while</span> <span class="br0">(</span> <span class="sy0">!</span> inb<span class="br0">(</span> <span class="nu12">0x379</span> <span class="br0">)</span> <span class="sy0">&amp;</span> <span class="nu12">0x80</span> <span class="br0">)</span>
 	<span class="br0">{</span>
 		Timer_Delay<span class="br0">(</span> <span class="nu0">10</span> <span class="br0">)</span><span class="sy0">;</span>
 	<span class="br0">}</span>
 <span class="br0">}</span></pre></div></div>
<p><tt>Timer_Delay()</tt> pauses processing for the specified number of milliseconds. <tt>inb()</tt> and <tt>outb()</tt> read and write a byte of data to/from the IO port.  You can find the IO functions in the <a href="https://wiki.osdev.org/Inline_Assembly/Examples#OUTx" title="Inline Assembly/Examples">Inline Assembly Examples page</a>.
</p><p><br>
</p><p><a rel="nofollow" class="external text" href="http://devel.archefire.org/TextRecordings/lpthandler.tar"><b><code>lpthandler.tar:</code></b> Code and binary for "LPT Handler for Windows"</a>
</p><p><a rel="nofollow" class="external text" href="http://www.youtube.com/watch?v=sJRbGohmA3M"><b>YouTube video:</b> Basics of Parallel Port Programming Under Windows, Part 1 of 2</a>
</p><p><a rel="nofollow" class="external text" href="http://www.youtube.com/watch?v=zAxeCLuWZCk"><b>YouTube video:</b> Basics of Parallel Port Programming Under Windows, Part 2 of 2</a>
</p><p><a href="https://wiki.osdev.org/File:Win32_lpthandler_exe_0000.jpg" class="image"><img alt="Win32 lpthandler exe 0000.jpg" src="./Parallel port - OSDev Wiki_files/Win32_lpthandler_exe_0000.jpg" width="954" height="540"></a>
</p>
<div dir="ltr" class="mw-geshi" style="text-align: left;"><div class="c source-c"><pre class="de1"><span class="coMULTI">/*
 In short we only need:
&nbsp;
  outl(LPT_Base_Address+2, 0);          //Reset Control port with 0
  outl(LPT_Base_Address,   0xFF-0x00);  //Write Data Port with any byte value
*/</span>
&nbsp;
&nbsp;
&nbsp;
<span class="co1">//Here the LPT_Base_Address can be:</span>
<span class="co1">//</span>
<span class="co1">//          0x3BC -- LPT1</span>
<span class="co1">//          0x378 -- LPT1</span>
<span class="co1">//          0x278 -- LPT2</span>
<span class="co1">//          0x3BC -- LPT3</span>
<span class="co1">///</span>
&nbsp;
<span class="co1">//We need to reset the Control Port writing a 0</span>
<span class="co1">//to configure their options, controlled for each of</span>
<span class="co1">//their bits:</span>
<span class="co1">///</span>
  outl<span class="br0">(</span>LPT_Base_Address<span class="sy0">+</span><span class="nu0">2</span><span class="sy0">,</span> <span class="nu0">0</span><span class="br0">)</span><span class="sy0">;</span>
&nbsp;
<span class="co1">//Now send an value betwewen 0 and 255 to the data port:</span>
<span class="co1">///</span>
  outl<span class="br0">(</span>LPT_Base_Address<span class="sy0">,</span> <span class="nu12">0xFF</span><span class="sy0">-</span><span class="nu12">0x00</span><span class="br0">)</span><span class="sy0">;</span></pre></div></div>
<h2> <span class="mw-headline" id="See_Also"> See Also </span></h2>
<h3> <span class="mw-headline" id="Threads"> Threads </span></h3>
<ul><li> <a href="http://forum.osdev.org/viewtopic.php?t=30279" class="extiw" title="topic:30279">Easy Parallel Port Programming Tests (Under Windows)</a>
</li></ul>

<!-- 
NewPP limit report
Preprocessor node count: 88/1000000
Post-expand include size: 834/2097152 bytes
Template argument size: 220/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key wikidb:pcache:idhash:2094-0!*!0!!en!2!* and timestamp 20231011104356 -->
</div>				<!-- /bodycontent -->
								<!-- printfooter -->
				<div class="printfooter">
				Retrieved from "<a href="https://wiki.osdev.org/index.php?title=Parallel_port&amp;oldid=27934">https://wiki.osdev.org/index.php?title=Parallel_port&amp;oldid=27934</a>"				</div>
				<!-- /printfooter -->
												<!-- catlinks -->
				<div id="catlinks" class="catlinks"><div id="mw-normal-catlinks"><a href="https://wiki.osdev.org/Special:Categories" title="Special:Categories">Categories</a>: <ul><li><a href="https://wiki.osdev.org/Category:Stubs" title="Category:Stubs">Stubs</a></li><li><a href="https://wiki.osdev.org/Category:Common_Devices" title="Category:Common Devices">Common Devices</a></li><li><a href="https://wiki.osdev.org/Category:Hardware_Interfaces" title="Category:Hardware Interfaces">Hardware Interfaces</a></li></ul></div></div>				<!-- /catlinks -->
												<div class="visualClear"></div>
				<!-- debughtml -->
								<!-- /debughtml -->
			</div>
			<!-- /bodyContent -->
		</div>
		<!-- /content -->
		<!-- header -->
		<div id="mw-head" class="noprint">
			
<!-- 0 -->
<div id="p-personal" class="">
	<h5>Personal tools</h5>
	<ul>
		<li id="pt-login"><a href="https://wiki.osdev.org/index.php?title=Special:UserLogin&amp;returnto=Parallel_port" title="You are encouraged to log in; however, it is not mandatory [alt-o]" accesskey="o">Log in</a></li>
	</ul>
</div>

<!-- /0 -->
			<div id="left-navigation">
				
<!-- 0 -->
<div id="p-namespaces" class="vectorTabs">
	<h5>Namespaces</h5>
	<ul>
					<li id="ca-nstab-main" class="selected"><span><a href="https://wiki.osdev.org/Parallel_port" title="View the content page [alt-c]" accesskey="c">Page</a></span></li>
					<li id="ca-talk"><span><a href="https://wiki.osdev.org/Talk:Parallel_port" title="Discussion about the content page [alt-t]" accesskey="t">Discussion</a></span></li>
			</ul>
</div>

<!-- /0 -->

<!-- 1 -->
<div id="p-variants" class="vectorMenu emptyPortlet">
		<h5><span>Variants</span><a href="https://wiki.osdev.org/Parallel_port#"></a></h5>
	<div class="menu">
		<ul>
					</ul>
	</div>
</div>

<!-- /1 -->
			</div>
			<div id="right-navigation">
				
<!-- 0 -->
<div id="p-views" class="vectorTabs">
	<h5>Views</h5>
	<ul>
					<li id="ca-view" class="selected"><span><a href="https://wiki.osdev.org/Parallel_port">Read</a></span></li>
					<li id="ca-viewsource"><span><a href="https://wiki.osdev.org/index.php?title=Parallel_port&amp;action=edit" title="This page is protected.
You can view its source [alt-e]" accesskey="e">View source</a></span></li>
					<li id="ca-history" class="collapsible"><span><a href="https://wiki.osdev.org/index.php?title=Parallel_port&amp;action=history" title="Past revisions of this page [alt-h]" accesskey="h">View history</a></span></li>
			</ul>
</div>

<!-- /0 -->

<!-- 1 -->
<div id="p-cactions" class="vectorMenu emptyPortlet">
	<h5><span>Actions</span><a href="https://wiki.osdev.org/Parallel_port#"></a></h5>
	<div class="menu">
		<ul>
					</ul>
	</div>
</div>

<!-- /1 -->

<!-- 2 -->
<div id="p-search">
	<h5><label for="searchInput">Search</label></h5>
	<form action="https://wiki.osdev.org/index.php" id="searchform">
		<input type="hidden" name="title" value="Special:Search">
				<input type="search" name="search" title="Search OSDev Wiki [alt-f]" accesskey="f" id="searchInput">		<input type="submit" name="go" value="Go" title="Go to a page with this exact name if exists" id="searchGoButton" class="searchButton">		<input type="submit" name="fulltext" value="Search" title="Search the pages for this text" id="mw-searchButton" class="searchButton">			</form>
</div>

<!-- /2 -->
			</div>
		</div>
		<!-- /header -->
		<!-- panel -->
			<div id="mw-panel" class="noprint">
				<!-- logo -->
					<div id="p-logo"><a style="background-image: url(/skins/common/images/osdev.png);" href="https://wiki.osdev.org/Main_Page" title="Visit the main page"></a></div>
				<!-- /logo -->
				
<!-- navigation -->
<div class="portal" id="p-navigation">
	<h5>Navigation</h5>
	<div class="body">
		<ul>
			<li id="n-mainpage"><a href="https://wiki.osdev.org/Main_Page" title="Visit the main page [alt-z]" accesskey="z">Main Page</a></li>
			<li id="n-portal"><a href="http://forum.osdev.org/" rel="nofollow" title="About the project, what you can do, where to find things">Forums</a></li>
			<li id="n-FAQ"><a href="https://wiki.osdev.org/Category:FAQ">FAQ</a></li>
			<li id="n-OS-Projects"><a href="https://wiki.osdev.org/Projects">OS Projects</a></li>
			<li id="n-randompage"><a href="https://wiki.osdev.org/Special:Random" title="Load a random page [alt-x]" accesskey="x">Random page</a></li>
		</ul>
	</div>
</div>

<!-- /navigation -->

<!-- about -->
<div class="portal" id="p-about">
	<h5>About</h5>
	<div class="body">
		<ul>
			<li id="n-This-site"><a href="https://wiki.osdev.org/OSDevWiki:About">This site</a></li>
			<li id="n-Joining"><a href="https://wiki.osdev.org/OSDevWiki:Joining">Joining</a></li>
			<li id="n-Editing-help"><a href="https://wiki.osdev.org/OSDevWiki:Editing">Editing help</a></li>
			<li id="n-recentchanges"><a href="https://wiki.osdev.org/Special:RecentChanges" title="A list of recent changes in the wiki [alt-r]" accesskey="r">Recent changes</a></li>
		</ul>
	</div>
</div>

<!-- /about -->

<!-- SEARCH -->

<!-- /SEARCH -->

<!-- TOOLBOX -->
<div class="portal" id="p-tb">
	<h5>Toolbox</h5>
	<div class="body">
		<ul>
			<li id="t-whatlinkshere"><a href="https://wiki.osdev.org/Special:WhatLinksHere/Parallel_port" title="A list of all wiki pages that link here [alt-j]" accesskey="j">What links here</a></li>
			<li id="t-recentchangeslinked"><a href="https://wiki.osdev.org/Special:RecentChangesLinked/Parallel_port" title="Recent changes in pages linked from this page [alt-k]" accesskey="k">Related changes</a></li>
			<li id="t-specialpages"><a href="https://wiki.osdev.org/Special:SpecialPages" title="A list of all special pages [alt-q]" accesskey="q">Special pages</a></li>
			<li><a href="https://wiki.osdev.org/index.php?title=Parallel_port&amp;printable=yes" rel="alternate">Printable version</a></li>
			<li id="t-permalink"><a href="https://wiki.osdev.org/index.php?title=Parallel_port&amp;oldid=27934" title="Permanent link to this revision of the page">Permanent link</a></li>
		</ul>
	</div>
</div>

<!-- /TOOLBOX -->

<!-- LANGUAGES -->

<!-- /LANGUAGES -->
			</div>
		<!-- /panel -->
		<!-- footer -->
		<div id="footer">
							<ul id="footer-info">
											<li id="footer-info-lastmod"> This page was last modified on 9 July 2023, at 10:05.</li>
											<li id="footer-info-viewcount">This page has been accessed 39,702 times.</li>
									</ul>
							<ul id="footer-places">
											<li id="footer-places-privacy"><a href="https://wiki.osdev.org/OSDev_Wiki:Privacy_policy" title="OSDev Wiki:Privacy policy">Privacy policy</a></li>
											<li id="footer-places-about"><a href="https://wiki.osdev.org/OSDev_Wiki:About" title="OSDev Wiki:About">About OSDev Wiki</a></li>
											<li id="footer-places-disclaimer"><a href="https://wiki.osdev.org/OSDev_Wiki:General_disclaimer" title="OSDev Wiki:General disclaimer">Disclaimers</a></li>
									</ul>
										<ul id="footer-icons" class="noprint">
					<li id="footer-poweredbyico">
						<a href="http://www.mediawiki.org/"><img src="./Parallel port - OSDev Wiki_files/poweredby_mediawiki_88x31.png" alt="Powered by MediaWiki" width="88" height="31"></a>
					</li>
				</ul>
						<div style="clear:both"></div>
		</div>
		<!-- /footer -->
		<!-- fixalpha -->
		<script type="text/javascript"> if ( window.isMSIE55 ) fixalpha(); </script>
		<!-- /fixalpha -->
		<script src="./Parallel port - OSDev Wiki_files/load(5).php"></script>
<script>if(window.mw){
	mw.loader.load(["mediawiki.user", "mediawiki.util", "mediawiki.page.ready", "mediawiki.legacy.wikibits", "mediawiki.legacy.ajax"]);
}
</script><script type="text/javascript" src="./Parallel port - OSDev Wiki_files/load(6).php"></script>
<script src="./Parallel port - OSDev Wiki_files/load(7).php"></script>
<script>if(window.mw){
	mw.user.options.set({"ccmeonemails":0,"cols":80,"date":"default","diffonly":0,"disablemail":0,"disablesuggest":0,"editfont":"default","editondblclick":0,"editsection":1,"editsectiononrightclick":0,"enotifminoredits":0,"enotifrevealaddr":0,"enotifusertalkpages":1,"enotifwatchlistpages":0,"extendwatchlist":0,"externaldiff":0,"externaleditor":0,"fancysig":0,"forceeditsummary":0,"gender":"unknown","hideminor":0,"hidepatrolled":0,"highlightbroken":1,"imagesize":2,"justify":0,"math":1,"minordefault":0,"newpageshidepatrolled":0,"nocache":0,"noconvertlink":0,"norollbackdiff":0,"numberheadings":0,"previewonfirst":0,"previewontop":1,"quickbar":5,"rcdays":7,"rclimit":50,"rememberpassword":0,"rows":25,"searchlimit":20,"showhiddencats":0,"showjumplinks":1,"shownumberswatching":1,"showtoc":1,"showtoolbar":1,"skin":"vector","stubthreshold":0,"thumbsize":2,"underline":2,"uselivepreview":0,"usenewrc":0,"watchcreations":0,"watchdefault":0,"watchdeletion":0,"watchlistdays":3,"watchlisthideanons":0,
	"watchlisthidebots":0,"watchlisthideliu":0,"watchlisthideminor":0,"watchlisthideown":0,"watchlisthidepatrolled":0,"watchmoves":0,"wllimit":250,"variant":"en","language":"en","searchNs0":true,"searchNs1":false,"searchNs2":false,"searchNs3":false,"searchNs4":false,"searchNs5":false,"searchNs6":false,"searchNs7":false,"searchNs8":false,"searchNs9":false,"searchNs10":false,"searchNs11":false,"searchNs12":false,"searchNs13":false,"searchNs14":false,"searchNs15":false});;mw.user.tokens.set({"editToken":"+\\","watchToken":false});;mw.loader.state({"user.options":"ready","user.tokens":"ready"});
	
	/* cache key: wikidb:resourceloader:filter:minify-js:4:19a4b18a9ac79a6b8c60b24af4668814 */
}
</script><!-- Served in 0.024 secs. -->
	

</body></html>
