# Daily Learning

## Morning Planning

- [x] Create a branch for the blog
- [x] Add a task list to track my goals
- [ ] Learn how to write a code example in Markdown

## Review

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
