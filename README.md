# RandomSites

The internet is suffocating under the weight of bloated frameworks.

Millions of dependencies drag systems down like anchors in the void. I didn't want any of that. I just needed pure, functional utility.

Welcome to RandomSites.

This is a collection of tools I have vibecoded into existence. No backend. No massive component libraries. Just raw, single-file HTML applications ready to execute the moment you open them.

***

## The Arsenal

### Workout Tracker (`workout_tracker.html`)

The UI is brutally simple. A dark, sterile interface waiting for input.

It doesn't ask for a login. It doesn't beam your telemetry to a corporate server. It just tracks the session.

**The Mechanics**
You input your total duration. You set the intervals. A slow phase for recovery. A fast phase for the sprint.

You hit start.

The environment shifts instantly. The screen bleeds into a deep, heavy green for the slow phase. When the intervals flip, it snaps to a harsh, adrenaline-pumping dark red.

A clean, synthesized *ding* cuts through the air during the final five seconds of every phase. A sharp auditory cue to brace yourself for the shift.

**The Distance Engine**
The engine calculates theoretical distance with ruthless precision. Fast phases simulate a 20 km/h pace. Slow phases drop to a 10 km/h crawl. The kilometers tick upward on the monitor, providing an unyielding metric of your progress.

**The Emergency Brake**
Sometimes, the physical body fails before the timer does.

I built an override hook directly into the system. Strike the `SPACE` bar. The system slides a prompt into your peripheral vision. Strike it again within five seconds, and the tracker instantly halts the current interval, plunging you into a five-minute pause.

A small, calculated mercy.

***

## Execution Protocol

Deployment is completely frictionless.

You don't need a terminal. You don't need to spin up a local server or install packages.

Just clone the repository and double-click the target HTML file. Your browser will execute the code instantly.

*More tools will be synthesized and added to this repository as the need arises.*