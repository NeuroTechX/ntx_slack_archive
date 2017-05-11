######machinelearning_ai

2/23/2017 4:22 PM

 **sydneyneurotechx** :

 ><http://spectrum.ieee.org/the-human-os/biomedical/imaging/ai-predicts-autism-from-infant-brain-scans>

2/24/2017 5:13 PM

 **r** :

 >What algorithms do you use for optimization: RandomSearch, gridSeacrg

2/24/2017 10:53 PM

 **r** :

 >zzzzzzzzzzz:zzz:

3/13/2017 11:20 PM

 **sydneyneurotechx** :

 >To view archived text from Slack please visit:

> 
<https://github.com/NeuroTechX/ntx_slack_archive/blob/master/machinelearning_ai.md>

3/16/2017 3:41 PM

 **yannick** :

 >Hey jnaulty I know you like awesome list. Here is a good one on deep learning: <https://github.com/terryum/awesome-deep-learning-papers>

3/22/2017 2:26 PM

 **harris** :

 >Although I've been teaching myself machinelearning &amp; ai through various online resources and my studies, where would be a good place for me to learn how to apply this knowledge to BCI related datasets

3/22/2017 2:28 PM

 **yannick** :

 >In few months from now the answer will be NeuroTechEDU (no pressure sydneyneurotechx) :wink:

5/4/2017 10:19 PM

 **watson** :

 >Of potential interest. Python probabilistic inference library handling modeling, inference and validation: <http://edwardlib.org/>

5/4/2017 10:20 PM

 **watson** :

 >As seen advertised on this post by Dustin Tran: <http://dustintran.com/blog/on-model-mismatch-and-bayesian-analysis>

5/11/2017 7:20 PM

 **dano** :

 >Anyone know a good way to use sklearn on multidimensional data?

5/11/2017 7:23 PM

 **dano** :

 >I'd like to be able to give models data from multiple EEG electrodes, but want to make sure I'm doing that in the best way possible

5/11/2017 7:25 PM

 **dano** :

 >For example, I can train with a matrix X that is `epochs x FFT_freqbins` and get pretty good results, but I'd like to do `epochs x FFT_freqbins x nb_electrodes`

5/11/2017 7:27 PM

 **dano** :

 >shouid I just make X 2 dimensions but flatten any extra dimensional data into a large number of features? `X = epochs x (FFT_freqbins_electrode 1 + FFT_freqbins_electrode 2 + ...)`?

5/11/2017 9:15 PM

 **maxim** :

 >yep that's how you'll do it unless you have some smarter way to use the structure

5/11/2017 9:15 PM

 **maxim** :

 >certainly fine for the first attempt

5/11/2017 10:21 PM

 **dano** :

 >Thanks, related question. Do you have a favorite way to work with multi-dimensional data? Coming from the Pandas school, I've immediately started using Panels, but they're actually getting deprecated in the next update!

> 


> 
Aren't all the cool kids working with Tensors these days? How are they doing that in Python?

5/11/2017 10:29 PM

 **pat** :

 >I would guess numpy - a tensor is pretty much an ndarray

