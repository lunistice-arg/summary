# Summary-Gist of the Lunistice ARG

### Subtitle of the Game: "Kit & Con and the 5 Verity Bells"

## Notes
If a Link starts with `/`, it is meant to be used in conjunction with `http://lunisticegame.com`, e.g. `http://lunisticegame.com/pleasecontinue.html`.  
The ARG is played mostly on this website as well as the Discord channel #a-r-g on the [Lunistice Discord]. Progress up to and including May 6 was made on the [HerrDekay Discord], specifically in the #❓arg channel.  
All times stated in this document are in CET/CEST, whichever is applicable at that point in time.  
HerrDekay's Twitch-Channel can be found on [dekay.tv].  
The original Pastebin-based summary text was made by "Schattenkobold", with additions by "Nemm".
 
 
## The Beginning (prior to April 30)
In the HTML code of the webpage http://lunisticegame.com/, the line `616672696b786b717265636163772e61626f70` was found. Using hexadecimal ASCII encoding, a text was discovered that, using Vigenère and the passphrase `Lunistice`, was translated into `pleasecontinue.html`.
 
## pleasecontinue.html (also prior to April 30)
On the webpage [/pleasecontinue.html], one could find only a background in the colour `#202039`, as well as 2 lines in the HTML code that, once again, were encrypted via Vigenère with the same passphrase line by line.
These lines read as:
```
Nice Try
Try again later
```
 
 
## Moon-GIF (April 30)
On monday, the channel "#❓arg" was created, and the webpage [/pleasecontinue.html] was redone. The text in the HTML code was gone, and instead there was a GIF. The name of the GIF is `oyrxvbdg.gif`  

![oyrxvbdg.gif]
 
The sign below the moon is, supposedly, something that is to be deciphered. As a "present", on wednesday, May 2, a screenshot was posted, containing the text `vvr glopbng ool pr wzrcevoav`. We were told there are three riddles, and only two of them have been solved so far. Curiously, Dekay posted "~~vvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv~~", crossing it out with Discord's inbuilt formatting, and simply stated "oops, slipped".  

![first present]
 
 
## Solution 1/3 (May 3)
On Thursday, it was discovered that the file name of the Moon Gif `oyrxvbdg` could be deciphered via Vigenère and passphrase `Lunistice` to `deepdive`. Deepdive means to extract "Dark Data" from a file.
Conclusion was that the "gift" was probably referring to the picture posted on May 2.
 
 
## Solution 2/3 (May 3)
A deadline was announced for 21:30 (9:30 p.m.) of the same day. Whilst it could not be met, the solution for that deadline was indeed found, but the creator of the ARG had used an erroneous cipher which would've made finding the solution impossible.
 
The solution would have been to convert the colour-code `#434F4E` of the screenshot from May 2 from HEX to ASCII-encoded text, which would have returned `CON`. This would have been the passphrase for Vigenère to get the text `The symbols may be important`, which most likely refers to the symbols in the moon GIF.
This has been found out 12h prior to the deadline, but was discarded as the erroneous cipher lead to `vvr glopbng ool pr wzrcevoav` getting translated into `the exbnnae abj be uleaqimmi`, which makes no sense.
 
## Holdontoit.html (May 3)
The next riddle was `iffqcokivh.ikgy`, along with the commentary "Shout-out to the one that found the solution for the GIF". This was a reference to user Bruno, "6bruno9", the first one to suggest converting the colour-code from HEX to ASCII to get the `CON` phrase, as mentioned in Solution 2/3.
Via Vigenère and passphrase `bruno`, the riddle `iffqcokivh.ikgy` was quickly deciphered as `holdontoit.html`
 
 
## Key (May 4)
Around 10:20 (a.m.), a change on the webpage [/holdontoit.html] had been noted. The GIF of a weathered key was found.

![weathered key]
 
On the key, symbols are found, similar to the Moon GIF, with the text below reading "TAKE IT, KEEP IT"
The webpage [/pleasecontinue.html] also had recieved changes. In the HTML-code, it now read "holdontoit", possibly a shortcut for people that joined the ARG later.
 
On [/holdontoit.html], in the HTML-code, the text `YWgsIHdoYXQgYSBzaGFtZSAtIG5vYm9keSBldmVyIHVud3JhcHMgbXkgcHJlc2VudHM=` was added. Decoded with base64, this turned into `ah, what a shame - nobody ever unwraps my presents`.
 
The players, for ease of accessibility, separated the symbols on the Moon GIF into an image on its own. 

![Unchanged Moon GIF Symbols]
 
 
## Massive Progress (May 5)
Around noon that saturday, the HTML code of [/holdontoit.html] had changed. The following lines were added:
```html
<!-- never lose track on what is truly important like you have done so many times before -->
<!-- 596e4a31644755675a6d39795932556764326c73624342755a585a6c636942695a5342306147556759323979636d566a64434268626e4e335a58493d -->
```
 
Decoding the second line from hex ASCII with Base64 returned the line `brute force will never be the correct answer`. This text was later then added into the HTML code, so that no decoding was needed.
 
Note: The creator of the arg probably added this line becase several participants of the ARG tried to simply guess the solution.
 
Around 14:00 (2 p.m.), it was speculated, that the text in the moon GIF meant `pleasecontinue`. Thus, the word in the key GIF, would be `deep`.
 
The user "GoRoy" found out at around 20:00 (8p.m.) that within the key GIF, there was a small `.png` file hidden. This `.png` file consisted of black and white pixels. Interpreting this as Black = 0 and White = 1, the resulting binary-string was put into a Binary to ASCII Converter.
The resulting base64-string was put through a base64 decoder, which returned
```
it seems like one half of the key is missing...
i take a look at my broken present and wonder...
how .deep do i have tttttttttttttttttttttttttttttttttttt
tttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttt
tttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttt
ttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttt
```
 
![PNG in Key Gif]  
Binary-String: https://ryuu.es/0o1FI
 
 
## Presents! (May 5)
 
At around 22:12 (10:15 p.m.) the Emoji of a present was posted on the Discord of the ARG-creator. The page [/holdontoit.html] had been updated, and now included a small GIF ([/anotherpresent.gif]). Looking at the GIF in Notepad++, the line `youknowwhattodo` can be found. Repeating the steps taken before, (Binary to ASCII, etc.)...

![/anotherpresent.gif]
 
## Lore?! (May 5)
 
...on [/deepdive.html], the picture [/YmVmb3JldGhlZmlyc3Rsb29w.gif] can be found, containing a long, unencrypted text, letters replaced by fake symbols. The name of the gif was encoded with base64. Decoding it returned the name as `beforethefirstloop`.

![/YmVmb3JldGhlZmlyc3Rsb29w.gif]


Thanks to the user "KatzeRegi", the symbols were quickly deciphered, and the following text was revealed. Basis for the solution was the presumption that the text in the moon GIF meant `pleasecontinue`. With the help of the creator, minor errors have been fixed.
 
```
We believe that, at this point, time is running out "the unseen king" must make sure that the "darkness" does not take hold and that they will not lose their way they need someone to guide them to verity and the five pillars
Now we must continue our deep dive and tear it all down
```
 
Twitter-Post of the User: https://twitter.com/KatzeRegi/status/992877438404386816  
A collection of the symbols and their meaning in the latin alphabet: https://puu.sh/AgM2W/a277f948a1.png
 
 
## Presents!! (May 6)
At 00:08 (8 minutes after midnight) a new present emoji was posted in the Discord channel. The page [/deepdive.html] was updated, containing at the bottom the picture [/next.gif]. 

![/next.gif]

This was quickly solved thanks to the already-known symbols, and read `andnowwewait.html`.
 
The page [/andnowwewait.html] currently shows the GIF [/goodnight.gif].

![/goodnight.gif]
 
The creator informed everyone that the next part is a little more extensive, and it will hence take a while until it is presented.

## ITSHAPPENING.GIF (July 8)
At 01:09 HerrDekay resumed the game with a cryptic 🤔. Few minutes later, user "Suicune" found that [/andnowwewait.html] now contained a different GIF, [/dGhlcG9ydGFs.gif].

![/dGhlcG9ydGFs.gif]

The file name, as decoded by "\[a.'lɛɪ̯sium\] || Lena" using utf8 base64 resulted in `theportal`.

By 02:31, "6bruno9" noted 'oh god, it continues D:' after opening [/theportal.html]. All the page contained at that point was `not yet`, which sparked the discussion if the players could even do anything at this point. 

## ARG loading... please wait... (July 9)

"iRobin" noticed a change in the source code of [/theportal.html] at 15:20. A small comment appeared (`<!-- [█         ] -->`), which was identified as a progress bar by the players. Still unsure if that progress bar was a waiting indicator for the next part of the ARG or a progress indicator for the players, the consensus was that the only way to find out is to wait.

## We Bible students now! (July 10)

"Litrax" announced at 13:37 that they found the progress bar in [/theportal.html] to have... progressed. Additionally another comment appeared.

```html
<!-- [██ ] -->
<!-- [at infinite sheol] -->
```

They hypothesized that the second comment had something to do with the Hebrew bible, but they weren't quite sure. Sheol is also called a place of darkness, as "webba" stated, and according to lore...

```
"THE UNSEEN KING" MUST MAKE
SURE THAT THE "DARKNESS" DOES
NOT TAKE HOLD
```

...which resulted in the assumption that this darkness's source is Sheol. 

## Oh god... it changed... pls change back D: (July 11)

Something or someone (probably the creator) 'corrupted the portal' shortly before or after midnight, as "Suicune" put it. Multiple users compaired the content of the page to a barcode, with two comments found in the source code, which were described as `nnnnnnnnnn` (first comment) and `Sheol` (second comment).

While initially thought to be scrambled, on second thought "6bruno9" noticed that the Sheol comment had the letters for `at infinite sheol` in correct order when read from top to bottom, then left to right.

The second comment also contained music note characters, stirring the thought that maybe music was also part of this riddle. 

"Suicune", unsure if it may help, shared some notes on the barcode, containing the lengths of passages, and transliterations to binary digits with `-` for the grey characters.

[Suicune's notes on the 'barcode']

The creator nudged the summary writer to update the summary, noting that we might need it. Considering that, the summary writer decided to add an archive of [/theportal.html] from July 11 2018, 20:55 to the gist, should [/theportal.html] change. 

[Lunistice Discord]: https://discord.gg/YfXtjAR
[HerrDekay Discord]: https://dekay.tv/discord
[dekay.tv]: https://dekay.tv
[oyrxvbdg.gif]: http://lunisticegame.com/oyrxvbdg.gif
[First Present]: https://bit.ly/2HO6Xin
[Weathered Key]: http://lunisticegame.com/takeitkeepit.gif
[Unchanged Moon GIF Symbols]: https://i.imgur.com/F1dODr7.png
[PNG in Key GIF]: https://i.imgur.com/vW7qrgV.png
[/anotherpresent.gif]: http://lunisticegame.com/anotherpresent.gif
[/YmVmb3JldGhlZmlyc3Rsb29w.gif]: http://lunisticegame.com/YmVmb3JldGhlZmlyc3Rsb29w.gif
[/next.gif]: http://lunisticegame.com/next.gif
[/goodnight.gif]: http://lunisticegame.com/goodnight.gif
[/pleasecontinue.html]: http://lunisticegame.com/pleasecontinue.html
[/holdontoit.html]: http://lunisticegame.com/holdontoit.html
[/deepdive.html]: http://lunisticegame.com/deepdive.html
[/andnowwewait.html]: http://lunisticegame.com/andnowwewait.html
[/dGhlcG9ydGFs.gif]: http://lunisticegame.com/dGhlcG9ydGFs.gif
[/theportal.html]: http://lunisticegame.com/theportal.html
[Suicune's notes on the 'barcode']: https://puu.sh/AUG2N/c5e63f222f.txt
