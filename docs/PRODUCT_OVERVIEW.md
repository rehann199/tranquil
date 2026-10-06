# Product Overview

Tranquil is a relaxation app built around two kinds of content: **scenes** (looping ambient video) and **sounds** (looping audio). It is used to wind down, fall asleep, study or fill a room with calm. This overview is based on the production projects and the two store listings supplied for this showcase.

<table>
  <tr>
    <td align="center"><img src="../assets/screenshots/tranquil-mobile-home.webp" width="200" alt="Mobile home screen"/><br/><sub><b>Home</b>: real Mobile screenshot</sub></td>
    <td align="center"><img src="../assets/screenshots/tranquil-mobile-sounds-mini-player.webp" width="200" alt="Sounds tab with mini player"/><br/><sub><b>Sounds</b>: real Mobile screenshot</sub></td>
    <td align="center"><img src="../assets/artwork/tranquil-android-tv-banner-artwork.webp" width="320" alt="Android TV banner artwork"/><br/><sub><b>Android TV</b>: banner artwork (not a screenshot)</sub></td>
  </tr>
</table>

## What the app is

- A scene opens a full-screen loop of stock footage with no on-screen noise beyond a few controls that fade away.
- A sound plays a looping audio track over a still artwork background, optionally dimming the screen.
- Both support a sleep timer, favourites and a saved default volume.
- There is no account. The App Store listing states that account creation or login is not required, and the production code contains no sign-in on any platform.

## Content

| Kind | Free | Premium | Total |
|---|---|---|---|
| Scenes | 8 | 15 | 23 |
| Sounds | 3 | 3 | 6 |
| Scene bundles | | 4 (three categories each) | 4 |

**Free scenes:** Travel Without Travel, Window Views, Summer Dusk, Spring Blossoms, Desert Nights, Tropical Dusk, Floating Balloons, Aquarium Fish.

**Premium scenes:** Focus & Flow, Grounding & Stability, Anxiety Relief, Japanese Forest Paths, Autumn Leaves, First Snow, Mountain & Highlands Calm, Water Worlds, Desert & Dunes Calm, Night Horizons, Candlelight & Fire Glow, Nordic Cabins, Counting Sheep, Soft Clouds, Royal Library Fireplace.

**Sounds:** Rain Forest Ambience, Ocean At Night and City Rain are free; Distant Thunder, Crackling Campfire and Wind Chimes are premium.

**Bundles:** Nature Escapes, Sleep Mode, Study Pack and Calm & Grounded, each unlocking three scene categories.

The same catalogue, tier split and bundle membership appear in the Mobile, Android TV and Apple TV projects.

## Premium model

| Path | Where |
|---|---|
| Monthly subscription unlocks everything and removes ads where ads exist | All platforms |
| One-time unlock of a single scene category or sound | All platforms (14 one-time products) |
| Bundle of three categories | All platforms |
| Rewarded ad for one hour of access to a locked item, bundle or sound | Mobile |
| Restore purchases | All platforms |

Subscription status comes from the store only. One-time unlocks are applied after the store confirms them, and once entitlements have synced, access checks use the store rather than a local flag. Purchase flows are blocked with a message when the device is offline.

## Mobile screens

The Mobile app has five tabs: **Home**, **Scenes**, **Sounds**, **Favorites** and **More**.

- **Home** shows a recommended scene with a "For you now" badge and a "Choose Your Experience" grid. The grid is reordered by time of day, and the suggestion can be switched off in settings.
- **Scenes** is a browser with All, Free and Premium tabs plus one tab per bundle.
- **Sounds** shows the six soundscapes with All, Free and Premium filters and a persistent mini player.
- **Favorites** lists saved scenes and sounds.
- **More** holds language, theme, playback, audio, sleep timer, notification, account and legal pages.
- **Playback** is a landscape screen with back, sleep-timer chips, a favourite toggle and previous, play and next controls that fade after a short idle period.

Selecting a language is part of first run; 20 languages are available, including Arabic and Urdu.

## TV screens

The Android TV and Apple TV apps share a structure: a splash, a home screen of focusable rows (scenes, sounds, bundles and a scheduled-mood card), a playback screen, a paywall, and a settings hub with sub-pages for account, audio, playback, sleep timer, scheduled moods and theme.

- **Scheduled moods** let the viewer define up to four time blocks, each mapped to a mood category. Launching the app inside a block starts a matching scene.
- **Playback** hides its controls after an idle delay; any remote press brings them back.
- **Sleep timer** offers preset durations with a countdown badge, and a prompt that offers to save a chosen duration as the default.

## Themes

Five colour themes: Default, Calm Ocean, Forest Mist, Sunset Glow and Night Serenity. They exist on Mobile, Android TV and Apple TV.

## Platform notes

| Platform | Notes |
|---|---|
| Android Mobile | Portrait app with background audio, lock-screen controls and push notifications |
| iOS | Same Mobile project; iPhone and iPad device family, iOS 15 minimum |
| Android TV | Listed on Google Play as an Android TV app; landscape, remote only |
| Fire TV | Store flavor of the TV project with Amazon billing and no ads or Firebase |
| Apple TV | Native app, tvOS 17 or later, no ads |

See [PLATFORM_ENGINEERING.md](PLATFORM_ENGINEERING.md) for how these differ in code.
