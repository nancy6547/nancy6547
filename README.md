## Nancy Singh

I work on browser testing tools and LLM reliability (open to work). 2026 CS graduate, Delhi.

### Open source

10 PRs merged: 8 into Google's Puppeteer and Chrome DevTools MCP, 1 into Hugging Face, 1 into Confident AI's DeepEval, a co-authored example in Instructor, plus bugs I found in Microsoft Playwright, Twenty and Documenso that their teams fixed.

- **Puppeteer** · [#15587](https://github.com/puppeteer/puppeteer/pull/15587) WebSocket handshake timeout · [#15590](https://github.com/puppeteer/puppeteer/pull/15590) `setGeolocation(null)` clears the override · [#15595](https://github.com/puppeteer/puppeteer/pull/15595) `respond()` skips undefined headers on CDP · [#15697](https://github.com/puppeteer/puppeteer/pull/15697) BiDi `respond()`/`abort()` no longer reject for gone requests
- **Chrome DevTools MCP** · [#3144](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3144) · [#3148](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3148) · [#3198](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3198) · [#3199](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3199) console, network and Lighthouse fixes
- **sentence-transformers** · [#4204](https://github.com/huggingface/sentence-transformers/pull/4204) PListMLE custom rank discount received a mask instead of ranks
- **DeepEval** · [#3470](https://github.com/confident-ai/deepeval/pull/3470) JSON dataset loader crashed on null `tools_called`/`expected_tools` (reported as [#3469](https://github.com/confident-ai/deepeval/issues/3469))
- **Instructor** · proposed a claim-decomposition example for fact-checking pipelines ([#2531](https://github.com/567-labs/instructor/pull/2531)); the maintainer incorporated it into `main` with co-author credit ([d1cfa23](https://github.com/567-labs/instructor/commit/d1cfa23b59049a106c6cc1963d1dc129795e8e57))
- **Playwright** · reported [#43459](https://github.com/microsoft/playwright/issues/43459), a codegen escaping bug, fixed in [#43472](https://github.com/microsoft/playwright/pull/43472)
- **Documenso** · reported [#3445](https://github.com/documenso/documenso/issues/3445), ~26 redundant `waitForTimeout` calls (~27.5 s of fixed sleep) found by parsing the E2E suite with the TypeScript Compiler API, fixed in [#3536](https://github.com/documenso/documenso/pull/3536)
- **XERJ Corpus Hub** · my #3199 fix is indexed as a [contributor corpus](https://hub.xerj.org/contributors/nancy6547), a reference library AI coding agents search before writing code
- **Twenty** · reported [#28342](https://github.com/twentyhq/twenty/issues/28342), Links field dropping slashes in query/hash, fixed in [#28421](https://github.com/twentyhq/twenty/pull/28421)

### Projects

| | |
|---|---|
| [Junban](https://github.com/nancy6547/junban) | Finds the API response order that breaks a flaky Playwright test. Caught 6/6 rare races by run 5; 3,000 plain reruns caught only 2/6. |
| [Zeitaku](https://github.com/nancy6547/zeitaku) | Replaces hard-coded sleeps in Playwright tests with network-aware waits over CDP. Built after the Documenso #3445 analysis. |
| [HalluGuard](https://github.com/nancy6547/halluguard) | Flags RAG answer sentences their sources don't support, using an NLI cross-encoder. |
| [Kensa](https://github.com/nancy6547/kensa) | Metamorphic testing for RAG apps. |
| [DocMind](https://github.com/nancy6547/docmind) | Question answering over PDFs, scanned ones included, with hybrid search. |
| [Attention-Guard](https://github.com/nancy6547/attention-guard) | Learns your personal "drifting" pattern from activity and 20-minute check-ins, and nudges you when focus slips. Runs fully on-device. |

TypeScript · Python · Playwright · Chrome DevTools Protocol · PyTorch

**Writing:** [I keep building tools that catch software lying about whether it works](https://medium.com/@singhnancy2004/i-keep-building-tools-that-catch-software-lying-about-whether-it-works-43ef67480b8e)

[nancy6547.github.io](https://nancy6547.github.io) · [LinkedIn](https://linkedin.com/in/nancy-singh-84367722a) · [X](https://x.com/Nancysingh251) · [Medium](https://medium.com/@singhnancy2004) · singhnancy2004@gmail.com
