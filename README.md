# About AlgoCompSynth
Musings on computer music, with some musical amusements

## About the name

"AlgoCompSynth" is a name I made up, from "algorithmic composition" and
"digital sound synthesis". I've had the domain for years but have mostly just
kept renewing it until now. If it's easier for you to think of it as "computer
music", be my guest.

## About my music

As the name implies, I'm interested in music composed and performed by digital
computers. Despite those technologies inexorably moving into the mainstream, I still consider it experimental music.

Although I've dabbled in computer music for decades, even before the Commodore 64, I've mostly been busy doing other things and have published very little. 
Early in 2021, on the 20th anniversary of the passing of [Iannis Xenakis](https://en.wikipedia.org/wiki/Iannis_Xenakis),
I decided it was time to focus on computer music more or less 
full-time. If you're interested in what I have done previously, my SoundCloud 
is at <https://soundcloud.com/znmeb/albums>.

## Musical influences

I was an undergraduate at the University of Illinois when both [Harry 
Partch](https://en.wikipedia.org/wiki/Harry_Partch) and 
[Lejaren Hiller](https://en.wikipedia.org/wiki/Lejaren_Hiller) 
were on the faculty. Iannix Xenakis was a major influence. So were [Alwin 
Nikolais](https://en.wikipedia.org/wiki/Alwin_Nikolais), [Henri 
Pousseur](https://en.wikipedia.org/wiki/Henri_Pousseur),
[Charles Dodge](https://en.wikipedia.org/wiki/Charles_Dodge_(composer)), and [Morton 
Subotnick](https://en.wikipedia.org/wiki/Morton_Subotnick). The music theory 
of [Professor William A. 
Sethares](https://en.wikipedia.org/wiki/William_Sethares)
is also a major influence.

But there have been others, in the popular, symphonic, and electronic realms. 
What I mostly listen to these days: Beethoven, Sibelius, Shostakovich, 
Prokofiev, Khachaturian, Gershwin, Hovhaness, Wendy Carlos, Loreena McKennitt 
and contemporary composers on YouTube:

-   [Sarah Belle Reid](https://www.youtube.com/user/sarahbellereid)

-   [HAINBACH](https://www.youtube.com/user/Hainbach101)

-   [Helene Vogelsinger](https://www.youtube.com/user/L3ine)

-   [Dolores Catherino](https://www.youtube.com/c/dolomuse)

-   [Khyam Allami](https://www.youtube.com/user/khyamallami)

-   [Sevish](https://www.youtube.com/c/Sevish)

-   [Ela Minus](https://www.youtube.com/channel/UCoRNtzYfful7ygcuC8HMQEg)

-   [bad snacks](https://www.youtube.com/channel/UCBCI_QCAMe1hx8UNyvJlM_Q)

## Works in progress

1.  Reworking ["When Harry Met Iannis 
(2009)"](https://soundcloud.com/znmeb/sets/when-harry-met-iannis-2009): I'm 
happy with the score, although I have no plans to generate any more music of 
that type. Markov chains make boring music; cutting the track lengths short as
I did is a cop-out.

    But the sound design badly needs reworking. It was done with 
    [SFront](https://john-lazzaro.github.io/sa/sfman/index.html) and was 
    supposedly a sung vowel emulation. It sounds muddy and awful and 
    nothing like sung vowels. I'll probably synthesize a Partch diamond
    marimba and a chromelodeon for the rework.

2.  Explorations of the [sonicLAB
Fundamental](https://www.sonic-lab.com/fundamental/) synthesizer: I've got the
[Sensel Morph / Buchla Thunder
overlay](https://morph.sensel.com/pages/sonic-lab-fundamental-and-buchla-thunder-overlay)
for exploration, but Fundamental also has microtonal capabilities (think
Partch) ***and*** stochastic controls (think Xenakis).

3.  Using GPUs for synthesis: This is pure research, which is the most fun I
can possibly have. I've got ~four~five of them:

    -   An NVIDIAⓇ Jetson™ Nano,
    -   An NVIDIA Jetson Xavier NX,
    -   An NVIDIA Jetson AGX Xavier,
    -   A laptop with an NVIDIA GTX 1050 Ti, and
    -   A desktop with an NVIDIA RTX 3090.

    I'm currently thinking along the lines of [Professor Stefan 
    Bilbao's](https://www.acoustics.ed.ac.uk/group-members/dr-stefan-bilbao/)
    work, but may end up with something simpler, like
    inverse FFTs. Or even [Real-time additive synthesis with one million
    sinusoids using a 
    GPU](https://www.aes.org/e-lib/online/browse.cfm?elib=15259).
    
    The Jetson project has it's own web presence; see [edgyR-containers:
    Docker Images for NVIDIAⓇ Jetson™ R
    Developers](https://github.com/edgyR/edgyR-containers).

4.  Sea chanteys: Long ago, I used to sing somewhat-less-than-family-friendly
songs in a pub in Annapolis, MD, accompanying myself badly on a tenor guitar.

    But this is 2021 - I still have the guitar, but most of the lyrics won't
    fly any more, so I'm curious what sort of lyrics one of these new-fangled
    generative natural language processing gizmos can come up with. The jury
    is still out on whether I'll sing them myself or force a computer to do
    it.
