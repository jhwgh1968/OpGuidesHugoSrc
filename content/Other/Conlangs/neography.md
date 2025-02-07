

# Neography & Conlangs:<br>Constructed Information Exchange

<!--

TODO: Explain why are there multiple programming languages in the DSL bit

https://psychomotorischetherapie.info/website/wp-content/uploads/2015/10/LMA-Workshop-Sheet-Laban.pdf - ask jan Usawi about this.

https://sozysozbot.github.io/akrantiain2/manuals/introduction/introduction_en.html

-->

<link rel="stylesheet" href="/css_overrides/light.css">

I would like to exchange information with you about the exchange of information. If you would like to continue this information transaction please continue scanning these symbols with your eyeballs and interpreting them in the language you think they are meant to encode using your past knowledge and cultural context. 

---

Broadly speaking, what is the purpose of language?

[No, seriously, think about this for a moment]

Probably the broadest possible answer is to communicate ideas and knowledge.

Now, *usually*, the intent is to do that:

* As accurately as possible
* As succinctly as possible 
* As unambiguously as possible 
* In a way that humans can pronounce

Additionally, natural languages will:

* Reflect their culture
* Evolve over time
* Have non-conformities in spelling and pronunciation
* Have a writing system that is capable of being written by humans

Now, some of those can interfere. If we strive for absolute accuracy and no ambiguity, we increase verbosity. Requiring humans to write them may limit how well machines can read them. Of course there are many other factors at play to, but for the most part natural languages are the result of a slow, Darwinian process, not the result of a craft. But what if we do try to construct a language?

What I want to explore on this page is what others have done, limitations of and hacks used in languages today, why someone might want to make their own language and/or script, and what we can learn from prior work. This includes everything from scripts and languages made for fantasy novels to programming languages, musical notation, and other fields that rely heavily on symbolic input methods.

## Some Natural Language Context

At risk of turning this page into a linguistics lesson, I want to provide just a *tiny* bit of context and a mental nudge to recall that, yeah, language is freakin' weird.

Sure, some languages may order things differently (orange<sub>adj.</sub> cat<sub>n.</sub> or gato<sub>n.</sub> naranja<sub>adj.</sub>? ) or grammatical gender, but those are only the tip of the iceberg.

* What *sounds* are in the language?
* Does the language convey information in pitch or tone? (Like asking a question in English)
  * Is this conveyed in the [writing system (vietnamesetypography.com)](https://vietnamesetypography.com/tone-marks/#:~:text=Vietnamese%20is%20a%20tonal%20language,-heavy%E2%80%9D%20(n%E1%BA%B7ng).)?

* How many words for different colors are there?
* How precisely is time conveyed grammatically? 
  * Past, Present, Future?
  * Far Past, Past, Immediately Past, Present, Immediately following, This day, This week, In this lifetime, Far Future?
* Word length / Compounding
  * Does the language go full German or Icelandic, or are words short and rarely to never compounded?
* Is the language written left to right, top to bottom?

Obviously, this is glossing over whole subjects and intricacies that linguists have spent lifetimes on and that I am absofuckinglutly (Hey, look at that, an *infix*) not qualified to talk about. My point is that there's a lot of ground to be covered and explored for conlangs and neoscripts - so, uh, what are those?

## Exploring Existing work

I already have a page on this website about {{< button relref="Other/conlangs/tokipona" color="other" >}} toki pona {{< /button >}} , one **con**structed **lan**guage or "conlang" that I particularly enjoy. Being in its community I've been introduced to many interesting ideas in the conlang and the adjacent **con**structed **scripts** (conscript) communities - also sometimes called "**neoscript**", I assume to avoid the existing usage of the term meaning to enlist in the armed services

{{< columns >}}

In these communities, I have seen some absolutely unhinged ideas:

<img src="/other/burgerscript.webp" style="border-radius:1em;">

<--->

</br>

Of course, most of what's on display here isn't this ridiculous. Some of these neoscripts are for conlangs - fully new languages that need their own writing system as no existing system would even work.

Some only make new symbols for existing alphabets - like BurgerScript. 

Some dramatically challenge the idea of what it means to "write" something. 

Some are used for building a world and culture in a fictional story: like Elvish in Lord Of The Rings.

Some serve as a form of artistic expression.

{{< /columns >}}

Some are an attempt to make a writing system that [fits an existing language better](https://www.omniglot.com/conscripts/finnishscript.htm) than system used today. 

Some are made to allow for sharing or concealing messages in mediums that wouldn't normally be thought of as places thoughts could be recorded at all.

### Conlangs

There are a few categories of conlangs:

* Those that try to act as "a global language for all", formally called "International auxiliary languages" or IALs
* "Engineered Languages" usually try to make a language that's all about making it as good as possible given some restrictions or intended use case. Arguably, IALs fall into this category.
* "Artistic languages" are those made primarily for their aesthetics or making a world feel more fantastical. Usually these are used for TV, novels, comics, or other entertainment media.

For the purposes of this page, I think engineered languages are the most interesting. I'll still talk about art langs

[TODO conlang critic]

I think I need to talk about a few interesting conlangs and what makes them interesting. 

* Toki Pona - 
* Esparanto -
* Kēlen - https://www.terjemar.net/kelen/lajathin.php
* Lojban - 

So, let's look at some scripts, what makes them interesting, and talk about what we can learn from them.

To get started, I want to look at scripts that have particularly interesting applications - that is, scripts which exist because the typical writing systems don't work well where they're used.

### (Somewhat) Practical Neoscripts

There's one of these you probably already know of, as you've probably seen a fair number of 7-segment displays in your life, and you've probably seen them used to represent Latin characters:

<span class="conlang" style="font-size:1.2em;">󿜿 󿜆 󿝛 󿝏 󿝦 󿝭 󿝽 󿜧 󿝿 󿝯 󿝷 󿝼 󿜹 󿝞 󿝹 󿝱 󿜽 󿝶 󿜅 󿜞 󿝴 󿜸 󿜫 󿜷 󿝫 󿝳 󿝧 󿜱 󿜭 󿜇 󿜾 󿝪 󿝾 󿝉 󿝮 󿜛 󿝙<span>

Now, you could probably debate if this is a new script or just a font, since clearly the intent is to show Latin characters - but because of the limitation being so severe, I think it might count, albeit barely. This is an important distinction though, because we don't want to consider every different font a whole new writing system!

So, more true to the actual spirit, lets start with [HexCasting](https://www.curseforge.com/minecraft/mc-mods/hexcasting), a Minecraft mod which requires the user learn to write spells into this hexagonal grid,

![](https://media.forgecdn.net/attachments/456/342/screenshot1.png)

Okay, neat, sure, but maybe it's a contrived example. It's solving a problem that could've been done by just letting the user type out commands (albeit that would be less fun). So, what about working around a real limitation...

[Pixelscript](https://omniglot.com/conscripts/pixelscript.htm) exists for people working on pixel art. At extremely low resolutions, there's just not room to add a normal signature and have it be legible anyway <a class="ptr">(1)</a>. Unlike with the 7-segment display Script/Font, this doesn't try to look like an existing alphabet.

![img](https://omniglot.com/images/langsamples/udhr_pixelscript.gif)

{{< attribution >}}From [omniglot.com](https://omniglot.com/conscripts/pixelscript.htm). Text is *"All human beings are born free and equal in dignity and rights. They are endowed with reason and conscience and should act towards one another in a spirit of brotherhood."* which is Article 1 of the Universal Declaration of Human Rights{{< /attribution >}}

Of course, there are other cases of fitting in writing when the tools or space for doing so are limited. A good example of this is [Nailscript](https://omniglot.com/conscripts/nailscript.htm):

When I tried writing my name I did realize you might want to wear ear protection when using this script!

![NailScript for English - Single Row Version](https://omniglot.com/images/writing/nailscript1.gif)

![Sample text in the Nail Script - Rats Nest style](https://omniglot.com/images/langsamples/udhr_nailscript4.gif)

{{< attribution >}}Again from [omniglot.com](https://omniglot.com/conscripts/nailscript.htm), and again this is Article 1 of the Universal Declaration of Human Rights {{< /attribution >}} 

It simplicity in construction, compactness, and use of the 3rd dimension as nails lay over one another really pushed my intuition for what a script could be.

Of course, the number one reason to make a new script is for a new language that needs a way to represent a possibly novel phonetic inventory (the list of sounds it uses) or needs to reflect the culture it's being designed around if it's for an art lang such as Klingon or Na'vi

As you can imagine, there's many more of these, but maybe Nailscript got you thinking, there's another use here: hiding messages. We'll talk about this more when we get to "why you might want to do this yourself" section.

## Limitations & Hacks

So, language isn't perfect. Natural languages especially so, but almost all languages suffer from a variety of problems. For example:

* Flexability - Can you say what you actually mean?
  * This can be a lack of vocabulary
* Ambiguity - Can what you've said mean more than one thing?
  * This includes everything from the existence of sarcasm to homophones
* Cultural differences - Will someone from a different culture still get the same meaning?

So, lets pick on a language to look at why these can be a problem:

### Flexibility: Western Music Notation

[TODO] {{< smalltext >}}[SMuFL](https://www.smufl.org/fonts/) is used to display this music on the web - it's basically just a really clever way of (ab)using fonts.{{< /smalltext >}}

Sometimes people will say that "Musical notation is a universal language among musicians"

and, uh, I have to call BS. It might be true that most musicians can read it, but that doesn't mean it's well suited to representing their art. It's <s>great</s> fine if you want to convey the idea as expressible by the instruments of western traditions for classical arrangements, but it's not universal, as I'm sure anyone who plays music with microtonal elements, complex timings, or where the timber of the instrument can be adjusted over time can tell you.

{{< columns >}}

For example, here's a track that uses microtonality. This look incredibly visually noisy. To some extent that level of visual noise is going to be present in any system with this level of flexability, but that also doesn't mean we couldn't do a lot better.

<--->

<iframe width="100%" height="250" src="https://www.youtube.com/embed/y_nQgNKSl5Y" title="Rare Chords: Supermothrian Polychords | Maj7b4b8♮13‡14⇂16b23 (harmony in 31-edo)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

{{< /columns >}}

More over, reading music is a bit difficult to learn. This has lead to the "universality" of the notation being a lie as most any guitarist will be familiar with tabs:

<pre>
e|---------------------------------------------------------------|
B|---------------------------------------------------------------|
G|-----------------------------------2---------------------------|
D|------------------2------4---5--4-------5---4--------2---------|
A|---------------------------------------------------------------|
E|---------------------------------------------------------------|



e|---------------------------------------------------------------| 
B|----2--3--2--2-0-----------------------------------------------| 
G|--4--------2-------------0--2------0---------------------------| 
D|-------------------0---2------4--2---4--2-4--------------------| 
A|-----------------2--------------------------5---7--------------| 
E|---------------------------------------------------------------|

</pre>

{{< attribution >}}

Part of the theme for the Halo games, ripped from ultimate-guitar.com, which is a dumpster fire of a website which I will not link directly to.

{{< /attribution >}}

Which can have various flavors of markings, including using `~` for vibrato, putting `X`'s above the lines for palm mutes, `/` for sliding from one fret to another, etc. It's a bit crude compared to sheet music and requires your guitar's tuning match the one listed, but it's quite easy to read.

But music today is often made in a piano roll,

[TODO] picture

and has historically been made in trackers,

[TODO] picture

In either case, the notes can carry a lot of added information - pitch bend (now sometimes per-note) and multiple data streams to represent the virtual turning of knobs. That interface is a writing system of sorts - you could even argue different input devices and instruments, as long as they're just giving a computer digital data, are really just different writing utensils.

There have been some efforts to make new music notation systems [Hummingbird](https://www.hummingbirdnotation.com) and [Clairnote](https://clairnote.org) both make moderate improvements (depending on who you ask) to the existing common music notation system, but don't really attempt to totally reinvent the wheel. [Dodeka](https://www.dodekamusic.com) goes a bit further, but mostly feels like an advert for a piano that just flattens the keybed.

To avoid loosing the thread here though, there's still a problem here. The only *true* writing system for modern music production that caries the information about the tracks is now whatever interface the software provides.

I should also point out there are other musical notation systems from cultures I am less familiar with. The [Musical Notation Wikipedia page](https://en.wikipedia.org/wiki/Musical_notation) shows some of these, but I'm not even sure how to go about research most of these in depth.

https://ofb.net/~elaforge/karya/doc/overview.md.html

microtonal stuff

Orca + that hex one

https://www.anaphoria.com/centaur.html

https://en.wikipedia.org/wiki/Numbered_musical_notation

https://github.com/skarukas/springs

https://jird.readthedocs.io/en/latest/index.html 

https://academo.org/demos/19-tet-keyboard/

### Ambiguity: Emoji

{{< speech triode >}}

Okay, but, what about Emoji? 🤔

{{< /speech >}}

Well, yeah, they're a writing system. They may not be incredibly precise if the exact symbol you need doesn't exist, but they can be rather information dense. 

👔💼🔜🏠👉👌 👨‍❤️‍💋‍👨 🍑🍆❓

Is a pretty clear message. 

Clearly talking in only emoji wouldn't really be ideal, but it's still wrong to discount it outright as a conlang/writing system (or would it be a natlang?)

But, it does have a massive fucking problem: it doesn't display consistently on different platforms. It boggles my mind that it's a crap shoot for if 🏳️‍⚧️ is a trans flag, or a trans symbol followed by a white flag (⚧️🏳️). Pride or surrender? Similarly, the Windows operating system is cool with gay pirates, 🏳️‍🌈🏴‍☠️, but no country flags will render correctly (though it is possible your browser will compensate, here's a US flag: 🇺🇸). More complicated yet, will the Taiwan flag (🇹🇼) render if you're in China? Doubtful. 

This means the medium itself isn't reliable.

We can more-or-less equate this with dialects or jargon. If you read the word "Biscuit" you may be thinking of a cookie or a scone depending on which side of the Atlantic you're on.

### Cultural Differences: Tone markers & txting styl 

[TODO] couldn't a conlang integrate this into the punctuation better?

[TODO] historical notes Obelos (†) and Metobelos (‡), bring in standards for marking up text for correction, 

If I'm in the car with someone and they ask me to send a text for them, I get uncomfortable because I don't know *how* they text.

Think about texting someone young that you've texted every day for years, they *probably* don't normally put full stops/periods at the end of sentences, so when they text

> Hey. We need to talk.

That's a different text from

> Hey we NEED to talk

Which is different from

> hey we need 2 talk...

I mean, most people would find any of the above alarming, but 1. probably has you going "Ah shit." while 2. has you frantically trying to figure out why and hoping that it's not something you did, while 3. might have you concerned about their happiness.

Related, usage of `\s` and other [tone markers could be better](https://www.youtube.com/watch?v=3bYXy1jT3m8). 

So, what if we just had some additions to the way we represent text? I'm not going to pretend to have any good ideas for what this would be, but 🤷‍♂️ it's a thought.

### Cultural Differences Bonus Round: Gender

He/Him She/Her Xe/Xyr Ze/Sir Fae/Faer They/Their ...

Different people have a different level of acceptance of different pronouns... because something-something culture war? Regardless, conlangs may provide different pronouns, often either adding one for non-binary individuals or just using a unified, un-gendered pronoun. <a class="ptr">(1)</a>

If this sounds difficult, just remember, the correct way to refer to someone in any language is whatever they want you to use, just like in English!

If you want a deep dive into pronouns, I recommend [this video from Language Jones (YouTube)](https://www.youtube.com/watch?v=Kh22m1QG6i4).

# TODO

{{< speech triode >}}

What about fonts?

{{< /speech >}}

Note on fonts being this but baby steps, with some being pretty wild - espically with ligatures

Music fonts... I forgot what these are called.

tools of communication - keyboards, hand gestures, voice, graphs, braille, etc. What weird ones exist?

Encodings

## Why Someone Would Make Their Own Language (or script)

Before we get in to any of the concrete reasons, it's important to acknowledge someone may make a conlang or neoscript for no other reason than the joy of the act of creating. Still, most people will have an end goal in mind or a challenge in the design. Let's look at some motivations.

### Hiding Messages

Hiding messages is an art form of itself, and can have a myriad of different requirements:

* Maybe you want any onlooker in the know to be able to decode the message
* Maybe you want it to be difficult to see there's a message at all
* Maybe you want it to be obvious there's a message and make it difficult to decode
* etc. etc.

This does start to go into a conversation about [steganography (Wikipedia)](https://en.wikipedia.org/wiki/Steganography). <a class="ptr">(2)</a>

{{< quote "[Wikipedia](https://en.wikipedia.org/wiki/Steganography)" >}}

**Steganography** is the practice of representing information within another message or physical object, in such a manner that the presence of the information is not evident to human inspection. In computing/electronic contexts, a computer file, message, image, or video is concealed within another file, message, image, or video.

{{< /quote >}}

{{< columns >}}

I have even made a tool for hiding binary data into the least significant bits of .WAV files (and it's even GPU accelerated!), and I suppose that means you could do something like stack ideas, using one of the few-pixel fonts with a binary data visualization tool like hobbits (pictured) but that's a bit meta.

<--->

![](https://github.com/Mahlet-Inc/hobbits/raw/master/docs/hobbits_screenshot.png)

{{< attribution >}}Example image from [the Hobbits GitHub repo](https://github.com/Mahlet-Inc/hobbits){{< /attribution >}}

{{< /columns >}}

To avoid losing the topic of this page, let's look at a few scripts that fill this function:

* [Babuk](https://www.omniglot.com/conscripts/baduk.htm) can be used to hide messages in a game of Go

### Better Serving Disability

#### Vision: Braille & Screen readers

##### Screen readers

##### Braille

[TODO] I really need to find someone who uses braille for this.

Clearly, people don't always want to have their ears occupied by whatever they're reading or be listening out loud and potentially disturbing others. Also, it's not exactly practical to have every sign include an embedded speaker repeating the same word forever. So, braille:

Braille is *mostly* just a font, but there are some special rules, mostly for contractions to make common words shorter. 

a-z0-9: ⠁ ⠃ ⠉ ⠙ ⠑ ⠋ ⠛ ⠓ ⠊ ⠚ ⠅ ⠇ ⠍ ⠝ ⠕ ⠏ ⠟ ⠗ ⠎ ⠞ ⠥ ⠧ ⠺ ⠭ ⠽ ⠵ ⠚ ⠁ ⠃ ⠉ ⠙ ⠑ ⠋ ⠛ ⠓ ⠊

Being that I'm not vision impaired and that I can't read braille, it's hard for me to know what is good or bad about it, but, I do know there's a real problem with the cost of braille displays. Even the least expensive option I could find was ~$700, but that one only displays 20 characters at a time. I also don't know if there are programs to make these devices more affordable.

Question: Why not single character that changes under the finger or let it encode to each finger, resting on the keyboard, like "bumping" the key in the home row? https://www.cs.unc.edu/~gb/blog/2007/01/22/an-inexpensive-tactile-braille-display-and-keyboard-with-reciprocity/

https://mymodernmet.com/braille-neue-typeface-kosuke-takahashi/

Holy shit the marketing for braille tech is slimy



#### Deaf: Sign Languages

### Same language, new system

Intriguingly, some neoscripts use an existing language but instead of just mapping the letters to new symbols change the way we think about a 'character' all together. 

<div style="float: right; width: 30%;">
<img src="https://www.omniglot.com/images/langsamples/udhr_fontok.gif" style="border-radius:.4em;filter: sepia(40%) hue-rotate(-50deg);">

{{< attribution >}}Example text in Fontok. Again, this image is from [omniglot](https://www.omniglot.com) and is Article 1 of the Universal Declaration of Human Rights{{< /attribution >}}

</div>

Of these, I particularly like [fontok](https://www.omniglot.com/conscripts/fontok.htm) which adds a significant number of characters as each *sound* (not character) in English is given its own symbol. Of course it doesn't hurt that text written in fontok is breathtakingly beautiful.

<br style="clear: both;">

### World Building & Art

[TODO] mention newspeak here too.

Getting into the more artistic uses, in *[The Art of Language Invention](https://www.amazon.com/Art-Language-Invention-Horse-Lords-World-Building/dp/0143126466)* by David J. Peterson - the guy who made Dothraki for *A Song of Ice and Fire* / *Game of Thrones* - discusses how Dothraki wasn't just a jumble of foreign looking language ideas but was informed by the culture of its fictional speakers and built up around their ideas and values. This same attitude applies to the script [which is on omniglot as well](https://omniglot.com/conscripts/dothraki.htm). 

Perusing omniglot there were some scripts that stood out to me as having a strong "for non-humans this would be good" flavor - these really make sense if you want to make a world feel alive for more than just the humans in it.

* [Scar](https://www.omniglot.com/conscripts/scar.htm) looks to be a good option for creatures lacking the dexterity afforded by fingers
* [12480](https://www.omniglot.com/conscripts/12480.htm) looks well suited to something which would communicate with binary but need a way for it to be legible to meat-based creatures if necessary.

There are many, many more that have been used for creating fictional fantasy or sci-fi stories of course. The most obvious that everyone knows is Tolkien's various languages from the *Lord of the Rings* trilogy and related works, such as Quenya (which is written in Tengwar),

<div class="conlang">
    <blockquote>             </blockquote>
</div>

{{< attribution >}}This font is [Fairfax HD](https://www.kreativekorp.com/software/fonts/fairfaxhd/) by [KreativeKorp](www.kreativekorp.com), which is licensed under the [open font license](https://github.com/kreativekorp/open-relay/blob/master/FairfaxHD/OFL.txt) It is used for all of the conlang displays on this page which are not static images. Some of the examples on this page are also copied directly from that page. {{< /attribution >}}

Of course, even for humans just having a new script and language alone can go a long way. 

Interestingly, even the discussion of language itself can be moving and artistic, as anybody who has seen Arrival (2016) can attest to,

<img src="/other/arrival.webp" style="border-radius:.4em;filter: sepia(70%);">

More fundamentally though, a script with meaning only to the author can still be beautiful. The calligraphy and attention to detail can still be inspiring even if the viewer doesn't know the full meaning. Hell, sometimes not knowing the meaning can be a statement in itself - making a script that looks like an existing language for commentary on a culture isn't unheard of. It's also not uncommon to hear songs using words in a meaningless (or at least grammatically incorrect) way for how they sound in any language's music - think phrases like "La, La, La", "Do-Wop", etc. - so it's only natural that some people would love the way that some conlangs sound and the different forms of expression that may be possible in the lyrics when using conlangs. 

My favorite conlanging musician is jan Usawi. They release some absolute bops that are sung in toki pona:

<iframe class="no-box" style="border: 0; width: 100%; height: 120px;" src="https://bandcamp.com/EmbeddedPlayer/track=3618927353/size=large/bgcol=333333/linkcol=0f91ff/tracklist=false/artwork=small/transparent=true/" seamless><a href="https://janusawi.bandcamp.com/track/sina">sina by jan Usawi</a></iframe>

On top of this, some tools which effectively have their own language for interacting with them can inspire new art because of the limitations or paths of least resistance of the language. On that note,

## What We Can Learn

### Domain Specific ~*Languages*~

In programming, there's this idea of domain specific languages. These are programming languages that don't really do everything - instead they do one thing really well. The most famous two are [regex (Wikipedia)](https://en.wikipedia.org/wiki/Regular_expression) and [SQL (Wikipedia)](https://en.wikipedia.org/wiki/SQL). I think you can apply that idea can apply in other niches too. If you think about *speech* vs *writing* vs *signing* vs *braille* and how each can have multiple co-existing (or competing) standards / systems, it's really not a stretch of the imagination.

My friend jan Usawi recently made a fantastic language called {{< button relref="Other/conlangs/rhapsodaic" color="other" >}} Rhapsodaic {{< /button >}} which is detailed on this website, but as a TL;DR: Rhapsodaic, as a core design philosophy, values preserving emotional meaning over all else... and I mean all. It means the actual meaning <s>might</s> will be ambiguous, but you'll definitely know how the speaker is feeling and it can be said more accurately than in most any other language. It's also very pretty as a script.

Where I see it as particularly interesting is using it along side a native language to either add context or clarity to something that's already written or have it be intermixed, mid sentence, with the native language as necessary - similar to how Regex and SQL are used in programming, sprinkled into other code written in a more capable but less in specific purpose language.

Frankly, I find it remarkable how well this analogy work out. Both programming DSLs and some engineered conlangs (such as Rhasodaic) share the common attributes of being purpose-driven, having a specific grammar and syntax, and - provided enough experience with them - are more concise for their application than the more general purpose alternatives.

This really got me thinking about what else we could do to make specific languages for talking or writing about different subjects. Arguably this is already common as systems for expressing trade knowledge are common,

* Musician → musical notation 

* Electrical engineer → circuit schematics
* Chemical engineer/Chemist →chemical drawings

But if we think about each of those, there are tools for working with them to make it easier than writing/drawing them by hand,

* Musicians can use digital audio workstations or musical composition software which allows them to playback the music as they alter the composition.

* Electrical engineers will use schematic entry software and simulation software such as [circuitjs](https://www.falstad.com/circuit/circuitjs.html)
* Chemists have various tools for entry, like [chemdraw](chemdrawdirect.perkinelmer.cloud)

Of course, there are many tools out there and I don't think it's unreasonable to consider each a different dialect, some more closely related than others.

Bringing this back around, what if we made software packages for language entry? Something that does more than just grammar and spell check but rather helps us consider how to think about complex ideas. Definitely not like Grammarly, sorta like Chat-GPT, but really I'm thinking about more tools like [prosodic (GitHub)](https://github.com/quadrismegistus/prosodic)

[TODO] screenshot

More than that though, imagine if we we could have a sort of "craft an emotion" dialogue that can help people write Rhapsodic?

But, I do want to wrap back around to that programming idea briefly. There are some programming languages that are pretty radically different in the way we input and output information, so while they may not be "writing systems" in the traditional sense, I think they're worth a look in this list.



Open SCAD

Orca

Geometry Nodes



Ligatures? Old school ascii art fonts. Emoji + unicode, Visual programming (node based)

Zoia, VCV





Within the realm of what we'd still call language, there's some I want to showcase just for being beautiful

* https://www.reddit.com/r/neography/comments/pj8xw4/griddy_script_font_finally_see_comment/
* https://www.omniglot.com/conscripts/sticks.htm
* https://www.omniglot.com/conscripts/beringin.htm
* https://www.omniglot.com/conscripts/chiri.htm
* https://www.omniglot.com/conscripts/keble.htm

Finally, there's some really, really bizzare ones I want to mention

* Pipeline 3D
* Conway Script
* https://www.omniglot.com/conscripts/alfakinetix.php
* https://www.omniglot.com/conscripts/betamaze.htm (also see https://www.omniglot.com/conscripts/patternscript.htm and https://www.omniglot.com/conscripts/spintype.php)
* https://www.omniglot.com/conscripts/6color.php
* https://www.omniglot.com/conscripts/eganes.htm (maybe move this one)

### Math

[TODO] this section still needs a lot of help

Knowing the audience for my website, you were probably mentally screaming above that I didn't mention the most obvious domain with it's own language: Math.

Personally, I think the definition of what should be considered language should be pretty board. It clearly includes this text itself and most of the writing systems above. It obviously includes speech, braille, sign language, and I think most would agree that both math and music constitute "language".

Now, this isn't to say there aren't some definitional lines. I don't think I'd consider a video a language - a medium on which multiple different languages can be expressed, sure - but not a language itself. The line can get blurry though, especially as you dive into data visualization and interactive content.

Regardless, I think it's worth considering how interesting math is as a language. I could tell you about how it's a "universal language", but is that even true?  Probably more so than for music, but not entirely: some languages alive today do use base 20 to varying degrees - French only kind of does, while [Dzongkha](https://en.wikipedia.org/wiki/Dzongkha_numerals), for example, is true base 20 - but if we ignore that, different symbols for the same things, and any system that's just modern math but without <u>⠀⠀⠀⠀</u> then, yeah, universal I think is fair. When the Cosmic Calls were made in '99 and '03, we made some new symbols for displaying mathematics, but sent a message that we thought could be reconstructed to unambiguously show that intelligent life had sent the messages. I highly recommend [reading about it (PDF)](https://www.plover.com/~mjd/misc/Dumas-Dutil/evpatoria07.pdf) .

What makes this interesting is the scope of what mathematical notation can convey in ways that most natural languages really struggle to do cleanly. For anything even remotely complicated to be understood it is to difficult for most mere mortals to process math without writing down anyway. For example if I say,

"One method for computing pi is to take the square root of twelve time the infinite sum, from zero to infinity, of the fraction whose numerator is the quantity negative one third raised to the index of the sum and whose denominator is the doubled index of the sum plus one."

I would think most people would have to write it down to have the slightest idea of what I just said, where if you're already used to reading mathematical notation, 

{{< katex >}}\pi ={\sqrt {12}}\sum _{k=0}^{\infty }{\frac {(-{\frac {1}{3}})^{k}}{2k+1}}{{< /katex >}}

</br>{{< smalltext >}}{{< button relref="Engineering/WrappingUp/latex" >}}{{< katex >}}\LaTeX{{< /katex >}}{{< /button >}} was used to format this math, it's pretty much the language for typesetting math digitally.{{< /smalltext >}}

is comparatively simple.



like the {{< katex >}}\LaTeX{{< /katex >}} above - have the fun of being a language which is has another language used to write it. I don't think that disqualifies them as languages (or at least writing systems) after all, if you have Google Translate translate something from English to Spanish, (and it works) it's not as if we think of the result as just "modified English" - it's Spanish.

Yet, there is still some fun to be had in this line of thought. If I type out 

"Hello World"

That string of text is transferred across the great series of tubes in a binary encoding. Does that make binary - or any base for that matter - it's own language? What if we have some agreed upon meaning for the binary, like we do for Unicode for text? Is it a writing system, a language in itself, or neither?

Does showing an audio spectogram qualify as a writing system? I think it can. Someone trained to do so could absolutely look at waveform or spectogram of a recording to understand what was being said - this idea has been taken further, see [Elektrum (omniglot.com)](https://omniglot.com/conscripts/elektrum.htm) but, say you literally show the raw spectrum, should that count as a script if others were trained to write it by hand? Is having others be able to write it by hand necessary for that definition?

This quickly devolves into interpreting encodings as their own "language" which, like, I *guessssss* could have an argument made for, but it's a stretch. Still, I think there's value in the metaphor, and especially for the technically inclined, thinking about encodings and APIs as forms of communication and taking inspiration from the conlang and conscript/neoscript community can only stand to bring about clever, innovative ideas in storage, compressing, representation, and elegance. I think that's worth being open to. But lets come back to that - 

### How does this tie in to the current AI boom?

I don't know if tools like ChatGPT will be something we all use every day. I also don't know if I *like* it. I have a big ol' blog post about it, {{< button relref="/posts/ai2" color="gradient-border2">}} Does It Still Count As A Tool? {{< /button >}} ,
of which the TL;DR is that I like computers to be deterministic and to feel in control, but using natural language makes me feel like I'm losing some of that, but I also appreciate its utility.

I do wonder if there's room (or necessity) for changes to languages and scripts to fill in some gaps here? 

Would it be good to have a sort of water-mark font that is used to say "An AI wrote this" - maybe having a reserved space in Unicode for it?

Obviously, this would depend on people not intentionally putting it back into the "human use" fonts, which would absolutely happen anyway. There might be some cryptographic way this could be done, but that assumes nobody will just run the generators locally to avoid this and that nobody would want to only partially alter the output - so not a great call. Plus this does sound like a massive pain, doubly so for users with accessibility needs.

What about putting tone indication or other elements into the UI or responses?

{{< speech ai >}}

AI systems could incorporate symbols or icons to indicate the tone of their responses. For example, a thumbs-up symbol could represent a positive or affirmative tone, while a warning sign could indicate caution or a serious tone. These visual cues help users quickly grasp the intended tone of the AI's message, even without relying on punctuation or writing style variations.

{{< /speech >}}

I think applying this the other way could be interesting too. What if we had bots to tell us what the tone of a received message probably is? As an accessibility tool that could be useful. Going a little into black-mirror territory, this could even be used to intentionally filter things. If the text to be shown is interpreted as being overly persuasive and so likely to be advertising, it could be rendered in a different font so the user can be trained to know to take it with a gain (or heaping pile of) salt. This could get pretty nuts.

[TODO] I don't like this section. I think thinking about how LLMs can acutally understand new langs or help invent them is more interesting. It's also possible LLMs could on-the-fly make a reasonable language that no human knows but which could be analyzed from context to try to learn on the fly. This could be useful for a video game, for example, so that it's a different language every play through.

[TODO] Section from Cadey about using conlangs to abuse LLMs

### Completely new forms of expression

Language and the symbols we use to communicate influence the way we think and how we approach problems. If we think of instruments as a writing utensil of sorts, the difference between a guitar and a piano are more than just their sound it's how we interact with them leading to some expressions being easier and harder.

I've already mentioned Rhapsodic allowing for much more emotional expression than existing languages (albeit at the cost of other functions) but I also love how the musical sequencing programming language [ORCΛ](https://github.com/hundredrabbits/Orca) pushes boundaries of creative expression.

<iframe width="100%" height="500" src="https://www.youtube.com/embed/DHYL9hojUTQ" title="bequa la froth ~ armadillidiids" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

... something about 5D chess may fit here, since we can sort of think of chess as a language?

### Radically enhanced expressiveness

### More powerful tools

Already mentioned Orca

There are a huge number of tools with their own in-built languages and a 

* Open SCAD
* Regex
* Teletype
* Geometry nodes
* KodeLife
* SonicPi

### Easier to understand standards

* The music ones

### Inteopability

The ORCA + Ronin + etc system (+ their themes)

Making the situation better for all users, including those of other natural languages, by having better tools - see ligatures and RTL or TtB

### Better exploration of data and connection

[TODO] Still not sure if I can make this relevant?

* The Hyperlink + Obsidian
* https://docs.kanaries.net/rath/explore-data/data-painter
  * link to Computers Suck section about making web data exposed and rendered locally 

## Why are we **not** pushing boundaries?

* Our input methods have become relatively static (keyboards and the keys on them)
* Our systems are designed for rendering plain text and have a hard time with implied style (AST aware syntax highlighting, language servers)
* Legacy compatability - show Arcan/Lash/Cat9
* Some of these are just hard to learn and retain

Simple, Fast, Expressive, Style points (does it look good)

Before we wrap up, I want to say there's an *insane* number of scripts I was unable to link here that I thought were more than deserving of being featured. It's also notable that the only language I speak fluently is English, so my ability to even appreciate the scripts and conlangs more heavily rooted in other cultures is significantly more limited. This has lead me to not feature any of the beautiful scripts that are heavily inspired by existing, natural Arabic, Asian, or braille scripts. If you'd like to see more, I highly encourage you to dive into this yourself and take a stroll though the conscript world without my biases filtering it.

### Thinking about communication as a complete system

Language + Writing system + Font + Input methods + AI assistance + DSLs

## Resources

Obviously this page is littered with links to [omniglot.com](https://www.omniglot.com) and I can not express enough gratitude to Simon Ager for all the effort that must go into maintaining such an incredibly large resource.

Additionally, both [r/conlangs](https://www.reddit.com/r/conlangs/) and [r/neography](https://www.reddit.com/r/neography/) have some great posts and is awe inspiring to scroll through each.

In writing this page I read [The Art of Language Invention](https://www.penguinrandomhouse.com/books/316207/the-art-of-language-invention-by-david-j-peterson/#:~:text=The%20Art%20of%20Language%20Invention%20includes%20a%20new%20chapter%20on,to%20language%20creation%20and%20linguistics.) By David J. Peterson and if you want a jam packed resource on the linguistic skills and concepts that go into conlanging, I can't recommend it enough. It is more of a text book than a gentle stroll though conlanging though.

If you'd like more sort of overview of the conlanging culture, existing languages, etc. - similar to my goals with this page - you may want to watch the documentary *Conlanging: The Art of Crafting Tongues* which, unlike this page, actually had a budget. It's a fantastic watch and acts a sort of language focused behind-the-scenes look into a few of the biggest franchises which have used conlangs on screen. 

Other links you may want to check out include:

* http://www.skyknowledge.com/perssonsscripts
* [neography.com](https://neography.info/writing-systems/)



<ol hidden id="footnotes">
    <li>FWIW, I think <a href="https://www.omniglot.com/conscripts/kfg.htm">KFG</a> may be a better choice if you're working at only a moderately low resolution, as while it's still not a text anybody can read super easily, it's more recognizably text at all, and the differention between glyphs makes it a hair easier to read.</li>
    <li>Not to be confused with Stenography, which is the process of writing in shorthand. Most commonly today this term is used to talk about how court reporters use special keyboards.</br>Also not to be confused with Stegography, the process of writitng with the tail of a Stegosaurus.</li>
<li>Some natural languages have more than two genders for pronouns too!</li>
</ol>


