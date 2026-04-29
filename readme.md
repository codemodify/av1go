# when
- started `2026 March 18`
- last update `2026 April 29`
- experiment concluded on `2026 April 29`

# what
- a science project to learn how to use AI and research what it can do

# scope
- as a toy project I picked to implement the AV1 video encoder/decoder based on the specs at https://aomediacodec.github.io/av1-spec/av1-spec.pdf

# results
&nbsp;		| status					| url
|----		|----						|----
Claude		| &#x2705; done, success	| https://github.com/codemodify/av1go-claude
Codex		| &#x2705; done, success	| https://github.com/codemodify/av1go-codex
Grok		| &#x274C; done, failed		| https://github.com/codemodify/av1go-grok
Gemini		| &#x274C; done, failed		| https://github.com/codemodify/av1go-gemini

&nbsp;		| personal remarks (so far)
|----		|----
Claude		| worked surprisingly well, almost magically reads your mind, as of today (2026 April 12) it got nerfed
Codex		| knows low level stuff, a bit grumpy and likes being baby-sited at times, 5.4 failed miserably similar to Gemini below, after switched to 5.5 it worked wonders, the videos play, I stopped at playing 90% with some glitches but the conclusion is that if I keep going with 5.5 it will succeed as it make a radical difference since started to use it
Grok		| it is honest, does not waste your time, for now it's good for light projects with answers from Stack Overflow or similar
Gemini		| out of control hallucinations, a wild horse doing whatever it wants, appears to start well but in reality it just bluffs, talks sweet but results are lacking - it just burns tokens, use Grok instead for now, complains a lot, forgets what we spoke 5 min ago, hogs the CPU, crashes a lot, it took a complete crash and a forced restart to analyze its own coding to acknowledge it broke the implementation few iterations ago and we've been headed for the last day into a wrong direction, it did this to me a few times, overall probably a smart attempt from Google to not follow the crowd but have a dedicated IDE, for now useful for light tasks only, this is probably normal for a Beta but no good for actual work. After taking me to strange roads for days it tells me this was all a pretend. I got the receipts, see screens. At this point this is worse than saying "dude you are nuts I'm not ready for this project" like Grok did.