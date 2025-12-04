**Student**: Samuel J. Roper 201835172 **Submission date**: \[DD/MM/YYYY\] **Academic Year**: 2025-26

------------------------------------------------------------------------

## [Privacy & Ethics Statement](#privacy--ethics-statement){.header} {#privacy--ethics-statement}

-   I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names)
-   I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible)
-   I confirm all participants gave informed consent
-   I confirm this work is my own (AI tools used for code assistance are cited below)

**AI tools used** (if any): \[e.g., "Copilot for route handler boilerplate (lines 45-67 in diffs)"\]

------------------------------------------------------------------------

## [1. Protocol & Tasks](#1-protocol--tasks){.header} {#1-protocol--tasks}

### [Link to Needs-Finding (LO2)](#link-to-needs-finding-lo2){.header}

**Week 6 Job Story #1**:

Job Story #1 ("Navigate with Tab"):
When I'm using tab to go through the task app,
I want highlighting around the box I am on,
so I can be certain which action I am taking without taking said action,
because my mouse is broken and I don't want to waste time undoing mistaken actions.

**How Task 1 tests this**: \[1 sentence explaining link\]

**Week 6 Job Story #2**:

Job Story #2 ("Delete with impaired vision"):
When I'm using my eyes to check my task list,
I want to be able to see the tasks clearly to distinguish them,
so I can delete the correct tasks after completing them,
because I am partially blind and it is difficult to distinguish similar colours.

**How Task 2 tests this**: \[1 sentence explaining link\]

**Week 6 Job Story #3**:

Job Story #3 ("Read task with screen reader"):
When I am reading my tasks,
I want to hear all the tasks as I iterate through the list,
so I can remember which tasks need to be completed,
because I am blind.

**How Task 3 tests this**: \[1 sentence explaining link\]

**Week 6 Job Story #4**:

Job Story #4 ("Editing tasks to correct spelling"):
When I am writing tasks for myself and others,
I want to to be able to edit them,
so I can correct any spelling mistakes,
because I make a lot of spelling errors and it is hard to read.

**How Task 4 tests this**: \[1 sentence explaining link\]

**Week 6 Job Story #5**:

Job Story #5 ("Filter tasks by 'buy'"):
When I am about to go shopping,
I want to filter my tasks by the word 'buy',
so I can create a shopping list from all the things I must buy,
because I am in a rush and do not want to check through each individual task.

**How Task 5 tests this**: \[1 sentence explaining link\]

------------------------------------------------------------------------

### [Evaluation Tasks (4-5 tasks)](#evaluation-tasks-4-5-tasks){.header}

#### [Task 1 (T1): Add task with Tab](#task-1-t1-task-name){.header}

-   **Scenario**: Mouse is broken and user wants to "Buy milk"
-   **Action**: Add task with title "Buy milk" by scrolling page with tab
-   **Success**: Add task box has highlight around it, user enters task without use of mouse, task appears in list, no errors
-   **Target**: 20 seconds
-   **Linked to**: Week 6 Job Story #1 ("Navigate with Tab")

#### [Task 2 (T2): Delete tasks with impaired vision](#task-2-t2-task-name){.header}

-   **Scenario**: User (wearing 4 pairs of sunglasses) has multiple tasks- consisting of "Buy milk", "Buy eggs" and "Drink milk"- and they want to delete
                just 1 of these tasks
-   **Action**: Delete task "Buy milk"
-   **Success**: Only the task "Buy milk" is removed from list, no errors
-   **Target**: 90 seconds
-   **Linked to**: Week 6 Job Story #2 ("Delete with impaired vision")

#### [Task 3 (T3): Read tasks with screen reader](#task-3-t3-task-name){.header}

-   **Scenario**: User is blind and wishes to check tasks- consisting of "Feed fish", "Eat fish", "Buy new fish", "Buy milk"
-   **Action**: Iterate through all tasks and delete task "Buy milk"
-   **Success**: Only task "Buy milk" is removed, no errors
-   **Target**: 110 seconds
-   **Linked to**: Week 6 Job Story #3 ("Read task with screen reader")

#### [Task 4 (T4): Edit task](#task-4-t4-task-name){.header}

-   **Scenario**: User misspelled 3 tasks which say- "bouy melk"(should be "Buy milk"), "Fiid Cot"( should be "Feed cat")
                and "Drenk Malk"( Should be "Drink milk")
-   **Action**: Edit each task to fix spelling errors
-   **Success**: Corrected tasks appear in list, no errors
-   **Target**: 98 seconds
-   **Linked to**: Week 6 Job Story #4 ("Editing tasks to correct spelling")

#### [Task 5 (T5): Filter tasks by 'buy'](#task-5-t5-task-name){.header}

-   **Scenario**: User does not want to waste time checking through all tasks and only wants to check tasks with the word
                'buy' so they can create a shopping list
-   **Action**: Filter all tasks by typing the word 'buy' into the filter box
-   **Success**: Only tasks with the word 'buy' should appear in the list, no errors
-   **Target**: 24 seconds
-   **Linked to**: Week 6 Job Story #5 ("Filter tasks by 'buy'")


------------------------------------------------------------------------

### [Consent Script (They Read Verbatim)](#consent-script-they-read-verbatim){.header}

**Introduction**: "Thank you for participating in my HCI evaluation. This will take about 15 minutes. I'm testing my task management interface, not you. There are no right or wrong answers."

**Rights**:

-   "Your participation is voluntary. You can stop at any time without giving a reason."
-   "Your data will be anonymous. I'll use a code (like P1) instead of your name."
-   "I may take screenshots and notes. I'll remove any identifying information."
-   "Do you consent to participate?" \[Wait for verbal yes\]

**Recorded consent timestamp**: \[e.g., "P1 consented 22/11/2025 14:05"\]
**Recorded consent timestamp**: \[e.g., "P1 consented 22/11/2025 14:05"\]
**Recorded consent timestamp**: \[e.g., "P1 consented 22/11/2025 14:05"\]
**Recorded consent timestamp**: \[e.g., "P1 consented 22/11/2025 14:05"\]
**Recorded consent timestamp**: \[e.g., "P1 consented 22/11/2025 14:05"\]

------------------------------------------------------------------------

## [2. Findings Table](#2-findings-table){.header} {#2-findings-table}

**Instructions**: Fill in this table with 3-5 findings from your pilots. Link each finding to data sources.

::: table-wrapper
  Finding                   Data Source                                   Observation (Quote/Timestamp)       WCAG                 Impact (1-5)   Inclusion (1-5)   Effort (1-5)   Priority
  ------------------------- --------------------------------------------- ----------------------------------- -------------------- -------------- ----------------- -------------- -----------
  SR errors not announced   metrics.csv L47-49 + P2 notes 14:23           P2: "I didn't hear any error"       3.3.1 Level A        5              5                 3              7
  \[Your finding 2\]        \[Link to metrics.csv line OR pilot notes\]   \[Participant quote + timestamp\]   \[WCAG criterion\]   \[1-5\]        \[1-5\]           \[1-5\]        \[Score\]
  \[Your finding 3\]                                                                                                                                                               
  \[Your finding 4\]                                                                                                                                                               
  \[Your finding 5\]                                                                                                                                                               
:::

**Priority formula**: (Impact + Inclusion) - Effort

**Top 3 priorities for redesign**:

1.  \[Finding #X - Priority score Y\]
2.  \[Finding #X - Priority score Y\]
3.  \[Finding #X - Priority score Y\]

**How to complete this table** (decision tree):

1.  **Identify finding**: From pilot observations, metrics.csv anomalies (high times, errors), or WCAG violations
2.  **Link data source**: Cite specific metrics.csv line numbers (e.g., "L47-49") OR pilot notes timestamps (e.g., "P2 notes 14:23")
3.  **Check WCAG**: If accessibility-related, find the criterion using [W3C WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)
4.  **Score priority**: Use [Week 10 Lab 1 prioritisation scales](../wk10/wk10-lab1-analysis-prioritisation.html#prioritisation-framework) to rate Impact (1-5), Inclusion (1-5), Effort (1-5), then calculate Priority = (Impact + Inclusion) - Effort

------------------------------------------------------------------------

## [3. Pilot Metrics (metrics.csv)](#3-pilot-metrics-metricscsv){.header} {#3-pilot-metrics-metricscsv}

**Instructions**: Paste your raw CSV data here OR attach metrics.csv file

``` csv
ts_iso,session_id,request_id,task_code,step,outcome,ms,http_status,js_mode
2025-11-22T14:18:23.456Z,P1_a7f3,req_001,T1_add,success,,890,200,on
[Your metrics data here - all rows from Logger.kt output]
```

**Participant summary**:

-   **P1**: \[Variant - e.g., "Standard mouse + HTMX"\]
-   **P2**: \[Variant - e.g., "Keyboard-only, HTMX-on"\]
-   **P3** (if applicable): \[Variant\]
-   **P4** (if applicable): \[Variant\]

**Total participants**: \[n=2, 3, or 4\]

------------------------------------------------------------------------

## [4. Implementation Diffs](#4-implementation-diffs){.header} {#4-implementation-diffs}

**Instructions**: Show before/after code for 1-3 fixes. Link each to findings table.

### [Fix 1: \[Fix Name\]](#fix-1-fix-name){.header}

**Addresses finding**: \[Finding #X from table above\]

**Before** (\[file path:line number\]):

``` kotlin
// ❌ Problem code
[Paste your original code here]
```

**After** (\[file path:line number\]):

``` kotlin
// ✅ Fixed code
[Paste your improved code here]
```

**What changed**: \[1 sentence - what you added/removed/modified\]

**Why**: \[1 sentence - which WCAG criterion or usability issue this fixes\]

**Impact**: \[1-2 sentences - how this improves UX, who benefits\]

------------------------------------------------------------------------

### [Fix 2: \[Fix Name\]](#fix-2-fix-name){.header}

**Addresses finding**: \[Finding #X\]

**Before**:

``` kotlin
[Original code]
```

**After**:

``` kotlin
[Fixed code]
```

**What changed**:

**Why**:

**Impact**:

------------------------------------------------------------------------

\[Add Fix 3 if applicable\]

------------------------------------------------------------------------

## [5. Verification Results](#5-verification-results){.header} {#5-verification-results}

### [Part A: Regression Checklist (20 checks)](#part-a-regression-checklist-20-checks){.header}

**Instructions**: Test all 20 criteria. Mark pass/fail/n/a + add notes.

::: table-wrapper
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| Check            | Criterion                             | Level       | Result            | Notes                                                          |
+==================+=======================================+=============+===================+================================================================+
| **Keyboard (5)** |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K1               | 2.1.1 All actions keyboard accessible | A           | \[pass/fail\]     | \[e.g., "Tested Tab/Enter on all buttons"\]                    |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K2               | 2.4.7 Focus visible                   | AA          | \[pass/fail\]     | \[e.g., "2px blue outline on all interactive elements"\]       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K3               | No keyboard traps                     | A           | \[pass/fail\]     | \[e.g., "Can Tab through filter, edit, delete without traps"\] |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K4               | Logical tab order                     | A           | \[pass/fail\]     | \[e.g., "Top to bottom, left to right"\]                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K5               | Skip links present                    | AA          | \[pass/fail/n/a\] | \[e.g., "Skip to main content works"\]                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Forms (3)**    |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F1               | 3.3.2 Labels present                  | A           | \[pass/fail\]     | \[e.g., "All inputs have or aria-label"\]                      |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F2               | 3.3.1 Errors identified               | A           | \[pass/fail\]     | \[e.g., "Errors have role=alert (FIXED in Fix #1)"\]           |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F3               | 4.1.2 Name/role/value                 | A           | \[pass/fail\]     | \[e.g., "All form controls have accessible names"\]            |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Dynamic (3)**  |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D1               | 4.1.3 Status messages                 | AA          | \[pass/fail\]     | \[e.g., "Status div has role=status"\]                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D2               | Live regions work                     | AA          | \[pass/fail\]     | \[e.g., "Tested with NVDA, announces 'Task added'"\]           |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D3               | Focus management                      | A           | \[pass/fail\]     | \[e.g., "Focus moves to error summary after submit"\]          |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **No-JS (3)**    |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N1               | Full feature parity                   | ---         | \[pass/fail\]     | \[e.g., "All CRUD ops work without JS"\]                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N2               | POST-Redirect-GET                     | ---         | \[pass/fail\]     | \[e.g., "No double-submit on refresh"\]                        |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N3               | Errors visible                        | A           | \[pass/fail\]     | \[e.g., "Error summary shown in no-JS mode"\]                  |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Visual (3)**   |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V1               | 1.4.3 Contrast minimum                | AA          | \[pass/fail\]     | \[e.g., "All text 7.1:1 (AAA) via CCA"\]                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V2               | 1.4.4 Resize text                     | AA          | \[pass/fail\]     | \[e.g., "200% zoom, no content loss"\]                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V3               | 1.4.11 Non-text contrast              | AA          | \[pass/fail\]     | \[e.g., "Focus indicator 4.5:1"\]                              |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Semantic (3)** |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S1               | 1.3.1 Headings hierarchy              | A           | \[pass/fail\]     | \[e.g., "h1 → h2 → h3, no skips"\]                             |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S2               | 2.4.1 Bypass blocks                   | A           | \[pass/fail\]     | \[e.g., "                                                      |
|                  |                                       |             |                   |                                                                |
|                  |                                       |             |                   | ::: {role="main"}                                              |
|                  |                                       |             |                   | landmark,                                                      |
|                  |                                       |             |                   |                                                                |
|                  |                                       |             |                   | for filter"\]                                                  |
|                  |                                       |             |                   | :::                                                            |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S3               | 1.1.1 Alt text                        | A           | \[pass/fail\]     | \[e.g., "No images in interface OR all have alt"\]             |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
:::

**Summary**: \[X/20 pass\], \[Y/20 fail\] **Critical failures** (if any): \[List any Level A fails\]

------------------------------------------------------------------------

### [Part B: Before/After Comparison](#part-b-beforeafter-comparison){.header}

**Instructions**: Compare Week 9 baseline (pre-fix) to Week 10 (post-fix). Show improvement.

::: table-wrapper
  Metric                    Before (Week 9, n=X)   After (Week 10, n=Y)   Change             Target Met?
  ------------------------- ---------------------- ---------------------- ------------------ -------------
  SR error detection        \[e.g., 0/2 (0%)\]     \[e.g., 2/2 (100%)\]   \[e.g., +100%\]    \[✅/❌\]
  Validation error rate     \[e.g., 33%\]          \[e.g., 0%\]           \[e.g., -33%\]     \[✅/❌\]
  Median time \[Task X\]    \[e.g., 1400ms\]       \[e.g., 1150ms\]       \[e.g., -250ms\]   \[✅/❌\]
  WCAG \[criterion\] pass   \[fail\]               \[pass\]               \[--- \]           \[✅/❌\]
:::

**Re-pilot details**:

-   **P5** (post-fix): \[Variant - e.g., "Screen reader user, NVDA + keyboard"\] - \[Date piloted\]
-   **P6** (if applicable): \[Variant\] - \[Date\]

**Limitations / Honest reporting**: \[If metrics didn't improve or only modestly: explain why. Small sample size? Wrong fix? Needs more iteration? Be honest - valued over perfect results.\]

------------------------------------------------------------------------

## [6. Evidence Folder Contents](#6-evidence-folder-contents){.header} {#6-evidence-folder-contents}

**Instructions**: List all files in your evidence/ folder. Provide context.

### [Screenshots](#screenshots){.header}

::: table-wrapper
  Filename                    What it shows                           Context/Link to finding
  --------------------------- --------------------------------------- --------------------------------------
  before-sr-error.png         Error message without role="alert"      Finding #1 - SR errors not announced
  after-sr-error.png          Error message WITH role="alert" added   Fix #1 verification
  regression-axe-report.png   axe DevTools showing 0 violations       Verification Part A
  \[your-screenshot-3.png\]   \[Description\]                         \[Which finding/fix this supports\]
:::

**PII check**:

-   All screenshots cropped to show only relevant UI
-   Browser bookmarks/tabs not visible
-   Participant names/emails blurred or not visible

------------------------------------------------------------------------

### [Pilot Notes](#pilot-notes){.header}

**Instructions**: Attach pilot notes as separate files (P1-notes.md, P2-notes.md, etc.). Summarize key observations here.

**P1** (\[ Variant - e.g., "Standard mouse + HTMX"\]):

-   **Key observation 1**: \[Quote + timestamp - e.g., "Struggled with filter button (09:47)"\]
-   **Key observation 2**: \[Quote + timestamp\]

**P2** (\[Variant\]):

-   **Key observation 1**: \[Quote + timestamp\]
-   **Key observation 2**: \[Quote + timestamp\]

\[Repeat for P3, P4 if applicable\]

------------------------------------------------------------------------

## [Evidence Chain Example (Full Trace)](#evidence-chain-example-full-trace){.header}

**Instructions**: Pick ONE finding and show complete evidence trail from data → fix → verification.

**Finding selected**: \[e.g., "Finding #1 - SR errors not announced"\]

**Evidence trail**:

1.  **Data**: metrics.csv lines 47-49 show P2 (SR user) triggered validation_error 3 times
2.  **Observation**: P2 pilot notes timestamp 14:23 - Quote: "I don't know if it worked, didn't hear anything"
3.  **Screenshot**: before-sr-error.png shows error message has no role="alert" or aria-live
4.  **WCAG**: 3.3.1 Error Identification (Level A) violation - errors not programmatically announced
5.  **Prioritisation**: findings-table.csv row 1 - Priority score 7 (Impact 5 + Inclusion 5 - Effort 3)
6.  **Fix**: implementation-diffs.md Fix #1 - Added role="alert" + aria-live="assertive" to error span
7.  **Verification**: verification.csv Part A row F2 - 3.3.1 now PASS (tested with NVDA)
8.  **Before/after**: verification.csv Part B - SR error detection improved from 0% to 100%
9.  **Re-pilot**: P5 (SR user) pilot notes - "Heard error announcement immediately, corrected and succeeded"

**Complete chain**: Data → Observation → Interpretation → Fix → Verification ✅

------------------------------------------------------------------------

## [Submission Checklist](#submission-checklist){.header}

Before submitting, verify:

**Files**:

-   This completed template (submission-template.md)
-   metrics.csv (or pasted into Section 3)
-   Pilot notes (P1-notes.md, P2-notes.md, etc. OR summarised in Section 6)
-   Screenshots folder (all images referenced above)
-   Privacy statement signed (top of document)

**Evidence chains**:

-   findings-table.csv links to metrics.csv lines AND/OR pilot notes timestamps
-   implementation-diffs.md references findings from table
-   verification.csv Part B shows before/after for fixes

**Quality**:

-   No PII in screenshots (checked twice!)
-   Session IDs anonymous (P1_xxxx format, not real names)
-   Honest reporting (limitations acknowledged if metrics didn't improve)
-   WCAG criteria cited specifically (e.g., "3.3.1" not just "accessibility")

**Pass criteria met**:

-   n=2+ participants (metrics.csv has 2+ session IDs)
-   3+ findings with evidence (findings-table.csv complete)
-   1-3 fixes implemented (implementation-diffs.md shows code)
-   Regression complete (verification.csv has 20 checks)
-   Before/after shown (verification.csv Part B has data)

------------------------------------------------------------------------

**Ready to submit?** Upload this file + evidence folder to Gradescope by end of Week 10.

**Estimated completion time**: 12-15 hours across Weeks 9-10

**Good luck!**
