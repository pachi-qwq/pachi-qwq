### Pachi

Java and Vue full-stack developer. I like the unglamorous half of the job — workflow
engines, dependency hygiene, the parts that only hurt when they are wrong — and I take
it as a good sign when a system ends up with fewer moving parts than it started with.

Most of my paid work is private enterprise Java (Spring, Flowable) and Vue, with
Eclipse Collections wherever a plain `List` would quietly do the wrong thing. In the
open I write small tools: a link cleaner that runs on Cloudflare, a Swing app that
drives Selenium test cases. I also read a lot of other people's source code to see how
they got there.

#### Currently exploring

- **Rust + Win32 + Direct3D 11** — [Pixstride](https://github.com/pachi-qwq/pixstride),
  a native Windows image viewer aimed at fast startup and bounded memory. It is in
  *design review*: architecture docs, stress-test plan and repo tooling only, no viewer
  binary yet. It is written down honestly, which is the point at this stage.
- **AI coding agents** — Codex and Hermes are part of my daily loop. The interesting
  part is keeping them accountable: AGENTS.md conventions, documentation linters, tests
  that actually fail.
- **Graphics and native desktop UI** — what a DXGI flip-model pipeline looks like when
  the requirement is a fast first frame instead of a demo scene.

#### Selected projects

**[link-cleaner-for-cloudflare-worker](https://github.com/pachi-qwq/link-cleaner-for-cloudflare-worker)**
— a Cloudflare Worker that strips tracking parameters from shared links while leaving
the surrounding text byte-for-byte intact. Zero runtime dependencies, one `index.js`,
no build step, unit and integration tests on `node --test`.

**[step-flow](https://github.com/pachi-qwq/step-flow)**
— a Java Swing desktop tool for composing and running Selenium UI tests: step table,
expression-driven test data, environment profiles, run history. Built because writing
the same test script by hand stopped being fun.

Most of my repositories are private enterprise work, so the two above are simply what
can be shown in public.

#### Languages

Bytes per language across my repositories, public and private — which is why the Java
and Vue share is mostly code you cannot see from here. Counted by `lowlighter/metrics`
every day at 10:30 Asia/Taipei.

<img src="./metrics-languages-light.svg#gh-light-mode-only" width="480" alt="Most used languages across my repositories, by bytes">
<img src="./metrics-languages-dark.svg#gh-dark-mode-only" width="480" alt="Most used languages across my repositories, by bytes">
