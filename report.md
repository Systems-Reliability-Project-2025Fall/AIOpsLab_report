# Evaluating LLM Agents for Debugging Cloud (Kubernetes) Issues

## Introduction – A concise overview of the project and its motivation

We aim to develop an LLM-driven agent capable of automatically detecting, localizing, analyzing, and mitigating faults in Kubernetes (K8s) clusters.

Today, Kubernetes operations depend heavily on metrics, logs, alerting systems, and human-engineered rules. Debugging typically requires an SRE to manually piece together signals and apply experience-driven heuristics to identify the root cause of failures.

Large Language Models, however, implicitly encode much of this troubleshooting knowledge. Their training data includes countless examples of real-world K8s debugging scenarios, allowing them to internalize the heuristics and reasoning patterns used by human operators. With recent advances in reasoning-capable LLMs, these models increasingly resemble the structured diagnostic processes of experienced engineers.

Although practitioners have begun experimenting with LLMs as assistants within the debugging loop, it remains unclear how well LLMs perform autonomously. Kubernetes provides an ideal testbed for evaluating this: the debugging process is complex, multi-step, and grounded in a standardized API surface that an agent can reliably interact with.

This project explores how effectively LLM agents can handle end-to-end Kubernetes fault diagnosis and remediation, and how their performance compares to human-driven workflows.

## Background and Related work– Relevant technical context and prior research needed to understand your project.

## Design – A clear description of your proposed system, technique, or approach.
## Implementation – Details of your technical implementation, including the specific tasks completed by each team member.
## Evaluation – An assessment of how well your system or technique performs based on your chosen metrics or methodology.

