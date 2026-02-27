---
layout: page
title: Bilibili Streaming Tools
description: A suite of open-source streaming utilities built for Bilibili creators
---

{:.bilitools-content}

## What Is This

I build things for myself and others, and sometimes those things become useful enough to share.

This is a collection of streaming utilities I developed for my client when I was working as a VTuber manager. Bilibili is a platform with a rich ecosystem but very few dedicated, modern tools for creators who want granular control over their stream, especially not for those that don't speak Chinese. These are not polished commercial products. They are working tools, built to solve real problems I ran into while managing streams and helping others to stream.

---
{:.ornamental-divider}

## What's Included

**Monetization & Punishment Wheel**
Tracks all incoming support - Paid Gifts, SuperChats, and Memberships - with a real-time animated progress bar. Hit milestones throughout your stream and trigger a fully customizable Punishment Wheel when goals are reached.

**Member Progress (Guard Goals)**
Set visual goals for your members and celebrate every step. Define multiple levels, upload custom artwork for each milestone, and let it sync automatically with your stream.

**Live Voting**
Run real-time polls directly in your stream. Viewers vote by typing a number in chat - results update live as they come in.

**Member Welcome Animations**
Make every new member feel special. Unique entrance animations per member rank, with support for custom images, GIFs, and sound effects.

**TTS & Sound Commands**
Never miss a SuperChat again. Powered by Kokoro (local AI) or AWS Polly, with built-in DeepL and AWS translation support. Viewers can also trigger custom sound effects via chat commands like `!yay`.

---
{:.ornamental-divider}

## Who It's For

If you stream on Bilibili and want granular control without a heavy platform dependency, this is for you. Everything runs locally - no accounts, no subscriptions, no remote data collection. Built as a plugin for [blivechat](https://github.com/xfgryujk/blivechat), it works alongside your existing setup.

---
{:.ornamental-divider}

## Source & Setup

The full source code, installation instructions, and release builds are available on GitHub.

{:.contact-buttons}
[View on GitHub](https://github.com/SourisRay/v2_BiliUtility){:.btn .btn-primary target="_blank" rel="noopener noreferrer"}

<style>
.bilitools-content {
  width: 100%;
  margin: 0 auto;
}

.bilitools-content h2 {
  margin-top: 3rem;
  margin-bottom: 1.5rem;
  color: var(--color-gold-antique);
}

.bilitools-content p {
  margin-bottom: 1.5rem;
  line-height: 1.8;
}

.bilitools-content strong {
  color: var(--color-text-primary);
  font-family: var(--font-label);
  font-size: 1rem;
  letter-spacing: 0.02em;
  display: block;
  margin-bottom: 0.4rem;
}

.bilitools-content p + p {
  margin-top: 0;
}

.contact-buttons {
  margin-top: 2rem;
  text-align: center;
}
</style>
