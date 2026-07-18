# Awesome Seedance Prompts

A curated collection of production-ready prompts, reusable structures, and practical techniques for creating cinematic, photorealistic, commercial, action, UGC, and narrative videos with **Seedance**.

> The examples below are adapted and rewritten from publicly shared creator experiments on X. They are not verbatim copies. Each example links to its source of inspiration so you can study the original post and result.

## Contents

- [Quick start](#quick-start)
- [A reliable prompt structure](#a-reliable-prompt-structure)
- [Prompt collection](#prompt-collection)
  - [Frozen-time celebration](#1-frozen-time-celebration--one-take-vfx)
  - [Luxury perfume commercial](#2-luxury-perfume-commercial)
  - [Documentary-style surprise hook](#3-documentary-style-surprise-hook)
  - [Luxury fountain pen](#4-luxury-fountain-pen)
  - [The last transmission](#5-the-last-transmission--sci-fi)
  - [Luxury villa UGC](#6-luxury-villa-ugc-ad)
  - [Supernatural city POV](#7-supernatural-city-pov)
  - [Reference-video camera transfer](#8-reference-video-camera-transfer)
  - [Action short](#9-grounded-cinematic-action)
  - [Emotional micro-story](#10-emotional-micro-story)
- [Reusable templates](#reusable-templates)
- [Camera language](#camera-language)
- [Realism and consistency](#realism-and-consistency)
- [Contributing](#contributing)
- [Sources](#sources)

## Quick start

A good Seedance prompt behaves like a compact director's brief:

1. State the format: duration, aspect ratio, visual medium, and pace.
2. Define the subject and the one thing that changes.
3. Break the clip into timed beats when the story has multiple events.
4. Give each shot one clear camera movement.
5. Describe sound as precisely as image.
6. End with continuity and failure constraints.

For image-to-video, avoid redescribing everything already visible in the reference. Spend prompt budget on **movement, performance, camera, timing, sound, and what must remain unchanged**.

## A reliable prompt structure

```text
FORMAT
[duration], [aspect ratio], [frame rate if needed], [visual style/medium]

SUBJECT
Who or what is on screen. Include only identity-critical details.

SCENE
Location, time, weather, lighting, atmosphere, and spatial relationships.

TIMELINE
[0–Xs] Subject action + camera + sound
[X–Ys] Subject action + camera + sound
[Y–Zs] Payoff + camera + sound

VISUAL DIRECTION
Lens feel, composition, lighting, color, texture, depth of field.

CONTINUITY
Keep face, clothing, body proportions, product geometry, scene layout,
light direction, and screen direction consistent.

CONSTRAINTS
Natural physics, anatomically correct motion, stable background,
no extra people or objects, no morphing, no text artifacts, no jump cuts
unless explicitly requested.
```

A useful shorthand is:

```text
Subject → Action → Environment → Camera → Style → Sound → Constraints
```

For complex clips, time blocks are more reliable than packing simultaneous actions into one sentence. For simple clips, a clean natural-language paragraph often works better.

---

## Prompt collection

### 1. Frozen-time celebration — one-take VFX

**Use case:** cinematic fashion, music video, magical realism  
**Mode:** text-to-video or image-to-video  
**Suggested settings:** 10–15s, 9:16, 24fps

```text
A seamless cinematic one-take at an elegant nighttime rooftop celebration.
A calm woman in a black evening dress walks forward through a party frozen
in time. Champagne hangs in mid-air as suspended droplets; ribbons, confetti,
hair, fabric, and laughing guests remain perfectly motionless.

The camera tracks backward at her walking speed, maintaining a medium shot
with natural handheld micro-movement. She studies the frozen scene, then
casually ducks beneath a suspended arc of champagne without touching it.
As she passes the camera, time resumes behind her in a soft expanding wave:
droplets fall, fabric continues moving, guests finish their gestures, and
ambient sound returns from silence.

Real photographed textures, physically plausible liquid and cloth, soft
practical lights, subtle film grain, shallow depth of field, restrained VFX,
no glossy CGI look. Preserve her face, dress, body proportions, and walking
rhythm. No teleporting, morphing, duplicated guests, or camera cuts.
Audio: muffled silence inside the frozen zone, distant low pulse, then a
natural rush of party ambience, glass clinks, and music when time resumes.
```

**Why it works:** one visual rule drives the whole clip; the subject has a simple continuous action; the resume wave provides a clear payoff.

Inspired by [@miilesus's Seedance freeze-effect experiment](https://x.com/miilesus/status/2046298278539763814).

### 2. Luxury perfume commercial

**Use case:** beauty, fragrance, jewelry, premium product ads  
**Mode:** image-to-video or reference-to-video  
**Suggested settings:** 10s, 9:16 or 1:1

```text
10-second luxury fragrance film, refined editorial realism.

[0–3s] Macro shot of the perfume bottle resting among pale pink peonies.
Soft morning light passes through the glass and creates delicate caustics.
A few petals drift slowly through the foreground. The camera makes a gentle
five-centimeter push-in; very shallow depth of field.

[3–7s] A graceful hand enters from frame right and lifts the bottle without
covering the label. The camera arcs subtly around the bottle while focus stays
locked on the logo. Condensation and glass reflections move naturally.

[7–10s] One controlled spray crosses a shaft of backlight as a fine mist.
The bottle returns to its hero position. End on a stable product close-up
with clean negative space for optional copy.

Premium real-product photography, accurate bottle geometry, readable and
unchanged label, soft ivory and blush palette, realistic skin texture,
restrained highlights, no plastic CGI surfaces. Audio: petals brushing,
quiet glass contact, crisp atomizer click, airy room tone. No extra fingers,
warped logo, duplicated bottle, floating product, or sudden camera move.
```

Inspired by [@OlivioSarikas's timed perfume example](https://x.com/OlivioSarikas/status/2044656318297129321).

### 3. Documentary-style surprise hook

**Use case:** viral shorts, comedy ads, surreal UGC  
**Mode:** image-to-video  
**Suggested settings:** 8–12s, 9:16

```text
100% live-action iPhone documentary texture, handheld single take, natural
available light, mild breathing shake, ordinary phone exposure, no cinematic
beauty filter.

[0–3s] A tired fast-food employee steps through the back door into a quiet
parking lot carrying a tray with a burger and fries. The camera operator
walks backward at close conversational distance. He exhales and glances down.

[3–7s] The asphalt trembles. A comically huge burger-shaped creature rises
slowly behind a parked car, scattering loose paper and dust. The employee
notices the shadow first, freezes, then turns naturally.

[7–10s] He looks at the burger on his tray, then at the creature, and quietly
says, “This is above my pay grade.” He backs through the door while keeping
the tray level. The camera hesitates, then follows.

Believable weight, grounded foot contact, imperfect real-world framing,
natural reaction timing, consistent wardrobe and location. The creature must
feel physically present in the phone footage, not like polished game CGI.
No gore, no brand-logo distortion, no extra limbs, no teleporting, no cuts.
Audio: ventilation hum, distant traffic, paper scraping, low ground rumble,
dry dialogue recorded by a phone microphone.
```

Inspired by [@egeberkina's real-life iPhone documentary prompt](https://x.com/egeberkina/status/2042738773054886152).

### 4. Luxury fountain pen

**Use case:** tabletop product film, craftsmanship, ASMR  
**Mode:** text-to-video or product image-to-video  
**Suggested settings:** 10–12s, 16:9 or 1:1

```text
A tactile luxury product film in a quiet writing studio: walnut desk, open
cream leather notebook, warm shaded lamp, dark green background.

[0–3s] Macro slider shot reveals a black lacquer fountain pen beside the
notebook. The gold nib catches one narrow highlight. Shallow depth of field.

[3–7s] A hand picks up the pen and writes one smooth abstract signature.
The nib remains correctly aligned with the paper; ink appears only where
the nib touches, with believable wet sheen and capillary flow. Camera tracks
parallel to the nib.

[7–10s] Rack focus from the fresh ink to the engraved nib as the pen is placed
diagonally across the page. Hold the final composition for one second.

Real commercial macro photography, accurate pen proportions and engraving,
rich wood grain, natural hand anatomy, restrained amber lighting, no synthetic
CG gloss. Audio: cap click, nib scratching softly on paper, leather movement,
quiet room tone. No malformed fingers, changing engravings, broken nib,
random letters, or discontinuous hand position.
```

Inspired by [@ChillaiKalan__'s “Luxury Fountain Pen” storyboard](https://x.com/ChillaiKalan__/status/2071854481378271359).

### 5. The last transmission — sci-fi

**Use case:** cinematic narrative, sci-fi teaser, multi-shot storytelling  
**Mode:** text-to-video  
**Suggested settings:** 15s, 16:9, 24fps

```text
15-second grounded science-fiction film, live-action production design,
anamorphic lens character, restrained red emergency lighting, deep shadows.

[0–3s] Wide establishing shot: a lone astronaut stands in the control ring of
a vast abandoned orbital station. Emergency lights pulse slowly; dust drifts
in zero gravity. Camera descends on a slow crane move.

[3–7s] Medium tracking shot as the astronaut crosses the dark console deck.
A cracked monitor wakes and displays a weak waveform. Keep screen direction
left-to-right. Heavy magnetic boots contact the floor with believable weight.

[7–11s] Tight helmet close-up. Reflected in the visor, a distant silhouette
moves behind the observation glass. The astronaut whispers, “Control, I found
the signal.” Radio compression and breath are audible.

[11–15s] The waveform becomes a human voice saying the astronaut's name.
The camera slowly dollies toward the visor; all emergency lights cut out on
the final word. End in darkness with one radio click.

Photoreal set materials, practical haze, subtle film grain, consistent suit
details and station geography, no game-engine surfaces. No monster reveal,
no random cuts, no floating body, no changing helmet, no unreadable title text.
```

Inspired by [@Ciri_ai's “The Last Transmission” Seedance story](https://x.com/Ciri_ai/status/2071616897423130937).

### 6. Luxury villa UGC ad

**Use case:** real estate, travel, creator ads  
**Mode:** reference-image-to-video  
**Suggested settings:** 12–15s, 9:16

```text
Vertical creator-style property tour filmed on a recent smartphone. Natural
handheld motion, realistic auto-exposure, crisp daylight, confident but
unscripted performance.

[0–3s] The creator walks toward a modern clifftop villa and says, “You will
not believe what is behind this door.” The camera follows from slightly behind
and to the side, with natural footsteps and mild phone shake.

[3–7s] Match the movement through the doorway into the open-plan living room.
Exposure adapts gradually from exterior sun to interior shade. The creator
gestures toward retracting glass walls and the ocean beyond.

[7–11s] One continuous walking reveal onto the terrace. The camera pans with
the gesture to show an infinity pool aligned with the horizon.

[11–15s] The creator turns to camera: “And this view wraps all the way around.”
Finish with a short, stable wide view rather than a speed ramp.

Authentic phone footage, believable architecture and reflections, consistent
floor plan, no impossible room expansion, no luxury-ad CGI polish, no warped
hands, no cloned furniture. Audio: direct phone-mic dialogue, footsteps,
sliding door, light wind, distant surf. Keep music subtle or absent.
```

Inspired by [@impaulxyz's handheld luxury-villa prompt](https://x.com/impaulxyz/status/2077520048944484854).

### 7. Supernatural city POV

**Use case:** mystery, fantasy POV, viral narrative hook  
**Mode:** text-to-video  
**Suggested settings:** 10–15s, 9:16

```text
A grounded supernatural mystery on a crowded modern city street during rush
hour. Begin as a normal observational film, then reveal one impossible rule.

[0–3s] Medium rear tracking shot of Rex walking through a dense crowd.
Thousands of commuters move naturally around him. Neutral daylight, realistic
street audio, 35mm documentary lens.

[3–7s] Shift into Rex's POV without a flashy transition. Every person now has
a faint translucent thread of light extending upward—except one woman standing
still across the crossing. The camera slows as Rex notices her.

[7–11s] Return to a tight profile of Rex. He looks toward her; the crowd keeps
flowing between them. Focus breathes naturally as people briefly occlude frame.

[11–15s] The woman raises one finger to her lips. All city sound drops out,
but the crowd continues moving. Slow push toward Rex's eye; cut to black.

Photoreal urban footage, subtle supernatural effect integrated into real light,
consistent crowd paths and screen direction, no glowing fantasy overload,
no duplicated pedestrians, no face morphing, no frozen background. Audio:
traffic and footsteps, gradual high-frequency tone, then precise silence.
```

Inspired by [@Strength04_X's supernatural-mystery Seedance prompt](https://x.com/Strength04_X/status/2078157151428816974).

### 8. Reference-video camera transfer

**Use case:** reproduce camera motion, edit rhythm, or choreography from a reference  
**Mode:** multimodal/reference-to-video

```text
Use @Image1 only for the protagonist's identity, face, hair, outfit, and color
palette. Do not inherit its background or pose.

Use @Video1 only for camera path, shot duration, cut rhythm, subject blocking,
and movement tempo. Do not copy its people, location, wardrobe, logos, or
specific copyrighted design.

Re-create the camera grammar of @Video1 in a rain-soaked neon alley at night.
The protagonist from @Image1 walks against the flow of pedestrians, turns at
the same narrative beat as the reference, and enters a small noodle shop.
Preserve the exact left-to-right screen direction and approximate camera speed.
Adapt all motion naturally to the new environment rather than tracing body
positions mechanically.

Live-action photography, wet asphalt reflections, motivated shop lighting,
natural crowd behavior, consistent face and wardrobe. Preserve environmental
geometry across cuts. Audio: rain on awnings, footsteps, distant traffic,
door chime. No borrowed characters, logos, dialogue, or recognizable set
design from @Video1; no face drift, outfit changes, or camera teleportation.
```

Technique inspired by [@op7418's reference-video workflow](https://x.com/op7418/status/2026325142398529926) and [@maxprokopp's camera-blocking workflow](https://x.com/maxprokopp/status/2071658167453515933).

### 9. Grounded cinematic action

**Use case:** martial arts, chase, action previs  
**Mode:** image-to-video or reference-to-video  
**Suggested settings:** 10s, 16:9, 24fps

```text
10-second live-action martial-arts sequence in a narrow hotel service corridor.
Two adult fighters only. Grounded stunt choreography, real contact spacing,
clear geography, no superpowers.

[0–2s] Low medium shot: the defender steps off-line from a straight punch,
redirects the wrist, and drives one shoulder check. Camera tracks laterally;
do not orbit.

[2–6s] Side-on wide shot keeps both full bodies visible. The attacker recovers,
throws a controlled round kick, and the defender leans back just enough for
the shoe to pass in front of the face, then sweeps the supporting leg.
Show preparation, contact, weight transfer, and recovery in continuous motion.

[6–10s] The attacker rolls safely, rises to one knee, and both pause as the
elevator bell rings behind them. Slow push-in; end on their reaction.

Real stunt-performer timing, stable anatomy, believable inertia, natural cloth
and hair movement, practical fluorescent lighting, subtle handheld camera.
No speed ramps, random flips, missed eyelines, extra fighters, limb fusion,
teleporting, excessive camera shake, impact flashes, blood, or game CGI.
Audio: shoes on carpet, fabric movement, controlled impacts, breath, elevator bell.
```

This example follows the community advice to keep actions continuous, camera moves simple, and stability constraints explicit; see [@PeterT69358109's concise prompt notes](https://x.com/PeterT69358109/status/2021143749263597854).

### 10. Emotional micro-story

**Use case:** short drama, branded story, cinematic social video  
**Mode:** text-to-video  
**Suggested settings:** 15s, 16:9

```text
15-second intimate live-action drama in a small neighborhood laundromat at
blue hour. Quiet, restrained acting; no melodrama.

[0–4s] Wide locked shot. An elderly tailor folds one child's red coat alone
under cool fluorescent light. Empty machines rotate in the background.
Only dryer hum and fabric sounds.

[4–9s] Medium profile. A young woman enters, sees the coat, and stops.
The camera makes one slow dolly-in. She says softly, “You kept it?”
He nods without looking up.

[9–13s] Close-up of his hands repairing a loose button. Her hand enters frame
and rests beside his, not on top of it. Warm street light passes across them
as a bus moves outside.

[13–15s] Return to the wide frame. They sit together with the small red coat
between them. The dryer stops; silence. Hold the final image.

Natural performances, realistic aging and skin texture, consistent eyelines,
subtle film grain, cool-blue room with one warm red focal point. No crying on
cue, no swelling fantasy light, no extra dialogue, no face drift, no changing
coat, no discontinuous hand positions.
```

---

## Reusable templates

### Single-shot template

```text
[DURATION], [ASPECT RATIO], one continuous live-action shot.

[SUBJECT] performs [ONE CLEAR ACTION] in [LOCATION].
The camera [ONE CAMERA MOVE] while maintaining [FRAMING].
The scene changes when [SINGLE TURNING POINT], ending on [PAYOFF].

Lighting: [MOTIVATED LIGHT].
Texture: real photographed materials, natural skin, believable physics.
Audio: [AMBIENCE], [FOLEY], [DIALOGUE IF ANY].
Keep [IDENTITY / PRODUCT / GEOMETRY] unchanged.
No cuts, morphing, duplicated objects, extra limbs, or unstable background.
```

### Timed multi-shot template

```text
[DURATION], [ASPECT RATIO], [STYLE].

[0–Xs] Shot 1 — [size + subject action]. Camera: [one move]. Audio: [cue].
[X–Ys] Shot 2 — [size + escalation]. Camera: [one move]. Audio: [cue].
[Y–Zs] Shot 3 — [size + payoff]. Camera: [one move]. Audio: [cue].

Continuity: identity, wardrobe, props, light direction, spatial geography,
screen direction, and cause-and-effect remain consistent across every cut.
Constraints: [top 3 likely failures only].
```

### Image-to-video template

```text
Use @Image1 as the visual source of truth for [IDENTITY / PRODUCT / OUTFIT].
Preserve its [CRITICAL FEATURES]. Do not inherit [UNWANTED FEATURES].

Animate only: [SUBJECT MOTION], [ENVIRONMENTAL MOTION], [CAMERA MOTION].
The motion begins with [PREPARATION], reaches [MAIN ACTION], and ends with
[RECOVERY / HOLD]. Keep the original composition unless the camera direction
explicitly changes it.

Natural physics, temporal consistency, no geometry drift, no face or label
change, no new objects, no sudden zoom, no automatic slow motion.
```

### Native-audio template

```text
Dialogue: “[SHORT LINE]” spoken by [CHARACTER], [PERFORMANCE DIRECTION].
Lip movement matches the exact line and language.

Foreground Foley: [2–3 PRECISE SOUNDS].
Ambience: [LOCATION BED].
Music: [STYLE / TEMPO / ENTRY POINT], lower than dialogue.
At [TIMESTAMP OR EVENT], [SOUND CHANGE] motivates [VISUAL CHANGE].
No narration, extra speech, canned audience noise, or overpowering music.
```

## Camera language

| Goal | Useful direction | Common failure to avoid |
|---|---|---|
| Reveal scale | slow crane down, pull back, foreground occlusion | instant zoom-out |
| Follow a person | lateral tracking or camera walks backward at subject speed | orbiting without motivation |
| Product hero shot | macro push-in, small controlled arc, locked label focus | full 360° spin |
| Tension | slow dolly-in, restrained focus shift, held composition | constant shake and fast zoom |
| UGC realism | mild handheld breathing, imperfect reframing, gradual auto-exposure | polished gimbal-commercial look |
| Action clarity | side-on wide shot, consistent screen direction | rapid cuts that hide choreography |
| Subjective POV | motivated POV transition, natural head movement | floating camera |
| Emotional intimacy | static medium shot, subtle push, longer hold | excessive close-ups and melodrama |

One camera move per shot is a strong default. Combine moves only when the path is physically clear, such as “track backward while gently lowering from eye level to chest level.”

## Realism and consistency

Prefer positive physical direction over long negative lists:

- Write the preparation, action, impact, and recovery—not only the impact.
- State what is fixed: face, outfit, product label, prop hand, light direction.
- Keep action complexity proportional to clip length.
- Use a wide or medium-wide shot when limb interaction matters.
- Let practical sources motivate light: window, lamp, streetlight, phone screen.
- Ask for real capture characteristics: exposure adaptation, focus breathing, rolling-shutter restraint, lens depth—not just “photorealistic.”
- Describe only the three to five most likely failure modes. Huge negative lists can dilute the direction.
- If a reference image already defines appearance, focus the prompt on motion and sound.
- If using a reference video, explicitly separate what to inherit from what not to copy.

## Contributing

Contributions are welcome. A useful submission should include:

- The prompt
- Seedance version and mode
- Duration and aspect ratio
- Input references, if any
- A result link or preview
- What worked and what still failed
- Attribution to the original creator or source

Please submit prompts you wrote yourself or have permission to redistribute. When adapting a public example, rewrite it, link the source, and explain the reusable technique instead of copying the post wholesale.

## Sources

Community examples and techniques referenced in this README:

- [@miilesus — frozen-time celebration](https://x.com/miilesus/status/2046298278539763814)
- [@OlivioSarikas — timed perfume commercial](https://x.com/OlivioSarikas/status/2044656318297129321)
- [@egeberkina — iPhone documentary realism](https://x.com/egeberkina/status/2042738773054886152)
- [@ChillaiKalan__ — luxury fountain pen storyboard](https://x.com/ChillaiKalan__/status/2071854481378271359)
- [@Ciri_ai — The Last Transmission](https://x.com/Ciri_ai/status/2071616897423130937)
- [@impaulxyz — luxury villa UGC](https://x.com/impaulxyz/status/2077520048944484854)
- [@Strength04_X — supernatural city mystery](https://x.com/Strength04_X/status/2078157151428816974)
- [@op7418 — reference-video camera and edit transfer](https://x.com/op7418/status/2026325142398529926)
- [@maxprokopp — camera blocking with a 3D reference](https://x.com/maxprokopp/status/2071658167453515933)
- [@PeterT69358109 — concise stability advice](https://x.com/PeterT69358109/status/2021143749263597854)
- [@maybeegreen — subject/action/environment/camera structure](https://x.com/maybeegreen/status/2042226474422297010)
- [@RetroValix — focus image-to-video prompts on movement](https://x.com/RetroValix/status/2074231054567866617)

Official model references:

- [Seedance 1.0](https://seed.bytedance.com/en/seedance)
- [Seedance 1.5 Pro](https://seed.bytedance.com/en/seedance1_5_pro)

---

If this collection helps, consider starring the repository. Contributions, tested variations, and failure notes are especially valuable.
