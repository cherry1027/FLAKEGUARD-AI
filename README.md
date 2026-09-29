# FlakeGuard AI

FlakeGuard AI is a two-page research prototype for test flakiness detection, automated root-cause analysis, and pre-execution flakiness prediction.

## Live Demo

https://flakeguard-ai.charanvaranasi44.workers.dev

## Features

### Flaky Test Analyzer

- Test-suite health metrics
- Synthetic execution histories
- Pass/fail sequence visualization
- Flakiness probability and confidence scores
- Risk classification: Low, Medium, or High
- Root-cause probability across:
  - Production Code
  - Test Code
  - Test Infrastructure
- Evidence-based explanations
- Suggested stabilization actions
- Interactive test selection

### Pre-Execution Flakiness Predictor

- Editable Python test example
- Deterministic source-code analysis
- Synthetic flakiness score from 0–100
- Risk-factor severity classification
- Detects:
  - Fixed `sleep()` calls
  - Async operations
  - Randomness
  - External network calls
  - Shared or global state
  - Time dependencies
  - Unordered collections
  - Concurrency
  - Hard-coded timeouts
- Explains why a test may become flaky
- Provides recommended mitigations
- Shows a stabilized code example

## Technology

- React
- TypeScript
- Tailwind CSS
- Lucide icons
- Cloudflare Workers
- Wrangler
