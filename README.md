# Fractional Upscale Factors: Why 1.25× Can Lose to 1.333×

Measured on a real photograph: 5/4 upscaling scored 0.64 dB worse than the larger 4/3 factor in 5 of 5 crops. PSNR at fractional ratios is not monotonic, and sharpening only pays when detail was already lost.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-fractional-upscale-factors/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
