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

