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

5/11/2017 10:30 PM

 **pat** :

 >unless using libraries like Theano or Tensorflow, which have their own inbuilt tensor type

5/11/2017 10:34 PM

 **dano** :

 >Hmm, I must be confused about the difference between Tensors and multidimensional arrays then. I thought tensors were all 3D+ matrices in code

5/11/2017 10:38 PM

 **maxim** :

 >yeah and multidimensional array is exactly a 3D+ matrix

5/12/2017 3:03 PM

 **watson** :

 >dano, coming from Pandas you might just consider using `xarray`, which is the chosen replacement for Panel. Its basically a wrapper on a numpy ndarray: <http://xarray.pydata.org/en/stable/why-xarray.html>

5/14/2017 3:03 AM

 **octonomy** :

 >to my understanding, a tensor is just another way of saying 4 dimensional array

5/14/2017 4:33 AM

 **yrenard** :

 >tensor is any matrix with 3 dimensions or more

5/14/2017 6:08 AM

 **pat** :

 >Is it? I believe tensor can be any dimension &gt;= 0, just that 0/1/2 are usually called scalar/vector/matrix

5/14/2017 4:19 PM

 **yrenard** :

 >yes you are right pat, just that 3 and above have no specific name :slightly_smiling_face:

5/17/2017 8:34 PM

 **dano** :

 >At 10:30am tomorrow PST, 1:30 est, there will be a talk at Google I/O on Tensorflow for Non-Experts at this link: <https://www.youtube.com/watch?v=safQDjgDVAQ>

11/2/2017 12:14 AM

 **sydneyneurotechx** :

 >Been a while since anyone's posted in here, but neat article from Nature. "Machine learning of neural representations of suicide and emotion concepts identifies suicidal youth" <https://www.nature.com/articles/s41562-017-0234-y>

11/2/2017 7:11 PM

 **psoulos** :

 >That study is really cool. There is some valid criticism in the Reddit thread about it tho: <https://www.reddit.com/r/MachineLearning/comments/7a4j2t/r_machine_learning_of_neural_representations_of/>

