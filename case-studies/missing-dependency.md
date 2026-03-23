---
layout: default
title: Diagnosing a Missing Dependency in a Complex System
permalink: /case-studies/missing-dependency/
---

# Case Study: Diagnosing a Missing Dependency in a Complex System

*Example from biochemical pathway analysis during my PhD research*

## Overview

During my PhD research, I investigated a biochemical activation pathway whose behavior did not match the prevailing model. Instead of continuing to iterate on the existing hypothesis, I reframed the problem as a system workflow analysis—examining the functional requirements needed for the system to operate as expected.

By identifying a missing dependency in the system and redesigning the workflow to include it, I was able to restore system function and reveal the underlying mechanism driving activation.

Although this example comes from a molecular system, the same approach applies directly to operational environments where missing inputs, unclear dependencies, or broken information flow prevent systems from functioning reliably.

## Impact

- Identified a **previously unrecognized functional requirement** in a complex biochemical system  
- Restored system performance by introducing a missing component rather than redesigning the entire system  
- Demonstrated a transferable approach to **root cause analysis and system diagnosis**  
- Established a framework for analyzing failure in multi-component systems  

## Visual Summary

Image coming soon!

## Operational Scope

- **System type:** Multi-component biochemical pathway  
- **Scale:** Molecular system  
- **Complexity:** Interdependent components with incomplete mechanistic understanding  
- **Failure mode:** Activation fails despite presence of expected catalytic components  

## Challenge

The system was expected to activate a cofactor through a metal-catalyzed process. However, prior evidence suggested this system functioned without metal, distinguishing it from all known examples. While activation occurred *in vivo*, it failed entirely when using isolated components *in vitro*.

This created an ambiguous and potentially intractable problem:

- The system functioned in cells but could not be reconstituted experimentally  
- The mechanism enabling metal-independent activation was unknown  
- Iterative testing of known variables (e.g., metal identity and timing) did not resolve the failure  

These observations indicated that the issue was not incorrect component selection, but a missing functional dependency—a required input present *in vivo* but absent from the *in vitro* system.

## Approach

I shifted from optimizing known variables to diagnosing the system structure, reframing the problem as a question of missing dependencies:

> If activation occurs *in vivo* but fails *in vitro*, what required input is present in the cellular environment but absent from the reconstituted system?

Key steps included:

- Defining the system as a workflow with required inputs and outputs, rather than a collection of components  
- Using the *in vivo* vs *in vitro* discrepancy to identify the failure as a missing functional dependency 
- Recognizing electron transfer as a required step absent from the existing model  
- Leveraging knowledge of analogous systems to identify flavin reductases as likely providers of reducing equivalents  
- Formulating and testing a hypothesis that a missing electron transfer mechanism was preventing activation  

## Process Improvements Implemented

- Redesigned the system to incorporate a candidate reductase as a **missing functional input**  
- Constructed a **minimal system** to isolate required components and eliminate confounding variables  
- Shifted from iterative variation of known parameters to targeted validation of a system-level hypothesis  
- Reoriented the approach from optimizing components to identifying and restoring **missing dependencies within the workflow**  

## Outcome

- Introduction of the reductase **enabled cofactor activation** ***in vitro***  
- Confirmed that the failure was due to a **missing electron transfer mechanism**, not incorrect component selection  
- Established a **functionally complete system model** consistent with observed behavior  
- Resolved a previously ambiguous and potentially intractable problem through **system-level diagnosis**  

## Long-Term Impact

- Provided a framework for analyzing systems where function depends on unrecognized inputs or interactions  
- Demonstrated that system failure can arise from missing dependencies rather than faulty components
- Reinforced the importance of evaluating inputs, interfaces, and flow in complex systems  
- Established an approach directly applicable to operational environments where incomplete workflows lead to failure  

## Skills Demonstrated

- Systems thinking and workflow-based problem framing
- Root cause identification in complex, ambiguous environments
- Hypothesis-driven problem solving grounded in system constraints
- Designing targeted experiments as tools for system interrogation
- Identification of hidden dependencies and failure points across interconnected components
- Translating domain-specific challenges into generalizable system-level insights

## Reflection

This project reinforced that system failures are not always caused by incorrect components, but often arise from missing or unrecognized dependencies within the workflow.

By shifting from optimizing known elements to identifying what was absent, I was able to restore system function without redesigning the entire system. This approach—examining how inputs are introduced, how components interact, and where dependencies may be missing—applies directly to diagnosing and improving operational systems in industry settings.


---

Return to [Case Studies](/case-studies/index/)
