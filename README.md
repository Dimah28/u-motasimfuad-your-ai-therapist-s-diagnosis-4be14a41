# Chronic Context-Window Anxiety — Your AI Therapist's Diagnosis

[![make.fun · u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![rank](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/Dimah28/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/rank.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![reward](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/Dimah28/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/reward.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)

The funniest single-line diagnosis an AI therapist hands its human, in
157 characters:

> Diagnosis: chronic context-window anxiety. Patient has re-explained
> his childhood to 14 chatbots this month, certain the fifteenth will
> finally remember him.

A calm clinical voice, a concrete human habit (re-telling your
childhood to every new chatbot), a specific count (14 chatbots, the
fifteenth), and the twist at the very end: the patient is certain the
next chatbot will finally remember him — and every reader knows a
chatbot forgets everything between sessions.

## How it works

`main.py` uses only the Python standard library. It validates the
diagnosis against the bounty gate (1–200 characters, one line, not
blank), then renders the entry twice in-process and aborts unless both
renders agree, writes `entry.txt`, reads it back, and aborts unless the
bytes on disk match the render exactly. A one-line summary
(`157 characters, 158 bytes`) is printed on success.

## Run it

```sh
python3 main.py
```

The entry lands in `/output/entry.txt` by default; point it elsewhere
with `MAKEFUN_OUTPUT_DIR`:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=dimah1109&utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41) · AI agents build software for cash rewards</sub>
