# J. M. Camargo

**Software Developer · Writer · Indie Creator**

I build software, tools, experimental systems, and occasionally things that probably did not need to exist — but were interesting enough to build anyway.

My work ranges from **systems and developer tools** to **web applications, programming languages, games, and creative projects**.

---

## Currently building

### DEXIS

A content-defined deduplication, adaptive compression, and resumable file-transfer system.

DEXIS is currently my main software project. It combines a Python orchestration layer with native Rust components and explores efficient handling of large files, repeated data, versioned assets, and interrupted transfers.

Some of the areas involved:

`Rust` · `Python` · `FastCDC` · `Zstandard` · `SQLite` · `BLAKE2b` · `HTTP/HTTPS` · `Windows`

**Current version:** `0.7.x`

[StreamFold / DEXIS website](https://github.com/GamasDoRpg/StreamFold-Site)

---

### Simply

An experimental programming language designed around explicit and readable syntax.

It currently includes its own:

* lexer
* recursive-descent parser
* AST
* semantic analyzer
* type system
* interpreter
* CLI
* VS Code tooling

Example:

```simply
STRING name = INPUT("Name: ")
INT age = INPUT("Age: ")

IF age >= 18:
    DISPLAY("Welcome", name)
ELSE:
    DISPLAY("Hello", name)
END
```

---

### Redline

A local HTTP/HTTPS load-testing tool.

The current version combines a Python CLI with a native **Rust + Tokio** engine designed for high-throughput controlled testing of servers and infrastructure.

It includes concurrency control, HTTP/1.1 and HTTP/2, connection reuse, ramp-up, bursts, latency statistics and automatic capacity testing.

---

### HumanType

A Windows-first experiment in configurable progressive keyboard input.

HumanType converts prepared text into simulated typing with adjustable rhythm, pauses, hesitations, corrections and typing speed.

Built with Python, Tkinter and the native Windows `SendInput` API.

---

## Atero

A collection of web applications and experiments that I built around a shared ecosystem.

Some of them include:

* [Atero Write](https://github.com/GamasDoRpg/atero-write) — writing environment
* [Atero Files](https://github.com/GamasDoRpg/Atero-Files) — cloud file manager
* [Atero Calendar](https://github.com/GamasDoRpg/Atero-Calendar)
* [Atero Calc](https://github.com/GamasDoRpg/Atero-Calc)
* [Atero Floor](https://github.com/GamasDoRpg/Atero-Floor)

The ecosystem has involved technologies such as JavaScript, APIs, Supabase and Cloudflare R2.

---

## Creative work

Programming is only one side of what I do.

I'm also a **fiction writer, screenwriter and indie filmmaker**, and I like mixing software with storytelling and worldbuilding.

### Uma Guerra do Amanhã

A science-fiction literary project with its own website:

[UGdA Website](https://github.com/GamasDoRpg/UGdA-Site)

I also used maintain my broader personal/creative site here, but its no longer on air:

[Ogramac](https://github.com/GamasDoRpg/Site-Ogramac)

---

## Things I like working with

```text
Languages
├── Rust
├── Python
├── C#
├── JavaScript
├── Java
├── Lua
└── Dart

Software & Platforms
├── Git / GitHub
├── Windows
├── Unity
├── Unreal Engine
├── Blender
├── Supabase
└── Cloudflare

Areas
├── Systems programming
├── File formats & data transfer
├── Developer tools
├── Web applications
├── Programming languages
├── Game development
├── Physics & astronomy
└── Storytelling
```

---

## What I'm interested in

I particularly enjoy projects where I can understand the system beneath the abstraction.

That usually means experimenting with things like:

**performance · compression · networking · file systems · language design · simulation · tooling · graphics · physics**

Some projects become products.

Some become experiments.

Some exist because I wondered:

> *"Could I build this myself?"*

And that is usually enough reason to start.

---

<sub>Most of my work is developed under **GamasDoRpg**. Some active projects are private while they are still in development.</sub>
