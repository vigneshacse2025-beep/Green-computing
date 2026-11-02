# Green Computing and Energy-Efficient Software Awareness

**CSE Capstone Project | Capstone 36**

This repository contains a student-ready awareness and demonstration project answering:

> How can AI help teach students to write and run software in a more energy-efficient way?

The project combines research, a green-software checklist, an article, a small Python code-variant benchmark, a quiz, presentation content, and an AI-prompt/verification log.

## Project objectives
- Explain how computing uses energy and why software choices matter.
- Teach practical green-software habits.
- Compare two implementations using repeatable runtime measurements.
- Demonstrate responsible use of AI research and writing tools.

## Repository contents

| Path | Purpose |
|---|---|
| `research/research-summary.md` | Background, research questions, and source list |
| `research/verification-report.md` | Fact-checking and measurement limitations |
| `article/carbon-impact-of-computing.md` | Awareness article with references |
| `checklist/green-software-checklist.md` | Practical checklist for students and campus IT |
| `code/benchmark.py` | Runs two equivalent code approaches and logs timing estimates |
| `code/README.md` | Instructions and interpretation notes |
| `quiz/quiz.md` | 10-question quiz and answer key |
| `presentation/slide-deck.md` | Six-slide presentation outline |
| `infographic/green-computing-habits.svg` | Editable vector infographic |
| `prompts/prompt-library.md` | Reusable prompts for research, writing, code review, and verification |
| `analysis/before-after-analysis.md` | Example of how to document improvements |
| `demo/final-demo.md` | Suggested final demonstration plan |

## Quick start
1. Download or clone this repository.
2. Install Python 3.9 or newer; no third-party packages are required.
3. Run:
   ```bash
   python code/benchmark.py --n 100000
   ```
4. Review the generated CSV file in `code/results/`.
5. Read the report and checklist, then adapt the presentation for your class.

## Important interpretation note
The benchmark records wall-clock runtime and calculates a **rough energy estimate** using a user-selected average power assumption. It does **not** directly measure electricity consumption. Actual energy depends on hardware, processor load, power management, runtime environment, and other processes. Use a power meter or validated hardware telemetry for a real energy measurement.

## Recommended workflow
1. Use the sources in `research/research-summary.md` as starting points.
2. Verify each statistic against the linked primary source before presenting it.
3. Run the benchmark several times and report the median, not just one run.
4. Keep the machine, Python version, input size, and other conditions as consistent as possible.
5. Do not claim that one short benchmark proves a universal energy saving.

## Suggested GitHub repository description
`A student capstone project on green computing, sustainable software practices, code runtime comparison, and AI-assisted awareness materials.`

## License
Educational use. You may adapt this project for your coursework. Verify citation and institutional requirements before submission.
