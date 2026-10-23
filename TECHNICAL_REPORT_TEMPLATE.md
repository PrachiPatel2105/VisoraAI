# Visora AI — Technical Report

## 1. Problem and intended users
Describe the inspection problem, who experiences it, and why it matters. Avoid claiming real-world impact without supporting evidence.

## 2. Solution overview
Explain the implemented workflow and what makes it agentic. Include one concrete example in which visual evidence changes a later action.

## 3. OpenCV 5 implementation
- OpenCV 5 version:
- Image/video operations actually used:
- Inputs and preprocessing:
- Detection/anomaly method:
- How suspicious regions are selected:
- Limitations:

## 4. Agent workflow
Describe perception → decision → action. Include a trace with input, visual result, decision, subsequent tool call/action, and final outcome.

## 5. AWS architecture and deployment
List the services actually used, region, compute/runtime configuration, storage, access controls, and cost controls. Include a diagram matching the real deployment.

## 6. Evaluation
Document dataset/source, sample count, labels, train/test split if applicable, and test procedure. Report measured metrics only.

| Metric | Result | Method |
|---|---|---|
| Precision | TBD | Calculate from labelled test cases |
| Recall | TBD | Calculate from labelled test cases |
| False-positive rate | TBD | Calculate from labelled test cases |
| End-to-end latency | TBD | State hardware and measurement method |
| Agent task success | TBD | Define successful completion criteria |

Include representative successes, false positives, false negatives, ambiguous cases, and failures.

## 7. User experience
Describe the interface and how a user reviews results or overrides a recommendation.

## 8. Responsible use
Explain that results may be wrong, when human review is required, what data is stored, and how access is protected.

## 9. Reproducibility
Provide repository URL, pinned dependency file, build/run/test commands, environment variables required (without secrets), and demo URL.

## 10. What we learned and next steps
Summarize actual implementation challenges and lessons learned. Distinguish completed work from planned improvements.
