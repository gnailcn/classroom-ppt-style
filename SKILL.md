---
name: classroom-ppt-style
description: Create or restyle campus/classroom PowerPoint decks in a clean white-background style. Use when Codex needs to generate, rebuild, polish, or convert PPT/PPTX slides for teachers or students, including classroom teaching, course presentations, student project reports, lesson demonstrations, teaching competitions, micro-lecture decks, defenses, and academic reports, with dark readable text, generous whitespace, and restrained blue/teal/orange accents.
---

# Classroom PPT Style

## Design Goal

Produce campus/classroom-ready PPT decks that feel bright, clean, professional, and readable on a projector. The style works for both teachers and students: teaching slides, course presentations, group reports, project demos, defenses, and academic summaries.

Default visual promise: **white background, black/dark text, structured color accents, high whitespace, no funeral-gray monotony, no over-decorated template look.**

## Core Style

- Use a true white or near-white page background.
- Use black or very dark navy text for all main reading content.
- Use color for structure, rhythm, and emphasis, not for long paragraphs.
- Prefer blue, teal, and warm orange accents.
- Keep pages airy: leave margins, avoid dense edge-to-edge blocks, and reduce unnecessary borders.
- Make hierarchy obvious from far away: title, subtitle, section label, card heading, bullet body.
- Preserve classroom practicality over visual spectacle: projected readability wins.

## Color System

Use this palette unless the user gives a school or brand palette:

- Ink: `#111827` or `#0F172A` for titles and body text.
- Secondary text: `#4B5563` for dates, footers, and metadata.
- Blue accent: `#2563EB` for objectives, process, numbered nodes, and section markers.
- Teal accent: `#00827C` or `#0D9488` for technology, practice, bridge lines, and icon details.
- Orange accent: `#F59E0B` for warnings, key questions, highlights, and warm visual energy.
- Pale blue: `#DBEAFE`, pale teal: `#CCFBF1`, pale orange: `#FEF3C7` for soft card backgrounds.
- Border: `#CBD5E1` or lighter; use sparingly.

Never turn the whole deck into black/white/gray only unless the user explicitly asks for monochrome.

## Layout Patterns

- Cover slide: large bold title on the left or center-left, short subtitle below, one small colored label above, one colored stripe or chip near the title, sparse footer metadata.
- Section slide: large section number or label, concise section title, one accent color and abundant whitespace.
- Content slide: 2-4 cards or columns; each card has a clear heading, short text, and a colored number/icon marker.
- Dense teaching slide: use cards, timelines, or split panels to group content; do not box every sentence.
- Summary slide: use three key takeaways or a simple map; avoid heavy paragraphs.
- Thank-you slide: centered title, three small colored feature icons or chips, clean footer metadata.

## Typography

- Prefer readable sans-serif fonts available in Office, such as Microsoft YaHei, DengXian, Aptos, Calibri, or Source Han Sans if available.
- Use strong title weight and clear size contrast.
- Body text should be large enough for classroom projection; avoid shrinking text to fit too much content.
- Keep Chinese and English spacing tidy. Avoid decorative fonts for body text.

## PPT Creation Workflow

1. Inspect the source material, target audience, and classroom use case.
2. Decide whether to preserve the existing deck structure or rebuild slides from content.
3. Apply white background and dark text first.
4. Add color accents only after the content hierarchy is clear.
5. Use cards, section markers, numbered dots, thin top bars, and pale highlight blocks to organize information.
6. Remove or simplify dark backgrounds, excessive gradients, heavy shadows, and decorative clutter.
7. Export preview images for at least the cover, one dense content slide, and the final slide.
8. Visually inspect the preview before finalizing.

## Tool Requirements

- This skill is a style and workflow guide, not a standalone PPT generation engine.
- For creating or editing PPT/PPTX files, use the PPT generation or presentation tooling available in the current Codex environment.
- In Codex Desktop, this usually pairs with the built-in Presentations capability.
- If the user is manually applying the style, PowerPoint, Keynote, WPS, Google Slides, or similar slide editors can all follow the style.

## Restyling Existing PPTX

When converting an existing deck:

- Create a copy; never overwrite the original unless explicitly requested.
- Use the available presentation editing tools to preserve or rebuild the deck as needed.
- Preserve text, slide order, and teaching intent.
- Remove full-slide dark decorative images if they conflict with white-background readability.
- Convert large panels to white or pale accent fills.
- Convert small icons, numbers, and visual markers to blue/teal/orange accents.
- Keep main text black/dark; use color only for labels, bullets, chips, icons, and emphasis.
- Reduce visual noise from unnecessary text-box borders.
- Validate by opening the output and exporting previews.

## Generation Prompt Template

Use this style direction when asking a model or script to create slides:

> White-background modern classroom teaching PPT. Use dark high-readability text, generous whitespace, clear hierarchy, and restrained blue/teal/orange accents. Use pale accent cards, numbered dots, thin section bars, and simple icons to organize content. Keep the tone professional, bright, and projection-friendly. Avoid dark backgrounds, excessive gray, cluttered borders, flashy gradients, and over-decorated templates.

## Quality Checklist

- The deck still reads clearly if viewed from the back of a classroom.
- Main content is black or near-black, not colored for decoration.
- Color helps the viewer understand structure or emphasis.
- White space is intentional and not just empty.
- No slide feels like a gray office form or a funeral announcement.
- No slide relies on low-contrast text over tinted backgrounds.
- Preview images confirm that the cover, dense content, and final slide look coherent.
