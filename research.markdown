---
layout: page
title: Research
permalink: /Research/
---

<br>

# **Current**
<br>

I) **Adaptation through focus and switch mechanisms**

This doctoral work was advised by Naomi Feldman and Bill Idsardi. The aim was to model a potential mechanism of adaptation in listening to speech in noise. This mechanism describes how listeners focus on reliable parts of the speech signal, while they ignore whatever is irrelevant in that moment. Speech carries redudant information (cues) pointing to linguistics units we are looking for in the signal. However, at any given moment, there may be noise or uncertainty present about how reliable these cues are. To maximize the information rate we are getting from the signal, we are proposing an internal perceptual strategy that focuses on the reliable parts of speech (cues) at any specific moment. For robust perception, listeners internally allow the unreliable parts of the signal to become so uncertain that they become irrelevant and focus only the reliable parts.

This project is aiming to show that perception is extremely flexible: we can pull relevant information out of the speech signal, despite any present noise, by internal adaptation that is guided by our statistical knowledge of speech sounds. 

<br>

II) **Recognizing repetitive yet not neccessarily identical patterns**

Thomas Schatz and I are aiming to describe an automatic, low-level mechanism of recognizing repetitive sounds by either adults, infants or animals. Our goal is to show that such a mechanism can be at play in various seemingly unrelated effects observed by prior research: white noise memory effects, compressed speech recognition, MMN effects, potentially infant sound learning (memory of words, syllable repetition and more). In all these, repetition of sounds is recognized by the brain, even when the inputs have no content (white noise), when the listeners are not consciously aware of it (MMN) or they do not speak the language yet (infant word memory).

To do this, we are describing efficient neural processing that takes as input a continuous signal with local time dependencies, spatializes a small chunk of the signal (i.e. 300ms) and given that predicts the input at the following time step. The combination of the spatialization and prediction is done by reservoir and predictive coding mechanisms.

<br>

III) **Bat's Echolocation Perception Modeling**

In collaboration with Jochen Triesch and Julio Hechavarria. Bats rely heavily on their echolocation to navigate. Their auditory cells have been shown to be sensitive to many auditory cues of the echolocation calls in experimental setups. Their neural cells are sentitive to specific frequency ranges, as well as to durations of the calls and also to delays between the calls. Our aim has been to build a simple neural network as we can (specifically, an auto encoder) that encodes real bat echolocation calls. We can then inspect the model to see if the model is sensitive to the same auditory cues as the real bat. To obtain similar auditory cue sensitivity, we propose some architectural adjustments that likely happen in the brain. Namely, those involve propagating information from one neuron to the next, where depth naturally makes a neuron more complex. Additionally, we combine information of neurons sensitive to low frequency and neurons sensitive to obtain neurons sensitive to both frequency ranges. With this, we mimic passive auditory perception of a brain tuned to highly specific calls that help the bat navigate and forage.

---
<br>

# **Prior**
<br>

*My **Master Thesis** was modelling non native speech perception and comparing it to human performance. The main idea behind was to explore where the mis-perception of non native speech sounds happen.*

Jurov, N. (2019). Phonetics or Phonology? Modelling Non-Native Perception (Unpublished Master thesis). University of Paris, Paris, France. [https://github.com/n-ika/abx_test_strut/blob/master/jurov_memoire.pdf](https://github.com/n-ika/abx_test_strut/blob/master/jurov_memoire.pdf)

<!-- <span style="font-size:1em;"> -->
<span>Perceptual differences of non native speech have been discussed extensively in the literature before. In order to shed a light on where the mis-perception occurs (phonetic/low-level or phonology/higher cognitive level), I used several models and compared them to human performance. I used an ABX discrimination task of non words (either English or French possible CVCs) on French and English natives and I was looking for a native language influence in non native speech perception. I found out that unsupervised model (k-means clustering) shows some native language effect, while the supervised model (ASR - kaldi) does not. Both are outperformed by the acoustic baseline (MFCC vectors distance predictions). Overall, the best fit for human performance seem to be the universal phonetic transcriber - bottleneck features distances predictions, which have the highest accuracy in the ABX task and improve the k-means clustering results.</span>

<br>

---
