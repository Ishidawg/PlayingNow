# Playing Now
> A Play Now widget to show music status on oBS.

## Dependency
This is just a _"widget"_ for [Tuna](https://obsproject.com/forum/resources/tuna.843/), I did a "music player" that shows the song data provided by Tuna. So donwload and install it _(I've tested on Linux and Windows)_.

## Instructions
1. Download and Install [Tuna](https://obsproject.com/forum/resources/tuna.843/)
2. Open Tuna Settings and configure like this:
   - You should create a directory
   - Set the cover to be in that directory
   - Add a new song info output called `song_info.json` and save in the same directory
   - Select your **Song source** (ex: MPRIS)
   - Set **Refresh Rate** to **800ms**
<div align="center">
  <p><i>Screenshot as an example to help you</i></p>
  <img src="https://i.imgur.com/hw3TbFF.png" width="600" />
</div>

3. Configure your Song source (ex: MPRIS) with you player
<div align="center">
  <p><i>Screenshot as an example to help you, I use Fooyin and Audacious as players</i></p>
  <img src="https://i.imgur.com/OfXvghX.png" width="600" />
</div>

4. Download the `index.html` in [Releases Page](https://github.com/Ishidawg/PlayingNow/releases) and save it in the same directory
<div align="center">
  <p><i>Your directory must looks like this in the screenshot</i></p>
  <img src="https://i.imgur.com/NldANUC.png" width="500" />
</div>

6. Add a **Browser** source in the obs and select the `index.html`
<div align="center">
  <p><i>Screenshot as an example to help you</i></p>
  <img src="https://i.imgur.com/oP9i0b9.png" width="600" />
</div>

7. Done

After complete the steps above, you just need to hit play in your media player and Tune will do all the work. As this is a `.html` you can customize it at your liking, just open the file and edit what you desire.

## Screenshots
<div align="center">
  <img src="https://i.imgur.com/PLhFmES.png" />
  <img src="https://i.imgur.com/d3HNAP0.png" />
</div>
