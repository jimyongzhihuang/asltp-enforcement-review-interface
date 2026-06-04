# ASLTP Enforcement Review Interface

A static legal-engineering prototype for the **ASLTP Antidote Log** and **Review-Ready Enforcement Record** described in the paper:

**Who Holds Discretion? AI-Assisted Enforcement, Route Literacy, and Public-Law Closure Before Consequence**

## Purpose

This repository demonstrates how a public authority using AI-assisted enforcement could visually separate:

1. the original human response;
2. the system's surface reading;
3. the system-generated label;
4. the transformation into enforcement risk; and
5. the final presentation to a human reviewer.

The purpose is not to build production software. The purpose is to show how **route literacy**, **ASLTP**, and **public-law closure** can be translated into a simple review interface.

## Legal Problem

In machine-assisted public enforcement, a system may detect, classify, score, route, recommend, and generate records before a responsible human authority reviews the file.

The risk is not only technical error. The risk is that human response may be converted into enforcement risk without legally controlled interpretation.

ASLTP describes this movement:

- **Affect**: the human response produced by contact with enforcement power.
- **Surface**: the form in which that response becomes visible to a system.
- **Label**: the administrative tag attached to the surface.
- **Transform**: the conversion of the label into risk, priority, escalation, or record status.
- **Present**: the later appearance of that transformation as official record, reason, or recommendation.

## Prototype Logic

The interface requires the reviewer to compare:

- the raw human response; and
- the system-generated enforcement interpretation.

The closure button remains locked until all five ASLTP stages are reviewed. This models the paper's claim that **human-in-the-loop is not enough**. A responsible human authority must identify the route, review the human response, correct or reject improper labels, give reasons, and legally own the consequence before enforcement action attaches.

## Repository Structure

- `README.md` — theoretical framing.
- `ui-wireframe.md` — interface structure and public-law logic.
- `sample-case.json` — fictional demonstration data.
- `prototype.html` — single-file static UI prototype.

## Disclaimer

This is a fictional academic prototype. It does not represent any real enforcement matter, real person, real public authority, or production system.
