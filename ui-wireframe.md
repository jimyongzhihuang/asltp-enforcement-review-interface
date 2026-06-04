# UI Wireframe Specification

## 1. Case Context Bar

The top bar displays the case ID, route status, and whether the file is still at the pre-consequence closure gate.

Legal function: the reviewer must know whether the case has already attached consequence or is still open for public-law closure.

## 2. Detection Root Panel

This panel shows the original factual trigger of enforcement.

Examples:

- detected speed;
- timestamp;
- detection device;
- threshold crossed;
- route entered.

Legal function: the reviewer must see what started the enforcement route.

## 3. Comparative Antidote Log

The main screen uses a two-column comparison.

| Left Column: Raw Human Response | Right Column: System Interpretation |
|---|---|
| Original words, documents, or transcript | System labels, scores, and recommendation |
| Human context and possible explanation | Administrative risk translation |
| Evidence before ASLTP conversion | Record after ASLTP conversion |

Legal function: this design prevents the reviewer from seeing only the system label. The reviewer must compare the human reality against the algorithmic transformation.

## 4. ASLTP Interception Matrix

The reviewer must confirm each ASLTP stage:

1. Affect — What human response is present?
2. Surface — How did the system see that response?
3. Label — What administrative label was attached?
4. Transform — What enforcement risk or route did the label produce?
5. Present — How was the transformation shown to the reviewer?

Legal function: each stage must be checked before public-law closure can occur.

## 5. Public-Law Closure Terminal

The footer contains:

- a reviewer reasons box;
- a closure checklist;
- a locked closure button.

The closure button becomes active only after all ASLTP stages are reviewed and reasons are entered.

Legal function: the UI models the principle that machine output must not become state consequence until a responsible human authority legally owns the route.

## 6. Review-Ready Record

The interface is designed to produce a review-ready enforcement record showing:

- Detection Root;
- Route History;
- ASLTP Antidote Log;
- Discretion Checkpoint;
- Closure Sign-off.
