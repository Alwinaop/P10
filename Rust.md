# Rust Learning and Project Resources

## Why Learn Rust?
Rust is a systems programming language focused on safety, speed, and concurrency. It guarantees memory safety without garbage collection, making it ideal for embedded systems, game engines, web assembly, and high-performance applications. Companies like Microsoft, Google, and Amazon use Rust for critical infrastructure. Its growing adoption in blockchain (Solana, Polkadot) and AI/ML makes it a future-proof skill.

---

## Free Learning Resources

### **Beginner-Friendly**
- **[The Rust Programming Language (The Book)](https://doc.rust-lang.org/book/)** - Official free guide covering syntax, ownership, and lifetimes.
- **[Rustlings](https://github.com/rust-lang/rustlings)** - Interactive exercises to practice Rust concepts.
- **[Rust by Example](https://doc.rust-lang.org/rust-by-example/)** - Learn through code snippets with live editing.
- **[FreeCodeCamp Rust Course](https://www.youtube.com/watch?v=gyMwXuJrbJQ)** - 16-hour hands-on YouTube tutorial.

### **Intermediate/Advanced**
- **[The Rustonomicon](https://doc.rust-lang.org/nomicon/)** - Master unsafe Rust and low-level optimizations.
- **[Writing an OS in Rust](https://os.phil-opp.com/)** - Build a kernel from scratch.
- **[Rust Atomics and Locks](https://marabos.nl/atomics/)** - Deep dive into concurrency primitives.
- **[Advent of Code Solutions in Rust](https://github.com/rust-lang/advent-of-code-2023)** - Algorithmic challenges.

---

## Project Ideas by Skill Level

### **Beginner**
1. **CLI Todo List**  
   - Practice file I/O and CRUD operations.  
   - *Crates*: `clap`, `serde`.  
   - [Sample Code](https://github.com/rust-lang/rustlings/tree/main/exercises).

2. **Weather CLI Tool**  
   - Fetch data via APIs using `reqwest`.  
   - *Crates*: `serde_json`, `tokio`.

3. **File Organizer**  
   - Sort files by type/date.  
   - *Crates*: `std::fs`, `chrono`.

### **Intermediate**
1. **Web API with Actix**  
   - Build a RESTful API with PostgreSQL.  
   - *Crates*: `actix-web`, `diesel`, `dotenv`.

2. **Real-Time Chat App**  
   - Use WebSockets (`tokio-tungstenite`).  
   - *Framework*: `axum` or `actix`.

3. **Markdown to HTML Converter**  
   - Parse and transform text.  
   - *Crates*: `pulldown-cmark`, `regex`.

### **Advanced**
1. **Blockchain Node**  
   - Implement consensus algorithms.  
   - *Crates*: `libp2p`, `parity-scale-codec`.

2. **Game Engine**  
   - 2D rendering with `Bevy` or `macroquad`.  
   - [Bevy Tutorial](https://bevyengine.org/learn/).

3. **Embedded Systems Project**  
   - Use `embassy-rs` for IoT devices.  
   - *Guide*: [Embedded Rust Book](https://docs.rust-embedded.org/book/).

---

## Tools & Frameworks

| Category          | Tools                                                                 |
|--------------------|-----------------------------------------------------------------------|
| **Web Development** | `actix-web`, `rocket`, `axum`, `leptos` (full-stack)                 |
| **Async Runtime**   | `tokio`, `async-std`                                                 |
| **Game Dev**        | `bevy`, `macroquad`, `fyrox`                                         |
| **GUI**             | `egui`, `iced`, `slint`                                              |
| **Testing**         | `criterion` (benchmarks), `mockito` (HTTP mocking)                   |
| **Embedded**        | `embassy-rs`, `probe-rs`, `cortex-m`                                 |

---

## Communities & Events
- **[r/rust](https://www.reddit.com/r/rust/)** - Active Reddit community.
- **[Rust User Forum](https://users.rust-lang.org/)** - Q&A and discussions.
- **[RustConf](https://rustconf.com/)** - Annual conference for Rustaceans.
- **[Hackathons](https://github.com/rust-community/events)** - Global Rust events.

---

## Books & Bonus Resources
- **[Programming Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)** - O’Reilly’s definitive guide.
- **[Zero To Production In Rust](https://zero2prod.com/)** - API development from scratch.
- **[Rust Cheat Sheet](https://cheats.rs/)** - Quick syntax reference.
- **[Rust Playground](https://play.rust-lang.org/)** - Experiment with code online.

---

## YouTube Channels
- **[Let’s Get Rusty](https://www.youtube.com/c/LetsGetRusty)** - Tutorials and book breakdowns.
- **[Jon Gjengset](https://www.youtube.com/c/JonGjengset)** - Advanced concurrency/OS topics.
- **[Tensor Programming](https://www.youtube.com/c/TensorProgramming)** - Project-based learning.

---

All links tested and verified (July 2024). 🦀  
