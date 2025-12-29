---
sidebar_label: Code Inspection
description: PROJECT NAME
---

# Code Inspection

<h1> `<Project Name>` </h1>
<h3> `<System / Feature>` </h3>

TODO: Notes: how are we going to determine the scope of the inspections, or what we are expecting?
Defect Classifications:
-Clarity
-Completeness
-Consistency
-Functionality
-Compliance
-Maintenance
-Level of Detail
-Traceability
-Reliabilty
-Performace
-Other

---

[Setting up a software quality inspection](https://www.design-reuse.com/article/57187-esc-setting-up-inspection-for-software-quality/)

[Google Style Guide](https://google.github.io/styleguide/tsguide)

## Functionality

- [ ] Code performs function as established by requirements.
- [ ] Does the code completely and correctly implement the design?
- [ ] Code avoids additional functionality.
- [ ] Code doesn't pre-optimize for future conditions.


## Structure

- [ ] Code adheres to the provided style guide.
- [ ] Code is abstracted properly.
- [ ] Does the code conform to any pertinent coding standards?
- [ ] Is the code well-structured, consistent in style, and consistently formatted?
- [ ] Are there any uncalled or unneeded procedures or any unreachable code?
- [ ] Are there any leftover stubs or test routines in the code?
- [ ] Can any code be replaced by calls to external reusable components or library functions?
- [ ] Are there any blocks of repeated code that could be condensed into a single procedure?
- [ ] Are symbolics used rather than “magic number” constants or string constants?
- [ ] Are any modules excessively complex and should be restructured or split into multiple routines?

## Documentation

- [ ] Code is written to be self-documenting.
- [ ] Is the code clearly and adequately documented with an easy-to-maintain commenting style?
- [ ] Are all comments consistent with the code?

## Variables

- [ ] Are all variables properly defined with meaningful, consistent, and clear names?
- [ ] Do all assigned variables have proper type consistency or casting?
- [ ] Are there any redundant or unused variables?

## Arithmetic Operations

- [ ] Does the code avoid comparing floating-point numbers for equality?
- [ ] Does the code systematically prevent rounding errors?
- [ ] Does the code avoid additions and subtractions on numbers with greatly different magnitudes?
- [ ] Are divisors tested for zero or noise?

## Loops and Branches

- [ ] Are all loops, branches, and logic constructs complete, correct, and properly nested?
- [ ] Are the most common cases tested first in IF- -ELSEIF chains?
- [ ] Are all cases covered in an IF- -ELSEIF or CASE block, including ELSE or DEFAULT clauses?
- [ ] Does every case statement have a default?
- [ ] Are loop termination conditions obvious and invariably achievable?
- [ ] Are indexes or subscripts properly initialized, just prior to the loop?
- [ ] Can any statements that are enclosed within loops be placed outside the loops?
- [ ] Does the code in the loop avoid manipulating the index variable or using it upon exit from the
loop?

## Error Handling

- [ ] Errors are handled, not swallowed.
- [ ] Error messages are useful for debugging.
- [ ] Error messages don't create security vulnerablilites.

## Security

- [ ] Inputs are validated and sanitized.
- [ ] No hardcoded secrets, keys, or credentials.
- [ ] Sensitive data is encrypted or protected.
- [ ] No injection vulnerabilities (SQL, command, template, etc.)

 
## Defensive Programming

- [ ] Are indexes, pointers, and subscripts tested against array, record, or file bounds?
- [ ] Are imported data and input arguments tested for validity and completeness?
- [ ] Are all output variables assigned?
- [ ] Are the correct data operated on in each statement?
- [ ] Is every memory allocation deallocated?
- [ ] Are timeouts or error traps used for external device accesses?
- [ ] Are files checked for existence before attempting to access them?
- [ ] Are all files and devices are left in the correct state upon program termination?

---

## Defect Log

**Error types**: TODO: create types

**Severity**: Major, Minor

| Error No. | Page/Line No. | System/Component | Type | Severity | Description |
| --------- | ------------- | ---------------- | ---- | -------- | ----------- |
|           |               |                  |      |          |             |
|           |               |                  |      |          |             |

---


## Approval

- [ ] Approved
- [ ] Rejected

**Reason for rejection:**


**Name of Approver:**  
**Date:**