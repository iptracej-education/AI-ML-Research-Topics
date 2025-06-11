This repository summarizes my research interests at the intersection of **AI-powered code analysis**, **security engineering**, and **automated vulnerability discovery**. My work integrates Large Language Models (LLMs), fuzzing, symbolic execution, and human-in-the-loop collaboration to explore scalable, adaptive, and intelligent vulnerability analysis platforms.

---

### Research Themes

1. LLM-Enhanced Deep Code Reasoning and Multi-Path Vulnerability Exploration <p>
   Using LLMs to break through the limitations of traditional single-path symbolic execution:

     - Beyond Crash Paths: Exploring alternative branches and variable transitions that static tools typically ignore.
     - Guided Input Mutation: Suggesting precise test inputs to trigger deeper and more complex code paths.
     - Concurrency and Shared Object Reasoning: Automating analysis of vulnerabilities dependent on multi-threaded logic and dynamic object sharing.

2. Adaptive and Data-Driven Vulnerability Discovery Pipelines

   Designing systems that continuously refine and optimize vulnerability detection and exploit generation:

  - Feedback-Oriented Pipelines: Orchestrating fuzzing, CodeQL analysis, and LLM suggestions in intelligent refinement loops.
  - Exploit Formula Optimization: Prioritizing low-complexity exploit paths using taint analysis and instruction complexity classification.
  - Scalable Context Engineering: Mitigating LLM limitations via smart context generation, static pre-filtering, and memory layout side-effect analysis.

3. Synergistic Human-Machine Collaboration in Vulnerability Research

   Building hybrid analysis platforms that combine the reasoning power of LLMs with expert human intuition:

  - LLM-Augmented Research: Leveraging LLMs to reason about complex vulnerabilities such as use-after-free bugs involving concurrency and shared state.
  - Human Oversight: Mitigating LLM false positives (e.g., ~1:50 signal-to-noise ratio) through expert review and manual curation.
  - Iterative Learning Loops: Enabling mutual improvement between human researchers and LLMs through collaborative debugging and continuous knowledge accumulation.


Keywords

`LLMs`, `Fuzzing`, `CodeQL`, `Symbolic Execution`, `Human-in-the-Loop`, `Exploit Generation`, `Concurrency Analysis`, `Memory Safety`, `Security Engineering`, `AI-Augmented Vulnerability Research`


#### 📫 Contact

Feel free to reach out with collaborations or discussions:

- Email: **kiwatana@hotmail.co.jp**
- LinkedIn: [Kiyoshi Watanabe](https://www.linkedin.com/in/kiyoshi-watanabe-06395213/)

