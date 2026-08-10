---
theme: '@ricoapon/slidev-theme-narrative'
colorSchema: dark
themeConfig:
  accent: '#30A46C'
title: Did The Engineer Learn It Or Did AI?
transition: slide-left
layout: cover
background: /cover.jpg
---

# Did The Engineer Learn It Or Did AI?

---
layout: statement
---

<Kicker>Why talk about this at all?</Kicker>

# AI changed education

<!--
AI doesn't only change work, it also changes the entire education system. Schools already have problems with this. 
In general, it has changed how we learn. So this also has an impact on how we guide other engineers.
-->

---
layout: image-left
image: /me.jpg
---

# Who am I?

<div class="flex flex-col gap-4 mt-4 text-xl">
  <div class="flex items-center gap-3"><div class="i-carbon-book" /> Epic fantasy reader <span class="muted text-base">(Brandon Sanderson!)</span></div>
  <div class="flex items-center gap-3"><div class="i-carbon-music" /> Salsa &amp; bachata dancer</div>
  <div class="flex items-center gap-3"><div class="i-carbon-education" /> Teacher & Coach</div>
  <div class="flex items-center gap-3"><div class="i-carbon-user-certification" /> Lead Engineer at Keylane</div>
</div>

<!--
Main thing to highlight is that I have teaching experience (educational minor + giving courses at Keylane). I guide many
Engineers of different levels, and I am in general interested in these kind of topics. I think about them,
talk about them, and have lots of experience. That makes me suited for talking about this topic.
-->

---
layout: image-right
image: /ai.jpg
---

# Usage of the word "AI"

<Kicker>Chat</Kicker>

## ChatGPT · Claude

<Kicker class="mt-8">In the editor</Kicker>

## Codex · Claude Code

<!--
The word "AI" is used in such a broad concept, where the general meaning (by non-technical people) is often related to
LLMs and the related tooling. I will use it as such as well. Not everybody might be on the same line or use the same 
words, so good to clarify this. If certain words become mainstream, I should switch to these words.

Also good to mention which tools I have the most experience with, just in case.
-->

---
layout: cover
background: /code.jpg
---

<Kicker>Goal</Kicker>

# Help them become a <u>better</u> engineer

---
layout: cover
background: /understanding.jpg
transition: fade
---

# Focus on understanding

---
layout: center
---

# Bloom's Taxonomy

<div class="flex gap-10" style="height: 22rem">

  <!-- Pyramid -->
  <div class="shrink-0 h-full" style="width: 10rem; clip-path: polygon(100% 0%, 100% 100%, 0% 100%)">
    <div class="flex flex-col h-full gap-1">
      <div class="flex-1" style="background: var(--text); opacity: 0.12"></div>
      <div class="flex-1" style="background: var(--text); opacity: 0.19"></div>
      <div class="flex-1" style="background: var(--text); opacity: 0.26"></div>
      <div class="flex-1" style="background: var(--text); opacity: 0.33"></div>
      <div class="flex-1" style="background: var(--accent)"></div>
      <div class="flex-1" style="background: var(--text); opacity: 0.40"></div>
    </div>
  </div>

  <!-- Steps -->
  <div class="flex flex-col gap-1 text-left">
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Create</div>
      <div class="muted">Design a new Spring Boot service from scratch</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Evaluate</div>
      <div class="muted">Decide if logic belongs in the controller or the service</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Analyze</div>
      <div class="muted">Trace a request through controller, service, repository</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Apply</div>
      <div class="muted">Build a REST endpoint backed by a repository</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight" style="color: var(--accent)">Understand</div>
      <div class="muted">Explain how Spring injects a @Service bean</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Remember</div>
      <div class="muted">Recall what @RestController and @Autowired do</div>
    </div>
  </div>
</div>

<!--
Understanding is one of 6 steps. It is crucial that you can only apply something that you understood. Sure, you can 
often do something without understanding it (following a manual for example). But in general, quality will be higher 
(and it will also feel better) if you understand what you are doing.
-->

---
layout: center
---

# What the research shows

<div class="mx-auto mt-8 flex flex-col gap-3" style="width: 42rem">

  <div class="flex items-center justify-between px-6 py-4 rounded-xl text-left" style="background: color-mix(in srgb, var(--accent) 12%, transparent); border: 1px solid var(--accent)">
    <div>
      <div class="text-2xl font-bold">AI as a mentor</div>
      <div class="muted">"Help me understand how this works."</div>
    </div>
    <div class="flex items-center gap-2 uppercase tracking-widest text-xs" style="color: var(--accent)"><div class="i-carbon-arrow-up" /> Better understanding</div>
  </div>

  <div class="flex items-center justify-between px-6 py-4 rounded-xl text-left" style="border: 1px dashed var(--hairline)">
    <div>
      <div class="text-2xl font-bold">No AI at all</div>
      <div class="muted">The baseline</div>
    </div>
    <div class="uppercase tracking-widest text-xs muted">Baseline</div>
  </div>

  <div class="flex items-center justify-between px-6 py-4 rounded-xl text-left" style="background: rgba(248,113,113,
0.13);  border: 1px solid rgba(248,113,113,0.45)">
    <div>
      <div class="text-2xl font-bold muted">AI as an answer machine</div>
      <div class="muted">"Fix it. Make no mistakes."</div>
    </div>
    <div class="flex items-center gap-2 uppercase tracking-widest text-xs muted"><div class="i-carbon-arrow-down" /> Worse understanding</div>
  </div>

</div>

<div class="citations mt-10 flex flex-wrap justify-center gap-x-6 gap-y-2 text-sm">
  <a href="https://arxiv.org/abs/2309.13060">arXiv 2309.13060</a>
  <a href="https://arxiv.org/abs/2603.24197">arXiv 2603.24197</a>
  <a href="https://arxiv.org/abs/2410.03017">arXiv 2410.03017</a>
  <a href="https://arxiv.org/abs/2506.08872">arXiv 2506.08872</a>
  <a href="https://www.mdpi.com/2075-4698/15/1/6">MDPI Societies 2025</a>
</div>

<!--
Using AI as a teacher will make Engineers sooo much better than Engineers that use it as an answer machine. 
Schools have already figured this out.

The key point: using it as an answer machine is worse than not using AI at all. So careful use is needed.

This goes back to "Focus on understanding". If they use AI to improve their understanding, then they basically have 
a teacher that is available for their questions 24/7.
-->

---
layout: statement
---

# Apply &ne; understanding

So how do you check?

<!--
Bloom's Taxonomy showed that you need to understand something to apply it. But nowadays, seeing it applied is not a 
good indication anymore for understanding. Result was never equal to understanding, but in some cases it was a good 
indication. If somebody programmed a  feature, then it is pretty clear they understood the design and how to 
implement the feature. Good enough.

These days, it could have been the result of a prompt, which could be generated without any understanding.
-->

---
layout: center
---

# Review chat history

<div class="mt-10 flex justify-center gap-12">
  <div class="px-5 py-4 text-xl rounded-2xl" style="border: 1px solid var(--hairline)">Fix it. Make no mistakes.</div>
  <div class="px-5 py-4 text-xl rounded-2xl" style="border: 1px solid var(--hairline)">Help me understand how this works.</div>
</div>

<!--
I think this is THE best way to see if they understood a topic. Their chat history shows you HOW they use AI: are they 
outsourcing the thinking ("fix it, make no mistakes") or using it to learn ("help me understand how this works")?

They might be scared to share it though, because it is so personal. Sharing is sometimes technically also a bit more 
difficult if it is split up in different chats or when using a desktop app. Figure out a way together. It is new 
technology and everyone does it differently. You might learn something from it too!

End on the call to action: their next PR, ask for the chat history. That is the one concrete thing to do on Monday.
-->

---
layout: cover
background: /end.jpg
---

# It was never about the code

<div class="mt-2 mx-auto w-max flex flex-col items-center gap-3">
  <div class="w-52 h-52 rounded-lg" style="background: url(/qr-code.png) center / contain no-repeat" role="img" aria-label="QR code linking to the slides"></div>
  <div class="px-4 py-2 rounded-full" style="background: var(--scrim)">github.com/ricoapon/slidev-guiding-engineers-ai</div>
</div>
