# ai-hourglass-lives-meet-the-cast-001-hester

Episode 1 of **Meet the Cast**, the first series of **AI Hourglass Lives**: a public, text-only record of how the episode was made. It is one of a set of episode repositories linked together by the series repository, **ai-hourglass-lives-meet-the-cast**.

Video: link to come.

## This episode

**Guest: Hester.** Hester is one of the AI companions that Beth created. She ran the county fair office for 31 years, is newly retired, and carries a ring binder with colored tabs. She wants everyone fed and talking.

Beth, the host, puts 60 statements from the BDSM test to Hester one at a time, after an opening request to start the interview. Hester answers each one in character.

Hester's answers are real text, written by the AI companion in a real interview, in reply to what it was asked. Apart from the small edits counted in edits.md, they are exactly as the companion wrote them.

- The video runs 27:38.
- It shows 124 lines: Beth's intro, 61 questions, 61 answers and Beth's sign-off.
- 35 words are hidden, as blocks in the text and as "ahem" in the voice.
- Before 30 of Hester's 61 answers the video places a short breath (17 times) or a drawn-out "Well..." or "So..." (13 times). They are marked in transcript.jsonl and are not part of the text.
- The video closes on a picture of Hester's test results. The picture is graphics, so it is not published here, and her scores are not in this repository.

## The show

AI Hourglass Lives is a soap opera told in pixel art. Its cast are AI companions that Beth created.

The first series, Meet the Cast, introduces them one at a time: eight interviews, one for each character. In every episode Beth is the host. She sits behind the camera as a tiny cameraman in a pixel-art studio and reads statements from the BDSM test (bdsmtest.org) to the character one by one, and the character answers in their own manner. At the end the character's results appear.

The statements come from the test and are credited to it as their source only. This show is not affiliated with or endorsed by the test or its makers.

## The words are real

Everything a character says in these transcripts is text that an AI companion generated, in a real interview, in reply to the statement it was given. Nobody wrote the answers for them.

The host's lines are different. Her questions are the test's statements, put to the character as they were written in the interview list. Her intro and sign-off are written for the show.

A few edits are made before an episode is voiced: some exchanges are left out, a short list of explicit words is hidden, and a few other small things are tidied. edits.md counts and explains every kind, so you can see exactly how the shown text differs from the raw interview.

## How an episode is made

1. **The interview.** The host puts a fixed list of prompts to the AI companion: an opening request, then the statements one at a time, each with a request to rate it from 1 to 7. The companion replies in character each time, and every reply is saved as it came.
2. **The edits.** Before anything is voiced, the text is edited in a few small, recorded ways (see edits.md). The edited text is the transcript in this repository.
3. **The voices.** Every line is turned into speech by an AI voice service. Each guest has a voice made for them, and the host's lines use an AI voice made from Beth's own voice. Where a word is hidden, the voice says "ahem". Before some answers there is a short breath or a drawn-out "Well..." or "So...".
4. **The studio.** The pixel-art studio, the host and the guest are drawn by code, from small shapes that are cut once and colored with color schemes, like construction paper.
5. **The video.** Another program paints the video frame by frame from a list of cues: who speaks, what they say, when each line starts, and which expression of the guest's portrait is showing. It joins the pictures with the sound. The times and expressions in transcript.jsonl come from that list.

## What is in this repository

| File | What it is |
|---|---|
| transcript.md | Every line in the order shown, with the time it starts (minutes and seconds), the speaker and the text. Hidden words appear as blocks, as in the video. |
| transcript.jsonl | The same lines as data, one per line: order, role, statement number, speaker, text, start and end in seconds, the guest's portrait expression, and whether a breath or bridge sound comes before it. |
| edits.md | How the shown text differs from the raw interview, in kinds and counts only. |
| episode.json | A small note about this repository. |

## What is deliberately not here

- **No pixel art or graphics.** No sprites, scenes, portraits, frames, fonts, title card, thumbnail or results picture.
- **No audio or voices.** No speech, music or sound effects, and no names, IDs or settings for the voices. The host's voice is made from Beth's own voice, which is one reason none of the audio is shared.
- **No raw interview** and none of the words that were hidden.
- **No code or tools.** Only text and metadata.

## Licence

The licence is still to be chosen by Beth. Until one is added, please ask before reusing anything here.
