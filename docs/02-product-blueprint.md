# Product Blueprint

Working title: `Parent-Curated Early Learning App`

This document is the original product direction inspired by the strengths of Khan Academy Kids, adapted to the goals we discussed:

- large content library,
- simple child dashboard,
- strong parent control over what appears,
- whole-child learning,
- calmer and more focused home experience.

## 1. Product Vision

Build a safe, joyful, development-based learning app where:

- children see only a small, friendly set of activities,
- parents choose what appears on the dashboard,
- the full library stays organized behind the scenes,
- content covers the whole child, not just alphabet and numbers.

## 2. Product Positioning

This product should not feel like:

- a chaotic mini-game marketplace,
- a passive video app,
- a worksheet app with loud rewards,
- a clone of Khan Academy Kids.

This product should feel like:

- a calm learning shelf,
- parent-curated,
- age-aware,
- low-pressure,
- replayable,
- rooted in early development.

## 3. Core Differentiator

The core differentiator is not "more content."

It is:

`a giant internal library + a tiny child-facing dashboard`

Parents can select:

- individual activities,
- themed packs,
- recommended age bundles,
- routine bundles such as morning, travel, calm-down, bedtime, or speech practice.

## 4. User Types

### Child

- wants immediate play,
- should not need to browse deep menus,
- benefits from repetition, predictability, and delight.

### Parent / caregiver

- wants to decide what is visible,
- wants easier access to the right content,
- may want only one game on the home screen,
- may want to reduce noise, distraction, or overstimulation.

### Teacher / therapist

- future extension user,
- may want assigned content, progress notes, and grouped playlists.

## 5. Product Principles

- `Calm first`: fewer things on screen, slower pacing, gentle audio.
- `Choice by adults, freedom for children`: adults set the shelf, children explore within it.
- `Whole-child learning`: literacy, language, math, SEL, motor, life skills, creativity.
- `Short loops`: quick wins, easy exits, no endless feed behavior.
- `Repeatable`: activities should improve with repetition, not depend only on novelty.
- `Original expression`: learn from market leaders without copying their visual identity.

## 6. Core Experience Model

### A. Parent setup flow

1. Create adult account
2. Add child profile
3. Choose age band
4. Choose goals
5. Choose dashboard mode
6. Choose visible packs or activities
7. Set sound and stimulation preferences

### B. Child dashboard modes

#### Mode 1: Focus mode

- Parent pins `1` activity or pack.
- App opens directly into it.
- Best for very young users, speech practice, or routine repetition.

#### Mode 2: Shelf mode

- Parent pins `2-6` items.
- Child home screen shows only those selected items.
- Best default mode.

#### Mode 3: Guided mode

- Parent allows a recommended path generated from selected packs and age level.
- Good when the child needs variety without a full library.

#### Mode 4: Full library mode

- Optional.
- Hidden behind a parent gate by default.

## 7. Information Architecture

### Child-facing IA

- `Start` or `Continue`
- `My Shelf`
- `Character / Guide helper`
- `Calm corner`

Optional child-facing tabs if enabled:

- `Books`
- `Create`
- `Music & Move`

### Parent-facing IA

- `Profiles`
- `Dashboard selection`
- `Packs`
- `Library`
- `Progress`
- `Audio & motion settings`
- `Offline downloads`
- `Recommendations`

## 8. Recommended Home Screen

Default child home screen should be simpler than Khan Academy Kids.

Suggested structure:

### Top row

- child avatar
- hidden parent gate entry
- sound icon if enabled

### Main area

- one large `Continue` tile or selected primary tile
- up to five smaller selected tiles

### Bottom area

- optional helper character
- optional calm prompt or off-screen prompt

What should not be on the default child dashboard:

- full category maze,
- too many mascots,
- ads,
- popups,
- seasonal clutter,
- recommended content carousels.

## 9. Parent Dashboard Selection System

This is the most important product system for our app.

Parents should be able to pin content at three levels:

- `Activity`
- `Pack`
- `Routine`

### Activity examples

- Match animals
- Count to 5
- Feelings faces
- Brush teeth steps

### Pack examples

- First Words
- Colors and Shapes
- Calm and Bedtime
- Speech Booster
- Story Time

### Routine examples

- Morning readiness
- Car ride calm pack
- Travel mode
- Post-school wind-down
- Pre-sleep quiet mode

Rules:

- If one item is pinned, open directly into it.
- If multiple items are pinned, show only those items.
- Parent can reorder the dashboard manually.
- Parent can schedule availability by time of day if needed later.
- Full library remains separate from dashboard.

## 10. Recommended Content Model

Each content item should have these fields:

- `id`
- `title`
- `domain`
- `skill`
- `age_band`
- `difficulty_level`
- `interaction_type`
- `estimated_duration`
- `requires_audio`
- `adult_support_level`
- `tags`
- `pack_ids`
- `is_dashboard_eligible`
- `offline_available`
- `progress_type`
- `offscreen_extension`

This schema makes the library manageable and keeps dashboard selection easy.

## 11. Learning Modes

Our app should support three learning modes:

### Structured practice

- clear prompt,
- one goal,
- immediate feedback,
- repeat and reinforce.

### Open-ended creation

- draw,
- place objects,
- tell a story,
- record voice,
- decorate a scene.

### Real-world bridge

- prompt the child to do something away from the screen:
  - find a red object,
  - copy a face,
  - clap a rhythm,
  - act out a story,
  - wash hands with a caregiver.

This third mode is one of the best ways to differentiate from standard mini-game apps.

## 12. Guide Character Strategy

Khan Academy Kids uses recurring characters heavily. We should keep the functional benefits without copying the brand expression.

Recommendation:

- use one original guide character or narrator system,
- keep the helper calm and supportive,
- allow instruction replay,
- use the guide mainly for transitions, praise, and modeling,
- avoid filling the dashboard with many large mascot elements.

## 13. Progress Model

We do not need a heavy score-first system.

Recommended progress layers:

- `Completed`
- `Practicing`
- `Confident`

Parent-facing progress can include:

- recent activity history,
- favorite packs,
- areas played most,
- areas not yet explored,
- gentle suggestions.

Avoid:

- shame language,
- streaks,
- competitive ranking,
- loud prize systems.

## 14. Content Access Strategy

We should split the internal content universe into:

- `Core curriculum`
- `Delight and creativity`
- `Routine and life skills`
- `Calm and regulation`
- `Off-screen companion prompts`

This avoids the trap of dumping every idea into one mixed library.

## 15. Monetization and Trust

Khan Academy Kids is powerful partly because it is free and ad-free.

If our product ever monetizes, the child experience must still remain:

- ad-free,
- no manipulative conversion surfaces,
- no fake scarcity,
- no gated essential learning.

If a paid model is needed later, prefer:

- adult-only subscription screen,
- premium parent tools,
- premium printable packs,
- premium reporting or therapy-oriented features.

Do not put revenue mechanics in kid mode.

## 16. Key Screens to Design Next

- onboarding
- child profile creation
- parent dashboard picker
- child home in focus mode
- child home in shelf mode
- library browser
- pack detail
- activity player
- book reader
- create canvas
- progress screen
- audio and motion settings
- parent gate

## 17. Success Metrics

Recommended product health metrics:

- first-session completion rate,
- percentage of parents who pin at least one dashboard item,
- average number of dashboard items pinned,
- repeat sessions per week,
- average session length,
- library-to-dashboard conversion rate,
- percentage of play launched from pinned items,
- activity completion rate,
- low force-quit / home-out rate,
- parent satisfaction with content control.

## 18. Immediate Build Recommendation

For MVP, do not attempt to match Khan Academy Kids breadth.

Ship:

- profiles,
- parent dashboard selector,
- focus mode and shelf mode,
- 6-8 packs,
- books with narration,
- simple create tool,
- sound and stimulation settings,
- lightweight progress states.

Then expand.
