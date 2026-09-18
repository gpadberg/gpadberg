# Grace Padberg

I build full-stack, systems, and data-driven software, and I’m looking for opportunities where I can ship reliable products end-to-end.

## Tech Stack
Rust · Python · JavaScript · Java · SQL · Flask · React · Firebase · SQLite · HTML/CSS

## Featured Projects

### 1) Distributed Poker Game *(Systems · Production-ready)*
**Repo:** [gpadberg/Distributed-Poker-Game](https://github.com/gpadberg/Distributed-Poker-Game)

- **Problem:** Build a real-time multiplayer poker system with consistent shared game state.
- **Role:** Primary developer and architect.
- **Tech stack:** Rust, WebSockets, HTTP API, SQLite, Trunk web client.
- **Key engineering decisions:**
  - Split architecture into HTTP menu/account server and per-table WebSocket game server.
  - Centralized shared protocol/types in a common Rust crate for client/server consistency.
  - Used server-driven game-state snapshots to keep clients synchronized.
- **Outcome/impact:** Delivered a browser-first multiplayer flow with account management, table creation, and live table updates.
- **Links:** [README](https://github.com/gpadberg/Distributed-Poker-Game/blob/main/README.md) · [Architecture](https://github.com/gpadberg/Distributed-Poker-Game/blob/main/ARCHITECTURE.md)

### 2) Fair Chance *(Mobile Team Project · Prototype)*
**Repo:** [Djay23/fair-chance-android-app](https://github.com/Djay23/fair-chance-android-app)

- **Problem:** Make event registration fair and accessible without first-come pressure.
- **Role:** Team contributor (Android/Firebase feature work in a collaborative course project).
- **Tech stack:** Android (Java), Firebase (Firestore/Storage/Auth), QR, geolocation/maps.
- **Key engineering decisions:**
  - Lottery-based waiting list instead of race-based signup.
  - Role-based workflows for entrants, organizers, and administrators.
  - QR-based event flow to reduce onboarding friction.
- **Outcome/impact:** Produced an end-to-end mobile event workflow focused on fairness, accessibility, and operational transparency.
- **Links:** [README](https://github.com/Djay23/fair-chance-android-app/blob/main/README.md)

### 3) EcoConnect *(Full-Stack Web App · Prototype)*
**Repo:** [gpadberg/EcoConnect](https://github.com/gpadberg/EcoConnect)

- **Problem:** Encourage sustainable habits through a social and gamified experience.
- **Role:** Full-stack developer.
- **Tech stack:** Flask, SQLite, HTML/CSS, Python.
- **Key engineering decisions:**
  - Lightweight Flask backend + SQLite for fast local development.
  - Habit logging and points model to drive behavior tracking.
  - Designed extensibility for social interactions and challenges.
- **Outcome/impact:** Built working authentication + habit tracking foundations with a clear roadmap for social features.
- **Links:** [README](https://github.com/gpadberg/EcoConnect/blob/main/README.md)

### 4) BME 415/615 Research Project *(Data Analysis · Research)*
**Repo:** [gpadberg/bme-415-615-project](https://github.com/gpadberg/bme-415-615-project)

- **Problem:** Organize and analyze biomedical datasets in a reproducible workflow.
- **Role:** Research collaborator and analysis contributor.
- **Tech stack:** Python, data processing workflows, scientific visualization artifacts.
- **Key engineering decisions:**
  - Kept raw, intermediate, and final outputs versioned in one repository.
  - Structured analysis artifacts to preserve reproducibility.
- **Outcome/impact:** Delivered a complete computational record tied to final figures and paper output.
- **Links:** [README](https://github.com/gpadberg/bme-415-615-project/blob/main/README.md)

### 5) ML Stock Price Prediction *(Data/ML · Learning Prototype)*
**Repo:** [gpadberg/ml-stock-price-prediction](https://github.com/gpadberg/ml-stock-price-prediction)

- **Problem:** Explore time-series forecasting for stock data.
- **Role:** Solo developer.
- **Tech stack:** Python, Pandas, NumPy, TensorFlow/Keras, scikit-learn, Matplotlib.
- **Key engineering decisions:**
  - Combined standard scaling + sequence windowing for LSTM-ready inputs.
  - Tracked forecasting quality with common regression/error metrics.
- **Outcome/impact:** Built and evaluated an end-to-end LSTM forecasting workflow over historical market data.
- **Links:** [Code](https://github.com/gpadberg/ml-stock-price-prediction/blob/main/project.py)

## Additional Projects

### Full-Stack / Front-End
- [gpadberg/websitev2](https://github.com/gpadberg/websitev2) *(Portfolio site evolution)*
- [gpadberg/my-website](https://github.com/gpadberg/my-website) *(React site foundation)*
- [gpadberg/PhobiaTest](https://github.com/gpadberg/PhobiaTest) *(Hackathon concept + web app experimentation)*

### Learning / Coursework
- [gpadberg/Projects](https://github.com/gpadberg/Projects) *(Python practice collection)*
- [gpadberg/learning](https://github.com/gpadberg/learning) *(C programming exercises)*
- [gpadberg/lab-06](https://github.com/gpadberg/lab-06) *(CMPUT 301 lab work)*
- [gpadberg/gpadberg](https://github.com/gpadberg/gpadberg) *(Profile/config repository)*

## About
I enjoy building software at different layers: user-facing product experiences, backend services, and data/ML workflows. I’m especially interested in roles that combine practical engineering with problem solving and iteration.

- GitHub: [@gpadberg](https://github.com/gpadberg)
- Email: gpadberg@ualberta.ca

## Portfolio Launch Checklist
- [ ] Add one visual artifact (screenshot/gif/diagram) for each featured project.
- [ ] Standardize featured project READMEs (problem, setup, architecture, role, outcomes).
- [ ] Add short “What I learned” section to each featured repository.
- [ ] Pin these same 5 featured projects on GitHub for consistency with portfolio site.
