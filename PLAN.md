# Matthew's AI credentials and revenue-variance agent plan

Prepared October 23, 2026. Updated October 28, 2026 for the Revenue Variance Investigation Agent and a five-to-six-hour weekly study budget. Start Week 1, Night 1 whenever you begin; weeks are learning blocks, not calendar deadlines.

## What this plan is designed to produce

- Two LinkedIn Learning certificates of completion.
- Microsoft Applied Skills: Generate reports with AI research agents, if the practical assessment is passed.
- Completion of the five courses listed as prerequisites for LangChain Certified Agent Engineer.
- LangChain Certified Agent Engineer, when prepared and the proctored exam is passed.
- Microsoft Certified: AI Transformation Leader (AB-731), if the proctored exam is passed.
- A public portfolio in the existing [revenue-variance repository](https://github.com/mattj8342/revenue-variance): verified financial calculations, an explanation agent, SQL and API integration, an approval workflow, a deployed demonstration, automated checks, and recorded results.

Weeks 1–8 establish Python foundations, revenue-variance calculations, and a first evaluated local agent. Weeks 9–16 deepen Python engineering and add SQL, APIs, workflow automation, deployment of this project, and continuous integration. Weeks 17–18 close course gaps and prepare the portfolio and Microsoft study. Weeks 19–20 reserve space for revision and exam attempts.

The twenty weeks represent roughly 100–120 planned hours. They are estimates, not guaranteed completion or job-readiness dates. Repeat a week when Python, financial analysis, course labs, account access, or practice results need more work. The scope of the revenue-variance project is broader than the earlier monthly-review project, so added weeks also allow time to verify its financial rules.

## The nightly rhythm

Nights 1–5: usually 45–55 minutes. Night 6: 30–40 minutes for practice, demonstration, or catch-up. Night 7: 15–20 minutes of review. Protect five to six hours per week in total, including courses, Python, project work, and exam preparation. These are allocations within that budget, not separate commitments.

On a normal night, spend five minutes reviewing the last note, 35–45 minutes doing the assigned task, and five minutes recording the result and next step. A tired-night minimum is 15 minutes: review one concept, fix one small issue, or write tomorrow's next action. Resume the unfinished task the next night. Do not double the next session to compensate for a missed night.

Assessment and exam weeks redistribute the same weekly budget. Reserve the provider's full uninterrupted assessment time and check-in/setup time; shorten or replace other study sessions that week. Do not add a long exam on top of five full core nights. Defer the attempt when the required uninterrupted block is unavailable.

Python practice continues throughout the project. Use the current task to practice functions, data structures, exceptions, modules, configuration, tests, and debugging; it is not an additional nightly course.

Your learning log should record: date, task, actual minutes, what worked, one thing you can explain, blocker, next step, and the relevant commit/certificate link. Checking a night as complete means its result was produced; course attendance, exam attempts, and credentials earned are separate records.

## The project

Use the existing [Revenue Variance Investigation Agent](https://github.com/mattj8342/revenue-variance). Do not create a replacement monthly-review repository. At this revision the repository contains project design and data specifications; the synthetic dataset, calculations, agent, and integrations remain planned work.

The project repository defines the analytical scope:

- [Business questions and analysis rules](https://github.com/mattj8342/revenue-variance/blob/main/docs/business-questions.md)
- [Synthetic data requirements](https://github.com/mattj8342/revenue-variance/blob/main/docs/data-contract.md)
- [Synthetic data folder notes](https://github.com/mattj8342/revenue-variance/blob/main/data/synthetic/README.md)
- [Learning log](https://github.com/mattj8342/revenue-variance/blob/main/docs/learning-log.md)

The three core questions are:

1. Has settled spend increased or decreased versus the prior comparable period, overall and by customer?
2. How have interchange mix and customer rebates affected the blended gross interchange rate and net revenue yield?
3. Which customers, vendors, or interchange categories show the largest changes in net revenue dollars and net revenue yield?

Version one uses one agent, local synthetic transaction data, and deterministic calculation tools for period comparison, mix and rate investigation, and driver rankings. Python functions or verified queries calculate the metrics; the model selects analytical steps and explains tool results. Include supporting figures, calculation references, limitations, suggested investigations, and human-review status.

Preserve the existing data contract:

- Thirteen generic columns, one fictional settled transaction per row, USD, settlement-date reporting, complete comparison months, and consistent fictional identities.
- Net revenue equals interchange minus customer rebate; it is not profit. Use cent-accurate calculations, such as integer cents or decimal arithmetic.
- Rates use aggregated amounts divided by aggregated settled spend. Rate movement in basis points is 10,000 times the change in the decimal rate.
- Rank customer, vendor, and interchange-category movements separately in dollars and basis points. These are alternative views of the same dollars; do not add their totals together.
- Include all comparable groups with positive spend in both periods in ordinary rate rankings, without a default minimum-dollar cutoff. Show spend beside rate movement.
- Preserve signed refund amounts in totals; show negative-spend refund groups separately. Zero-denominator rates are undefined, and negative net revenue with positive spend remains eligible.
- Distinguish observed changes from hypotheses. A formal volume/mix/rate attribution bridge is a later extension requiring a documented method that reconciles; do not claim one from simple rankings.

Version one remains local and read-only: no changes to analytical source data, automatic distribution, or business actions. Weeks 10–16 introduce a separate sandbox extension. Operational run, approval, and investigation records use their own store; analytical data stays read-only. Human approval is required before creating a sandbox investigation record. No company-system access is required.

Evidence of a finished first version:

- All three business questions answered from verified calculations.
- The eleven evaluation scenarios in the data contract plus unsupported-request checks, with known amounts or expected behavior.
- Numerical reconciliation, rate and refund handling, and actual evaluation results documented.
- A reproducible README, sample output, and a two- to three-minute demonstration.
- Invented data only, following the agreed project contract; credentials kept outside Git.

Evidence of the later engineering extension:

- SQL results agree with the verified local calculations.
- A documented analytical API and an authenticated sandbox integration.
- A repeatable analysis-to-approval-to-investigation workflow with persisted state, bounded retries, and duplicate prevention.
- This portfolio project deployed in a controlled demo environment, with startup instructions and monitoring.
- Automated checks on commits, a demonstrated failure and recovery, and recorded end-to-end results.

Python readiness gate: be able to run and change a function, read a CSV, use dictionaries/lists, install project dependencies, and explain an error. Week 2 supplies a dedicated foundation block; repeat it if needed. Week 9 develops engineering habits further, with practice embedded in the intervening work.

## Quantic and the available study time

The current five-to-six-hour budget is allocated to this plan. Quantic's [MSAIE workload guidance](https://support.quantic.edu/article/1791-how-long-does-the-msaie-take-to-complete) describes consistent study over thirteen months with variable effort and heavier project/exam periods; it does not establish that the degree fits this same weekly budget.

Use the Week 8 and Week 16 reviews to reconsider the degree, actual out-of-pocket cost, and sustainable capacity. Before enrolling, obtain the cohort's normal and peak workload expectations and assignment calendar. If Quantic becomes the main learning commitment, replace or postpone certification study and reduce project scope; do not automatically stack the degree on top of this full schedule.

The revenue-variance problem may provide useful practice alongside a degree, but existing work counts toward Quantic assignments or a capstone only if the school permits it. This plan does not reserve an enrollment date or assume credit for the project.

## Credential choices and resources

1. [Give Your AI Agent Skills — LinkedIn Learning](https://www.linkedin.com/learning/give-your-ai-agent-skills): 46 minutes of video; certificate of completion. Allow extra time for notes and practice.
2. [Agentic AI: Build Your First Agentic AI System — LinkedIn Learning](https://www.linkedin.com/learning/agentic-ai-build-your-first-agentic-ai-system): 65 minutes of video; certificate of completion.
3. [Microsoft Applied Skills: Generate reports with AI research agents](https://learn.microsoft.com/en-us/credentials/applied-skills/generate-reports-with-ai-research-agents/): beginner practical credential using Researcher. [Assessment study guide](https://learn.microsoft.com/en-us/credentials/applied-skills/resources/study-guides/apl-6501). Check practice access early; the assessment itself runs in a supplied lab environment. [Lab FAQ](https://learn.microsoft.com/en-us/credentials/support/assessment-lab-frequently-asked-questions).
4. [Microsoft Certified: AI Transformation Leader — AB-731](https://learn.microsoft.com/en-us/credentials/certifications/ai-transformation-leader/): beginner certification for business decision-makers; no coding required. It covers AI business value, Microsoft AI capabilities, and adoption. The exam is proctored and lists 45 minutes. [Study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ab-731). Use the official preparation and practice links; current training structure may change.
5. [LangChain Certified Agent Engineer](https://academy.langchain.com/pages/certifications-lcae): online-proctored exam covering building, testing, deployment, and monitoring. Currently $99, 120-minute exam, approximately 135-minute seat time, 24-month validity. Read the current rules before booking.

The five LangChain courses:

- [Introduction to LangChain — Python](https://academy.langchain.com/courses/foundation-introduction-to-langchain-python)
- [Introduction to Deep Agents](https://academy.langchain.com/courses/foundation-introduction-to-deepagents)
- [Building Reliable Agents with LangSmith](https://academy.langchain.com/courses/building-reliable-agents)
- [Monitoring Production Agents](https://academy.langchain.com/courses/production-monitoring)
- [Introduction to LangSmith Deployment](https://academy.langchain.com/courses/langsmith-deployment)

Microsoft Learn self-paced training is [free](https://learn.microsoft.com/en-us/training/support/faq). Confirm the current assessment fee, regional Microsoft exam price, practice-product access, and model/deployment charges before spending. Free course enrollment does not mean every external service used for exercises is free. Use a personal Microsoft account for your certification record, as Microsoft recommends, so the record stays accessible through job changes.

Optional later additions: [Microsoft Applied Skills: Build an agent in Microsoft Copilot Studio](https://learn.microsoft.com/en-us/credentials/applied-skills/build-an-agent-in-microsoft-copilot-studio/) is intermediate and needs hands-on preparation; [MCP: Hands-On with Agentic AI](https://www.linkedin.com/learning/model-context-protocol-mcp-hands-on-with-agentic-ai) is a possible third LinkedIn class. They are not additional requirements for these twenty weeks.

Prioritize the LangChain technical exercises and working-project milestones when study time competes. AB-731 supports business/adoption knowledge; keep its preparation flexible around the engineering work. Certification coverage does not establish a universal hiring requirement or guarantee a promotion.

## Exam readiness and LinkedIn visibility

Book each exam independently when you have covered the official objectives, completed the relevant exercises, can explain your practice mistakes, and can handle unfamiliar examples. Repeated practice-question recall alone is not readiness. Follow the issuer's assessment rules and complete assessments independently.

Keep each issuer's exact title. LinkedIn Learning certificates of completion, Microsoft Applied Skills credentials, and Microsoft Certifications are different achievements. Add verification links only after award; use completion dates accurately.

Visibility checkpoints:

- End of Week 1: course certificates added if earned.
- Week 3 or later: Microsoft Applied Skills credential added if passed.
- Week 6: first working revenue-variance agent committed, with supporting metrics.
- Week 8: first evaluated local demonstration and a documented project status.
- Week 16: integrated project demonstration and evidence of SQL, API, workflow, deployment, and automated checks.
- Week 18: repository and demo ready for LinkedIn Featured; draft a post explaining one result and one limitation.
- Weeks 19–20 or later: add exam certifications after official results. Share credentials alongside examples of what you learned or built.

## Night-by-night checklist

### Week 1 — Introductory courses and the existing revenue-variance project

Target: Two introductory course completions if earned, a clear project brief, and a Python starting-point check. Use the existing `revenue-variance` repository; its current contents describe the design, not an implemented agent.

- [ ] **Night 1 — Agent Skills: first half (45–55 min)**

  Watch roughly 25 minutes of Give Your AI Agent Skills. Write three takeaways and describe one reusable revenue-variance analysis skill in your own words.

  Result: Three notes and one skill idea.

- [ ] **Night 2 — Finish Agent Skills (45–55 min)**

  Finish the remaining videos and completion requirements. Save the certificate URL only if awarded. Draft a skill with its purpose, inputs, and expected output using one of the project's business questions.

  Result: A course completion record and a small skill draft, or a precise remaining task.

- [ ] **Night 3 — First Agentic AI System: first half (45–55 min)**

  Watch about 30–35 minutes. Sketch question → read-only tool → calculation → explanation → human review for the Revenue Variance Investigation Agent. Check Microsoft Learn sign-in and access to practice with Researcher.

  Result: A simple agent workflow and an access check.

- [ ] **Night 4 — Continue the second LinkedIn course (45–55 min)**

  Finish Agentic AI: Build Your First Agentic AI System if time allows. Save the completion certificate only if earned and note one design idea to apply. Carry unfinished exercises forward.

  Result: A course progress record and one project design decision.

- [ ] **Night 5 — Review the existing project specification (45–55 min)**

  Open `revenue-variance` and review its README, business questions, data contract, and learning log. Keep its three questions, 13-column synthetic schema, settlement-month scope, and net-revenue definitions. Prepare a local working copy if needed and record the next implementation task; do not create a duplicate portfolio repository.

  Result: A project brief linked to the existing repository and an accurate design-stage status.

- [ ] **Night 6 — Check your Python starting point (30–40 min)**

  Run and change a small function using a dictionary, a list, and a CSV file. Explain its output and one error. Note which topics need attention in Week 2.

  Result: A working script or a specific Python practice list.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Add course certificates to LinkedIn only if earned. Update the learning log with actual time, unfinished work, and the next task. Use a later practice session for course gaps before starting another course.

  Result: An accurate progress record and a focused Week 2 plan.

### Week 2 — Python foundations through revenue-variance examples

Target: Read and validate a small fictional dataset, organize simple functions, and explain failures. Python practice uses the nightly blocks; it is not an extra assignment outside the weekly budget.

- [ ] **Night 1 — Functions, inputs, and return values (45–55 min)**

  Write small functions for a dollar change and interchange minus rebate. Change their inputs and predict the outputs before running them. Explain the difference between returning a value and printing it.

  Result: Two small functions you can modify and explain.

- [ ] **Night 2 — Lists, dictionaries, and grouping (45–55 min)**

  Represent a few invented transactions with lists and dictionaries. Group them by customer and sum a financial amount. Relate the steps to a SQL `GROUP BY` you already understand.

  Result: A working grouping example and a short SQL-to-Python explanation.

- [ ] **Night 3 — CSV files, dates, and financial types (45–55 min)**

  Read a tiny practice CSV using the project's field names. Preserve customer IDs and MCCs as text, parse settlement dates, and use Decimal or integer cents for money. Keep this practice file separate from the reviewed evaluation dataset.

  Result: A loader that preserves the intended data types.

- [ ] **Night 4 — Validation and understandable errors (45–55 min)**

  Check required fields, valid dates, and the identity revenue = interchange minus rebate. Reject a missing amount rather than replacing it with zero. Deliberately introduce one bad record and trace the error to its source.

  Result: A small validation function and one explained failure.

- [ ] **Night 5 — Modules, configuration, and a first automated check (45–55 min)**

  Separate loading and calculation functions into understandable modules. Create a project environment, record dependencies, and keep configuration outside the calculation logic. Add an automated check with a known cent-accurate answer.

  Result: A repeatable command and one passing calculation check.

- [ ] **Night 6 — Recreate and debug an example (30–40 min)**

  Recreate one function without copying the finished answer, then debug a deliberate mistake. Explain its inputs, output, and error behavior; commit only reviewed fictional examples and code.

  Result: A small example you can build and debug independently.

- [ ] **Night 7 — Python readiness review (15–20 min)**

  Check that you can change a function, read a CSV, use lists/dictionaries, install dependencies, and explain an error. Repeat the relevant core nights if these are still unfamiliar. Keep the later course and exam dates flexible.

  Result: A justified decision to advance or repeat Python practice.

### Week 3 — Microsoft Applied Skills and the first synthetic dataset

Target: Attempt the reporting assessment if ready, start LangChain, and produce a small reviewed dataset matching the existing contract. On an assessment week, cap Nights 1, 2, 4, and 5 at 45 minutes, Night 6 at 30 minutes, and Night 7 at 15 minutes. With a 60–90-minute assessment, the total is 285–315 minutes; move unfinished work forward instead of adding hours.

- [ ] **Night 1 — Prepare for AI research reports (45 min this week)**

  Read the Generate reports with AI research agents study guide and linked training. Practice setting scope, audience, objectives, and sources for a report. Use only invented or permitted practice material.

  Result: A report prompt with explicit scope and source requirements.

- [ ] **Night 2 — Practice the complete report workflow (45 min this week)**

  Work through a sample report, refine its structure, check references, and create an executive summary. Review the lab orientation and the assessment's current time requirements. Defer the attempt if preparation or access is incomplete.

  Result: A checked practice report or completed official exercise.

- [ ] **Night 3 — Reporting assessment or focused practice (Reserve 60–90 min)**

  Confirm the full assessment and setup time on the launch page. Complete the assessment independently in one uninterrupted session if ready. If the required block is longer than budgeted, reduce other sessions or move the assessment; if not ready, use 45 minutes for targeted practice.

  Result: An earned Applied Skills credential, or a documented preparation/retry task.

- [ ] **Night 4 — Start Introduction to LangChain — Python (45 min this week)**

  Follow the course setup, keep model credentials outside Git, check provider costs, and run the first example. Explain one function and one model call. Carry setup problems forward before advancing through the course.

  Result: A successful local course example or a specific blocking task.

- [ ] **Night 5 — Generate the first contract-matching dataset (45 min this week)**

  Use the exact 13 fields in `revenue-variance/docs/data-contract.md` to create a small fictional transaction CSV in `data/synthetic/`. Use USD, two complete settlement months, consistent customer/category coverage, text IDs and MCCs, and a distinct signed-refund category. Review the generated values and reconciliation before committing; finish this milestone in another core session if needed.

  Result: A reviewed starter dataset, or an explicit generation/validation task to finish first.

- [ ] **Night 6 — Tool calls and short-term memory (30 min this week)**

  Continue the LangChain introduction only after setup works. Change one example tool and explain when the model calls it. If the dataset still needs work, use this block to resolve the smallest data issue and carry the course exercise forward.

  Result: A modified tool example or a completed dataset correction.

- [ ] **Night 7 — Weekly review (15 min this week)**

  Record the actual assessment result and add its exact title and verification URL only if passed. Check the dataset against the contract and list unfinished course work. Begin Week 4 only when the base data is valid.

  Result: An accurate credential entry and a clear dataset/course checkpoint.

### Week 4 — Verified spend and net-revenue calculations

Target: Deterministic period comparisons with known answers before exposing the calculations to an agent. Keep the analytical data read-only.

- [ ] **Night 1 — Continue LangChain: context and tools (45–55 min)**

  Complete the next introduction exercise after any setup gaps. Explain how context, state, and tool results affect the answer. Keep the project design to one agent and note one Python concept to practice in the calculation code.

  Result: A completed exercise or precise remaining task, plus a design note.

- [ ] **Night 2 — Continue LangChain: reliability and oversight (45–55 min)**

  Work through the introduction's middleware and human-review examples at your pace. Modify one example and explain the change. Carry incomplete course work forward rather than recording the course as finished.

  Result: A working example and an accurate introduction-course progress check.

- [ ] **Night 3 — Record expected results and validate the base data (45–55 min)**

  Manually verify the starter dataset's spend, interchange, rebate, and net-revenue totals for both months. Save expected answers before implementing the period-comparison tool. Check period coverage, consistent fictional identities, required fields, and cent-level reconciliation.

  Result: Known base answers and a dataset-validation check.

- [ ] **Night 4 — Build the period-comparison tool (45–55 min)**

  Calculate current and prior spend, interchange, rebates, net revenue, dollar changes, and meaningful percentage changes. Derive periods from settlement date. Treat a percentage change with a zero prior denominator as undefined and test it explicitly.

  Result: A verified period-comparison function with automated checks.

- [ ] **Night 5 — Build customer spend and revenue comparisons (45–55 min)**

  Group by the consistent customer ID/name pair and compare spend and net revenue. Reconcile customer dollar changes to the overall change. Use absolute dollar changes when a near-zero overall variance makes contribution percentages unstable.

  Result: A verified customer-comparison function and reconciliation checks.

- [ ] **Night 6 — Explain, debug, and commit (30–40 min)**

  Explain one calculation without assistance, reproduce one expected answer, and inspect a failed check. Keep functions small enough to understand, then commit the dataset, expected results, and working checks.

  Result: A reproducible spend/net-revenue milestone and an explained fix.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Check the calculation outputs against known answers. Record unresolved validation or Python issues and remaining LangChain exercises. Repeat the needed core nights before adding mix and rate analysis.

  Result: A justified readiness decision for the next calculation layer.

### Week 5 — Mix, rebates, rate movements, and driver rankings

Target: Answer all three documented business questions with verified calculations and distinct dollar/rate views. Describe observed mix and within-category changes; a formal volume/mix/rate attribution bridge remains outside this milestone.

- [ ] **Night 1 — Calculate aggregate rates and basis-point changes (45–55 min)**

  Add gross interchange rate, rebate rate, and net revenue yield from aggregate dollar totals divided by aggregate spend. Check the yield identity on the same population and denominator, round only for display, and verify that 2.00% to 1.80% is minus 20 basis points.

  Result: Verified rate functions and basis-point checks.

- [ ] **Night 2 — Compare interchange mix and rebates (45–55 min)**

  Use `transaction_description` as interchange categorization. Compare category spend shares and their changes, gross rates, rebate rates, and net yields across the two periods. Create known-answer examples that separate a mix change from a within-category rate or rebate change.

  Result: A category-comparison tool and documented expected results.

- [ ] **Night 3 — Rank drivers in dollars and rates (45–55 min)**

  Create separate net-revenue-dollar and yield-basis-point rankings for customers, standardized vendor names, and interchange categories. Include increases and decreases. Show both periods' spend beside rate movements, with no default minimum-dollar cutoff for comparable positive-spend groups.

  Result: Separate, testable dollar-impact and rate-movement views.

- [ ] **Night 4 — Handle refunds and exceptional denominators (45–55 min)**

  Preserve signed refund amounts in the totals and show their effect separately. Mark zero-spend rates undefined; show negative-spend refund groups outside ordinary positive-spend rankings. Keep negative revenue with positive spend eligible and flag small denominators caused by purchase/refund cancellation.

  Result: Documented refund and denominator behavior with checks.

- [ ] **Night 5 — Reconcile the three business answers (45–55 min)**

  Compare the tools with known answers, including a large-dollar customer and a small customer with a large basis-point movement. Reconcile each dimension separately to overall dollars; customer, vendor, and category views describe the same dollars and must not be added together. Build or correct fixtures for the data contract's evaluation scenarios before connecting these results to the agent.

  Result: Verified outputs for the three questions and a visible fixture/expected-answer checklist.

- [ ] **Night 6 — Refactor and explain one investigation (30–40 min)**

  Organize reusable calculation and validation functions into modules. Explain one finding, its supporting figures, and an unconfirmed hypothesis. Commit the analytical code and checks; finish missing fixtures in another core session if needed.

  Result: A reproducible analysis example with clear limits.

- [ ] **Night 7 — Calculation readiness review (15–20 min)**

  Check all three business questions, reconciliation, rate eligibility, and evaluation-fixture coverage. Carry unfinished work forward. Advance only when the agent can rely on the calculation outputs; do not add a formal attribution bridge to meet the calendar.

  Result: A justified decision to connect the agent or repeat calculation work.

### Week 6 — First revenue-variance agent and Deep Agents coursework

Target: One agent selects verified read-only tools and explains the project's three business questions with supporting figures. Keep source writes, automatic distribution, and business actions outside version one.

- [ ] **Night 1 — Connect the agent to verified tools (45–55 min)**

  Finish any blocking LangChain introduction exercise, then expose the validation, period-comparison, mix/rate, and driver tools to one agent. Ask the spend-comparison question and inspect the actual tool calls.

  Result: A first answer tied to verified tool output.

- [ ] **Night 2 — Define the investigation response (45–55 min)**

  Include the question, comparison periods, dataset reference, metric definitions, headline changes, dollar/rate rankings, anomalies, calculation references, follow-up questions, and human-review status. State that net revenue is interchange minus rebate, not profit; separate observed results from suggested explanations.

  Result: A consistent investigation summary with supporting evidence.

- [ ] **Night 3 — Start Introduction to Deep Agents (45–55 min)**

  Complete the setup and first exercise if earlier prerequisites are ready. Explain which concepts help the current project. Keep advanced features as course practice unless the first-version requirements actually need them.

  Result: A working exercise or precise setup task and a design note.

- [ ] **Night 4 — Continue Deep Agents exercises (45–55 min)**

  Study tools, execution environment, and context management at your pace. Change one setting and explain the effect. Record unfinished exercises without treating course attendance as completion.

  Result: A modified example you understand and an accurate course status.

- [ ] **Night 5 — Test the agent on the three questions (45–55 min)**

  Run the spend, mix/rebate, and dollar/rate-driver questions. Compare every numerical statement with expected tool results and fix the most important error. Check that customer, vendor, and category views are not double-counted.

  Result: A first working agent or a focused list of blocking failures.

- [ ] **Night 6 — Capture the first demonstration (30–40 min)**

  Save one full question → tool → result → explanation run. Explain the relevant Python functions and commit the project improvements. Keep the demonstration's status accurate if some questions remain unfinished.

  Result: Evidence of the first agent run and an explained implementation change.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Explain the agent's choices and limits in plain English. Record open numerical issues and unfinished Deep Agents exercises. Repeat the relevant core nights before broadening the feature set.

  Result: A two-minute explanation and a realistic reliability task list.

### Week 7 — Evaluation, edge cases, and failure investigation

Target: Evaluate the 11 scenarios in the existing data contract plus an unsupported request. Use known figures or explicit expected behavior and document actual results.

- [ ] **Night 1 — Finish the next Deep Agents gap (45–55 min)**

  Complete the highest-priority outstanding course exercise. Explain one Python or agent-design lesson and note which advanced features remain outside version one. If the course needs more sessions, carry it forward before opening another course.

  Result: A completed exercise and an accurate remaining-work list.

- [ ] **Night 2 — Start Building Reliable Agents with LangSmith (45–55 min)**

  Once prerequisites are ready, follow the tracing and observation lessons. Inspect a tool call, its validated arguments, and the model's response. Trace one incorrect project answer to the relevant calculation, tool selection, or explanation step.

  Result: One trace you can explain and a classified failure.

- [ ] **Night 3 — Assemble the contract-based evaluation set (45–55 min)**

  Continue the course's dataset/experiment exercises. Assemble the 11 data-contract scenarios with their reviewed fixtures and known answers, then add an unsupported question whose expected outcome is a clear scope limitation. Keep a precise list if any fixture or expected answer is unfinished.

  Result: A 12-case evaluation specification with explicit completion status.

- [ ] **Night 4 — Evaluate business findings and numerical accuracy (45–55 min)**

  Run the ready cases for volume changes, mix changes, within-category rates, rebates, and large/small customer drivers. Check amounts, basis points, supporting spend, and response structure. Record actual outcomes and fix one important failure.

  Result: Measured evaluation results and one verified improvement.

- [ ] **Night 5 — Evaluate anomalies and unsupported requests (45–55 min)**

  Run the refund, incomplete-period, missing-value, zero-denominator, inconsistent-revenue, and unsupported-request cases. Check that misleading totals, invented baselines, and unsupported causal explanations are avoided. Retest the relevant ordinary positive-spend ranking rules after fixes.

  Result: Documented edge-case results, with unfinished cases still visible.

- [ ] **Night 6 — Explain and commit one failure fix (30–40 min)**

  Trace a failure from input through Python/tool output to the final explanation. Explain its cause, add or improve an automated check, and show the result before and after the fix.

  Result: A reproducible before-and-after example in the learning log.

- [ ] **Night 7 — Evaluation readiness review (15–20 min)**

  Check that all 11 contract scenarios and the unsupported request have expected outcomes and recorded results. Carry missing fixtures, failures, or coursework into another core session or repeat week. Do not report an accuracy percentage without the actual evaluated denominator and results.

  Result: An evidence-based reliability checkpoint and remaining-work list.

### Week 8 — Monitoring, deployment coursework, and a repeatable local demo

Target: Apply reliability training, begin monitoring/deployment coursework, and make the current project easy to run. Deployment of the portfolio application itself is a later explicit milestone; a course exercise or local demo does not satisfy it.

- [ ] **Night 1 — Close the next Reliable Agents gap (45–55 min)**

  Complete the most important unfinished experiment or exercise and apply one lesson to the project evaluations. Record exactly what remains rather than assuming the course is complete at the end of this session.

  Result: A completed exercise and updated prerequisite checklist.

- [ ] **Night 2 — Start Monitoring Production Agents (45–55 min)**

  Once earlier course gaps are resolved, work through cost, latency, errors, and answer-quality monitoring. Trace a revenue-variance run and record the measurements the tools actually expose.

  Result: A first project monitoring record with explainable measurements.

- [ ] **Night 3 — Continue monitoring exercises (45–55 min)**

  Inspect a failed run or unnecessary tool call using the course's monitoring approach. Make one small improvement and rerun the relevant evaluation. Keep unfinished labs visible and carry them forward.

  Result: A monitoring improvement with a regression check.

- [ ] **Night 4 — Start Introduction to LangSmith Deployment (45–55 min)**

  Check the current account, environment, authentication, and cost requirements. Complete the first course deployment exercise if ready and access allows; otherwise record the precise prerequisite or access gap. Keep credentials and sensitive trace contents outside Git.

  Result: A deployment-course exercise or a documented blocking task.

- [ ] **Night 5 — Make the local revenue-variance demo repeatable (45–55 min)**

  Provide one simple command or interface for the three business questions. Test starting from the documented environment setup and synthetic data. Make expected configuration errors understandable and record remaining setup problems.

  Result: A repeatable local demonstration and checked setup instructions.

- [ ] **Night 6 — Record a demo and update the project README (30–40 min)**

  Save one investigation summary with its supporting dollar/rate figures, a human-review status, and an edge case. Update the README to distinguish completed features from planned SQL, API, workflow, and deployment extensions; commit the evidence.

  Result: A usable local-demo milestone with an accurate project status.

- [ ] **Night 7 — Eight-week review (15–20 min)**

  Review Python confidence, the three business answers, all evaluation outcomes, and progress across the five LangChain courses. Reconsider Quantic only after checking its cost, normal/peak workload, and what study it would replace. Repeat needed core nights before integrations. The upcoming engineering extensions and later exam windows move with actual readiness.

  Result: A specific integration-readiness decision and honest course-completion checklist.

### Week 9 — Python engineering in the revenue-variance project

Target: Make the existing calculations easier to understand, test, configure, and maintain.

- [ ] **Night 1 — Organize the working code (45–55 min)**

  Separate data validation, financial calculations, agent tools, and the entry point into small modules. Move one function at a time and rerun the known-answer checks.

  Result: A module layout with unchanged analytical results.

- [ ] **Night 2 — Handle expected errors (45–55 min)**

  Add clear exceptions for missing files, invalid dates, missing fields, and inconsistent financial amounts. Keep undefined rates explicit; do not replace invalid data with zero.

  Result: Documented error behavior and regression checks.

- [ ] **Night 3 — Separate configuration from code (45–55 min)**

  Use configuration for data location, comparison periods, and model selection. Read secrets from the environment and provide a placeholder-only example configuration.

  Result: A repeatable configuration setup without credentials in Git.

- [ ] **Night 4 — Add focused unit tests (45–55 min)**

  Test the net revenue identity, aggregate rates, basis-point movement, refund signs, and a zero denominator. Use the established expected answers rather than reproducing the implementation in each test.

  Result: A local command that runs meaningful calculation tests.

- [ ] **Night 5 — Debug a controlled failure (45–55 min)**

  Introduce a small bug on a temporary local branch or working copy. Trace it with a debugger or logs, explain the cause, fix it, and run the regression test.

  Result: A learning-log entry explaining diagnosis and verification.

- [ ] **Night 6 — Explain and simplify one module (30–40 min)**

  Explain one function without assistance, simplify unclear code, and commit the refactor with passing checks.

  Result: A reviewed Python engineering milestone.

- [ ] **Night 7 — Review readiness for SQL (15–20 min)**

  Check that the application still runs from documented setup instructions and list remaining Python gaps.

  Result: A readiness decision for the SQL extension.

### Week 10 — SQL data source and calculation parity

Target: Use the same synthetic data in a local SQL database while preserving the approved metrics.

- [ ] **Night 1 — Choose a small local database (45–55 min)**

  Start with SQLite unless another database is already useful and available. Map the existing thirteen columns, preserve text IDs/MCCs, and document cent-accurate money representation.

  Result: A schema and a documented data-mapping decision.

- [ ] **Night 2 — Load the synthetic transactions (45–55 min)**

  Write a repeatable loader with data validation. Verify row counts, period coverage, signed refunds, and amount totals against the source file.

  Result: A reproducible synthetic-data load.

- [ ] **Night 3 — Implement period queries (45–55 min)**

  Use parameterized period inputs and verified queries for settled spend, interchange, rebates, net revenue, and aggregate rates.

  Result: Read-only period queries with known-answer checks.

- [ ] **Night 4 — Implement driver and mix views (45–55 min)**

  Add customer, vendor, and category views. Preserve separate dollar/rate rankings, positive-spend comparability rules, and refund presentation.

  Result: SQL analysis views consistent with the project contract.

- [ ] **Night 5 — Compare SQL with the original tools (45–55 min)**

  Run the same evaluation cases through the SQL and local-function paths. Reconcile amounts and rate outputs and investigate differences.

  Result: A documented SQL/local parity report.

- [ ] **Night 6 — Document read-only access (30–40 min)**

  Document the fixed query/tool boundary and the database read-only mechanism. Keep the loader separate from analytical execution.

  Result: A committed SQL milestone with reproducible setup.

- [ ] **Night 7 — Review the data boundary (15–20 min)**

  Confirm that analysis does not modify source transactions and that periods remain parameterized.

  Result: A checked boundary and the next API task.

### Week 11 — A read-only analytical API

Target: Expose the verified analysis through a small Python service and test its contract.

- [ ] **Night 1 — Define the API contract (45–55 min)**

  Choose a small Python web framework. Define period-summary, mix/rates, and driver-ranking requests and responses, including periods, metric definitions, and undefined-rate behavior.

  Result: A documented analytical API contract.

- [ ] **Night 2 — Implement the first endpoint (45–55 min)**

  Expose the period-comparison calculation through the service. Validate requested periods and return structured data with its dataset reference.

  Result: A working period-comparison endpoint.

- [ ] **Night 3 — Add the remaining analytical endpoints (45–55 min)**

  Connect mix/rate and driver tools. Reuse the verified calculation layer instead of writing a second set of formulas.

  Result: Endpoints returning the established metrics.

- [ ] **Night 4 — Test invalid requests and authentication (45–55 min)**

  Reject malformed/unsupported requests. Protect non-health endpoints with a simple demo authentication mechanism, keeping its token in environment configuration.

  Result: API tests for valid, invalid, and unauthenticated requests.

- [ ] **Night 5 — Connect the agent to the API (45–55 min)**

  Have the explanation agent call the analytical API through a defined tool wrapper. Verify numbers against existing expected answers.

  Result: An agent run supported by API results.

- [ ] **Night 6 — Run the API demonstration (30–40 min)**

  Start the service from its README, submit a question, and capture supporting calculations and a clear error case.

  Result: A repeatable local API demonstration.

- [ ] **Night 7 — Review the service boundary (15–20 min)**

  List the endpoints, credentials setup, error behavior, and any remaining gaps.

  Result: A clear API milestone and sandbox-integration plan.

### Week 12 — Sandbox API integration

Target: Connect the project to a separate fictional investigation service without changing analytical source data.

- [ ] **Night 1 — Define the investigation record (45–55 min)**

  Specify the sandbox record fields, such as run ID, periods, headline variance, supporting references, review status, and reviewer decision. Keep them separate from the thirteen-column transaction contract.

  Result: A small operational record contract.

- [ ] **Night 2 — Build a sandbox investigation service (45–55 min)**

  Create a local mock/sandbox service that can accept and retrieve fictional investigation records. This is an operational store, not a write endpoint for transaction data.

  Result: A functioning sandbox service.

- [ ] **Night 3 — Write the authenticated connector (45–55 min)**

  Use a Python HTTP client, environment-based credentials, request validation, and explicit timeouts to call the sandbox service.

  Result: A connector exercised against the local sandbox.

- [ ] **Night 4 — Test rejected and failed calls (45–55 min)**

  Exercise missing credentials, invalid payloads, unavailable service, and a timed-out request. Return clear errors without exposing credentials.

  Result: Recorded connector tests and expected failure behavior.

- [ ] **Night 5 — Prepare drafts without sending them (45–55 min)**

  Create a structured investigation draft from verified analysis. Mark it pending review and verify that preparing a draft does not create a ticket.

  Result: A reviewable draft and a no-send-before-approval check.

- [ ] **Night 6 — Document and commit the integration (30–40 min)**

  Record the API contract, sandbox-only boundary, setup, and sample request/response.

  Result: A documented sandbox connector milestone.

- [ ] **Night 7 — Review before workflow automation (15–20 min)**

  Confirm that the analytical source is still read-only and that no draft is sent automatically.

  Result: A clear starting point for approval workflow work.

### Week 13 — Approval workflow and persisted state

Target: Run analysis, prepare a draft, pause for review, and create one sandbox record only after approval.

- [ ] **Night 1 — Define states and run identity (45–55 min)**

  Describe pending analysis, ready for review, approved, rejected, completed, and failed states. Assign a stable run ID and documented period/dataset scope.

  Result: A workflow diagram or state table.

- [ ] **Night 2 — Persist run state (45–55 min)**

  Store workflow status and analytical references in a separate local operational store. Save enough information to resume after the process exits.

  Result: A run that survives a restart.

- [ ] **Night 3 — Add explicit human approval (45–55 min)**

  Provide a simple review screen or command with approve/reject actions. Record the decision; rejected or unreviewed drafts must not invoke the investigation API.

  Result: An approval gate with tested outcomes.

- [ ] **Night 4 — Connect approval to the sandbox service (45–55 min)**

  Send an approved draft through the connector and store the returned sandbox record ID. Tie the action to the reviewed analysis and draft version.

  Result: One approved end-to-end sandbox run.

- [ ] **Night 5 — Add a repeatable trigger (45–55 min)**

  Support a manual period-specific run and an optional local scheduled trigger. Reuse the same workflow entry point; all outbound sandbox actions still require review.

  Result: A documented trigger and approval behavior.

- [ ] **Night 6 — Demonstrate pause and resume (30–40 min)**

  Start a run, exit while it awaits approval, restart, and finish it after review. Inspect the saved state and sandbox result.

  Result: Evidence of a resumed workflow.

- [ ] **Night 7 — Review state and approvals (15–20 min)**

  Check rejected, pending, and approved paths and record unresolved state-transition issues.

  Result: A verified approval workflow milestone.

### Week 14 — Failure recovery, duplicate prevention, and audit records

Target: Make retries and restarts predictable without creating repeated investigation records.

- [ ] **Night 1 — Classify failures (45–55 min)**

  Separate transient connection/service failures from invalid requests, authentication failures, and invalid analytical data. Define which failures are retryable.

  Result: A short failure-handling policy.

- [ ] **Night 2 — Implement bounded retries (45–55 min)**

  Retry only suitable transient failures, with a timeout, limited attempts, and backoff. Keep a visible final failed state when the retry budget is exhausted.

  Result: Tests showing successful recovery and a bounded failure.

- [ ] **Night 3 — Prevent duplicate actions (45–55 min)**

  Use a stable idempotency key derived from the logical run and reviewed draft version. Have the sandbox receiver enforce uniqueness and return the existing result for a repeat.

  Result: A duplicate request that produces one investigation record.

- [ ] **Night 4 — Test an uncertain outcome (45–55 min)**

  Simulate a request accepted by the sandbox followed by a lost response, then retry after restart. Confirm the persisted run and unique key resolve to the same record.

  Result: Evidence that a timeout/restart does not create duplicates.

- [ ] **Night 5 — Record the audit trail (45–55 min)**

  Log state changes, review decisions, action IDs, and outcomes. Keep secrets out of logs and ensure a changed draft needs a new explicit review.

  Result: An explainable run history and review-version check.

- [ ] **Night 6 — Run the failure scenarios (30–40 min)**

  Demonstrate service down, rejected approval, repeated trigger, restart, and eventual recovery. Save actual outcomes.

  Result: A failure/recovery report and committed fixes.

- [ ] **Night 7 — Review operational reliability (15–20 min)**

  Explain how the workflow handles an ambiguous API result and how to investigate a failed run.

  Result: A readiness decision for deployment.

### Week 15 — Deploy the revenue-variance project

Target: Run this portfolio project's service and workflow in a controlled demo environment.

- [ ] **Night 1 — Choose the deployment approach (45–55 min)**

  Check a provider's current limits and cost before spending. Decide how the analytical service, sandbox service, operational state, and local/manual trigger will run. Prefer one small deployment over extra infrastructure.

  Result: A deployment diagram, budget, and chosen environment.

- [ ] **Night 2 — Package the application (45–55 min)**

  Pin dependencies and document startup commands. Add a container only if useful for the chosen environment. Recreate the application from a clean environment.

  Result: A reproducible application package.

- [ ] **Night 3 — Configure persistence and access (45–55 min)**

  Use persistent storage for run state, protect analytical/review endpoints, and set credentials through the deployment environment. Keep synthetic data and operational stores distinct.

  Result: Documented deployment configuration and access checks.

- [ ] **Night 4 — Deploy this project (45–55 min)**

  Deploy the Revenue Variance Investigation Agent and required demo services, not just a course exercise. Verify health, authentication, and a read-only analytical request.

  Result: A running controlled deployment with a successful request.

- [ ] **Night 5 — Run the approved workflow (45–55 min)**

  Execute analysis, review the draft, approve it, and verify one sandbox record and persisted status. Restart the service and check that state remains available.

  Result: A deployed end-to-end run.

- [ ] **Night 6 — Inspect monitoring and teardown (30–40 min)**

  Inspect errors, latency, model usage/cost, and workflow outcomes. Document how to stop the deployment and remove paid resources when the demonstration ends.

  Result: A monitoring record and teardown instructions.

- [ ] **Night 7 — Review deployment evidence (15–20 min)**

  If access or budget blocks hosting, record the remaining requirement and keep it incomplete; a local demo is not a completed deployment milestone.

  Result: A truthful deployment status and next task.

### Week 16 — Continuous integration and an end-to-end portfolio demonstration

Target: Automate meaningful checks on commits and demonstrate the integrated project.

- [ ] **Night 1 — Add the first CI workflow (45–55 min)**

  Use the repository's CI platform to install dependencies and run deterministic unit/calculation tests on commits and pull requests.

  Result: A passing automated check tied to a commit.

- [ ] **Night 2 — Add SQL and API regression checks (45–55 min)**

  Run synthetic-data validation, SQL/local parity checks, and API contract tests. Keep routine CI independent of paid model calls by using fixtures or a fake model.

  Result: Repeatable regression checks without live credentials.

- [ ] **Night 3 — Add workflow reliability checks (45–55 min)**

  Automate approval gating, persisted resume, duplicate prevention, and the lost-response retry scenario against the sandbox.

  Result: Meaningful automated workflow tests.

- [ ] **Night 4 — Run a separate live agent evaluation (45–55 min)**

  Run the real model on the fixed evaluation set when budget allows. Record model/version, dataset, date, cost if available, numerical correctness, and actual failures.

  Result: A dated live evaluation report separate from mocked CI.

- [ ] **Night 5 — Record the integrated demonstration (45–55 min)**

  Show the business question, verified metrics, AI draft, approval, sandbox investigation, and one failure/recovery in a short demo. Link the running demo only when access is appropriate.

  Result: A demonstration of both applied AI and automation skills.

- [ ] **Night 6 — Update the portfolio documentation (30–40 min)**

  Document architecture, setup, metrics, tests, deployment, actual results, limitations, and operating cost. Keep unfinished work clearly labeled.

  Result: A portfolio README supported by code and evidence.

- [ ] **Night 7 — Review progress and Quantic capacity (15–20 min)**

  Assess the four extensions and remaining course work. Revisit degree cost and normal/peak workload within the same five-to-six-hour budget; postpone other study if a degree becomes primary.

  Result: A realistic next study block and degree decision note.

### Week 17 — Finish LangChain prerequisites and begin Microsoft certification

Target: Close course gaps, strengthen the README, and start AB-731 preparation.

- [ ] **Night 1 — Complete the next monitoring/deployment gap (45–55 min)**

  Finish the highest-priority outstanding exercise from Monitoring Production Agents or LangSmith Deployment. Record the exact remaining tasks.

  Result: One fewer prerequisite gap.

- [ ] **Night 2 — Continue deployment exercises (45–55 min)**

  Practice connecting to the agent and reviewing memory/authentication concepts as covered by the course. Complete more outstanding exercises.

  Result: A successful course exercise and updated completion checklist.

- [ ] **Night 3 — AB-731 study block 1 (45–55 min)**

  Start Drive AI transformation in your organization. Study the business value of generative AI and take notes using an analytics-management example.

  Result: Completed training units and one business example.

- [ ] **Night 4 — AB-731 study block 2 (45–55 min)**

  Continue the official learning path. Map business needs to Microsoft AI services and review relevant knowledge checks.

  Result: Completed units and a service-selection note.

- [ ] **Night 5 — Review the project README (45–55 min)**

  Review the revenue-variance problem, thirteen-column synthetic data contract, financial definitions, SQL/API tools, workflow, deployment, automated checks, actual evaluation results, limitations, and lessons learned. Update any gaps left after Week 16.

  Result: An updated portfolio README with evidence.

- [ ] **Night 6 — Check LangChain exam readiness (30–40 min)**

  Try part of the official practice exam within the time available, or review its domains. Record gaps without treating a partial attempt as a full practice score.

  Result: A focused LangChain revision list.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Verify which of the five prerequisite courses are actually complete. Reorder upcoming study sessions around remaining exercises.

  Result: A truthful course and project status.

### Week 18 — Microsoft preparation and revenue-variance portfolio presentation

Target: Complete the AB-731 training and publish a clear demonstration of the agent.

- [ ] **Night 1 — AB-731 study block 3 (45–55 min)**

  Continue Microsoft AI capabilities and use-case selection. Explain why you would choose one service over another.

  Result: Completed units and two service-selection examples.

- [ ] **Night 2 — AB-731 study block 4 (45–55 min)**

  Study AI adoption, implementation, and responsible AI. Apply the ideas to an analytics team's rollout.

  Result: A short adoption outline and completed units.

- [ ] **Night 3 — AB-731 study block 5 (45–55 min)**

  Continue the remaining official training and knowledge checks. Track what is incomplete.

  Result: An updated objective-by-objective checklist.

- [ ] **Night 4 — AB-731 study block 6 and remaining training (45–55 min)**

  Finish the remaining training if possible; otherwise continue it next week. The six 45–55-minute sessions allocate roughly 4½–5½ study hours. Extend preparation when needed; listed video/module time does not establish mastery.

  Result: Completed training or a specific completion plan.

- [ ] **Night 5 — Record the portfolio demonstration (45–55 min)**

  Show a revenue-variance question, verified dollar and basis-point metrics, the agent explanation, and one approval/recovery example in a concise demo. Reuse the Week 16 recording if accurate, or update it for the current version. Commit documentation and example outputs.

  Result: A concise, understandable project demonstration.

- [ ] **Night 6 — Prepare LinkedIn Featured material (30–40 min)**

  Draft a short project post describing the problem, approach, measured test results, and one limitation. Add the public repository to Featured when ready.

  Result: A project link and a factual draft post.

- [ ] **Night 7 — Eighteen-week review (15–20 min)**

  Check course completions, earned credentials, the revenue-variance demonstration, and remaining gaps. Keep the next two weeks flexible for exams or unfinished work, prioritizing project gaps.

  Result: An evidence-based exam preparation plan.

### Week 19 — Microsoft exam readiness and first certification target

Target: Attempt AB-731 if ready while keeping the project and LangChain study active.

Weekly allocation: up to 55 + 55 + 40 + 90 + 40 + 30 + 20 = 330 minutes (5 hours 30 minutes). The longer exam replaces ordinary study time.

- [ ] **Night 1 — Take the Microsoft practice assessment (45–55 min)**

  Finish any remaining AB-731 training first, then attempt the official practice assessment. Explain each missed answer in your own words.

  Result: A list of weak objectives and reasons for errors.

- [ ] **Night 2 — Repair Microsoft knowledge gaps (45–55 min)**

  Use official material to revisit weak objectives. Work through new business scenarios rather than memorizing repeated questions.

  Result: A corrected set of explanations.

- [ ] **Night 3 — Make the AB-731 readiness decision (30–40 min)**

  Recheck practice performance and explain the main exam objectives without notes. If ready, schedule the exam and complete the provider's system check; otherwise use the exam night for more study.

  Result: A justified exam decision and confirmed logistics if booked.

- [ ] **Night 4 — AB-731 exam or focused study (Reserve 75–90 min if booked)**

  Take the 45-minute proctored exam with time for check-in if you are prepared and have booked it. Otherwise work on the weakest objectives and defer the exam.

  Result: An exam result or completed targeted preparation.

- [ ] **Night 5 — Resume LangChain practice (30–40 min)**

  Complete any prerequisite gap, then practice building, testing, deployment, or monitoring based on your weakest area.

  Result: One worked example addressing a real gap.

- [ ] **Night 6 — Update your evidence (20–30 min)**

  Add the Microsoft Certified title and verification link only if earned. Otherwise record the next preparation or retake step. Fix one small project issue.

  Result: Accurate profile details and a maintained project.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Check remaining LangChain gaps and choose the next week's priority. Keep an exam attempt separate from a credential earned.

  Result: A clear LangChain exam-week plan.

### Week 20 — LangChain readiness and technical certification target

Target: Attempt the LangChain certification when prepared and show the completed portfolio clearly.

Weekly allocation: 30 + 30 + 120 + 20 + 135 + 10 + 10 = 355 minutes (5 hours 55 minutes). These short review sessions replace ordinary core nights. If the provider requires a longer block, or practice reveals gaps, move the certification attempt to another week.

- [ ] **Night 1 — Review building and testing agents (30 min)**

  Recreate a small tool-calling example and explain state, tools, tracing, and evaluation. Finish any corresponding course gap.

  Result: A working example and clear explanations.

- [ ] **Night 2 — Review deployment and monitoring (30 min)**

  Work through weak deployment/monitoring topics and explain cost, latency, errors, and quality checks using your project.

  Result: A completed revision exercise.

- [ ] **Night 3 — Complete a full LangChain practice exam (Reserve up to 120 min)**

  Take the official practice exam under suitable conditions, allowing the time it specifies. Review errors and explain the answers rather than relying on recall.

  Result: A full practice result and a final gap list.

- [ ] **Night 4 — Make the LangChain readiness decision (20 min)**

  Confirm all prerequisites and major practice gaps are covered. Schedule only when prepared and complete the provider's system check. Otherwise turn the exam session into further study.

  Result: A justified exam decision and logistics if booked.

- [ ] **Night 5 — LangChain exam or targeted practice (Reserve about 135 min if booked)**

  Take the proctored certification exam only if booked and ready. The listed exam is 120 minutes, with about 135 minutes of seat time. If not ready, continue focused practice.

  Result: An exam attempt or a completed study milestone.

- [ ] **Night 6 — Finish the portfolio record (10 min)**

  After results arrive, add the certification only if awarded. Pin the GitHub project, link the demo in LinkedIn Featured, and publish the project post when it is ready.

  Result: A profile supported by verifiable credentials and a project.

- [ ] **Night 7 — Choose the next step (10 min)**

  Review what you can now build and explain. Choose the next step from remaining Python/integration gaps, another revenue-variance feature, more exam preparation, or a Quantic decision based on verified cost and study capacity.

  Result: A specific next goal based on remaining gaps.

## Repeat-week rule

At each weekly review, complete the prerequisite work needed for the next milestone before advancing. Reuse Night 6 for small gaps; if the gap needs more than one session, repeat the relevant core nights. When an assessment is deferred, the replacement task is targeted practice, not an extra credential. Keep unfinished work visible and move the later exam window instead of rushing.

Keep the five-to-six-hour weekly cap when tasks move. Complete a deferred item in place of another session, or add a week. Do not compress financial verification, human approval, or deployment checks to preserve an exam date.
