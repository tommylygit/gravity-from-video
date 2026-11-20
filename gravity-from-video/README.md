# Gravity from video

A small reproduction of the gravity test from **WorldBench** (Upadhyay et al., 2026, [arXiv:2601.21282](https://arxiv.org/abs/2601.21282)), using my own phone videos.

**Question:** if I track a falling object in a video and fit its trajectory, do I recover g ≈ 9.81 m/s²? And do videos produced by a video-generation model give the same value?

## Status

Work in progress.

- [ ] Record real drops
- [ ] Track the ball in each frame
- [ ] Fit the trajectory and estimate g with an uncertainty
- [ ] Run the same pipeline on generated videos
- [ ] Compare and write up the results

## Setup

- Ball: (to fill in)
- Camera: (phone model, frame rate)
- Scale reference: (object of known size, placed in the plane of the fall)
- Drop height: (to fill in)

## Repository layout

```
data/real/         short clips of real drops
data/generated/    clips produced by a video-generation model
src/               tracking and fitting code
notebooks/         exploration
results/figures/   plots used in this README
```

## Results

(to come)

## What didn't work

(to come)
