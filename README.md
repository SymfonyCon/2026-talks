# [SymfonyCon - Warsaw 2026](https://live.symfony.com/2026-warsaw-con/schedule) talks

> [!IMPORTANT]  
> <ins>If you’re a speaker, please consider sharing your insights in a blog post</ins>, it would really help beginners and uplift the entire community! 🤗

> [!NOTE]  
> - All talks are in **English**.
> - You can send feedback and love to speakers on their social networks.
> - Social posts during the event: [Blusky](https://bsky.app/search?q=%23symfonycon+since%3A2026-11-25+until%3A2026-11-29) · [Mastodon](https://mastodon.social/tags/symfonycon) · [Twitter](https://x.com/search?q=(%23symfonycon%20OR%20%40symfonycon)%20until%3A2026-11-29%20since%3A2026-11-25%20-filter%3Areplies&src=typed_query)
> - [Photos during the event](https://pixi.live/gallery/symfonycon-warsaw-2026)

#### Blog post & videos about the event <sup>[[add link]](https://github.com/SymfonyCon/2026-talks/edit/main/README.md)</sup>

---

## Keynote

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
💻 on [![github](icon/github.svg) @fabpot](https://github.com/fabpot)  <sup>[💚](https://github.com/sponsors/fabpot)</sup>  
✍ on [🌐 fabien.potencier.org](https://fabien.potencier.org)  
💬 on [![bluesky](icon/bluesky.svg) @fabien.potencier.org](https://bsky.app/profile/fabien.potencier.org)
· [![twitter](icon/twitter.svg) @fabpot](https://twitter.com/fabpot)
· [![mastodon](icon/mastodon.svg) @fabpot@mastodon.social](https://mastodon.social/@fabpot)
· [![linkedin](icon/linkedin.svg) @fabienpotencier](https://linkedin.com/in/fabienpotencier)

---

## Web-less Console: Standalone Apps in Symfony 8.2

<dl>
  <dt>Description</dt>
  <dd>The Console component runs almost everywhere PHP does: Composer, PHPStan, most frameworks and CMSes, and your own applications. Until recently, using it outside the full-stack framework meant giving up dependency injection and lazy services, or dragging the entire HTTP layer into a tool that never serves a single request.

Symfony 7.3 redesigned commands to be simpler, more powerful and more expressive. Symfony 8.2 goes further with a DI-powered, HTTP-less foundation: a real container, real service wiring, no web stack anywhere in sight.

Come see what modern Symfony commands look like today, and how standalone CLI applications finally become first-class citizens of the framework.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Robin Chalas](https://connect.symfony.com/profile/chalas_r)  
💻 on [![github](icon/github.svg) @chalasr](https://github.com/chalasr)  <sup>[💚](https://github.com/sponsors/chalasr)</sup>  
✍ on [🌐 baksla.sh/blog](https://baksla.sh/blog)  
💬 on [![bluesky](icon/bluesky.svg) @chalasr.bsky.social](https://bsky.app/profile/chalasr.bsky.social)
· [![twitter](icon/twitter.svg) @chalas_r](https://twitter.com/chalas_r)
· [![mastodon](icon/mastodon.svg) @chalasr@phpc.social](https://phpc.social/@chalasr)
· [![linkedin](icon/linkedin.svg) @robinchalas](https://linkedin.com/in/robinchalas)

---

## Why AI Output Is the New XSS

<dl>
  <dt>Description</dt>
  <dd>Developers know one golden rule: never use innerHTML on user input. Yet, as we're integrating Large Language Models (LLMs) into our applications, we often make a fatal mistake. We're treating AI output as a trusted source. This is fine. Well, not automatically...

Let’s look at OWASP LLM05 and how "Improper Output Handling" affects web security. Therefore, let's discuss examples of how safe inputs can trick models, leading to vulnerabilities such as XSS and injection attacks. By the end, you’ll learn how to be "professionally pessimistic" for AI. You’ll see how to sanitize LLM data, safely render Markdown, and manage AI-generated content. Let's approach technology with caution, I look forward to exploring this with you! ❤️</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Ramona Schwering](https://connect.symfony.com/profile/leichteckig)  
💻 on [![github](icon/github.svg) @leichteckig](https://github.com/leichteckig)  
✍ on [🌐 ramona.codes/blog](https://www.ramona.codes/blog/)  
💬 on [![bluesky](icon/bluesky.svg) @leichteckig.bsky.social](https://bsky.app/profile/leichteckig.bsky.social)
· [![twitter](icon/twitter.svg) @leichteckig](https://twitter.com/leichteckig)
· [![linkedin](icon/linkedin.svg) @ramona-schwering](https://linkedin.com/in/ramona-schwering)

---

## Pedal to the Metal: Compiling PHP to Native Code

<dl>
  <dt>Description</dt>
  <dd>For nearly thirty years, writing PHP has meant writing for an interpreter. When that one Symfony endpoint that won't go faster becomes performance-critical, you reach for a C extension or a rewrite in Go or Rust and leave PHP behind.

Elephc does the opposite. Written in Rust, it compiles a static subset of PHP straight to native machine code: no Zend engine, no fallback interpreter. Your project stays in PHP, only the critical modules go through Elephc.

It's the same wall that stalled a recent generics RFC: monomorphization is free in Rust but too costly in a dynamic engine like PHP. As always, the interpreter is the constraint, not the language.

After a tour of the tool, I'll take you from an everyday example to a Doom-style demo, limitations included. You'll leave with a clear mental model of AOT compilation.</dd>
</dl>

[Slides](https://speakerdeck.com/guikingone/elephc-pedal-to-the-metal-symfonycon-2026)  
~~Video~~  
~~Blog post~~

By [Guillaume Loulier](https://connect.symfony.com/profile/guikingone)  
💻 on [![github](icon/github.svg) @Guikingone](https://github.com/Guikingone)  
✍ on [🌐 guikingone.substack.com](https://guikingone.substack.com)  <sup>[![rss](icon/rss.svg)](https://guikingone.substack.com/feed)</sup>  
💬 on [![twitter](icon/twitter.svg) @guikingone](https://twitter.com/guikingone)
· [![linkedin](icon/linkedin.svg) @guillaume-loulier-…](https://linkedin.com/in/guillaume-loulier-594438101)

---

## Beyond the Demo: Shipping Real AI Features

<dl>
  <dt>Description</dt>
  <dd>Symfony AI gives you the components to ship AI features. It doesn't tell you how to structure them once they hit production. Human-in-the-loop approval, workflows that run for minutes instead of milliseconds, retries, cost tracking, and the extension points you reach for when the happy path stops being enough. This talk walks through the patterns that hold up in real applications, the ones that don't, and where the component boundaries actually sit. You'll leave with a working mental model for designing AI features, not just calling a model.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Christopher Hertel](https://connect.symfony.com/profile/chertel)  
💻 on [![github](icon/github.svg) @chr-hertel](https://github.com/chr-hertel)  
✍ on [🌐 christopher-hertel.de](https://christopher-hertel.de/)  
💬 on [![twitter](icon/twitter.svg) @chr_hertel](https://twitter.com/chr_hertel)
· [![mastodon](icon/mastodon.svg) @chris@phpc.social](https://phpc.social/@chris)
· [![bluesky](icon/bluesky.svg) @chr-hertel.bsky.social](https://bsky.app/profile/chr-hertel.bsky.social)
· [![linkedin](icon/linkedin.svg) @christopher-hertel](https://linkedin.com/in/christopher-hertel)

---

## Symfony UX + Symfony AI: Taking Agent Interactions to the Next Level

<dl>
  <dt>Description</dt>
  <dd>What if we combined Symfony UX and Symfony AI to make our agents even more interactive?

Imagine interacting with an agent not only through text, but also by exploring locations on a map, visualizing data through interactive charts, or selecting exactly what you need with an autocomplete, all using components you make available to your agents.

And why stop there? We can also expose tools that let them act directly on the frontend and update the UI live, thanks to Turbo.

This is exactly what AG-UI, a new protocol for agent-to-frontend communication, is designed for. In this talk, we'll explore a small PHP implementation of it, and see what it takes to give our agents new ways to interact with users and with our applications themselves.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Matheo Daninos](https://connect.symfony.com/profile/mathdns)  
💻 on [![github](icon/github.svg) @WebMamba](https://github.com/WebMamba)  
✍ on [🌐 dev.to/webmamba](https://dev.to/webmamba)  <sup>[![rss](icon/rss.svg)](https://dev.to/feed/webmamba)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @webmamba.bsky.social](https://bsky.app/profile/webmamba.bsky.social)
· [![twitter](icon/twitter.svg) @matheodaninos](https://twitter.com/matheodaninos)
· [![linkedin](icon/linkedin.svg) @mathéo-d](https://linkedin.com/in/math%C3%A9o-d)

---

## Beyond Mocks

<dl>
  <dt>Description</dt>
  <dd>Symfony applications rarely live alone. They communicate with payment providers, identity services, messaging platforms, AI APIs, and countless external systems. But as these integrations grow, testing them becomes increasingly difficult: too many mocks, fragile fixtures, outdated assumptions, and tests that no longer reflect reality.

In this talk, we will explore modern approaches to testing HTTP integrations in Symfony applications. We will go beyond traditional mocking strategies and discover how to build tests that are both reliable and maintainable.

Using Symfony HttpClient as a foundation, we will look at practical techniques to improve the developer experience: from controlling HTTP responses, to recording and replaying real interactions, to validating that our application still respects external API contracts.

You will learn how to design a testing strategy that gives confidence without sacrificing speed, making your integrations easier to evolve and safer to maintain.</dd>
</dl>

[Slides](https://imenezzine.github.io/symfony-con-warsaw-2026/)  
~~Video~~  
~~Blog post~~

By [Imen Ezzine](https://connect.symfony.com/profile/imen-ezzine)  
💻 on [![github](icon/github.svg) @imenezzine](https://github.com/imenezzine)  
✍ on [🌐 imenezzine.github.io](https://imenezzine.github.io)  <sup>[![rss](icon/rss.svg)](https://imenezzine.github.io/rss.xml)</sup>  
💬 on [![twitter](icon/twitter.svg) @imenezzine1](https://twitter.com/imenezzine1)
· [![linkedin](icon/linkedin.svg) @imen-ezzine-…](https://linkedin.com/in/imen-ezzine-09938a45)

---

## Your Parents Holidayed in Yugoslavia

<dl>
  <dt>Description</dt>
  <dd>Your parents flew to Split for their summer holiday. They went to Yugoslavia. Yugoslavia doesn't exist any more, so why does your flight tracker insist they went to Croatia?

That's the question that made me realise my nice, simple CRUD database had quietly stopped being simple. Airlines merge and rebrand. Airports get renamed, and sometimes change country. Borders move. A row that just says "Croatia" rewrites my parents' holiday every time the world does.

This is the story of how a hobby flight logger outgrew its schema, and what event sourcing actually looks like once you build it instead of reading blog posts about it. No Kafka, no swarm of microservices: just Symfony, Doctrine, Messenger and a few hundred lines of PHP. We'll go through the parts that matter (append-only events, projections, and the temporal queries that let me ask "what country was this on the day of the flight?") using real, messy aviation data.

And if your parents holidayed in Yugoslavia too, you're in the right room.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Marek Matulka](https://connect.symfony.com/profile/super_marek)  
💻 on [![github](icon/github.svg) @mareg](https://github.com/mareg)  
_✍ blog not found_  
💬 on [![mastodon](icon/mastodon.svg) @marek@phpc.social](https://phpc.social/@marek)
· [![twitter](icon/twitter.svg) @super_marek](https://twitter.com/super_marek)
· [![linkedin](icon/linkedin.svg) @marek-matulka](https://linkedin.com/in/marek-matulka)

---

## Exposing Your API to AI Agents

<dl>
  <dt>Description</dt>
  <dd>Picture this: you connect an AI agent to your API and, all at once, dozens of "tools" pile into its context before it's done a thing. There has to be a better way, and there are a few, each with its own trade-offs.

After a quick refresher on the Model Context Protocol (MCP) and its PHP SDK (how an agent discovers your tools, understands what they expect, and calls them), we'll look at how to feed an agent its tools with Symfony and API Platform. From automatic strategies (generating tools from your API, or a Hydra gateway that lets the agent discover them by navigating hypermedia links) to the manual approach, declaring exactly the tools you want using PHP attributes.

We'll build them live and weigh them honestly: what saturates the context, what scales, what respects the constraints of REST/HATEOAS. You'll leave knowing which approach fits your own APIs.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Antoine Bluchet](https://connect.symfony.com/profile/soyuka)  
💻 on [![github](icon/github.svg) @soyuka](https://github.com/soyuka)  <sup>[💚](https://github.com/sponsors/soyuka)</sup>  
✍ on [🌐 soyuka.me](https://soyuka.me/)  <sup>[![rss](icon/rss.svg)](https://soyuka.me/index.xml)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @soyuka.me](https://bsky.app/profile/soyuka.me)
· [![mastodon](icon/mastodon.svg) @soyuka@phpc.social](https://phpc.social/@soyuka)
· [![twitter](icon/twitter.svg) @s0yuka](https://x.com/s0yuka)
· [![linkedin](icon/linkedin.svg) @soyuka](https://linkedin.com/in/soyuka)

---

## Giving AI Agents a Durable Memory

<dl>
  <dt>Description</dt>
  <dd>How can AI agents retain project context, working conventions and past decisions across sessions and tools? This talk shows how user- and project-level instructions can route agents through a small, indexed and versioned Markdown knowledge base, giving them the operational context they need without turning every prompt into a briefing document. We will also explore the limits of this approach, how it compares with native memory, and when heavier retrieval systems become a better fit.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Clément Bertillon](https://connect.symfony.com/profile/skigun)  
💻 on [![github](icon/github.svg) @skigun](https://github.com/skigun)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @BERTILLONClment](https://twitter.com/BERTILLONClment)
· [![linkedin](icon/linkedin.svg) @clément-bertillon-…](https://linkedin.com/in/cl%C3%A9ment-bertillon-10207894)

---

## final class Entity: Doctrine Mapping for Modern PHP

<dl>
  <dt>Description</dt>
  <dd>For fifteen years, Doctrine shaped the way we write entities, and not always for the better. Entities could not be final, because proxies had to extend them. Every field grew a getter and a setter. Domain concepts like money, addresses and identifiers ended up as strings and floats, because mapping anything richer was more trouble than it was worth.

None of that was a design decision. Those were workarounds for things PHP could not express yet.

It can now. Attributes, backed enums, property hooks, asymmetric visibility, native lazy objects, and an arbitrary-precision number object in core. Doctrine ORM 3.4 and DBAL 4.3 pick all of it up, and ORM 4 will be built on it.

We take one realistic entity, too many lines of accessors and primitives, and refactor it live on the slides: final classes, no setters, enums, typed identifiers, embedded value objects, custom DBAL types that register themselves. Same database schema at the end. No migration. Considerably less code.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Alexander M. Turek](https://connect.symfony.com/profile/derrabus)  
💻 on [![github](icon/github.svg) @derrabus](https://github.com/derrabus)  <sup>[💚](https://github.com/sponsors/derrabus)</sup>  
✍ on [🌐 medium.com/@derrabus](https://medium.com/@derrabus)  <sup>[![rss](icon/rss.svg)](https://medium.com/feed/@derrabus)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @derrabus.bsky.social](https://bsky.app/profile/derrabus.bsky.social)
· [![mastodon](icon/mastodon.svg) @derrabus@phpc.social](https://phpc.social/@derrabus)
· [![twitter](icon/twitter.svg) @derrabus](https://twitter.com/derrabus)
· [![threads](icon/threads.svg) @derrabus](https://www.threads.net/@derrabus)
· [![linkedin](icon/linkedin.svg) @amturek](https://linkedin.com/in/amturek)

---

## The Hidden Cost of `return new Response()`

<dl>
  <dt>Description</dt>
  <dd>Most Symfony applications buffer everything: Doctrine results, serialized objects, JSON, exports. They build the entire response, then send it. This works fine, until it doesn't: memory spikes, time-to-first-byte creeps up, and exports start dying in production.

LLMs make the problem impossible to ignore. When a model takes several seconds to answer, waiting for the return means staring at a spinner the whole time. Streaming isn't a back-end optimization anymore. It's the foundation modern user experience is built on.

In this talk, we tear down an assumption baked into most Symfony apps: that a response has to be fully built before it's sent. We'll rethink the data flow end to end: StreamedResponse, incremental JSON encoding with the JsonStreamer component, iterable Doctrine data sources, Server-Sent Events, and EventStreamResponse for real time.

You'll walk away knowing how to stream data as it's produced, power live interfaces, generate exports of several million rows, and keep memory flat, using tools already sitting in Symfony.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Mathias Arlaud](https://connect.symfony.com/profile/mtarld)  
💻 on [![github](icon/github.svg) @mtarld](https://github.com/mtarld)  <sup>[💚](https://github.com/sponsors/mtarld)</sup>  
✍ on [🌐 baksla.sh/blog](https://baksla.sh/blog)  
💬 on [![bluesky](icon/bluesky.svg) @mtarld.bsky.social](https://bsky.app/profile/mtarld.bsky.social)
· [![twitter](icon/twitter.svg) @matarld](https://twitter.com/matarld)
· [![linkedin](icon/linkedin.svg) matarld](https://www.linkedin.com/in/matarld)

---

## Form Component Through the Ages: History of (not so) Black Magic

<dl>
  <dt>Description</dt>
  <dd>`$form-&gt;handleRequest($request);`

One line, and somehow your data is hydrated, validated, CSRF-protected and ready to be persisted.

The Form component is probably the most powerful and the most misunderstood piece of Symfony. We use it every day, we copy-paste code like `'by_reference' =&gt; false` without really understanding what it does, and we cross our fingers when a data transformer doesn't fire. Black magic? Not quite.

Each "magic" behavior of the Form component has a story behind it: a problem it solved, a version it landed in, a trade-off someone had to make. Let's travel through 15 years of Symfony forms to understand why they work the way they do:

- The origins: How its start and how it gave birth to other components you use every day.

- Under the hood: Type inheritance vs. type extensions, type guessing, data transformers/mappers, form events, etc…

- Last year (7.4): Multi-step form, create your own (black magic) wizard.

- Today (8.2): Attribute-based forms, and why this brand-new syntax stands on the very same foundations.

Whether you love forms or avoid them, you'll leave this session reading the Form component like an open book rather than a spellbook.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Benjamin Georgeault](https://connect.symfony.com/profile/wedgesama)  
💻 on [![github](icon/github.svg) @WedgeSama](https://github.com/WedgeSama)
· [![gitlab](icon/gitlab.svg) @WedgeSama](https://gitlab.com/WedgeSama)  
_✍ blog not found_  
💬 on [![bluesky](icon/bluesky.svg) @wedgesama.bsky.social](https://bsky.app/profile/wedgesama.bsky.social)
· [![mastodon](icon/mastodon.svg) @wedgesama@mastodon.social](https://mastodon.social/@wedgesama)
· [![twitter](icon/twitter.svg) @WedgeSama](https://twitter.com/WedgeSama)
· [![linkedin](icon/linkedin.svg) @benjamin-georgeault-…](https://linkedin.com/in/benjamin-georgeault-67212172)

---

## PHP Wasn't Supposed to Do That

<dl>
  <dt>Description</dt>
  <dd>To build a website, we used PHP. To build a mobile application, we used something else. It was a simple rule. Almost self-evident.

Then one day, a request arrived, the kind every team eventually hears: "The website is great. Now we need a mobile app." From there the script is usually familiar: new technologies, new skills, new hires, new lines in a README nobody will read.

In this talk, I'll show how Symfony UX Native quietly bends what we thought was an immovable line between web and mobile. Through concrete demos, we'll see how a single Symfony codebase (Twig templates, Doctrine entities, Form types, all of it) turns into a real iOS and Android application via Hotwire Native. We'll write a bridge component live. We'll watch ux_is_native() reshape a single template for two surfaces. We'll talk honestly about architecture, developer experience, the limits of the approach, the use cases where it genuinely shines, and the questions every PHP developer asks the first time they see it work.

Because in the end, the surprising thing isn't that a mobile application can be built with Symfony. The surprising thing is that it's starting to feel perfectly logical, even though PHP wasn't supposed to do that.

(PS: No PHP developer was harmed, or forced to learn Swift, during the preparation of this talk.)</dd>
</dl>

~~Slides~~  
~~Video~~  
[Blog post](https://bludevon.com/symfonycon-warsaw-2026)  
[Code](https://github.com/feymo/symfonycon-remit-demo)  
[Live demo](https://sfcon26.bludevon.com/expenses)

By [Felix Eymonot](https://connect.symfony.com/profile/hyanda)  
💻 on [![github](icon/github.svg) @feymo](https://github.com/feymo)  
_✍ blog not found_  
💬 on [![bluesky](icon/bluesky.svg) @hyanda.bsky.social](https://bsky.app/profile/hyanda.bsky.social)
· [![linkedin](icon/linkedin.svg) @felix-eymonot](https://linkedin.com/in/felix-eymonot)

---

## From Serializer to JsonStreamer: the debrief

<dl>
  <dt>Description</dt>
  <dd>Reindexing millions of documents across 10 Elasticsearch indexes was taking hours, long enough that it only ran on weekends. With a growing number of custom Normalizers slowing things down, Symfony's Serializer wasn't cutting it anymore.

We built a proof of concept with Symfony's JsonStreamer to see if it was as fast as advertised.

This talk is an honest account of that journey: the challenges, what we learned, and how it could apply to your application as well.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Gary PEGEOT](https://connect.symfony.com/profile/gary-p)  
💻 on [![github](icon/github.svg) @GaryPEGEOT](https://github.com/GaryPEGEOT)  
_✍ blog not found_

---

## When vibes meets reality

<dl>
  <dt>Description</dt>
  <dd>Somewhere in some company, people who don't write code are prompting their way into production. They build tools in a browser, deploy them without a single line of traditional code, and hand them off to the rest of the business. Eventually, maintaining that platform becomes someone's job. It became mine. Low-code and vibe-coding platforms are gaining massive adoption, but they offer almost none of the engineering practices we take for granted. This talk is about what happens when you try to apply rigor, testing, and architecture to an ecosystem designed to ignore them.

Following one small function from concept to production, we'll uncover everything these platforms fail to provide, and how to fix it. Because while the tools change, the core problem-solving doesn't.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Stiven Llupa](https://connect.symfony.com/profile/sllupa)  
💻 on [![github](icon/github.svg) @llupa](https://github.com/llupa)  
✍ on [🌐 llupa.rocks](https://llupa.rocks/)  <sup>[![rss](icon/rss.svg)](https://llupa.rocks/feed/)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @llupa@phpc.social](https://phpc.social/@llupa)
· [![linkedin](icon/linkedin.svg) @stiven-llupa-…](https://linkedin.com/in/stiven-llupa-3a6367238)

---

## Green Is Not Done

<dl>
  <dt>Description</dt>
  <dd>When a coding agent writes code, your CI becomes its definition of done, and anything your checks cannot see can pass as finished. This talk introduces harness engineering for existing Symfony applications. It covers turning tools like PHPStan and deptrac into feedback an agent can act on, adding custom architecture rules for controllers, and enforcing them on legacy code with a baseline ratchet.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Anne-Julia Seitz](https://connect.symfony.com/profile/dazs)  
💻 on [![github](icon/github.svg) @dazz](https://github.com/dazz)  
✍ on [🌐 blog.dazzlog.de](https://blog.dazzlog.de)  <sup>[![rss](icon/rss.svg)](https://blog.dazzlog.de/index.xml)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @dazz@phpc.social](https://phpc.social/@dazz)
· [![twitter](icon/twitter.svg) @dazzlog](https://twitter.com/dazzlog)
· [![linkedin](icon/linkedin.svg) @anne-julia-seitz-…](https://linkedin.com/in/anne-julia-seitz-166654)

---

## Securing Your API: The OWASP API Top 10

<dl>
  <dt>Description</dt>
  <dd>APIs are the foundation of our AI applications today and need to be secure. From broken authorisation and authentication to injection attacks, the OWASP API Security Top 10 identifies the most critical security issues facing APIs today. In this talk, we'll walk through the items on the list and explore these security flaws and look at how to prevent them. By the end of this session, you'll have a clear understanding of the most critical API security risks and be equipped with the knowledge to build more secure APIs.</dd>
</dl>

[Slides](https://akrabat.com/wp-content/uploads/2026-11-26_SymfonyCon_OWASP-API-Top-10.pdf)  
~~Video~~  
~~Blog post~~

By [Rob Allen](https://connect.symfony.com/profile/akrabat)  
💻 on [![github](icon/github.svg) @akrabat](https://github.com/akrabat)  <sup>[💚](https://github.com/sponsors/akrabat)</sup>  
✍ on [🌐 akrabat.com](https://akrabat.com/)  <sup>[![rss](icon/rss.svg)](https://akrabat.com/feed/)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @rob@akrabat.com](https://social.akrabat.com/@rob)
· [![bluesky](icon/bluesky.svg) @akrabat.com](https://bsky.app/profile/akrabat.com)
· [![twitter](icon/twitter.svg) @akrabat](https://twitter.com/akrabat)
· [![linkedin](icon/linkedin.svg) @akrabat](https://linkedin.com/in/akrabat)

---

## Real Browsers, Real Kernel: Playwright Testing in Symfony

<dl>
  <dt>Description</dt>
  <dd>A Symfony application comes to life in the browser: navigation, validation, dynamic components, and JavaScript interactions. A DOM emulator can reproduce the HTML, but not the behavior of a real browser. Yet browser tests often run outside Symfony, against a separate application server and lifecycle, with little access to application state.

Playwright drives real browsers with semantic locators, automatic waiting, and web-first assertions. PlaywrightPHP brings this API to PHP: navigate, fill forms, drag and drop, execute JavaScript, inspect the network and console, record traces, or generate PHP code. The Playwright Symfony bundle brings that journey into Symfony's test environment. One PHPUnit test drags a card in a real Live Component, waits for the asynchronous update, then asserts the DOM, dispatched events, and database state.

The browser sends a real request. The bundle turns it into a Symfony Request, lets the test kernel handle it in the same PHP process as the test, and returns the Symfony Response to the page. No separate web server is required. The same test sees both sides: network, console, and trace in the browser; Request, Response, profiler, logs, and database state in Symfony.

Through one application and three live demonstrations, you will see how this model tests payment flows, Live Components, and design systems, protects critical user journeys, and catches visual regressions.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Simon André](https://connect.symfony.com/profile/simonandre)  
💻 on [![github](icon/github.svg) @smnandre](https://github.com/smnandre)  <sup>[💚](https://github.com/sponsors/smnandre)</sup>  
✍ on [🌐 smnandre.dev/blog](https://smnandre.dev/blog/)  
💬 on [![bluesky](icon/bluesky.svg) @smnandre.dev](https://bsky.app/profile/smnandre.dev)
· [![twitter](icon/twitter.svg) @simonandre](https://twitter.com/simonandre)
· [![linkedin](icon/linkedin.svg) @smnandre](https://linkedin.com/in/smnandre)

---

## Composer & Packagist Supply Chain Security: Report from the trenches

<dl>
  <dt>Description</dt>
  <dd>At SymfonyCon 2025 we asked “Package Manager Security in 2025: What’s Next?” and outlined our long term supply chain security strategy. Reality caught up with us fast!

The PHP ecosystem has been hit by the same class of supply chain attacks that has repeatedly hit npm and PyPI: taken-over GitHub accounts and stolen access tokens used to publish malicious tags on packages the attackers had no legitimate access to. This talk walks through what we changed across Composer and Packagist in response, and what is still in flight.

Our response came in two phases. First, detection: the Aikido malware feed integrated into Packagist.org, a public transparency log that helped analyze attacks. Then the prevention work: Composer 2.10's unified dependency policy framework covering malware, advisories, and abandoned packages, stable version immutability on Packagist.org so tagged releases can no longer be silently rewritten. We’ll look at more recent changes like Composer 2.11’s minimum-release-age configuration, maintainer security posture and MFA status publication on Packagist, and the new organization level ownership and controls over open-source packages on Packagist.org.

We’ll provide concrete tips and best practices for keeping your own supply chain secure, and give an outlook into what we have planned for 2027.</dd>
</dl>

[Slides](https://naderman.de/slippy/slides/2026-11-26-SymfonyCon-2026-Warsaw-Composer-and-Packagist-Supply-Chain-Security-Report-from-the-trenches.pdf)  
~~Video~~  
~~Blog post~~

By [Jordi Boggiano](https://connect.symfony.com/profile/seldaek)  
💻 on [![github](icon/github.svg) @Seldaek](https://github.com/Seldaek)  <sup>[💚](https://github.com/sponsors/Seldaek)</sup>  
✍ on [🌐 seld.be](https://seld.be)  <sup>[![rss](icon/rss.svg)](https://seld.be/feed.atom)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @seld.be](https://bsky.app/profile/seld.be)
· [![mastodon](icon/mastodon.svg) @seldaek@mastodon.social](https://mastodon.social/@seldaek)
· [![twitter](icon/twitter.svg) @seldaek](https://twitter.com/seldaek)
· [![linkedin](icon/linkedin.svg) @seldaek](https://linkedin.com/in/seldaek)

By [Nils Adermann](https://connect.symfony.com/profile/naderman)  
💻 on [![github](icon/github.svg) @naderman](https://github.com/naderman)  <sup>[💚](https://github.com/sponsors/naderman)</sup>  
✍ on [🌐 blog.packagist.com](https://blog.packagist.com/)  <sup>[![rss](icon/rss.svg)](https://blog.packagist.com/feed/)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @naderman.de](https://bsky.app/profile/naderman.de)
· [![mastodon](icon/mastodon.svg) @naderman@phpc.social](https://phpc.social/@naderman)
· [![twitter](icon/twitter.svg) @naderman](https://twitter.com/naderman)
· [![linkedin](icon/linkedin.svg) @nilsadermann](https://linkedin.com/in/nilsadermann)

---

## Ten Easy Steps Towards a More Inclusive Workplace

<dl>
  <dt>Description</dt>
  <dd>Diversity is a big topic and yet a lot of companies I encounter are hardly diverse. What could be the cause, and how can we change this?

Are you aware of how your daily common language may exclude certain people or groups? Could it be that implicit bias and our own behaviour may impact our chances of improving diversity? Slightly changing your language and behaviour and being aware of potential pitfalls may make your workplace more inclusive and welcoming. In this talk we'll discuss 10 situations in which we can improve our daily (work) life to be more inclusive. It includes practical examples that can be directly applied to your team or company.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Stefan Koopmanschap](https://connect.symfony.com/profile/skoop)  
💻 on [![github](icon/github.svg) @skoop](https://github.com/skoop)  
✍ on [🌐 skoop.dev](https://skoop.dev/)  <sup>[![rss](icon/rss.svg)](https://skoop.dev/feed/)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @Skoop@phpc.social](https://phpc.social/@skoop)
· [![twitter](icon/twitter.svg) @skoopnl](https://twitter.com/skoopnl)
· [![linkedin](icon/linkedin.svg) @stefankoopmanschap](https://linkedin.com/in/stefankoopmanschap)

---

## Mercure 1.0: Real-Time Symfony, Eight Years On

<dl>
  <dt>Description</dt>
  <dd>Eight years ago, Mercure was born: an open-source protocol and Go server designed to bring the power of real-time to any web architecture, especially ecosystems like PHP that don't natively support persistent connections.

Symfony quickly adopted Mercure as its official solution for real-time features. Today, Mercure has become an essential standard, powering hundreds of production projects, from startups to enterprise accounts. Fully integrated into Symfony (via Symfony UX) as well as API Platform, and bundled by default in FrankenPHP, Mercure radically simplifies the developer experience. Whether you are building collaborative editors (Google Docs style), syncing instant dashboards, notifying your users when a background task finishes, or, more recently, streaming LLM tokens and tracking AI agent progress, Mercure stands out as the ideal solution.

Today, we are releasing Mercure 1.0 along with a brand-new Symfony integration! This protocol overhaul leverages the latest web standards, "URL Pattern" and "OAuth Rich Authorization Requests," to make developing AI and real-time features even simpler, more powerful, and more secure. This new version also brings optional compatibility with OAuth and OIDC servers.

Join me during this talk to discover all the new features in this latest release of Symfony Mercure, and make your apps more interactive than ever!</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
💻 on [![github](icon/github.svg) @dunglas](https://github.com/dunglas)  <sup>[💚](https://github.com/sponsors/dunglas)</sup>  
✍ on [🌐 dunglas.dev](https://dunglas.dev/)  <sup>[![rss](icon/rss.svg)](https://dunglas.dev/feed/)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @dunglas@mastodon.social](https://mastodon.social/@dunglas)
· [![bluesky](icon/bluesky.svg) @dunglas.dev](https://bsky.app/profile/dunglas.dev)
· [![twitter](icon/twitter.svg) @dunglas](https://twitter.com/dunglas)
· [![linkedin](icon/linkedin.svg) @dunglas](https://www.linkedin.com/in/dunglas)

---

## Developing the Developer: A Year of Journaling with AI

<dl>
  <dt>Description</dt>
  <dd>In order to be able to show growth and improve myself as a developer and coworker, I need a system. Previous attempts at journaling failed, but with the rise of LLMs and AI, there is a new option.

In this talk, I explain my journaling system, how it works for me, and how you can use the open sourced template to make it your own.

This is for developers: it is not an app, nor a SaaS. It's something you can use within your own IDE, with your own workflow, and your own modifications.

I've been using this system for a year now. It has grown, like I have. I will share some of the pitfalls and improvements I've gone through so far, which includes better text writing, use of MCPs to pull data from other systems, and more.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Timo Bakx](https://connect.symfony.com/profile/timobakx)  
💻 on [![github](icon/github.svg) @TimoBakx](https://github.com/TimoBakx)  <sup>[💚](https://github.com/sponsors/TimoBakx)</sup>  
✍ on [🌐 timobakx.dev](https://timobakx.dev/)  <sup>[![rss](icon/rss.svg)](https://timobakx.dev/feed.xml)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @timobakx@phpc.social](https://phpc.social/@timobakx)
· [![bluesky](icon/bluesky.svg) @timobakx.bsky.social](https://bsky.app/profile/timobakx.bsky.social)
· [![twitter](icon/twitter.svg) @TimoBakx](https://twitter.com/TimoBakx)
· [![linkedin](icon/linkedin.svg) @timobakx](https://linkedin.com/in/timobakx)

---

## Works on my machine. The agent said so.

<dl>
  <dt>Description</dt>
  <dd>What it takes to run coding agents in production across your team.

Every team has a coding agent that ships great code on someone's laptop, and that stops working once the whole team relies on it. Drawing on what we learned running (and building) a software factory at Upsun, we'll dig into a few problems: sandboxing untrusted code, keeping non-deterministic models on a deterministic track, giving agents shared context instead of per-developer prompt files, and evaluating agent work beyond "the tests passed.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Jonas Kröger](https://connect.symfony.com/profile/devicezero)  
💻 on [![github](icon/github.svg) @devicezero](https://github.com/devicezero)  
✍ on [🌐 upsun.com/blog/author/jonas-krger](https://upsun.com/blog/author/jonas-krger/)  
💬 on [![twitter](icon/twitter.svg) @devicezero](https://twitter.com/devicezero)
· [![linkedin](icon/linkedin.svg) @jonaskroeger](https://linkedin.com/in/jonaskroeger)

---

## Fixing PHP2Shell

<dl>
  <dt>Description</dt>
  <dd>This talk reflects on the PHP2Shell vulnerability, telling the full story of what happened and discussing its impact and why it gained so much attention.

We will cover the whole process, from what led to its discovery to testing and validation to remediation and how the PHP team coordinated and rolled out the fix.

Discussion will include how agentic security research combined with human expertise led researchers to the exploit and how LLMs are changing the landscape of security going forward.

We will reflect on lessons learned, share advice for other projects and the wider PHP ecosystem, and provide practical suggestions for organizations and projects.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Volker Dusch](https://connect.symfony.com/profile/edorian)  
💻 on [![github](icon/github.svg) @edorian](https://github.com/edorian)  
✍ on [🌐 tideways.com/profiler/blog](https://tideways.com/profiler/blog)  <sup>[![rss](icon/rss.svg)](https://tideways.com/feed)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @edorian.bsky.social](https://bsky.app/profile/edorian.bsky.social)
· [![mastodon](icon/mastodon.svg) @edorian@phpc.social](https://phpc.social/@edorian)

---

## Protect Your Data with Queryable Encryption

<dl>
  <dt>Description</dt>
  <dd>Storing your users’ email addresses, dates of birth, or social security numbers in plain text poses a major risk in the event of a database leak. With robust application-side encryption, you can make the data unreadable by the database. But then it becomes impossible to do a WHERE email = :value. How can you secure your sensitive data without sacrificing essential business functionality?

We will see how to implement client-side field encryption with Doctrine and a key management system. The algorithms to use, key management and rotation: learn how to turn your database into a safe without losing your ability to query it.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Jérôme Tamarelle](https://connect.symfony.com/profile/gromnan)  
💻 on [![github](icon/github.svg) @GromNaN](https://github.com/GromNaN)  
✍ on [🌐 dev.to/gromnan](https://dev.to/gromnan)  <sup>[![rss](icon/rss.svg)](https://dev.to/feed/gromnan)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @jerome.tamarelle.net](https://bsky.app/profile/jerome.tamarelle.net)
· [![mastodon](icon/mastodon.svg) @gromnan@phpc.social](https://phpc.social/@gromnan)
· [![twitter](icon/twitter.svg) @GromNaN](https://twitter.com/GromNaN)
· [![linkedin](icon/linkedin.svg) @jerometamarelle](https://linkedin.com/in/jerometamarelle)

---

## If You Build It, They Won't Come

<dl>
  <dt>Description</dt>
  <dd>Your code was never the problem. The problem is nobody wanted the thing you built. Learn how to find out who actually wants a feature before you build it, and why the answers double as the pitch you'll need later to get people to use it. Four questions, asked before you write a line. No personas. No funnels. Just the research that tells you what deserves to exist.

At Upsun, I don't decide what gets built. I'm the one who has to explain it afterwards, which makes me the first to find out when nobody did the thinking. So we'll walk the four questions you can ask before anything starts, what a bad answer sounds like, and how to kill an idea (including your own) with evidence instead of taste. Then the turn: those same four answers, relabelled, are your entire positioning. Building got cheap. Deciding didn't. You'll leave with a framework that serves as a build decision and a positioning doc, because they were never two documents.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Greg Qualls](https://connect.symfony.com/profile/gregqualls)  
💻 on [![github](icon/github.svg) @gregqualls](https://github.com/gregqualls)  
✍ on [🌐 gregqualls.com/writing](https://gregqualls.com/writing)  <sup>[![rss](icon/rss.svg)](https://gregqualls.com/rss.xml)</sup>  
💬 on [![bluesky](icon/bluesky.svg) @gregqualls.com](https://bsky.app/profile/gregqualls.com)
· [![twitter](icon/twitter.svg) @gregqualls](https://twitter.com/gregqualls)
· [![linkedin](icon/linkedin.svg) @gregqualls](https://linkedin.com/in/gregqualls)

---

## Headless vs Monolith: The Final Battle

<dl>
  <dt>Description</dt>
  <dd>Should your next Symfony application be headless, or should it remain a monolith?

In e-commerce, this is often one of the first architectural questions teams need to answer. Clients want modern, dynamic, responsive user experiences. Developers want maintainable systems. Businesses want fast delivery, good SEO, reasonable costs, and the ability to evolve the product over time.

For a long time, the discussion has often been presented as a binary choice: either we build a traditional server-rendered application, or we move to a fully headless architecture with a separate frontend application. Both options have strong arguments. Both also come with hidden costs.

In this talk, we will compare both approaches from a practical Symfony perspective. We will look at SEO, performance, responsiveness, frontend flexibility, team workflow, deployment complexity, maintaining multiple repositories, and the long-term cost of ownership.

But the main goal of this talk is not to declare a single winner.

Instead, we will ask a more useful question: do Symfony teams still have to choose between a classic monolith and a fully headless architecture?

Thanks to Symfony UX, Live Components, Twig Components, and the ability to use React or Vue components directly inside Twig, Symfony gives us a powerful middle ground. We can keep the productivity, simplicity, and SEO advantages of a traditional Symfony application, while progressively introducing dynamic, interactive frontend experiences exactly where they bring real value.

I will share how we successfully implemented this approach in Sylius, what we learned from the e-commerce world, and how these lessons can help Symfony teams build modern, dynamic applications without immediately turning every project into a fully headless architecture.

Attendees will leave with a practical framework for deciding when to stay with a monolith, when to go headless, and when a hybrid Symfony architecture can give them the best of both worlds.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Gracjan Józefczyk](https://connect.symfony.com/profile/gracjanjozefczyk)  
💻 on [![github](icon/github.svg) @GracjanJozefczyk](https://github.com/GracjanJozefczyk)  
_✍ blog not found_  
💬 on [![linkedin](icon/linkedin.svg) @gracjan-jozefczyk](https://linkedin.com/in/gracjan-jozefczyk)

---

## Symfony Mate: From Hallway Idea to Daily Driver

<dl>
  <dt>Description</dt>
  <dd>Mate started as a hallway conversation at SymfonyCon Amsterdam 2025. A few weeks later it shipped in Symfony AI 0.1, and in April it had its first public outing at SymfonyLive Berlin. Now it comes back to the conference where it began.

You'll learn what Mate is, the principles behind it, and how it gives coding agents real insight into a running Symfony application. Then we'll look at the two biggest changes since Berlin. Mate dropped its MCP server for a native CLI, after we measured how agents actually discover and use tools. And Agent Skills now ship with the packages they belong to, so the people who build a bundle can also teach agents how to use it.

There will be a live demo, and I'll be honest about the wrong turns along the way.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Johannes Wachter](https://connect.symfony.com/profile/wjohannes)  
💻 on [![github](icon/github.svg) @wachterjohannes](https://github.com/wachterjohannes)  
✍ on [🌐 johanneswachter.dev/blog](https://johanneswachter.dev/blog/)  <sup>[![rss](icon/rss.svg)](https://johanneswachter.dev/blog/rss.xml)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @wachterjohannes@phpc.social](https://phpc.social/@wachterjohannes)
· [![twitter](icon/twitter.svg) @wachterjohannes](https://twitter.com/wachterjohannes)
· [![linkedin](icon/linkedin.svg) @wachterjohannes](https://linkedin.com/in/wachterjohannes)

---

## The building blocks of an agentic software factory

<dl>
  <dt>Description</dt>
  <dd>An agentic software factory connects the work of deciding what to build, implementing it, checking it, and running it. The coding agent is just a starting point. Around it, the factory expands in four directions. Intent and specifications give the work a purpose and clear constraints. Validation and verification establish whether the result works and solves the intended problem. Delivery and operations keep it running. Strategy uses evidence to decide what deserves attention next.

We will explore the building blocks that connect these responsibilities into a working system. Shared context, explicit handoffs, automated checks, and human decisions let each workflow use what the others learn. You'll leave with a conceptual map for building a real system around the coding agents your Symfony team already uses.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Elie Auvray](https://connect.symfony.com/profile/elieauvray)  
💻 on [![github](icon/github.svg) @elieauvray](https://github.com/elieauvray)  
_✍ blog not found_

---

## Calling the Symfony Container from Legacy Code

<dl>
  <dt>Description</dt>
  <dd>Migrating legacy PHP to Symfony stalls on shared resources. The database, the session, the mailer all exist twice, and duplicating that code is the cheap answer nobody wants to maintain. Calling into Symfony from outside the framework looks impossible, but it isn't. This talk shows how to boot the container from legacy code and get full dependency injection on both sides of the migration, with the trade-offs and the sharp edges spelled out. Assumes familiarity with Symfony's DI configuration.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Rachelle Scheijen](https://connect.symfony.com/profile/youconix)  
💻 on [![github](icon/github.svg) @rachelle-scheijen](https://github.com/rachelle-scheijen)
· [![gitlab](icon/gitlab.svg) @youconix](https://gitlab.com/youconix)  
_✍ blog not found_  
💬 on [![linkedin](icon/linkedin.svg) @rachelle-scheijen](https://linkedin.com/in/rachelle-scheijen)

---

## Beyond HTML: Colocating Assets in Twig Components

<dl>
  <dt>Description</dt>
  <dd>Twig Components have made it easier than ever to build reusable UI components in Symfony. But while templates are often nicely organized, their CSS, JavaScript, images, and other assets usually end up somewhere else.

What if every component could own everything it needs?

In this talk, we'll explore an approach that keeps templates and their assets together, making components easier to understand, reuse, and maintain. While this architecture fits naturally with Atomic Design, it works equally well for any component-based Symfony application.

To demonstrate the concept, I'll introduce AtomicAssetsBundle, an open-source bundle that automatically discovers and bundles assets alongside your Twig components. Along the way, we'll discuss the challenges of component-scoped assets, how this approach integrates into existing Symfony projects, and the trade-offs of keeping everything in one place.

Whether you're building a design system or simply want a cleaner way to organize your frontend code, you'll leave with practical ideas for creating truly self-contained Symfony components.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Matthias Krauser](https://connect.symfony.com/profile/mkrauser)  
💻 on [![github](icon/github.svg) @mkrauser](https://github.com/mkrauser)  
_✍ blog not found_  
💬 on [![twitter](icon/twitter.svg) @mat_krauser](https://twitter.com/mat_krauser)

---

## From 30% to 100%: Fifteen Years of Hearing Loss and Tech

<dl>
  <dt>Description</dt>
  <dd>I'm Field CTO at Upsun, with profound hearing loss since birth. My primary job is to help our teams collaborate better in order to solve our customers’ problems. An ironic position given my disability.

In this personal presentation, I share six technological advancements that transformed my career over 15 years: hearing aids, subtitles, text-based communication, Bluetooth connectivity, live captions, and smart glasses.

These technologies increased my comprehension from 30% to 90-100% in meetings, enabling me to thrive in a fully remote company for 11 years. But here's the challenge: we have the technology, yet accessibility is rarely the default.

I'll demonstrate how accessibility features benefit everyone (subtitles in noisy environments, text communication for time zones, searchable captions), and provide three concrete actions developers can take tomorrow to make technology more inclusive. Every developer choice either includes or excludes 15% of users. Choose inclusion.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Florian Margaine](https://connect.symfony.com/profile/ralt)  
💻 on [![github](icon/github.svg) @ralt](https://github.com/ralt)  
✍ on [🌐 upsun.com/blog/author/florian-margaine](https://upsun.com/blog/author/florian-margaine/)  
💬 on [![linkedin](icon/linkedin.svg) @florian-margaine-…](https://linkedin.com/in/florian-margaine-43971136)

---

## From 14s to 1.8s: A Symfony Cold Start Autopsy

<dl>
  <dt>Description</dt>
  <dd>On Cloud Run, our backend answered its first request in 14 seconds. Almost all of that time went to one place nobody on the team would have guessed, and the profiler alone never found it.

This is the full hunt: the tooling that finally showed us the truth, the framework internals we had to read to understand what we were seeing, and the obvious optimizations that quietly made cold starts worse before anything got better. Image size, autoloading, the compiled container, cache warmup, and the way they interact.

We finished at 1.8 seconds. You'll leave with a method for diagnosing your own cold starts, not a list of tricks to copy.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Rémi JANOT](https://connect.symfony.com/profile/rjanot)  
💻 on [![github](icon/github.svg) @rjanot](https://github.com/rjanot)  
_✍ blog not found_  
💬 on [![linkedin](icon/linkedin.svg) @remi-janot](https://fr.linkedin.com/pub/remi-janot/5/6b8/36b)

---

## You Are (Not) a Machine

<dl>
  <dt>Description</dt>
  <dd>In this talk we compare the Symfony HttpKernel and its heavy usage of EventListeners to your own behavior and the "legacy code" event listeners that you developed early in your life, but that might sabotage you today.

This is a mostly non-technical talk, rather centered around mental health.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Peter Dietrich](https://connect.symfony.com/profile/xosofox)  
💻 on [![github](icon/github.svg) @xosofox](https://github.com/xosofox)  
✍ on [🌐 xosofox.de/blog](https://www.xosofox.de/blog/)  
💬 on [![twitter](icon/twitter.svg) @xosofox](https://twitter.com/xosofox)
· [![linkedin](icon/linkedin.svg) @pdietrich](https://linkedin.com/in/pdietrich)

---

## Zero to production on SymfonyCloud, live

<dl>
  <dt>Description</dt>
  <dd>You have an idea for a Symfony app. How long until it is in production, safe and observable?

Live on stage, we create a small app and deploy it to SymfonyCloud, the official cloud for Symfony, without writing a single build or deploy script.

Then you use it from your phone.

Next, we add a slow feature on a copy of production, your votes included, find the bottleneck with Blackfire, move the work to a background worker, and ship it safely.

No prior Symfony experience needed.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Vincent Robert](https://connect.symfony.com/profile/vrobert78)  
💻 on [![github](icon/github.svg) @vrobert78](https://github.com/vrobert78)  
_✍ blog not found_

---

## PHP’s Type System Dissected

<dl>
  <dt>Description</dt>
  <dd>PHP has a type system, and it has quietly become one of the more interesting ones among dynamic languages. It grew by accretion over two decades: scalar types, nullable types, union and intersection types, never, true, and a notion of subtyping built on Liskov's Substitution Principle.

This talk starts from the formal question of what a type system actually is, then uses that vocabulary to explain PHP's. Why LSP is the rule that governs subtyping, what variance means for the signatures you write every day, and where PHP's system is genuinely sound as opposed to pragmatically compromised.

We finish by looking forward: what PHP's type system could still gain, what each addition would cost, and what is realistically on the table. And there's a practical reason to care right now. Types are the clearest signal a codebase gives a model about what it may do, so knowing what they actually guarantee is worth more than it was two years ago.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Gina Banyard](https://connect.symfony.com/profile/girgias)  
💻 on [![github](icon/github.svg) @Girgias](https://github.com/Girgias)  <sup>[💚](https://github.com/sponsors/Girgias)</sup>  
✍ on [🌐 gpb.moe/blog](https://gpb.moe/blog/)  <sup>[![rss](icon/rss.svg)](https://gpb.moe/blog/atom.xml)</sup>  
💬 on [![mastodon](icon/mastodon.svg) @Girgias@phpc.social](https://phpc.social/@Girgias)
· [![twitter](icon/twitter.svg) @Girgias](https://twitter.com/Girgias)
· [![linkedin](icon/linkedin.svg) @girgias](https://linkedin.com/in/girgias)

---

## Not All Messenger Transports Are Equal

<dl>
  <dt>Description</dt>
  <dd>Let’s compare different transports for Symfony Messenger and examine their business impact. Symfony offers multiple high-quality integrations, but teams often lack the practical know-how to decide which queue system is best for their application.

I will provide data-driven insights to guide that choice, covering retry strategies implementation, idempotency (exactly-once vs at-least-once systems), failure handling, operational hazards and hardware requirements, and how they impact your choice.

Rather than treating the Messenger component as a uniform high-level abstraction, I will look at where differences between backends matter in practice: how messages are acknowledged, how workers behave under high load or failure, how efficient different systems are budget-wise, and which trade-offs emerge when you optimize for throughput, reliability, or simplicity.

The goal is to give you a clear, technically grounded way to evaluate queue transports in Symfony-based systems and to avoid assumptions that do not hold once the system reaches production.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Oskar Barcz](https://connect.symfony.com/profile/oskarbarcz)  
💻 on [![github](icon/github.svg) @oskarbarcz](https://github.com/oskarbarcz)  
✍ on [🌐 blog.barcz.me](https://blog.barcz.me/)  
💬 on [![linkedin](icon/linkedin.svg) @oskarbarcz](https://linkedin.com/in/oskarbarcz)

---

## Nobody typed this: reviewing agentic code

<dl>
  <dt>Description</dt>
  <dd>Your agents open pull requests faster than your team can check them. Approving them is not a review policy.

This talk is about the review process that matches modern realities. Who reviews agent-written code, and what they should actually look at. How much review a change deserves, and when this decision is taken. Who stays accountable when the code is fully generated. And how to keep a record of why a change was made, so the person who signed off can explain it six months later.

Drawn from our discovery interviews with multiple PHP teams, from Symfony agencies to a 2,000-engineer group, and from how we run review in Upsun ourselves. You leave with a review guidelines that you can start applying in your next development cycle.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Kateryna Dvornichenko](https://connect.symfony.com/profile/kateryna_dvornochenko)  
✍ on [🌐 upsun.com/blog/author/kateryna-dvornichenko](https://upsun.com/blog/author/kateryna-dvornichenko/)  
💬 on [![linkedin](icon/linkedin.svg) @katerynadvornichenko](https://linkedin.com/in/katerynadvornichenko)

---

## The PHP Runtime I Want to See

<dl>
  <dt>Description</dt>
  <dd>For twenty years PHP has worked the same way: one request, one process, and then everything is forgotten. That model is why PHP is simple, robust and easy to deploy. It is not the problem.

The problem is what it cannot do. Nothing can wait, watch, or remember between requests. So we built cron jobs, supervisors, TTLs and Redis keys around the runtime to make up for one missing capability.

This talk is about adding that capability without giving up the model. I've spent the last months adding background workers to FrankenPHP: long-running PHP outside of HTTP, publishing data your requests read directly, with no serialization, no TTL and no restart. Your controllers don't change. Your requests still forget everything. Something beside them now remembers.

I'll show what that makes possible, what each step really costs, and why the runtimes that ask you to rewrite your code will stay niche while this one becomes normal.</dd>
</dl>

~~Slides~~  
~~Video~~  
~~Blog post~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
💻 on [![github](icon/github.svg) @nicolas-grekas](https://github.com/nicolas-grekas)  <sup>[💚](https://github.com/sponsors/nicolas-grekas)</sup>  
✍ on [🌐 medium.com/@nicolas.grekas](https://medium.com/@nicolas.grekas)  <sup>[![rss](icon/rss.svg)](https://medium.com/feed/@nicolas.grekas)</sup>  
💬 on [![twitter](icon/twitter.svg) @nicolasgrekas](https://twitter.com/nicolasgrekas)
· [![bluesky](icon/bluesky.svg) @nicolasgrekas.bsky.social](https://bsky.app/profile/nicolasgrekas.bsky.social)
· [![mastodon](icon/mastodon.svg) @nicolasgrekas@phpc.social](https://phpc.social/@nicolasgrekas)
· [![linkedin](icon/linkedin.svg) @nicolasgrekas](https://linkedin.com/in/nicolasgrekas)
