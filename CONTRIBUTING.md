# Contributing 🙌

First off, thank you for considering contributing to WPE Sounds. It's people like you that help make WP Elevation a great place.

## Pull Request Process 👨‍💻 👩‍💻

1. Add a new sound per the standards below.

2. Update `README.md` file with changes per the standard below.

3. Pull requests can be submitted [here](https://github.com/nicksocha/wpesounds-com/pulls).

## Our Standards ☑️

### Add a new sound 🔊

> **_Step 1_**
>
> - [ ] Clone, Download, or Fork the [WPE Sounds Repository](https://github.com/nicksocha/wpesounds-com) from [GitHub](https://github.com/). Help can be found [here](https://help.github.com/en/github) if needed.

> **_Step 2_**
>
> - [ ] Verify your clip is safe for work, family friendly, and non political.
> - [ ] Record your new sound in the .wav format using your software of choice. We recommend [Audacity](<https://en.wikipedia.org/wiki/Audacity_(audio_editor)>) if you currently do not have software to record audio as it is free.
> - [ ] Name your new audio file using Kebab Case `looks-like-this.wav`.
> - [ ] Copy your new audio file to the sounds folder.

> **_Step 3_**
>
> - [ ] Duplicate code below entering the new information between the brackets and removing all the brackets \[ \].
> - [ ] New code from step 3 should be located in the `index.html` file within the `<!-- Main Section -->` in no special order.
>
> ```html
> <!-- [SOUND NAME] -->
> <div class="key" id="[KEYBOARD KEY]" onClick="clickHandler('[KEYBOARD KEY]')">
>   <kbd>[KEYBOARD KEY]</kbd>[SOUND NAME]
> </div>
> ```
>
> **_Example_**: below is the example code for a sound named Nick and uses the N key on the keyboard.
> ![Nick Example](https://github.com/nicksocha/wpesounds-com/blob/master/images/nick-example.jpg?raw=true)

> **_Step 4_**
>
> - [ ] Duplicate code below entering the new information between the brackets and removing all the brackets \[ \].
> - [ ] New code from step 4 should be located in the `index.html` file within the `<!-- Audio Data Attributes Section -->` in the same order as the sounds are in the `<!-- Main Section -->`.
>
> ```html
> <audio data-key="[KEYBOARD KEY]" src="sounds/[AUDIO FILE NAME].wav"></audio>
> ```
>
> **_Example_**: below is the example code for a sound named Nick that uses the N key on the keyboard and has an audio file named nick.wav located in the sounds folder.
> ![Nick Sound Example](https://github.com/nicksocha/wpesounds-com/blob/master/images/nick-sound-example.jpg?raw=true)

### Update README 📑

> - [ ] Duplicate code below entering the new information between the brackets and removing one set of brackets \[ \] from each.
> - [ ] New README code should be added to the `README.md` file in the same order as the sounds are in the `<!-- Main Section -->`.
>
> ```markdown
> - ([KEYBOARD KEY]) Credit to [[NAME]]([URL]) on [[SOURCE]]([URL]) for the "[SOUND NAME]" [clip]([URL]).
> ```
>
> **_Example_**: below is the example code to credit Troy Dean for a clip named "Troy Dean Here" from YouTube using the A key on the keyboard.
> ![Nick Sound Example](https://github.com/nicksocha/wpesounds-com/blob/master/images/readme-example.jpg?raw=true)

## Our Responsibilities 🏋️‍♂️ 🏋️‍♀️

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.
