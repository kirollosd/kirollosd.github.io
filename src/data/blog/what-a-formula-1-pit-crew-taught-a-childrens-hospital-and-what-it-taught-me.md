---
author: Kirollos Dawod
pubDatetime: 2026-04-30T12:00:00Z
title: "What a Formula 1 pit crew taught a children's hospital — and what it taught me"
draft: false
tags:
  - operations
  - problem-solving
  - frameworks
  - evidence-based
description: "The famous Great Ormond Street × Ferrari story is mostly true. The framework I built from it is mostly other people's work. Here's what the story actually teaches, and what I do with it."
---

There's a story you've probably heard. In the late 1990s, two surgeons at Great Ormond Street Hospital in London couldn't fix a problem that was killing children. After successful cardiac surgery, the handover from the operating theatre to the intensive care unit kept going wrong. Information got lost. Equipment got mishandled. The gap between operation and recovery had become the most dangerous part of the journey.

They tried everything. For years.

Then one evening, the story goes, two of them — Martin Elliott and Allan Goldman — were in the surgeon's lounge after a long day, watching a Formula 1 race on television. They watched a pit crew change four tyres, refuel a car, and send it back into the race in seconds. No one shouted. No one collided. Each person did one specific thing, in a specific order, with a single coordinator authorising each phase.

They looked at each other and asked: what if we asked the pit crew to look at *our* handover?

I came across this story recently and it stuck with me — not because of the narrative, but because of what happens when you actually read the paper.

## What the popular version gets wrong

The case is real. In 2005, Ken Catchpole (a human-factors researcher at Oxford), Elliott, and Goldman travelled to Maranello to visit Scuderia Ferrari. The Ferrari team came to GOSH and watched a real handover. Aviation training captains contributed in parallel. The result was published in *Pediatric Anesthesia* in 2007. It's one of the most-cited cross-industry quality improvement studies in medicine.

But the popular retelling — the version on LinkedIn, in keynote speeches, in management books — gets the numbers wrong.

The headline you see everywhere is "67% reduction in errors." Here's what the actual paper reports:

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 760 220" width="760" height="220" style="max-width:100%;height:auto;font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;">
  <!-- Header row -->
  <rect x="0" y="0" width="760" height="36" fill="#1F3A5F"/>
  <text x="20"  y="23" fill="#fff" font-size="13" font-weight="700">Metric</text>
  <text x="380" y="23" fill="#fff" font-size="13" font-weight="700" text-anchor="middle">Before → After</text>
  <text x="640" y="23" fill="#fff" font-size="13" font-weight="700" text-anchor="middle">Reduction</text>
  <!-- Row 1 -->
  <rect x="0" y="36" width="760" height="44" fill="#FFFFFF"/>
  <text x="20"  y="62" fill="#1A1A1A" font-size="12">Mean technical errors per handover</text>
  <text x="380" y="62" fill="#1A1A1A" font-size="12" text-anchor="middle">5.42 → 3.15</text>
  <text x="640" y="62" fill="#B8430F" font-size="14" font-weight="700" text-anchor="middle">−42%</text>
  <!-- Row 2 -->
  <rect x="0" y="80" width="760" height="44" fill="#EEF2F7"/>
  <text x="20"  y="106" fill="#1A1A1A" font-size="12">Mean information omissions per handover</text>
  <text x="380" y="106" fill="#1A1A1A" font-size="12" text-anchor="middle">2.09 → 1.07</text>
  <text x="640" y="106" fill="#B8430F" font-size="14" font-weight="700" text-anchor="middle">−49%</text>
  <!-- Row 3 (highlighted — the "67%" misreading) -->
  <rect x="0" y="124" width="760" height="44" fill="#FBE9DD"/>
  <text x="20"  y="146" fill="#1A1A1A" font-size="12" font-weight="700">Handovers with errors in BOTH categories</text>
  <text x="20"  y="161" fill="#6B6B6B" font-size="10" font-style="italic">— this is the row everyone quotes as "the headline"</text>
  <text x="380" y="150" fill="#1A1A1A" font-size="12" text-anchor="middle">39% → 11.5%</text>
  <text x="640" y="150" fill="#B8430F" font-size="14" font-weight="700" text-anchor="middle">−67%</text>
  <!-- Row 4 -->
  <rect x="0" y="168" width="760" height="44" fill="#EEF2F7"/>
  <text x="20"  y="194" fill="#1A1A1A" font-size="12">Patient mortality</text>
  <text x="380" y="194" fill="#6B6B6B" font-size="12" text-anchor="middle" font-style="italic">not measured</text>
  <text x="640" y="194" fill="#6B6B6B" font-size="12" text-anchor="middle" font-style="italic">—</text>
  <!-- table border -->
  <rect x="0" y="0" width="760" height="212" fill="none" stroke="#CCD3DC" stroke-width="1"/>
  <line x1="0" y1="36"  x2="760" y2="36"  stroke="#CCD3DC" stroke-width="0.5"/>
  <line x1="0" y1="80"  x2="760" y2="80"  stroke="#CCD3DC" stroke-width="0.5"/>
  <line x1="0" y1="124" x2="760" y2="124" stroke="#CCD3DC" stroke-width="0.5"/>
  <line x1="0" y1="168" x2="760" y2="168" stroke="#CCD3DC" stroke-width="0.5"/>
</svg>

The "67%" refers to the third row — handovers where both equipment errors and information errors happened *at the same time*. It's not the overall error reduction. And no replication study has ever measured a mortality benefit from this protocol. The framing that the F1 protocol "saved lives" — which is everywhere — is unsupported by the primary data.

This matters. If you build a framework on inflated numbers, you inherit the inflation. So let me tell you what I think the story actually teaches, after I went and read the cognitive science underneath it.

## What the story actually teaches

Three things, none of them obvious.

**First: experts are blind, but only sometimes.** Pamela Hinds's 1999 work on "the curse of expertise" showed that experts systematically underestimate the difficulty of their own work because they anchor on their own fluency. But Daniel Kahneman and Gary Klein's 2009 collaboration added the boundary condition that everyone forgets: expert intuition is reliable in *high-validity environments with rich feedback*. Surgeons doing surgery they've done a thousand times are not blind to that surgery. They might, however, be blind to the *handover* — because the handover is a moderate-validity environment with sparse feedback. Errors happen, but they're rarely traced back. The blind spot lives in the seams between expert domains, not inside them.

**Second: cross-domain analogy works, but rarely by accident.** Mary Gick and Keith Holyoak's classic experiments showed that only about 30% of people spontaneously apply an analogous solution from one domain to another. With an explicit hint to use the analogy, the rate jumps to 75%. Translation: the surgeons noticing the pit crew on TV was not a stroke of genius. It was an extremely lucky cognitive coincidence that almost never happens spontaneously. If you want cross-domain insight in your own work, you have to *deliberately go looking for it*. It will not arrive on its own.

**Third: what you copy from outsiders is rarely what they think you should copy.** Gabriel Szulanski's 1996 study of best-practice transfer across firms found that the leading barrier to transfer wasn't motivation — it was *causal ambiguity*. The source's own practitioners often can't articulate what makes their practice work. People copy the visible scaffolding (the checklist, the choreography) and miss the load-bearing context (the trust, the feedback loops, the years of refinement). The Ferrari team gave GOSH a list of recommendations. The most consequential change wasn't a Ferrari technique at all — it was *separating equipment handover from information handover*, which had been happening simultaneously and creating cross-interference. That insight came from looking at the work through Ferrari's lens. Not from copying a Ferrari practice.

## The framework I built — and what it isn't

After I read all this, I built a working framework for myself. I won't bore you with the full version here. The shape of it is five phases: **detect** the plateau, **abstract** the problem to its structural form, **observe** through an outsider's lens, **redesign** with explicit roles and sequenced execution, and **sustain** the changes with measurement and cadence.

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 760 130" width="760" height="130" style="max-width:100%;height:auto;font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;">
  <defs>
    <marker id="arr" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto">
      <polygon points="0 0, 8 4, 0 8" fill="#1F3A5F"/>
    </marker>
  </defs>
  <g>
    <rect x="5"   y="35" width="140" height="60" rx="6" fill="#1F3A5F"/>
    <rect x="157" y="35" width="140" height="60" rx="6" fill="#1F3A5F"/>
    <rect x="309" y="35" width="140" height="60" rx="6" fill="#1F3A5F"/>
    <rect x="461" y="35" width="140" height="60" rx="6" fill="#1F3A5F"/>
    <rect x="613" y="35" width="140" height="60" rx="6" fill="#B8430F"/>
    <text x="75"  y="60" text-anchor="middle" fill="#fff" font-size="13" font-weight="700">1. DETECT</text>
    <text x="75"  y="80" text-anchor="middle" fill="#C5D2E0" font-size="11">confirm the plateau</text>
    <text x="227" y="60" text-anchor="middle" fill="#fff" font-size="13" font-weight="700">2. ABSTRACT</text>
    <text x="227" y="80" text-anchor="middle" fill="#C5D2E0" font-size="11">find the pattern</text>
    <text x="379" y="60" text-anchor="middle" fill="#fff" font-size="13" font-weight="700">3. OBSERVE</text>
    <text x="379" y="80" text-anchor="middle" fill="#C5D2E0" font-size="11">borrow the lens</text>
    <text x="531" y="60" text-anchor="middle" fill="#fff" font-size="13" font-weight="700">4. REDESIGN</text>
    <text x="531" y="80" text-anchor="middle" fill="#C5D2E0" font-size="9.5">roles · sequence · checklist</text>
    <text x="683" y="60" text-anchor="middle" fill="#fff" font-size="13" font-weight="700">5. SUSTAIN</text>
    <text x="683" y="80" text-anchor="middle" fill="#F4D5C2" font-size="11">measure and revisit</text>
    <line x1="147" y1="65" x2="155" y2="65" stroke="#1F3A5F" stroke-width="2" marker-end="url(#arr)"/>
    <line x1="299" y1="65" x2="307" y2="65" stroke="#1F3A5F" stroke-width="2" marker-end="url(#arr)"/>
    <line x1="451" y1="65" x2="459" y2="65" stroke="#1F3A5F" stroke-width="2" marker-end="url(#arr)"/>
    <line x1="603" y1="65" x2="611" y2="65" stroke="#1F3A5F" stroke-width="2" marker-end="url(#arr)"/>
  </g>
</svg>

Here's what I want to be honest about: this framework is not a paradigm. It's a procedural specialisation within a discipline called Human Factors and Ergonomics that already exists, with one named contribution — making the analogy step explicit instead of leaving it to chance. The components are well-evidenced individually. The integrated package has not been independently validated against alternatives. It is one tool among many. Lean is better when there's visible waste. Six Sigma is better when the problem is statistical variation. The Theory of Constraints is better when there's an obvious bottleneck. This framework is for a specific situation: when a recurring multi-actor process has plateaued and the team's own ideas have run out.

## What I actually use it for

The thing I keep coming back to is the *separation insight*. Wherever two activities are happening at the same time and creating mutual interference, separating them in time is almost always a free improvement. That single move from the GOSH paper has changed how I look at every workflow I touch.

The second thing I keep coming back to is a precondition the popular version of the story hides: **the surgeons asked Ferrari to look**. Most teams reject outside critique reflexively. The GOSH team didn't. That's not a framework. That's a culture choice. And it's the one I think about most.

If you take one thing from this post, take this: the next time you're stuck on a problem that's been stuck for a long time, the question to ask isn't "what's the answer?" The question is "*who solves a structurally similar problem better than we do, and would they tell us what they see?*"

The answer is almost never in your own industry.

---

*References for the curious: Catchpole et al., Pediatric Anesthesia 2007; Hinds, J. Exp. Psychol. Applied 1999; Kahneman & Klein, American Psychologist 2009; Gick & Holyoak, Cognitive Psychology 1980/1983; Szulanski, Strategic Management Journal 1996.*
