---
layout: page
title: About
description: Learn more about my approach to scriptwriting
---

{:.about-content}

{:.welcome-section}

<div class="welcome-container">
  <div class="welcome-image">
    <img src="{{ site.baseurl }}/assets/images/profile.jpg" alt="Souris Ray">
    <p class="image-credit">Art Credit: joy_oops</p>
  </div>
  <div class="welcome-text">
    <h2>Welcome</h2>
    <p>You've arrived at a quiet place. I'm Souris Ray, and these are my scripts - writeen slowly, offered openly, waiting patiently for voices yet to come. Make yourself comfortable. I hope you find something worth staying for.</p>
  </div>
</div>

## Philosophy

I believe a script should build towards something complete. The story itself can be simple, but the progression must be clear, logical, and earned. What I car about is emotional complexity. Real feeling is rarely one piece at a time. We as human carry contradictions. We react in ways shaped by experiences no one else shares. Two people in the same momnet may feel entirely differently, and both are valid and true.
I would like my script to reflect that. Through simple stories, I try to show the nuance of what it means to feel.

## My Approach

Every script beings with a single thread: a character and a moment that can be captured in one sentence. From there, I build outward - designing each act, then filling in the details until the story feels complete.

I believe in clear sturctures. It keeps the story honest and helps it breathe. But sturcutre alone isn't enough. A script needs to communicate intention - not just what happens, but why it matters and how it should feel. That's why my scripts are rich with acting notes and sound cues. These scripts may be recorded by actors who I may never speak to, so the script itself must do the work of a converstaion. Every pause is deliberate, and every note is there to help the actor understand what lives beneath the words. Even if the voice actors choose to interpret things differently, I believe it matters to understand the original intention first. Improvisation is the most powerful when it comes from a place of understanding.

Emotionally, I like the script to take things slow I build graduatlly, relying on the voice itself to carry the feeling. Strong prosody and subtle shifts create a performance that earns its emotional peaks. Sound cues are there to support but not to replace scene building, to hint at what's coming, and to appeal to something felt before it's understood.

## Collaboration

All scripts are open-source and free to record unless explicitly marked otherwise.

I only ask that if you plan to use a script, you let me know beforehand. I appreciate hearing from voices who connect with my work.

I'm not currently open to commissions or requests, but I welcome suggestions for themes. If there's a feeling or scenario you'd like to see explored, I'm always listening.

Before recording, please visit the [guidelines ]({{ site.baseurl }}/guidelines) page. It covers everything you need to know about credit, usage, and how to approach these scripts with care.

---
{:.ornamental-divider}

## Connect With Me

The best way to reach me is through Discord. Join the community to discuss scripts, share feedback, or just chat.

{:.contact-buttons}
[Join the Discord]({{ site.discord_url }}){:.btn .btn-primary target="_blank" rel="noopener noreferrer"}

<style>
.about-content {
  width: 100%;
  margin: 0 auto;
}

/* Welcome Section with Image */
.welcome-section {
  margin-bottom: 4rem;
}

.welcome-container {
  display: grid;
  grid-template-columns: 300px 1fr;
  gap: 3rem;
  align-items: start;
  margin-bottom: 3rem;
}

.welcome-image {
  position: relative;
}

.welcome-image img {
  width: 100%;
  height: auto;
  border-radius: var(--radius-md);
  border: 2px solid var(--color-gold-antique);
  box-shadow: var(--shadow-md);
  transition: all var(--transition-normal);
}

.welcome-image img:hover {
  box-shadow: var(--shadow-lg), var(--shadow-glow-gold);
  transform: translateY(-4px);
}

.image-credit {
  font-family: var(--font-label);
  font-size: 0.75rem;
  color: var(--color-text-muted);
  text-align: center;
  margin-top: 0.5rem;
  font-style: italic;
}

.welcome-text h2 {
  margin-top: 0;
  margin-bottom: 1.5rem;
  color: var(--color-gold-antique);
  font-family: var(--font-heading);
  font-size: 2rem;
}

.welcome-text p {
  line-height: 1.8;
  margin-bottom: 1rem;
}

/* Responsive: Stack image on top for smaller screens */
@media (max-width: 768px) {
  .welcome-container {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .welcome-image {
    max-width: 300px;
    margin: 0 auto;
  }

  .welcome-text {
    text-align: center;
  }
}

.about-content h2 {
  margin-top: 3rem;
  margin-bottom: 1.5rem;
  color: var(--color-gold-antique);
}

.about-content p {
  margin-bottom: 1.5rem;
  line-height: 1.8;
}

.about-content p:first-of-type::first-letter {
  font-family: var(--font-heading);
  font-size: 3.5rem;
  font-weight: 700;
  line-height: 1;
  float: left;
  margin: 0 0.15em 0 0;
  color: var(--color-gold-antique);
}

.contact-buttons {
  margin-top: 2rem;
  text-align: center;
}
</style>
