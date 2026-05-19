## LLM-Website-Tests

This repository is dedicated to testing how different Large Language Models (LLMs) generate websites based on a structured prompt pattern. The main goal is to evaluate and compare the capabilities of various LLMs in building a stylish, technically proficient, and accessible DevOps engineer resume as a single-file HTML webpage.

### Prompt Pattern
Each LLM is given a sequence of prompts to iteratively improve the generated webpage:

1. **Initial Prompt:**
	> Create a DevOps engineer resume as a HTML webpage that will be stylish while showing a technical expertise with statistics and some achievements / projects. All CSS and JS need to be in the same file and website has to follow the best of UX and UI design patterns.

2. **Enhancement Prompt:**
	> Make it more epic with more visual effects and animations

3. **Accessibility Prompt:**
	> Make the page follow the best industry standard accessibility guidelines and design patterns

### Repository Structure
- Each generated HTML file is stored in this repository, representing the output from a specific LLM and prompt stage.
- Alongside the HTML files, Copilot traces are included. These traces contain information about the chat and the generation process for transparency and reproducibility.

### Purpose
- **Comparison:** Assess how different LLMs interpret and execute complex, multi-stage web development prompts.
- **Best Practices:** Evaluate adherence to UX/UI and accessibility standards.
- **Showcase:** Provide examples of LLM-generated, single-file, stylish DevOps resumes with technical depth and modern design.

---
Feel free to explore the generated files and traces to see how each LLM approaches the challenge!
