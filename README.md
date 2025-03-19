# compress

[![Version](https://img.shields.io/badge/version-0.0.1-blue.svg)](https://github.com/hjlarry/dify-plugin-compress)
[![Repo](https://img.shields.io/badge/repo&issue-github-green.svg)](https://github.com/hjlarry/dify-plugin-compress)

A tool to compress Image/Audio/Video files.

When sending a video to the LLM, it extracts the key frames. So, why not compress the video beforehand? This would significantly lower both token and transfer costs.

This tool utilizes Pillow to compress image quality, effectively reducing image size. Additionally, it employs FFmpeg to adjust parameters, minimizing the size of video and audio files.
![1](_assets/1.png)

The video has been compressed to just 1/20 of its original size.
![2](_assets/2.png)


