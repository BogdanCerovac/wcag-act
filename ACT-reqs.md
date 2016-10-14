ACT Framework Requirements
==========================

Abstract
--------

The Accessibility Conformance Testing Framework will be a W3C Recommendation, developed by the ACT Taskforce, lead by the WCAG Working Group. This document outlines the requirements for the ACT Framework. The ACT Framework is one part of the deliverables of the ACT Taskforce, for more details on this read [[ACT Deliverables]].

Status of This Document
-----------------------

This is the first draft of this document. It has not yet been submitted for formal review to the WCAG Working Group.

1. Introduction
---------------

The Accessibility Conformance Testing (ACT) Framework will be a recommendation on how to write rules for accessibility conformance testing. For an introduction on Accessibility Conformance Testing, read [What is ACT](https://www.w3.org/WAI/GL/task-forces/conformance-testing/wiki/ACT_Overview_-_What_is_ACT).

The ACT Framework is developed by the [ACT Taskforce](https://www.w3.org/WAI/GL/task-forces/conformance-testing/), lead by the [WCAG Working Group](https://www.w3.org/WAI/GL/). The ACT Framework will standardize those aspects all rules have in common that ensure them to be reliable, implementable by different ATTs and transparent for the users of this tool. By standardizing this, the ACT Taskforce aims to promote a common understanding of how accessibility can be tested for certain technologies.

Development and implementation of ACT Rules are outside the scope of the ACT Framework. This work is currently done within the [Auto-WCAG Community Group](https://www.w3.org/community/auto-wcag/). The ACT Taskforce support the Auto-WCAG Community group in the development of the first set of ACT Rules.

2. Requirements
---------------

### 2.1 Ensure Readability

The ACT Framework should ensure that the rules are readable by both tool developers and less-technical users. For instance, the ACT Framework may discourage the use of pseudo code in favor of plain English.

### 2.2 Ensure Justification

The ACT Framework should ensure that ACT Rules are well grounded in the requirements they test. It is insufficient for an ACT Rule to merely claim something violates a requirement. The ACT Framework has to ensure that ACT Rules document why its claims are a valid interpretation of the requirement.

### 2.3 Ensure Consistency

The ACT Framework has to ensure that ACT Rules can be implemented in a way that produces consistent results. An ACT Rule must include a way to test the implementation of that rule.

### 2.4 Ensure Measurable Accuracy

The ACT Framework will provide criteria and benchmarking mechanism to validate and measure the accuracy of test rules. Note: Accuracy is difference of actual test results to expected results.

### 2.5 Ensure Evolution

As web technologies change, the rules for testing them should change as well. Because of this it is important that ACT Framework outlines a way to deal with that. Rules should be dated and versioned, so that users of rules can understand that a rule needs to be updated. A possible approach to this could be semantic versioning, although there are many other possibilities.

### 2.6 Existing Rulesets can be Transformed to ACT Rules

The ACT Framework will provide support for different organizations and vendors to migrate their test rules into the required format. This may include mappings to other formats, and tolerance for different test rules structures and parameters where possible

### 2.7 Accessibility Support

The ACT Framework ensures that ACT Rules consider difference in assistive technologies. ACT Rules can be configured to use or ignore accessibility features that are not consistently implemented. Gathering accessibility support data is outside the scope of ACT Rule design.

### 2.8 Run As Negative Feature Tests

ACT Rules are negative feature tests. Meaning they can test if some accessibility requirement is not met. Testing if such requirement was met is outside the scope of ACT Rules and should be left up to expert accessibility evaluators.

### 2.9 Provide a common output format

The ACT Framework must ensure that results from ACT Rules can be aggregated to gain higher level insight. This must be possible across tools, so that the output of different tools can complement each other. This could be particularly useful to aggregate accessibility for different technologies.

### 2.10 Rules Not Included


### 2.11 No New Accessibility Requirements


### 2.12 Automation and Manual Rules


### 2.13 Applicable to Web and Digital Publishing Technologies


### 2.14 Useable With Different Accessibility Requirements


### 2.15 Leverages WCAG Failure Techniques




Definitions
-----------

### Rule

A rule is the description of the procedure used to evaluate the status (pass or fail) of one ore more conditions of a requirement in a given context.

The rule defines:

* the context in which it is applicable (e.g. a set of elements in a DOM)
* a set of assumptions about the environment (e.g. the way in which technologies are used)
* a set of logical steps to carry out the procedure
* a set of possible results

### Test

A test is the application of a rule.

### Requirement

A requirement is a statement of necessity in a given domain (e.g. accessbility). It can be broken down into a set of conditions.
