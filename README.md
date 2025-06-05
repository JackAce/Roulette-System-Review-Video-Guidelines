# Roulette System Review Video Guidelines

This repository is meant to document the video editing guidelines for producing Roulette System Reviews for the [JackAceDotCom YouTube channel](https://www.youtube.com/@JackAceDotCom).

## Layout
There are several components to the long form Roulette System Review Videos we edit for the JackAce YouTube channel.

![Full Video Layout](img/Video-Layout-1920x1080.png)

Each component is in its own layer in the Adobe Premiere timeline. The bottom-most layer is underneath the other components. I've provided guideline numeric values starting with the bottom layer (the lowest number) up to the top layer (the highest number).

Here are each of the components split out:

* [100 - Roulette Betting Layout](100-Roulette-Betting-Layout.md)
* [200 - iPad Roulette App](200-iPad-Roulette-App.md)
* [300 - Betting Progression](300-Betting-Progression.md)
* [500 - Front Facing Camera](500-Front-Facing-Cam.md)
* [800 - Win/Loss Table](800-Win-Loss-Table.md)
* [900 - Scoreboard](900-Scoreboard.md)
	* [910 - Last Number](910-Last-Spin.md)
	* [920 - Last Win/Loss](920-Last-Win-Loss.md)
	* [930 - Running Win/Loss](930-Running-Win-Loss.md)

## Video Sequences
There should generally be 4 sequences for the Roulette System Review.
* [Seq 01 - Cold Open](S01-Cold-Open.md)
* [Seq 02 - Live Trials](S02-Live-Trials.md)
* [Seq 03 - Simulator](S03-Simulator.md)
* [Seq 04 - Review](S04-Review.md)

These can be split up into 4 separate sequences in Adobe Premiere Pro, but I generally group the Cold Open and the Live Trials into a single segment.

### Cold Open
In this segment, an introduction is give to some HOOK to intice the viewer to watch the video. "WITH THIS SYSTEM, YOU CAN WIN $1000 IN JUST 3 SPINS!". It usually ends with "Let's checkout [SYSTEM XYZ] together, today on JackAce!"

There should be a transition using the `brand/JackAce-Intro-v1.mp4` video between the cold open and the trials.

### Live Trials
Here, we test out the system in "real time" to see how it works and to see how it performs.

### Simulator
The system is run through the JackAce Roulette Simulator and we display the success percentages for 1 to 3 different target win amounts.

### Review
The system is given an review, including the 6 sub-ratings. This segment closes with "Always gamble responsibly, never play 000 Roulette, and peace out, donkeys!"

After this segment, I would like to use the `brand/JackAce-Outro-insta-tiktok-github-v1.mp4` outro video, as it contains social media links. You should also use audio from the `audio/outro` folder for the outro. This folder contains copyright free music.

## Video Composition
There are 3 main video recordings used for the Live Trials sequence.
* The iPad Screen Capture of the Roulette Royale app
* The spin-by-spin bet-by-bet game calling (front facing camera video)
* The system facts and other chatter (front facing camera video)

The first two videos can be time synched. I usually record myself placing the same exact 10 bets rapidly in succession and then removing those same 10 bets. You should be able to hear this audio on the spin-by-spin front-facing camera video and it can be used to sync the two videos. So when the ball lands on 21 red, I should follow up shortly afterwards with "21 Red, that's a whack. Now we increase the bet to $20" or something like that.

The third video has a bunch of facts about the roulette system being tested. It's just a series of facts that need to be cut and inserted into the dead air of the other two videos.

These facts should be inserted HEAVILY at the beginning of the video. For the first 4 or 5 spins, there should be NO dead air. Each of the first 4/5 spins should have facts inserted while the bets are being made...while the wheel is spinning... Keep the dead air to a minimum.

After those first 4 or 5 spins, the facts can be "sprinkled in" more sparingly. Instead of being inserted every spin, you can insert a fact every TWO spins. You can use this cadence for spins 6-15. After that, you can insert the facts every 3 spins. Near the end of the video, you can insert them every 4 or 5 spins. Not only that, but you can even CUT OUT THE PLACEMENT OF THE BET and CUT DIRECTLY TO THE BALL BOUNCING AND LANDING ON A NUMBER. You can do this if the video is particularly long (more than 40 spins).

## General Guidelines
The following guidelines should be maintained
* The amount of "Dead Air" should be cut down to a minimum
* If there is a complicated betting pattern that takes a long time to set up, make an effort to speed up or cut out the set up of the bet
* Keep similar video clips on the same layer
    - Talking head video
    - iPad Screen recording
    - Scoreboard
    - Progression
    - Win/Loss cover
    - Win/Loss
    - Last Spin image
    - Running total text
    - Last win/loss text
* Keep similar audio clips on the same layer
    - iPad audio
    - Talking head audio
    - Sound f/x (`gta-wasted`, `gta-mission-passed`)
* Make an effort to delete unneeded video layers
* Make an effort to delete unneeded audio layers
* There should be THREE video layers between the win/loss layer and the talking head layer

## File Asset Organization
We need to keep files organized in folders. Files should follow naming conventions to keep things tidy. This includes the name of the Adobe Premiere project file.

### Folder structure
The project should have the following folder structure:

(this is a work in progress)

```plaintext
📁 yyyy-mm-dd-RSR-ROULETTE-SYSTEM-NAME
├── 📁 a-roll
│   ├── 📄 canon-01-spin-by-spin.mov
│   ├── 📄 canon-02-filler-facts.mov
│   ├── 📄 ipad-screen-recording.mov
│   └── 📄 simulator-screen-recording.mov
├── 📁 audio
│   ├── 📁 outro
│   │   ├── 📄 Anno Domini Beats - Welcome.mp3
│   │   ├── 📄 Brooklyn and the Bridge - Nico Staf.mp3
│   │   └── 📄 Statement (Clean) - NEFFEX.mp3
│   ├── 📄 jackace-intro-banjo.mp3
│   └── 📄 simulator-voiceover.mp3
├── 📁 b-roll
│   ├── 📄 broll-gta-mission-passed.mp4
│   ├── 📄 broll-gta-wasted.mp4
│   ├── 📄 green-screen-money-falling-01.mp4
│   ├── 📄 broll-clip1.mp4
│   └── 📄 broll-clip2.mp4
├── 📁 brand
│   ├── 📄 Be_Right_Back_Looping_FINAL.mp4
│   ├── 📄 brand-plug-discord.mov
│   ├── 📄 brand-plug-google-forms.mov
│   ├── 📄 brand-plug-roulette-catalog-rba.mov
│   ├── 📄 lowerthirds-06-jackhaze.qt
│   └── 📄 file2.ext
├── 📁 images
│   ├── 📁 _background
│   │   ├── 📄 bg-black-80.png
│   │   └── 📄 bg-red.png
│   └── 📄 file4.png
└── 📄 yyyy-mm-dd-RSR-ROULETTE-SYSTEM-NAME.prproj
```
