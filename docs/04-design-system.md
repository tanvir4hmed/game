# Child-Safe Design System

This document defines the visual, audio, motion, and interaction principles for the app.

Important note:

- I did not find a single official pediatric app rulebook for exact color grades or exact audio style.
- The recommendations below are original design guidance informed by current child-development, hearing-safety, screen-use, and accessibility guidance.

## 1. Design Goals

- `Calm`
- `Clear`
- `Friendly`
- `Predictable`
- `Accessible`
- `Playful without overload`

## 2. Emotional Tone

The app should feel:

- welcoming,
- gentle,
- safe,
- curious,
- encouraging.

The app should not feel:

- loud,
- urgent,
- competitive,
- hyper-stimulating,
- cluttered.

## 3. Visual Principles

- Use fewer objects per screen.
- Keep one dominant action per view.
- Favor large targets and clear illustration silhouettes.
- Use consistent icon meanings across the app.
- Limit decorative motion that does not help comprehension.

## 4. Suggested Color System

Use a calm base palette with limited saturated accents.

### Base backgrounds

- `Cream`: `#F8F5EE`
- `Sky Mist`: `#EAF5FB`
- `Mint Wash`: `#EEF8F1`
- `Peach Wash`: `#FFF1E8`

### Core accents

- `Blue`: `#4D8CF5`
- `Teal`: `#2F9E8F`
- `Sunny Gold`: `#F2B134`
- `Coral`: `#E97A5F`
- `Berry`: `#D86494`

### Deep support colors

- `Ink`: `#223046`
- `Slate`: `#56657A`
- `Forest`: `#2E6358`

Rules:

- Use bright color for focus and success, not for every surface.
- Do not place many equally loud accents on the same screen.
- Avoid neon-heavy screens.
- Ensure text contrast meets accessibility requirements.
- Never use color as the only way to communicate meaning.

## 5. Typography

Recommended typography direction:

- rounded, friendly display font for titles,
- highly readable sans-serif for labels and body text,
- generous sizing,
- short lines,
- strong spacing.

Suggested font pairing:

- display: `Fredoka` or another rounded headline font
- UI/body: `Lexend` or another highly readable rounded sans-serif

Rules:

- Avoid tiny labels.
- Avoid all caps for long text.
- Keep instructions short and spoken aloud when possible.

## 6. Illustration Style

Illustration direction should be original and not resemble Khan Academy Kids.

Suggested approach:

- simple soft shapes,
- rounded corners,
- friendly eyes and expressions,
- clear emotional reads,
- limited texture,
- strong object recognition,
- uncluttered backgrounds.

Avoid:

- copying mascot silhouettes,
- recreating their room layouts,
- using lookalike art direction.

## 7. Interaction Rules

- One clear action at a time.
- Minimum tap targets should be large enough for toddler and preschool hands.
- Important controls should stay in stable positions.
- Narration should be replayable with one tap.
- Exits should be easy for adults, not too tempting for children during guided tasks.

## 8. Motion Rules

- Prefer gentle scale, fade, slide, and bounce.
- Keep transitions short and readable.
- Avoid fast flicker, rapid zooms, and chaotic particle bursts.
- Do not exceed accessibility limits around flashing content.
- Offer a reduced-motion setting in the parent section.

Suggested motion levels by content:

- `Static`: books, routine cards, calm corner
- `Gentle`: matching, vocabulary, tracing
- `Active`: movement songs, dance prompts

## 9. Audio System

The sound design should be calmer and more controllable than most kids apps.

### Audio categories

- `Narration`
- `Sound effects`
- `Background music`

### Required controls

- master mute,
- independent music mute,
- separate narration replay button,
- optional low-stimulation mode.

### Audio design rules

- voice should be warm, slow, and clear,
- effects should be short and soft,
- avoid harsh, metallic, or piercing tones,
- avoid constant looping music on every screen,
- music should support mood, not demand attention,
- use pauses and silence intentionally.

### Safe listening guidance for product design

- assume young children may use the device close to their ears,
- avoid loud surprise sounds,
- avoid headphone-dependent design,
- keep rewards emotionally positive without being sonically aggressive.

## 10. Reward System

Rewards should encourage learning without compulsion.

Good reward patterns:

- warm verbal praise,
- tiny celebratory motion,
- collection of gentle stickers or badges,
- visible progress on a pack.

Avoid:

- loud jackpot sounds,
- flashing reward explosions,
- variable-reward compulsion loops,
- streak anxiety,
- frequent interruption to show prizes.

## 11. Books and Reading UX

Book UX should include:

- read-to-me mode,
- read-myself mode,
- word highlighting during narration,
- easy page turning,
- simple replay,
- optional parent discussion prompt.

## 12. Create UX

Creative tools should include:

- crayons,
- pencils,
- stickers,
- scene backgrounds,
- voice recording,
- play back recorded scene,
- gallery save.

Design rules:

- keep tool count limited on first view,
- hide advanced tools behind a simple reveal,
- make saved work easy for adults to review.

## 13. Dashboard UX

The dashboard must support our parent-curated strategy.

Rules:

- if one item is selected, launch directly into it,
- if multiple items are selected, show only selected items,
- show manual order chosen by parent,
- do not auto-fill the dashboard with library content,
- keep the shelf visually stable to build familiarity.

## 14. Parent Gate

The parent gate should be:

- easy for adults,
- hard for accidental child access,
- calm and invisible in kid mode.

Recommended parent gate methods:

- long press plus adult prompt,
- simple math or year-entry challenge,
- profile switch with grown-up confirmation.

## 15. Accessibility

- support screen rotation strategy intentionally,
- ensure text contrast meets WCAG guidance,
- provide captions or text support when practical,
- do not rely on audio only,
- do not rely on color only,
- support reduced motion,
- support music mute,
- support predictable navigation.

## 16. Content Safety and Trust

- no ads in kid mode,
- no third-party recommendation feeds,
- no autoplay chains,
- no pushy upsells,
- no manipulative timers,
- no external links from child screens,
- minimal data collection,
- clear privacy and parental control messaging.

## 17. Session Design

Target session shapes:

- `2-5 minutes` for focus mode,
- `5-10 minutes` for shelf mode,
- `10-15 minutes` for guided mode with breaks.

Use clean stop points:

- after one activity,
- after one book,
- after one song,
- after one calm exercise.

## 18. Source Basis

The design choices above are informed by the following current references reviewed on March 29, 2026:

- CDC milestones: https://www.cdc.gov/act-early/milestones/index.html
- AAP media guidance: https://publications.aap.org/pediatrics/article/138/5/e20162591/60503/Media-and-Young-Minds
- WHO physical activity, sedentary behavior, and sleep guidance: https://www.who.int/news-room/detail/24-04-2019-to-grow-up-healthy-children-need-to-sit-less-and-play-more
- NIH hearing safety: https://www.nidcd.nih.gov/health/protect-your-childs-hearing
- W3C flashing guidance: https://www.w3.org/WAI/WCAG21/Understanding/three-flashes.html
- W3C contrast guidance: https://www.w3.org/WAI/WCAG21/Techniques/general/G18.html
- Khan Academy Kids healthy screen-time article: https://blog.khanacademy.org/healthy-screen-time-young-children/
