# Contribute a case

We collect outcomes with inspectable evidence and clear attribution. A useful everyday accomplishment is welcome alongside a scientific breakthrough.

## Submit

Start with the [case submission form](https://github.com/kaluli123123/ai-did-that/issues/new?template=submit-a-case.yml), or copy [the case template](templates/case-template.md) into `cases/` and open a pull request. Submissions in any supported language are welcome. Use a short descriptive filename and add a brief README entry linking to the full case. English is the editorial source for synchronized translations. Maintain the complete account in the case file; keep the index concise.

## Selection standard

Every case needs an observed result, an identifiable AI system, a specific explanation of its contribution, human credit, a dated source, and material limitations. Product announcements without demonstrated outcomes, benchmark scores presented as real-world deployment, and unsupported promotional claims need more evidence before inclusion.

Use primary papers, project artifacts, official reports, or direct participant accounts. Explain what each source supports. A press announcement and a paper from the same team are not two independent confirmations. A working link alone does not verify a claim.

### Evidence labels

| Label | Meaning |
| --- | --- |
| Published research | A research paper reports the result. Publication does not mean this repository has replicated it. |
| Project-reported result | The responsible project describes its outcome and review process. Identify the organizer or provider. |
| Provider-reported deployment | An organization reports a production result from its own systems. Attribute its numbers. |
| Firsthand account | A contributor describes their own experience. State whether an artifact or independent check is available. |

Choose the best-fitting label and describe additional evidence separately. Reserve independent-replication claims for a named independent source that actually repeated the relevant result.

### Keep claims precise

- Distinguish predictions, experiments, demonstrations, and deployments.
- Report dates, measured quantities, baselines, and relevant conditions. Do not convert compute capacity into money saved without evidence.
- Explain what people provided: training data, hardware, instructions, editing, validation, or deployment.
- Identify specialized models separately from general-purpose assistants; do not imply that a chatbot can reproduce every case.
- Include limitations and what was not independently checked. Use the date the sources were actually inspected as the source-check date.

## Review and corrections

See [language editions and review status](LANGUAGES.md). Translated introductions and summaries should preserve dates, quantities, sources, human credit, and limitations. Native-speaker review is welcome. Keep English full-case links explicitly labeled in translated editions. If a source claim changes, update its translations or label affected editions as outdated.

A maintainer checks the sources, attribution, scope, and index wording before accepting an entry. Public submissions are suggestions, not approved cases. Review can result in acceptance, a request for evidence, or rejection with a reason.

Use the [correction form](https://github.com/kaluli123123/ai-did-that/issues/new?template=correction.yml) for factual errors, missing credit, source changes, or accessibility issues. Update both a case and its README summary when the claim changes. Record material corrections under a dated `Corrections` section in the case. Remove or qualify entries whose evidence no longer supports them.

There is no build step. Before submitting, preview Markdown, check relative links and source destinations, and ensure the required case sections are complete. For SVG changes, check legibility and alternative text in both light and dark surroundings.

## Rights and conduct

Contribute original text and artwork you can license under the [MIT License](LICENSE). Cite and link third-party work rather than copying its images or article text. Linked papers, code, and datasets retain their own terms. Do not post private data. Keep discussion focused on evidence and treat contributors and research participants respectfully.
