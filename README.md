# vsrg-format-docs
An aggregation of information about as many mania-style VSRG chart formats as possible, including documentation, sample files, and links to code implementations

# Formats
- `.bms`/`.bme`/`.bml`: **Beat Mania series** chart, including bm98, bms, ddr4, ddr6, bme, bme3, bme5, bme7, 2dx keys
  - StepMania C++ impl: [reader](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesLoaderBMS.cpp) and [writer](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesWriterBMS.cpp)
  - [Bemuse JS impl](https://github.com/bemusic/bemuse-notechart/tree/master/src)
- `.dwi`: **Dance With Intensity** chart
  - StepMania C++ impl: [reader](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesLoaderDWI.cpp) and [writer](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesWriterDWI.cpp)
- `.ksf`: **Kick It Up** chart
  - StepMania C++ impl: [reader](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesLoaderKSF.cpp) and [writer](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesWriterKSF.cpp)
- `.sm`: **StepMania series** chart
  - StepMania C++ impl: [reader](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesLoaderSM.cpp) and [writer](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesWriterSM%60.cpp)
- `.sma`: **StepMania AMX**
  - StepMania AMX is a pump-oriented fork of StepMania 3.95
  - StepMania C++ impl: [reader](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesLoaderSMA.cpp) and [writer](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesWriterSMA.cpp)
- `.ssc`: **StepMania 5** chart
  - StepMania C++ impl: [reader](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesLoaderSSC.cpp) and [writer](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesWriterSSC.cpp)
- `.vos`: **Virtual Orchestra Studio and CanMusic** chart, including 000, 001, 006, 022 versions
- `.pms`: **pop'n music** chart, including pms, pms3, pms5, pmse keys
- `.dtx`: **DTXMania** chart, including 6-key, 9-key drum, 5-key, 7-key guitar, and bass keys
- `.gda`/`.g2d`: **DTXMania** chart
  - [DTXmaniaNX C# impl](https://github.com/limyz/DTXmaniaNX/blob/master/DTXCreator/Code/00.App/CDTXInputOutput.cs)
- `.msd`: **Dance Dance Revolution** chart
- `.ssq`: **Dance Dance Revolution 4th Mix** chart
- `.sdf`: **Pocket DDR** chart, derived from .sm
  - [StepMania-hosted docs](https://github.com/stepmania/stepmania/tree/master/Docs/SimfileFormats/SDF)
- `.dwi`: **Dance With Intensity** chart
- `.pt`: **DJMax** chart
- `.ucs`: **Pump It Up** chart
- `.dance`: **pydance** chart
  - [Description](https://github.com/stepmania/stepmania/blob/master/Docs/SimfileFormats/misc.txt), [Format](https://github.com/stepmania/stepmania/blob/master/Docs/SimfileFormats/dance-spec.txt), [Implementation](https://github.com/mbenkmann/pydance)
- `.tja`: **Taiko Jiro** chart, including taiko and jube modes
- `.ojn`: **O2Jam** chart
- `.osu`: **osu!** chart, including osu, taiko, ctb, mania modes
- `.xml`: **Music Master** chart
- `.xml`: **Music Times** chart
- `.vox`: **SOUND VOLTEX** chart
- `.ksh`: **K-Shoot Mania** chart
- `.imd`: **Rhythm Master** chart, classic mode
- `.mde`: **Rhythm Master** chart, star motion mode
- `.mc`: **Malody** chart, including key, step, dj, catch, pad, taiko, ring, slide modes
- `.xml`: **Dynamix** chart
- `.aff`: **Arcaea** chart
- `.txt`: **Cytus** chart, including original and Version2
- `.txt`: **Cytus2** chart
- `.txt`: **Musync** chart, including plaintext and encryption
- `.txt`: **BanG Dream!** chart
- `.json`: **Deemo** chart
- `.json`: **Rhythm Master WeChat Mini Program** chart
- `.json`: **StepMania Micro** chart
  - StepMania Micro is an old web-based copy of StepMania, playable [here](https://web.archive.org/web/20150110063934/http://old.stepmania.com/wiki/StepMania_Micro)
  - [Website source code](https://web.archive.org/web/20150110120332if_/https://dl.dropboxusercontent.com/u/2963913/smjs-0.3/index.html) (view source)
  - StepMania C++ impl: [reader](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesLoaderJson.cpp) and [writer](https://github.com/stepmania/stepmania/blob/5dad6a1c9a1caba66ebc1aa0feab9bc920399455/src/NotesWriterJson.cpp)
- `.xml`: **QQ Hyun Dance Mobile Game** chart, including star motion mode, quarter moon mode, marble mode, traditional mode, bubble mode
- `.drb`: **DanceRail** chart
- `.d2r`: Obscure old Japanese format
- `.slo`: Obscure old Japanese format
- `.sul`: http://web.archive.org/web/20040205071612/http://paramax.hypermart.net/
- `.step`:
- `.ftb`:
  - Raindrop implementation: [reader](https://github.com/zardoru/raindrop/blob/662dd11f05994f6f36493575b04ecb64b04dcd7b/src/NoteLoaderFTB.cpp)
- `???`: **DirectMove**
  - Found on the [StepMania Wikia page for StepMania AMX](https://step-mania.fandom.com/wiki/StepMania_AMX)

Sources and useful links:

- Tool to convert between a bunch of formats [Description](https://lrfasd.github.io/rmstZ/) [Demo](https://lrfasd.github.io/rmstZ/rmstZ_20200403.html)
- [Raindrop VSRG Engine](https://github.com/zardoru/raindrop/tree/master/src), contains several format parsers
- [StepMania's simfile format docs](https://github.com/stepmania/stepmania/tree/master/Docs/SimfileFormats)
