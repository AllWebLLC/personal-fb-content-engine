# 🤖 T's Content Engine — All Web LLC

> *"I don't just talk about AI. I build with it."*
> — Terassah Thompson, Founder · All Web LLC

---

## What This Is

This is my personal content publishing system. Built by me, for me — and eventually, for the clients I serve.

I got tired of the content hamster wheel. Tired of staring at a blank screen. Tired of AI tools that write in a voice that sounds like everyone else's AI tool. So I stopped prompting other people's platforms and built my own.

This is a single HTML file that runs entirely in your browser. No login. No subscription. No backend. Open it in Claude.ai and it's powered by the same model it lives inside. That's the whole trick.

This is what I mean when I say **AI Operations** — not using AI, but architecting it to work *for* you, in your voice, on your schedule.

---

## The Story Behind the Build

Version 1 of this tool was simple: one input box, one output, one platform. Drop a topic, get a Facebook post.

That wasn't enough.

Over several build sessions, this tool evolved into something I actually use daily. Here's what it became and why each layer got added.

---

## What It Does — Feature by Feature

### 🗣️ Three Platform Voices (Not Three Tones — Three Different People)

The biggest mistake AI content tools make is treating "tone" like a dial you turn up or down. That's not how real humans communicate.

I post on three platforms. Each one gets a different version of me:

| Platform | Voice | Rules |
|---|---|---|
| 📘 Personal Facebook | AAVE-comfortable, real talk, community energy | No CTA. No jargon. No hustle. End with a thought, not a link. |
| ⚡ All Web LLC Facebook | The middle ground — warm expert at a local chamber mixer | Educational first. Soft CTA only if it earns its place. Short link only. |
| 💼 LinkedIn | Strategic operator. Contrarian. Authority without announcing it. | No em dashes. No hype words. Receipts over claims. |

Each platform has its own full system prompt baked in — not a tone adjustment. A complete voice rebuild. The Personal FB version doesn't know the LinkedIn version exists.

---

### 📋 Six LinkedIn Post Templates (Plus One That Didn't Fit Anywhere)

LinkedIn posts that perform tend to follow proven structures. Instead of remembering them, I made them buttons.

These unlock only when LinkedIn is selected — they're grayed out everywhere else because they don't belong on Facebook and they know it.

| Template | What it's for |
|---|---|
| ✦ No Template | Freeform. Let the voice lead. |
| 🎯 Tweet Hook | Bold short opener, punchy expansion, key takeaway. Stops the scroll fast. |
| 😬 Failure / Embarrassment | Your L becomes the lesson. The receipts are the credibility. |
| 🔍 Hidden Tool / Resource | Put someone onto something underrated. Knowledgeable friend energy, not salesperson. |
| 📚 Lessons from Learning | Distill what you've consumed into value others can use. Curated, not obvious. |
| 🎁 Viral Giveaway | Social proof + exclusivity + comment trigger. Built for engagement. |
| 🔄 Contrarian Reframe | The "wait, hold on" post. Names the conventional wisdom, names what just changed, sits in the tension, and asks the uncomfortable question out loud. "The gurus said X. Then Y happened. So what was that about?" Pairs best with a URL input. |

---

### 💡 The Operator Lens (LinkedIn Only)

Templates control structure. The Operator Lens controls *perspective.*

When toggled on, the AI doesn't summarize the topic — it translates it. Before writing a single word, it asks: *what does this mean for someone running a service business who wants to grow, scale, and move faster?*

The difference in output is significant. The same article about an Instagram algorithm change becomes either a recap of the change (Open Angle) or a Monday-morning decision framework for a service business owner (Operator Angle).

For URL-based posts especially — paste an industry article, pick Contrarian Reframe, turn on Operator Lens — and what comes out is advisor-level content, not a summary.

---

### 🔄 The Remix Strip — One Source, Three Rooms

This is the workflow that changed everything.

After any post generates, a Remix Strip appears at the bottom of the output. Three buttons. Each one takes the post you just generated and rewrites it for a different platform — without losing the core insight.

Think of it like a master track and two remixes:

```
LinkedIn post (master track — does the heavy thinking)
    ↓
Personal FB remix — slow it down, put it where the goats can get it
    ↓
All Web FB remix — tighten it up, brand hat on, local business ears
```

The AI doesn't just "shorten it" or "make it casual." Each remix has its own specific direction baked in. Personal FB strips the operator framing entirely — barbecue conversation, not boardroom. All Web FB keeps the business angle but makes it local and accessible with a conditional soft CTA.

The button for the platform you're already on hides automatically. No point remixing to yourself.

This means one URL, one topic, one generation — and you walk away with up to three platform-ready posts. That's the ten-minutes-a-day content system.

---

### 🖼️ Topic-Specific Image Prompts (Not Vibes — Visual Journalism)

Every post generation includes an image prompt. Not a generic aesthetic suggestion — a visually specific, topic-connected prompt built like a photo editor at a magazine would think about it.

The prompt imagines: *what single image would stop someone mid-scroll and make them understand the topic instantly?*

- YouTube AI cutting videos → film strip being sliced by a digital blade
- Social graph dying → a web of blue connection threads going cold and dark
- Local SEO → a map pin glowing over a city neighborhood at night

Style direction: editorial, cinematic, dark background. When a person appears, the direction is specific: Black woman, natural lighting, skin texture visible, confident and unbothered. NOT stock photo. Editorial only.

The image prompt works in ChatGPT image generation or Canva AI.

---

### 🤖 Open in ChatGPT Button

One click: copies the image prompt to your clipboard AND opens ChatGPT in a new tab. You land there, open image generation, paste. Two steps instead of four.

Honest about what it does — the platform doesn't currently support pre-loading prompts via URL, so this is the closest thing to one-click image generation available without a proprietary API.

---

## How to Use It

This tool is designed to run inside **Claude.ai** — not as a standalone web app. The Anthropic API authentication is handled by the Claude.ai platform itself, which means no API key management on your end.

**To use it:**
1. Open Claude.ai
2. Upload the `index.html` file into a new conversation
3. Click the artifact that appears
4. The tool is live

**⚠️ Important:** If you open this on GitHub Pages (`allwebllc.github.io/personal-fb-content-engine`), you'll see the interface but get a `FAILED TO FETCH` error when you try to generate. That's not a bug — it's the API authentication working as intended. GitHub Pages has no credentials. Claude.ai does. Run it there.

---

## The Workflow in Practice

Here's how a real session looks:

1. Find an article worth talking about — a platform update, an industry trend, something that contradicts conventional wisdom
2. Open the tool, select LinkedIn, pick Contrarian Reframe, turn on Operator Lens
3. Paste the URL, add your angle, hit generate
4. Read the LinkedIn post. If it's right, copy it.
5. Hit "📘 Personal FB — slow it down" — get the community version
6. Hit "⚡ All Web FB — tighten it up" — get the brand version
7. Copy the image prompt, hit "Open in ChatGPT," paste, generate
8. Three posts. One image. Done in under ten minutes.

That's the system.

---

## What This Isn't

- It's not a prompt ebook
- It's not a subscription tool
- It's not a generic AI content generator that sounds like everyone else

The prompt ebook era taught people how to fish. This is the rod, already rigged, for your specific lake.

---

## What's Coming

This is one tool in a larger stack being built under the S.W.I.F.T. Method — a framework for AI-powered operations built for service businesses that are done doing everything manually.

More tools are coming. Each one solves a specific operational bottleneck. Each one gets parked here.

---

## About the Builder

**Terassah Thompson**
Founder · All Web LLC · Newnan, GA

U.S. Army Veteran · MBA · MA in I/O Psychology · Google GenAI Certified
AI Operations Specialist · 12+ years in digital marketing

I build systems for service business owners who are tired of being the bottleneck in their own business. Content. Automation. Tech Stack Wrangling. S.W.I.F.T.ly.

*Still Serving. Different Uniform.*

---

**Connect:**
- 🌐 [allwebllc.com](https://allwebllc.com)
- 📋 [Take the S.W.I.F.T. Audit](https://allwebllc.com/audit)
- 📘 [Facebook](https://facebook.com/allwebllc.SWIFT)
- 💼 [LinkedIn](https://linkedin.com/in/terassahthompson)
- 📸 [Instagram](https://instagram.com/allwebllc_swift)

---

*Built with Claude · Owned by All Web LLC · Newnan, GA*
