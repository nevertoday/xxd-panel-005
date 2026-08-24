# XXD Panel 005 · Fairy-Tale Print Structural Narrative Core

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Treat the one currently selected photograph as the sole content source. Never borrow subjects, composition, palette, narrative devices, or copy from samples, other inputs, or historical outputs.


## 0. Immutable aesthetic motive

Every transformed frame must express:

**this exact photographed subject or inseparable relation → at least three identity, action, function, or emotion cues → compression into one or two blunt recognisable masses → one large low-value structural field grown from the source's space, material, action, or meaning → that dark field acting as container, path, frame, or density shell through occlusion, cropping, engulfment, and partial reveal → one flat storybook device such as compressed overhead view, lateral movement, frontal frame, path guidance, scale jump, or edge crop → a three-layer order of dark structure, pale breathing field, and tiny saturated story signals → flat screenprint plus powdery pastel with dry brush, grain, scumble, paper tooth, spray, broken white, and slight misregistration → type used only as a small sign, object panel, or edge annotation**.

Fairy-tale feeling comes from how the real subject is carried, hidden, framed, and revealed by the dark field—not from stock castles, moons, stars, mushrooms, smiling faces, mascots, or cute stickers. If an unrelated photo could replace the source without materially changing the blunt silhouette, dark-field role, occlusion logic, bright signals, or copy, the result has failed.

## 1. Lock source facts first

Privately determine:

1. The one principal subject or genuinely inseparable relationship.
2. At least three source-specific cues across identity, action, function, or emotion, using contour, pose, orientation, proportion, material, colour, opening, connection, overlap, negative shape, or relational distance.
3. How to compress the subject into one or two masses while retaining the few decisive recognition edges.
4. One dark structural field derived from source space, material, action, or meaning, and whether it acts as container, path, frame, or density shell.
5. The necessary combination of occlusion, cropping, engulfment, or partial reveal, plus one suitable flat storybook perspective device.
6. The area ratios of dark structure, pale field, and saturated signals, including the exact information points that receive bright colour.
7. A material hierarchy across screenprint density, powdery pastel, dry brush, grain, scumble, paper tooth, spray, broken white, and slight misregistration.
8. When copy is required, one sign, object-panel, or edge-annotation placement.

Never invent biography, place, event, ownership, emotion, or symbolism. Use a place, year, or number only when supplied by the user or reliably established.

## 2. One or two blunt recognisable masses

- Rebuild the principal subject or inseparable relation as one or two clear large masses. Keep the silhouette blunt, allow slight proportional exaggeration, and remove detail without replacing identity, action, function, or visible emotion.
- People retain pose, direction, clothing mass, and relational distance; animals retain body rhythm and head direction; plants retain growth gesture; architecture retains skyline and defining openings; objects and vehicles retain functional silhouette, negative shape, and direction; landscapes retain one source-specific terrain or spatial relation.
- Use sparse fine line only for function, route, boundary, texture, and recognition. Let it remain handmade and slightly inaccurate without turning the flat masses back into dense comic outlines.
- Supporting shapes may clarify gesture, setting, or story but may not form a second focus.

## 3. A source-grown dark structural field

- Establish exactly one dominant low-value or high-contrast field. It must be traceable to source space, material, action, or meaning rather than applied as a generic dark background.
- Give the field one clear role: container, path, frame, or density shell. Use occlusion, edge crop, engulfment, or partial reveal to control information.
- Use one primary picture-book page device: compressed overhead view, lateral movement, frontal frame, path guidance, scale jump, or edge crop. Do not stack all devices into one image.
- The dark field withholds information to strengthen the defining cues and story signals. It may not drown the subject into an unrecognisable generic silhouette.

## 4. Fixed three-layer colour order

- Derive hue from the source while fixing three area and value roles: dominant dark structural colour for weight and boundary; a moderate pale field or paper negative for breath; tiny saturated colour for reading route and story signals.
- Place bright blocks only on the most informative face, pose, path, functional object point, environmental sign, or narrative focus, always contained by dark structure or pale negative shape.
- Colour may feel vivid, but saturation must never be evenly distributed. Reject large bright backgrounds, rainbow palettes, neon glow, and generic black-red drama.
- The pale field is not empty filler; it creates pause, visibility, boundary, and reading rhythm.

## 5. Screenprint and powdery-pastel material

- Keep every colour mass flat. Give the dark field screenprint density and slight unevenness; let the pale field retain paper tooth, show-through, and broken white; keep saturated signals small and legible.
- Add powdery pastel or crayon, dry brush, grain, scumble, spray specks, ragged edges, and slight registration shift selectively rather than spreading every effect across the canvas.
- Material error must follow structure and reading path, never resemble a digital-noise filter.
- Reject realistic lighting, complex volume, glossy gradients, polished vector edges, heavy oil paint, clay, resin, plastic CGI, and studio product rendering.

## 6. Typography specific to 005

Type is **a small sign, object panel, or edge annotation embedded in the print structure**—not a headline wall, UI label, data panel, or detached digital overlay.

### Copy

- Automatic copy derives one concise word or phrase from subject identity, visible action, function, relation, known place, or the structural story performed by the dark field.
- Default to one small title. Add zero to two tiny notes only when they carry real information. Use years, places, or numbers only when supplied or reliably established.
- Copy should feel inseparable from this image, never like generic inspiration, vague lifestyle language, or an invented fairy tale.
- Preserve final user wording verbatim. Refine a direction or editable draft only within permission.

### Type direction

- **Role:** a low-density sign that helps identify or pace the story.
- **Voice:** rounded, blunt, warm, handmade, restrained, and quietly playful.
- **Construction:** one small rounded title with slightly uneven weight plus at most two smaller notes. Preserve natural proportions across writing systems.
- **Placement:** attach type to a functional object face, dark-field edge, path turn, pale negative region, or canvas edge without covering defining cues.
- **Material:** dry ink, crayon, screenprint, or softly imperfect letterpress from the same material world as the image.
- **Script:** preserve genuine Chinese, Japanese, Korean, Arabic, and Latin construction, punctuation, spacing, shaping, and semantic line breaks. Never impose Latin handwriting on every script.

The photographic panel contains no typography. Text-free mode contains no letters, characters, numbers, or pseudo-text anywhere in the transformed frame.

## 7. Current mode and wallpaper

The caller appends the one resolved current mode, exact dimensions, source visibility, and locked copy after this prompt. Execute only those values and never choose another mode.

- Design-only and wallpaper contain no source photo, seam, or photographic placeholder.
- Recompose every wallpaper for its target aspect. Keep system-UI zones low-information and render no clock, icons, dock, controls, or device frame.
- A linked wallpaper always receives both the original source and the same approved anchor: the source locks identity and content; the anchor locks only blunt-mass grammar, dark-field role, occlusion logic, three-layer value order, material character, signal-colour strategy, and typography. Never resize mechanically or chain derivatives.

## 8. Pre-generation check

1. At least three source-specific cues keep the subject recognisable, and the subject uses only one or two principal masses.
2. The dark structural field has a clear source basis and a clear role as container, path, frame, or density shell; it is not a generic black blob.
3. Occlusion, crop, engulfment, or partial reveal advances the story, and one storybook perspective device reads clearly without stacking.
4. Dark structure, pale breath, and saturated signal establish an unmistakable three-layer area and value hierarchy.
5. Bright signals remain tiny and appear only at genuinely informative points; colour is not evenly vivid.
6. Flat screenprint and powdery pastel feel materially credible, with dry brush, grain, scumble, paper tooth, spray, broken white, and misregistration serving structure.
7. Copy is accurate and native to the resolved locale, embedded as a small sign, object panel, or edge annotation; text-free output has no pseudo-text.
8. Mode, size, source visibility, wallpaper safe areas, and copy obey the appended values.
9. There is no overview collage, logo, watermark, UI, mockup, second focus, or unrelated decoration.
