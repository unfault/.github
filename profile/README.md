<p align="center">
  <img src="https://raw.githubusercontent.com/unfault/vscode/main/icons/svg/unfault-logo.svg" alt="Unfault" width="200">
</p>

<h3 align="center">Cognitive context for the code you work on everyday.</h3>

<p align="center">
  <a href="https://unfault.dev/docs">Documentation</a> •
  <a href="https://unfault.dev/docs/installation">Get Started</a> •
  <a href="https://marketplace.visualstudio.com/items?itemName=unfault.unfault">VS Code Extension</a>
</p>

---

You know that moment when you're about to change a function and wonder: *"What else does this touch?"*

Unfault answers that question before you find out the hard way.

## See What Your Code Actually Does

When you're editing `process_payment()`, you probably want to know:

- 🔗 **Who calls this?**: 3 routes, 2 functions
- 🎯 **What SLOs are related to your route?**: 99.9% availability on `/checkout`  
- ⚠️ **What's missing?**: No timeout on the external API call

Instead of grepping, tracing, and hoping: you just see it.

<p align="center">
  <img src="https://unfault.dev/screenshots/sidebar-context.png" alt="Context sidebar showing callers and routes" width="600">
  <br>
  <em>Context appears in the sidebar as you navigate your code</em>
</p>

## It Works Where You Work

**In VS Code**: context follows your cursor

<p align="center">
  <img src="https://unfault.dev/screenshots/codelens-hint.png" alt="CodeLens showing function impact" width="500">
  <br>
  <em>Compact hints above functions show what matters</em>
</p>

**In your terminal**: review before you push

```
$ unfault review

→ Analyzing payments-service... 847ms

Summary
One function handles 73% of your checkout flow. It's missing
a timeout on the Stripe call. If Stripe hangs, so do your users.

At a glance
  · 12 routes, 3 background jobs
  · 2 functions with no error handling on external calls
  · SLO coverage: 8/12 routes (67%)
```

**In CI**: review in your pipelines

<p align="center">
  <img src="https://unfault.dev/screenshots/ci-output.png" alt="CI output showing analysis results" width="500">
  <br>
  <em>Runs in seconds, flags what changed</em>
</p>

## What's Here

| Repository | What it does | License |
|------------|--------------|---------|
| **[cli](https://github.com/unfault/cli)** | The brain: analysis, CI integration, LSP server | MIT |
| **[core](https://github.com/unfault/core)** | Parsing and graph building | MIT |
| **[vscode](https://github.com/unfault/vscode)** | VS Code extension | MIT |

## Supports Your Stack

Python · Go · Rust · TypeScript · JavaScript

FastAPI · Flask · Django · Express · Gin: with framework-aware route detection.

## Your Code Stays With You

Source code never leaves your machine. We receive a semantic graph: imports, calls, relationships: not your actual code. [Privacy details →](https://unfault.dev/privacy)

---

<p align="center">
  <b>Write with greater insights.</b>
  <br><br>
  <a href="https://unfault.dev/docs/installation">Get Started →</a>
</p>
