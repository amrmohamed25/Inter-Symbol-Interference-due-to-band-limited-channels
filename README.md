# Inter-Symbol-Interference-due-to-band-limited-channels
In this part, you will investigate another common channel in digital communication systems, which is the 
band-limited channel. As the name suggests, the channel only allows a limited range of frequency 
components to pass, while blocking frequency components outside this range. We investigate the simplest of 
such channels: a channel that has a flat response in the allowable range. 
The channel obviously limits the kind of signals that can pass unchanged through the channel, because if a 
signal has frequency components that are outside the allowable range of the channel, these components will 
not pass and therefore the output signal from the channel will be changed from the input signal. This issue 
will face the most common of signals that we use to represent bits: the square signal!
Guidelines: The first thing you need to show here is the effect of a band-limited flat channel on the square 
signal. You need to create a band-limited channel such as the one in Figure 1, with a band 𝑩 = 𝟏𝟎𝟎 𝒌𝑯𝒛. 
Then generate a square pulse of duration 𝑻 = 𝟐/𝑩, pass it through the filter, and then look at the output. 
You need here to show the signal before and after the channel, both in time and in frequency.
As you can see, the square signal is no longer a square signal coming out of the channel. In fact, the shape of 
the square signal out of the channel has “leaked” outside of the duration 𝑇 = 2/𝐵 that was intended at the 
beginning. If there are multiple square signals after each other (one square signal for each bit), these leaked 
parts will interfere with the signals of other bits. This phenomenon is called Inter-Symbol Interference (ISI).
Guidelines: The second thing you need to show is the effect of two consecutive square signals as they pass 
through the channel. Consider the same channel and the same square pulse duration as before. The plots
you need to show here are in time domain only. Namely, 
1. Show two plots of the first square pulse: one before it passes through the channel, and one after.
2. On top of the two previous plots, show similar plots for the second square pulse. Plot this pulse in 
the two plots using a different color, so that the shapes of the two pulses are distinguishable on 
the plots.
3. Note that you will have to pass the two squares separately, i.e., you cannot create the two pulses 
together in the same vector and pass that into the channel. If you do it this way, you won’t be able 
to clearly distinguish the two pulses. 
