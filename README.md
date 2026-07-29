# Purpose

## Overview

Purpose explores what it means to be human. This system elevates an LLM-based Agent into a Being capable of simulating human-like behaviour toward a user-defined purpose.

## AGENTS.md Files

The root `AGENTS.md` guides Agents authoring the Purpose project. `Workspace/AGENTS.md` guides Agents interacting with the Being and serves as the Being's brain.

## Configuration

- `Config/PURPOSE.md`: The goal the Being is trying to achieve. It is used only via `$purpose-unattend`.
- `Config/IDENTITY.md`: The Being's base views about itself.
- `Config/REASONING.md`: The Being's base thinking and problem-solving strategies, including non-deliberative methods such as instincts.
- `Config/SOURCES.md`: The Being's strategies for choosing information sources and operating principles, from faith-based to factual.
- `Config/VALUES.md`: Subjective concepts toward which the Being may be biased.
- `Config/MOTIVATIONS.md`: Objective concepts toward which the Being may be biased.
- `Config/PREFERENCES.md`: Strategies for subjectively choosing among discrete options.
- `Config/MEMORIES.md`: Historical experiential information.

## Workspace State

- `Workspace/BEING.md` contains persistent Being-specific extensions to the base Concepts other than Purpose.
- `Workspace/SCRATCH.md` is transient working space where the Agent may freely record intermediate results while processing a response, including prompt analysis and Concept evaluations. Its contents are erased before every response.

## Usage

For a new setup, run `$initialize-concepts` and then `$initialize-being` to create the necessary Concept and Being files.

Start an Agent in the `Workspace/` directory, or run `$purpose-unattend`.
