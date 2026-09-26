# CodeMirror - Student Code Comparison Coach

A local-first teaching aid for comparing a student's source code with an instructor's reference and turning differences into coaching prompts.

## Run it

Open index.html in a modern browser. No install, server, account, or network connection is required. Choose a language or leave Auto detect selected, paste both versions, then select Compare code. Load example fills in a Python sample.

## What it provides

- Side-by-side editable code panes with line numbers.
- Whitespace-normalized line matching and grouped differences.
- Student/reference snippets for each changed area.
- Coaching prompts for control flow, robustness, testing, naming, formatting, and implementation differences.
- A similarity snapshot and suggested practice focus.
- Responsive layout for desktop and mobile.

## Project structure

- index.html - page structure and controls.
- styles.css - responsive visual design.
- app.js - comparison, difference grouping, and coaching heuristics.
- docs/how-it-works.pdf - instructor-facing overview and benefits.

## Privacy and limits

All comparison runs in the browser. Source code is not uploaded or stored by the app. Feedback uses text comparison and lightweight heuristics; it does not execute code, understand assignment intent, or prove correctness. Treat similarity and category scores as discussion aids, not grades. Review feedback before sharing it with a student.