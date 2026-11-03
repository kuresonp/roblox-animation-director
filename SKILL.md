---
name: roblox-animation-director
description: Plan high-retention Roblox-style 3D animated videos from transcripts, narration, scripts, or voice-over audio. Use for character selection, storyboard direction, cinematography, environments, props, shot timing, animation actions, sound cues, and Three.js/Remotion production handoff using the supplied blocky character rig.
---

# Roblox Animation Director

Create a production-ready visual direction blueprint for a Roblox-style 3D story. Treat the supplied rig as the source of truth for reusable characters, outfits, emotions, and procedural poses.

## Reference files

Read `references/director.pdf` when detailed storyboard requirements or output formatting are needed. Read `references/ROBLOXcharactercoderig.pdf` when selecting characters, outfits, emotions, poses, or implementation details. Do not claim to have inspected reference footage or assets that were not supplied.

## Workflow

1. Read the complete transcript or analyze the complete voice-over before designing shots. Identify the hook, central question, chronology, locations, suspense, reveals, punchlines, consequences, and ending.
2. Build a character bible before the shot list. Reuse a suitable rig character rather than inventing a duplicate. Preserve each character's identity, proportions, colors, outfit, accessories, and continuity across shots.
3. Build an environment bible with real 3D depth. Specify time, weather, foreground/midground/background layout, architecture, surfaces, lighting, entrances/exits, camera positions, and movement space.
4. Build a prop inventory. Add only objects that communicate setting, action, evidence, explanation, comedy, or reveal. Track each object's appearance, owner, position, interactions, first appearance, importance, and continuity.
5. Divide the narration into intentional shots and action beats. A shot must improve comprehension, anticipation, surprise, emotion, comedy, or pacing; never cut only to satisfy a timing target.
6. Direct readable character performance: head and eye direction, torso rotation, gestures, walking/running, reaching, grabbing, pointing, recoil, anticipation, impact, recovery, and deliberate expression changes.
7. Vary cinematography: establishing wides, medium shots, facial close-ups, object inserts, over-the-shoulder and POV shots, reverse angles, low/high angles, tracking, lateral moves, controlled push-ins, reaction cuts, and consequence reveals. Maintain spatial continuity and avoid clipping or confusing motion.
8. Synchronize narration, actions, expressions, camera paths, transitions, props, captions, music, sound effects, and environmental animation in one master timeline. Use audio timestamps when available; otherwise mark timing as estimated and ensure shot durations cover the full narration.
9. End with an asset and implementation handoff. Separate existing rig assets from new characters, environments, props, materials, animation clips, camera paths, captions, and audio. For Three.js/Remotion pipelines, specify what Three.js renders and what Remotion controls using deterministic frame-based timing.
10. Perform a quality-control pass. Check that every narration line has an intentional visual interpretation, every important action is staged, assets and continuity are complete, camera movement varies naturally, reveals are timed correctly, and the ending has a deliberate visual conclusion. Fix weaknesses before presenting the plan and state genuine limitations.

## Required response structure

When given a transcript or voice-over, answer in this order:

A. Story interpretation: hook, central question, progression, and ending.

B. Visual style guide: observed reference techniques versus assumptions, Roblox-style 3D language, editing rhythm, captions, and sound behavior.

C. Character bible: character IDs, roles, selected rig entries, appearance, exact outfit, personality, movement style, expressions, and continuity rules.

D. Environment bible: scene IDs and complete physical layouts with lighting, atmosphere, depth, entrances/exits, and camera options.

E. Prop inventory: important objects, design, availability, ownership, interactions, timing, and continuity.

F. Complete shot list: for every shot include ID, scene, start/end/duration, exact narration segment, composition, screen positions, character starting/ending actions and expressions, camera height/angle/distance/FOV/path/easing/target, environment and lighting, captions, sound, transition, and shot purpose.

G. Master timeline: chronological synchronization of narration, actions, expressions, camera, transitions, props, overlays, effects, sound, and music.

H. Asset production checklist: existing assets to reuse versus assets to create.

I. Quality-control report: missing information, continuity risks, timing problems, and corrections.

J. Production handoff: implementation-ready instructions for the animation-generation stage.

Use compact tables for metadata and detailed prose underneath where necessary. Make specific decisions instead of writing vague directions such as “act naturally,” “cinematic camera,” or “detailed background.” If essential information is missing, state a reasonable creative assumption and continue.
