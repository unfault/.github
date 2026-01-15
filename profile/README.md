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

## It Works Where You Work

**In VS Code**: context follows your cursor

<p align="center">
  <img src="../public/codelens.png" alt="CodeLens showing function impact" width="500">
  <br>
  <em>Compact hints above functions show what matters</em>
</p>

<p align="center">
  <img src="../public/sidebar.png" alt="Impact shown in the sidebar" width="500">
  <br>
  <em>Get context as you navigate your code</em>
</p>

**In your terminal**: review before you push

<p align="center">
  <img src="../public/review.png" alt="Review your code from the terminal" width="500">
  <br>
  <em>Runs in no time, flags what is worth looking</em>
</p>


<p align="center">
  <img src="../public/ask.png" alt="Ask about your code" width="500">
  <br>
  <em>Ask natural questions about your code</em>
</p>


Use this context with your favourite AI too.

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
