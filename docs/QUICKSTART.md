# Quickstart Guide

## Prerequisites
```bash
python 3.10+
pip install -r requirements.txt
# Set your API keys
export OPENAI_API_KEY=sk-...
export ANTHROPIC_API_KEY=sk-ant-...
```

## Phase Overview & Quick Run

### Phase 1: FSM (Finite State Machine)
```bash
cd phase-01-fsm
python main.py
```
**What it does**: Deterministic state transitions for LLM workflows.
**Key concept**: Force non-deterministic models into predictable paths.

### Phase 2: Durable Execution
```bash
cd phase-02-durable
python main.py
```
**What it does**: Survive crashes mid-workflow with checkpointing.

### Phase 3: Retry & Fallback
```bash
cd phase-03-retries
python main.py
```
**What it does**: Exponential backoff + model fallback chains.

### Phase 4: DAG Pipelines
```bash
cd phase-04-dags
python main.py
```
**What it does**: Directed acyclic graphs for parallel LLM tasks.

### Phase 5-14: Advanced Topics
| Phase | Topic | Key Takeaway |
|-------|-------|-------------|
| 5 | Agent Runtimes | Tool-using autonomous agents |
| 6 | Model Routing | Pick the right model per task |
| 7 | Edge Inference | Run models on-device |
| 8 | RAG | Ground LLMs in your data |
| 9 | Memory | Short/long-term context |
| 10 | Multi-Agent | Coordinated agent swarms |
| 11 | Security | Prompt injection defense |
| 12 | Observability | Trace and debug LLM calls |
| 13 | Evaluation | Benchmark your system |
| 14 | Production | Deploy with confidence |

## Which Phase Should I Start With?
- **New to AI engineering?** → Phase 1 (FSM)
- **Building a chatbot?** → Phase 8 (RAG) + Phase 9 (Memory)
- **Need reliability?** → Phase 2 (Durable) + Phase 3 (Retries)
- **Multi-model setup?** → Phase 6 (Routing) + Phase 10 (Multi-Agent)
