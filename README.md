### Boris Armenta

Former Software Developer. I write native Windows software in **C++20/23** and **.NET** — Win32 shells,
Direct2D renderers, COM-style plugin runtimes, WinUI 3 clients — and I care as much about the process
around the code as about the code itself.

**Selected work**

- **[Basalt](https://github.com/borisarm/Basalt)** — local-first Markdown editor for Obsidian vaults, with
  one GitHub repository per vault. .NET 10 + Avalonia, cross-platform. Built spec-first: the
  specification is the source of truth and an AI agent writes the code against it. 19 ADRs, mutation
  testing, coverage gates, CI on three operating systems.
- **[equator](https://github.com/borisarm/equator)** — worksheet-style computer algebra system for Windows,
  with a symbolic engine written from scratch in C#: exact arithmetic, factorisation over ℚ, symbolic
  integration, ODEs. WinUI 3 + Win2D for typesetting and plotting. Published on the
  [Microsoft Store](https://apps.microsoft.com/detail/9P7WTJNFC7J8).
- **[component_registry](https://github.com/borisarm/component_registry)** — runtime port→adapter
  resolution for C++23 hexagonal monoliths: the useful half of COM, without IDL, apartments or
  marshaling.
- **[talmon](https://github.com/borisarm/talmon)** — native Windows monitor for Talos Linux clusters,
  talking gRPC straight to the Talos machine API (WinUI 3 + C++/WinRT, mutual TLS).
- **[DiagramApp](https://github.com/borisarm/DiagramApp)** — modular diagramming engine: C++20 modules,
  Domain-Driven Design, Win32 shell, Direct2D renderer, Blender-style tools, runtime shape plugins.

**How I work**

Specs in `docs/specs/` before code → an ADR for every decision that would be expensive to reverse →
tests with coverage and mutation gates → CI that actually runs. The rule in anything that touches user
data: when in doubt, keep both versions.

Some older repositories here are kept on purpose, warts and all — restarts, dead ends and rewrites
included. That is what learning a craft looks like from the inside.

📫 boris@barquillo.net
