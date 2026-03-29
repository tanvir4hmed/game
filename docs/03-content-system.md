# Content System

This document turns the raw "game idea" list into a structured content framework that can grow without becoming chaotic.

## 1. Internal Developmental Domains

Use these internal domains for planning, tagging, reporting, and recommendations:

- `Literacy and language`
- `Math and logical thinking`
- `Social-emotional learning`
- `Executive function and attention`
- `Motor and physical development`
- `Life skills and routines`
- `Creativity and expression`
- `World knowledge and discovery`

These are more standardized and scalable than a random mini-game list.

## 2. Child-Facing Shelves

Children should not see the internal taxonomy directly.

Suggested child-facing pack labels:

- `Words`
- `Numbers`
- `Feelings`
- `Shapes`
- `Move`
- `Books`
- `Create`
- `Everyday`
- `Animals`
- `World`
- `Calm`

## 3. Age Bands

Recommended app age bands:

- `0-18 months`: caregiver-led companion content only
- `18-24 months`: first interactive play
- `24-36 months`: matching, naming, routines, feelings
- `36-48 months`: stronger sequences, patterns, stories
- `48-60 months`: pre-K / kindergarten foundations
- `60-96 months`: optional advanced extension if we want school-ready content later

## 4. Content Unit Types

Every item in the system should be one of these:

- `Activity`
- `Book`
- `Song or video`
- `Create prompt`
- `Routine card`
- `Off-screen prompt`

## 5. Activity Interaction Types

Tag each activity with one main interaction type:

- `tap`
- `drag`
- `match`
- `sort`
- `trace`
- `listen and choose`
- `sequence`
- `story response`
- `creative free play`
- `movement prompt`

## 6. Core Packs

Below is the recommended pack system. This is the cleanest way to organize a very large library.

### Literacy and language packs

- `First Words`
- `Animal Names`
- `Everyday Objects`
- `Action Words`
- `Body Parts`
- `Opposites`
- `Prepositions`
- `Rhymes`
- `Letter Sounds`
- `Uppercase and Lowercase`
- `Tracing Letters`
- `Sight Words`
- `Story Listening`
- `Story Retell`
- `Vocabulary Builder`
- `Question Words`
- `Sentence Builder`
- `Print Awareness`
- `Decodable Readers`
- `Read Along Stories`

### Math and logical thinking packs

- `Count to 3`
- `Count to 5`
- `Count to 10`
- `Count to 20`
- `More and Less`
- `Big and Small`
- `Same and Different`
- `Sorting by Color`
- `Sorting by Shape`
- `Pattern Play`
- `Compare Numbers`
- `Simple Addition`
- `Simple Subtraction`
- `Shapes Basics`
- `Measurement Basics`
- `Time and Sequence`
- `Ten Frames`
- `Number Line Play`
- `Puzzles and Logic`
- `Memory Match`

### Social-emotional packs

- `Faces and Feelings`
- `Happy Sad Angry Calm`
- `Friendship`
- `Sharing and Taking Turns`
- `Kindness`
- `Helping`
- `Manners`
- `Empathy`
- `Problem Solving`
- `Waiting and Self-Control`
- `Calm Breathing`
- `Bedtime Wind-Down`
- `School Readiness Feelings`
- `Safety Feelings`

### Executive function and attention packs

- `Focus Finder`
- `Remember the Pattern`
- `Follow the Rule`
- `Switch and Sort`
- `Find the Difference`
- `Stop and Go`
- `Copy the Sequence`
- `Plan the Steps`

### Motor and physical development packs

- `Tap Targets`
- `Drag and Drop`
- `Trace the Path`
- `Stack and Balance`
- `Follow the Motion`
- `Finger Warmups`
- `Scissor Skills Companion`
- `Healthy Habits`
- `Food and Nutrition`
- `Movement Songs`
- `Dance and Freeze`

### Life skills and routine packs

- `Brush Teeth`
- `Wash Hands`
- `Get Dressed`
- `Clean Up Toys`
- `Snack Time`
- `Toilet Routine`
- `Morning Routine`
- `Bedtime Routine`
- `Crossing the Street`
- `Home Safety`
- `Community Helpers`
- `Going to the Doctor`
- `Travel Day`

### Creativity and expression packs

- `Color and Paint`
- `Sticker Stories`
- `My Voice Story`
- `Pretend Scenes`
- `Music and Rhythm`
- `Sing Together`
- `Dance Together`
- `Make a Number Story`
- `Retell a Book`
- `Emotion Art`
- `Build a Scene`

### World knowledge and discovery packs

- `Animals`
- `Ocean Life`
- `Birds`
- `Insects`
- `Fruits and Vegetables`
- `Weather`
- `Seasons`
- `Vehicles`
- `At Home`
- `At the Park`
- `At School`
- `Farm`
- `Space Basics`
- `Plants and Growth`
- `Day and Night`
- `Land Water Sky`

## 7. Example Activity Templates

### Template: Tap and name

- child sees one item,
- narrator says the word,
- child taps,
- item animates,
- narrator repeats,
- optional second prompt asks the child to find the named item.

Good for:

- first words,
- animals,
- feelings,
- colors.

### Template: Match pair

- child drags or taps matching items,
- feedback is immediate,
- difficulty increases by count or distractors.

Good for:

- shapes,
- numbers,
- letters,
- object categories.

### Template: Sort buckets

- child places items into bins,
- items can be sorted by color, size, type, emotion, or beginning sound.

Good for:

- logic,
- vocabulary,
- executive function.

### Template: Narrated story check-in

- short story page,
- one gentle question,
- one choice or open repeat prompt.

Good for:

- comprehension,
- SEL,
- language.

### Template: Create and retell

- child decorates a scene,
- records voice,
- plays it back.

Good for:

- story language,
- math story problems,
- emotional expression.

### Template: Off-screen bridge

- app gives a short real-world mission,
- adult can join,
- app celebrates completion without needing proof.

Examples:

- find something blue,
- show a happy face,
- clap three times,
- wash your hands with a grown-up,
- point to your nose.

## 8. Metadata Schema

Recommended content metadata schema:

| Field | Type | Purpose |
| --- | --- | --- |
| `id` | string | Stable content key |
| `title` | string | Display title |
| `content_type` | enum | Activity, book, video, create, routine, off-screen |
| `domain` | enum | Standardized learning domain |
| `pack` | string | Main pack assignment |
| `subskill` | string | Fine-grained skill |
| `age_band` | enum | Development fit |
| `difficulty` | integer or enum | Sequencing and adaptation |
| `interaction_type` | enum | Input model |
| `duration_minutes` | number | Expected time |
| `adult_support_level` | enum | Solo, assisted, co-play |
| `audio_level` | enum | Silent, low, narrated |
| `motion_level` | enum | Static, gentle, active |
| `offline_ready` | boolean | Download planning |
| `dashboard_eligible` | boolean | Parent pinning |
| `progress_mode` | enum | Complete, practice, mastery |
| `prerequisites` | array | Sequencing |
| `offscreen_extension` | string | Real-world follow-up |

## 9. Dashboard Eligibility Rules

Not every content item should be pin-able to the child home screen.

Good dashboard candidates:

- repeatable activities,
- quick books,
- favorite songs,
- calming tools,
- routines,
- simple create prompts.

Poor dashboard candidates:

- one-time setup activities,
- advanced parent reports,
- dense curriculum browsers,
- complicated multi-step flows.

## 10. Recommendation Logic

The app can recommend content using three simple inputs:

- child age band,
- parent goals,
- recently completed activities.

Parent goal examples:

- speech and vocabulary,
- calm play,
- bedtime,
- fine motor,
- counting,
- school readiness,
- SEL,
- independent quiet play.

## 11. MVP Content Scope

Do not launch with the entire library.

Recommended MVP packs:

- First Words
- Animals
- Colors and Shapes
- Count to 5
- Faces and Feelings
- Brush Teeth
- Story Listening
- Color and Paint

## 12. Expansion Strategy

Phase 1 expansion:

- Opposites
- Prepositions
- Rhymes
- Sorting by Color
- Sorting by Shape
- Calm Breathing
- Weather
- Movement Songs

Phase 2 expansion:

- Letter Sounds
- Tracing Letters
- Count to 10
- Pattern Play
- Friendship
- Helping
- Community Helpers
- Pretend Scenes

Phase 3 expansion:

- Sight Words
- Decodable Readers
- Simple Addition
- Simple Subtraction
- Story Retell
- Problem Solving
- Focus Finder
- Safety packs

## 13. Unique Ideas Worth Adding

These can make the app feel more original and more useful than a normal mini-game app:

- `Calm Corner`: breathing, soft sounds, simple emotion labeling
- `Parent Prompt Cards`: quick off-screen ideas tied to packs
- `Routine Scheduler`: show only morning or bedtime packs at certain times
- `Shelf Rotation`: automatically rotate a small set of parent-approved items
- `Interest Packs`: if a child loves animals or vehicles, surface deeper related content
- `Co-Play Mode`: parent sees quick talking prompts while the child plays
