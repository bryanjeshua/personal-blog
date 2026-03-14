---
title: "First Impression of Claude Code: An Accelerator, Not a Replacement"
description: "I used Claude Code to build this entire site. Here's what I learned about AI-assisted development — the good, the limits, and why your fundamentals still matter."
date: "2026-03-14"
author: "Bryan Jeshua"
tags: ["ai", "claude code", "building in public", "product management"]
draft: false
---

> **Disclaimer:** This blog post was generated with the assistance of AI. The opinions, experiences, and reflections are mine — the writing was shaped with the help of Claude Code itself.

# First Impression of Claude Code: An Accelerator, Not a Replacement

I built this entire website using Claude Code.

The layout, the dark mode toggle, the gallery component, the blog system, the deployment pipeline — all of it was scaffolded, iterated, and shipped with Claude sitting in my terminal. And I have to be honest: it was fast. Impressively fast.

But "fast" is not the same as "good." And that distinction is where things get interesting.

## What Claude Code Gets Right

The speed is real. I went from a blank Astro starter to a fully styled, dark-mode-enabled personal site with a CMS, blog, photo gallery, and GitHub Pages deployment in a single session. Tasks that would normally eat up a weekend — wiring up Tailwind tokens, writing responsive layouts, configuring build pipelines — happened in minutes.

For someone who works in product and spends most of my coding time in Python and data pipelines, this was a genuine unlock. I could focus on *what I wanted to build* instead of getting stuck on *how to implement it*. I described the Vox.com-inspired editorial aesthetic I was going for, and Claude gave me a working starting point with Fraunces and Outfit typography, a yellow-and-white palette, and magazine-style layouts.

That starting point matters. It means I can explore ideas faster, test directions sooner, and get to the interesting decisions quicker.

## But Here's the Catch

Every single output required tweaking.

Not small tweaks. Real, meaningful adjustments — the kind that require you to *know what you're looking at*. The first version of this site looked fine at a glance. Clean layout, decent spacing, working components. But it was also generic. It looked like what an AI thinks a personal website should look like, because that's exactly what it was.

The color choices were safe. The copy was bland. The component structure was over-engineered in some places and too simple in others. The "Why Choose Us" section on my personal site — a section designed for SaaS landing pages — made no sense for a portfolio. I had to catch that. Claude didn't.

This happened over and over. The blog copy was grammatically perfect but said nothing specific. The feature cards described abstract value propositions instead of real things I've done. The dark mode implementation worked technically but the color contrast wasn't where I wanted it. Each time, I had to step in with an opinion, a correction, a direction.

## The Fundamental Skills Problem

Here's what I keep coming back to: **you can only get good output from AI if you can recognize bad output.**

When Claude generated a CSS color scheme, I could tell whether the contrast felt right because I've looked at enough well-designed sites to have a sense for it. When it wrote marketing copy for my hero section, I knew the first version was too vague because I've worked in product and understand what specific, compelling messaging looks like. When it structured the codebase, I could evaluate the architecture because I write code for a living.

But what if I couldn't?

If I had no design sense, I would've shipped the first version and thought it looked great. If I hadn't studied copywriting frameworks, I would've accepted "Build Something Amazing" as a headline and moved on. If I didn't understand frontend architecture, I wouldn't have known to question the component boundaries Claude chose.

This is the part that concerns me about the current AI hype. The tools are powerful, but they're powerful *in proportion to your existing skill*. A junior developer using Claude Code will ship something that works. A senior developer using Claude Code will ship something that works *and* is well-structured, performant, and maintainable. The difference isn't the tool — it's the operator.

## Taste Is the Bottleneck

There's a concept in creative work called "taste" — the gap between what you can recognize as good and what you can currently produce. Ira Glass talks about it in the context of storytelling, but it applies everywhere.

AI tools like Claude Code close the *production* gap. You can produce more, faster. But they don't close the *taste* gap. You still need to know what good looks like. You still need to have opinions about typography, about information hierarchy, about whether a piece of copy actually says something or just fills space.

When I asked Claude to make the site look like Vox.com, it gave me something that had Vox-like *elements* — bold serif headings, category labels, editorial grid layouts. But it didn't capture the *editorial confidence* that makes Vox's design work. That required me to push back, adjust, and iterate with specific feedback. The AI didn't know what I meant by "editorial confidence." I had to translate my taste into instructions it could execute.

## What I'd Tell Other Builders

If you're thinking about using Claude Code — or any AI coding tool — here's my honest take after building with it:

**Use it.** The productivity gain is real and it's significant. I would not have shipped this site this fast without it.

**Don't trust it blindly.** Read every line of output. Question every design decision. If you can't explain *why* a piece of code is structured the way it is, you don't understand it well enough to ship it.

**Invest in your fundamentals first.** AI makes strong developers stronger. It doesn't make weak developers strong. Learn the craft — the design principles, the architectural patterns, the domain knowledge — and then use AI to move faster within that expertise.

**Develop taste before you develop speed.** Spend time looking at great work in your field. Study what makes it great. Build that internal compass. Because when an AI gives you output, that compass is the only thing telling you whether to ship it or scrap it.

**Treat AI output as a first draft, always.** The best writing happens in editing. The best code happens in review. The best designs happen in iteration. Claude gives you a first draft in seconds. The real work — the work that makes something yours — is everything that comes after.

## The Bottom Line

Claude Code is the best coding assistant I've used. It's fast, it's capable, and it genuinely accelerates the building process. This site exists because of it.

But this site is *mine* because of the hundreds of small decisions I made after Claude gave me its suggestions. The choice to use a Vox-inspired editorial layout instead of a generic portfolio template. The decision to lead with "I turn research into products people actually use" instead of "Welcome to my website." The instinct to kill the "Why Choose Us" section because it didn't fit a personal site.

Those decisions came from experience, from taste, from having built and shipped things before. Claude didn't make those calls. I did.

And that's the real lesson: AI is an accelerator, not a replacement. It multiplies what you bring to the table. Bring more, and you get more. Bring nothing, and you get something that looks like everything else.

---

*This site was built with Astro, styled with Tailwind CSS, and developed with Claude Code. The irony of using AI to write a post about AI's limitations is not lost on me.*
