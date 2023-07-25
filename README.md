# [Kids Cheering Detector](https://pggamer2.github.io/Rickroll-Detector/)
Detect any [KC SFX] in some seconds!

*I had to check a lot of videos and callouts to make this.*.

## Q&A

### What is [KC SFX]?
It means the kids cheering sound effect, The sound effect is this -->  [[https://soundeffects.fandom.com/wiki/Sound_Ideas,_CHILDREN,_CROWD_-_SMALL_STUDIO_AUDIENCE_OF_CHILDREN:_BIG_CHEER,_CHEERING_01]], And since it triggers some misophonic (Fear of certain sounds) people, I decided to make it.

### It doesn't detect *this* link! Can you add it?
Sure. Report it in the issue tab or make a PR.

### How does it work?
It basically detects if the video's ID is inside a "blacklist" contained inside *kcsfxs.json*. Then it checks if the video has a part where it uses the sound effect using timestamps between another blacklist and after that it also screenshots the part where the sound effect is played.
Also, I added a "history" of previous kids cheers that have been detected by the user. These are stored using cookies.
