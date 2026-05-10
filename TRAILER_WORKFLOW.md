# AI Movie Trailer Creation System
## Seedream Image Storyboard + Seedance 2.0 Video Prompt Workflow

---

## 1. Purpose

Two-step system for short AI-generated movie trailers:

1. **Seedream** → one storyboard image per scene (shows full action progression)
2. **Seedance 2.0** → animates each storyboard image into a 15-second video scene

Each image is a **visual instruction sheet** for the video model — not just a pretty picture.

---

## 2. Core Method: Pictorial Scene Storyboard

Each scene = one image containing multiple visual beats:
- Opening shot
- First action beat
- Middle action beat
- Climax
- Ending frame

---

## 3. Image Format Rules

- 9:16 vertical
- 4–5 separated horizontal panels
- Clean black borders between panels
- Each panel = one action beat
- **No text, no scene numbers, no captions, no logos, no subtitles**

---

## 4. Trailer Structure (60 seconds)

| Scene | Duration | Asset |
|-------|----------|-------|
| Scene 1 | 15s | Image 1 + Seedance Prompt 1 |
| Scene 2 | 15s | Image 2 + Seedance Prompt 2 |
| Scene 3 | 15s | Image 3 + Seedance Prompt 3 |
| Scene 4 | 15s | Image 4 + Seedance Prompt 4 |
| Bonus BTS CTA | 15s | Image 5 + Seedance Prompt 5 |

---

## 5. Character Consistency Rule

**Must stay identical across all scenes:**
- Same face, head shape, beard, skin tone, body type
- Same eyes, lips, facial proportions

**May change:**
- Clothes, environment, pose, action, camera angle, lighting, emotion

---

## 6. Character Identity Lock Template

```
Use the original uploaded reference photos as the primary identity reference for the main character.
The character must look like the exact same person from the reference images: a young Black man, late 20s,
bald head, short trimmed beard, medium-dark skin, round face, expressive eyes, athletic-to-stocky build.
Preserve his facial identity consistently across all scenes. Do not redesign him into a different person.
Only change outfit, pose, environment, lighting, and action.
```

---

## 7. Master Character Sheet (First Step)

Before any trailer scenes, create one character sheet showing:
- Front, back, left side, right side, 3/4 angle
- Close-up face, full body
- Same outfit in every angle
- Neutral studio background
- No text, no labels, no captions

---

## 8. Seedream Image Prompt Formula

```
Create a single cinematic storyboard collage image in 9:16 vertical format, with clearly separated panels
and clean borders between each panel. No text, no captions, no logos, no subtitles.

Use the original uploaded reference photos as the main character identity reference. Keep the exact same face,
bald head, short trimmed beard, skin tone, body type, and overall identity.

Scene description:
[Setting, genre, mood, visual style.]

Panel 1: [Opening shot.]
Panel 2: [First action beat.]
Panel 3: [Middle action beat.]
Panel 4: [Climax.]
Panel 5: [Ending frame.]

Style: [cinematic, film grain, lighting, color palette, lens feel, mood.]

Restrictions: No text, no captions, no readable signs, no logos, no subtitles, no children, no gore,
no distorted face, no inconsistent character identity.
```

---

## 9. Seedance 2.0 Video Prompt Formula

**Always start with:**
```
Use the reference image as the full visual storyboard for this 15-second scene.
Animate the actions in the same order shown inside the pictorial.
```

**Then follow:**
```
Keep the main character identical to the reference image across the entire shot:
[character identity lock]

Opening shot: [panel 1]
First action beat: [panel 2]
Middle action beat: [panel 3]
Climax: [panel 4]
Ending frame: [panel 5]

Camera movement: [simple director language]
Lighting: [describe lighting]
Mood: [emotional tone]
Visual style: [film style]
Character consistency: [repeat identity lock]
```

---

## 10. Camera Language (Keep Simple)

Good: `slow push-in`, `low-angle tracking shot`, `side tracking shot`, `smooth orbit`, `whip pan`,
`slow-motion moment`, `final heroic push-in`, `handheld documentary feel`, `wide establishing shot`,
`medium close-up`, `tight close-up`

---

## 11. Visual Style (This Project)

- 1970s Hong Kong martial arts cinema
- Old film grain, faded celluloid colors
- Warm golden hour lighting
- Slight VHS-era softness
- Epic but slightly comedic parody tone
- Character acts like everything is life-or-death

---

## 12. Restrictions (Always Include)

- Adults only, no children
- No gore, no excessive blood
- No readable text, subtitles, captions, logos, watermarks
- No scene numbers inside images
- No distorted hands/face
- No inconsistent character identity

---

## 13. Example Trailer: "THE LAST MASTER TEST"

**Genre:** Kung fu action comedy parody  
**Character:** Young Black man, late 20s, bald head, short trimmed beard, athletic-to-stocky build, white karate gi, black belt.

### Scene 1 — Temple Arrival

**Seedream prompt:**
```
Create a single cinematic storyboard collage image in 9:16 vertical format, with 5 clearly separated
horizontal panels using clean black borders between each panel. No text, no captions, no logos, no subtitles.

[Character identity lock block]

He wears a white karate gi with a black belt. Keep the outfit consistent.

1970s Hong Kong martial arts scene at golden hour. Setting: misty ancient Chinese mountain temple, long stone
steps, bamboo, warm sunset light, drifting fog.

Panel 1: wide establishing shot from behind — hero at bottom of massive stone staircase leading to temple.
Panel 2: close-up of hero's face, looking upward with intense determination, jaw set, eyes focused.
Panel 3: low-angle — hero sprinting up the stone stairs, gi and belt moving with the wind.
Panel 4: silhouettes of martial artists waiting at the top in front of the glowing temple gate.
Panel 5: hero reaches upper courtyard, lands in a strong karate fighting stance in front of temple entrance.

Style: cinematic live-action, 1970s Hong Kong kung fu film, heavy film grain, faded celluloid colors,
warm amber sunlight, misty atmosphere, epic but slightly comedic parody tone.

Restrictions: no text, no readable signs, no captions, no logos, no subtitles, no children, no gore,
no distorted face, no changing identity.
```

**Seedance prompt:**
```
Use the reference image as the full visual storyboard for this 15-second scene. Animate the actions in the
same order shown inside the pictorial.

[Character identity lock]

Opening shot: wide cinematic shot from behind — hero at bottom of massive temple staircase. Mist rolls across
mountain peaks, warm golden sunlight fills the frame.
First action beat: close-up of his face as he looks upward with serious determination.
Middle action beat: he sprints up the stone stairs, gi and belt move in the wind, camera tracks upward from low angle.
Climax: shadowy martial artists appear at the top in front of the glowing temple gate.
Ending frame: hero reaches upper courtyard, stops in a powerful karate stance, centered in front of temple entrance.

Camera: slow push-in at start, low-angle tracking during run, final heroic push-in on stance.
Lighting: warm golden hour, amber sunlight, soft mist glow.
Mood: epic, determined, exaggerated, slightly comedic but acted completely serious.
Visual style: 1970s Hong Kong martial arts cinema, aged celluloid, heavy film grain, faded colors, vertical 9:16.
Maintain strict character consistency. Do not redesign face, outfit, hairstyle, or body type.
```

### Scene 2 — Bamboo Training Montage
*(See full prompt in training doc — bamboo forest, wooden post, balance on post, high kick, exhaustion)*

### Scene 3 — Humiliation Fight
*(See full prompt — temple courtyard, hero vs elderly master, hero crashes into pole, master unimpressed)*

### Scene 4 — Rise of the Hero
*(See full prompt — temple courtyard, deep breath, perfect martial arts combo, master reacts with respect)*

### Bonus Scene — Behind the Scenes CTA

**French CTA line (best version):**
```
Si vous voulez apprendre à créer des vidéos comme celle-ci avec l'IA, commentez "AI" et je vous envoie le lien.
```

---

## 14. Short Master Prompts for Any New Scene

**Image prompt:**
```
Create a 9:16 cinematic storyboard collage image with clearly separated panels and clean borders.
No text, no captions, no logos, no subtitles.

[Character identity lock]

Show one complete 15-second scene. Each panel = one action beat in order:
opening shot → first action beat → middle action beat → climax → ending frame.

Style: cinematic live-action, 1970s Hong Kong martial arts film, heavy film grain, faded celluloid colors,
warm dramatic lighting, parody-comedy tone but serious performance.

Scene: [Insert scene here.]

Restrictions: no text, no captions, no logos, no subtitles, no children, no gore, no distorted face,
no changing character identity.
```

**Seedance prompt:**
```
Use the reference image as the full visual storyboard for this 15-second scene.
Animate the actions in the same order shown inside the pictorial.

Keep the main character identical to the reference image across the entire shot.
Do not change his face, hairstyle, beard, body type, or outfit unless specifically instructed.

Opening shot: [panel 1]
First action beat: [panel 2]
Middle action beat: [panel 3]
Climax: [panel 4]
Ending frame: [panel 5]

Camera movement: [simple camera movement]
Lighting: [lighting]
Mood: [tone]
Visual style: [style]

Maintain strict character consistency. Do not redesign the person.
```

---

## 15. Key Rules Summary

1. Always preserve main character identity from reference photos
2. Always create one image per 15-second scene
3. Each image = separated-panel storyboard (not blended)
4. Each panel = one clear action beat
5. Never add text/captions/logos/subtitles inside images
6. Always use 9:16 vertical format
7. Use cinematic lighting, film grain, strong composition
8. Seedance prompts always start with the storyboard sentence
9. Keep video prompts direct, ordered, outcome-focused
10. Always describe: opening shot → action beats → climax → ending frame → camera → lighting → mood → style → character consistency
