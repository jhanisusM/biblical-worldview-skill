# biblical-worldview

<p align="center"><img src="assets/avatar.jpg" alt="Bible bot avatar: an open Bible with golden light on navy" width="160"></p>

An agent skill for answering Bible questions from a fundamental, Bible-believing Baptist view.

- Scripture is always fetched live and the translation is named: KJV by default, plus NKJV, NASB, and Reina-Valera 1960.
- Verses are read in context, with exposition over proof-texting.
- Teachers (Charles Spurgeon, John MacArthur, and your pastor) are quoted only from sermons and books actually opened, with title and link.
- Sources: the free [TheologAI](https://mcp.theologai.xyz/mcp) MCP server, no-key Bible APIs ([bible-api.com](https://bible-api.com), [bolls.life](https://bolls.life), [bible.helloao.org](https://bible.helloao.org)), Spurgeon's public-domain sermons from [Spurgeon Gems](https://www.spurgeongems.org/spurgeon-sermons/) and [The Spurgeon Center](https://www.spurgeon.org/resource-library/sermons/), and [Grace to You](https://www.gty.org) sermon transcripts.
- Ships with a Classical Baptist preset (Calvary Road Baptist Church, Dr. John S. Waldrip's [sermon library](https://johnwaldriplibrary.com) and [Classical Baptist Press](https://www.classicalbaptist.press)). Swap in your own church and pastor.

## Install
Copy `SKILL.md` into a folder named `biblical-worldview` in your agent's skills directory (Claude Code: `~/.claude/skills/`, Cursor: `.cursor/skills/`, Grok Bot: save it as a skill). Optionally add the TheologAI MCP server.

## License
MIT
