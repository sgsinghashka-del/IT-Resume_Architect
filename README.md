# IT Resume Architect

<p align="center">
  <strong>Prompt-driven resume analysis, optimization, and career guidance</strong>
</p>

<p align="center">
  <a href="https://github.com/sgsinghashka-del/IT-Resume_Architect"><img src="https://img.shields.io/github/stars/sgsinghashka-del/IT-Resume_Architect?style=flat-square" alt="GitHub stars"></a>
  <a href="https://github.com/sgsinghashka-del/IT-Resume_Architect/issues"><img src="https://img.shields.io/github/issues/sgsinghashka-del/IT-Resume_Architect?style=flat-square" alt="GitHub issues"></a>
  <a href="https://github.com/sgsinghashka-del/IT-Resume_Architect/commits/main"><img src="https://img.shields.io/github/last-commit/sgsinghashka-del/IT-Resume_Architect?style=flat-square" alt="Last commit"></a>
  <a href="https://github.com/sgsinghashka-del/IT-Resume_Architect/blob/main/README.md"><img src="https://img.shields.io/badge/documentation-README-blue?style=flat-square" alt="Documentation"></a>
</p>

## Overview

IT Resume Architect demonstrates how prompt engineering can be used to analyze, improve, and tailor resumes. It focuses on structured instructions, reusable prompt blocks, controlled outputs, and privacy-aware execution.

The repository currently includes the project documentation, the system prompt, and a sample ATS-friendly resume.


## What the project demonstrates

- Convert unstructured resume content into structured insights
- Extract skills, experience, and career signals
- Score resume quality and role alignment
- Identify career gaps and recommend improvements
- Support online LLM execution and deterministic offline processing
- Keep prompt logic, business rules, and presentation concerns separated

## Prompt architecture

The prompt workflow is designed around:

1. **Input normalization** — read and structure resume content.
2. **Context management** — preserve relevant information across prompt steps.
3. **Analysis** — extract skills, experience, gaps, and career signals.
4. **Optimization** — produce role-specific recommendations and resume improvements.
5. **Validation** — constrain output formats for predictable, explainable results.

## Repository contents

| File | Description |
| --- | --- |
| [`Chat gpt_API System Prompt`](./Chat%20gpt_API%20System%20Prompt) | System prompt used to guide resume analysis and optimization |
| [`Alex_Morgan_Software_Engineer_ATS_Resume.pdf`](./Alex_Morgan_Software_Engineer_ATS_Resume.pdf) | Sample ATS-friendly resume for demonstration |
| [`README.md`](./README.md) | Project documentation |

## Demo material

### Sample resume

Open the included [sample ATS resume](./Alex_Morgan_Software_Engineer_ATS_Resume.pdf) to inspect the document used as demonstration input.

### Prompt demonstration

Review the [ChatGPT API system prompt](./Chat%20gpt_API%20System%20Prompt) to see the instructions used for structured analysis, optimization, and career guidance.


## Installation and usage



1. Clone the repository:

   ```bash
   git clone https://github.com/sgsinghashka-del/IT-Resume_Architect.git
   cd IT-Resume_Architect
   ```

2. Open the sample resume:

   ```text
   Alex_Morgan_Software_Engineer_ATS_Resume.pdf
   ```

3. Review and adapt the system prompt:

   ```text
   Chat gpt_API System Prompt
   ```

4. To run an application, add the project source and dependency manifest (for example, `requirements.txt` or `pyproject.toml`) and document the framework-specific start command here.

## Planned capabilities

- Resume parsing from PDF and text inputs
- Skill distribution and career progression visualizations
- Role-specific job-description matching
- Offline, deterministic analysis mode
- Secure local storage and role-based access control
- Optional PostgreSQL and vector-search integrations

## Security and privacy

Do not commit real personal resumes, API keys, passwords, or other sensitive information. Use synthetic or redacted documents for demonstrations and keep secrets in environment variables.

## Author

**Ashka Singh**

## Contributing

Contributions and feedback are welcome. Please open an issue describing the proposed improvement before submitting a pull request.

