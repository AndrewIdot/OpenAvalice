# OpenAvalice
A soon-to-be cleaned up decompilation of Freedom Planet's Torque Steam beta (1.21.3) for Clickteam Fusion 2.5. For now, this is simply an empty repo as I'm busy with other projects, however this will be worked on eventually.

### Decompilation changes
A handful of changes have been made from the original game for more convenient modding:
- Character's sprite objects have all been made global for the sake of replacing sprites easier
- The frame "Character Select (DEBUG)" from older versions has been reimported, as it was set to not compile in this version.

### Progress: 0%
- [x] Basic Clickteam decompilation output
- [ ] Decompilation issues fixed
  - [ ] Issues with "Insta Shields" and breakable objects (ie bombs and crystals) (Fixed, DV frame 1 Only)
  - [ ] Bombs triggering all at once (bugfix found by Mr. Farkle) (Fixed, Trap Hideout Only)
  - [ ] Visual Issues (Fixed, DV frame 1 Only)
- [ ] Global Values renamed
- [ ] Object alterable values renamed
- [ ] Object strings renamed

Decomp specific:
- [ ] Code comments for easier usage?
- [ ] Maybe a debug utility of sorts?

# FAQ
### When will this decompilation be finished?
I have no idea.
### How will it be distributed?
Since .MFA files, unlike most other game project files, usually contain the entirety of a game, releasing this legally might be a bit tricky. However, the way I'm planning to do it is by releasing an .xdelta file that can then be patched on top of the usual Steam beta 
### If the above is true, will getting the decompilation via a GOG copy be an option?
No. This decompilation is specifically of a Steam-exclusive beta and I will not be providing any way to patch it into a GOG copy of the game. Besides, I don't own the game on GOG, so I'm not sure how I would provide a patch for it...
### Will you clean up any other decompilations of older Freedom Planet builds? (i.e the betas)
Not in the plans, but maybe! Once this decomp is done, it'll likely be easy to port back value names and all to older builds.
