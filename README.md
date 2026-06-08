## Mohammad Al-Masalmeh

CS @ UT Austin

---

### Markets & ML

**[headsup-cfr](https://github.com/MohammadAlMasalmeh/headsup-cfr)**  
Heads-up no-limit Texas Hold'em solver implemented with Deep Counterfactual Regret Minimization. Game state is bucketed into information set abstractions and a neural network approximates regret values for states not stored in memory. Trains through self-play until strategy profiles converge toward Nash equilibrium.  
*Python, PyTorch*

**[Kalshi-Analyzer](https://github.com/MohammadAlMasalmeh/Kalshi-Analyzer)**  
Analysis of pricing efficiency across 1M+ settled NBA prediction market contracts on Kalshi. Measures favorite-longshot bias and time-decay drift in contract prices over the lifetime of each market. Includes backtests of trading strategies constructed from the observed inefficiencies.  
*Python, pandas, NumPy*

**[TransformerAddition](https://github.com/MohammadAlMasalmeh/TransformerAddition)**  
A GPT-style transformer built and trained from scratch (custom tokenizer, dataset, causal self-attention, and training loop, with no pretrained weights) that learns to perform 3-digit addition purely from examples. Trains autoregressively on 50k generated problems with a causal mask, then generates answers token by token at inference time, mirroring how large language models produce text one token at a time.  
*Python, PyTorch, custom tokenizer/dataset/transformer*

---

### Systems

**[Word_Counter](https://github.com/MohammadAlMasalmeh/Word_Counter)**  
Multithreaded C++ word frequency counter for the full English Wikipedia XML dump. Producer threads chunk the input file and push raw text blocks onto a shared queue. Consumer threads tokenize each chunk using `string_view` for zero-copy reads, accumulate per-thread frequency maps, and merge them under a mutex at shutdown.  
*C++17, std::thread, std::mutex*

---

### Agents

**[opencode-excel](https://github.com/MohammadAlMasalmeh/opencode-excel)** · ⭐ 4  
AI coding agent embedded in Excel. Translates plain-English instructions into Python that executes in a local sandbox against the active workbook. The agent reads runtime errors and revises its code in a self-correcting loop until the transformation completes.  
*TypeScript, Python*

**[MultiAgentOpenCode](https://github.com/MohammadAlMasalmeh/MultiAgentOpenCode)**  
Multi-pane dashboard for running several Claude sessions concurrently against the same codebase. Each pane is bound to a configurable model, streams live file diffs as agents edit, and supports prompt fan-out so the same task can be dispatched to multiple agents in parallel.  
*Next.js, TypeScript*

**[LeetAgent](https://github.com/MohammadAlMasalmeh/LeetAgent)**  
Agentic coding interview platform. Provisions an intentionally broken multi-file repository inside an E2B cloud sandbox, hands it to the candidate model, and grades the attempted fix using a hidden pytest suite. Includes a Next.js frontend and Supabase-backed session management.  
*Next.js, Supabase, E2B*

**[underleaf](https://github.com/MohammadAlMasalmeh/underleaf)**  
LaTeX editor with live PDF compilation and an integrated Claude assistant. The assistant edits the Tex source directly, repairs compilation errors, refactors document structure, and generates inline citations from a connected reference database.  
*Next.js, Claude API, MorphLLM*

**[GooseGuard](https://github.com/shriyaabalaji/hackhackgoose)** · 🏆 Hackathon winner  
AI security patrol platform where attacker and guardian agents run real exploit/mitigation loops against a codebase in real time, visualized as a live goose standoff. Streams round-by-round probe/defense exchanges over WebSocket, scores live security health, and surfaces prioritized fixes, then ships them straight to a PR with one click: the sandbox patches and verifies the changes so you never have to touch the errors yourself.  
*React, FastAPI, WebSocket, Claude/Gemini/OpenAI*

---

### Earlier

**[Newsify](https://github.com/MohammadAlMasalmeh/Newsify)**  
Classifier that flags potential misinformation in news articles. Builds TF-IDF feature vectors from article text and feeds them into an ensemble model trained on a labeled dataset of verified and fabricated articles.  
*Python, scikit-learn*

**[MoodBot](https://github.com/MohammadAlMasalmeh/MoodBot)**  
Discord bot that performs emotion classification on chat messages in real time. When the model detects sustained negative affect from a user, the bot surfaces a supportive response inside the channel.  
*Python*

**[Dorm2Door](https://github.com/MohammadAlMasalmeh/Dorm2Door)**  
Campus services web app. Lets students browse and order from on-campus resources through a unified React frontend backed by a lightweight Node service.  
*React, Node.js*

---

<sub>`malmasalmeh.2019@gmail.com`</sub>
