# awesome-eve [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for [eve](https://vercel.com/eve) — Vercel's filesystem-first framework for building, running, and scaling durable AI agents.

**🤖🤖 GLM 5.2 free for eve agents through August 27 via Blackbox on AI Gateway**

eve treats each agent as a directory of files: Markdown for instructions and skills, TypeScript for tools, with durable execution, sandboxed compute, human-in-the-loop approvals, subagents, and evals built in. Think "Next.js for agents." Released June 17, 2026 (Apache-2.0).

*Not affiliated with Vercel. Community-maintained. Contributions welcome — see [Contributing](#contributing).*

## Contents

- [Official](#official)
- [The Agent Stack](#the-agent-stack)
- [Templates](#templates)
- [Tutorials & Guides](#tutorials--guides)
- [Articles & Coverage](#articles--coverage)
- [Videos](#videos)
- [Community](#community)
- [Showcase](#showcase)
- [Contributing](#contributing)

## Official

- [eve on GitHub](https://github.com/vercel/eve) — Source code, issues, and the canonical README.
- [eve.dev](https://eve.dev) — Official site.
- [Documentation](https://eve.dev/docs/introduction) — Getting started and concepts.
- [First Agent Tutorial](https://eve.dev/docs/tutorial/first-agent) — Build a complete agent end-to-end.
- [Introducing eve (blog)](https://vercel.com/blog/introducing-eve) — The official launch announcement.
- [eve landing page](https://vercel.com/eve) — Overview of features and primitives.
- [npm package](https://www.npmjs.com/package/eve) — `npx eve@latest init my-agent`.
- [GitHub Discussions](https://github.com/vercel/eve/discussions) — Ask questions and share what you built.

## The Agent Stack

Vercel primitives eve builds on, useful when taking agents to production.

- [The Agent Stack (blog)](https://vercel.com/blog/agent-stack) — Overview of Vercel's agent infrastructure.
- [Vercel Connect](https://vercel.com/connect) — Scoped, short-lived credentials so agents access systems without long-lived secrets.
- [Vercel Sandbox](https://vercel.com/docs/sandbox) — Isolated compute for running untrusted or agent-generated code.
- [Vercel Passport](https://vercel.com/kb/vercel-passport) — Put internal apps and agents behind your identity provider (Okta, Entra).
- [Vercel Agent](https://vercel.com/docs/agent) — AI investigations and automated installs for your projects.
- [Chat SDK](https://chat-sdk.dev/) — Ship agents into the apps where your users already are.

## Templates

Official starting points from `vercel-labs`.

- [eve Content Agent Template](https://github.com/vercel-labs/eve-content-agent-template) — Slack content assistant that drafts posts and publishes to Notion. ([guide](https://vercel.com/kb/guide/eve-content-agent))
- [eve Chat Template](https://github.com/vercel-labs/eve-chat-template) — Web chat with an eve agent, Better Auth sign-in, Neon-backed history.
- [eve Slack Agent](https://vercel.com/templates/eve/eve-slack-agent) — Slack agent you can @mention.
- [Personal Agent Template](https://github.com/vercel-labs/personal-agent-template) — Durable personal agent: web chat, Slack, Linear, long-term memory (Eve + Nuxt + Better Auth + Connect).
- [Knowledge Agent Template](https://github.com/vercel-labs/knowledge-agent-template) — File-system knowledge agent using grep/find/cat — no embeddings, no vector DB.
- [Eve software Factory Template](https://github.com/vercel-labs/eve-software-factory-template) - Meet Foreman, an eve Software Factory.
- 

## Tutorials & Guides

- [Build a Slack AI Agent with eve and Firecrawl](https://www.firecrawl.dev/blog/build-slack-ai-agent-eve) — Scaffold, add typed tools, deploy to Slack.
- [Give Your eve Agent a Memory (NAMS + Neo4j)](https://lyonwj.com/blog/agent-memory-with-eve-and-nams) — Persist conversations as a context graph.
- [What we've built with eve so far — Roboto Studio](https://robotostudio.com/blog/building-agents-on-eve) — A real content-ops agent and lessons learned.
- [Building Reviewable Mobile QA Agents with eve — Callstack](https://www.callstack.com/blog/building-reviewable-mobile-qa-agents-with-vercel-eve) — eve inside a CI workflow.
- [How to Build Your First AI Agent with eve](https://pasqualepillitteri.it/en/news/5680/how-to-build-ai-agent-vercel-eve-guide) — Two files to start, then tools, skills, subagents, connections.
- [How to Build and Deploy Anything with AI Agents — Developers Digest](https://www.developersdigest.tech/tutorials/eWs50bhFvMY) — Step-by-step eve walkthrough.
- [Should You Build Your Next Agent on eve?](https://medium.com/@hamzamlwh/should-you-build-your-next-agent-on-vercels-eve-1c5bee591fbf) — An honest review of strengths and trade-offs.

## Articles & Coverage

- [Vercel launches eve — The New Stack](https://thenewstack.io/vercel-launches-eve-an-open-source-framework-that-treats-agents-as-directories/)
- [Vercel Releases Eve — MarkTechPost](https://www.marktechpost.com/2026/06/17/vercel-releases-eve/)
- [Vercel Introduces Eve — InfoQ](https://www.infoq.com/news/2026/06/vercel-eve-agents/)
- [Vercel debuts eve, fixes shadow AI with Passport — DevClass](https://www.devclass.com/devops/2026/06/23/vercel-debuts-eve-open-source-agent-framework-tries-to-fix-shadow-ai-with-passport/5260169)

## Videos

- [Eve Just Changed How I Build AI Agents](https://www.youtube.com/watch?v=z8sp1dALZTI) — What eve is and why it matters, with a live build.
- [Can Eve Make AI Agents Easier to Build and Run? — Callstack livestream](https://www.callstack.com/events/can-eve-make-ai-agents-easier-to-build-and-run)

## Community

- [GitHub Discussions](https://github.com/vercel/eve/discussions) — Official Q&A and "Show and tell."
- [Vercel Community](https://community.vercel.com/) — Weekly updates and broader Vercel discussion.

## Showcase

Agents and projects built with eve. Open a PR to add yours.

- [Agentcn](https://github.com/shadcn-labs/agentcn) — shadcn/ui, but for building agents. 🤖
- [evex](https://evex.sh) — The open registry for eve agents. Install any community agent with `npx shadcn@latest add @evex/{slug}`, preview every file before it lands, and publish your own by pull request.
- _Your project here — open a pull request!_

## Contributing

Contributions are welcome! Please read the [contribution guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md) first. Add real, high-quality eve resources — one link per line, with a short description. Keep sections alphabetical where it makes sense.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
