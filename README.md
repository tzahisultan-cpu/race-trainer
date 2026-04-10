**Race Trainer AI** is a personalized, adaptive running training plan app powered by Claude AI.

You connect it to your Garmin running history (via CSV export), set a race distance — 5K, 10K, 15K, half marathon, or full marathon — and a target finish time. Claude analyzes your recent runs, estimates a realistic goal time based on your actual fitness level, and builds a fully periodized training plan spanning 6 to 20 weeks depending on the race.

What makes it different from static training plans is that it adapts in real time. After every workout, you log what actually happened — distance, pace, heart rate, and how you felt. Claude reads that data and adjusts every future session accordingly. If you're struggling, the plan backs off. If you're ahead of schedule, it pushes you further. If you skip a session, you tell it why — illness, injury, time, weather — and it reshapes the coming weeks around that.

The app also monitors whether your goal time is still realistic as training progresses. If your actual paces consistently diverge from what your target requires, Claude flags it and offers an updated goal, which you can accept or ignore.

The standalone version runs entirely in the browser as a single HTML file with no installation required. Each user connects their own Anthropic API key, and all training data is stored locally on their device. It works on mobile and desktop.
