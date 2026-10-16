### Hi, I'm Nancy 👋

I build tools that make software tell the truth about whether it works: flaky browser tests and LLM answers that aren't backed by their sources. CS grad (2026), Delhi, open to remote or relocating.

**Projects**

- **[Junban](https://github.com/nancy6547/junban)**: finds the exact order of API responses that makes a flaky Playwright test fail, and writes a test that fails every time. Caught 6/6 rare races by the 5th run; plain reruns caught 2 in 3,000. [Live report](https://nancy6547.github.io/demos/junban/)
- **[Zeitaku](https://github.com/nancy6547/zeitaku)**: a TypeScript codemod that replaces hard-coded sleeps in Playwright tests with network-aware waits (Chrome DevTools Protocol). Found 240 sleeps across 7 open-source repos. [Playground](https://nancy6547.github.io/demos/zeitaku/)
- **[HalluGuard](https://github.com/nancy6547/halluguard)**: flags the sentences in a RAG answer that its sources don't support, with an NLI model, benchmarked on RAGTruth. [Live demo](https://halluguard-ak4qp46x8utv6muwu3mgcd.streamlit.app/)
- **[Kensa](https://github.com/nancy6547/kensa)**: tests a RAG app without knowing the right answers: changes the input in ways with a known effect (delete the source, change a number) and checks the answer reacts correctly. [Demo report](https://nancy6547.github.io/demos/kensa/)
- **[DocMind](https://github.com/nancy6547/docmind)**: ask questions about any PDF, scanned ones too: OCR, hybrid search, and every answer sentence checked. [Live demo](https://docmind-4trkdxlqhqz3mtx3wnmpja.streamlit.app/)
- **[Attention-Guard](https://github.com/nancy6547/attention-guard)**: learns when you drift into doomscrolling from your own check-ins, privately on your computer. [Demo report](https://nancy6547.github.io/demos/attention-guard/)

**Open source: 5 PRs merged into Google projects** (Puppeteer and Chrome DevTools MCP)

- **Puppeteer (Google), 2 merged:** [#15587](https://github.com/puppeteer/puppeteer/pull/15587) `handshakeTimeout` so connecting to a browser that never answers fails fast · [#15590](https://github.com/puppeteer/puppeteer/pull/15590) `page.setGeolocation(null)` removes a location override (CDP and BiDi), requested by the maintainer
- **Chrome DevTools MCP (Google), 3 merged:** [#3148](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3148) unhandled promise rejections show their reason · [#3144](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3144) Lighthouse explains unsupported URLs · [#3198](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3198) redirect chains only list earlier hops
- **Playwright (Microsoft):** found a codegen bug, [#43459](https://github.com/microsoft/playwright/issues/43459): multiline aria snapshots escaped `${` twice, so generated tests crashed. Reported with the root cause; fixed by the Playwright team in [#43472](https://github.com/microsoft/playwright/pull/43472)
- **Documenso:** [#3445](https://github.com/documenso/documenso/issues/3445) issue: 26 sleeps in the E2E tests that can be removed

**Stack:** TypeScript · Node.js · Playwright · CDP · Python · PyTorch · Hugging Face · FAISS

[Portfolio](https://nancy6547.github.io) · [LinkedIn](https://linkedin.com/in/nancy-singh-84367722a) · [Medium](https://medium.com/@singhnancy2004) · singhnancy2004@gmail.com
