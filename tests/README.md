# Local Exercise Test Cases

This directory contains standalone, documented test cases and REPL instructions for exercises from Functional Programming in Scala.

## Purpose

Because the 1st edition exercise repository does not include automated test suites, these files serve as a personal reference for:

- Quick manual verification via the interactive sbt console or Scala worksheets.

- Documented edge cases (empty collections, boundary limits, duplicates, and ordering invariants).

- Reproducible sanity checks to revisit solutions in the future.

## Quick Start

1. Start the interactive console for the exercises project from the repository root:

> sbt "project exercises" console


(Note: sbt automatically recompiles any modified .scala files before launching the prompt).

2. Open the file corresponding to the exercise you want to test (e.g., Ex2-1.txt, Ex2-2.txt).

3. Copy and paste the import statements, helper functions, and test expressions directly into the scala> prompt.

4. Compare your output against the annotated Expected results.

5. When finished, exit the console:

> scala> :quit or Ctrl+C


## Adding New Test Files

When creating tests for upcoming exercises:

- Name the file consistently (e.g., Ex<chapter>-<exercise>.txt).

- Include the exact package import.

- Document regular inputs, inverse/failing inputs, and critical boundary edge cases.
