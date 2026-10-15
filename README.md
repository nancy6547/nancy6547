### Hi, I'm Nancy 👋

I build tools that make software tell the truth about whether it works: flaky browser tests and LLM answers that aren't backed by their sources. CS grad (2026), Delhi, open to remote or relocating.

**Projects**

- **[Junban](https://github.com/nancy6547/junban)**: finds the exact order of API responses that makes a flaky Playwright test fail, and writes a test that fails every time. Caught 6/6 rare races by the 5th run; plain reruns caught 2 in 3,000. [Live report](https://nancy6547.github.io/demos/junban/)
- **[Zeitaku](https://github.com/nancy6547/zeitaku)**: a TypeScript codemod that replaces hard-coded sleeps in Playwright tests with network-aware waits (Chrome DevTools Protocol). Found 240 sleeps across 7 open-source repos. [Playground](https://nancy6547.github.io/demos/zeitaku/)
- **[HalluGuard](https://github.com/nancy6547/halluguard)**: flags the sentences in a RAG answer that its sources don't support, with an NLI model, benchmarked on RAGTruth.
- **[DocMind](https://github.com/nancy6547/docmind)**: ask questions about any PDF, scanned ones too: OCR, hybrid search, and every answer sentence checked. [Live demo](https://docmind-4trkdxlqhqz3mtx3wnmpja.streamlit.app/)
- **[Attention-Guard](https://github.com/nancy6547/attention-guard)**: learns when you drift into doomscrolling from your own check-ins, privately on your computer. [Demo report](https://nancy6547.github.io/demos/attention-guard/)

**Open source**

- **Puppeteer (Google), merged:** [#15587](https://github.com/puppeteer/puppeteer/pull/15587) adds a `handshakeTimeout` option so connecting to a browser that never answers fails fast instead of hanging
- **Chrome DevTools MCP (Google):** [#3144](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3144) Lighthouse error for unsupported URLs · [#3145](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3145) clear geolocation emulation · [#3148](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/3148) show the reason for unhandled promise rejections
- **Stagehand (Browserbase):** [#3175](https://github.com/browserbase/stagehand/pull/3175) networkidle fix · [#3194](https://github.com/browserbase/stagehand/pull/3194) extension upload on Deno
- **Kensa** ([repo](https://github.com/nancy6547/kensa)): my metamorphic testing tool for RAG apps · [Documenso #3445](https://github.com/documenso/documenso/issues/3445) issue: removable sleeps in E2E tests

**Stack:** TypeScript · Node.js · Playwright · CDP · Python · PyTorch · Hugging Face · FAISS

[Portfolio](https://nancy6547.github.io) · [LinkedIn](https://linkedin.com/in/nancy-singh-84367722a) · [Medium](https://medium.com/@singhnancy2004) · singhnancy2004@gmail.com
