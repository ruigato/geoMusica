![geoMusica romanesco Logo](http://www.ruigato.info/blog/wp-content/uploads/2020/07/logo21_romanesco_720.png)

“We have also sound-houses, where we practise and 
 demonstrate all sounds, and their generation. 
 We have harmonies which you have not, of 
 quarter-sounds, and lesser slides of sounds. 
 Divers instruments of music likewise to you 
 unknown, some sweeter than any you have, together 
 with bells and rings that are dainty and sweet. 
 We represent small sounds as great and deep; 
 likewise great sounds extenuate and sharp; 
 we make divers tremblings and warblings of sounds,
 which in their original are entire. We represent 
 and imitate all articulate sounds and letters, 
 and the voices and notes of beasts and birds. 
 We have certain helps which set to the ear do 
 further the hearing greatly. We have also divers 
 strange and artificial echoes, reflecting the 
 voice many times, and as it were tossing it: 
 and some  that give back the voice louder than it 
 came, some shriller, and some deeper; yea, some 
 rendering the voice differing in the letters or 
 articulate sound from that they receive. 
 We have also means to convey sounds in trunks 
 and pipes, in strange lines and distances." 
 
 Sir Francis Bacon, in "The New Atlantis", 1626
 

///////////////////////////////////////////////

geoMusica 1.210301

Copyleft 2016-2021:
Rui Gato
gato.rui@gmail.com
http://www.ruigato.info/blog/
https://www.patreon.com/GeoMusica


///////////////////////////////////////////////

# **ABOUT:**

geoMusica is a tool to make music with geometry. Compose geometries and listen to the musical translation in realtime, perform and experiment with the Sacred Geometry inspired methods and be amazed by the beauty hidden within the Mathemagics. 

it is structured as a multi-layer composing tool, focused on geometrical parameters that can be set with special proportions and shapes, and should be used has a MIDI note generator, connected with your favorite electronic instruments to reproduce the musical output. Therefore, should be considered as a generative MIDI sequencer in terms of families of musical software, and its aimed at musicians that use electronic tools for creation. 

this project started as a personal research on Sacred Geometry studies, within the scope of the 3 year introdutory course that I attended led by Prof. Luis Elye, to the amazing field of knowledge hidden inside the Traditional geometrical legacy. with roots lost in time, this knowledge proved fundamental in bringing ordered geometrical shapes that generate meaningful musical correspondance, and revealing a hidden structural connection between geometry and music that becames obvious when exploring this tool.

as the research evolved, i've managed to do some outputs in form of talks and live concerts, that generated a surprising reaction on the interested audience, namely my fellow coleagues geometers, the TD artists community, and the Boom Festival community. that feedback gave meaning to the publication and release of this tool.

the aim for publication is to support the further development of this tool, either by other developers in the open-source spirit, or by anyone that use this tool and want to help supporting via the Patreon platform.

it is also a way of retribution to the fantastic TouchDesigner community, that along the years of using TD allways gave generously without asking for return.

**DEDICATION:**

this public release of geoMusica is dedicated to my grandfather Francisco Alves Gato. I did'nt had the luck of meeting him personally, but I know that he, has many of us before and certainly after, was one of the humans that felt the sparkle of the search for Knowledge and Beauty, which led him to research on a special tuning for the Portuguese Guitar. I know we would had good times together playing with geoMusica!

///////////////////////////////////////////////

# **PLEASE SUPPORT DEVELOPMENT:**

https://www.patreon.com/GeoMusica

This Patreon page is made for supporting the research and development of the GeoMusica software. If you like to use GeoMusica, or if you just want to help, please join in!


///////////////////////////////////////////////

# **INSTALL AND USAGE INSTRUCTIONS:**

this package contains the 3 processes of geoMusica:

## **geoMusicaEngine:** 
its the heart of geoMusica, where the geometrical shapes get converted into MIDI signal, and also frequencies and triggers for geoMusicaSynth. the Engine tries to run at 480 fps, so it matches the MIDI standard timming resolution. You should connect the Engine via MIDI to your favorite sound source, preferably a Polyphonic Aftertouch able synth so you can enjoy the full spectrum of frequencies that geoMusica generates. IMPORTANT: the Engine is hardwired to output each layer in a separate MIDI channel, so Layer 1 goes to MIDI Channel 1, and so on.

## **geoMusicaUI:**
the control center for the system, here you define all the parameters to generate the compositions, create presets with TDMorph (Darien Brito https://github.com/darienbrito) and synchronize with external systems.

## **geoMusicaRender:**
here the geometry gets visualized, in the most synthetical way possible, so you can focus on the musical composition. You can run the Engine without the Render if you want.

## **geoMusicaSynth (extra module):**
(currently only available if you are a supporting Patron)
A wavetable synth inspired in the "howtoaudio.toe" examples (Owen Kirby), designed to fully render the frequencies generated by the GM system, without any constraints of temperament or tuning systems. This will translate directly the GM data into sound, using wavetable synthesis to give more timbre options. Still in early development but already supports voice allocation, effects, and sample selection.



1. install Derivative TouchDesigner 2021.10330 (current official)
(https://derivative.ca/download/)

2. allow firewall access to TouchDesigner on both 
private and public networks (if asked)

3. run "GeoMusica.toe"

4. wait for the 3 processes to open

5. on geoMusicaEngine, under "settings" page, select your MIDI Out Port. If you don't have a virtual midi loopback utility, I recommend:

For PC:
 loopMIDI by Tobias Erichsen (http://www.tobias-erichsen.de/) for localhost usage, and rtpMIDI for remote usage.

For Mac:
IAC driver in Audio MIDI Setup
https://help.ableton.com/hc/en-us/articles/209774225-How-to-setup-a-virtual-MIDI-bus

6. If you are an Ableton user (which I strongly recommend for sequencing and composition), you should install TDAbleton from the TDABLETON preferences pane, Utilities page.

7. If you don't have easy access to sound generation modules, go to https://dotpiano.com/ and enjoy your GeoMusica in a nice webSynth Piano!

///////////////////////////////////////////////

# **LICENSING:**

Since we are artists/programmers and not lawyers, I trust you will give credit where credit is due and respect the licence: 

GNU General Public License v3 (GPL-3) 

This means that if at some point you would like to use this tool in a commercial endeavour or you do not want to disclose the source code you will get in touch first, so a fair arrangement can be made.


///////////////////////////////////////////////

# **AKNOWLEDGEMENTS:**

geoMusica has benefit from the incredible work of Darien Brito with TDMorph, that allowed for a seamless integration of a preset system that is at the same timea parametric generative tool by itself, expanding the possibilities of geoMusica greatly.

geoMusicaSynth is based on the very much helpfulTD community asset from Owen Kirby, clarifying the correct way to do audio in TD, "howtoaudio.toe".


///////////////////////////////////////////////

# **SPECIAL THANKS:**

to my wife and kids that generously agreed to share our time with this life project, 

special thanks to my Sacred Geometry teacher: Luis Elye,

special thanks to this developers from the TD Community that contributed with inspiration, code or other to this project:

Fermat Spiral .toe inspiration - Calvin Zirk,
TDMorph - Darien Brito,
Line intersections python script - Vytenis Zagorskis,
howtoaudio (in TouchDesigner) - Owen Kirby, 
eventCHOP usage for ultraoptimization on geoMusicaEngine - Wieland Hilker,
wisdom along the way - Ivan delSol, Idzard Kwadijk, Felix Larreta, Roy Gerritsen, Tim Gerritsen, 
private beta team - Darien Brito, Roy Gerritsen, Tim Gerritsen.

and last but not least, shout out to the Derivative team, without you guys this would not be possible!

///////////////////////////////////////////////

Enjoy!

Rui Gato
gato.rui@gmail.com
http://www.ruigato.info/blog

patreon page:
https://www.patreon.com/GeoMusica

facebook project page:
https://www.facebook.com/geomusicasoftware

youtube channel:
https://www.youtube.com/channel/UC7Hu034JhXIkvVUFGZE40QA/

instagram project page:
https://www.instagram.com/geomusica.software
