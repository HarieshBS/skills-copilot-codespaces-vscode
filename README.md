# Skills: Copilot + Codespaces + VS Code

This repository is a practical guide to **fully understand and utilise GitHub Copilot** in a real development workflow.

## Goal

By the end, you should be able to:
- Use Copilot for code generation, explanation, refactoring, and debugging
- Work efficiently with Copilot Chat in VS Code/Codespaces
- Write better prompts and verify generated output safely
- Integrate Copilot into daily development habits

## Prerequisites

- A GitHub account with access to GitHub Copilot
- VS Code (local) or GitHub Codespaces
- GitHub Copilot and GitHub Copilot Chat extensions enabled in VS Code

## Setup

1. Open this repository in **GitHub Codespaces** (or clone locally in VS Code).
2. Sign in to GitHub in VS Code.
3. Confirm Copilot is active:
   - Copilot completions appear while typing
   - Copilot Chat opens from the sidebar or command palette

## Core Learning Workflow

Use this loop for each task:

1. **Understand**  
   Ask Copilot Chat to explain a file/function in simple terms.
2. **Plan**  
   Ask for a step-by-step approach before requesting code.
3. **Implement**  
   Generate small code blocks, not large unreviewed files.
4. **Validate**  
   Run tests/lint/build and fix issues with targeted prompts.
5. **Refine**  
   Request simplification, edge-case handling, and docs updates.

## High-Value Prompts

- “Explain this code and list edge cases I should test.”
- “Refactor this function for readability without changing behavior.”
- “Generate unit tests for this function using the existing test style.”
- “Why is this error happening? Suggest the smallest fix.”
- “Review this change for security and reliability risks.”

## Best Practices

- Keep prompts specific (context + constraints + expected output)
- Ask Copilot for **alternatives** and trade-offs
- Always review generated code before accepting
- Never paste secrets/tokens into prompts
- Prefer incremental changes and verify each one

## Self-Check: Have You Fully Utilised Copilot?

- [ ] I can use Copilot completions effectively while coding
- [ ] I can use Copilot Chat to understand existing code quickly
- [ ] I can produce better results with clear, constrained prompts
- [ ] I validate all AI-generated changes with tests or manual checks
- [ ] I use Copilot for both speed (generation) and quality (review/refactor)
