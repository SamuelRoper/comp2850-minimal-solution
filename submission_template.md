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

**Recorded consent timestamp**: \[e.g., "p1_0001 consented 04/12/2025 17:33"\]
**Recorded consent timestamp**: \[e.g., "p2_0002 consented 04/12/2025 18:05"\]
**Recorded consent timestamp**: \[e.g., "p3_0003 consented 04/12/2025 18:46"\]
**Recorded consent timestamp**: \[e.g., "p4_0004 consented 06/12/2025 16:43"\]
**Recorded consent timestamp**: \[e.g., "p5_0005 consented 06/12/2025 21:06"\]

------------------------------------------------------------------------

## [2. Findings Table](#2-findings-table){.header} {#2-findings-table}

**Instructions**: Fill in this table with 3-5 findings from your pilots. Link each finding to data sources.

::: table-wrapper
  Finding                   Data Source                                   Observation (Quote/Timestamp)       WCAG                 Impact (1-5)   Inclusion (1-5)   Effort (1-5)   Priority
  ------------------------- --------------------------------------------- ----------------------------------- -------------------- -------------- ----------------- -------------- -----------
  Purpose of web app unclear   p1_0001 notes 17:53           p1_0001: "Don't know what it's supposed to do"       2.1 Level AA        1              1                1               1
  Unclear when buttons had worked        p2_0002 notes 18:19 + p3_0003 notes 19:05   p2_0002: "Buttons weren't very responsive and gave no indication they were working" + p3_0003: "Had to click save a couple of times"   2.1 Level AA   3        1         3        1
  Could only scroll page with keyboard in one direction        p2_0002 notes 18:20        p2_0002: "When cycling with Tab, if you missed something you had to go all the way round"      2.1 level AA     3     3     4     2                                                                                                     
  Easy to accidentally click delete after saving an edit      p3_0003 notes 19:05       p3_0003: "Mouse would hover over 'delete' after 'save' from editing"       2.1 level AA       2     1     3     0 
  User can't see how many tasks they have         p5_0005: "Doesn't say how many tasks there are"              2.1 level AA           1               1               1               1
  User can't easily tell if filter has been applied       p5_0005 notes 21:26       5_0005: "When I filtered the tasks I didn't actually know that it worked" + p5_0005: "If it said for example filtering 4 out of 10 tasks that would be nice"        2.1 level AA        3     1     1     3
  When deleting a task, the screen reader read out the URL of the codespace       p5_0005 notes 21:25       p5_0005: "Screen reader should not read random crap, a bunch of random numbers is confusing"    2.1 level AA      4     3     5     2
:::

**Priority formula**: (Impact + Inclusion) - Effort

**Top 3 priorities for redesign**:

1.  Finding # User can't easily tell if filter has been applied - Priority score 3
2.  Finding # Unclear when buttons had worked - Priority score 1
3.  Finding # Easy to accidentally click delete after saving an edit - Priority score 0

For the finding [Finding # When deleting a task, the screen reader read out the URL of the codespace - Priority score 2] upon researching, I found it appears to be impossible as far as I can tell to make a button partially read out by a screen reader

For the finding [Finding # Could only scroll page with keyboard in one direction - Priority score 2] after a quick search, I realised it was possible to navigate a webpage in the opposite direction with just shift + Tab

For the finding [Finding # Purpose of web app unclear - Priority score 1] it dawned on me after the trials that the purpose of the web app is stated at the top of the page. Myself and p1_0001 appeared to miss this.

For the finding [Finding # User can't see how many tasks they have - Priority score 1] I realised that this is stated at the top of the page. Myself and p5_0005 missed this. There is a slight issue with this however as it only shows how many tasks are displayed, instead of how many there are in total.

Task 1 had a median completion time of 29.68 seconds, which is above the target.

All other tasks had a median completion time below the target.

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
2025-12-04T17:36:57.298516317Z,p1_0001,r_dcd6feb9,T0_list,success,,14,200,off
2025-12-04T17:37:23.599451664Z,p1_0001,r_3ed19450,T3_add,success,,20,200,on
2025-12-04T17:38:00.712219905Z,p1_0001,r_38aef5f4,T4_delete,success,,2,200,on
2025-12-04T17:38:04.351733944Z,p1_0001,r_9962a810,T4_delete,success,,2,200,on
2025-12-04T17:38:32.629321603Z,p1_0001,r_b8466993,T3_add,success,,5,200,on
2025-12-04T17:38:39.509290871Z,p1_0001,r_6ad6d39b,T3_add,success,,15,200,on
2025-12-04T17:38:56.483521067Z,p1_0001,r_5573762c,T3_add,success,,11,200,on
2025-12-04T17:39:50.965894524Z,p1_0001,r_494d8820,T0_list,success,,32,200,off
2025-12-04T17:40:05.945323399Z,p1_0001,r_4d9e5256,T0_list,success,,9,200,off
2025-12-04T17:40:22.575654533Z,p1_0001,r_7fcd10e4,T4_delete,success,,4,200,on
2025-12-04T17:41:37.813811079Z,p1_0001,r_8c8343c8,T4_delete,success,,1,200,on
2025-12-04T17:41:41.914734289Z,p1_0001,r_4109e37e,T4_delete,success,,4,200,on
2025-12-04T17:41:57.060488071Z,p1_0001,r_08cd33ef,T3_add,success,,6,200,on
2025-12-04T17:42:03.670021857Z,p1_0001,r_17aecc1f,T3_add,success,,5,200,on
2025-12-04T17:42:14.945405782Z,p1_0001,r_51c38e78,T3_add,success,,5,200,on
2025-12-04T17:42:22.473614451Z,p1_0001,r_8ad7ef32,T3_add,success,,8,200,on
2025-12-04T17:43:05.488675808Z,p1_0001,r_b6b52777,T0_list,success,,6,200,off
2025-12-04T17:47:02.692073602Z,p1_0001,r_10b91310,T4_delete,success,,2,200,on
2025-12-04T17:47:41.353024282Z,p1_0001,r_fd5566ff,T4_delete,success,,3,200,on
2025-12-04T17:47:42.963376502Z,p1_0001,r_b798b3f9,T4_delete,success,,2,200,on
2025-12-04T17:47:44.970646766Z,p1_0001,r_ceec78ff,T4_delete,success,,2,200,on
2025-12-04T17:48:17.760707563Z,p1_0001,r_da63f23a,T3_add,success,,6,200,on
2025-12-04T17:48:26.293314615Z,p1_0001,r_09f375cb,T3_add,success,,5,200,on
2025-12-04T17:48:40.349443557Z,p1_0001,r_d2b096d3,T3_add,success,,7,200,on
2025-12-04T17:48:47.009433046Z,p1_0001,r_872849f3,T0_list,success,,7,200,off
2025-12-04T17:50:59.705052054Z,p1_0001,r_36a384f9,T3_add,success,,5,200,on
2025-12-04T17:51:08.910645837Z,p1_0001,r_0a5d03c2,T3_add,success,,9,200,on
2025-12-04T17:51:15.475442353Z,p1_0001,r_2bd80653,T3_add,success,,6,200,on
2025-12-04T17:51:20.859834688Z,p1_0001,r_489f8dd7,T0_list,success,,6,200,off
2025-12-04T17:51:45.232696085Z,p1_0001,r_878b868a,T1_filter,success,,13,200,on
2025-12-04T17:51:47.185640791Z,p1_0001,r_020a3d2e,T1_filter,success,,3,200,on
2025-12-04T18:06:10.458467638Z,p2_0002,r_65a15a09,T3_add,success,,3,200,on
2025-12-04T18:06:53.683686576Z,p2_0002,r_23376fca,T3_add,success,,3,200,on
2025-12-04T18:07:02.621170172Z,p2_0002,r_53bd1493,T3_add,success,,4,200,on
2025-12-04T18:07:13.663015071Z,p2_0002,r_69ca9fbd,T1_filter,success,,1,200,off
2025-12-04T18:07:15.516324920Z,p2_0002,r_ed2f73a3,T0_list,success,,5,200,off
2025-12-04T18:08:46.492787171Z,p2_0002,r_08bbbcf6,T4_delete,success,,1,200,on
2025-12-04T18:09:12.995458611Z,p2_0002,r_99bfc891,T4_delete,success,,1,200,on
2025-12-04T18:09:15.079341294Z,p2_0002,r_cfb29910,T4_delete,success,,1,200,on
2025-12-04T18:09:25.424626065Z,p2_0002,r_6e6463da,T3_add,success,,3,200,on
2025-12-04T18:09:31.546391542Z,p2_0002,r_744e8294,T3_add,success,,10,200,on
2025-12-04T18:09:46.704430720Z,p2_0002,r_0dd6c641,T3_add,success,,5,200,on
2025-12-04T18:09:54.510236401Z,p2_0002,r_82897d69,T3_add,success,,4,200,on
2025-12-04T18:12:56.394337735Z,p2_0002,r_8d2a23d5,T4_delete,success,,1,200,on
2025-12-04T18:13:53.599440879Z,p2_0002,r_197f8d5d,T4_delete,success,,2,200,on
2025-12-04T18:13:55.710599629Z,p2_0002,r_e275a72c,T4_delete,success,,2,200,on
2025-12-04T18:13:57.209597982Z,p2_0002,r_f5f4260e,T4_delete,success,,1,200,on
2025-12-04T18:14:17.190507325Z,p2_0002,r_a4f2544e,T3_add,success,,6,200,on
2025-12-04T18:14:26.517900287Z,p2_0002,r_a8701f05,T3_add,success,,3,200,on
2025-12-04T18:14:39.020331292Z,p2_0002,r_31d81796,T3_add,success,,4,200,on
2025-12-04T18:16:38.778995533Z,p2_0002,r_b536e8e9,T3_add,success,,3,200,on
2025-12-04T18:16:46.070440779Z,p2_0002,r_71e62d47,T3_add,success,,14,200,on
2025-12-04T18:16:55.839913150Z,p2_0002,r_d0d64f5b,T3_add,success,,4,200,on
2025-12-04T18:17:02.645796482Z,p2_0002,r_5aebe2f0,T3_add,success,,8,200,on
2025-12-04T18:17:14.246659593Z,p2_0002,r_b6ce45b9,T3_add,success,,4,200,on
2025-12-04T18:17:35.687345494Z,p2_0002,r_b8dafcc1,T1_filter,success,,3,200,on
2025-12-04T18:17:36.264263926Z,p2_0002,r_10b34a61,T1_filter,success,,3,200,on
2025-12-04T18:47:41.725417720Z,p3_0003,r_62417e18,T4_delete,success,,3,200,on
2025-12-04T18:47:42.476997443Z,p3_0003,r_3d7b80f8,T4_delete,success,,1,200,on
2025-12-04T18:47:44.484932351Z,p3_0003,r_6231d721,T4_delete,success,,1,200,on
2025-12-04T18:47:46.863322876Z,p3_0003,r_45a075f0,T4_delete,success,,1,200,on
2025-12-04T18:47:52.115937882Z,p3_0003,r_fde62700,T1_filter,success,,0,200,off
2025-12-04T18:47:54.025628258Z,p3_0003,r_5f805198,T0_list,success,,2,200,off
2025-12-04T18:52:28.726787897Z,p3_0003,r_4efa4757,T3_add,success,,2,200,on
2025-12-04T18:52:35.069748796Z,p3_0003,r_06b0702f,T3_add,success,,2,200,on
2025-12-04T18:52:46.288770321Z,p3_0003,r_d4830892,T3_add,success,,2,200,on
2025-12-04T18:53:03.657730909Z,p3_0003,r_d0f92037,T0_list,success,,4,200,off
2025-12-04T18:55:05.121915506Z,p3_0003,r_1e062017,T4_delete,success,,1,200,on
2025-12-04T18:56:41.089725369Z,p3_0003,r_767f571c,T4_delete,success,,1,200,on
2025-12-04T18:56:43.158571088Z,p3_0003,r_8a36818b,T4_delete,success,,2,200,on
2025-12-04T18:56:53.241143720Z,p3_0003,r_0b6820d9,T3_add,success,,4,200,on
2025-12-04T18:56:57.720823052Z,p3_0003,r_273f6dd1,T3_add,success,,4,200,on
2025-12-04T18:57:02.760660422Z,p3_0003,r_ff42068a,T3_add,success,,2,200,on
2025-12-04T18:57:08.596242447Z,p3_0003,r_5024ca33,T3_add,success,,3,200,on
2025-12-04T18:57:22.261753437Z,p3_0003,r_ecd5a8e0,T0_list,success,,4,200,off
2025-12-04T18:58:22.436649987Z,p3_0003,r_1cb8f092,T1_filter,success,,2,200,on
2025-12-04T18:58:32.652662937Z,p3_0003,r_90336a9a,T1_filter,success,,4,200,on
2025-12-04T18:59:20.600998119Z,p3_0003,r_43b08857,T4_delete,success,,2,200,on
2025-12-04T19:00:06.878915193Z,p3_0003,r_1533c439,T4_delete,success,,1,200,on
2025-12-04T19:00:09.626874168Z,p3_0003,r_02fe21a4,T4_delete,success,,1,200,on
2025-12-04T19:00:19.557745187Z,p3_0003,r_5409da8c,T4_delete,success,,1,200,on
2025-12-04T19:00:39.942183764Z,p3_0003,r_5390a422,T3_add,success,,3,200,on
2025-12-04T19:00:48.610380255Z,p3_0003,r_5736a0ff,T3_add,success,,3,200,on
2025-12-04T19:01:04.284652228Z,p3_0003,r_16966b67,T3_add,success,,4,200,on
2025-12-04T19:01:15.223935384Z,p3_0003,r_03145abd,T1_filter,success,,0,200,off
2025-12-04T19:01:15.582511294Z,p3_0003,r_ed992f8c,T0_list,success,,3,200,off
2025-12-04T19:03:04.598303457Z,p3_0003,r_08ceabf9,T3_add,success,,3,200,on
2025-12-04T19:03:08.628485160Z,p3_0003,r_4df36481,T3_add,success,,4,200,on
2025-12-04T19:03:14.642173429Z,p3_0003,r_df3767c7,T3_add,success,,4,200,on
2025-12-04T19:03:18.264540068Z,p3_0003,r_1dd431a3,T3_add,success,,4,200,on
2025-12-04T19:03:26.738994781Z,p3_0003,r_2e09d5bb,T3_add,success,,3,200,on
2025-12-04T19:03:42.557765037Z,p3_0003,r_ac4e8c9c,T3_add,success,,3,200,on
2025-12-04T19:03:49.231550021Z,p3_0003,r_ed1d8bd8,T3_add,success,,4,200,on
2025-12-04T19:04:19.865332447Z,p3_0003,r_5020aca5,T1_filter,success,,6,200,on
2025-12-04T19:04:21.744056891Z,p3_0003,r_bf26bf33,T1_filter,success,,3,200,on
2025-12-04T19:04:24.115519769Z,p3_0003,r_427807a3,T1_filter,success,,2,200,on
2025-12-04T19:04:25.927413245Z,p3_0003,r_48d75f72,T1_filter,success,,2,200,on
2025-12-04T19:04:27.853733690Z,p3_0003,r_6b8f72d7,T1_filter,success,,2,200,on
2025-12-04T19:04:30.270276006Z,p3_0003,r_1cd45609,T1_filter,success,,5,200,on
2025-12-06T16:41:41.429825134Z,p4_0004,r_ba600f93,T0_list,success,,64,200,off
2025-12-06T16:43:45.785922795Z,p4_0004,r_90a98492,T0_list,success,,15,200,off
2025-12-06T16:45:11.347130077Z,p4_0004,r_0d42ec21,T4_delete,success,,13,200,on
2025-12-06T16:45:14.497163687Z,p4_0004,r_48d2724f,T4_delete,success,,14,200,on
2025-12-06T16:45:18.810593355Z,p4_0004,r_17a244c8,T4_delete,success,,3,200,on
2025-12-06T16:45:21.358696796Z,p4_0004,r_fe11ad3d,T4_delete,success,,5,200,on
2025-12-06T16:45:23.336452411Z,p4_0004,r_4554ec33,T4_delete,success,,2,200,on
2025-12-06T16:45:24.030616331Z,p4_0004,r_4d5c9960,T4_delete,success,,3,200,on
2025-12-06T16:45:26.095743908Z,p4_0004,r_b4f8dcd7,T4_delete,success,,6,200,on
2025-12-06T16:45:29.402574654Z,p4_0004,r_89d6d3b2,T4_delete,success,,2,200,on
2025-12-06T16:45:29.958044097Z,p4_0004,r_5122e6c5,T4_delete,success,,4,200,on
2025-12-06T16:45:30.089422965Z,p4_0004,r_9318cdf5,T1_filter,success,,4,200,on
2025-12-06T16:45:32.620783612Z,p4_0004,r_f4103a29,T4_delete,success,,1,200,on
2025-12-06T16:45:35.975304970Z,p4_0004,r_ff4d1867,T1_filter,success,,1,200,off
2025-12-06T16:45:37.055084251Z,p4_0004,r_93dd5e14,T0_list,success,,6,200,off
2025-12-06T16:46:09.273070804Z,p4_0004,r_3d903400,T3_add,success,,14,200,on
2025-12-06T16:47:01.468750523Z,p4_0004,r_30dfe5f5,T3_add,success,,8,200,on
2025-12-06T16:47:06.896989979Z,p4_0004,r_2cbb81a0,T3_add,success,,4,200,on
2025-12-06T16:47:12.681234522Z,p4_0004,r_aa4ea468,T3_add,success,,5,200,on
2025-12-06T16:47:17.252338069Z,p4_0004,r_0c51d1ff,T3_add,success,,6,200,on
2025-12-06T16:47:25.089378692Z,p4_0004,r_b26c074f,T4_delete,success,,6,200,on
2025-12-06T16:47:30.682961858Z,p4_0004,r_5add1e5c,T0_list,success,,8,200,off
2025-12-06T16:51:33.460698414Z,p4_0004,r_cfe66824,T0_list,success,,9,200,off
2025-12-06T16:54:00.710215418Z,p4_0004,r_c1663596,T4_delete,success,,2,200,on
2025-12-06T16:54:02.476594717Z,p4_0004,r_4eb95549,T4_delete,success,,1,200,on
2025-12-06T16:54:03.282278777Z,p4_0004,r_d13530b8,T4_delete,success,,2,200,on
2025-12-06T16:54:06.223297934Z,p4_0004,r_2f4f2d9b,T4_delete,success,,2,200,on
2025-12-06T16:54:25.478558456Z,p4_0004,r_b987fbaa,T3_add,success,,4,200,on
2025-12-06T16:54:29.817078201Z,p4_0004,r_7b588dc9,T3_add,success,,5,200,on
2025-12-06T16:54:38.361973315Z,p4_0004,r_a8e1e099,T3_add,success,,3,200,on
2025-12-06T16:55:32.164638024Z,p4_0004,r_3f1b2b88,T0_list,success,,5,200,off
2025-12-06T16:58:13.810808255Z,p4_0004,r_5908d66a,T4_delete,success,,2,200,on
2025-12-06T16:59:02.027884813Z,p4_0004,r_7b0a0432,T4_delete,success,,1,200,on
2025-12-06T17:00:08.671755521Z,p4_0004,r_7b675732,T4_delete,success,,1,200,on
2025-12-06T17:00:23.916040150Z,p4_0004,r_0f67fa28,T3_add,success,,4,200,on
2025-12-06T17:00:40.911341709Z,p4_0004,r_e41cfa8d,T3_add,success,,4,200,on
2025-12-06T17:00:48.789190986Z,p4_0004,r_29352e12,T3_add,success,,4,200,on
2025-12-06T17:01:43.622482025Z,p4_0004,r_ba968c15,T0_list,success,,4,200,off
2025-12-06T17:04:38.812759839Z,p4_0004,r_02b3cd3c,T3_add,success,,4,200,on
2025-12-06T17:04:45.774789428Z,p4_0004,r_7ef06341,T3_add,success,,4,200,on
2025-12-06T17:04:49.457281049Z,p4_0004,r_08b5fd71,T3_add,success,,10,200,on
2025-12-06T17:04:53.348723547Z,p4_0004,r_f2e115e5,T3_add,success,,7,200,on
2025-12-06T17:04:58.018006693Z,p4_0004,r_8d928f59,T3_add,success,,5,200,on
2025-12-06T17:05:05.613215398Z,p4_0004,r_62cbc061,T3_add,success,,13,200,on
2025-12-06T17:05:11.902645062Z,p4_0004,r_68f51dc1,T3_add,success,,6,200,on
2025-12-06T17:05:39.218187627Z,p4_0004,r_fe9f1434,T1_filter,success,,8,200,on
2025-12-06T17:05:39.583781196Z,p4_0004,r_33c435a3,T1_filter,success,,4,200,on
2025-12-06T17:05:54.755526071Z,p4_0004,r_d33e3ee6,T1_filter,success,,3,200,on
2025-12-06T21:07:53.962808052Z,p5_0005,r_357fbeb8,T0_list,success,,274,200,off
2025-12-06T21:09:02.721934453Z,p5_0005,r_bb3f8782,T3_add,success,,46,200,on
2025-12-06T21:09:23.680681806Z,p5_0005,r_3d8e9c53,T4_delete,success,,8,200,on
2025-12-06T21:09:31.707179040Z,p5_0005,r_bfe72100,T3_add,success,,8,200,on
2025-12-06T21:09:37.852656709Z,p5_0005,r_25fef5c7,T3_add,success,,7,200,on
2025-12-06T21:09:53.213624085Z,p5_0005,r_0a0438f7,T3_add,success,,10,200,on
2025-12-06T21:11:13.673605138Z,p5_0005,r_a6697ef0,T4_delete,success,,2,200,on
2025-12-06T21:12:40.756653197Z,p5_0005,r_98fd0ad5,T4_delete,success,,2,200,on
2025-12-06T21:12:43.010809368Z,p5_0005,r_5b94c742,T4_delete,success,,4,200,on
2025-12-06T21:12:53.010726519Z,p5_0005,r_7d73c494,T3_add,success,,6,200,on
2025-12-06T21:12:58.311133017Z,p5_0005,r_951b9f68,T3_add,success,,7,200,on
2025-12-06T21:13:05.897885464Z,p5_0005,r_ee24f7f3,T3_add,success,,9,200,on
2025-12-06T21:13:12.213032932Z,p5_0005,r_7a95607c,T3_add,success,,8,200,on
2025-12-06T21:13:18.358597371Z,p5_0005,r_5e936589,T0_list,success,,18,200,off
2025-12-06T21:15:47.992405099Z,p5_0005,r_709342c0,T4_delete,success,,3,200,on
2025-12-06T21:16:33.831169900Z,p5_0005,r_b1ea0146,T4_delete,success,,3,200,on
2025-12-06T21:16:35.294859569Z,p5_0005,r_9526f2ef,T4_delete,success,,2,200,on
2025-12-06T21:16:36.356429180Z,p5_0005,r_a7c44ebd,T4_delete,success,,2,200,on
2025-12-06T21:17:10.596243485Z,p5_0005,r_f922ab73,T3_add,success,,5,200,on
2025-12-06T21:17:18.048504415Z,p5_0005,r_19b19116,T3_add,success,,5,200,on
2025-12-06T21:17:24.356557127Z,p5_0005,r_0b9eceda,T3_add,success,,17,200,on
2025-12-06T21:19:19.512478385Z,p5_0005,r_cb7dce3d,T3_add,success,,6,200,on
2025-12-06T21:19:24.677526826Z,p5_0005,r_cdfccca3,T3_add,success,,9,200,on
2025-12-06T21:19:28.601441738Z,p5_0005,r_5af72137,T3_add,success,,8,200,on
2025-12-06T21:19:31.164242384Z,p5_0005,r_b36865ca,T3_add,success,,11,200,on
2025-12-06T21:19:36.793848233Z,p5_0005,r_2219c942,T3_add,success,,7,200,on
2025-12-06T21:19:45.266662262Z,p5_0005,r_18a7a99e,T3_add,success,,8,200,on
2025-12-06T21:19:49.957039124Z,p5_0005,r_cbf2ecaa,T3_add,success,,9,200,on
2025-12-06T21:20:16.497428676Z,p5_0005,r_1c2eaf6f,T1_filter,success,,13,200,on
2025-12-06T21:20:19.720199774Z,p5_0005,r_e076109e,T1_filter,success,,4,200,on
2025-12-06T21:22:21.352663981Z,p5_0005,r_5be56630,T1_filter,success,,11,200,on
2025-12-06T21:22:22.693899319Z,p5_0005,r_60dbaef2,T1_filter,success,,5,200,on
2025-12-06T21:22:23.781753819Z,p5_0005,r_54f78c9f,T1_filter,success,,3,200,on
2025-12-06T21:22:24.939186017Z,p5_0005,r_2f484782,T1_filter,success,,8,200,on
2025-12-06T21:22:25.930247057Z,p5_0005,r_5230d244,T1_filter,success,,3,200,on
2025-12-06T21:22:33.899563683Z,p5_0005,r_562a5c25,T1_filter,success,,4,200,on
2025-12-06T21:22:33.968850542Z,p5_0005,r_823323ae,T1_filter,success,,6,200,on
2025-12-06T21:22:35.748307896Z,p5_0005,r_b9b59386,T1_filter,success,,5,200,on
2025-12-06T21:22:35.817575719Z,p5_0005,r_d80b2608,T1_filter,success,,9,200,on
2025-12-06T21:23:03.060390930Z,p5_0005,r_43c484ed,T1_filter,success,,8,200,on
2025-12-06T21:23:05.167476116Z,p5_0005,r_27ac7edd,T1_filter,success,,6,200,on
2025-12-06T21:23:06.827333016Z,p5_0005,r_83392f97,T1_filter,success,,11,200,on

```

**Participant summary**:

-   **p1_0001**: Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on
-   **p2_0002**: Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on
-   **p3_0003**: Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on
-   **p4_0004**: Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on
-   **p5_0005**: Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on

**Total participants**: n=5

------------------------------------------------------------------------

## [4. Implementation Diffs](#4-implementation-diffs){.header} {#4-implementation-diffs}

**Instructions**: Show before/after code for 1-3 fixes. Link each to findings table.

### [Fix 1: Show how many filtered tasks](#fix-1-fix-name){.header}

**Addresses finding**: Finding # 'User can't easily tell if filter has been applied' from table above

**Before** (src/main/resources/tasks/index.peb 60-82):

``` html
{# Search/Filter Tasks Form - Week 8 #}
    <section aria-labelledby="search-heading">
        <h2 id="search-heading">Filter Tasks</h2>

        <form action="/tasks" method="get"
              hx-get="/tasks/fragment"
              hx-trigger="keyup changed delay:300ms from:#search-query, submit"
              hx-target="#task-area"
              hx-swap="innerHTML"
              hx-push-url="true">

            <label for="search-query">Filter by title</label>
            <input type="search"
                   id="search-query"
                   name="q"
                   placeholder="Type to filter..."
                   aria-describedby="search-hint"
                   value="{{ query | default('') }}">

            <small id="search-hint">Filters tasks as you type; works without JavaScript.</small>
            <button type="submit">Apply Filter</button>
            <label for="search-query">Filtering {{ page.items|length }} out of {{ page.totalItems }} tasks by {{ query }}</label>
        </form>
    </section>
```

**After** (src/main/resources/tasks/index.peb line 81):

``` html
// ✅ Fixed code
<p>Filtering {{ page.items|length }} out of {{ page.totalItems }} tasks by {{ query }}</p>
```

**What changed**: I added a new line of text that shows the user how many tasks are being filtered and by what query

**Why**: This is to help show the user that the filter has been applied

**Impact**: Now whenever people use the filter and refresh the page, it will be obvious that the filter has worked, which can prevent confusion. It also means that a user can realise they have more tasks than what is being displayed on screen in their list.

------------------------------------------------------------------------

### [Fix 2: Make button response clearer](#fix-2-fix-name){.header}

**Addresses finding**: Finding # Unclear when buttons had worked

**Before**:

``` css
/* Override Pico.css button color for WCAG 1.4.3 AA compliance */
    button[type="submit"],
    button {
      color: white !important; /* White text on blue background for better contrast */
    }
```

**After**:

``` css
/* Override Pico.css button color for WCAG 1.4.3 AA compliance */
    button[type="submit"],
    button {
      color: white !important; /* White text on blue background for better contrast */
    }
    button:hover {
      color: black !important;
    }
    button:focus {
      color: black !important;
    }
    button:active {
      background-color: #ffaa00 !important;
    }
```

**What changed**: When hovering over or selecting a button, its text goes black. Also when activating a button its background will go orange.

**Why**: This is to make it clearer to users which button they are on and if it has responded to their usage of it. Many of the people I studied appeared to struggle to recognise when a button had been clicked, or if it was unresponsive.

**Impact**: This makes it far clearer when using buttons, especially for the visually impaired, where their mouse or focus is. The turning orange when being used is useful for everyone to show how responsive the buttons are.

------------------------------------------------------------------------

Finding # Easy to accidentally click delete after saving an edit is incredibly low priority, as deleting a task creates an alert that you have to select to delete the task, so accidentally deleting a task is unlikely. Furthermore, it would be very difficult to change the location of the save button as I am unsure of where in the code I would need to change to swap the input text box anad the save button. It is also undesirable as the input text box appears right where the task was, which is very elegant.

Overall I believe there is no demand for making such a change.

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
| K1               | 2.1.1 All actions keyboard accessible | A           | pass              |  Tested Tab/Enter on all buttons                               |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K2               | 2.4.7 Focus visible                   | AA          | pass              |  2px blue outline on all interactive elements                  |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K3               | No keyboard traps                     | A           | pass              |  Can Tab through filter, edit, delete without traps            |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K4               | Logical tab order                     | A           | pass              |  Top to bottom, left to right                                  |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K5               | Skip links present                    | AA          | pass              |  Skip to main content works                                    |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Forms (3)**    |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F1               | 3.3.2 Labels present                  | A           | pass              |  All inputs have or aria-label                                 |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F2               | 3.3.1 Errors identified               | A           | pass              |  Errors have role=alert (FIXED in Fix #1)                      |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F3               | 4.1.2 Name/role/value                 | A           | pass              |  All form controls have accessible names                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Dynamic (3)**  |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D1               | 4.1.3 Status messages                 | AA          | pass              |  Status div has role=status                                    |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D2               | Live regions work                     | AA          | fail              |  Tested with Orca, only works for deleting                     |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D3               | Focus management                      | A           | fail              | Focus does not move to error summary after submit              |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **No-JS (3)**    |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N1               | Full feature parity                   | ---         | fail              | All CRUD ops work without JS except edit                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N2               | POST-Redirect-GET                     | ---         | pass              | No double-submit on refresh                                    |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N3               | Errors visible                        | A           | fail              | Error of task name too long not shown in no-JS mode            |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Visual (3)**   |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V1               | 1.4.3 Contrast minimum                | AA          | pass              | All text 7.1:1 (AAA) via CCA                                   |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V2               | 1.4.4 Resize text                     | AA          | pass              | 200% zoom, no content loss                                     |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V3               | 1.4.11 Non-text contrast              | AA          | pass              | Focus indicator 4.5:1                                          |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Semantic (3)** |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S1               | 1.3.1 Headings hierarchy              | A           | pass              | h1 → h2 → h3, no skips                                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S2               | 2.4.1 Bypass blocks                   | A           | pass              |                                                                |
|                  |                                       |             |                   | <a class="skip-link" href="#main">Skip to main content</a>     |
|                  |                                       |             |                   |                                                                |
|                  |                                       |             |                   |                                                                |
|                  |                                       |             |                   |                                                                |
|                  |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S3               | 1.1.1 Alt text                        | A           | pass              | No images in interface                                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
:::

**Summary**: 16/20 pass, 4/20 fail **Critical failures** (if any): N/A

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

**p1_0001** (Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on):

-   **Key observation 1**: 'Blind users are going to struggle'()
-   **Key observation 2**: 'I don't know what its supposed to do'()

**p2_0002** (Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on):

-   **Key observation 1**: 'Buttons weren't very responsive and gave no indication they were working'()
-   **Key observation 2**: 'When cycling with Tab, if you missed something you had to go all the way round, so a way to go up for example with the up arrow key would be much better'()

**p3_0003** (Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on):

-   **Key observation 1**: 'Mouse would hover over 'delete' after 'save' from editing'()
-   **Key observation 2**: 'Had to click save a couple times'()

**p4_0004** (Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on):

-   **Key observation 1**: 'I like the colour contrast, makes it easy to use, I like how it stands out'

**p5_0005** (Task1 Keyboard-only JS on, Task2 impaired vision JS on, Task3 Blind Screenreader JS on, Task4 Standard Mouse and Keyboard JS on, Task5 Standard Mouse and Keyboard JS on):

-   **Key observation 1**: 'Screen reader should not read random crap, a bunch of random numbers is confusing'
-   **Key observation 2**: 'When I filtered the tasks I didn't actually know that it worked'


Was unsure of how to attach pilot notes files, so they are below.

p1_0001-notes:

Consented: 04/12/2025 17:33
Task 1: 17.33 seconds
Task 2: 13.62 seconds
Task 3: 204.39 seconds
Task 4: 52.75 seconds
Task 5: 8.57 seconds

Quotes:

'Blind Users are going to struggle', 17:52
'[The web app was]Plain and simple', 17:52
'I don't know what its supposed to do', 17:53
'Tasks are clearly labelled', 17:53


p2_0002-notes:

Consented: 04/12/2025 18:05
Task 1: 34.88 seconds
Task 2: 11.23 seconds
Task 3: 62.52 seconds
Task 4: 45.00 seconds
Task 5: 5.79 seconds

Quotes:

'Voice was terrible and hard to listen to', 18:19
'Spoke too quickly and no pauses in between words', 18:19
'Buttons weren't very responsive and gave no indication they were working', 18:19
'When cycling with Tab, if you missed something you had to go all the way round, so a way to go up- for example with the up arrow key would be much better', 18:20


p3_0003-notes:

Consented: 04/12/2025 18:46
Task 1: 180 seconds
Task 2: 72.63 seconds
Task 3: 72.43 seconds
Task 4: 59.27 seconds
Task 5: 10.29 seconds

Quotes:

'Mouse would hover over 'delete' after 'save' from editing', 19:05
'Had to click save a couple times', 19:05
'Once I figured it out it was pretty straight forward', 19:05
'Quite confusing at first but get into rhythm of it quite quickly', 19:05


p4_0004-notes:

Consented: 06/12/2025 16:43
Task 1: 29.68 seconds
Task 2: 180 seconds
Task 3: 170.00 seconds
Task 4: 128.41 seconds
Task 5: 14.58 seconds

Quotes:

'Straight forward', 17:07
'I'm not that computer literate so it was hard to see what I was doing by just following the voice'( referring to task 3), 17:07
'I like the colour contrast, makes it easy to use. I like how it stands out', 17:08
'Easy to add and filter tasks', 17:08


p5_0005-notes:

Consented: 06/12/2025 21:06
Task 1: 15.89 seconds
Task 2: 12.80 seconds
Task 3: 100.45 seconds
Task 4: 49.15 seconds
Task 5: 7.96 seconds

Quotes:

'Screen reader should not read random crap, a bunch of random numbers is confusing', 21:25
'When I filtered the tasks I didn't actually know that it worked', 21:26
'Doesn't say how many tasks there are', 21:26
'If it said filtering 4 out of 10 tasks that would be good', 21:26

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
