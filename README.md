<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/banner-compact-dark.webp">
  <source media="(max-width: 600px)" srcset="assets/banner-compact-light.webp">
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.webp">
  <img alt="R.V.Onisca: solo founder in Sibiu, Romania. I make remarkable places explorable from anywhere. Background: LiDAR contour lines of Cățănaș hill, Tilișca." src="assets/banner-light.webp" width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/razvanonisca/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://archaic-knowledge-next.vercel.app">Archaic Knowledge</a> &nbsp;·&nbsp;
  <a href="https://neatmedia.co/">neatmedia.co</a>
</p>

I capture real places (ruins, ridges, old streets) and turn them into things people can explore on a screen: Gaussian-splat scans, LiDAR reconstructions, maps and small games. Most of it serves **Archaic Knowledge**, my platform for ancient and geological sites. I fly the drone, carry the scanner and write the code.

I also bring seven years of gamification and behavioral design (Octalysis), which is why my products tend to have quests in them.

<sub>TypeScript · Three.js / WebGPU · Spark · PlayCanvas · Next.js · Flutter · Supabase · Python · Blender · Cloudflare</sub>

### Recognition

**Best Natural Landscape Reconstruction**, Niantic Spatial [#SplatYourWorld](https://nianticspatial.com/blog/splatyourworld-winners), 2026, for my capture of Detunata Goală, a basalt nature reserve in Transylvania.

### Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://archaic-knowledge-next.vercel.app"><img src="assets/archaic-knowledge-web.jpg" alt="Archaic Knowledge home page: a night scene of Petra, the Giza pyramids, Göbekli Tepe and rock-cut tombs around a winding stone path, under the title Unravel Enduring Mysteries." width="100%"></a>
      <br>
      <b>Archaic Knowledge</b> &nbsp;<sub>Live · <a href="https://archaic-knowledge-next.vercel.app">visit ↗</a></sub>
      <br>
      A map, globe and 3D library of ancient and geological sites, with quizzes, tours and a restored photo archive. Rebuilt for search and AI answers.
      <br>
      <sub>Next.js 16 · Supabase · Mapbox GL · Three.js · Gaussian splats</sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/archaic-knowledge-mobile.jpg" alt="Three phone screens of the Archaic Knowledge app: the welcome screen, a 3D scan of stone ruins and the Derinkuyu Underground City page." width="100%">
      <br>
      <b>Archaic Knowledge for Android and iOS</b> &nbsp;<sub>Working build</sub>
      <br>
      The same world in your pocket: map home screen, globe, quizzes, an eSIM store for travellers and a splat viewer.
      <br>
      <sub>Flutter · Riverpod · flutter_map · Supabase</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/splat-studio.gif" alt="A Gaussian-splat capture of the Tholos at Delphi assembling itself from a glowing ring while the camera orbits." width="100%">
      <br>
      <b>Splat Studio</b> &nbsp;<sub>Internal tool</sub>
      <br>
      Turns 3DGS and LiDAR scans into cinematic video: 31 keyframed effects, 16 camera moves and frame-exact MP4 export, all in the browser.
      <br>
      <sub>TypeScript · Spark · Three.js · Mediabunny · Vitest</sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/digitaltwinz.jpg" alt="Aerial Gaussian-splat scan of grassy burial mounds with a white wireframe grid draped over part of the terrain." width="100%">
      <br>
      <b>DigitalTwinz</b> &nbsp;<sub>In development</sub>
      <br>
      A marketplace for splat scans of real places, for game, VR and heritage teams, plus a drone "Ride" with physics through each scan.
      <br>
      <sub>TanStack Start · React 19 · PlayCanvas · Rapier · Supabase · Cloudflare R2</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/tilisca-reconstruction.jpg" alt="3D reconstruction of a Dacian hillfort: stone ramparts, a timber palisade, a gatehouse and smoking houses on green terraced slopes." width="100%">
      <br>
      <b>Tilișca, Cățănaș hill</b> &nbsp;<sub>Working build · public after review</sub>
      <br>
      The Dacian fortified settlement, rebuilt from LiDAR and archaeological plans into a site you can walk through in the browser.
      <br>
      <sub>Python · Blender · Three.js · Vite · Cloudflare Workers</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://mythos-defense.vercel.app"><img src="assets/mythos-defense.jpg" alt="Tower-defense game on a floating island at Delphi: painted Greek temples guard a stone path while mythical monsters advance." width="100%"></a>
      <br>
      <b>Mythos Defense</b> &nbsp;<sub>Phase 0 · <a href="https://mythos-defense.vercel.app">stress test ↗</a></sub>
      <br>
      A tower-defense game set at real ancient sites, with monsters drawn from the sources. Every model is built in code; two switchable art styles.
      <br>
      <sub>React 19 · Three.js · deterministic TypeScript sim · Vitest</sub>
    </td>
  </tr>
</table>

<sub>Most repositories are private while the products are in development. I'm happy to walk you through the code.</sub>

### Also on the bench

- **Merge Splats** (Python): aligns and merges two LiDAR + splat scans of the same place (FFT coarse fit, ICP, elastic warp) and scores the result with its own renderer.
- **Procedural twin** (Python, Blender, Three.js): turns a splat capture into a 6.6 MB relightable scene that runs at about 220 fps.
- **Reel pipeline** (Python, FFmpeg): from an edit list to a finished reel with captions, voice, mix and titles.
- **Nunti** (Next.js): animated wedding invitations with RSVP, about 2.4 KB of own code per invitation.

### Working together

I build photorealistic digital twins for museums, heritage sites and travel teams, and the products around them. The best way to reach me is [LinkedIn](https://www.linkedin.com/in/razvanonisca/).
