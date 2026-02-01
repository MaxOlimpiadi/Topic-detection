# Topic Signature Extraction via EM

This repository implements a lightweight text processing pipeline for extracting **chapter-specific topic signatures** from literary texts using an **Expectation–Maximization (EM) algorithm**.

The approach models each chapter as a mixture of:
- a **topic distribution** (words characteristic of the chapter), and
- a **background distribution** estimated from the full text.

Words with high posterior probability under the topic distribution are interpreted as **salient or chapter-specific vocabulary**.

---

## Input

- `chapter.htm`
