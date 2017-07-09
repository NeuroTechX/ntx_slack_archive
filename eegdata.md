######eegdata

2/8/2017 1:01 AM

 **andyh616** :

 >:clap: :metal:

2/8/2017 1:02 AM

 **yannick** :

 >:ntx2:

2/8/2017 7:03 PM

 **stephen** :

 ><http://www.openmhealth.org/documentation/#/overview/get-started>

2/8/2017 7:03 PM

 **stephen** :

 ><http://www.openmhealth.org/>

2/8/2017 7:04 PM

 **stephen** :

 >Anyone familiar with this mobile health data open source framework ?

2/8/2017 10:39 PM

 **jaymutzafi** :

 >You folks seen this? <https://medicalxpress.com/news/2017-02-advanced-eeg-analysis-reveals-complex.html>

> 
Can this be applied programmatically?

2/9/2017 4:41 AM

 **joeyo** :

 >lol. Multitaper methods aren't exactly new for field potential analysis. But perhaps they havent been used clinically yet?

2/9/2017 6:00 AM

 **pierre** :

 >Yeah multitaper isn't very new, but their results are pretty cool 

2/9/2017 6:01 AM

 **pierre** :

 >Haven't seen much EEG sleep multitapers but it looks really consistent 

2/21/2017 11:15 AM

 **firassafieddine** :

 >hello

> 


> 
I am currently trying to extract data from an epoc emotic 14 channel eeg headset , I am having some trouble being able to extract the data stream

> 
Any suggestions?!

2/21/2017 3:32 PM

 **ray_cassani** :

 >yes it is: <https://github.com/bcimontreal/bci_workshop>

2/21/2017 3:44 PM

 **firassafieddine** :

 >thanks alot

2/27/2017 7:55 PM

 **mpontais** :

 >Hey there! I'm trying to make electronic structures respond to data given by an Emotiv Epoc headset, and I'm facing some troubles.. I'm for now using MindyourOscs, through Processing, then sending the signals to Arduino. It works for facial recognition features, but does not respond when I call affective functions (Excitement/Meditation/Frustration/...) which are the ones I'm interested about! 

> 
Did someone know about this issue? And is there a "known" solution? Else I'm not really familiar with the Emotiv Epoc, so would there be a better/quicker/easier way to be able to program microcontrollers according to the EEG data other than the Processing/Arduino interface? 

> 
Thanks a lot!

2/28/2017 3:12 PM

 **natanel** :

 >hola!

> 
does anyone here has eeg readings of febromealgia vs healthy patients?

> 
can i get some of that? :slightly_smiling_face:

2/28/2017 3:45 PM

 **mpontais** :

 >Oh sorry I just realized I miss read your post as a question! Um I've never use Unity but I heard a lot about it for VR. Can you also control other electronic structures than a VR headset with it?

2/28/2017 4:03 PM

 **bhargava2566302** :

 >If u want u can pm

3/2/2017 10:21 PM

 **alexandre.barachant** :

 ><http://alexandre.barachant.org/blog/2017/03/02/Hands-on-OpenBCI-Ganglion.html>

3/3/2017 4:10 PM

 **alexandre.barachant** :

 >indeed. In terms of signal quality, the muse is good. with optimal electrode placement i have no doubt AUC would get better

3/3/2017 4:58 PM

 **melanie** :

 >can anyone point me in the direction of a tutorial for doing ICA on resting state EEG data? I can only seem to find things for erp paradigms.

3/3/2017 5:00 PM

 **melanie** :

 >(worth noting that I'm not even sure my question makes sense)

3/3/2017 5:53 PM

 **qbarthelemy** :

 >you can look at MNE

> 
<http://martinos.org/mne/dev/manual/preprocessing/ica.html>

3/3/2017 6:09 PM

 **melanie** :

 >qbarthelemy: thanks - can't seem to find anything on how to use their ICA package without having a stimulus file. Currently just using the sklearn ica package. It seems to be working (ish) :slightly_smiling_face:

3/3/2017 7:45 PM

 **yrenard** :

 >melanie also there exist different ways of doing ICA ; ICA is a family of methods and you should be neet picky as to which one suits your problem and its apriori parameters the best

3/3/2017 7:51 PM

 **qbarthelemy** :

 >I do agree. FastICA is not the best one...

3/3/2017 7:55 PM

 **yrenard** :

 >:wink:

3/3/2017 8:04 PM

 **hectordomorozco** :

 >yrenard can you point us to some resources as to fully understand this? :slightly_smiling_face:

3/3/2017 8:09 PM

 **yrenard** :

 >you should start with the wikipedia page I guess, this already mentions quite a few different techniques

3/3/2017 8:25 PM

 **qbarthelemy** :

 >Arnaud Delorme has an excellent paper on BSS methods

> 
<http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0030135>

3/3/2017 9:38 PM

 **hectordomorozco** :

 >Thanks

3/6/2017 7:56 PM

 **sydneyneurotechx** :

 >alexandre.barachant  Did you make your own EEG cap?

3/6/2017 7:56 PM

 **alexandre.barachant** :

 >yep

3/6/2017 7:57 PM

 **sydneyneurotechx** :

 >Do you have any tutorials on building one? :stuck_out_tongue:

3/6/2017 7:59 PM

 **alexandre.barachant** :

 >not really, i took some picture and planned to make a tutorial back when i built it (summer 2016) but it was not that usefull since the offset of the electrode was too big for the OpenBCI board.

> 
Now it is compatible with the ganglion so i might do it

3/6/2017 8:00 PM

 **alexandre.barachant** :

 >however, i'm not 100% satisfied with the electrodes, confortwise

3/6/2017 8:03 PM

 **alexandre.barachant** :

 >AJ made a video of assembling the electrodes : <https://www.youtube.com/watch?v=kgNdJGsjy-Q>

3/6/2017 8:04 PM

 **alexandre.barachant** :

 >the rest is just a swim cap and a hot glue gun :slightly_smiling_face:

3/6/2017 11:08 PM

 **sydneyneurotechx** :

 >Where did you get those electrodes?

3/7/2017 7:30 AM

 **physionikhil** :

 >can any one help me with the hardware part for making an eeg controlled electrical muscle stimulation device

3/7/2017 9:01 AM

 **alexandre.barachant** :

 >sydneyneurotechx  this is my own design. There a link with the video with instruction to oder components (PCB + pogo pins)

3/10/2017 11:10 AM

 **octonomy** :

 >hi everybody, long time no see. hope youre all doing well in your work as spring arrives.

> 
I have a sklearn question to ask. Has anyone tried to use the sklearn TimeSeriesSplit instead of the more common StratifiedKFold() or test_train_split() cross-eval methods?

> 


> 
<http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.TimeSeriesSplit.html>

3/10/2017 11:12 AM

 **octonomy** :

 >Im trying to understand, from high level, if this is going to be problematic for EEG epochs data? It is a weird concept: 

> 
"Note that unlike standard cross-validation methods, successive training sets are supersets of those that come before them.

> 


> 
Here is example of what happens with this split:

> 
```

> 
&gt;&gt;&gt; from sklearn.model_selection import TimeSeriesSplit

> 
&gt;&gt;&gt; X = np.array([[1, 2], [3, 4], [1, 2], [3, 4]])

> 
&gt;&gt;&gt; y = np.array([1, 2, 3, 4])

> 
&gt;&gt;&gt; tscv = TimeSeriesSplit(n_splits=3)

> 
&gt;&gt;&gt; print(tscv)  

> 
TimeSeriesSplit(n_splits=3)

> 
&gt;&gt;&gt; for train_index, test_index in tscv.split(X):

> 
...    print("TRAIN:", train_index, "TEST:", test_index)

> 
...    X_train, X_test = X[train_index], X[test_index]

> 
...    y_train, y_test = y[train_index], y[test_index]

> 
TRAIN: [0] TEST: [1]

> 
TRAIN: [0 1] TEST: [2]

> 
TRAIN: [0 1 2] TEST: [3]

> 
```

3/10/2017 11:12 AM

 **octonomy** :

 >so your train sets are gradually increasing. its like each test fold is trained with X cumulative up to the y.

3/10/2017 11:14 AM

 **alexandre.barachant** :

 >This is an interesting split that keep time structure. 

> 
I generally use K-Fold when i don't shuffle, but this one will make sure you don't train with data that will be recorded after your test set.

3/10/2017 11:15 AM

 **alexandre.barachant** :

 >this is a cool validator for benchmarking the number of trial to use in a realistic setup

3/10/2017 11:16 AM

 **octonomy** :

 >yes i never notice it before, but not sure its new to 0.18

3/10/2017 11:16 AM

 **alexandre.barachant** :

 >yes, it's new

3/10/2017 11:16 AM

 **alexandre.barachant** :

 >they rewrote the cross validation API

3/10/2017 11:16 AM

 **octonomy** :

 >yeah i saw that. with this model_selection package

3/10/2017 11:16 AM

 **octonomy** :

 >its good

3/10/2017 11:17 AM

 **alexandre.barachant** :

 >they have also GroupKFold or LeaveOneGroupOut that is very usefull for cross-subject, session

3/10/2017 11:20 AM

 **octonomy** :

 >yes ive been struggling with the kfolds. im able to keep my train and test separate just fine for final analysis, but within the gridsearch step in training, where one might further split into train/validation, i end up using CV, and am worried that train data is overfitting by being mixed with validation folds because they are close in time proximity.

3/10/2017 11:23 AM

 **octonomy** :

 >hm no, actually im cropping epochs, so its not like sampling randomly from a continuous time series. sorry, just thinking out loud.

3/10/2017 11:54 AM

 **octonomy** :

 >one problem with the TimeSeriesSplit I guess is that it is mixing times series information from different classes?  for example: in the example above, if X[0] and X[2] were class 1, and X[1] and X[3] were class 2, then:

> 
```

> 
[0] -&gt; class 1

> 
[0, 1] -&gt; class 2

> 
[0,1,2] -&gt; class 1

> 
[0,1,2,3] -&gt; class 2

> 
```

> 
this seems not good. must be some other use case where this split is useful, but maybe not already epoched EEG.  seems like this would be useful where cumulative past time series leads to current class label.

3/13/2017 11:18 PM

 **sydneyneurotechx** :

 >To view archived text from Slack please visit:

> 
<https://github.com/NeuroTechX/ntx_slack_archive/blob/master/eegdata.md>

3/15/2017 10:56 AM

 **omer** :

 >Yeaa probably, we use this kind of ful  night spectrals in our lab for years also in publications. I guess it just new for the clinic, you don't really need multitaper for that...

3/15/2017 10:57 AM

 **omer** :

 >you can build one yourself

3/16/2017 9:16 AM

 **dojeda** :

 >Hey, is anyone currently saving EEG data on a distributed database (i.e. opentsdb, hbase, etc)? I am wondering how performant (or not) this is.

> 
When you read about "time series analysis" around the web, where the time series are stored in some sort of database, examples are mostly with series whose Fs &gt;&gt; 1Hz, but in EEG we are generally interested in &gt;128Hz. OpenTSDB, for instance, has a warning on their frequently asked questions:

> 
&gt; Can I store sub-second precision timestamps in OpenTSDB? As of version 2.0 you can store data with millisecond timestamps. However we recommend you avoid storing a data point at each millisecond as this will slow down queries dramatically.

3/16/2017 10:16 AM

 **pierre** :

 >marion w have done this in cloudbrain

3/16/2017 7:06 PM

 **firassafieddine** :

 >hello everyone,

> 


> 
Im trying to figure out what each of the sensors of the emotiv epoc 14 channels sense:

> 


> 
AF3, AF4, F3, F4, FC5, FC6, F7, F8, T7, T8, P7, P8, O1, O2

> 


> 
anything about that ?

3/16/2017 7:09 PM

 **yrenard** :

 >firassafieddine ^^ <http://www.mariusthart.net/downloads/eeg_electrodes_10-20.svg>

3/16/2017 7:09 PM

 **yrenard** :

 >and <https://en.wikipedia.org/wiki/10-20_system_(EEG)>

3/16/2017 7:11 PM

 **firassafieddine** :

 >looks helpful! thanks yrenard  Im trying to find what each one of these sensors get

3/16/2017 7:31 PM

 **yannick** :

 >firassafieddine There is no "simple" answer to your question. Perhaps reading a little more on EEG (<https://en.wikipedia.org/wiki/Electroencephalography>) would help refine your question?

3/17/2017 4:32 AM

 **sydneyneurotechx** :

 >firassafieddine The best answer as to what each of the electrodes will get, is dependent on the type of task you are looking to measure. There are a variety of types of brain signals that you can acquire with an eeg(For example your emotiv). for example you can look at Neural Oscillations (more commonly known as brain waves) or Event Related Potentials, which is where you measure the brains response to some form external or internal stimulation. iMotions has a great pdf which explains the basic of eeg (If you find the wiki article overwhelming). I'd also looking at their pdf on experimental design as it's good idea to follow an experimental procedure when trying to acquire eeg signal

3/17/2017 5:31 AM

 **physionikhil** :

 >Does any one know about an affordable and portable Nirs device for measure cerebral oxygenation in stroke patients after physical therapy interventions including conditioning exercises

3/18/2017 9:19 AM

 **a.tech** :

 >physionikhil 

> 
You might like to look at

> 
<https://www.biopac.com/application/fnir-functional-near-infrared-optical-brain-imaging/>

3/18/2017 10:58 AM

 **physionikhil** :

 >a.tech hi thnx for the info for Biopac. Do u have an idea how much their system cost. I also searched about artinis oxymon Fnirs device. Yet to get a quote from them

3/18/2017 1:39 PM

 **sydneyneurotechx** :

 >The cheapest consumer NIRS I found was 2 thousand by Hitachi. Not sure if you can find cheaper or not

3/18/2017 2:16 PM

 **physionikhil** :

 >2000$? Their units go over 500k I think

3/18/2017 2:20 PM

 **physionikhil** :

 >Artinis have another by the name porta lite , not sure how reliable it is

3/18/2017 2:20 PM

 **yannick** :

 >Nan they do have a "consumer" version they presented last year

3/18/2017 2:21 PM

 **yannick** :

 ><http://www.hitachi-hightech.com/global/about/news/2016/nr20160224.html>

3/18/2017 2:21 PM

 **physionikhil** :

 >yannick thnx let me check

3/18/2017 2:23 PM

 **physionikhil** :

 >yannick any experience with artinis octamon or portalite for Nirs studies?

3/18/2017 2:34 PM

 **yannick** :

 >No, sorry :disappointed:

3/18/2017 2:40 PM

 **physionikhil** :

 >Ok

3/18/2017 4:11 PM

 **nedack** :

 >physionikhil I'm using Nirsport made by NIRX (<https://nirx.net/nirsport/>) and my supervisor told me it costs around 30k¬. Also, I know Biopac sell a fNIRS system at 19000 ¬ HT in France but i don't remember if it's the fNIR100 or other

3/19/2017 11:26 AM

 **physionikhil** :

 >nedack thank you, may I know what are your applications for fNIRS system

3/19/2017 2:20 PM

 **nedack** :

 >physionikhil Yeah, I'm working on the assessment of the mental workload in flight condition

3/19/2017 3:06 PM

 **physionikhil** :

 >nedack great

3/20/2017 3:18 PM

 **eferdinand** :

 >any recommendation for reading ECG from the forehead?

3/20/2017 4:48 PM

 **alexandre.barachant** :

 >you can read ECG everywhere as long as the reference electrode and the signal electrodes are far away.

> 
so if you can only place electrodes on the forehead that will be tricky

3/20/2017 6:15 PM

 **mkos** :

 >Hi, I am interested in buying Muse 2016 for my research project. I found some inconsistencies on Muse's website and I am wondering if the following are available for Muse 2016?

> 
a) MuseIO,

> 
b) MuseLab,

> 
c) MusePlayer.

3/20/2017 6:48 PM

 **amilenkovic** :

 >I believe Muse are still working on updating the SDK to support the Muse 2016 hardware, though I hope someone will correct me if that information is out of date

3/20/2017 6:49 PM

 **amilenkovic** :

 >if you are looking for a solution to access EEG data on a Muse 2016, there's an app called MuseMonitor on both Android / iOS that works quite well and lets you pair the muse to a phone or tablet, as well as get the full data in CSV / Zip / stream to an OSC server

3/20/2017 6:50 PM

 **amilenkovic** :

 >There are also some ways to get a muse 2016 working in Linux apparently, though I haven't tried them since I have a 2014

3/20/2017 8:46 PM

 **mkos** :

 >oh, very useful! thank you amilenkovic !

3/20/2017 8:46 PM

 **mkos** :

 >So for now, the safest bet would be to get the older hardware, correct?

3/20/2017 10:53 PM

 **sydneyneurotechx** :

 >Older hardware will work, but from my understanding the 2016 hardware should work just fine with those three applications  mkos . Correct me if I'm wrong graeme

3/20/2017 10:57 PM

 **graeme** :

 >That's right, and we're working on an update to the research tools for Windows, which will work with all the Muses (and be more awesome in general) 

3/21/2017 12:38 AM

 **mkos** :

 >graeme - nice but I want to ran a pilot next month :slightly_smiling_face:

3/21/2017 12:41 AM

 **graeme** :

 >you can easily stream eeg data from Muse Monitor right now (also via MuseLab) then forward it to wherever you want. That will only create challenges if you're looking for low-latency responses because of the network latency

3/21/2017 9:13 AM

 **alexandre.barachant** :

 >mkos On linux, you can use my code : <https://github.com/alexandrebarachant/muse-lsl>

> 
It can works on windows/mac but you need a special dongle and patching the pygatt python library

3/21/2017 1:47 PM

 **mkos** :

 >excellent - I like linux :slightly_smiling_face: thanks! alexandre.barachant

3/21/2017 1:53 PM

 **alexandre.barachant** :

 >mkos you can read more on my blog : <http://alexandre.barachant.org/blog/2017/01/27/reverse-engineering-muse-eeg-headband-bluetooth-protocol.html>

3/22/2017 3:44 AM

 **pierre** :

 >I'm not quite sure where to post this, but you can get attention through cross-brain correlations with the OpenBCI ganglion!

3/22/2017 3:44 AM

 **pierre** :

 >I led a lab on this today, and everyone got it to work and got interesting results

3/22/2017 3:44 AM

 **pierre** :

 >I feel it has a lot of promise

3/22/2017 3:45 AM

 **pierre** :

 >here's a reference: <https://github.com/NeurotechBerkeley/bci-course/tree/master/lab7>

3/22/2017 3:48 AM

 **pierre** :

 >we placed the electrodes in frontal and temporal, so it should be doable with muse, but I'm guessing you guys are already aware of this

3/22/2017 5:58 AM

 **lemiesz** :

 >Hi everyone, im new to this but it all sounds really interesting. 

> 
Anyone have any resources I could read, to help introduce me to Muse/EEGs/Neurofeedback

3/22/2017 7:01 AM

 **physionikhil** :

 >lemiesz u can check this out

3/22/2017 1:15 PM

 **sydneyneurotechx** :

 >lemiesz You can take a look at our awesome BCI page. It has a non-exhaustive list of resources to help you get started.

3/22/2017 1:15 PM

 **sydneyneurotechx** :

 >We are also working on NeurotechEDU and content should be ready soon for that.

3/22/2017 6:52 PM

 **dano** :

 >pierre that looks really cool! I'll see if we can get a replication with the Muse at one of our TO hacknights

3/22/2017 6:52 PM

 **pierre** :

 >dano that'd be awesome, let me know how it goes!

3/22/2017 7:00 PM

 **pierre** :

 >Feel free to message me if you have any questions or concerns

3/23/2017 1:02 AM

 **graeme** :

 >pierre that is really slick

3/23/2017 1:03 AM

 **bhargava2566302** :

 >graeme: hey i need a help with you guys

3/23/2017 1:03 AM

 **bhargava2566302** :

 >When i uploading an app that uses muse its asking for some id can you just how can i get it

3/23/2017 1:04 AM

 **graeme** :

 >send me an email at moffat at interaxon dot ca

3/23/2017 5:27 AM

 **lemiesz** :

 >Thanks guys

3/23/2017 5:27 AM

 **lemiesz** :

 >So the way I understand it, MuseIO does not work with the current headband right now

3/23/2017 6:25 AM

 **franko** :

 >Hello, any reviews on Emotiv Insight? Need something for brain work analysis during working hours. Is it accurate?

3/23/2017 12:12 PM

 **sydneyneurotechx** :

 >I don't see why it wouldn't. How did you come to that conclusion?

3/23/2017 8:27 PM

 **igweckay** :

 >Has anyone connected Emotiv with Processing.js ? 

3/24/2017 8:02 AM

 **rimsmb** :

 >Hi,

> 
try this application with your device (for Muse2016) to read and save the signals from Muse2016, it is the only solution until now <https://play.google.com/store/apps/details?id=com.myr.mymuse2017>

3/24/2017 8:29 PM

 **graeme** :

 >lemiesz you can use Muse Monitor as a substitute for MuseIO if you're using the 2016 headband. It can output an osc stream in the same way MuseIO does.

3/26/2017 10:30 PM

 **maxim** :

 >By the way, you can use official Muse test application as well. It will save all the data in the file in sdcard, that file can then be saved and analyzed (if there is no need for realt-time interaction)

3/27/2017 10:29 PM

 **danbaker** :

 >lemiesz I believe thats correct - I had purchased a 2016 band but it doesnt work with latest bluetooth LE or whatever it is, so I had to return it and use the 2015 model

3/28/2017 4:38 PM

 **d.adamos** :

 >Hi all,  an event synchronization tutorial between OpenSesame open-source experiment builder and Emotiv EEG Testbench is provided in our Groups web page: <http://neuroinformatics.gr/node/37>

4/2/2017 6:52 PM

 **dano** :

 >Anyone interested in recording data from a Muse headset can now use EEG 101 to do so! We skip the .muse format and go straight to simple, legible CSVs

> 
<https://play.google.com/store/apps/details?id=com.eeg_project&amp;hl=en>

4/2/2017 11:40 PM

 **sydneyneurotechx** :

 >dano  I'd suggest include a sample Muse dataset for the eeg 101 tutorial for people that don't have the Muse

4/2/2017 11:40 PM

 **sydneyneurotechx** :

 >It would also help for when I'm talking at events about your projects :stuck_out_tongue:

4/2/2017 11:43 PM

 **dano** :

 >But.. who's brain? What should they be doing? So many questions get raised everytime I ponder offline mode! :open_mouth:

4/3/2017 12:22 AM

 **sydneyneurotechx** :

 >Your brain!

4/3/2017 12:22 AM

 **sydneyneurotechx** :

 >My brain!

4/3/2017 12:23 AM

 **sydneyneurotechx** :

 >I volunteer my brain

4/5/2017 2:51 AM

 **octonomy** :

 >My dear Mr. alexandre.barachant , a small question for you. I have been using the pyRiemann lib (which is excellent,, thank you for this gift), and noticed it seems to frequently come back with the `ValueError: array must not contain infs or NaNs` error.

> 


> 
I try the `cov_data_train = np.nan_to_num(cov_data_train)` right before clf_mdm.fit(), but doesnt help. 

> 


> 
Is there any chance theres something in the code a bit deeper that might cause the dreaded Nan/Inf?

4/5/2017 5:58 AM

 **yrenard** :

 >octonomy: the number one reason is if your input signal, for any reason, has inf or nan numbers. You can check your epochs with `np.all(np.isfinite())` and validate that this input is always numeric

4/5/2017 5:59 AM

 **yrenard** :

 >the number two reason is that the rank of your matrices is not up to the number of channels (which means you lost a degree of freedom, e.g. by referencing all channels to the common average)

4/5/2017 6:00 AM

 **yrenard** :

 >in order to avoir that, you should ensure that the rank of your matrices is equal to the number of channels you have (use `np.linalg.rank` to get this), or reduce the matrices by dropping some channels that can be reconstructed as a linear combination of other channels

4/5/2017 6:01 AM

 **yrenard** :

 >if you referenced to common average, just drop any of your input channels before sending them to pyriemann

4/5/2017 11:49 AM

 **alexandre.barachant** :

 >octonomy: yrenard got it right. this error usually happens when you have rank deficient matrices. This is the case when applying an average reference, or when the number of time sample in your covariance window is lower than the number of channels. To fix that, disable average refrence (older version of MNE set it by default), increase your window size, or add regularization during the estimation.

4/5/2017 11:50 AM

 **alexandre.barachant** :

 >Note that i suggest you to work from the github version of the toolbox. I recently added some more explicit error message for this problem

4/5/2017 11:53 AM

 **alexandre.barachant** :

 >I plan to release a new version in the next couple of weeks

4/5/2017 12:30 PM

 **octonomy** :

 >thanks so much yrenard and alexandre.barachant for the clues. yrenard i did put in this check you mention `np.isfinite()` right before the call to `fit()` and the data is ok, so its something further down inside the fit() call that further transforms my input data to result with nan/inf

4/5/2017 12:31 PM

 **alexandre.barachant** :

 >yes, the problem is not input matrices contain nans, they are rank deficient

4/5/2017 12:31 PM

 **alexandre.barachant** :

 >if you estimates your cov mats with regularization =&gt; `Covariances(estimator='lwf').transform(EEG)` the the problem will go away

4/5/2017 12:32 PM

 **alexandre.barachant** :

 ><https://github.com/alexandrebarachant/pyRiemann/issues/40>

4/5/2017 12:35 PM

 **octonomy** :

 >ah ok, i was looking down the average reference suggestion, which i think  is set by `mne.io.set_eeg_reference`. i will try regularization, this was my next idea too. happy to see its just a param to the covariances() constructor so i dont have to do it from scratch

4/5/2017 12:39 PM

 **octonomy** :

 >in this way you showed just now, do you not pass in EEG as X to constructor, and instead pass it in into the transform call explicitly? I expected: `Covariances(X=EEG, estimator='lwf')` instead of `Covariances(estimator='lwf').transform(EEG)`?

4/5/2017 12:43 PM

 **alexandre.barachant** :

 >no, the data nevers goes into the constructor

4/5/2017 12:43 PM

 **alexandre.barachant** :

 >for mne, the average reference is generally applied during the epoching

4/5/2017 12:44 PM

 **alexandre.barachant** :

 ><http://martinos.org/mne/stable/generated/mne.Epochs.html>

4/5/2017 12:44 PM

 **alexandre.barachant** :

 >add_eeg_ref=False

4/5/2017 12:45 PM

 **alexandre.barachant** :

 >```

> 
add_eeg_ref : bool

> 
      If True, an EEG average reference will be added (unless one already exists). The default value of True in 0.13 will change to False in 0.14, and the parameter will be removed in 0.15. Use mne.set_eeg_reference() instead.

> 
```

4/5/2017 12:45 PM

 **octonomy** :

 >im working with pyRiemann 0.2.4.  the example here does pass in X to constructor of covariances:

> 
```

> 
# compute covariance matrices

> 
cov_data_train = covariances(epochs_data_train)```

> 
<http://pythonhosted.org/pyriemann/auto_examples/motor-imagery/plot_single.html>

4/5/2017 12:46 PM

 **alexandre.barachant** :

 >yes, because that's a function, not a class.

4/5/2017 12:47 PM

 **alexandre.barachant** :

 >i should change the example to use the `Covariances` class instead

4/5/2017 12:47 PM

 **octonomy** :

 >ah, ok. i see, you gave me example with capital C, so its class, not function. understood.

4/5/2017 12:48 PM

 **alexandre.barachant** :

 >haha, i already did it on the last code

4/5/2017 12:48 PM

 **alexandre.barachant** :

 ><https://github.com/alexandrebarachant/pyRiemann/blob/master/examples/motor-imagery/plot_single.py#L68>

4/5/2017 12:48 PM

 **alexandre.barachant** :

 >When i will release the new version, the doc will be updated

4/5/2017 12:50 PM

 **octonomy** :

 >ohhh. i see, so your master is ahead of distributed package used by pip

4/5/2017 12:51 PM

 **alexandre.barachant** :

 >yes, big time :slightly_smiling_face:

4/5/2017 12:52 PM

 **octonomy** :

 >so to work from latest master, i could just `pip uninstall pyriemann`, git clone master, and then do setup.py?

4/5/2017 12:53 PM

 **alexandre.barachant** :

 >yep, you can uninstall pyriemann, clone the master, and then do `python setup.py develop`

4/5/2017 12:53 PM

 **alexandre.barachant** :

 >this way when you update the repo, the package follows

4/5/2017 12:54 PM

 **octonomy** :

 >great. im curious about why MNE would *add* the average reference by default? wouldnt you want to subtract the average rather than add it, if you were to use it?

4/5/2017 12:55 PM

 **alexandre.barachant** :

 >that's not a 'add' in mathematical sense, you add the projector tha apply the average reference

4/5/2017 1:03 PM

 **octonomy** :

 >ok, thank you. im now using the latest master of pyRiemann, excited to be here on the edge.

4/5/2017 1:05 PM

 **octonomy** :

 >may i ask one more q? in your work with xgboost, alexandre.barachant were you using that algorithm with inputs of covariance (like with pyRiemann) or spatial filters (like with CSP), or something else entirely?

4/5/2017 1:07 PM

 **alexandre.barachant** :

 >i was using tangent space, which produce vectors from covariances matrices

4/5/2017 1:07 PM

 **alexandre.barachant** :

 >you can build a pipeline like that

4/5/2017 1:08 PM

 **octonomy** :

 >i see

4/5/2017 1:08 PM

 **alexandre.barachant** :

 >```

> 
clf = make_pipeline(Covariances(estimator='lwf'), TangentSpace(), XGBClassifier())

> 
clf.fit(EEG_data, labels)

> 
```

4/5/2017 1:16 PM

 **octonomy** :

 >understood. thanks for your help today

4/6/2017 3:40 PM

 **octonomy** :

 >alexandre.barachant if you use the pipeline as you showed above, when it comes to your test data, how do you apply the transform to it before score()?  in the example above, could I just use

> 
```

> 
clf.score(test_X, test_y)

> 
```

> 
Does this properly handle the transform on the new data before running score?

4/6/2017 3:42 PM

 **alexandre.barachant** :

 >yes.

> 
in a pipeline, when you fit, it call `fit_transform` to every steps, except the last one where it call `fit`.

> 
Then, when you predict (or score) it call `transform` on every step, then call `predict` on the last one

4/6/2017 3:44 PM

 **alexandre.barachant** :

 ><http://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html>

4/6/2017 3:53 PM

 **octonomy** :

 >thank you

4/6/2017 3:59 PM

 **alexandre.barachant** :

 >pipelines are super usefull :slightly_smiling_face:

4/6/2017 4:04 PM

 **octonomy** :

 >i love it. just getting the hang of it

4/6/2017 4:05 PM

 **octonomy** :

 >in your pyRiemann library, you offer a CSP transformer? how is it different from the MNE version?

4/6/2017 4:06 PM

 **octonomy** :

 >i guess i shoudl say estimator, since it is not just transform

4/6/2017 4:07 PM

 **alexandre.barachant** :

 >it works on covariances matrices instread of epochs data. MNE does the covariance estimation within the CSP function.

> 
This makes pyriemann CSP more flexible (can be piped as a covariance matrix dimentionality reduction, with the parameter `CSP(log=False)`) and you can also use different metric for mean covariance estimation

4/6/2017 4:07 PM

 **octonomy** :

 >i still dont quite understand the diff between estimator vs classifier. i thought estimator was just sklearns word for a classifier

4/6/2017 4:08 PM

 **alexandre.barachant** :

 >finally, CSP in pyRiemann is also implementing multiclass CSP, which i later added to the CSP of mne

4/6/2017 4:09 PM

 **alexandre.barachant** :

 >i actually fixed a small bug in the CSP implementation of MNE yesterday (<https://github.com/mne-tools/mne-python/pull/4144>). they are now strictly equivalent

4/6/2017 4:11 PM

 **alexandre.barachant** :

 >An estimator is the "base class" of sklearn

4/6/2017 4:11 PM

 **alexandre.barachant** :

 >CSP is a transformer

4/6/2017 4:11 PM

 **alexandre.barachant** :

 >tranformer have a fit and transform, but no predict

4/6/2017 4:12 PM

 **alexandre.barachant** :

 >the other base class have (Classifier, Regressor, Cluster) have a predict

4/6/2017 4:13 PM

 **octonomy** :

 >yes, CSP is a way to extract features only

4/6/2017 4:13 PM

 **alexandre.barachant** :

 >A transformer typically does data "preprocessing" i.e step before a classifier. Feature extraction in a general sense

4/6/2017 4:13 PM

 **octonomy** :

 >so, its like both a classifier and estimator can both be said to be subset of estimator

4/6/2017 4:13 PM

 **alexandre.barachant** :

 ><http://scikit-learn.org/stable/modules/classes.html#module-sklearn.base>

4/6/2017 4:15 PM

 **alexandre.barachant** :

 >a transformer is an estimator, a classifier is also an estimator. that is just the base name for a sklearn class

4/6/2017 4:19 PM

 **octonomy** :

 >yes, i see

4/6/2017 4:21 PM

 **alexandre.barachant** :

 >some estimator can be both classifier and transformer. like my MDM which has a transform method (and return the distance to each centroid). it can therefore be piped before another classifier to to 'manifold embedding'

4/7/2017 12:26 AM

 **pat** :

 >Has anyone had luck connecting Muse to openvibe? I'm trying to go through LSL, but after running muse-io --lsl_eeg I can't seem to connect (and muse-lsl.py fails as gatt can't connect to my device, though it's unclear why not)

4/7/2017 12:32 AM

 **dano** :

 >Have you tried this? Never used OpenVibe, but it worked for me

> 
<https://github.com/alexandrebarachant/muse-lsl>

4/7/2017 12:32 AM

 **pat** :

 >yep, that's muse-lsl.py

4/7/2017 12:33 AM

 **pat** :

 >unfortunately gatt can't connect after 5s, although muse-io has no problems.

4/7/2017 12:34 AM

 **dano** :

 >Of course. You might have a gatt BLE issue then. Can you test on another computer/OS?

4/7/2017 12:40 AM

 **pat** :

 >not easily :disappointed: no worries though, I'll look into why gatt is failing. thanks!

4/7/2017 12:55 AM

 **pat** :

 >ah, damn - I guess the original muse wasn't BLE, so won't be found by gatt?

4/7/2017 1:11 AM

 **pat** :

 >ok, ignore the above - it looks like I could get --lsl_eeg working! :slightly_smiling_face:

4/7/2017 1:31 AM

 **alexandre.barachant** :

 >pat do you have a muse 2014 headband ? my code is only compatible with muse 2016

4/7/2017 1:46 AM

 **pat** :

 >Indeed, that was the issue (e.g. not appearing in lescan)

4/7/2017 1:56 AM

 **pat** :

 >Do the 2016 devices not work with musi-io's --lsl_eeg, or was muse-lsl.py adding more functionality that I should be wary of missing with muse-io?

4/7/2017 9:21 PM

 **dano** :

 >pat: The official support for 2016 headbands hasn't been added to muse-io yet. Alexandres code is a good stop gap solution

4/7/2017 9:40 PM

 **pat** :

 >Thanks! Good to know it's safe for me to stick to muse-io then

4/8/2017 5:02 PM

 **octonomy** :

 >alexandre.barachant about the pipeline, pyriemann, xgb:

> 


> 
I was expecting the same results from either of these 2 operations. However, they give different scores.

> 


> 
```

> 
# split transformer and classifier

> 
transformer = make_pipeline(Covariances(estimator='lwf'), TangentSpace())

> 
clf = XGBClassifier()

> 
clf.fit(transformer.transform(train_X), train_y)

> 
print clf.score(transformer.transform(test_X),test_y)

> 
```

> 
```

> 
# unified pipeline

> 
clf2 = make_pipeline(Covariances(estimator='lwf'), TangentSpace(), XGBClassifier())

> 
clf2.fit(train_X, train_y)

> 
print clf2.score(test_X, test_y)

> 
```

> 
do you know why?

4/8/2017 5:05 PM

 **octonomy** :

 >the reason i want to split transformer and estimator is 

> 
1) decouple them to allow modular configuration of feature extraction method/classifier

> 
2) to be able to try some extra code in between the transform and fit step (optimization attempts) 

> 


> 
im now wondering if splitting them into two steps significantly alters the classification outcome.

4/8/2017 5:44 PM

 **maxim** :

 >maybe use fit_transform instead of transform on train_X?

4/8/2017 5:49 PM

 **octonomy** :

 >maxim thanks, do you mean in the first code block or second?

4/8/2017 5:50 PM

 **octonomy** :

 >ah yes, i see, that does it

4/8/2017 5:52 PM

 **octonomy** :

 >so i changed 

> 
`clf.fit(transformer.transform(train_X), train_y)` to:

> 
`clf.fit(transformer.fit_transform(train_X), train_y)`

> 
but the second call, to `test_X` remains only `transform()`

4/8/2017 5:53 PM

 **octonomy** :

 >i see, so the transform should be fit when using the train data. and then that information is persisted until you use it to transform the test data later. im familiar with this from CSP, where you have to calculate some spatial filters from the covariances.

4/8/2017 5:53 PM

 **octonomy** :

 >thanks for the help, it was obvious, but im still learning.

4/8/2017 6:05 PM

 **maxim** :

 >yeah, you are exactly right

4/8/2017 6:05 PM

 **maxim** :

 >Some transformers are stateless and you don't have to fit them, but a lot of them need to be fit first

4/8/2017 6:06 PM

 **maxim** :

 >As an alternative, you can call transformer.fit(train_X) first, and then have two transforms

4/8/2017 10:36 PM

 **aj** :

 >Had any one done wensockets? Arduino to node.js?

4/8/2017 10:37 PM

 **bhargava2566302** :

 >Yes tell

4/9/2017 1:00 AM

 **octonomy** :

 >Yes done websockets but not with arduino 

4/10/2017 3:13 AM

 **dano** :

 >Did a websocket project off a Raspberry Pi once. Websockets are awesome, especially when hooked up with RxJs and Redux Observables 

4/10/2017 5:02 AM

 **aj** :

 >yea trying to figure them out

4/10/2017 5:02 AM

 **aj** :

 >going with a standard tcp socket for now

4/10/2017 5:02 AM

 **aj** :

 >just working on how to pass along the port and ip address

4/10/2017 5:02 AM

 **aj** :

 >brainwaves coming to an internet near you shortly

4/13/2017 6:14 AM

 **w** :

 >Has anyone come across a Node module for LSL, at least publishing to LSL if not reading from

4/13/2017 7:37 AM

 **alexandre.barachant** :

 >w I don't think there exist one.

4/13/2017 1:40 PM

 **aj** :

 >w there is not a js wrapper for LSL 

4/13/2017 6:09 PM

 **w** :

 >Thanks

4/14/2017 4:00 PM

 **aj** :

 >w <https://github.com/sccn/labstreaminglayer/issues/168>

4/16/2017 7:11 AM

 **octonomy** :

 >hi everyone. possible discussion topic if anyone is interested. I could move this over to <#C09H26C83|literaturereview> channel if thats better. anyway& in my work trying to compare performance of different classification algorithms on a common set of session datasets, I was looking for the most accepted method for reporting statistical significance.

> 


> 
that is, many studies might attempt to show that classifier A &gt; B &gt; C with performance metric of mean accuracy, when applied to datasets 1, 2, 3, 4, 5, 6, 7, 8, etc.  however, its not enough to show just that a classifier has better accuracy than others, but also that this better performance is statistically significant.

> 


> 
in my search of how to do this (there are many ways), the best I found was this method. its a generalized 2 step process outlined by Bashashati and earlier Demsar.  First step is to use the Friedman test, then, if null hypothesis is rejected, you can go on to post-hoc Holm test.

> 


> 
so far form the literature I reviewed, this seems like the most sound method of comparing multiple classifiers across multiple datasets. Im just floating this out into the channel to a) see if anyone has better suggestions for evaluating statistical significance of classifier performance, and b) to share with the group in case this has not crossed your radar before.

> 


> 
Bashashatis paper is freely available here if anyone is interested: <http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0129435>

4/16/2017 9:28 PM

 **joeyo** :

 >The Friedman test looks reasonable and it doesn't seem to make too many assumptions. I personally prefer permutation tests in this situation, but I think it's mostly a matter if taste.

4/16/2017 9:35 PM

 **joeyo** :

 >The second test also makes sense, but it seems like there should be a correction applied to account for the multiple comparisons (maybe there already is, I'm not very familiar with the Holm test).

4/18/2017 5:52 PM

 **wanfuse123** :

 >Hi! I have a few straight forward questions I would like to ask someone who knows something about capturing eeg data

4/18/2017 5:52 PM

 **wanfuse123** :

 >anyone have time?

4/18/2017 5:58 PM

 **yrenard** :

 >wanfuse123 don't ask to ask, just ask, a lot of people here obviously know about capturing eeg data, whoever has time and skills for your question will voice an answer

4/18/2017 6:04 PM

 **wanfuse123** :

 >ok sorry thanks

4/18/2017 6:08 PM

 **yrenard** :

 >Sure no pb

4/18/2017 6:08 PM

 **wanfuse123** :

 >my first question is: what kind of equipment (and expense) would it cost to use eeg to detect and verify that a human brain is present vs no brain at all? in other words not to discern individual patterns (like the person is saying something) but just verify the presence of a brain?

4/18/2017 6:10 PM

 **wanfuse123** :

 >the only other qualification on the question is an eeg not directly attached

4/18/2017 6:10 PM

 **yrenard** :

 >if you compare healthy brain to literally no brain, just looking at the signal spectrum will give you good information as the human EEG is quite standard

4/18/2017 6:11 PM

 **yrenard** :

 >if you want to investigate on healthy brain vs some unconscious brain, it is another question and there is a lot of research currently on this problem

4/18/2017 6:11 PM

 **yrenard** :

 >you want to do that with no EEG equipment ?

4/18/2017 6:12 PM

 **wanfuse123** :

 >right just detect a brain in the vicinity

4/18/2017 6:13 PM

 **wanfuse123** :

 >anywhere from a few inches to maybe 2 feet

4/18/2017 6:13 PM

 **yrenard** :

 >what would you do that ?

4/18/2017 6:14 PM

 **wanfuse123** :

 >for a project of mine

4/18/2017 6:14 PM

 **wanfuse123** :

 >house IoT devices

4/18/2017 6:14 PM

 **yrenard** :

 >well, then EEG is not the way to go as you obviously need a contact to do that

4/18/2017 6:15 PM

 **yrenard** :

 >I have no good answer to the problem, maybe others have

4/18/2017 6:16 PM

 **yrenard** :

 >You may be interested by the MIT work on hear rate measurement from videos, you could definitely detect that some heart is beating with no contact, and conclude that there might be a brain somewhere

4/18/2017 6:16 PM

 **yrenard** :

 >sorry, this is nearly as vague as the question :wink:

4/18/2017 6:16 PM

 **wanfuse123** :

 >hmm thats not a bad thought

4/18/2017 6:17 PM

 **yrenard** :

 ><http://people.csail.mit.edu/mrub/vidmag>

4/18/2017 6:17 PM

 **wanfuse123** :

 >so how close does eeg need to be to pick up a basic signal directly attached or up against ?

4/18/2017 6:18 PM

 **yrenard** :

 >I'm not sure what you are asking

4/18/2017 6:19 PM

 **wanfuse123** :

 >to pick up a basic signal do the leads have to be attached to the head or just up against the head like a hat?

4/18/2017 6:20 PM

 **yrenard** :

 >it needs ot be in contact with the skin - if it's not, then use gel to bridge the skin to electrode gap

4/18/2017 6:22 PM

 **wanfuse123** :

 >ok, thanks for the information , its appreciated

4/22/2017 2:54 AM

 **ch.yumin** :

 >Hello everyone! I'm starting a project that I want to control a robotic arm with the Ganglion Board (4 Channels EEG from OpenBCI). I already have the robotic arm, it needs 8 commands for full control (3 joints and 1 actuator) or at least 6 commands (2 joints and 1 actuator). Can anyone give some advices about the best techniques/algorithms to use and where should I place the electrodes? This would be my first project, I don't even know if it's possible to get good results with 4 channels EEG haha

4/22/2017 2:42 PM

 **eferdinand** :

 >ch.yumin you have to talk with nicomaque.jette i know he had similar project

4/23/2017 1:32 AM

 **ch.yumin** :

 >eferdinand Ok! thank you

4/25/2017 5:21 PM

 **mesca** :

 >My account request for the DEAP dataset (<http://www.eecs.qmul.ac.uk/mmv/datasets/deap/index.html>) has been denied because I am an autodidact individual and not an academic researcher. Same for the HCI dataset (<https://mahnob-db.eu/hci-tagging/>) because I dont own an institutional email address. Can anyone suggest open and interesting datasets on which I can try my Machine Learning / Deep Learning skills? Thanks!

4/25/2017 7:29 PM

 **pierre** :

 >mesca: Hello fellow Pierre, have you checked out the datasets listed in the awesome-bci repo? Here: <https://github.com/NeuroTechX/awesome-bci#brain-databases>

4/25/2017 7:37 PM

 **mesca** :

 >pierre Looking into it right now! Thanks :slightly_smiling_face:

4/25/2017 7:56 PM

 **yannick** :

 >That awesome awesome-bci list. :ntxblue:  :slightly_smiling_face:

5/1/2017 7:51 PM

 **sydneyneurotechx** :

 ><!channel>  I would to announce NeuroTechX's  new initiative, the "Mother of all BCI Benchmark" project. 

> 


> 
The Goal of this project is to build a comprehensive benchmark of popular BCI algorithms applied on an extensive list of freely available EEG dataset. The code will be made available on github, serving as a reference point for the future algorithmic developments. Algorithms can be ranked and promoted on a website, providing a clear picture of the different solutions available in the field.

> 


> 
Reproducible Research in BCI has a long way to go. While many BCI datasets are made freely available, researchers do not publish code, and reproducing results required to benchmark new algorithms turns out to be more tricky than it should be. Performances can be significantly impacted by parameters of the preprocessing steps, toolboxes used and implementation tricks that are almost never reported in the literature. As a results, there is no comprehensive benchmark of BCI algorithm, and newcomers are spending a tremendous amount of time browsing literature to find out what algorithm works best and on which dataset.

> 


> 


> 
alexandre.barachant will lead the initiative and I will provide logistic support to push it forward. This will be mostly a coding project (It will be open source, so anyone can contribute), however people with a design background are invited as well.

> 


> 
If you are interested in participating, please fill out the doodle below. We will arrange one or two calls based on everyones availability. 

> 


> 
<https://doodle.com/poll/4ngxy9h8qpcmkhpb>

> 


> 
More details on the project can be found here:

> 


> 
<https://docs.google.com/document/d/18nU07Qci_VDbzZCLveDQqPgqRODt7HCNBfKeNPVwMQY/edit#>

5/1/2017 7:52 PM

 **c00p3r** :

 >is this a product that you will be talking about/demostrating on at defcon?

5/1/2017 7:55 PM

 **sydneyneurotechx** :

 >Haha, if there is enough time, but likely not c00p3r  (We plan to start in June, probably won't be enough time)

5/1/2017 8:01 PM

 **aj** :

 >can we start working on this sooner? i already started thinking about this like three weeks ago

5/1/2017 8:11 PM

 **mhough** :

 >Yeah great/needed project

5/1/2017 8:11 PM

 **sydneyneurotechx** :

 >It's partially dictated by alexandre.barachant's schedule (Mine as well). Alexandre what do you think? What's the earliest you can do?

5/1/2017 8:16 PM

 **sydneyneurotechx** :

 >mhough Sign up if you are interested :slightly_smiling_face:

5/1/2017 8:22 PM

 **mhough** :

 >Oh definitely. Any interest in running the same stuff on open clinical EEG?

5/1/2017 8:25 PM

 **sydneyneurotechx** :

 >When you say open clinical EEG, what are you referring to? Open Databases?

5/1/2017 8:58 PM

 **aj** :

 >just send some prs my way

5/1/2017 8:58 PM

 **aj** :

 >whenever y'all are ready on your end

5/1/2017 10:17 PM

 **a.tech** :

 >What an awesome project! This is definitely going to help grow the field. Preprocessing algos is such a huge bottle for new ppl! 

5/2/2017 1:23 AM

 **mhough** :

 >Yeah sydneyneurotechx  it's continuous EEG done for whatever hospitals can bill for? I haven't looked at it closely for events etc. I'll get the link. Only heard about it from a stats guy a couple of months ago. All low channel count so not so interesting for much spatially. 

5/2/2017 1:25 AM

 **mhough** :

 >And yes it's an open database. Should have led with that:)

5/2/2017 3:15 AM

 **sydneyneurotechx** :

 >I

5/2/2017 4:53 AM

 **octonomy** :

 >very nice. ill try to join this meeting

5/2/2017 6:15 AM

 **mhough** :

 >Understood sydneyneurotechx. Sorry if this is a repeat (can I not search the archives?) but I think he was talking about the Temple University EEG dataset

5/2/2017 6:15 AM

 **mhough** :

 ><https://www.isip.piconepress.com/publications/presentations_misc/2017/temple_innovation/auto_eeg/04_poster_v00.pdf>

5/2/2017 9:10 AM

 **alexandre.barachant** :

 >mhough We will use any dataset where we can apply supervised machine learning. We will focus on BCI at first, because the problems are better defined  and the dataset are smaller (in size), but it won't be incompatible with some clinical EEG problem (sleep, seizure, etc, as long as the data have annotation)

5/2/2017 12:05 PM

 **yannick** :

 >alexandre.barachant, dan.rizzuto and his team opened their invasive recordings from DARPA RAM related studies on memory. Lots of high quality labeled data on which they do machine learning to classify if the memory will be encoded or not. That could also be an interesting dataset / paradigm. (just thinking out loud)

5/2/2017 12:06 PM

 **alexandre.barachant** :

 >yannick do you have a link ?

5/2/2017 5:15 PM

 **mhough** :

 >That's great alexandre.barachant. I was jumping ahead I know. That's cool yannick. Yeah love a link

5/2/2017 5:23 PM

 **yannick** :

 >Here is the full wiki: <http://memory.psych.upenn.edu/RAM>

5/2/2017 5:24 PM

 **yannick** :

 >You have a link at the bottom of the main page to Download the dataset. 

> 
(You request access and they will share the Box - kinda Dropbox folder - with you)

5/3/2017 12:37 PM

 **alexandre.barachant** :

 >yannick Thanks. There will be some work to do to list all these datasets :slightly_smiling_face: We need to be carefull with the licence and will avoid using datasets that are behind a wall like this.

5/3/2017 3:15 PM

 **yannick** :

 >And/Or to work with the people behind the wall to make a door in the wall :slightly_smiling_face:

5/3/2017 3:27 PM

 **alexandre.barachant** :

 >yep sure, if the dataset is really interesting, we can try to convince people to make it available in direct download.

5/3/2017 4:58 PM

 **mhough** :

 >What are you looking for in the license? 

5/3/2017 5:52 PM

 **pat** :

 >what's the best way to ask questions about moabb? currently the announcement was in a few channels, would it make sense to create a new one?

5/3/2017 8:38 PM

 **alexandre.barachant** :

 >pat Good idea. We will create a channel before the end of the week. sydneyneurotechx and I are still working on the details.

5/3/2017 8:43 PM

 **alexandre.barachant** :

 >mhough I want to avoid datasets that are 'freely available' with restrictions. The whole point of this is to make it easy to use and accessible to everyone, whether you are part of a research lab, a company or an individual.

5/3/2017 8:48 PM

 **mhough** :

 >Yeah no worries. I know exactly what you mean. I followed up a few people's complaints about data access and they could get the data but they were perhaps too literal with the download instructions. It would be good to talk about it a little later but like you said just ignore those for now

5/3/2017 8:53 PM

 **alexandre.barachant** :

 >yep sure. i think the first step is to list all dataset available, what they contains and how they can be accessed. Then we will see how we can do it.

> 
Also, i thinks it's better to have a lot of smaller dataset, rather than a few big one. it is important to have diversity in the benchmark, so results are more robust

5/3/2017 8:55 PM

 **alexandre.barachant** :

 >there will be some interesting questions about how we rank the different algorithm.

5/3/2017 9:03 PM

 **mhough** :

 >Ok. I can start a list. I am doing the same for ERPs studies anyway. Is there a wiki or something I should use?

5/3/2017 9:09 PM

 **mhough** :

 >Once all the free stuff is organized I wonder if it will be easier to ask labs if they could give subsets of their data that could give you more of those small batches you want. I'm sure you've thought about it already. 

5/3/2017 9:21 PM

 **mhough** :

 >alexandre.barachant I know this is an ERP study but do people ignore the old Begleiter data on the UCI machine learning repository because they don't have the raw data? I'll ask the Poldrack lab. Years ago I tried to contact the person who took over after he retired (died?) to try and get the continuous EEG but its was a different time back then and honestly they might not even have it backed up somewhere:)

5/3/2017 11:49 PM

 **octonomy** :

 >mhough alexandre.barachant there is an awesome list one sec

5/4/2017 12:51 AM

 **octonomy** :

 >One key dataset is the BCI competition IV. It's referenced by so many papers. It sits behind a free registration where you must give email to get access. This was from 2008, i wonder if the original people would be willing to release access. I think by regulations probably this would require consent of original subjects, wherever they are. Just because of paperwork that is signed for experiments.

5/4/2017 12:55 AM

 **octonomy** :

 >I'd be happy to work with SF neurotech x chapter to collect our own royalty-free dataset of MI data using OpenBCI 8-channel and 16-channel, to add some lower resolution data to the mix. If it's useable for this project. I can use a standard MI protocol and document it.

5/4/2017 12:56 AM

 **octonomy** :

 >sydneyneurotechx created the <#C588BQVH9|moabb> channel. It's on

5/4/2017 1:11 AM

 **sydneyneurotechx** :

 >yup <!channel>  for those who want to join, please check out <#C588BQVH9|moabb>

5/4/2017 3:03 AM

 **aj** :

 >octonomy i could donate motor imagery data from thinker

5/4/2017 3:03 AM

 **aj** :

 >we should just make a formal way to add it

5/4/2017 3:03 AM

 **aj** :

 >please god not edf

5/4/2017 3:04 AM

 **octonomy** :

 >come on down to <#C588BQVH9|moabb> dont be a slacker

5/4/2017 3:05 AM

 **octonomy** :

 >oh what? you dont like BDF? ha ha ha

5/5/2017 3:44 PM

 **octonomy** :

 >alexandre.barachant may i ask you a question?  among the riemannian methods, would you say that MDM and TS represent fundamentally different feature spaces?  im asking because im trying to decide if classifiers using either method are appropriate to compare in the same statistical significance test.

5/5/2017 3:44 PM

 **alexandre.barachant** :

 >they both work on same input (covariance matrices), so it's fine as long as you estimated them with the same method

5/5/2017 3:46 PM

 **octonomy** :

 >ive been working from the ideas for comparing multiple classifiers across multiple datasets by Bashashati. In that they segregate test based on Band Power (BP) features vs Morlet wavelet features.  They say: The reason we compared the performance of different classifiers when a single feature extraction methodology was used was that the nature of feature spaces was different for each setting and the results could thus be misleading. For example, when we use the BP features, the feature space is of low dimensions compared to the settings where the Morlet feature is used. Therefore, classification methodologies could only be compared when they are applied on the same feature space.

5/5/2017 3:50 PM

 **alexandre.barachant** :

 >this is true if you want to compare classifiers, i.e for example is it better to use LDA or SVM

5/5/2017 3:50 PM

 **octonomy** :

 >would you describe MDM and TS as projection into a comparable feature space? if the same estimation is used, as you say? im uncertain if the additional projection back to a euclidean plane by TS qualifies as a fundamentally different space than MDM. to the point where it doesnt make sense to compare the same classifier (LDA or LR) against MDM vs TS

5/5/2017 3:51 PM

 **octonomy** :

 >yes, my goal is to compare different classifiers.  im not sure if MDM and TS must be segregated, or if they can be in the same signficance test (Im using Friedman with posthoc Holm)

5/5/2017 3:52 PM

 **alexandre.barachant** :

 >i'm not sure the question can be framed that way

5/5/2017 3:53 PM

 **alexandre.barachant** :

 >basically, you can only compare thing that are comparable, i.e. that took the same inputs. so here you are not comparing LDA or SVM, but the pipeline TS + classifier versus MDM

5/5/2017 3:54 PM

 **alexandre.barachant** :

 >basically, you can benchmark TS+SVM versus TS+LDA versus MDM

5/5/2017 3:54 PM

 **octonomy** :

 >i see. so since the pipeline takes the same inputs (covariance matrices).

5/5/2017 3:55 PM

 **octonomy** :

 >in this way, could you also add then also the pipeline of CSP+LDA, since it also takes the same inputs (covariance matrices)?

5/5/2017 3:55 PM

 **alexandre.barachant** :

 >yes. the same way they could have compared BP and wavelets (they both take raw data as input), the difference is in the intepretation. it's the whole pipeline that is better, not just the classifier

5/5/2017 3:58 PM

 **octonomy** :

 >got it. thank you for this clarification.

5/5/2017 3:59 PM

 **octonomy** :

 >i get confused sometimes about where exactly is the distinction between feature extraction vs classification.

5/5/2017 4:00 PM

 **octonomy** :

 >like, for example, to what extent is a grid search considered a Feature extraction.  if it results in restricting the bandpass filter a certain way, it is changing the information which will be considered by the classifier. and yet, it is a part of the classifier as well, since it uses the classifier to decide which preprocess params are best.

5/5/2017 4:01 PM

 **alexandre.barachant** :

 >IMO comparing classifier is only relevant when you want to know which classifier is better for a given feature set. but that's just a part of the story.

5/5/2017 4:02 PM

 **alexandre.barachant** :

 >if you have a good classifier for a given feature set, that is not given that this classifier will be optimal for another feature set

5/5/2017 4:05 PM

 **alexandre.barachant** :

 >and yes, you can add CSP+LDA

5/5/2017 4:05 PM

 **alexandre.barachant** :

 >all of these algorithms will be benchmarked in the <#C588BQVH9|moabb>

5/5/2017 4:09 PM

 **octonomy** :

 >in my interpretation, i prefer to think of this idea of the entire pipeline as the classifier. thank you for the advice

5/6/2017 12:42 AM

 **jfrayshe** :

 >Long time reader first time poster, was wondering if anyone could point me to some datasets that would be useful for analyzing neural oscillations?

> 


5/6/2017 4:48 PM

 **yannick** :

 >jfrayshe did you check the awesome-bci list? There are some datasets listed there.

5/6/2017 8:11 PM

 **octonomy** :

 >yannick the awesome list is pretty small on datasets actually

5/8/2017 4:27 AM

 **sydneyneurotechx** :

 >octonomy  Add more if you find :slightly_smiling_face:

5/8/2017 5:24 AM

 **octonomy** :

 >fair enough!

5/10/2017 9:05 PM

 **jfrayshe** :

 >I have looked at it but struggled to pull the individual datasets using python, any suggestions?

5/10/2017 10:15 PM

 **jfrayshe** :

 >Noob questions: what do events refer to in the case of eegdata?

5/10/2017 10:21 PM

 **octonomy** :

 >jfrayshe try MNE library. Install it. There are tutorials on their site that explain (I think) how to download a sample dataset.  I have not used their prerecorded data sets so I'm not speaking from experience.

5/10/2017 10:22 PM

 **octonomy** :

 >Events are literally events. In an experiment, it almost always refers to some stimulus presented to the subject.

5/10/2017 10:24 PM

 **jfrayshe** :

 >Cheers l will look into thay

5/10/2017 10:24 PM

 **octonomy** :

 >So for example, if you're working with motor imagery, and classifying left hand vs right hand, you have two "classes" of event, left and right. Conventionally, these classes are represented by integer codes, like left=2, right=3. An event in this case means you show either class 2 or 3 to the subject

5/10/2017 10:25 PM

 **octonomy** :

 >Technically event could be used for anything. But most common use is to tag or label data for supervised learning. 

5/11/2017 6:38 PM

 **yannick** :

 >Hey jfrey I see you did commit on: <https://github.com/conphyture/LSL2Unity>

> 
but in the ToDos its also mention to look at: <https://github.com/xfleckx/LSL4Unity>

> 
Im looking for LSL in Unity, any idea what to use?

5/12/2017 12:46 AM

 **jfrayshe** :

 >Thanks octonomy that clarifies things and is quite applicable to the data I'm working on.

5/12/2017 12:48 AM

 **jfrayshe** :

 >Is it common practice to automatically preprocess eeg data to filter out electrode signals that occupy a space that should have no impact on what I'm measuring? For example if I was analyzing neural oscillations (alpha and beta) during motor control should I automatically preprocess out signals from electrodes that aren't close to that region of the brain?

5/12/2017 6:40 AM

 **jfrey** :

 >yannick: I started my version because I could not get LSL4Unity work, at least on linux. I have been using LSL2Unity on Linux and Windows, but not extensively. I would say that my library is simpler to grasp, but I think you would be better of using LSL4Unity, it seems they have more features, It's definitely more thoroughly tested and... it's maintained. Once you'll have played with it, I'd like to hear your feedback :wink:

5/12/2017 11:47 PM

 **octonomy** :

 >I think it's your call jfrayshe . I think it depends on your technique. Methods like CSP will apply weights to each electrode, so if those electrodes you want to exclude are truly useless they would end being given little weight anyway

5/12/2017 11:55 PM

 **octonomy** :

 >Another thing to consider is, the presence of non relevant electrodes (also called "channels") is that they actually might be relevant if they can help reduce weight of channels you think are relevant.  For example, if a "good" channel right over motor cortex shares information with a "bad" channel over forehead, the extent to which the good channel's signal is "similar" (in covariance) might actually help to eliminate that part of the "good" channel's signal to "correct" it. Just a high level speculation here to share 

5/12/2017 11:57 PM

 **octonomy** :

 >In my own work I've experimented with removing channels one by one, using a "leave one out" approach, and haven't seen it to be too much difference on outcome.  I suggest you try running experiments with and without the "bad" electrodes and see for yourself what pattern emerges.

5/14/2017 1:49 AM

 **jfrayshe** :

 >octonomy cheers, thank you for your input it is helpful. I think for my work I might apply CSP since the data I am working with is not my own and I don't have much time to experiment with it.

5/14/2017 1:50 AM

 **jfrayshe** :

 >Anyone care to weigh on the function within mne they use to convert time based eeg data to frequency?

5/14/2017 2:00 AM

 **octonomy** :

 >yes its a good standard.  the work being done with riemannian geometry is as good and better it is looking like more and more, you might consider it.  check out pyRiemann library. you can use it like a scikit  learn classifier

5/14/2017 2:00 AM

 **octonomy** :

 >there are at least 2 ways to go with this - FFT and DWT

5/14/2017 2:00 AM

 **octonomy** :

 >FFT = fast fourier transform, and DWT = discrete wavelet transform.

5/14/2017 2:01 AM

 **octonomy** :

 >FFT removes the time information.  so you chose some kind of binning strategy (i.e. what size epoch windows you want to look at) and then fourier transform yields a histogram of power at different frequency bands.

5/14/2017 2:02 AM

 **octonomy** :

 >DWT is similar, but it retains the time information

5/14/2017 2:03 AM

 **octonomy** :

 >if you care about that.  but DWT is more complex because it is producing a lot more features to deal with. it gives you band power over time, and can also be used to show the phase information as well.  DWT is typically shown as the rainbow colored map, where red or blue is high or low voltage, on a plot where y axis is frequency bands, and x axis is time.  so its really a 3d graph

5/14/2017 2:04 AM

 **octonomy** :

 >FFT usually shows power on the y axis, and frequency band on the x axis. shown as a bar chart histogram, or line graph

5/14/2017 2:05 AM

 **octonomy** :

 >are you working with labeled data?

5/14/2017 2:07 AM

 **octonomy** :

 >i have done some work with getting nonstandard EEG files into MNE form.  basically if you can get your data into numpy arrays, you can then load them up in to MNE objects.  basically you want to create a RawArray object, and then if you have class labels (i.e. events), you can use the RawArray to create an Events object.  once you have an events object, you can quickly and easily select epochs as needed.  

> 


> 
the parts you have to work out are just how to load up the objects properly, you have to tell the RawArray which channels are EEG and which are STIM (i.e. not electrodes, but channels providing data about events, or stimulation).

5/14/2017 2:22 AM

 **jfrayshe** :

 >Thanks octonomy for the response. I suppose I'm looking for a specific example using mne, do they have a tutorial worth looking at?

5/14/2017 3:01 AM

 **octonomy** :

 >yep

5/14/2017 3:02 AM

 **octonomy** :

 >they have quite a few. what general type of work are you doing? are you trying to classify motor imagery?

5/15/2017 12:09 PM

 **sc** :

 >Lovely explanation of the Fourier Transform <http://gizmodo.com/digital-music-couldnt-exist-without-the-fourier-transfo-1699155287>

5/15/2017 2:29 PM

 **dano** :

 >sc: Really accessible. Will keep this in mind for teaching

5/15/2017 3:40 PM

 **jfrayshe** :

 >octonomy essentially I am attempting to visualize neural oscillations in the alpha and beta range that occur during actual vs imagined motion from the eegbci dataset available in mne.datasets

5/15/2017 6:03 PM

 **octonomy** :

 >So you want to apply alpha and/or beta filter on epochs of event labeled data?

5/15/2017 6:05 PM

 **octonomy** :

 >Thereby making graphs of epochs labeled  "actual" side-by-side with epochs labeled "imagined".

5/15/2017 6:06 PM

 **octonomy** :

 >To be honest, it sounds more like you're in the realm of ERP type study

5/15/2017 6:08 PM

 **octonomy** :

 >In which you might take say, 100 "active" epochs and average them. And then 100 "passive" epochs and average them. Producing two side by side average visualizations. Which could be either the average actual signal filtered in the range you want, or histogram presenting statistics

5/15/2017 6:08 PM

 **octonomy** :

 >How much time do you have to do this?

5/15/2017 7:25 PM

 **jfrayshe** :

 >Hmmm about a week at this point. I've laid a foundation but I wasn't approaching it from an ERP perspective 

5/15/2017 7:47 PM

 **jfrayshe** :

 >I'm really attempting to use a eeg data to demonstrate neural oscillations as a feature extraction 

5/15/2017 7:48 PM

 **jfrayshe** :

 >I'm only focusing on alpha and beta since they are predominant during motor control.

5/16/2017 3:26 AM

 **octonomy** :

 >I understand. I work with motor imagery, and alpha and beta too. The alpha and beta we usually just filter in one pass, from 7-30. There's a bandpass  filter in MNE. 

5/16/2017 3:26 AM

 **octonomy** :

 >My question is about your visualization.

5/16/2017 3:26 AM

 **octonomy** :

 >You said you want to visualize active vs imagined.

5/16/2017 3:27 AM

 **octonomy** :

 >Now my question was about whether you're doing single trial or averaged across many trials

5/16/2017 3:27 AM

 **octonomy** :

 >Like, let's say you have a dataset with 200 labeled trials, each say 4sec long, and 100 are active, 100 are imagined.

5/16/2017 3:28 AM

 **octonomy** :

 >Are you looking to plot 200 individual graphs? Of all epochs filtered to alpha/beta?

5/16/2017 3:29 AM

 **octonomy** :

 >In ERP, you show two graphs. In one, the average waveform of the 100 active, and the average waveform of the 100 imagined. That's one way to go

5/16/2017 3:30 AM

 **octonomy** :

 >The other way to go is, sounds like what you're trying, FFT to produce histogram, or bar chart, showing power at different frequency bands.

5/16/2017 3:31 AM

 **octonomy** :

 >But in this case, you have the same question: are you going to plot 200 bar chart histograms? Or are you going to present averages of 100 and 100 into just 2 graphs.

5/16/2017 7:53 PM

 **fred-simard** :

 >technically, jpeg compression is the cosine transform, but close enough

5/16/2017 11:24 PM

 **jfrayshe** :

 >The latter is what I envisioned, an average of values between 2 different experimental runs 

5/16/2017 11:25 PM

 **octonomy** :

 >Good ok. So if you take that approach of average, if you choose to show waveforms it's the ERP approach

5/17/2017 10:43 PM

 **octonomy** :

 >Wondering if anyone has a rough estimate of what's the state of the art performance accuracy for motor imagery BCI these days? What's the best achieved with online use? Anyone have any idea?

> 


> 
For two class my guess is somewhere around 80%

5/17/2017 11:03 PM

 **yrenard** :

 >It depends how many channel you have available and where they are located, but assuming you have good amount of electrodes and good locations, and that your subjects are also well trained, I would more shoot for 90 % accuracy for a two class BCI ; check out alexandre.barachant 's <https://hal.archives-ouvertes.fr/hal-00693321/file/esannBCI.pdf>

5/17/2017 11:34 PM

 **octonomy** :

 >Thanks yrenard . I was asking for any number of channels, whatever is the highest mark so far. Thanks for the paper this helps. I know the Riemann methods seem to be the leading accuracy right now

5/18/2017 8:37 AM

 **alexandre.barachant** :

 >octonomy yrenard I have a current version of the <#C588BQVH9|moabb> for 2 classes motor imagery (9 different dataset, 227 subjects). You get this kind of performances

5/18/2017 8:38 AM

 **alexandre.barachant** :

 >basically, with Riemannian geometry, 80% of the subjects get and AUC &gt; 0.6, and 20% of them can achieve &gt; 0.9. The median is around 0.75 AUC

5/18/2017 8:39 AM

 **alexandre.barachant** :

 >a breakdown for each dataset

5/18/2017 8:44 AM

 **qbarthelemy** :

 >Alexandre, have you got the results with classical MDM?

5/18/2017 8:50 AM

 **alexandre.barachant** :

 >yes, it is around CSP

5/18/2017 8:51 AM

 **alexandre.barachant** :

 >with MDM :

5/18/2017 8:52 AM

 **alexandre.barachant** :

 >it depends on the dataset, because MDM does not performs well for high channel count (generally)

5/18/2017 8:53 AM

 **qbarthelemy** :

 >ok, thx!

5/18/2017 12:55 PM

 **aj** :

 >this is cool

5/18/2017 12:55 PM

 **aj** :

 >good work alexandre.barachant

5/18/2017 11:24 PM

 **octonomy** :

 >Thank you this is excellent I will study this more to understand these! Awesome.

5/18/2017 11:26 PM

 **octonomy** :

 >P.s. I successfully defended my thesis today and will be awarded my masters degree in computer science! Looking forward a summer of BCI coding now that I'm free

5/19/2017 12:31 AM

 **jfrayshe** :

 >Congrats!

5/19/2017 10:02 PM

 **okbalefthanded** :

 >octonomy congrats! what was it about ?

5/20/2017 5:28 PM

 **octonomy** :

 >okbalefthanded brain computer interface development software. I worked on open source Python package and also a low cost headset for it which uses OpenBCI. Additionally, I used my equipment and software to do a statistical significance test of many classifiers against many datasets. Open source software to be released later this summer, with the goal of making EEG data collection and ML analysis simple for researchers

5/20/2017 5:34 PM

 **yannick** :

 >octonomy so I guess youll be involved in the Mother of All BCI Benchmark :stuck_out_tongue: (<#C588BQVH9|moabb> )

5/21/2017 5:12 PM

 **octonomy** :

 >Yep I'm going to try and make myself useful

5/30/2017 2:55 PM

 **andyh616** :

 >let me know if you are interested! here is the project website: <https://github.com/ContextLab/hypertools>

5/30/2017 2:56 PM

 **andyh616** :

 >we are participating in the mozilla code sprint this thurs and fri: <https://mozilla.github.io/global-sprint/> it would be awesome if anybody was interested in helping to implement the real-time plotting feature

5/30/2017 3:06 PM

 **yannick** :

 >Nice work andyh616! It sounds like something naoto &amp; sidksv would be interested in ^

5/30/2017 3:06 PM

 **andyh616** :

 >thanks!

5/30/2017 3:07 PM

 **andyh616** :

 >naoto sidksv DM me if you might be interested :slightly_smiling_face:

5/30/2017 3:24 PM

 **aj** :

 >andyh616 hey!

5/30/2017 3:25 PM

 **andyh616** :

 >hey man! hows it hangin?

5/30/2017 3:45 PM

 **bciguy** :

 >Hey <!channel> has anyone here applied DEEP LEARNING to RAW EEG? As far as Im aware most groups are still doing feature extraction by hand, so I thought this would be the best group to ask.

5/30/2017 3:46 PM

 **salazarparis** :

 >We do it <http://www.synapbox.com|www.synapbox.com> EEG and Facial recognition/Eye-tracking

5/30/2017 3:46 PM

 **alexandre.barachant** :

 >bciguy  <https://arxiv.org/pdf/1703.05051.pdf>

5/30/2017 3:46 PM

 **bciguy** :

 >salazarparis: you are applying deep learning directly to raw EEG?

5/30/2017 3:46 PM

 **hassan** :

 >salazarparis  and does it work?

5/30/2017 3:47 PM

 **salazarparis** :

 >Yes actually we are using Emotiv and Neurosky (Attention only)

5/30/2017 3:47 PM

 **bciguy** :

 >what kind of network are you using?

5/30/2017 3:47 PM

 **salazarparis** :

 >we work with Emotiv and Neurosky

5/30/2017 3:47 PM

 **bciguy** :

 >how do you overcome overfitting?

5/30/2017 3:48 PM

 **salazarparis** :

 >but we prefered to play with raw data from facial recognition and eyetracking

5/30/2017 3:49 PM

 **salazarparis** :

 >we can talk it somewhere else, we are trying to manage our know-how internally with specific people

5/30/2017 3:49 PM

 **salazarparis** :

 >not yet open to all

5/30/2017 3:49 PM

 **alexandre.barachant** :

 >there was a special session at the 2016 BCI meeting. Long story short, no one made it works better than hand crafted feature + LDA

5/30/2017 3:50 PM

 **alexandre.barachant** :

 >(that's not completely true, but that was the feeling)

5/30/2017 3:50 PM

 **yannick** :

 >Because everybody were using their own datasets, or people were leveraging the all the datasets available online as a general training, and then retraining for the task at hand? (kinda transfer learning from general EEG to specific EEG)

5/30/2017 3:50 PM

 **bciguy** :

 >alexandre.barachant: very interesting, I would love to see that presentation.. Do you know why it didnt work? Due to overfitting?

5/30/2017 3:51 PM

 **hassan** :

 >I saw once that US army (or a related agency) released  about 100 GB of raw EEG data. Cannot find the link. However, do we really consider this as an enough data to model a complex signal like EEG via deep learning?

5/30/2017 3:52 PM

 **alexandre.barachant** :

 >hassan, yep, those guy where the only one to present kind of good results at the conference

5/30/2017 3:53 PM

 **salazarparis** :

 >would you like to check an opportunity @synapbox ?

5/30/2017 3:53 PM

 **yannick** :

 >You obviously cant do deep learning with your own data within a lab experiment. Youll train on noise and overfit big time. You need a massive amount that will kinda learn what general EEG is, then learn the specificity of the task at hand.

5/30/2017 3:54 PM

 **alexandre.barachant** :

 >IMO, reason why it is not that efficient right now is :

> 
- Dataset are too small.

> 
- Most problem are binary classification problem, where current feature extraction are quasi-optimal.

> 
- DL don't like noisy data. DL like complex and structured data with a good SNR (like image, text, etc)

5/30/2017 3:55 PM

 **bciguy** :

 >salazarparis not sure I understand your answer - is this^ a solicitation for a job or future customer?

5/30/2017 3:56 PM

 **alexandre.barachant** :

 >the paper i pointed out here, they took a interesting approach, which is to build an architecture that reproduce current feature extraction pipeline. That's a way to let the network learn parameters that makes sense and can be interpreted

5/30/2017 3:56 PM

 **alexandre.barachant** :

 >the paper i pointed out here, they took a interesting approach, which is to build an architecture that reproduce current feature extraction pipeline. That's a way to let the network learn parameters that makes sense and can be interpreted

5/30/2017 3:57 PM

 **alexandre.barachant** :

 >it's basically like injecting a little bit of domain knowledge to help convergence

5/30/2017 3:57 PM

 **bciguy** :

 >alexandre.barachant: I get your reasoning here, but isnt the whole theory behind DL that the autoencoders create features in the hidden layers, and wouldnt that deal with the noise issue? Again, all theoretical and a very interesting discussion :smile:

5/30/2017 3:58 PM

 **bciguy** :

 >alexandre.barachant: yep, but the network does it on its own with data

5/30/2017 3:58 PM

 **salazarparis** :

 >I see you are in this

5/30/2017 3:58 PM

 **salazarparis** :

 >nice

5/30/2017 3:58 PM

 **bciguy** :

 >alexandre.barachant: yes this was my thought exactly, thanks again

5/30/2017 3:58 PM

 **salazarparis** :

 ><https://sleepwithaurora.com/>

5/30/2017 3:58 PM

 **salazarparis** :

 >let me know if you want

5/30/2017 3:58 PM

 **alexandre.barachant** :

 >the network learn the parameter, not the architecture.

5/30/2017 3:59 PM

 **bciguy** :

 >salazarparis I would be happy to speak with your team

5/30/2017 3:59 PM

 **bciguy** :

 >email me at <mailto:daniel@iwinks.org|daniel@iwinks.org>

5/30/2017 3:59 PM

 **alexandre.barachant** :

 >yes, but when feature are buried in noise, the auto-encoder has a lot of trouble to converge to a good solution

5/30/2017 4:00 PM

 **bciguy** :

 >I see what you are saying, I forgot to note the utility of BSS as a preprocessing step (PCA/ICA / Hilbert etc)

5/30/2017 4:02 PM

 **bciguy** :

 >semantics& the knowledge is in the neurons :wink:

5/30/2017 4:02 PM

 **salazarparis** :

 >ok, I will reach you tomorrow for sure

5/30/2017 4:02 PM

 **salazarparis** :

 >have a great day

5/30/2017 4:02 PM

 **alexandre.barachant** :

 >by architecture, i mean the amount and type of layer you pile up

5/30/2017 4:03 PM

 **ray_cassani** :

 >can't be possible the preprocessing is also a layer in the DL model? so the it learned rather than imposed?

5/30/2017 4:03 PM

 **hassan** :

 >alexandre.barachant: Do you have a link to their publications about that (if any)?

5/30/2017 4:03 PM

 **bciguy** :

 >yannick: why do you say this? Standard image recognition samples are within the same range as EEG 1s single trial / single channel (dim reduced) samples.

5/30/2017 4:04 PM

 **alexandre.barachant** :

 >for example, 1D conv layer are like temporal filter. by adding this layer you tell the network 'learn me the optimal temporal filter'.

> 


> 
The network by itself is not trying to figure out what kind of layer it should use (yet)

5/30/2017 4:05 PM

 **alexandre.barachant** :

 >yes, that was basically what they did in the paper i shared here

5/30/2017 4:10 PM

 **mrkrause** :

 >These end-to-end pipelines are all the rage right now--Ive seen a few kicking around for speech recognition too. 

> 


> 
Technically, its really impressive and I can see how (e.g.) not having to choose the filter settings is nice. On the other hand, I worry that they provide new and exciting ways to shoot oneself in the foot (what if the 60 Hz noise varies between conditions or subjects?) and it seems like you would have to completely retrain the model even after trivial changes (e.g., sampling rate)

5/30/2017 4:37 PM

 **yannick** :

 >Standard samples for image recognition problem can be within the same data size range. Not sure exactly what you mean here?

5/30/2017 4:39 PM

 **bciguy** :

 >Im saying that one sample (image) in the computer vision problem can be similar in size to a single trial single channel EEG sample

5/30/2017 4:40 PM

 **bciguy** :

 >Im calling you out on You obviously cant do deep learning with your own data within a lab experiment

5/30/2017 4:49 PM

 **yannick** :

 >Yes, and if you try to classify X and Os you need little samples because the data is highly structured with fairly low variance. The more complex the image and the more variance (e.g. races of dogs) the more data you will need. But a real-life image remains a highly structured piece of data.

5/30/2017 4:51 PM

 **yannick** :

 >EEG and time series such as stock market are not  necessarily as structured. Which makes Deep Learning harder.

5/30/2017 5:20 PM

 **dano** :

 >using matplotlib 2.0.2

5/30/2017 5:20 PM

 **dano** :

 >using matplotlib 2.0.2

5/30/2017 5:23 PM

 **alexandre.barachant** :

 >dano not sure it will wokrs , but try the parameter `interpolation='bilinear'`

5/30/2017 5:25 PM

 **dano** :

 >thanks!

5/30/2017 7:29 PM

 **dano** :

 >the interpolation parameter isn't in the matplotlib docs for specgram, I'll write a note to the devs

5/30/2017 7:30 PM

 **alexandre.barachant** :

 >it's in **kargs

5/30/2017 7:31 PM

 **alexandre.barachant** :

 >it's in the parameters for imshow or something like this

5/30/2017 7:31 PM

 **alexandre.barachant** :

 >it's in the parameters for imshow or something like this

5/30/2017 7:31 PM

 **dano** :

 >yea, it's there for imshow

5/30/2017 7:31 PM

 **alexandre.barachant** :

 >**kwargs :

> 


> 
Additional kwargs are passed on to imshow which makes the specgram image

5/30/2017 7:31 PM

 **dano** :

 >ahh, I see, imshow's like the general purpose plotting funciton

5/30/2017 7:32 PM

 **alexandre.barachant** :

 >(from the doc)

5/30/2017 7:32 PM

 **alexandre.barachant** :

 >yep, when I don't find the right param for this kind of thing, i often look at the **kargs param from the doc to know which base function it is using

5/30/2017 7:33 PM

 **alexandre.barachant** :

 >that's a bit annoying, but it usually works

5/30/2017 8:36 PM

 **bciguy** :

 >yannick when you say structured do you mean that latent variables have relatively lower variance?

5/30/2017 8:37 PM

 **bciguy** :

 >Yes EEG is noisy, everyone here knows that. I dont expect DL to work out of the box for EEG/BCI, and weve already talked about a few of the reasons why. However I suspect that it is going to be a very powerful tool in the next decade of EEG/BCI research, since it has made such a significant impact in *virtually all other domains of machine learning*, but not yet in EEG/BCIs.

5/30/2017 8:48 PM

 **bciguy** :

 >I dont expect DL to work out of the box for all EEG/BCI applications, and weve already talked about a few of the challenges for attempting to do so in this channel. However there must be an EEG correlate to Eigenimages or the like appearing in computer vision, and its difficult to even imagine what deep learning might be able to tell us about our datasets without just doing it (my excuse is lack of time!) I just wanted to have this discussion since I dont see it going on anywhere else.

5/30/2017 9:02 PM

 **yannick** :

 >Im using the X and O example because its a popular one in Deep Learning, simpler than MNIST. (just finished Yoshua Bengio Deep Learnings Class at University Montreal so I might be a little too much into it haha.)

> 
There is no doubt that Deep Learning will have a significant impact in the coming years, but like any other fields deep learning impacted, data is key. We need efforts that can leverage large(r) amount of data. The performance we see today in deep learning is also possible because of the amount of images of a cat or text or speech available online. All the large corpus of organized data now available online made a huge difference in the field, now moving so fast. MNIST, MSCOCO, LSUN, Flickr, Cornell Movie Dialogue, Stanford Twitter Sentiment, etc.

> 
What will help Deep Learning for EEG/BCI, is a similar grouping of data and benchmark to test algorithms to iterate quickly on approaches. Deep Learning right now is a lot of Try, Try, Try, Try& No one can tell what hyper parameter to use and such. So its all about iterating quickly. Which the EEG/BCI field need to get better at.

5/30/2017 9:06 PM

 **yannick** :

 >The field is moving so fast that the class itself (Deep Learning) is about What happened in the last 2-3 years. And the final project description says To our knowledge, this is a novel task and has never been done before, so a successful project would in fact be a valuable research contribution.  However we also designed the project so that a very simple solution will still be able to achieve reasonable results.  (quite intimidating, hahahaha)

5/30/2017 9:07 PM

 **yannick** :

 ><https://ift6266h17.wordpress.com/project-description/>

> 
(the final project for the class)

5/31/2017 2:20 PM

 **naoto** :

 >andyh616: I'm not available this week so I can't help you but it seems quite relevant to what I'm doing. I use t-SNE on training/calibration data and mapping real-time data by finding the smallest Euclidean distance <http://naotohieda.com/muse/>

5/31/2017 2:25 PM

 **andyh616** :

 >thats awesome! the package we are developing currently plots multivariate data using PCA, but we are extending it to support, t-SNE, MDS, and a whole bunch more.  Hopefully, we'll support streaming data soon.  I'd love to chat about your project sometime :slightly_smiling_face:

5/31/2017 8:25 PM

 **bciguy** :

 >yannick luckily my company is about to release a device that will create a massive database of single channel forehead (FP1-FP2) EEG  during sleep (or any other activity) from thousands of users around the world. What would you like to see  us do with this database that could be impactful for NeuroTechX and the field in general?

6/1/2017 1:35 PM

 **andyh616** :

 >if anyone is interested, we're hacking on eeg data visualization using hypertools: <http://hypertools.readthedocs.io/en/latest/> today and tommorow in the mozilla sprint. the goal is to get streaming eeg data from openbci in a realtime plot as a line in 3D using dimensionality reduction. if you are interested in getting involved, let me know!

6/1/2017 2:12 PM

 **bryan_j** :

 >andyh616: dano

6/1/2017 4:39 PM

 **vjayaram** :

 >What sort of dimensionality reduction?

6/1/2017 4:57 PM

 **dano** :

 >Awesome! I might not be able to help much since I'm also working on a mozilla sprint project: <https://github.com/NeuroTechX/eeg-101>

> 
However, I'd love to take a look at the library. Showing some cool data visualization might be fun for this upcoming outreach event we're holding

6/1/2017 8:50 PM

 **andyh616** :

 >vjayaram - currently, PCA. but we're going to support ICA, t-SNE, MDS, Isomap and a few more

6/1/2017 8:51 PM

 **andyh616** :

 >dano no worries! eeg-101 looks great! i've almost got a streaming version working, but it will be a little while til its generally usable i think

6/15/2017 4:34 PM

 **davidevaleriani** :

 >Hi everyone, I have started working with the OpenBCI 8bit after a few months and the board does not connect to the dongle anymore, although the LEDs are on. I have changed the battery with a new one, but nothing. Do you have any suggestions on what to try?

6/21/2017 4:53 PM

 **davidevaleriani** :

 >Hi all, I am trying to use the MNE library to extract CSP features from a 4-class MI dataset, however I get the following error:

> 
TypeError: 'float' object cannot be interpreted as an integer

> 
The 2-class version works perfectly. Do you have any example code for 4-class CSP? Am I missing something?

7/4/2017 1:56 PM

 **jk** :

 >Hi peeps. Where can I find various sets of eeg data online?

7/4/2017 2:09 PM

 **alexandre.barachant** :

 >jk 

> 
<http://bnci-horizon-2020.eu/database/data-sets>

> 
<https://zenodo.org/search?page=1&amp;size=20&amp;q=EEG&amp;type=dataset&amp;access_right=open&amp;sort=mostrecent>

7/4/2017 2:11 PM

 **alexandre.barachant** :

 >jk what kind of EEG are you interested in ?

7/4/2017 6:56 PM

 **pat** :

 >Has anyone here looked at Muse's raw_fft channels? I'm trying to recreate the /eeg -&gt; /alpha_absolute processing using the notes at <http://developer.choosemuse.com/research-tools/available-data#Raw_FFTs_for_Each_Channel>, but neither the /eeg -&gt; /raw_fft0 nor /raw_fft0 -&gt; /alpha_absolute appear to be working

7/4/2017 6:58 PM

 **pat** :

 >/raw_fft0 -&gt; /alpha_absolute feels like it should be the simplest, but calculating alpha power from each /raw_fft0 doesn't match the /alpha_absolute emitted just after:

7/4/2017 7:13 PM

 **pat** :

 >is there usually averaging added to alphas to smooth them out over time?

7/5/2017 8:22 PM

 **benjamindeleener** :

 >fred-simard nice work! I was wondering if you would like to share the code so we can try to reproduce? It would be awesome to try get the same results as you

7/5/2017 8:55 PM

 **dano** :

 >pat good detective work!

7/5/2017 8:56 PM

 **dano** :

 >Any ideas, hubertjb?

7/6/2017 12:43 PM

 **qbarthelemy** :

 >&gt; 1. SSVEP is detected using CCA (cross-canonical Analysis) 

> 
Yes. But CCA is not able to treat a resting-state class, contrary to Riemannian geometry. See <https://hal-uvsq.archives-ouvertes.fr/hal-01351623/document>

7/6/2017 1:26 PM

 **fred-simard** :

 >okbalefthanded qbarthelemy Thanks guys, really nice of you, I didn't expected to get answers. To be fair, I already had the answers for myself, although I haven't wrote the report. Since you were nice enough to share your methods with me, I'll do the same:

> 
1. I got some pretty good results using Bayesian classifier over the native statistics of the SSVEP, that is the f-test. The parametric formulation in the Bayesian framework leads to an intuitive formulation of the problem that allowed me to build a weakly-supervised detector that performed at 75% without any training (biased toward idle, so I had less than 2% of false positive).

7/6/2017 10:27 PM

 **samuelbg13** :

 >Hi guys! I am interested in BMIs and neurorobotics. I wanted to ask about the "mental commands" of the cognitive suite of the Emotiv Epoc, the famous virtual cube. Has anybody worked with that?  I am just wondering how does it really work, since as they brand it could seem it performs better than the standard paradigms of motor imagery decoded from SMRs.  How do they manage to get rid of all the perturbations? And assuming that the perturbations are somehow useful as part of the signal (i.e. muscle signals from the face), do you think it would work with locked-in and completely locked-in patients?  Any literature on the matter would be much appreciated :slightly_smiling_face:.

7/7/2017 1:40 PM

 **jk** :

 >alexandre.barachant I found these interesting - music (<http://doc.ml.tu-berlin.de/bbci/BNCIHorizon2020-MusicBCI/BNCI_MusicBCI.pdf>) and emergency brake (<https://lampx.tugraz.at/~bci/database/002-2016/description.txt>)

7/7/2017 1:43 PM

 **jk** :

 >alexandre.barachant I'm trying to get openvibe to run on my mac. Did you ever get chance to write that script for mac port?

7/7/2017 2:26 PM

 **alexandre.barachant** :

 >jk no, I gave up Mac and came back to my good old Linux laptop.

7/9/2017 5:22 AM

 **rashi** :

 >I've tried it out but I am no neuroscientist so I don't know what your words mean.  Perhaps you could ask questions and I'll tell you what I recall from trying it out

