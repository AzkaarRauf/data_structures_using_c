# Exam Intel Extracted from 4 Lecture Transcripts

The user provided 4 recorded class transcripts (11 Apr intro/C-basics, 12 Apr stacks/queues, 19 Apr linked lists, 16 May revision/LMR + searching/sorting). All exam-relevant signals are now distilled in `reference/exam-blueprint.html`, tiered by certainty and cross-checked against the SLM PDF (`pdf_extracted.txt`). The SLM is source of truth; transcripts only signal *what to master*.

**Highest-certainty exam items (TIER 1):** Infix→Postfix (teacher: "at least one question", table method only — no shortcuts); stack push/pop code; linear + binary search (iterative); one sorting algo (insertion) cold; arrays + array-vs-linked-list.

**Paper pattern:** Section A MCQs (definitions, complexity values) + Section B case study/code at 7.5 marks. Code + line explanation = best (~7 max, never 7.5); code only = ~4.5–5; pseudocode WITH explanation = partial; never leave blank. Method taught: flowchart first, then translate to C.

**Notable SLM-vs-teacher conflict:** teacher said algorithm needs "at least one input"; SLM says "zero or more inputs, one or more outputs." Exam answer follows SLM.

**Queue:** concept only, NO direct coding question (teacher stated). But expect a trace-the-FIFO-output MCQ. Binary-search-with-recursion will NOT appear (that's MCA).

**Implications:** Lessons should be built in Hit List order from the blueprint. Lesson 2 (infix→postfix) already done. Next priorities: stack push/pop code, then linear/binary search.
