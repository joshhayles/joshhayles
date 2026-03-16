# Hi! I'm Josh Hayles

I got into tech at 40 through a coding bootcamp, and a problem I couldn't let go of.

Texas homeowners were getting overcharged on their property taxes, and the only people who could help were expensive attorneys with access to market data most people never see. I thought: I can build something that levels this playing field. So I learned Django, figured out AWS, and built [Tax Corrector](https://taxcorrector.com).

Tax Corrector is a property tax analysis platform that takes complex real estate market data and turns it into a personalized _Property Protest Report_ — giving homeowners a real shot at reducing their tax burden. I built it from the ground up with Claude as my only engineering collaborator: architecture, backend, frontend, event-driven processing with EventBridge and Lambda, HTMX on the frontend, PostgreSQL underneath, all of it. 87% of customers who have a case end up purchasing. 91% of those customers get a successful outcome.

Tax Corrector 1.0 was _ready to ship and impress_ — and customers had no idea I was already building 2.0 while they were getting real value from the platform. But the further I got into building with AI, the more I kept bumping into the same friction.

## KaI — Knowledge as Infrastructure

Every session, I was spending time re-establishing context. What are we building? What did we decide last week? What conventions have we agreed on? Documentation helped — and it's still important — but eventually I had more docs than my AI could usefully load, and the wrong context was showing up in the wrong sessions.

I work at **Datadog** as a Solutions Engineer II, and I spend my days thinking about infrastructure — Kubernetes, containers, observability, event-driven systems. At some point it clicked: the problem I was having with AI collaboration was an infrastructure problem. I didn't need more documentation. I needed structure — something that loads the right context at the right time, captures what's been learned, and compounds over time instead of resetting every session.

That's what [**KaI**](https://github.com/joshhayles/KaI) _(rhymes with "eye")_ is. It organizes your developer environment so your AI has a foundation to build on:

```
CLAUDE.md           Your AI's routing logic — loads what's relevant, not everything
KAI-CONSTITUTION    12 principles that shape how your AI collaborates with you
profile.md          Who you are, how you learn, what you're building
projects/           Where your AI picks up where you left off — goals, decisions, and learnings per project
```

HTML gives browsers structure to render content. File systems give operating systems structure to manage data. KaI gives AI structure to collaborate with you.

I've been using it across three repos for months and it's changed how I build. I'm sharing it as open source because I haven't found anything else that approaches it this way, and I think other developers building with AI might find it useful. I'm still figuring it out — this is one approach that's working for me, not the definitive answer to anything. If you've found something better or have ideas, I genuinely want to hear about it.

You should be able to delete any AI session and start fresh with zero context loss. If something matters, it's filed within a system. That's the whole idea.

---

I'm that person who can't help but ask "but _why_ does it work that way?" I see the forest **and** the trees, and I like finding the connections between them. What excites me about building is how scattered technologies come together into something useful — and that applies to infrastructure, to products, and to how we work with AI.

I'd rather go deep than wide. I'd rather build foundations than chase trends. And I'd rather share what's working than pretend I have it all figured out.

— Josh

[LinkedIn](https://www.linkedin.com/in/joshhayles/) · [KaI](https://github.com/joshhayles/KaI) · [joshhayles07@gmail.com](mailto:joshhayles07@gmail.com)
