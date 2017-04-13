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

