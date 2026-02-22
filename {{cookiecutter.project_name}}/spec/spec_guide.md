# Specification Guide

> **How to use this file:**
> This is a guide for writing your own spec. Replace every `[YOUR PROJECT: ...]` block with
> content specific to your project. Delete this instructions block when done.
> This document serves as the source of truth for both human developers and AI coding agents.

---

## 1. Executive Summary & Purpose

[YOUR PROJECT: Write 2-3 sentences describing what your system is and its core purpose. 
Who is it for? What does it enable the user to do? Provide the baseline value it offers.]

---

## 2. User Flows & Interfaces

[YOUR PROJECT: Walk through the system from the user's perspective, step by step. 
Be concrete — name actual UI elements, file formats, CLI commands, API endpoints, triggers, and outputs.]

### Flow 1: [Primary Action Name]
1. **Trigger:** [How does the user start this flow?]
2. **Action:** [What does the user do?]
3. **System Output:** [What is the expected result or next screen?]

### Flow 2: [Secondary Action Name]
*(Add more flows as necessary for the core functionality)*

---

## 3. Business Rules & Data Transformations

[YOUR PROJECT: Explain the domain rules, constraints, or data handling logic that govern the system. 
Instead of explaining *how* to code it, explain *what* must happen to the data. Use real numbers or examples.]

*   **Rule 1:** [e.g., "All uploaded images must be compressed to under 1MB before storage."]
*   **Rule 2:** [e.g., "If a user is inactive for 30 days, their account status changes to 'archived'."]
*   **Rule 3:** [...]

---

## 4. Edge Cases & Error Handling

[YOUR PROJECT: List the most critical failure scenarios and how the system should respond to maintain a good user experience and system stability.]

### Scenario 1: [Error Type, e.g., Invalid Input Format]
*   **What happened:** [Description of the issue]
*   **System response:** [What the user sees / What the system logs]
*   **Recovery:** [How the user or system recovers]

### Scenario 2: [Error Type, e.g., 3rd Party API Down]
*   **What happened:** [...]
*   **System response:** [...]
*   **Recovery:** [...]

---

## 5. Acceptance Criteria & Trade-offs

### Absolute Requirements (The "Must-Haves")
[YOUR PROJECT: What can NEVER be violated? These are hard constraints that determine if the feature is broken.]

1.  [Constraint 1, e.g., "Passwords must never be stored in plain text."]
2.  [Constraint 2, e.g., "The API response time must be under 500ms."]

### Optimization Goals / Preferences (The "Nice-to-Haves")
[YOUR PROJECT: When trade-offs must be made, what gets prioritized? List them in order of importance.]

1.  **Priority 1:** [e.g., "Readability of generated code over execution speed."]
2.  **Priority 2:** [e.g., "Memory efficiency over CPU usage."]

---

## 6. Output Examples: Good vs. Bad (Optional but Recommended)

[YOUR PROJECT: Provide concrete examples of what an ideal output looks like compared to an unacceptable one. This helps AI agents understand your exact expectations.]

**Example 1: [Context of the output]**
*   ✅ **Ideal Output:** [Show the perfect result]
*   ❌ **Unacceptable Output:** [Show a common mistake or bad result]
*   **Why:** [Briefly explain the difference]

---

## 7. Validation & Testing

[YOUR PROJECT: Define how we know this spec is satisfied. How will the Overlord system or testing framework validate the output? List the expected test cases or verification steps.]

*   **Test Case 1:** [e.g., "Run `npm run test:auth`. Expect 100% pass rate on all authentication functions."]
*   **Test Case 2:** [e.g., "Upload a 5MB CSV. Verify the system rejects it with a 'File too large' error message."]
*   **Overlord Validation:** [e.g., "The Overlord script will parse `output.log` and verify that the 'Unmatched Groups' metric equals 0."]
