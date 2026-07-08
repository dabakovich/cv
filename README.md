Lviv, Ukraine 🇺🇦  
[LinkedIn](https://www.linkedin.com/in/david-tabaka-394939107)  

[Telegram](https://t.me/dabakovich)  

[github.com/dabakovich](https://github.com/dabakovich)  

[dabakovich@gmail.com](mailto:dabakovich@gmail.com)  


### About Me
Senior React Native Engineer with 6+ years across the full mobile stack — React Native and TypeScript up the stack, Swift/Kotlin and TurboModules down it. Tech-lead and people-manager experience (3–6 direct reports) on top, plus a public open-source footprint outside work. Agent-native for 1.5+ years: ~98% of my code is now agent-generated, driven through disciplined planning, custom skills, and MCP — not vibe-coding, but engineered agent workflows.

### Selected Achievements
- Built and maintained Guesty mobile apps used daily by **thousands of property managers worldwide** across iOS + Android.
- Cut Guesty app initial load 78% (700 ms → 150 ms) and tripled scroll FPS by building a virtualized 2D grid for React Native.
- Shipped 50+ store releases with zero critical rollbacks across iOS + Android.
- Author of `react-native-controlled-mentions` — 30k+ weekly npm downloads, used in production by multiple companies.
- Volunteer contributor to **Smart Event Detector** (2024) — Ukraine-defense acoustic-triangulation system that locates battlefield explosion sites via sound.
- Pioneered **reliable autonomous agent loops for React Native** — wired Claude Code to Maestro e2e tests so the agent runs the app on-device, reads real UI results, and self-corrects without a human in the loop.
- Built my own coding agent (**[ai-project-assistant](https://github.com/dabakovich/ai-project-assistant)**) in early 2024, before Cursor/Claude Code were mainstream; now run **~98% agent-generated code** across production work with 1.5+ years of regular agentic development.
- Mentored 3–6 engineers with weekly 1:1s, PDPs.  


### Agentic AI Development

Two years running production development through AI agents, evolving from a custom-built agent to today's tooling. The workflow is engineered, not ad-hoc:

- **Planning-first:** decompose work into specs and plans before the agent writes code.
- **Skills:** compose reusable agent skills — primarily [superpowers](https://github.com/obra/superpowers)-based, with other tech-specific or custom skills per project.
- **MCP:** integrate tools and context sources via Model Context Protocol.
- **Agent loops:** closed-loop self-correction, including a Maestro-based approach for real React Native e2e verification on device.
- **Tooling:** Claude Code, Codex, and Cursor — matched to the task.


### Skills And Technology

**Mobile (Primary):** React Native, TypeScript, react-navigation, Reanimated, Redux Toolkit, MobX, MMKV/AsyncStorage, Jest, Detox, Firebase, App Store Connect, Google Play Console  

**Native bridging:** Swift, Kotlin, Objective-C basics, TurboModules, custom native modules (including New Architecture)  

**Mobile delivery:** CI/CD (Fastlane, GitHub Actions), OTA updates (CodePush), crash reporting, A/B testing, feature flags, Push Notifications, Deep Linking  

**Agentic AI development:** Claude Code, Codex, Cursor · agent skills (superpowers + custom) · MCP · spec/plan-driven workflows · closed-loop agents (Maestro e2e for RN) · 2+ years, ~98% agent-generated code  

**Frontend:** React, Redux Toolkit, MobX, Material UI, React Router  

**Backend:** Node.js, Express, NestJS, REST, MongoDB/Mongoose  

**Practices:** Performance profiling (Flipper, RN DevTools), TDD, code review, performance profiling, i18n

### Other interests

**ML/AI:** Python, NumPy, Pandas, scikit-learn, TensorFlow, Reinforcement Learning, genetic algorithm LLM-based agents, LangChain, LangGraph, RAG  


### Leadership

- Managed 3–6 engineers across two squads; ran weekly 1:1s, PDPs, and quarterly reviews.  

- Hired 2 engineers end-to-end (sourcing → tech screen → offer);  

- Tech-lead duties: architecture decisions, best practices implementation and control, mentorship.

### Work Experience

**Senior React Native Engineer [Guesty](https://apps.apple.com/us/app/guesty/id1344816619) Mobile Apps** at **[Forbytes](https://forbytes.com/)**  

May 2022 - May 2026  · iOS + Android · Hospitality / PMS platform  

*Hospitality Management Platform*  


As a Senior React Native Engineer at Guesty, I played a critical role in developing and maintaining the "Guesty" and "Guesty for Hosts" mobile apps. These apps enable property managers to manage reservations, automate guest communication, and streamline operations. Some of my key contributions to this project included:

- Managed migration legacy code to application from scratch, decreased initial load from 2s to 600ms.
- Shipped **50+** App Store / Play Store releases with zero critical rollback.
- Owned key flows: core Multi-Calendar feature and Tasks/Listings features.
- Implemented virtualized grid (like FlatList but 2d), optimized initial load from **700ms to 150ms**, increased scroll FPS **from 20 to 60**.
- Collaborating with the team to develop and implement new features, such as integrating third-party APIs for payment processing and booking management.
- Developing and maintaining a robust codebase using best practices and standards, with a strong emphasis on code quality and testing.
- Partnered with design + product on a shared component system.

**Mobile / Full-Stack Engineer (later People Manager) — Rake** at **[42flows.tech](https://42flows.tech)** (previously [Chatbots.Studio](https://chatbots.studio/))  

September 2018 - May 2022  


Allows businesses to connect external platforms (Twilio, FB, WhatsApp, web widgets) to the workspace in Rake and communicate with their customers.

- Worked with the team on both backend and frontend side.
- Completely developed mobile application using React Native and TypeScript.
- Owned CI/CD on App Center → migrated to Fastlane, cutting release time from **2h to 25m**.
- Drove TypeScript strict-mode rollout across the codebase, eliminating `any` from **400+ files**.
- Mentored 3 mid-level engineers; ran weekly tech-review calls and PDP cycles.

### Projects

**[DevYoga](https://github.com/dabakovich/dev-yoga)** — *Pet Project — AI task tracker built in one week · Jun 2026*  

Full-stack task tracker for developers with a built-in conversational **AI agent** that manages the board through chat. React Native app on the latest Expo SDK 56 with native SwiftUI components, NestJS backend — designed, built, and shipped **in one week**.

- Built a multi-step AI agent (Claude via Vercel AI SDK) with tool-calling for task creation, "plan my day" prioritization, and triage — with human-in-the-loop confirmation before writes and persistent agent memory.
- Implemented stateless chat: the transcript is persisted on-device (MMKV) and replayed per request, keeping the backend session-free.

**Smart Event Detector** — *Volunteer project — Ukraine defense · Feb 2024 – Jul 2024*  

Distributed acoustic-triangulation system that pinpoints battlefield explosion sites by measuring the arrival-time delta of the shockwave across a network of Android devices — conceptually GPS, but with sound waves instead of radio. The React Native app continuously analyzes the raw audio stream, detects explosion events locally with high-precision timestamps, and forwards them to the backend, which solves for the source coordinates via time-difference-of-arrival (TDoA).

- Built the React Native client: continuous raw-audio capture, on-device explosion detection, and precise event timestamping for server-side multilateration.
- Authored a custom **TurboModule (New Architecture)** to run the real-time sound-event detection off the JS thread, cutting per-batch processing from **~60 ms to <1 ms (60× faster)** — essential for the sub-millisecond timestamp accuracy the TDoA math requires.
- Designed the mobile↔backend event protocol so multiple devices can stream synchronized detection events for coordinate triangulation.
- Integrated **Firebase Realtime Database** for low-latency device presence and live GPS tracking, giving operators an instant map view of which devices are online and where on the battlefield.

**[react-native-controlled-mentions](https://www.npmjs.com/package/react-native-controlled-mentions)** — *React Native community library 30k+ NPM weekly downloads, ★ 250+ on GitHub*  

Widely-used React Native library for mentions and rich text inside TextInput, no native modules required. 30k+ weekly npm downloads, 250+ GitHub stars, used in production by multiple companies. Originally built for Rake, then open-sourced.

**[ai-project-assistant](https://github.com/dabakovich/ai-project-assistant)** — *Custom AI coding agent — Jan 2024*

Autonomous coding assistant I built to navigate, read, and modify a codebase and run Git operations from natural-language tasks — a self-made agent that predated mainstream tools like Cursor and Claude Code, and shaped how I work with agents today.

- Implemented an agent loop on OpenAI GPT models with tool/function-calling to drive file navigation, read/create/modify operations, and Git diffs.
- Architected around clear modules — AI interaction, file-system operations, and shared utilities for message generation and tool-call handling.
- Built entirely in TypeScript on Node.js, with type-safe tool definitions bridging the model to the local project.

**[Neural Network from Scratch](https://github.com/dabakovich/neural_network_playground)** — *Pet Project*  

Custom neural network implementation built from scratch using NumPy with full back-propagation algorithm. The project includes a reinforcement learning experiment where two AI agents learn to play TicTacToe through self-play.

- Implemented complete neural network with support for multiple activation functions (ReLU, Leaky ReLU, Sigmoid, Tanh, Softmax) and proper weight initialization strategies (He, Xavier).
- Developed back-propagation algorithm with support for both MSE and Log loss functions, including special Jacobian matrix handling for Softmax layers.
- Built reinforcement learning system with two competing agents (9→18→18→9 architecture) that learn optimal TicTacToe strategies through reward-based training over thousands of self-play games.
- Implemented real-time statistics tracking and visualization to monitor agent performance, win rates, and learning progression.

### Earlier Projects

[Strobe Spectroscopy](https://github.com/dabakovich/StrobeSpectroscopy) — *Controller*  

Early student project. Application with Swing GUI, that control motor stepper through Arduino, and reading analog data from the micro-controller. This allows to computerize instrument for measuring light spectrum.

### Education

**[Ready Tensor](https://app.readytensor.ai/hubs/ready_tensor_certifications)** — Agentic AI Developer Certification Program  

May 2025 - July 2025  

- Built agentic systems using LangChain with RAG (Retrieval-Augmented Generation) pipelines and vector database integration.

**robot_dreams** – How to build a recommendation model in Python in 2 days  

August 2024

**Stratoplan Manager School** — Course "Team"  

September 2021 - February 2022  


- Team audit on entry
- Communication within the team (constructive confrontations)
- Interviewing, hiring and firing
- Setting and controlling tasks, delegation
- Team status monitoring and feedback

**Logos, Lviv** — Java (Hibernate, JPA, Spring)  

April 2016 - September 2016  


**LNU, Lviv** — LNU, Master’s degree, Electronics  

September 2011 - July 2017  


### Languages

- **Ukrainian**: Native
- **English**: B2, comfortable with daily standups, written communication, and code reviews

