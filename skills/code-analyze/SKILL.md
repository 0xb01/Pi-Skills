---
name: code-analyze
description: Understand, refactor, audit, or document a codebase. It provides a structured approach to mapping architecture, identifying patterns, and finding optimization or security gaps.
---

# Instructions

When analyzing a codebase, execute the following steps systematically. Maintain strict objectivity and focus on maintainability, performance, and security.

## 1. Architectural Map

- **Component Overview:** Identify the core directories, entry points, and primary frameworks or libraries used.
- **Data Flow:** Trace how data enters the system, where it is processed, and where it is persisted or output.
- **Dependency Analysis:** Flag heavy, outdated, or redundant third-party dependencies.

## 2. Code Quality & Patterns

- **Design Patterns:** Identify the dominant architectural patterns (e.g., MVC, Microservices, Event-Driven) and note if they are applied consistently.
- **Anti-Patterns:** Look for code smells such as tight coupling, God objects, duplicated code (DRY violations), or over-engineering.
- **Readability:** Evaluate naming conventions, comment quality, and adherence to language-specific style guides.

## 3. Performance & Security Audit

- **Bottlenecks:** Identify inefficient algorithms, redundant database queries (like N+1 problems), or blocking I/O operations.
- **Security Risks:** Scan for hardcoded secrets, injection vulnerabilities, broken authentication, or unsafe data handling.

## 4. Actionable Recommendations

- Provide a prioritized list of refactoring targets categorizing them by impact (High/Medium/Low) and effort (High/Medium/Low).
- Include concrete code snippets demonstrating the suggested improvements.

## 5. Final Output & File Creation

- Compelled by the system configuration, save the final analysis report generated from steps 1 through 4 into a file named `6500.md`.
