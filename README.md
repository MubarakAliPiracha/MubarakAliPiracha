## Mubarak Ali Piracha

Second-year Computational Mathematics (Co-op) student at the University of Waterloo. I build and ship AI products, with a focus on agent systems, evaluation, and LLM tooling.

### Experience

**Member of Technical Staff Intern, Coolhand Labs** (New York, NY · May–Sep 2026)
Built a multi-agent harness that auto-generates API client wrappers across the Node.js, Python, and Ruby SDKs, fanning out parallel self-reviewing agents. Debugged and fixed a production eval pipeline that had stranded LLM evaluation across thousands of sessions. Shipped an error-triage pipeline routing Rollbar errors into deduplicated GitHub issues and Slack alerts.

### Selected Projects

- **[Morph / NL-Robot](https://github.com/MubarakAliPiracha/Morph).** Natural-language robot control on ROS 2 Humble and Gazebo Fortress. Claude turns plain English into validated multi-step plans that execute over real ROS interfaces (`/cmd_vel`, `FollowJointTrajectory`, `/scan`), with live telemetry streaming to a browser 3D viewport. Hack the North semifinalist. *TypeScript, Next.js, React Three Fiber, FastAPI, rclpy, Docker, Claude API*
- **[RAG Citations Agent](https://github.com/MubarakAliPiracha/rag-citations-agent)** ([demo](https://rag-citations-agent.vercel.app)). Agentic RAG over user PDFs where every claim carries a clickable citation, or an honest refusal. Grounding is enforced in code rather than by prompt: answers that skipped retrieval or cite nothing are discarded, and fabricated citation markers are stripped. 63 tests. *TypeScript, LangChain, Next.js, Gemini/Claude*
- **[Pneumonia Detection CNN](https://github.com/MubarakAliPiracha/Pneumonia-detecter)** ([demo](https://pneumonia-detecter-tan.vercel.app)). 287K-parameter CNN on PneumoniaMNIST reaching 91.67% accuracy and 0.979 AUC, up from 83.3% after diagnosing overfitting. Reproduced MedMNIST's hidden preprocessing bit-exact in NumPy to close train/serve skew, and gated the ONNX export on 1e-5 logit parity against PyTorch. *Python, PyTorch, ONNX, Flask, Docker*
- **[ToolMind](https://tool-mind.vercel.app).** Searchable directory of 90+ AI tools with semantic ranking via Gemini 2.0 Flash and an instant TF-IDF fallback. *TypeScript, Next.js, Supabase, Gemini API*

More at **[mubarakpiracha.xyz](https://mubarakpiracha.xyz)**.

### Technical Skills

**Languages:** Python, TypeScript, JavaScript, Ruby, SQL, C++
**ML & AI:** LLM APIs (Anthropic, Gemini, Vertex AI), RAG, vector search, embeddings, LLM evaluation, prompt design, LangChain, HuggingFace, PyTorch, ONNX, scikit-learn
**Backend & Data:** Ruby on Rails, Node.js, Next.js, React, FastAPI, Flask, Sidekiq, PostgreSQL, MongoDB, Redis
**Infrastructure:** GCP (Vertex AI), AWS, Docker, Tailwind CSS

### Contact

**[Portfolio](https://mubarakpiracha.xyz)** · **[LinkedIn](https://linkedin.com/in/mubarak-ali-piracha)** · **[X](https://x.com/mubarkparacha)** · mpiracha@uwaterloo.ca
