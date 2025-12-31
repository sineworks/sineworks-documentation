---
sidebar_label: Construction Principles
description: Follow these principles during construction
---

# Construction Principles

## Managing complexity is Sineworks's Primary Technical Imperative.

> “Any fool can write code that a computer can understand. Good programmers write code that humans can understand.“ —Martin Fowler

---

### Write code for people first, computers second.

### Construction is tranforming the design into an executable program.

### Nothing less than quality code is acceptable.

- Quality code results in faster development.
- Quality code will be especially encouraged early in the construction process.
- Quality code is self-documenting.
- Every line of code will be reviewed and formally inspected.
- Quality examples will be documented and provided.
- Elegance is a requirement.
- Defects will be recorded with inspections, and defect hotspots will be noted.
- Testing is merely one way to ensure code quality and does not replace other methods.

### The construction process is highly iterative.

- Iterations serve to remove defects and improve code quality.
- Iteration encourages responding to change over following a plan.
- The primary purpose of formal inspections is to iterate.
- Iterations may include changing the design.

### Changes will be controlled through the change control procedure.

- Estimate the cost of changes.
- Relook design if there are a high volume of changes.

### Consistently re-estimate the construction schedule.

### Construction progress will be measured.


- Progress is not qualifiable.
- Progress is measured by working code.

## Principles of Continuous Integration

### Put source code into a version controlled mainline

- A minimally configured environment should be able to easily build, and run the product after cloning the repository
- It should be easy to find the code for a given piece of work
- The mainline is a single, shared branch that acts the current state of the product

### Automate the build

- Anyone should be able to bring in a clean machine, check the sources out of the repository, issue a single command, and have a running system on their own environment.

### Make the build self-testing

- Any programming task combines both modifying the functionality of the program, and also augmenting the test suite to verify this changed behavior

### Every push to mainline should trigger a build

- Utilize GitHub Actions

### Fix broken builds immediately

### Keep the Build Fast

- Set up a deployment pipeline

### Hide work-in-progress

- Utilize [keystone interfaces](https://martinfowler.com/bliki/KeystoneInterface.html)

### Test in a clone of the production environment

### Automate deployment



