# Experiment methodology

## 1. Define the question

Choose a bounded claim or technical decision. Record the expectation and evaluation criteria before inspecting test results.

## 2. Identify the sources and implementation scope

Cite primary sources and versions. State whether the project is a paper-inspired prototype, partial implementation, or reproduction attempt. Document implemented components, deviations, and missing details.

## 3. Plan a meaningful comparison

Specify dataset versions, sampling, splits, baselines, model settings, prompts, metrics, repetitions, hardware, and budget. Avoid using test answers to tune retrieval or generation. Keep exploratory diagnostics separate from held-out evaluation.

## 4. Preserve the evidence

Save configurations, commands, code commit, raw outputs, scoring rules, and measured usage. Keep credentials and private data out of committed artifacts. Respect dataset and upstream code licenses.

## 5. Report the full outcome

Report sample size, correct or successful cases, failures, and denominators. Label recovered runs and mixed execution versions. Never silently replace a published result with a later run.

Measure runtime and resource consumption when relevant. Separate build, query, and evaluation costs. Include retries and explain cache treatment. Missing provider usage is unknown, not zero.

## 6. Interpret within the tested scope

Separate observations from explanations and broader hypotheses. Disclose limitations and judge uncertainty; do not generalize a small custom evaluation to an entire paper benchmark.

## 7. Publish a traceable conclusion

Register the project in PROJECTS.md. Link articles and videos to the supporting commit or release and evidence. Record corrections transparently when conclusions change.
