---
{"dg-publish":true,"permalink":"/church-training-audio-bible/misc-tips-and-trivia/vocal-mix-tip-multiband-compression/","tags":["learning"]}
---


This Vocal Mix Tip was highlighted in this video clip
https://www.facebook.com/share/r/1EBSnRqwzb/?mibextid=wwXIfr

It's not a secret in the industry, but it is definitely a bit of an intermediate tip! We will break this down and hopefully impart the full extent of understanding and implementing this Vocal Mix Tip.



# Walkthrough
There are a few things to know ahead of this concept. Open up each heading to learn more, or skip to a heading that you need a refresher on.
If you're across all the prerequisites, go on and get to [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Putting it all together\|#Putting it all together]]

Enjoy the learning!

## Prerequisites
1. [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Compression\|#Compression]]
2. [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Side Chain\|#Side Chain]]
3. [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Dynamic-EQ\|#Dynamic-EQ]]

## Compression
Compression is a basic concept, where there are four basic parameters :
- [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Threshold\|#Threshold]]
- [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Ratio\|#Ratio]]
- [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Attack\|#Attack]]
- [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Release\|#Release]]

> [!info] Additional Parameters
> Compressors most commonly have those parameters to adjust, but there are occasionally additional parameters such as makeup-gain, hysteresis, hold, and knee. 


### Threshold
When an audio signal level hits the threshold level - set by you, the user, the other 3 parameters come into play.

### Ratio
Ratio is **how much** the audio is compressed once the threshold is hit. 
In example, a 2:1 ratio would mean that if the original audio was supposed to get to -8db, the threshold is set at -10db, and ratio is set to 2:1...

Then the resulting output would be -9db ; where after the threshold of -10db every increment of 2db results in only a 1db increase.

In the scenario where original audio is supposed to get to -2db, threshold is -10db, and ratio is set to 4:1... what is the resulting audio output level?

Try to calculate it before revealing the answer below!

> [!done]- Answer
> The result is -8db!
> 
> Threshold being set to -10db and ratio at 4:1 means that after -10db, every 4db increase will only result in 1db of additional level. Therefore, -2db which is 8db louder than -10db, will only result in a 2db increase of level after -10db, bringing us to a -8db output level!


### Attack
In simplest terms, the attack parameter dictates how **fast** the compressor acts once the signal hits the threshold. 

A smaller value (e.g. 2ms) means that the compressor acts faster in compressing the signal as soon as the threshold is hit.

A higher value (e.g. 40ms) means that the compressor waits a moment (40ms) before compressing the audio.

What does this mean in terms of how it sounds? A faster attack will compress more of the percussive elements (think anything snappy, poppy and full of attack/bite)

> [! Example] Controlling Transients
> When dealing with instruments such as a kick or snare drum that is too harsh/bitey, a fast attack can help compress the sharp and quick transients whilst still allowing the rest of the *body* and deeper sound still come through. 

> [!info] Quick Tip
> While not a hard and fast rule, a general idea is for percussive elements (things that are hit to make sounds) a faster attack may help, this can include a bassist slapping or plucking the bass strings or a very aggressive pianist!


### Release
In contrary to attack, the release is the time that the compressor takes to let go after the audio signal drops **below** the set ratio.

In essence, it is how quickly it STOPS compressing AFTER the audio goes below the aforementioned threshold. Open up the tip below regarding Release vs Hold to learn more.

> [!note]- Release vs Hold
> Release is how quick the compressor lets go of the audio, and hold is how quick BEFORE the compressor lets go of the audio.
> 
> Picture this, you are the compressor, and I am the audio signal. Door is the ratio.
> 
> When I try to push past the door, how fast you close the door on me is the **attack.**
> When I stop going through the door, how long before you let go of the door is **HOLD**
> When you finish waiting, how fast you physically open the door again is the **release**
> 

You will mostly be playing with attack and release to adjust the "tone" of the compressor, by controlling the transients or the body of the signal. The additional parameter **hold** adds another dimension of control, but you will find 80%-90% of the time you will suffice just fine with the attack and release.



## Side Chain
Side Chain is actually a feature within most\* compressors.

What it does is that instead of using the original audio to determine when to compress the signal, it listens to a separate signal, to trigger the compression.

An example of this is using the kick drum to trigger compression of the bass guitar.
Another example is the very Vocal Mix Tip we are discussing now - where we use the instruments (full band) to trigger the compression of the vocals!

> [! example]- Picturing a side-chain
> In understanding compressors, we learn that when the signal reaches the threshold, the signal gets compressed, and when the signal drops below the threshold, the compression stops.
> All this is triggered by the same audio signal.
> 
> Think of this - If I am running fast enough, someone will slow me down and tell me not to run indoors. This is how a regular compressor works.
> 
> With a side-chain, I can be walking at a regular pace, but if someone ELSE is running fast, the threshold is actually set for THEM and when they trigger it, I will be told to slow down, and there is no affect to the other person.
> 
> This is how side chain works, another signal is used ONLY as a trigger, and the compression applies to the original audio signal

This feature is very handy in creating space for elements in a mix where two or more instruments/components of a mix take up the same frequencies, and we want to prioritize one over  the other.

Without compressing each and every component, we can compress one signal, based on the other.
This way when the vocals are not singing - we do not need to compress the instruments. Only when they clash, the compression works on the instruments and gives a little space back to the vocals.

> [! danger]- Going too deep
> Whilst this is a very rewarding trick up the sleeve, too much side chain compression can lead to a very bad mix!
> 
> As you can imagine, it requires a lot more management and awareness. Managing compression of a signal based on it's own level is much easier than managing compression based on other signal levels.
> 
> For instance if you forget that you have side chain compression, you might struggle to get the guitars to stand out because it constantly gets compressed by the vocals when they sing.


## Dynamic-EQ
Dynamic EQ is also known as Multiband Compression.

> [! info] EQ -  Equalizer
> EQ stands for Equalizer.
> An EQ works by adjusting the gain level of different frequencies. 
> Common examples of use cases are to "shape" the sound by making it sound brighter, or bass heavy.


If you are familiar with what an EQ does, a dynamic EQ is just an EQ, but instead of working 100% of the time, it only works when triggered. It is like an EQ that works on a threshold, similar to a compressor.

> [! info]- EQ vs Dynamic EQ
> A normal EQ will adjust the sound 100% of the time. If you boost the bass, it will just keep doing that (normal operation)
> This is expected and what we usually want.
> 
> A Dynamic EQ only works on a threshold, so it will only boost (or cut) frequencies when it is triggered, so it becomes more creative and does not affect the normal tone of the signal unless the threshold is reached.


If you think of it the other way around, it is like a compressor. It only works when it hits the threshold, BUT instead of compressing the WHOLE signal (low and high frequencies alike), it only applies compression to a specific BAND in the frequency spectrum. This is sort of like applying an EQ to the signal, but only when a specific threshold is hit.

Using this knowledge, you are then using an EQ with some "rules".

> [!example] Example of "Rules"
> - IF the guitar gets too boomy and bassy, reduce the bass frequencies
> - IF the guitar is not too bassy, stop reducing the bass frequencies

This will result in a guitar that sounds more **consistent** as when there is not enough bass or *body* there won't be any cutting of that frequencies, but when it gets too messy, it reduces it so it mostly matches what it sounds like earlier.

## Putting it all together

Now that we have all that information - let's try to break it down into stages.

- All the vocal mics are going to a vocal mix. It is a mix that only consists of vocals and nothing else.
- All the instruments are going to a band mix. It is a mix that only consists of instruments and nothing else.

If you listen to it, the band mix ONLY has the band, and the vocal mix ONLY the vocals.


The signal flow might look a little like this - with the individual channels going to their respective mixes, then those two mixes go to the MAIN Mix.


- Main MIX
	- Vocal Mix
		- Vocals 1
		- Vocals 2
		- Vocals 3
	- Band Mix
		- Drums
		- Bass
		- Guitars
		- Keys



> [! info] Configuration
> Our current church audio configuration does not have this set up. As this requires separate mixes purely for band and vocals, which then gets mixed into the MAIN mix, we do not have the capacity to do it whilst also making In-Ear mixes from the same console. 

Both the BAND and the VOCAL mix are going to the same Master Main mix.

In the BAND mix, we apply a [[Church Training - Audio Bible/Misc Tips and Trivia/Vocal Mix Tip - Multiband Compression#Dynamic-EQ\|#Dynamic-EQ]] on the mix itself. This will affect the whole instruments mix as a whole but leave the vocals unaffected.

In the settings panel of the Dynamic-EQ, the side-chain is selected as the VOCAL mix.
This means that the VOCAL mix level will be the trigger for the Dynamic-EQ.

> [! tip]- Side Chain reminder
> As mentioned earlier, by setting the side chain as the vocal mix, the vocals are actually unaffected directly by this compressor/EQ. The processing is only happening on the BAND mix.

The Dynamic-EQ on the BAND mix is set to do a reduction or **cut** of a few db (usually around -3db) at 2kHz. 
This will mean that the band will get an EQ applied of -3dB on the 2kHz frequency region - but ONLY when the vocals trigger the threshold.

When the vocals are not singing (or not hitting the set threshold), then there is no EQ applied to the whole BAND mix. This will result in a big, full sounding band.

However, when the vocals are all singing in unison and triggering the threshold, the EQ reduction of -3db at 2kHz is applied to the BAND mix, which gives a bit more space for the vocals to stand out in the mix WITHOUT having to push the vocals above the band.

This gives proper separation to hear the vocals clearly and sound "big" during the big and heavy moments of the songs whilst retaining the fullness of the band when there is only one singer or none.

