# FAQ

**Is there an iPhone version?**
In the works.

**Which varios work?**
Thermik is built around the Skytraxx 2.0 but reads any standard IGC file, plus GPX, KML and KMZ
from other apps (e.g. ApexGPS, Komoot, Strava exports, Flightradar24 KML).

**The track is under the ground / floating.**
Choose **Fused** as the altitude source (the default). Raw pressure altitude is referenced to
the standard atmosphere and can be off by up to ~200 m. Hikes, rides and drives are always
drawn on the terrain.

**The terrain looks blurry.**
Outside Austria, Switzerland, Bavaria and France the imagery is Sentinel-2 at 10 m per pixel:
sharp from a distance, soft up close.

**A recording was dated wrong.**
Fix it in **Edit activity → Start**: the whole track moves, the original file stays untouched.

**Does Thermik need the internet?**
Only to download an activity's terrain, imagery and place names, once. Replay, logbook, export
and sharing work offline.

**Does Thermik change my track files?**
No. Imported folders are only read, and IGC export is the original byte for byte.

**Does it use my location?**
No. Thermik has no location permission; it only reads the files you give it.

**How do I clear downloaded terrain?**
**Settings → Storage → Downloaded terrain and imagery → Clear**.

**Thermik crashed.**
**Settings → About → Share last crash report** sends the error to the developer (app version,
phone model, no logbook data).

Other questions: [sandwalker.one@proton.me](mailto:sandwalker.one@proton.me)
