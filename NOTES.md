# Teaching Notes

## User Profile
- BCA student, goal: pass semester exams
- Knows C basics: loops, functions, pointers, structs
- DS is new territory

## Preferences
- Exam-focused: theory explanations + C code implementations
- No need to re-teach C syntax

## Exam Paper Pattern (from 16 May revision class)
- Section A: MCQs (definitions, complexity values, LIFO/FIFO traces)
- Section B: case study + write C code, 7.5 marks each
- Code + short explanation = best (~7 max; teacher never gives 7.5)
- Code only = 4.5–5; pseudocode WITH explanation = partial; NEVER leave blank
- Method to teach: flowchart first → translate to C line by line
- Questions are basic but framed "tricky" on purpose

## Source-of-truth handling
- PDF = source of truth. Extracted to `pdf_extracted.txt` via `pdftotext -layout` (pdftoppm missing, but pdftotext works). Grep this file to verify any fact.
- Transcripts = signal for WHAT to master, not truth.
- Known conflict: teacher said algorithm "at least one input"; SLM says "zero or more". Use SLM.
- SLM has end-of-module self-assessment MCQs (good practice) — search pdf_extracted.txt for "What is".

## Session Notes
- Built `reference/exam-blueprint.html` = master tiered extraction of all exam signals. Central doc.
- Lessons follow the blueprint's "Hit List" order. Done: L1 intro, L2 infix→postfix.
- Next lesson priorities: stack push/pop code → linear/binary search → insertion sort.
