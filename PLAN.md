# Matthew's AI credentials and agent-building plan

Prepared October 23, 2026. Start Week 1, Night 1 whenever you begin; weeks are learning blocks, not calendar deadlines.

## What this plan is designed to produce

- Two LinkedIn Learning certificates of completion.
- Microsoft Applied Skills: Generate reports with AI research agents, if the practical assessment is passed.
- Microsoft Certified: AI Transformation Leader (AB-731), if the proctored exam is passed.
- Completion of the five courses listed as prerequisites for LangChain Certified Agent Engineer.
- LangChain Certified Agent Engineer, when prepared and the proctored exam is passed.
- A public GitHub project demonstrating a Monthly Revenue Review Agent, with sample data, numerical checks, results, and a short demo.

Eight weeks cover learning and project work. Weeks 9–10 reserve space for revision and exam attempts. These are planning estimates, not guaranteed completion dates. Extend a week when Python, course labs, account access, or practice results need more work.

## The nightly rhythm

Nights 1–5: usually 45–60 minutes. Night 6: 30–45 minutes for practice, demonstration, or catch-up. Night 7: 15–20 minutes of review. This is roughly five to six hours per week. Assessment and exam nights have a longer explicitly marked block; reserve the full time shown by the provider and allow for check-in/setup.

On a normal night, spend five minutes reviewing the last note, 35–50 minutes doing the assigned task, and five minutes recording the result and next step. A tired-night minimum is 15 minutes: review one concept, fix one small issue, or write tomorrow's next action. Resume the unfinished task the next night. Do not double the next session to compensate for a missed night.

Your learning log should record: date, task, actual minutes, what worked, one thing you can explain, blocker, next step, and the relevant commit/certificate link. Checking a night as complete means its result was produced; course attendance, exam attempts, and credentials earned are separate records.

## The project

Repository: `monthly-revenue-review-agent`, separate from your resume repository.

Question: “What changed in monthly revenue, which customers or products drove the change, and what should a manager investigate?”

Version one uses one agent, one fixed synthetic CSV, and three calculation tools: period summary, customer contribution, and product contribution. Python calculates the numbers; the agent chooses the appropriate tools and explains their results. Show the period, supporting figures, and limits of the analysis. Suggested explanations are hypotheses to investigate, not established causes.

Evidence of a finished first version:

- Three core business questions answered from verified calculations.
- Ten evaluation questions plus checks for missing periods, zero prior revenue, and unsupported requests.
- Actual evaluation results documented, without invented accuracy or business-impact claims.
- A reproducible README, sample output, and a two- to three-minute demonstration.
- Synthetic or permitted public data only; model credentials kept outside Git.

Python readiness gate: be able to run and change a function, read a CSV, use dictionaries/lists, install project dependencies, and explain an error. If unfamiliar, use the next two to four core nights for those basics; move later tasks back accordingly.

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

Optional later additions: [Microsoft Applied Skills: Build an agent in Microsoft Copilot Studio](https://learn.microsoft.com/en-us/credentials/applied-skills/build-an-agent-in-microsoft-copilot-studio/) is intermediate and needs hands-on preparation; [MCP: Hands-On with Agentic AI](https://www.linkedin.com/learning/model-context-protocol-mcp-hands-on-with-agentic-ai) is a possible third LinkedIn class. They are not additional requirements for these ten weeks.

## Exam readiness and LinkedIn visibility

Book each exam independently when you have covered the official objectives, completed the relevant exercises, can explain your practice mistakes, and can handle unfamiliar examples. Repeated practice-question recall alone is not readiness. Follow the issuer's assessment rules and complete assessments independently.

Keep each issuer's exact title. LinkedIn Learning certificates of completion, Microsoft Applied Skills credentials, and Microsoft Certifications are different achievements. Add verification links only after award; use completion dates accurately.

Visibility checkpoints:

- End of Week 1: course certificates added if earned.
- Week 2 or later: Microsoft Applied Skills credential added if passed.
- Week 4: first working agent committed, with a sample output.
- Week 8: repository and demo ready for LinkedIn Featured; draft a post explaining one result and one limitation.
- Weeks 9–10 or later: add exam certifications after official results. Share credentials alongside examples of what you learned or built.

## Night-by-night checklist

### Week 1 — Quick LinkedIn wins and project setup

Target: Two course certificates, a clear project brief, and a Python readiness check.

- [ ] **Night 1 — Agent Skills: first half (45–60 min)**

  Watch roughly 25 minutes of Give Your AI Agent Skills. Write three takeaways and describe one reusable analytics skill in your own words.

  Result: Three notes and one skill idea.

- [ ] **Night 2 — Finish Agent Skills (45–60 min)**

  Finish the remaining videos and quiz. Save the certificate URL. Draft a small skill with a purpose, required inputs, and expected output.

  Result: First LinkedIn Learning certificate and a skill draft.

- [ ] **Night 3 — First Agentic AI System: first half (45–60 min)**

  Watch about 30–35 minutes. Sketch question → tool → result → explanation for the Monthly Revenue Review Agent. Check Microsoft Learn sign-in and access to practice with Researcher.

  Result: A simple agent workflow and an access check.

- [ ] **Night 4 — Finish the second LinkedIn course (45–60 min)**

  Finish Agentic AI: Build Your First Agentic AI System and its completion requirements. Save the certificate URL. Note one design idea to use in your project.

  Result: Second LinkedIn Learning certificate and one project design decision.

- [ ] **Night 5 — Create the project repository (45–60 min)**

  Create monthly-revenue-review-agent separately from the resume repository. Add README, .gitignore, and a learning log. State the three business questions and synthetic-data scope; commit and push.

  Result: A visible GitHub project with a clear purpose.

- [ ] **Night 6 — Check your Python starting point (30–45 min)**

  Run a small script using a function, a dictionary, and a CSV file. Explain what each part does. If this is unfamiliar, turn the next core sessions into Python practice before advancing.

  Result: One working script, or a specific Python bridge plan.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Add the two certificates to LinkedIn only if earned. Record what you learned, where you got stuck, and the next task. No new course tonight.

  Result: Updated progress log and a clear next step.

### Week 2 — First Microsoft credential and LangChain foundations

Target: An Applied Skills assessment attempt and the first working LangChain example.

- [ ] **Night 1 — Prepare for AI research reports (45–60 min)**

  Read the Generate reports with AI research agents study guide and linked training. Practice setting scope, audience, objectives, and sources for a report.

  Result: A report prompt with explicit scope and source requirements.

- [ ] **Night 2 — Practice the complete report workflow (45–60 min)**

  Create or work through a sample report, refine its structure, check references, and create an executive summary. Review the assessment lab orientation.

  Result: A checked practice report or completed official exercise.

- [ ] **Night 3 — Attempt the reporting assessment if ready (Reserve 60–90 min)**

  Confirm the launch page's full assessment time and allow for setup. Complete the lab yourself in one uninterrupted session. If not ready or access fails, use tonight for practice and carry the attempt forward.

  Result: An earned Applied Skills credential, or a documented preparation/retry task.

- [ ] **Night 4 — Start Introduction to LangChain — Python (45–60 min)**

  Follow the course setup. Configure model credentials outside Git, confirm provider costs, and run the first example. If Python needs work, use this session for the bridge instead.

  Result: A successful local course example.

- [ ] **Night 5 — Learn tool calls and short-term memory (45–60 min)**

  Continue the first LangChain module. Change one example tool and observe the result. Explain when the model decides to use the tool.

  Result: A modified example you can explain.

- [ ] **Night 6 — Define the synthetic revenue dataset (30–45 min)**

  Create a small synthetic CSV and document its columns. Use fixed dates, customer IDs, products, and revenue; include at least two comparable months. Keep the first file small enough to check manually.

  Result: A documented sample dataset committed to GitHub.

- [ ] **Night 7 — Weekly review (15–20 min)**

  If the assessment was passed, add its exact Applied Skills title and verification URL to LinkedIn. Review setup issues and decide whether to repeat a Python week.

  Result: An accurate credential entry and an adjusted pace.

### Week 3 — Verified revenue calculations

Target: Correct analysis tools before connecting them to your own agent.

- [ ] **Night 1 — Continue LangChain: context and tools (45–60 min)**

  Work through the next course section and its exercise. Note how context, state, and tool results affect the response; keep your project to one agent.

  Result: Course exercise completed and short notes.

- [ ] **Night 2 — Continue LangChain: reliability and oversight (45–60 min)**

  Work through middleware and human-review examples. Complete remaining introduction exercises as time allows; carry unfinished work to the next session.

  Result: A working example and an introduction-course progress check.

- [ ] **Night 3 — Build the period summary tool (45–60 min)**

  Calculate monthly revenue totals, absolute change, and percentage change from the synthetic dataset. Check the values manually, including a zero prior-period total.

  Result: A verified period-summary function.

- [ ] **Night 4 — Build the customer contribution tool (45–60 min)**

  Calculate each customer's contribution to the total revenue change. Reconcile the customer changes to the overall change.

  Result: A verified customer-contribution function.

- [ ] **Night 5 — Build the product contribution tool (45–60 min)**

  Calculate revenue change by product. Save expected answers for three business questions and add numerical checks.

  Result: Three useful calculation tools with known answers.

- [ ] **Night 6 — Explain and commit the calculations (30–45 min)**

  Run the tools and explain one calculation without assistance. Commit the working tools, sample data, and checks.

  Result: A reproducible calculations milestone on GitHub.

- [ ] **Night 7 — Weekly review (15–20 min)**

  List what is correct, what remains unfinished in the introduction course, and the next smallest task.

  Result: A clear readiness decision for connecting the agent.

### Week 4 — First working agent and Deep Agents

Target: An agent that selects calculation tools and produces an evidence-backed revenue explanation.

- [ ] **Night 1 — Connect your agent to the calculation tools (45–60 min)**

  Finish any blocking introduction exercise, then expose the verified revenue tools to one LangChain agent. Ask the month-over-month question.

  Result: A first answer based on a real tool result.

- [ ] **Night 2 — Write the response format (45–60 min)**

  Include the date range, revenue figures, largest customer/product changes, and suggested investigation. Separate observed changes from possible explanations.

  Result: A consistent management summary with supporting figures.

- [ ] **Night 3 — Start Introduction to Deep Agents (45–60 min)**

  Complete the setup and first building exercises. Note which features are relevant to your project and why.

  Result: A working course exercise and a short design note.

- [ ] **Night 4 — Continue Deep Agents exercises (45–60 min)**

  Study tools, execution environment, and context management. Run an exercise and change one setting to understand its effect.

  Result: A modified course example you understand.

- [ ] **Night 5 — Test the first agent on your three questions (45–60 min)**

  Run each project question, compare every number to the expected answer, and fix the most important failure.

  Result: A working version answering the three core questions.

- [ ] **Night 6 — Capture the first demonstration (30–45 min)**

  Save a screenshot or short local recording of one full question-and-answer run. Commit the project improvements.

  Result: Evidence of the first working agent.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Explain the agent's choices and limits in plain English. Record unfinished Deep Agents exercises for next week.

  Result: A two-minute explanation of how the agent works.

### Week 5 — Reliable answers and evaluation

Target: A small evaluation set and evidence that the agent handles common failures.

- [ ] **Night 1 — Finish Deep Agents exercises (45–60 min)**

  Complete the remaining course exercises at your pace. Record which advanced features you intentionally kept out of version one and why.

  Result: Completed course exercises or a precise remaining-work list.

- [ ] **Night 2 — Start Building Reliable Agents (45–60 min)**

  Follow the tracing and observation lessons. Inspect a course example's tool calls and model responses.

  Result: One trace you can explain.

- [ ] **Night 3 — Continue Reliable Agents: evaluation (45–60 min)**

  Work through datasets and experiments. Create ten fixed project questions with expected figures or expected behavior.

  Result: A ten-question evaluation set.

- [ ] **Night 4 — Run evaluations and fix a failure (45–60 min)**

  Compare agent outputs with expected results. Check numerical correctness and whether the summary follows the requested format. Record actual results.

  Result: An evaluation report and one verified improvement.

- [ ] **Night 5 — Add edge cases (45–60 min)**

  Check missing months, zero prior revenue, and an unsupported question. Give clear responses rather than misleading totals or explanations.

  Result: Three documented edge-case checks.

- [ ] **Night 6 — Review one failure from start to finish (30–45 min)**

  Trace the failure to its cause, explain the fix, and commit the evidence.

  Result: A before-and-after example in the learning log.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Record evaluation outcomes and remaining issues. If coursework is unfinished, carry it forward before opening another course.

  Result: A realistic reliability checkpoint.

### Week 6 — Monitoring, deployment practice, and a usable demo

Target: Finish reliability training, begin monitoring/deployment, and make the project easy to run.

- [ ] **Night 1 — Finish Building Reliable Agents (45–60 min)**

  Complete remaining experiments and exercises. Apply one lesson to your evaluation set.

  Result: Reliable Agents exercises completed or a remaining-work list.

- [ ] **Night 2 — Start Monitoring Production Agents (45–60 min)**

  Work through cost, latency, errors, and quality monitoring. Trace a project run and note what you can measure.

  Result: A first project monitoring record.

- [ ] **Night 3 — Continue monitoring exercises (45–60 min)**

  Work through the remaining labs or capstone as time allows. Inspect an unnecessary tool call or failed run.

  Result: A monitoring improvement and course progress recorded.

- [ ] **Night 4 — Start Introduction to LangSmith Deployment (45–60 min)**

  Check current account, environment, and cost requirements. Complete the first deployment exercise if access allows; document any access gap.

  Result: A course deployment exercise or a documented setup task.

- [ ] **Night 5 — Make the local demo usable (45–60 min)**

  Provide a simple command or interface for the three example questions. Test starting the project with your documented setup instructions.

  Result: A repeatable local demonstration.

- [ ] **Night 6 — Commit and record a demo run (30–45 min)**

  Save an example summary and its supporting numbers. Record one remaining reliability or setup issue.

  Result: A usable demo milestone on GitHub.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Check progress across all five LangChain courses. Repeat a week if monitoring or deployment exercises need more time.

  Result: An honest prerequisite completion checklist.

### Week 7 — Finish LangChain prerequisites and begin Microsoft certification

Target: Close course gaps, strengthen the README, and start AB-731 preparation.

- [ ] **Night 1 — Complete the next monitoring/deployment gap (45–60 min)**

  Finish the highest-priority outstanding exercise from Monitoring Production Agents or LangSmith Deployment. Record the exact remaining tasks.

  Result: One fewer prerequisite gap.

- [ ] **Night 2 — Continue deployment exercises (45–60 min)**

  Practice connecting to the agent and reviewing memory/authentication concepts as covered by the course. Complete more outstanding exercises.

  Result: A successful course exercise and updated completion checklist.

- [ ] **Night 3 — AB-731 study block 1 (45–60 min)**

  Start Drive AI transformation in your organization. Study the business value of generative AI and take notes using an analytics-management example.

  Result: Completed training units and one business example.

- [ ] **Night 4 — AB-731 study block 2 (45–60 min)**

  Continue the official learning path. Map business needs to Microsoft AI services and review relevant knowledge checks.

  Result: Completed units and a service-selection note.

- [ ] **Night 5 — Write the project README (45–60 min)**

  Document the problem, setup, tools, sample questions, evaluation results, data source, limitations, and lessons learned.

  Result: A portfolio README with evidence.

- [ ] **Night 6 — Check LangChain exam readiness (30–45 min)**

  Try part of the official practice exam within the time available, or review its domains. Record gaps without treating a partial attempt as a full practice score.

  Result: A focused LangChain revision list.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Verify which of the five prerequisite courses are actually complete. Reorder upcoming study sessions around remaining exercises.

  Result: A truthful course and project status.

### Week 8 — Microsoft preparation and portfolio presentation

Target: Complete the AB-731 training and publish a clear demonstration of the agent.

- [ ] **Night 1 — AB-731 study block 3 (45–60 min)**

  Continue Microsoft AI capabilities and use-case selection. Explain why you would choose one service over another.

  Result: Completed units and two service-selection examples.

- [ ] **Night 2 — AB-731 study block 4 (45–60 min)**

  Study AI adoption, implementation, and responsible AI. Apply the ideas to an analytics team's rollout.

  Result: A short adoption outline and completed units.

- [ ] **Night 3 — AB-731 study block 5 (45–60 min)**

  Continue the remaining official training and knowledge checks. Track what is incomplete.

  Result: An updated objective-by-objective checklist.

- [ ] **Night 4 — AB-731 study block 6 and remaining training (45–60 min)**

  Finish the remaining training if possible; otherwise continue it next week. Across six sessions, allow roughly five to six study hours rather than assuming the listed video/module time equals mastery.

  Result: Completed training or a specific completion plan.

- [ ] **Night 5 — Record the portfolio demonstration (45–60 min)**

  Show a business question, the tool calculations, the final summary, and an edge case in a two- to three-minute demo. Commit documentation and example outputs.

  Result: A concise, understandable project demonstration.

- [ ] **Night 6 — Prepare LinkedIn Featured material (30–45 min)**

  Draft a short project post describing the problem, approach, measured test results, and one limitation. Add the public repository to Featured when ready.

  Result: A project link and a factual draft post.

- [ ] **Night 7 — Eight-week review (15–20 min)**

  Check course completions, earned credentials, GitHub demo, and remaining gaps. Keep the next two weeks flexible for exams or unfinished work.

  Result: An evidence-based exam preparation plan.

### Week 9 — Microsoft exam readiness and first certification target

Target: Attempt AB-731 if ready while keeping the project and LangChain study active.

- [ ] **Night 1 — Take the Microsoft practice assessment (45–60 min)**

  Finish any remaining AB-731 training first, then attempt the official practice assessment. Explain each missed answer in your own words.

  Result: A list of weak objectives and reasons for errors.

- [ ] **Night 2 — Repair Microsoft knowledge gaps (45–60 min)**

  Use official material to revisit weak objectives. Work through new business scenarios rather than memorizing repeated questions.

  Result: A corrected set of explanations.

- [ ] **Night 3 — Make the AB-731 readiness decision (45–60 min)**

  Recheck practice performance and explain the main exam objectives without notes. If ready, schedule the exam and complete the provider's system check; otherwise use the exam night for more study.

  Result: A justified exam decision and confirmed logistics if booked.

- [ ] **Night 4 — AB-731 exam or focused study (Reserve 75–90 min if booked)**

  Take the 45-minute proctored exam with time for check-in if you are prepared and have booked it. Otherwise work on the weakest objectives and defer the exam.

  Result: An exam result or completed targeted preparation.

- [ ] **Night 5 — Resume LangChain practice (45–60 min)**

  Complete any prerequisite gap, then practice building, testing, deployment, or monitoring based on your weakest area.

  Result: One worked example addressing a real gap.

- [ ] **Night 6 — Update your evidence (30–45 min)**

  Add the Microsoft Certified title and verification link only if earned. Otherwise record the next preparation or retake step. Fix one small project issue.

  Result: Accurate profile details and a maintained project.

- [ ] **Night 7 — Weekly review (15–20 min)**

  Check remaining LangChain gaps and choose the next week's priority. Keep an exam attempt separate from a credential earned.

  Result: A clear final-week plan.

### Week 10 — LangChain readiness and technical certification target

Target: Attempt the LangChain certification when prepared and show the completed portfolio clearly.

- [ ] **Night 1 — Review building and testing agents (45–60 min)**

  Recreate a small tool-calling example and explain state, tools, tracing, and evaluation. Finish any corresponding course gap.

  Result: A working example and clear explanations.

- [ ] **Night 2 — Review deployment and monitoring (45–60 min)**

  Work through weak deployment/monitoring topics and explain cost, latency, errors, and quality checks using your project.

  Result: A completed revision exercise.

- [ ] **Night 3 — Complete a full LangChain practice exam (Reserve up to 120 min)**

  Take the official practice exam under suitable conditions, allowing the time it specifies. Review errors and explain the answers rather than relying on recall.

  Result: A full practice result and a final gap list.

- [ ] **Night 4 — Make the LangChain readiness decision (45–60 min)**

  Confirm all prerequisites and major practice gaps are covered. Schedule only when prepared and complete the provider's system check. Otherwise turn the exam session into further study.

  Result: A justified exam decision and logistics if booked.

- [ ] **Night 5 — LangChain exam or targeted practice (Reserve about 135 min if booked)**

  Take the proctored certification exam only if booked and ready. The listed exam is 120 minutes, with about 135 minutes of seat time. If not ready, continue focused practice.

  Result: An exam attempt or a completed study milestone.

- [ ] **Night 6 — Finish the portfolio record (30–45 min)**

  After results arrive, add the certification only if awarded. Pin the GitHub project, link the demo in LinkedIn Featured, and publish the project post when it is ready.

  Result: A profile supported by verifiable credentials and a project.

- [ ] **Night 7 — Choose the next step (15–20 min)**

  Review what you can now build and explain. Decide between another project feature, the optional third LinkedIn course, or another week of exam preparation.

  Result: A specific next goal based on remaining gaps.

## Repeat-week rule

At each weekly review, complete the prerequisite work needed for the next milestone before advancing. Reuse Night 6 for small gaps; if the gap needs more than one session, repeat the relevant core nights. When an assessment is deferred, the replacement task is targeted practice, not an extra credential. Keep unfinished work visible and move the later exam window instead of rushing.
