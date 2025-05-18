---
title: owning my music
permalink: posts/{{ title | slug }}/index.html
date: '2024-09-12'
tags: [how i do things, tech]
---

Time is a flat circle: 25 years after I started listening to music on my computer in the form of MP3s in folders, I find myself back where I started, only this time with M4As and FLACs and a whole plethora of other options besides Winamp and foobar2000.

(slight upfront digression: that said, I was pleasantly surprised to learn that [foobar2000][1] is well and alive, and even available for the Mac these days. But my needs have evolved a too much for fb2k to still be a viable option. I did try.)

My drive to own my music once again really began with general frustration over every single streaming option:
- I’ve been a Spotify user since 2009, but I have come to really dislike their algorithm-driven interface (Kyle Chayka [sums up the frustration well][2]), how little they pay their artists, and the poor audio quality at a time when its competitors are streaming FLAC and lossless files (even on my built-in iMac speakers, I can hear the difference!).
- TIDAL is really good. It sounds the best to my (albeit untrained) ears, and has an interface that suits my listening habits. TIDAL is the only service I have found that separates individual tracks you have favourited from whole albums in your library, which means my ♥ Tracks list is comprised only of songs and not whole albums. However, my big problem with TIDAL is that the catalogue is significantly smaller and lacks a lot of my favourite music. I listen to too many Japanese anime and stage play soundtracks that aren’t available on TIDAL.
- Apple Music is the best balance of everything for my needs. The cons are that I do find the interface clunky, and there’s the one big glaring unchangeable issue with it, which is *Apple*. I don’t love the idea of my music being tied to my Apple ID, plus if you want to play music on your smart TV, you’re out of luck unless you buy an Apple TV. That said, they pay artists better than Spotify, have a very good catalogue, and they have lossless audio.

At the same time I was navigating these dissatisfactions with streaming music, I was growing disillusioned by the rapidity and suddenness with which streaming services could purge media from their lineups, and I had been gradually accumulating DRM-free ebooks and Blu-rays of shows I love as a safeguard. For years, I’d also been buying anime and stage play soundtracks off Apple Music Japan when they weren’t streamable on my usual services. I was already moving in the direction of owning my media, so starting to invest into building my own music library seemed like a logical next step.

## where to buy music?
I started with the iTunes Store, as I was already an Apple Music user, but quickly learned to my great annoyance that Apple Music only provides lossless audio files for streaming. Not for purchase. You get 256kbps AAC files with purchased music.

Even if I was only deluding myself that I could hear the difference, I felt that if I was going to do this thing seriously, I wanted the best quality audio files I could get. What if I invested into a better sound system in the future?

So here’s where I’ve been buying my music:
- [Bandcamp][3] - I listen to a lot of ambient music and game soundtracks, and have found Bandcamp to have a great catalogue for them. Very affordable, and pays artists well.
- [HDTracks][4] - expensive, but more likely to have major label releases than Bandcamp. My second port of call if Bandcamp doesn’t have the thing I want.
- [OTOTOY][5] and [Mora][6] - where I get all my Japanese music, and some not-Japanese music that inexplicably isn’t available on English-speaking platforms (Brian Eno’s “Ambient 1”, for example).
- Physical CDs - I order them online, or raid Tower Records and HMV when I go to Japan, since a lot of my listening is anime and stage play soundtracks. I personally really enjoy seeing the CDs on my shelf and I feel like the audio quality of a ripped CD is superior to anything else. But shelf space at home is sorely limited, so I only get physical CDs if I really love the album or I can’t find a lossless digital version anywhere.

I still have a long wishlist, but to avoid spending way too much in one shot, I’ve been spreading out my purchases over the months, and I’m really happy with the state of my library now.

One thing maybe worth noting here is that my listening habits are very instrumental-heavy. I don’t listen to music with words when I’m working, reading or writing, which is pretty much all I do on the computer (otherwise I’m watching things or gaming, which obviously also means I’m not playing music). So that means I don’t actually need a huge library of music because I tend to put on instrumentals that don’t distract me. At time of writing I have 146 albums in my library, half of which are instrumental, and it takes a *long* time to get tired of listening to 70 instrumental albums. I don’t think I would feel the same if I mainly listened to music with words (I only do so when I’m commuting). So someone with different listening habits from mine might take a longer time to get their library built up to an acceptable state.

## how do i get my music on all my devices??
Of course, the thing about streaming is: you get used to having your music everywhere. This suddenly becomes a huge problem when you are no longer streaming.

When I listened to folders of MP3s on Winamp, I had no other devices. At the most, I had an iPod that plugged into my computer and loaded all the MP3 files via iTunes, and that was it. Now, I have a phone, an iPad and a work laptop, which makes at least three other devices that need to sync my music.

I tried initially the old-school way—dragging and dropping music to my devices, keeping a synced Dropbox folder of music on my work laptop—but this was untenably laborious and also, more importantly, did not sync ratings and play counts across devices. I carefully maintain smart playlists such as “rating more than 3 stars + not played in the last two weeks”, so ideally, I needed a solution that would allow me to upkeep this.

If you don’t mind the labour and don’t need to sync ratings and playlists, the best app I found for coordinating music across Apple devices is [Doppler][7]. It’s really clean, nice to use, transfers music quickly, and plays FLAC files (Apple Music does not).

## enter Plex
[Plex][8] is where I wound up eventually, and I’m really happy with it. It’s a media server that catalogues all your movies, TV shows and music. You can run it off your home computer, and once you get the Plex media server up and running, if you leave your computer on and connected to the internet all the time, you can stream anywhere on any of your devices. (Caveat that this does not work if your computer is on a double router setup, like a mesh wifi connected to your main router. I ran into a lot of problems with this.)

The free version of Plex is already plenty usable, but after using it for a while I was pretty sure I would be around for the long haul, so I dropped the money for a lifetime Plex Pass (you can also sub monthly or yearly) which among other things unlocks the power to download your media and Sonic Analysis for your music library. Sonic Analysis is the secret sauce that makes Plex really shine with your music. It scans the sonic traits of your library, and with it, [Plexamp][9] (Plex’s amazing in-house music app) can do things like generate music mixes and track radio based on sonic similarity. It can take a playlist and after every track, insert a few others that are sonically similar to it before going to the next track. It’s a really fun way of listening to my music and has allowed me to explore my library in ways I haven’t before. I really find it boring now to just listen to music on shuffle like I used to, without the intelligent features of Plexamp and Sonic Analysis.

I started out running Plex off my iMac at home, but due to issues with my double router setup blocking remote access, as well as the need for more storage space for my ballooning media library, I eventually took the leap and got a Synology NAS (DS224+). Plex runs beautifully off it, remote access works cos the NAS plugs directly into my main router, and I no longer fear running out of storage space. A NAS probably an overkill solution for your average user, but if you, like me, have terabytes of blurays ripped, I recommend it heartily.

I still have Spotify for emergencies, but it’s really just to test listen to music before I buy it. These days for music discovery I turn to good old internet radio and YouTube. Otherwise, I am really happy with putting a guest DJ on Plexamp and letting it play my library for me, and it is so satisfying knowing I own all this music.

[1]:	https://www.foobar2000.org
[2]:	https://www.newyorker.com/culture/infinite-scroll/why-i-finally-quit-spotify
[3]:	https://www.hdtracks.com
[4]:	https://www.hdtracks.com
[5]:	https://ototoy.jp
[6]:	https://mora.jp
[7]:	https://brushedtype.co/doppler/
[8]:	https://www.plex.tv
[9]:	https://www.plex.tv/plexamp/
