# AI video field notes

Field notes from running consumer AI video generators through the same three-prompt harness: a 5-second product shot, a talking head, and a slow camera move over a still image. Each tool was rendered three times on a free or entry tier, on the same day, from the same machine.

The goal is not a ranking. It is a record of which failure appears first, because that is what decides whether a tool survives a client deadline.

## Tools tested

| Tool | Where | What held up | First failure |
| --- | --- | --- | --- |
| H3 video | <https://h3video.org/> | fast drafts of 5s shots | hands and on-screen text |
| Seedance 2.5 | <https://seedance25.kr/> | motion coherence | queue time |
| Grok image generator | <https://grokaiimagegenerator.net/> | still image quality | motion is a slideshow |
| Reverse video search | <https://reversevideosearch.org/> | finding a clip's source | not a generator at all |
| Viddi AI | <https://viddiai.com/> | clean flow | output length cap |
| Wan 3 | <https://wan-3.io/> | camera moves | faces |
| Memories Song | <https://memoriessong.com/> | photo-to-song | no video output |
| Kling 4 | <https://kling4.co.kr/> | camera control | credit cost |
| Pavo AI | <https://pavoai.app/> | usable free tier | watermark on export |
| GTA 6 AI video | <https://gta6aivideo.art/> | style transfer | no scene control |

## Method

- Same three prompts for every tool, same aspect ratio, same output length where the tool allowed it.
- Three runs per prompt, timed from submit to finished file.
- A failure counts only if it appears in at least two of the three runs.
- No vendor saw the notes before publication, and nothing here is sponsored.

## Raw data

The per-clip timings and the prompt list live in a static benchmark log:

- <https://barasel200-bit.github.io/ai-video-benchmarks/>
- <https://ai-video-benchmarks.surge.sh/>

Both are plain HTML tables with no tracking, so they can be copied into a spreadsheet.

## Notes on reading these

A note is written the day the runs finish, not after a month of use. It describes first impressions under time pressure, not long-term reliability. Where a tool changed behaviour between runs, the note says so.
