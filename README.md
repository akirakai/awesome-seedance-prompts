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
  - [Mechanical bloom](#11-mechanical-bloom--one-take-macro)
  - [Paper-camera screen transformation](#12-paper-camera-screen-transformation)
  - [Layered-reference launch sequence](#13-layered-reference-launch-sequence)
  - [Liquid-porcelain couture transformation](#14-liquid-porcelain-couture-transformation)
  - [Harvest-to-table sensory ASMR](#15-harvest-to-table-sensory-asmr)
  - [Beat-locked street rap MV](#16-beat-locked-street-rap-mv)
  - [Calm-anchor flood reveal](#17-calm-anchor-flood-reveal)
  - [Micro-expression performance score](#18-micro-expression-performance-score)
  - [Effect-only reference injection](#19-effect-only-reference-injection)
  - [Parametric multilingual FPV descent](#20-parametric-multilingual-fpv-descent)
  - [Rock-color origin-story commercial](#21-rock-color-origin-story-commercial)
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

### 11. Mechanical bloom — one-take macro

**Use case:** technology branding, material showcase, abstract product film  
**Mode:** text-to-video or image-to-video  
**Suggested settings:** 15–30s, 16:9, 24fps

```text
A continuous macro one-take for a premium technology brand. Begin in near
darkness on a closed mechanical flower bud made from brushed titanium,
smoked glass, and fine copper conductors. One narrow moving highlight reveals
the outer silhouette while the background remains black.

[0–6s] The camera performs a slow, centered macro push-in. The outer metal
petals unlock in a clear mechanical sequence: tension builds in the hinges,
micro-gears rotate, and each petal opens only after the previous latch releases.
Movement is delicate and physically plausible, never explosive.

[6–16s] Without cutting, the camera passes between two opening petals and
enters the flower's inner mechanism. Focus transfers from the front edge to
nested glass membranes, tiny bearings, and current flowing through copper
traces. Reflections and refractions remain consistent with the same moving
light source.

[16–24s] The inner structure expands like a camera iris. Warm light grows from
the center and travels outward through the translucent parts. The camera slows
and gently pulls back as the full flower reaches its final geometry.

[24–30s] Hold a symmetrical hero composition. A soft pulse of light moves once
from the core to every petal tip, then settles. No logo or subtitle.

Real macro cinematography, stable central composition, coherent mechanism,
fine machining marks, accurate metal weight, glass thickness and refraction,
restrained bloom and cinematic grading. Keep every component attached and
preserve its material across the transformation. No liquid-metal morphing,
random floating parts, duplicated petals, impossible interpenetration, sudden
speed ramp, camera cut, or synthetic game-CGI surface.
Audio: tiny latch clicks, quiet gear movement, low electrical hum, one soft
resonant tone at full bloom; no narration.
```

**Why it works:** the prompt treats the reveal as a causal mechanical process—latch, rotation, opening, illumination—and uses one evolving light source to preserve spatial and material continuity.

Adapted from ByteDance / Volcano Ark's official Seedance 2.5 preview, documented in the [official model showcase](https://ark.volcengine.com/promotion?modelName=seedance-2-5) and the [traceable prompt archive](https://github.com/renoise-ai/awesome-seedance-2-5-prompts#mechanical-bloom).


### 12. Paper-camera screen transformation

**Verified model:** Seedance 2.0 — confirmed by the public prompt-gallery
metadata and linked original creator post

**Use case:** mixed-media transitions, travel reels, illustration reveals,
screen-within-screen effects  
**Mode:** text-to-video  
**Suggested settings:** 15s, 9:16

```text
15-second vertical first-person phone video with nostalgic Japanese summer
texture. A handmade red-and-yellow paper digital camera is held in one hand
throughout. Its shape, buttons, LCD border, scale, and hand grip remain
unchanged across every shot.

The real environment always stays live action. Only the rectangular image
inside the paper camera's LCD may change style. At the beginning of each shot,
the LCD shows the same live scene aligned with the background. When the thumb
presses the shutter, a clear camera click occurs and the pixels strictly inside
the LCD transform into a simple, charming hand-drawn 2D illustration of the
same subject. Nothing outside the LCD changes.

[0–3s] Tokyo Tower at night, seen beyond the paper camera. Press the shutter;
the tower and city lights inside the LCD become a warm children's-book drawing.

[3–7s] Clean cut to summer-festival fireworks. Re-establish the live LCD view,
then press the shutter; only the fireworks inside the screen become flat
watercolor shapes and ink lines.

[7–11s] Clean cut to a bright sunflower field. The camera is held at the same
foreground distance. On the click, the LCD becomes a soft yellow-and-green
hand-drawn illustration while the real flowers continue moving in the breeze.

[11–15s] Clean cut to a seaside view through a moving train window. On the final
click, the LCD turns the sea, sky, and passing poles into a nostalgic 2D anime
background. Hold long enough to compare the illustrated screen with the moving
live-action world around it.

Authentic handheld POV, mild phone exposure changes, soft summer color,
consistent paper texture and natural fingers. Maintain exact LCD boundaries,
matching composition, perspective, and subject placement before and after each
shutter press. The illustrated content may move subtly but must remain clipped
to the screen.

No full-frame style change, no illustration leaking beyond the LCD, no floating
overlay, no warped camera body, no extra fingers, no changing screen size, and
no mismatch between the LCD subject and the real background.
Audio: location ambience for each scene, paper handling, four distinct shutter
clicks, distant train rhythm in the final shot; no narration.
```

**Why it works:** the prompt defines two simultaneous visual domains—live
action outside the prop and illustration inside it—and repeatedly states the
LCD as a hard spatial boundary. Re-establishing the live view before every
shutter click also gives each transformation a visible cause and reset.

Adapted from [GENEL's original paper-camera prompt and result](https://x.com/genel_ai/status/2078044912168341890).
The Seedance 2.0 attribution, prompt, preview, and original-source mapping are
preserved in the [traceable gallery entry](https://youmind.com/en-US/seedance-2-0-prompts?id=7437).


### 13. Layered-reference launch sequence

**Verified model:** Seedance 2.0 — explicitly identified by the original
creator and confirmed by the linked prompt-gallery metadata

**Use case:** mecha or vehicle launch scenes, fast commissioning montages,
multi-reference animation  
**Mode:** multi-reference image-to-video  
**Suggested settings:** 15s, 16:9, 480p

```text
15-second theatrical 2D animated launch sequence with clean linework,
precise mechanical drawing, restrained cel shading, and rapid insert shots.

REFERENCE ROLES
@Image1 defines only the pilot: face, hair, eyewear, suit, body proportions.
@Image2 defines only the crewed machine: head, armor, palette, wings, rear
unit, thrusters, light color, and scale.
@Image3 defines only the cockpit: seat, controls, displays, UI, interior
geometry, and color scheme.
Keep all three designs unchanged and do not mix one reference's job with
another. Do not invent weapons, transformations, or equipment.

[0–2s] In the dark cockpit, a fingertip approaches and presses the ignition.
A clean electronic click triggers a ring of light in @Image2's accent color.
Cut briefly to the pilot's profile as the glow reflects in the eyes.

[2–4s] Displays wake in layers: radar, machine diagram, and output gauges.
Use short inserts of both hands gripping the controls, one safety switch
releasing, and UI light moving across the pilot's unchanged face and suit.

[4–6s] A communications window confirms that launch checks are complete.
Keep the line short and clearly spoken. If no operator reference is supplied,
use a visually distinct generic operator and never duplicate the pilot.

[6–8s] Low-angle wide shot in the hangar: the complete machine from @Image2
stands in its restraints. Cables disconnect, service arms withdraw, cooling
vapor vents, and warning lights sweep across the original armor geometry.

[8–10s] Rapid mechanical inserts: foot lock, armor vibration, spinning
thruster interior, wing or rear-unit readiness, and sensor illumination.
Show only mechanisms already visible in @Image2.

[10–12s] Back in the cockpit, the pilot nods, tightens both hands on the
controls, and announces: "[MACHINE NAME], launching." If the reference
does not provide a reliable name, say: "Unit ready, launching." Push the
main control forward as the output gauge rises.

[12–13s] Extreme close-up of the machine's head. Both eyes ignite in the
exact reference color, synchronized to one sharp power-up tone.

[13–15s] Restraints clear and all visible thrusters fire. The machine
accelerates along the launch rail and exits into open sky or space. End on
a low three-quarter full-body view with a brief light trail and no title card.

No shot lasts longer than two seconds. Bind every visible state change to a
specific click, lock release, warning tone, power surge, or engine sound.
Begin with low machinery and breathing; add restrained piano and strings
after ignition, then percussion and brass for launch. Dialogue stays clear.

No identity drift, alternate machine design, cockpit redesign, extra pilot,
missing eyewear, added weapon, extra finger, garbled UI text, combat, enemy,
impact, explosion, or launch delayed beyond 15 seconds.
```

**Why it works:** each reference has one non-overlapping responsibility, so
the model can preserve three complex designs while the timeline changes
scale rapidly. Sub-two-second inserts keep the commissioning montage legible;
audio-event binding supplies causality, and the fallback line prevents an
unknown machine name from turning into unstable text or dialogue.

Adapted from [Kuma to kuma's original complete Seedance 2.0 prompt and result](https://x.com/Kumatokuma1/status/2078268822688063715),
published July 18, 2026. The model attribution, publication date, and
original-source mapping are also preserved in the [traceable YouMind entry](https://youmind.com/zh-CN/video-prompts/robot-anime-launch-sequence-cinematic-7441).


### 14. Liquid-porcelain couture transformation

**Verified model:** Seedance 2.0 — confirmed by the public Seedance 2.0
prompt-gallery metadata and its mapping to the original creator post

**Use case:** fashion films, material transformations, fantasy branding  
**Mode:** text-to-video or image-to-video  
**Suggested settings:** 15s, 9:16, 24fps

```text
15-second surreal couture film. Keep one adult model, one blue-and-white
liquid-porcelain gown, and one shallow mirror plain beneath a bright clouded
sky consistent through all three shots.

Shot 1 (0–5s): Low-angle medium-long tracking shot as the model walks toward
camera. The gown behaves like heavy flexible porcelain: blue glaze patterns
flow slowly across the white surface, the hem displaces a thin layer of water,
and each step produces a restrained ceramic chime. End with the model stopped
and centered.

Shot 2 (5–10s): Cut to a stable chest-up portrait. The model raises one hand
and snaps once. Starting at the lower hem, the gown separates into hundreds
of small ink-painted swallows carrying droplets and blue pigment. The flock
spirals upward around the unchanged body without covering the face, then exits
toward the mirrored ground behind the model.

Shot 3 (10–15s): Overhead shot descending in one slow spiral. The swallows
strike their reflections and dissolve into liquid ink; concentric blue-black
rings spread across the mirror, then pull the model's reflection and the cloud
reflection into one deep vortex. The real model remains intact at the edge of
the final frame while the vortex settles.

Use fibrous ink edges, glazed ceramic highlights, real fluid weight, restrained
wind, and one consistent sun direction. Sound: footsteps in shallow water,
small ceramic resonance, one dry finger snap, wings, droplets, then a low liquid
pull. Preserve face, hair, body proportions, and garment palette. No second
model, body transformation, random costume change, weightless fragments,
material change before the snap, or full-frame ink covering the final image.
```

**Why it works:** every change has a visible trigger and a material consequence.
The same blue pigment travels from gown to birds to water, so three large visual
states still read as one causal transformation.

Adapted from [@johnAGI168's original prompt and result](https://x.com/johnAGI168/status/2025849650654122348),
published February 23, 2026. The Seedance 2.0 attribution and complete
source mapping are preserved in the [traceable gallery entry](https://youmind.com/en-US/seedance-2-0-prompts?id=594).


### 15. Harvest-to-table sensory ASMR

**Verified model:** Seedance 2.0 — confirmed by the public Seedance 2.0
prompt-gallery metadata and its mapping to the original creator post

**Use case:** food, hospitality, slow living, tactile brand stories  
**Mode:** text-to-video  
**Suggested settings:** 15s, 16:9, 24fps

```text
15-second live-action harvest-to-table film in one modern rural home. Natural
late-afternoon light, quiet observational pacing, no dialogue and no music.
Keep the same adult cook, linen shirt, tomatoes, kitchen, and garden geography.

Shot 1 (0–5s) — freshness: Backlit macro view of a hand twisting one ripe
tomato from the vine. Fine leaf hairs, dew, and skin texture remain sharp.
The stem releases with a small snap; one droplet rolls over the thumb. The
camera makes a five-centimeter lateral slide and ends on the tomato in hand.
Sound: leaves, insects, stem snap, fingertip on wet skin.

Shot 2 (5–10s) — craft: Interior macro shot follows the knife, not the face.
The cook completes two deliberate cuts; juice and seeds move only from blade
contact. Cut once to the pan as the pieces land and sizzle, with steam bending
toward the open window. Sound: board contact, knife, one pan sizzle, low fire.

Shot 3 (10–15s) — rest: Medium-wide locked frame at the garden table. The same
cook sets down the finished bowl, tucks one loose strand of hair behind the ear,
takes one quiet bite, and pauses to watch steam cross the sunlight. End on the
settled table and surrounding breeze. Sound widens to birds, cloth, cutlery,
wind, and distant kitchen fire.

Real food photography, natural hand anatomy, believable moisture and heat,
consistent ingredient quantity and clothing. Progress from macro detail to a
wider human moment. No glamour-food CGI, impossible knife path, extra fingers,
instant cooked food within a shot, continuity jump, narration, or loud score.
```

**Why it works:** each shot owns one sensory idea and one completed action.
Widening the frame and sound field turns detail into process, then process into
a calm payoff without overloading any single beat.

Adapted from [@johnAGI168's original rural ASMR prompt and result](https://x.com/johnAGI168/status/2021818021354848258),
published February 12, 2026. The Seedance 2.0 attribution and complete
source mapping are preserved in the [traceable gallery entry](https://youmind.com/en-US/seedance-2-0-prompts?id=288).


### 16. Beat-locked street rap MV

**Verified model:** Seedance 2.0 — confirmed by the public Seedance 2.0
prompt-gallery metadata and its mapping to the original creator post

**Use case:** short music videos, performance reels, character-led campaigns  
**Mode:** text-to-video or image-to-video  
**Suggested settings:** 15s, 16:9, 24fps

```text
15-second street-performance music video featuring one fictional 80-year-old
woman with silver hair, a black leather jacket, and simple metal jewelry.
Night exterior under blue and violet practical lights. Use an original sparse
90-BPM hip-hop beat; do not imitate an existing song or performer.

Shot 1 (0–3s): Medium tracking move through a small circle of onlookers. The
performer raises the microphone on the first kick and meets camera with a calm,
self-possessed look. End when the beat is fully established.

Shot 2 (3–7s): Locked medium close-up for accurate lip movement. She performs
one short original line: “I outlived the noise; now the beat keeps time.”
One pointing gesture lands on “beat”; a small head nod lands on the final word.
Lower the music beneath the vocal and keep the face nearly frontal.

Shot 3 (7–11s): Full-body wide frame. No new lyric. On four downbeats she
performs a readable sequence: two grounded bounce steps, one brief freeze,
one restrained body wave, then returns both feet to a stable stance. Cut only
after the recovery is complete.

Shot 4 (11–15s): Slow push from medium shot to close-up as the rhythm strips
down to bass and finger snaps. She turns one shoulder toward camera, says
“Still here,” then holds a quiet half-smile. The final bass hit and camera stop
occur together.

Keep the same face, age, silver hair, jacket, microphone, crowd size, and street
direction. Mouth moves only during the two quoted lines. Natural elderly body
mechanics, clear hands, full feet in the dance shot, no age change, face drift,
extra jewelry, copied celebrity likeness, frenetic camera, random dance loop,
garbled lyric, or music overpowering speech.
```

**Why it works:** the beat is the only timing system. Lip-sync, one hand gesture,
four dance accents, the final line, and the camera stop each receive their own
musical landmark instead of competing on every beat.

Adapted from [松果先森's original Seedance performance prompt and result](https://x.com/songguoxiansen/status/2033175478765289598),
published March 15, 2026. The Seedance 2.0 attribution and complete source
mapping are preserved in the [traceable gallery entry](https://youmind.com/en-US/seedance-2-0-prompts?id=1403).


### 17. Calm-anchor flood reveal

**Verified model:** Seedance 2.0 — confirmed by the public Seedance 2.0
prompt-gallery metadata and its mapping to the original creator post

**Use case:** scale reveals, surreal comedy, disaster-film hooks  
**Mode:** text-to-video or image-to-video  
**Suggested settings:** 12–15s, 16:9, 24fps

```text
One continuous live-action shot with no cuts. Begin at water level inside a
modern office that is already deeply flooded. A calm adult swimmer wearing
plain goggles is the visual anchor; surrounding coworkers provide escalating
chaos without blocking the anchor for more than a moment.

The camera pullback is already moving on the first frame. Start on an extreme
close view of churning water as the swimmer's face rises through the surface
during the same backward motion—do not stage the emergence first and begin the
camera move afterward. Keep pulling back and rising at one continuous speed
from eye-level close-up to a slightly elevated medium-wide view.

As the frame widens, reveal floating keyboards, chairs, papers, and coworkers
trying to reach desks. Foreground splashes and people may briefly occlude the
lens, but the calm swimmer stays near center, breathes naturally, and looks once
toward the surrounding panic. End with the entire flooded office readable while
the swimmer's face remains large enough to recognize; settle for one second
without reversing or restarting the move.

35mm live-action perspective, cool fluorescent practical light, realistic water
volume, buoyancy, wet cloth, reflections, and object collisions. Sound begins
with breath and close splashes, then expands into alarms, distant voices, water,
and floating objects as the space is revealed. No second pullback, speed jump,
tiny unreadable anchor, dry clothing, duplicated people, floating objects with
no buoyancy, face drift, camera cut, or polished game-CGI water.
```

**Why it works:** subject emergence and camera movement begin concurrently, so
the reveal never stalls. A calm central performer gives the expanding chaos a
stable scale reference, while the final-size constraint prevents over-pulling.

Adapted from [Jouhatsu's original prompt and result](https://x.com/Jouhatsu_ai/status/2078241030021824983),
published July 17, 2026. The Seedance 2.0 attribution and complete source
mapping are preserved in the [traceable gallery entry](https://youmind.com/en-US/seedance-2-0-prompts?id=7443).


### 18. Micro-expression performance score

**Verified model:** Seedance 2.0 — confirmed by the public Seedance 2.0
prompt-gallery metadata and its mapping to the original creator post

**Use case:** actor direction, dialogue reactions, intimate portrait scenes  
**Mode:** image-to-video  
**Suggested settings:** 15s, 16:9 or 9:16, 24fps

```text
Use @Image1 only as the source of truth for the adult performer's identity,
hair, wardrobe, background, composition, and light. Preserve them exactly.
Animate a restrained 15-second reaction in a locked chest-up portrait with
natural breathing. No dialogue and no music.

0–2s: Eyes lowered; a small closed-mouth smile and relaxed jaw.
2–4s: The smile recedes. The eyes lift slowly toward frame right while the head
moves only a few degrees.
4–6s: Brows rise slightly; eyes open a little wider; lips part as if a sentence
might begin, then stop.
6–8s: Gaze falls. The lower lip firms and the chin tucks, showing contained
disappointment without tears.
8–10s: Eyes close for one measured breath. One corner of the mouth forms a
brief self-aware smile, then relaxes.
10–12s: The performer raises the gaze toward the key light; posture straightens
by a few centimeters and the eyes become more alert.
12–15s: Hold a quiet, moist-eyed look into camera. The lips move once as if
choosing not to speak, then become still. End on the held gaze; do not fade.

Restrict motion to eyes, eyelids, brows, mouth corners, jaw, chin, breathing,
and a very small head angle. Preserve facial geometry, skin texture, eye color,
hairline, clothing, camera, and light direction. No spoken words, tears,
exaggerated grimace, beauty-filter skin, head turn, body sway, face drift,
blinking loop, sudden emotion switch, or camera movement.
```

**Why it works:** abstract emotion becomes seven observable muscular changes.
The locked camera and narrow motion budget protect identity while the breathing
and held endpoint keep the performance from feeling like a sequence of poses.

Adapted from [Loriel.AI's original facial-performance timeline](https://x.com/ou_zhen599/status/2078137477425172769),
published July 17, 2026. The Seedance 2.0 attribution and complete source
mapping are preserved in the [traceable gallery entry](https://youmind.com/en-US/seedance-2-0-prompts?id=7422).


### 19. Effect-only reference injection

**Verified model:** Seedance 2.5 — official ByteDance / Volcano Ark showcase

**Use case:** adding one controlled VFX layer to an existing performance  
**Mode:** edit or multi-reference video-to-video  
**Suggested settings:** inherit @Video1 duration, aspect ratio, cuts, and timing

```text
REFERENCE ROLES
@Video1 is the source clip and controls the performer, face, body, wardrobe,
jungle environment, composition, camera path, action, edit rhythm, and duration.
Preserve every one of those layers unchanged.
@Image1 controls only the silhouette, blue-white palette, and energy texture of
a magical bow and arrow. Do not transfer its person, pose, background, camera,
lighting, or any other object.

CHANGE ONLY THE EFFECT LAYER
Before the performer's empty hand begins the drawing action, faint blue-white
arcs gather around that hand and connect into a translucent bow with stable
grip placement. As the opposite hand pulls backward, one luminous arrow
condenses continuously between string and bow; the string tension, arm motion,
and growing light intensity share the same timing as @Video1.

On the exact release frame in @Video1, the string straightens, the arrow leaves
the hand, and one sharp continuous light trail follows its real flight path.
The trail bends only with the arrow trajectory, illuminates nearby skin, cloth,
leaves, and haze, then dissipates into small particles before the source clip
ends. Keep the bow attached to the grip until the action is complete.

Use restrained electrical filaments, fine particles, a bright core, soft bloom,
and motivated blue-white spill. Sound: low charge, rising tension tone, one
release snap, fast air pass, short electrical decay. Do not alter the source
performance, anatomy, timing, framing, camera, environment, or clip length.
No extra weapon, free-floating bow, early arrow, hand intersection, copied
identity from @Image1, explosive screen flash, effect covering the face, or
new cut.
```

**Why it works:** the prompt freezes every source-video channel except one and
gives the new layer its own attachment points, causal stages, release frame,
environmental interaction, and dissipation endpoint.

Adapted from ByteDance / Volcano Ark's official Seedance 2.5
[model showcase](https://ark.volcengine.com/promotion?modelName=seedance-2-5);
the complete official prompt is preserved in the
[traceable archive entry](https://github.com/renoise-ai/awesome-seedance-2-5-prompts#energy-bow-vfx-imagevideo-reference).


### 20. Parametric multilingual FPV descent

**Verified model:** Seedance 2.5 — official ByteDance / Volcano Ark showcase

**Use case:** destination films, multilingual campaigns, continuous aerial reveals  
**Mode:** text-to-video  
**Suggested settings:** 30s, 16:9, 30fps

```text
30-second continuous FPV descent with no cuts, hidden transitions, teleporting,
or reverse motion. Begin above bright clouds and end hovering two meters above
a city plaza. Use one uninterrupted downhill flight path through six connected
zones. Each zone contains exactly one correctly spelled greeting and no other
letters, numbers, captions, signs, or logos.

0–5s — “HELLO”: descend through cloud vapor shaped by sunlight into the word.
Speed 4 m/s; pitch down 12 degrees; roll below 3 degrees. The letters disperse
into mist as the camera passes through them.

5–10s — “你好”: accelerate through a green valley toward a waterfall. The two
characters appear only in the waterfall mist, then dissolve into spray. Speed
rises smoothly from 6 to 12 m/s; one gentle 20-degree yaw follows the river.

10–15s — “こんにちは”: skim above a blue lake. The exact characters form from
one continuous line of reflected sunlight on the water, then break into ripples
behind the camera. Peak speed 15 m/s; height remains two meters above water.

15–20s — “HOLA”: cross a flower field where the five letters are formed by
five continuous planted color bands. Climb only enough to read the whole word;
no separate floating typography. Speed eases to 10 m/s.

20–25s — “BONJOUR”: enter the city along one avenue. The exact word appears as
warm window lights across a single connected facade, never as a subtitle.
Decelerate from 10 to 5 m/s and level the horizon.

25–30s — “안녕하세요”: arrive above the plaza. The exact Korean greeting is
drawn by embedded ground lights as the camera settles to a stable hover.
Decelerate to 2 m/s, pitch returns to zero, roll below 2 degrees, then hold.

Preserve continuous geography, forward direction, time of day, wind direction,
and exposure. Every word belongs physically to its environment and disappears
before the next appears. Sound moves continuously from high wind to waterfall,
lake rush, flowers and insects, city traffic, then plaza ambience. No hard cut,
camera collision, repeated zone, mixed languages in one zone, misspelling,
floating caption, unreadable tiny text, sudden speed change, or unstable horizon.
```

**Why it works:** the route, equal event slots, exclusive text zones, physical
text carriers, and explicit speed-orientation curve give a long one-take both
creative variety and measurable continuity anchors.

Adapted from ByteDance / Volcano Ark's official Seedance 2.5
[model showcase](https://ark.volcengine.com/promotion?modelName=seedance-2-5);
the complete official prompt is preserved in the
[traceable archive entry](https://github.com/renoise-ai/awesome-seedance-2-5-prompts#fpv-multilingual-one-take-descent).


### 21. Rock-color origin-story commercial

**Verified model:** Seedance 2.5 — official ByteDance / Volcano Ark showcase

**Use case:** ingredient provenance, regional brands, heritage product films  
**Mode:** text-to-video  
**Suggested settings:** 30s, 3:4, 24fps

```text
30-second flat rock-color animation on fibrous paper. Mineral-pigment texture,
layered mural composition, restrained parallax, cinnabar red, malachite green,
lapis blue, sand gold, and warm paper beige. A single pomegranate is the visual
anchor across six shots. Keep its crown shape and red-gold palette recognizable.

Shot 1 (0–5s) — origin: A pomegranate ripens on a branch in an orchard painted
with granular mineral pigment. One shaft of morning light travels across the
skin; the fruit becomes fully red as the branch bends under its weight. Slow
rostrum-camera push; leaves and cloth move as separate paper layers.

Shot 2 (5–10s) — harvest: A hand twists the same fruit free and places it into
a woven basket. The circular crown fills frame at the end and becomes a graphic
match point. Sound: leaves, basket fiber, one small bell.

Shot 3 (10–15s) — journey: Match cut from the crown shape to a sun above an
ancient desert trade road. A camel caravan carries baskets with the same red
fruit visible at the top. Track laterally across mural-like mountains; dust
moves as translucent pigment washes, not 3D particles.

Shot 4 (15–20s) — time bridge: The caravan passes behind a painted gate. Its
geometric border slides across frame and becomes the patterned edge of a modern
kitchen counter. The same pomegranate rolls gently into a waiting hand. Preserve
screen direction and size through the transition.

Shot 5 (20–25s) — craft: Top-down close-up. A knife completes one clean cut;
ruby seeds appear in a flat jewel-like arrangement. Pressing the seeds produces
one ribbon of red juice that follows an ancient-road motif across the paper
toward a clear glass.

Shot 6 (25–30s) — payoff: An adult lifts the glass in a quiet contemporary
courtyard. The camera pulls back as orchard branches, trade-road lines, and the
glass align into one poster-like composition. End with clean negative space,
the whole fruit, cut fruit, and drink visible; hold for one second, no generated
brand copy.

Maintain hand-painted line quality, paper grain, flat depth, character design,
fruit geometry, palette, and left-to-right journey. Sound connects each era:
orchard wind, basket, caravan bells, gate slide, knife, seeds, pour, final sip.
No photorealism, glossy 3D fruit, changing ingredient, floating product, random
historical costume, illegible text, broken transition direction, or extra logo.
```

**Why it works:** one product anchor travels through origin, transport, craft,
use, and final key visual. The match shapes and consistent screen direction
turn a historical montage into a continuous provenance story rather than six
unrelated pictures.

Adapted from ByteDance / Volcano Ark's official Seedance 2.5
[model showcase](https://ark.volcengine.com/promotion?modelName=seedance-2-5);
the complete official prompt is preserved in the
[traceable archive entry](https://github.com/renoise-ai/awesome-seedance-2-5-prompts#rock-color-silk-road-animation).

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

### Occlusion-assisted transformation template

**Verified model:** Seedance 2.0 — explicitly identified by the original creator

Use this when an object, photo, doorway, or effect must reveal a full-size person
or a radically different scene. Do not ask the source object to morph directly
into the target. Build a brief, motivated full-frame occlusion and change states
only while the source and target are completely hidden.

```text
[DURATION], [ASPECT RATIO], one transformation with a physically motivated
hidden cut.

[0–Xs] BEFORE STATE
[SUBJECT] interacts with [SOURCE OBJECT] in [LOCATION]. Establish the source,
target scale, camera position, lighting, and background clearly. Keep the
target absent.

[X–Ys] OCCLUSION TRIGGER
[TRIGGER ACTION] releases [SMOKE / STEAM / CLOTH / DUST / FOREGROUND OBJECT]
from a believable source. It expands toward the lens until it covers 100% of
the frame, including the subject, source object, hands, floor, and background.
Do not reveal any part of the target before full coverage.

At the single fully occluded frame, hide one hard cut. Replace the before state
with the complete after state behind the occluder. Keep camera position, lens,
light direction, background geometry, and subject identity anchors unchanged.

[Y–Zs] AFTER STATE
The occluder clears naturally to reveal [COMPLETE TARGET] already at correct
human scale and with normal anatomy. Show a short physical reaction, recovery,
or interaction that proves the target occupies the scene. Settle into a stable
final composition and hold.

Continuity: one source object, one target, consistent location and lighting.
The target appears whole behind the occlusion—not by stretching, growing,
crawling out, or passing through the source object.
No partial body, scale drift, fused anatomy, premature reveal, weak coverage,
source-object deformation, camera jump, or background change.
Audio: [TRIGGER], [OCCLUDER MOVEMENT], [REVEAL FOLEY], continuous room tone.
```

**Why it works:** the prompt separates the effect into two stable states and
assigns the impossible change to a frame where no geometry is visible. The
occluder also gives the model a causal transition and preserves the spatial
anchors needed for a convincing reveal.

Adapted from [@johnAGI168's complete Seedance 2.0 popcorn-machine prompt](https://x.com/johnAGI168/status/2077631766374822080),
which uses expanding smoke to conceal the state change before revealing a
full-size character.

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

### Long-form one-take continuity template

For 20–30 second generations, define a small set of invariants before adding
scene changes. The surroundings may transform, but the camera path and spatial
anchors should not.

```text
[DURATION], one continuous shot with no cuts, jump cuts, or hidden transitions.

INVARIANTS
The protagonist keeps [IDENTITY / WARDROBE] unchanged.
The camera follows [DIRECTION AND DISTANCE] at [CONSTANT OR PLANNED SPEED].
Every zone preserves [SHARED ARCHITECTURAL ANCHORS].
Light in each zone is motivated by [WINDOW / PRACTICAL SOURCE].
The protagonist always crosses thresholds from [SCREEN DIRECTION].

TIMELINE
[0–5s] Zone 1: [VISUAL RULE], [ONE ACTION], [ONE SOUND CUE].
[5–10s] Cross a visible doorway while [TRANSFORMATION MECHANISM].
[10–15s] Zone 2: [NEW RULE], preserving all invariants.
[15–20s] Cross the next threshold; prepare the emotional or visual turn.
[20–25s] Zone 3: [PAYOFF].
[25–30s] Decelerate, settle into [FINAL COMPOSITION], and hold.

CONTINUITY
Doors remain connected; floor level, window positions, walking pace, camera
height, screen direction, and body scale remain coherent. Transform style only
after the subject fully crosses a threshold. No camera teleportation, looping
hallway, duplicated subject, skipped room, or transformation before the doorway.
```

This “fixed invariants + threshold-triggered transformations” pattern is adapted
from the official Seedance 2.5 six-room one-take preview. See the
[Volcano Ark showcase](https://ark.volcengine.com/promotion?modelName=seedance-2-5)
and [archived full prompt](https://github.com/renoise-ai/awesome-seedance-2-5-prompts#six-room-one-take-transition).

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
- [@johnAGI168 — Seedance 2.0 full-frame occlusion transformation](https://x.com/johnAGI168/status/2077631766374822080)
- [GENEL — Seedance 2.0 paper-camera LCD transformation](https://x.com/genel_ai/status/2078044912168341890)
- [Kuma to kuma — Seedance 2.0 layered-reference launch sequence](https://x.com/Kumatokuma1/status/2078268822688063715)
- [YouMind — version metadata and full-source mapping for the launch sequence](https://youmind.com/zh-CN/video-prompts/robot-anime-launch-sequence-cinematic-7441)
- [@johnAGI168 — Seedance 2.0 liquid-porcelain couture transformation](https://x.com/johnAGI168/status/2025849650654122348)
- [@johnAGI168 — Seedance 2.0 harvest-to-table sensory ASMR](https://x.com/johnAGI168/status/2021818021354848258)
- [松果先森 — Seedance 2.0 beat-locked street rap performance](https://x.com/songguoxiansen/status/2033175478765289598)
- [Jouhatsu — Seedance 2.0 calm-anchor flood reveal](https://x.com/Jouhatsu_ai/status/2078241030021824983)
- [Loriel.AI — Seedance 2.0 micro-expression performance score](https://x.com/ou_zhen599/status/2078137477425172769)
- [YouMind OpenLab — Seedance 2.0 prompt, preview, author, and source metadata](https://github.com/YouMind-OpenLab/awesome-seedance-2-prompts)
- [@maybeegreen — subject/action/environment/camera structure](https://x.com/maybeegreen/status/2042226474422297010)
- [@RetroValix — focus image-to-video prompts on movement](https://x.com/RetroValix/status/2074231054567866617)
- [ByteDance / Volcano Ark — Seedance 2.5 official preview showcase](https://ark.volcengine.com/promotion?modelName=seedance-2-5)
- [Renoise AI — traceable archive of 12 official Seedance 2.5 preview prompts](https://github.com/renoise-ai/awesome-seedance-2-5-prompts)

Official model references:

- [Seedance 1.0](https://seed.bytedance.com/en/seedance)
- [Seedance 1.5 Pro](https://seed.bytedance.com/en/seedance1_5_pro)

---

If this collection helps, consider starring the repository. Contributions, tested variations, and failure notes are especially valuable.
