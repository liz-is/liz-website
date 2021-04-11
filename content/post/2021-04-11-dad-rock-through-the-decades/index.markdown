---
title: 'Dad Rock Through the Decades'
author: Liz Ing-Simmons
date: '2021-04-11'
slug: now-that-s-what-i-call-data-science-dad-rock-through-the-decades
categories: []
tags: []
subtitle: '*Now That''s What I Call Data Science!*'
summary: ''
authors: []
lastmod: '2021-04-11T15:53:57+02:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---



I've reached the age where many of my friends are becoming parents, which is both very exciting for them and slightly terrifying for those of us who feel like we were 18 only yesterday! 
I'm 30, so that's right on cue: for [babies born in the UK in 2019](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/livebirths/bulletins/birthcharacteristicsinenglandandwales/2019), the average age of mothers was 30.7, and the average age of fathers was 33.6. 

Nevertheless, there's something unsettling about seeing songs I listened to as a teenager, or danced to at university, included in a "Dad Rock" compilation!
I found out about "Now That's What I Call Dad Rock!" via [Boing Boing](https://boingboing.net/2021/04/03/the-now-thats-what-i-call-music-dad-rock-compilation-will-haunt-you.html) last week, and suddenly had an idea of what to do with a week off work during a pandemic and terrible weather. 

## The Compilation



You can listen to the 2018 compilation "Now That's What I Call Dad Rock!" on Spotify [here](https://open.spotify.com/playlist/11lFedD9gvEIrhQVrKrQlk?si=whfwZOTJT-Srtb8Il6cNow). It includes 59 tracks. 
In order to find out more about about what the compilers considered to be Dad Rock, I took the track listing from the Boing Boing article and used Wikipedia to find out the year each song was first released[^1], and what genre(s) each song falls into[^2]. 

[^1]: For Whitesnake's "Here I Go Again '87", since the 1987 version of the song was specifically included, I used 1987 as the release year. 
[^2]: "Addicted to Love" by Robert Palmer had no specified genre on the song's Wikipedia page, so for that song I used the genres given on the artist page.

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-3-1.png" width="672" />

The oldest song included is from 1968 ("Born to Be Wild" by Steppenwolf), while the most recent song ("The Sound" by The 1975) was released in 2016 - only  2 years before the compilation. The album spans an impressive 48 years. 
1987 is the median release year, while the mean is slightly later at 1991.
The distribution of release year seems to be bimodal, with distinct peaks for songs released before and after 1990. 



A typical dad of a newborn in 2019, with an average age of 33.6, is younger than 22 of the tracks of the album, and 
61% of them were released before he was ten years old. 

## Genres



Are the songs chosen to represent Dad Rock really rock? I've gotta say I have my doubts about some of them... As a hopefully less subjective source, I took the genres assigned on Wikipedia. Most songs (35) have more than one genre (median genres = 2), and there's a total of 45 different genres in the dataset. 

Tallying up the most frequent genres across all tracks, it's pretty clear that the most frequent are all sub-genres of rock.

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-6-1.png" width="576" />

In fact, 52 songs have a genre that contains the word "rock". So far so good. What about the rest?


|Song                  |Artist        | Year|Genre                        |
|:---------------------|:-------------|----:|:----------------------------|
|"Ace of Spades"       |Motorhead     | 1980|speed metal                  |
|"There She Goes"      |The La's      | 1988|jangle pop                   |
|"Ho Hey"              |The Lumineers | 2011|indie folk                   |
|"Crazy Crazy Nights"  |Kiss          | 1987|glam metal                   |
|"In Too Deep"         |Sum 41        | 2001|pop punk                     |
|"The Sound"           |The 1975      | 2016|house, pop, disco, synth-pop |
|"Here I Go Again '87" |Whitesnake    | 1987|glam metal                   |

There's no obvious pattern for these seven songs - "glam metal" appears twice, but the genres are pretty varied, and so are the release years. I thought that more recent songs might be more likely to not be classified as rock, but that doesn't seem to be the case. 

Related to this, I wondered if the most common sub-genres of rock had changed over time. 

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-8-1.png" width="672" />

This is a pretty rough analysis given the low numbers of songs, but it looks like the most common genre, "hard rock", is only used for songs released before 2000, and "alternative rock", "pop rock", and "indie rock" became more common over time.

What's missing in the plot above is that actually these top five genres only account for 39 % of all assigned genres.

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-9-1.png" width="672" />

And, of course, while I can make some guesses, I don't know how common these genres are in *all* music from these decades - and that would be a whole other project. Instead, I went down a different route for follow-up analysis. 

## Opinions



I decided to see if my biases about what does and doesn't count as Dad Rock were shared. I prepared a short survey and distributed it to friends and family. Including my own assessments, I received 22 responses. 

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-11-1.png" width="672" />

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-12-1.png" width="576" />



