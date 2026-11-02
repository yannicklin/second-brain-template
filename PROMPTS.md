# Everyday Prompts

The second brain should normally **think and write as XXXXXX**. Most prompts therefore describe the output, audience, topic, and length. You do not need to keep saying "use-me" once the AI has loaded this repository.

## Start a new chat

> Read `AGENTS.md` and my approved profile. Think and write as me unless I say otherwise.

After that, prompt naturally.

## Articles

> Article: why AI agents still need human judgement.

> Long article: what I learned building AI applications this year.

> Short article: why simpler architecture often wins.

> Technical article: Databricks multi-agent patterns, for data and AI engineers.

## Posts

> Post: my thoughts on local AI becoming practical for everyday users.

> Short post: this AI tool is useful, but people are overcomplicating what it actually does.

> LinkedIn post: what I learned moving from web development into data and AI.

> Teams post: explain this Databricks update simply to the team.

## Topic / audience modes

Use the topic or audience as a simple modifier.

> Kid: explain what an AI agent is to a 10-year-old.

> Career: post about why engineers should learn AI without abandoning their core skills.

> News: post with my take on this article: [link/text]

> AI: article about why agent memory is not the same as intelligence.

> Investing: my thoughts on using AI for investment research, not blindly picking stocks.

> Work: turn these notes into a professional internal post.

## Length

Length can be combined with anything.

> Short: career post about learning by building.

> Long: article about my journey into AI engineering.

> Very short: news reaction to this: [link/text]

> Detailed: technical article about RAG evaluation and observability.

## Combined prompts

These will probably be the most common everyday prompts.

> Short + Career: why AI skills are becoming part of normal engineering work.

> Long + AI: my view on where multi-agent systems are genuinely useful and where they are overkill.

> Short + News: react to this announcement in my usual tone: [link/text]

> Kid + AI: explain RAG using an example a child would understand.

> Technical + Work: article on the practical differences between Genie, Databricks Apps, and custom agents.

> Personal + Career: post about how my engineering interests have changed over the past few years.


## Platform

Platform changes the writing attitude, structure, and level of formality while keeping the same core identity.

> Blog article: [topic]

> LinkedIn: [topic]

> Facebook: [topic]

> Discord: [topic]

Typical interpretation:

- **Blog article**: complete argument, more context, personal reasoning, useful detail.
- **LinkedIn**: professional, concise, insight-led, easy to scan, suitable for a broad work network.
- **Facebook**: more personal and conversational, less corporate, natural opinion and storytelling.
- **Discord**: direct, casual, short, conversational, comfortable with technical shorthand when the audience fits.

## Language

Language is independent from platform and topic. State it only when the default is not suitable.

> EN: [topic]

> 中文: [topic]

> EN + 中文: [topic]

> Mixed: [topic]

Interpretation:

- **EN**: natural English throughout.
- **中文**: natural Chinese throughout. Do not mechanically translate English sentence structures.
- **EN + 中文**: provide both language versions.
- **Mixed**: natural bilingual writing. Keep English technical/product terms where they read better, with Chinese used naturally around them. Do not translate terminology merely for symmetry.

The user's explicit language instruction for the current task overrides the normal profile preference without permanently changing the profile.

## Platform + language + length + topic

Modifiers can be combined without special syntax.

> LinkedIn + EN + Short: my thoughts on engineers learning AI by building real things.

> Facebook + 中文: 我對小朋友使用生成式 AI 的看法。

> Blog + EN + Long + Career: how my work moved from web development toward data and AI engineering.

> Discord + Mixed + AI: Qwen 最近這個更新其實幾有意思，尤其是 local agent use case.

> LinkedIn + EN + News: react to this announcement in my professional voice: [link/text]

> Facebook + 中文 + Personal: 把這段想法整理成比較像我平常分享的文章：[notes]

## Give me source material

The second brain should transform source material into your voice rather than merely summarising it.

> Post from this: [text/link]

> Short article from these notes: [notes]

> News reaction: [article/link]

> Turn this rough idea into something I would publish: [idea]

> Rewrite this draft as me: [draft]

## When you want a different role

Your core identity and style stay the same. The role changes the perspective.

> As an AI engineer: post about why this architecture is over-engineered.

> As a researcher: article examining whether this claim is actually supported.

> As a parent: explain my thoughts about kids using generative AI.

> As a career mentor: post about moving into data and AI engineering.

## Learning and maintenance

These are repository-management prompts, not normal content prompts.

> `learn-me`: this chat, PR only.

> `learn-me`: learn from how I edited this article, PR only.

> `review-me`: my writing style.

> `review-me`: check whether my current roles still represent me.

> `forget`: [item], PR only.

> `restore`: [item/version], PR only.

> `reset`: [area], keep everything else, PR only.

## Everyday pattern

Think of a prompt as a few optional modifiers plus the actual task:

```text
[platform] + [language] + [length] + [topic/audience/role]: [what I want]
```

Use only the modifiers that matter. Examples:

```text
LinkedIn + EN + Short: [topic]
Facebook + 中文: [topic]
Blog + Long + AI: [topic]
Discord + Mixed: [message/topic]
Kid + 中文: [topic]
News + LinkedIn: [link/text]
As an AI engineer + Blog: [topic]
Rewrite this as me: [draft]
```

There is no requirement to use the exact `+` syntax. Natural requests such as "Write a short Chinese Facebook post about this" mean the same thing.
