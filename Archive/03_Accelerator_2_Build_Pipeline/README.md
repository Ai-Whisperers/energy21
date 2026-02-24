# Accelerator 2: Build Pipeline / Quality Automation

**Status:** Separate proposal to be created  
**Client:** Energy21 / Eneve + W.P.G. Weiss Poll Group

---

## Scope (from Three Accelerators transcript)

### What it does
- **CI/CD pipeline automation** — Build process produces quality reports (documentation, unit tests, CRAP score, licenses)
- **Automated fix cycle** — Report output → run prompt → make fix → commit → compile → new report → repeat
- **Current state:** Process exists; prompts are prepared; Eva has Cursor instances. Manual execution.
- **Goal:** Implement in N8N so the cycle runs automatically

### Key points from transcript
- "The workflow one is a complete workout process already. It's in the whole CI/CD pipeline we have feedback—a completely fine feedback loop but it needs to be automated."
- "At this moment we need to kick in prompt by prompt by prompt. Output from the build process can be directly fed into the next process to run."
- "Prompts that I already prepared are already prepared for N8N. All of those things are already there. They need to be implemented in N8N."
- "It should be the easiest one to set up. That one has also the biggest value."
- "Eva actually has already the cursor instances with all the prompts in it that do that flow."

### What gets fixed automatically
- Documentation (classes, functions not documented)
- Unit tests
- CRAP score
- License problems
- Warnings from build reports

### Deliverable format (per transcript)
- Executive summary: What the project is, what it costs, what it accelerates
- Short form for Gaston
- Detailed proposal

---

## Next steps
1. Gather exact list of prompts and build pipeline steps from Eva
2. Create proposal document
3. Price: $15,000 - $20,000 | Timeline: ~2 weeks ("easiest to set up")
