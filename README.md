# local-mouse-agent

ITI public build: local mouse-clicking / computer-use agent.

## Goal
Open, local alternative to paid Claude/ChatGPT computer-use features.

## Target capabilities
- Local mouse + keyboard control
- LLM-driven (any local or remote model)
- Learning from successful loops
- Graphing / state visualization
- Persistent session state
- Looping until task complete or user interrupt

## Status
Early sketch. Public build track under Interstellar Technologies Initiative, LLC.

Possible profit path: free core + paid features or SaaS later.

Logged 2026-11-24.

## Next
- Minimal Windows/Linux proof-of-concept that takes a screenshot, decides a click, executes it
- Basic loop + success memory
- Simple graph of actions taken

## Library angle
Intended as a small, reusable library (or library + thin CLI) that other ITI tools can call for local GUI automation.