---
layout: default
title: Beamtime Coordination System Redesign
permalink: /case-studies/beamtime-coordination/
---
# Case Study: Beamtime Coordination System Redesign

## Overview

During my graduate research, I coordinated crystallography data collection at national synchrotron facilities. These experiments required managing a complex workflow that included proposal submissions, facility access approvals, sample preparation, cryogenic shipping logistics, remote data collection scheduling, and post-collection sample handling.

Initially, this entire process depended on a single individual—myself—who managed every aspect of coordination. While the system functioned, it created a major operational risk: the workflow relied heavily on undocumented institutional knowledge and could not easily be transferred to other team members.

When I prepared to take maternity leave, I redesigned the workflow to make it documented, transferable, and sustainable for a larger team.

## Impact

- **10–20 active users** supported per beamtime session
- **35+ total users** across **6 research labs**
- **1–2 beamtime sessions per month** during active run cycles
- Expanded from **2 beamlines** to **3 total beamlines** while maintaining the same coordination system
- Reduced dependency on a single coordinator and enabled sustainable team-based operation

## Visual Summary

<div style="text-align: left;">
  <img src="/assets/images/Beamtime_Redesign_flow.png"
       alt="Beamtime Coordination System Redesign"
       style="display: inline-block; max-width: 100%; height: auto;">
</div>

*This redesign transformed beamtime coordination from a single-person dependency into a structured, team-based workflow supported by standardized processes and operational controls, enabling reliable coordination for more than 35 researchers across six laboratories and multiple national synchrotron facilities.*

## Operational Scope

The beamtime coordination system supported a large and distributed research operation involving:

- multiple national synchrotron facilities
- distinct credentialing systems and scheduling procedures at each facility
- 10–20 active users per beamtime session
- more than 35 total users across six research laboratories

Our group initially collected data at two beamlines, each operating on roughly three-month run cycles. These facilities typically provided two to three data collection sessions per cycle, resulting in approximately one to two beamtime sessions per month during active periods.

Because the beamlines scheduled independently—and one facility assigned collection dates without flexibility—beamtime sessions sometimes occurred close together. Coordinating these events required careful planning to ensure samples, equipment, and personnel were prepared across multiple laboratories.

## Challenge

Coordinating beamtime required managing multiple interconnected processes:

- proposal preparation and submission
- facility credentialing and user access management
- sample preparation and cryogenic shipment logistics
- coordination of remote data collection sessions
- communication with researchers during beamtime
- data transfer and storage
- sample return, storage, and equipment cleanup

Before redesign, the workflow depended on a single coordinator, responsibilities were informal, and key requirements—especially those tied to facility compliance—were not systematically documented.

This created several operational risks:

- critical knowledge existed only in one person’s experience
- responsibilities were unclear to other team members
- facility compliance steps could be overlooked
- the lab lacked continuity if the primary coordinator was unavailable
- the process had limited scalability as the user base and facility complexity grew

## Approach

I approached the problem as a system design challenge, focusing on reliability, continuity, and scalability:

> *How can beamtime coordination be structured to eliminate single points of failure, ensure consistent execution across users, and remain scalable as system complexity increases?*

This led to a redesign of the system around clearly defined roles and standardized workflows:

### Beamtime Manager

A single individual responsible for administrative coordination and interactions with synchrotron facilities.

**Responsibilities included:**

- proposal preparation and submission
- beamtime scheduling
- facility credentialing and user access
- coordination with beamline staff
- oversight of overall beamtime logistics

### Beamtime Facilitator (Rotating Role)

A rotating role within the lab responsible for operational execution.

**Responsibilities included:**

- sample preparation coordination
- cryogenic shipment logistics
- communication during beamtime
- sample return and storage
- equipment cleaning and preparation

This structure separated strategic coordination from operational execution, allowing multiple team members to participate without requiring deep institutional knowledge of the full system.

## Process Improvements Implemented

To support the redesigned structure, I formalized the workflow using several operational tools.

### Standard Operating Procedure (SOP)

I created a comprehensive SOP describing the entire beamtime process from proposal submission through post-collection cleanup.

### Credential Access Guides

I developed step-by-step instructions for obtaining required access credentials at synchrotron facilities, reducing friction and ambiguity for users.

### Beamtime Facilitator Checklists

I built quick-reference checklists for Beamtime Facilitators to ensure consistent execution during each phase of the process.

These checklists clearly identified which steps were **facility compliance requirements** versus internal lab procedures, helping ensure that critical requirements were never missed.

### Standardized Turnaround Window

I also established a **minimum turnaround time** between beamtime sessions. This ensured that equipment and samples could be received, processed, cleaned, and prepared for the next shipment without requiring the purchase of additional cryogenic shipping dewars.

This change helped maximize beamtime utilization while minimizing equipment costs.

## Outcome

After redesign, beamtime coordination became a structured, team-based system supported by **documented procedures, defined roles, and repeatable operational controls**.

Key results included:

- beamtime operations continued smoothly during my maternity leave
- responsibilities could be rotated among lab members
- compliance with facility requirements became standardized
- onboarding new users became significantly easier
- the system remained in use after my return and continued supporting the lab

Most importantly, the workflow no longer depended on a single individual. What had previously been an informal and vulnerable system became a sustainable operational model.

## Long-Term Impact

The redesigned system proved resilient during major operational change.

When the Advanced Photon Source (APS) shut down for upgrades, our group transitioned to two new synchrotron beamlines at different facilities. Because the workflow was modular and well documented, the team adapted quickly to the new environments.

When APS later returned online, the lab expanded operations across three total beamlines while continuing to use the same coordination system.

This demonstrated that the redesigned process was not only transferable, but also scalable.

## Skills Demonstrated

- process analysis and redesign
- workflow standardization
- SOP development
- cross-team coordination
- knowledge transfer
- operational continuity planning
- cost-conscious resource management
- scalable systems design

## Reflection

I developed this system years before learning the formal language of Lean Six Sigma. At the time, I was not thinking in terms of DMAIC, role redesign, standard work, or process controls—I was simply solving a systems problem in the way that came most naturally to me.

Looking back, this project reflects the kind of work I am consistently drawn to: identifying operational risk, clarifying responsibilities, reducing friction, and building systems that are durable enough to function beyond any one individual.

