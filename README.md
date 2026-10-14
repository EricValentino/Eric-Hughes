## Eric Hughes

Computer Science student who builds full-stack web apps in Python and JavaScript. I like projects that pull real data from external APIs, and I care about the unglamorous parts: input validation, error handling, tests, and READMEs that tell the truth about what the code does.

**Next up:** user authentication for AniTracker, and getting more comfortable with testing and CI.

---

### Featured projects

**[AniTracker](https://github.com/EricValentino/Manga-Tracker-)** · Python · FastAPI · SQLModel · SQLite · JavaScript · OpenAI API<br>
Manga and anime tracker with LLM-generated recommendations. A FastAPI backend wraps the AniList GraphQL API, stores a personal library and reading progress, and sends the saved list to an OpenAI model. The model's JSON output is validated, titles already saved are filtered out, and each pick is enriched with real cover art. Request bodies are validated at the edge, and upstream failures map to clear `502`/`503` errors instead of crashes.

**[Stock price forecasting with an LSTM](https://github.com/EricValentino/stock-price-lstm)** · Python · PyTorch · pandas · NumPy<br>
A time-series experiment built around careful evaluation. It uses a chronological train/test split, a scaler fitted only on training data to avoid look-ahead leakage, and test RMSE in dollars reported next to a naive "tomorrow equals today" baseline. It includes a training CLI, a prediction script and saved checkpoints.

**[Cosmic Treasure Hunt](https://github.com/EricValentino/Interactive-Website)** · JavaScript · Canvas · Web Audio API · [live](https://vxentino.neocities.org)<br>
A multi-page browser game written without frameworks or engines. The centerpiece is a canvas bullet-hell boss fight with a three-phase state machine, several attack patterns and a parry mechanic, plus sound effects synthesized at runtime with the Web Audio API.

<details>
<summary><b>Smaller experiments</b></summary>

- **[OpenGL Cube](https://github.com/EricValentino/OpenGL-Cube)**: a rotating cube in fixed-function OpenGL with Pygame; perspective projection, matrix stack, depth testing
- **[Heart Grove](https://github.com/EricValentino/Roblox-Game)**: a Roblox Studio world with Lua scripting for teleports, NPC dialogue and UI effects

</details>

---

### Tools I use

| Area | Tools |
|---|---|
| Languages | Python, JavaScript, HTML/CSS, Lua |
| Backend | FastAPI, SQLModel / SQLAlchemy, SQLite, REST and GraphQL APIs, httpx |
| Frontend | Vanilla JS, Canvas 2D, Web Audio API, GSAP |
| ML and data | PyTorch, pandas, NumPy, Matplotlib |
| Graphics and games | PyOpenGL, Pygame, Roblox Studio |
| Tooling | Git, GitHub, virtual environments |

**Learning:** pytest, GitHub Actions, authentication and authorization, database migrations.

---

<!-- Contact: add the links you want public (LinkedIn, email, résumé) before publishing. -->
