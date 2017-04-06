######devices

2/11/2017 10:34 PM

 **pierre** :

 ><@U0B586TUL> no I haven't but let me know if you have it!

2/11/2017 10:34 PM

 **pierre** :

 >I'll probably end up having to figure it out over the next week anyway

2/11/2017 10:45 PM

 **aj** :

 >do you want programmatic setup or GUI setup?

2/12/2017 12:29 AM

 **pierre** :

 >I want to stream raw data through python

2/12/2017 12:29 AM

 **pierre** :

 >I guess programmatic setup?

2/12/2017 12:29 AM

 **pierre** :

 ><@U0B586TUL> ^

2/12/2017 12:59 AM

 **aj** :

 >Most brute force way is the example in interfacing with other tools in the node js ganglion repo

2/12/2017 1:00 AM

 **aj** :

 >If you want more sophisticated see the Python example in the Cyton aka `OpenBCI_NodeJS`

2/12/2017 2:57 AM

 **pierre** :

 >Ah okay great thanks, will look into it

2/12/2017 10:15 AM

 **alexandre.barachant** :

 ><@U073X4JRL> will LSL streaming works for you ? i adapted the LSL example of `OpenBCI_NodeJS` for the ganglion. i can send you the files

2/20/2017 4:12 PM

 **sydneyneurotechx** :

 >Only thing that is inaccurate in the article is that the material has been around for a while. It's just being used in a different use case.

2/22/2017 5:24 AM

 **pierre** :

 >Hey <@U0AJ51TKJ>, I tried your LSL code and it worked very well! Thanks!

2/22/2017 8:40 AM

 **alexandre.barachant** :

 >sweet

2/22/2017 5:36 PM

 **benjamindeleener** :

 ><!channel> has anyone had difficulties connecting the OpenBCI Gui to the Cython on Mac OS X Sierra? The software doesnt seem to detect the board. It is working on Mac OS X El Capitan, with the same installation (Driver and Gui)

2/22/2017 6:19 PM

 **benjamindeleener** :

 >Its working when I moved the OpenBCI_GUI application into the application folder. Some stuff seem to have changed in Sierra. Happy that it is working though!

2/28/2017 9:04 PM

 **stephen** :

 >List of all ECG devices one can wear: <https://forum.quantifiedself.com/t/reliable-wearable-ecg/2653>

3/3/2017 1:50 AM

 **jfrey** :

 ><@U073X4JRL>: if you still want give ganglion + python a try (...and if you are a linux-powered guy), it's getting easier: <http://openbci.com/forum/index.php?p=/discussion/1017/ganglion-board-now-working-with-python-on-linux>

3/3/2017 6:12 AM

 **pierre** :

 >I'm still on the lookout for pure Python solutions though

3/7/2017 3:00 PM

 **physionikhil** :

 >hi i am trying to develop an eeg controlled electrical stimulation device for stroke patients , can anyone advise me on the hardware and assembly

3/7/2017 3:26 PM

 **sydneyneurotechx** :

 >Hi physionikhil. Do you have an idea of where you want to place the electrodes and the type of stimulation you would like to do?

3/7/2017 4:30 PM

 **physionikhil** :

 >Yes , for the muscle stimulation I want to place the Electrodes on the extensor compartment of forearm and for the leg region I want to place on the front of the thigh and just below the knee outside the shin bone, usually a interrupted galvanic current is used with a 9V medically approved stimulator

3/7/2017 9:09 PM

 **aj** :

 >Hey I'm gonna have 2 Wifi Shields for OpenBCI Cyton. Anyone interested in one? It's plug and play with an over the air update to the OpenBCI 32bit Cyton board.

3/7/2017 9:35 PM

 **sydneyneurotechx** :

 >physionikhil: For the EEG component, how many electrodes will you be using?

3/8/2017 12:42 AM

 **physionikhil** :

 >For EEG 8 Electrode system

3/8/2017 2:50 AM

 **physionikhil** :

 >Anyone interested to sell cyton board?

> 


3/8/2017 2:56 PM

 **sydneyneurotechx** :

 >And the electrode montage will primarily be in the C location? Also, out of curiosity is there any ethical dilemmas in doing this project? Do you have University approval or is it not required?

3/12/2017 5:25 AM

 **physionikhil** :

 >Yes that can work as well but fronto parietal locations will be better suited for it in my opinion. I am a private clinician and we already have patients with stroke and movement dysfunction. We will be taking written consents from our therapy clients and even now we have their verbal consent. I don't think there should be any ethical dilemma in this kind of study. If we could develop a working prototype of it I will be able to get a University approval where I am teaching

3/13/2017 11:17 PM

 **sydneyneurotechx** :

 >To view archived text from Slack please visit:

> 
<https://github.com/NeuroTechX/ntx_slack_archive/blob/master/devices.md>

3/14/2017 3:35 AM

 **physionikhil** :

 >Cheap cranial stimulation device from China, not sure how authentic it is as it doesnt specify any technical info

> 


> 
<https://f2rq3.app.goo.gl/?link=https%3A%2F%2Fm.alibaba.com%2Fproduct%2F60315578379%2FHaobro-design-electric-brain-stimulate-device.html&amp;apn=com.alibaba.intl.android.apps.poseidon&amp;ibi=com.alibaba.sourcing&amp;isi=503451073&amp;amv=69>

3/17/2017 4:14 PM

 **octonomy** :

 >Has anyone experienced an issue with openBCI dropping every other sample? I have a 16 channel kit but running it in 8 channel mode. Wondering if it's a limitation of the board (like you have to take off daisy while running in 8 channel mode). Looking it up on openBCI forum now but thought I'd ask you all here too

3/17/2017 4:16 PM

 **yrenard** :

 >No you can ask the 8 channels of the OpenBCI without removing the daisy board

3/17/2017 4:16 PM

 **yrenard** :

 >It must be deactivated though

3/17/2017 4:16 PM

 **yrenard** :

 >and this has an impact on the sampling rate

3/17/2017 4:16 PM

 **yrenard** :

 >You would receive twice as much samples from the board than what you would receive if the daisy module was activated

3/17/2017 5:48 PM

 **octonomy** :

 >Do you know the procedure to deactivate it? Is it a command line option or a physical hardware switch?

3/17/2017 5:49 PM

 **octonomy** :

 >Right it is 250hz for 8channel and 125 for 16channel. I was hoping I could just switch between those by specifying correct device

3/17/2017 5:50 PM

 **yrenard** :

 >It is a command that you send through the BT protocol

3/17/2017 5:50 PM

 **octonomy** :

 >Ok I see 

3/17/2017 5:50 PM

 **yrenard** :

 >Let me check the OpenViBE driver

3/17/2017 5:50 PM

 **octonomy** :

 >I'll look that up. Thanks for confirming, it's kind of a hard thing to search for in openBCI forum

3/17/2017 5:53 PM

 **yrenard** :

 >So sending `c` should do the trick

3/17/2017 5:55 PM

 **yrenard** :

 >Btw, you should find it in the documentation - But I needed to read it once to understand how to search in it :wink:

3/17/2017 5:57 PM

 **yrenard** :

 >You need to look at this page specifically <http://docs.openbci.com/OpenBCI%20Software/04-OpenBCI_Cyton_SDK>

3/19/2017 12:02 AM

 **octonomy** :

 >Thank you!!

3/22/2017 1:54 AM

 **a.tech** :

 >Has anyone tried printing an UltraCortex using a flexible filament like (TPE or TPU) instead of ABS or PLA? 

> 


> 
Maybe it'll get better contact or be more comfortable if the helmet had some flex to it?

3/22/2017 1:55 AM

 **a.tech** :

 >Im ordering in some filament right now so I thought I'd ask haha

3/22/2017 3:44 AM

 **sydneyneurotechx** :

 >conor  Showed me some prototype with ninja flex I believe. Unsure of the results though

3/22/2017 3:52 AM

 **sydneyneurotechx** :

 >irene.viguix  May have an answer for you

3/22/2017 2:27 PM

 **yannick** :

 >hey jmhorschig do you have an idea of the price range for the OctaMon device?

> 
<http://www.artinis.com/octamon/>

> 
We were having a discussion about the price range of portable fNIRS devices recently.

3/22/2017 6:54 PM

 **aj** :

 >anyone know have experience with MQTT?

3/22/2017 6:55 PM

 **aj** :

 >i've seen and held one

3/23/2017 8:20 PM

 **harris** :

 >Is there any software to use with openBCI that is like emotiv's where you can do command recognition

3/23/2017 8:57 PM

 **sydneyneurotechx** :

 >Like Keyboard control?

3/23/2017 8:59 PM

 **sydneyneurotechx** :

 >If so, you could potentially with OpenVibe

3/23/2017 9:00 PM

 **sydneyneurotechx** :

 ><http://openbci.com/forum/index.php?p=/discussion/475/moving-the-cursor-via-openvibe-ongoing-tutorial-for-beginners>

3/23/2017 9:05 PM

 **harris** :

 >How much work needs to be done with OpenVIBE to achieve something similar to Emotiv's kit?

3/24/2017 7:52 AM

 **jmhorschig** :

 >yannick: sure I have, I am working here ;) the whole industry is hesitant with making their prices publicly available though (not sure why, we all know what prices of competitors are anyway), and it varies per country Think of something around 20k$.

3/24/2017 12:21 PM

 **yannick** :

 >jmhorschig yeah, we had a similar conversation few months ago about some EEG (research) devices not showing their prices but offering a "Get a Quote" button. (e.g. Cognionics)

3/24/2017 12:21 PM

 **yannick** :

 >Thanks for the price range!

3/24/2017 12:35 PM

 **jmhorschig** :

 >Generally with EEG research devices, it's about 500$ per channel up until 32ch, and then 250$ per additional channel up until 64ch, and from then on ~125$ per channel ( i.e. 8ch is 4k$, 32ch ~16k$, 64ch ~24k$, 128ch ~32k$, 256ch ~48k$). Just rough estimates though, differs a bit per company. It's a bit stupid that it's so secretive, but that's the market...

3/24/2017 3:42 PM

 **sydneyneurotechx** :

 >yrenard Any ideas?

3/24/2017 3:58 PM

 **yrenard** :

 >I would say reading the tutorials mainly, to understand the underlying of a BCI process (preprocess, feature extraction, modeling and feedback pipeline basically) - Everything is in the software to let you do pretty much the same as Emotiv's EmoKey

3/24/2017 3:58 PM

 **yrenard** :

 >Say 2 days of reading and messing around with the software and you should be good to build what you need

3/31/2017 6:13 AM

 **pierre** :

 >Anybody know the status of this and similar open TMS projects? 

> 
<http://open-rtms.sourceforge.net/>

3/31/2017 12:08 PM

 **yannick** :

 ><http://www.neuroelectrics.com/products/caps/headcap-cover-r>

> 
Adding a Faraday shielding over the EEG cap. Interesting...

3/31/2017 2:59 PM

 **aj** :

 >Lit

3/31/2017 3:12 PM

 **physionikhil** :

 >This is great

4/1/2017 12:13 PM

 **yannick** :

 >Looking forward to see the signal from:

> 
<https://www.youtube.com/watch?v=5CZtoYbfbHU>

4/2/2017 11:05 PM

 **harris** :

 >yannick are those glasses at the end the supposed product?

4/2/2017 11:06 PM

 **yannick** :

 >Yup, the new InteraXon's device. (you can kinda recognize the Muse behind the ear electrodes)

4/2/2017 11:06 PM

 **harris** :

 >'Lowdown Focus Mpowered by Muses frames includes brainwave-sensing EEG, EOG and EMG technology as well as other sensors, including a 3-axis accelerometer, a 3-axis gyro, a 3-axis magnetometer, a UV sensor (UVA and UVB), a temperature gauge and a pressure sensor, providing a rich upgrade path for applications via an open SDK.'

4/3/2017 3:08 AM

 **octonomy** :

 >what i want is to start an eeg modeling agency

4/3/2017 3:19 AM

 **sydneyneurotechx** :

 >Neat cap. What is  Spacer and silver fabric? Anyone have any ideas? Can't find much online.

4/4/2017 6:15 AM

 **sydneyneurotechx** :

 >For those interested. japesinator  created at TDCS Badge for Cyphercon (Hacker conference in Wisconsin). It is functional (tried it on myself). I did a simple optic nerve stimulation and it created beautiful phosphenes.

> 


> 
All hail Electric Cthulhu!

4/6/2017 4:19 PM

 **octonomy** :

 >hello, does anyone on here use an openbci with daisy module? wondering if i have the wires hooked up correctly

4/6/2017 4:20 PM

 **octonomy** :

 >im seeing weirdness, quite high voltage readings (range of ~2000uv) and every channel is identical, which im pretty sure is not supposed to happen

4/6/2017 4:23 PM

 **octonomy** :

 >My connections are like this:

> 
All electrodes on bottom row of both boards 

4/6/2017 4:25 PM

 **octonomy** :

 >Including the GND (connected bottom row on bottom board) and the SRB (connected bottom pins on both boards - to a y-connector)

4/6/2017 4:35 PM

 **sydneyneurotechx** :

 >Does it work correctly without the Daisy module? octonomy ?

4/6/2017 4:41 PM

 **octonomy** :

 >yes, without the daisy its great

