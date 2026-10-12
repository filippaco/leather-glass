# Leather Glass

A web-based interactive self-portrait, made for the course *GCT 501 Introduction to Culture Technology* at KAIST.

**Play it:** https://filippaco.github.io/leather-glass/
*(Best on a computer, with sound on. Click once on the page to start the audio.)*

## About

*Leather Glass* is a portrayal of an inner world, generated with Claude through iterative prompting. I'm Swedish, studying in a Korean class, so I wanted something that works without a shared language.

- **Move calmly:** the sky is warm and the music is mellow.
- **Move fast:** the spikes sharpen, the sky darkens and black holes open in the field.
- **Stop moving:** the black holes slowly pull you in. Falling in doesn't end anything. You respawn and keep going.

Four memories appear one at a time, each somewhere new in the field: a woman smoking behind a glass door, a flower blooming, rings of colour like different eras of a life, and a record player. When you've found all four, the field becomes a warm apartment at dinner, and the black orb takes the empty chair at the table.

## How to play

- **Mouse or touch:** move to steer. The further your cursor is from the blob, the faster it goes.
- **Memories:** stay calm and still on the golden shine to open one. A soft glow at the edge of the screen points you towards it.
- **Black holes:** the more memories you find, the more holes appear.
- **Ending:** after the last memory, move the blob onto the empty chair and hold it there.

## Technical notes

- A single self-contained `index.html` file, with no build step and no dependencies except one Google Font (Cormorant Garamond) for the title.
- Everything is drawn live on an HTML canvas: the blob, sky, field, memories and ending.
- The sound is generated in the browser with the Web Audio API (no audio files). The tempo and brightness follow how fast you move.

## Made with generative AI

The ideas, feelings and design decisions are mine. They came from 25 questions about myself that I answered with Claude. Claude helped me turn those answers into concepts and wrote the code, and I directed it over many rounds of feedback.
