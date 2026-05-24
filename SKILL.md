---
name: cn-econ-management-literature-review
description: Draft, expand, restructure, or review Chinese academic literature reviews in economics and management with verified sources, sequential numeric in-text citations, GB/T 7714 reference lists, strict one-use-per-source citation control, and synthesis-oriented logic. Use for Chinese journal papers, dissertations, theses, project applications, reports, and literature review sections in economics, management, finance, industrial economics, digital economy, innovation, entrepreneurship, policy, and sports economy or management.
---

# 中文经济管理文献综述

## Core Goal

Write Chinese economics and management literature reviews that are evidence-grounded, logically synthesized, and citation-safe. Treat citation accuracy as a hard constraint, not a formatting detail.

## Non-Negotiable Rules

- Verify every cited source before use through supplied PDFs, user-provided bibliographic records, academic databases, publisher pages, DOI/Crossref records, government or international organization pages, or other reliable sources.
- Never invent authors, titles, journals, years, volume/issue numbers, pages, publishers, DOIs, report names, or URLs.
- Use sequential numeric citations in the body, such as `[1]`, `[2]`, `[3]`.
- Format the reference list according to GB/T 7714.
- Use each source in the body exactly once. After a source is cited, do not cite it again later, even for related claims.
- Make every citation support the exact sentence it is attached to. Do not cite a source for a broader, narrower, or different claim than it actually supports.
- If verified, non-repeating sources are insufficient, narrow the claim, shorten the section, mark the gap, or ask for more sources. Do not fill gaps with weak, repeated, or fabricated citations.
- Do not show the search or verification process unless the user asks for it.

## Workflow

1. Define the review task: topic, discipline, research object, intended output, time span, and whether the text is for a journal article, dissertation, proposal, or report.
2. Build a citation ledger before drafting. Track each source's verified metadata, supported claim, source type, and whether it has already been used.
3. Design the review architecture around concepts, theories, mechanisms, methods, empirical evidence, disagreements, and research gaps.
4. Assign citations at the sentence level. Match each key sentence to verified, unused sources before writing the final prose.
5. Draft the review in formal Chinese academic style, with vertical evolution and horizontal comparison.
6. Output the GB/T 7714 reference list in the order of first appearance.
7. Run the citation integrity checklist before finalizing.

## Citation Sentence Types

Use two main sentence-level citation patterns.

### Synthesis Sentences

Use synthesis sentences for generalized claims, category summaries, mechanism summaries, or cross-study conclusions. A synthesis sentence should usually cite two to four distinct, unused sources at the sentence end.

Pattern:

```text
围绕某一研究问题，既有文献主要从理论路径A、机制路径B和情境条件C三个方面展开解释[1][2][3]。
```

Rules:

- Ensure each cited source directly supports the synthesized sentence.
- Do not attach many sources to a vague sentence such as "相关研究较为丰富".
- Do not use a synthesis sentence to hide uncertainty or disagreement. If the sources conflict, state the conflict.
- Do not cite the same source again later after it appears in a synthesis sentence.

### Specific Study Sentences

Use specific study sentences when describing one article, book, report, dissertation, or identifiable research design. The author or research object may appear in the sentence, but the citation marker remains numeric.

Pattern:

```text
某项基于特定样本和方法的研究发现，变量A与结果B之间存在特定关系[4]。
```

Rules:

- Use one citation for one specific study sentence unless the sentence explicitly compares multiple studies.
- Include the study's sample, method, setting, or key finding only when the verified source supports that detail.
- Do not overstate the finding as causal, universal, or conclusive unless the source's design supports that interpretation.
- Do not turn every paragraph into a list of specific study sentences; connect them through synthesis and critique.

## Review Logic Standard

Do not write a literature review as a mechanical sequence of "one scholar plus one finding" sentences. Each paragraph must perform at least one analytical function:

- define or delimit a concept
- trace theoretical development
- classify mechanisms or explanatory paths
- compare methods, data, or research settings
- identify consistent findings and boundary conditions
- explain disagreement or mixed evidence
- expose an unresolved gap
- position the current study without using second-person language

Combine vertical and horizontal logic:

- Vertical logic: show how the research question, theory, method, or evidence evolved over time.
- Horizontal logic: compare different theoretical perspectives, mechanisms, datasets, methods, sectors, regions, or institutional contexts.

## Style Rules

- Use formal, precise Chinese academic prose.
- Avoid empty phrases such as "具有重要意义", "非常重要", "学者们进行了大量研究", "值得我们关注", and "在你的研究中".
- Avoid unsupported absolutes such as "已经证明", "一致认为", "毫无疑问", and "必然导致".
- Prefer claim-first paragraphs: topic sentence, evidence synthesis, comparison or critique, and transition to the next issue.
- Use cautious wording when evidence is partial, context-bound, or method-dependent.

## Output Requirements

For drafting tasks, output:

1. Title or section heading
2. Literature review body with sequential numeric citations
3. `参考文献` list in GB/T 7714 format

For review or revision tasks, output:

1. Main issues in logic, synthesis, or citation safety
2. Revised structure or revised prose
3. Citation gaps or sources that require verification

## References

Load only the needed reference file:

- `references/gbt7714-rules.md` for citation placement and reference-list formatting.
- `references/review-logic-patterns.md` for literature review structure and synthesis patterns.
- `references/citation-integrity-checklist.md` before finalizing any cited output.
