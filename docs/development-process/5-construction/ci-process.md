---
sidebar_label: Continuous Integration Process
description: PROJECT NAME
---

# Continuous Integration Process

> Trunk-Based Development is a key enabler of Continuous Integration and by extension Continuous Delivery.

<br></br>

![Scaled Trunk-Based](../../assets/scaled-trunk-based.png)

1. Create a feature branch

2. Label commits with relevant work items

    - Ex. "SA-12: complete software design document"

3. Initiate pull request

4. Conduct [Code Inspection](./inspections/code-inspection.md)

5. Approve code into trunk / reject code

6. Delete branch


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