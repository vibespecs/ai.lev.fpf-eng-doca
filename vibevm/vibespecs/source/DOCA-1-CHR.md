# DOCA.1.CHR - Characterize the Development Subject and Intended Change: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Development Opportunity Construction and Development-Direction Advising Principles Framework* (2026-09-29), `Engineering DPF Suite/DEVELOPMENT-OPPORTUNITY-CONSTRUCTION-AND-DEVELOPMENT-DIRECTION-ADVISING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DOCA.1.CHR:5 - Archetypal Grounding {#archetypal-grounding}

### DOCA.1.CHR:5.1 - Person and representative later Work {#person-and-representative-later-work}

Mira's bounded inquiry concerns incident-review and handoff Work over four months. “Become better at AI” is discarded as a characteristic. The selected characteristics are: time to identify a material handoff gap, quality of the explanation supplied to the next reviewer, ability to detect unsupported model output, confidential-data exposure, review workload, and transfer to two representative incident classes.

The current account has qualified examples for explanation quality and workload, but no comparable evidence for transfer or unsupported-output detection. Those readings remain unknown. The intended contribution is faster detection without worsening explanation quality, confidentiality, or sustainable workload. HCD owns the human demand, capability, support, and transfer evidence. The characterization returns those useful readings and unknowns; it supplies no course recommendation or transfer claim. Representative-Work evidence becomes a request only when the attainable contribution warrants acquisition for the next use.

### DOCA.1.CHR:5.2 - Organization without one maturity score {#organization-without-one-maturity-score}

An engineering organization is called “low maturity” because releases are slow. The inquiry concerns reliable product-family delivery over twelve months. The characterization separates release lead time, rework, service interruption, platform reuse, security exposure, scarce-specialist attention, team autonomy, and customer-impact distribution.

Lead time has a lower-is-better quantity scale under a stated window; team autonomy has an ordinal scale and no ratio arithmetic; security exposure uses separately governed risk results. The intended configuration may improve lead time while worsening specialist bottlenecks or security. The account therefore remains multi-coordinate and indeterminate until organization, platform, operations, and security owners provide the missing premises.

### DOCA.1.CHR:5.3 - AI arrangement and configuration identity {#ai-arrangement-and-configuration-identity}

A team wants to “improve the model.” The actual subject is a model edition with a retrieval corpus, tool permissions, evaluator, human escalation path, and operating environment. Selected characteristics include task success under the declared evaluation, false-action rate, explanation adequacy, data exposure, escalation latency, compute use, operator workload, and robustness to changed inputs.

A benchmark from the bare model does not characterize the deployed arrangement. Human learning evidence does not establish model adaptation. The next question is whether the current evaluation covers the intended tool-enabled configuration and protected safety/security conditions.

### DOCA.1.CHR:5.4 - Already adequate characterization {#already-adequate-characterization}

A facility team already has current, source-qualified service, safety, operability, resource, and affected-community characteristics for the same configuration and horizon. No meaning, scale, or evidence window changed. The team reuses the account and proceeds to joint reachability. Reformatting it into this pattern's compact form would add burden without changing action.

## DOCA.1.CHR:6 - Bias-Annotation {#bias-annotation}

- **Score realism:** a number can feel more objective than its method, scale, weighting, and uncertainty warrant.
- **Maturity ladder bias:** one ordered label invites a universal sequence and higher-is-better assumption.
- **Human transfer bias:** person learning and capability measures do not characterize organizations, AI arrangements, or engineered systems.
- **Architecture projection:** architecture characteristics are tempting general quality labels; use them only when architecture is the bearer.
- **Available-data bias:** easily measured coordinates can crowd out protected or distributional consequences that matter more.
- **Benefit-only selection:** desired result coordinates can hide resources, affected Systems, transition burdens, and option losses.
- **Unknown-to-zero bias:** missing evidence is neither absence nor a favorable baseline.
- **Form completion bias:** a full table does not supply qualified measurements or direct-owner conclusions.

## DOCA.1.CHR:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Why it fails | Repair |
| --- | --- | --- |
| One maturity score | Meanings, weights, scales, protections, and uncertainty disappear. | Select the characteristics that can change this inquiry and preserve their distinct scales. |
| Method or tool inventory as characterization | Possession or use does not establish the subject's state or contribution. | Ask which result or protected condition each item changes and obtain the direct evidence. |
| Target without baseline | The proposed delta cannot be interpreted. | State the current reading or an explicit unknown under the same subject, scale, and horizon. |
| Measurement by dashboard | A display is treated as subject state, result, evidence, and verdict. | Recover the complete C.16 measurement chain and separate later interpretation. |
| Higher is always better | Polarity and target regions are assumed. | Declare higher-, lower-, target-, or unordered semantics for each scale. |
| Person-to-system transfer | Human capability or learning evidence is reused for an AI model or organization. | Identify the actual bearer and configuration, then obtain the transfer basis from the direct practice owning the receiving characteristic and its evidence under `DOCA.1.CHR:4.5`. |
| Benefits-only comparison | Resources, affected Systems, distribution, and protections vanish. | Orient the complete coordinate set before finite comparison. |
| Unknown as favorable | A missing premise enters a direction as if it had passed. | Preserve `unknown` and state the strongest claim it blocks. |
| Characterization as diagnosis of everything | Entry burden expands beyond the decision. | Keep only action-changing characteristics and name relevant unsearched areas. |

## DOCA.1.CHR:10 - Rationale {#rationale}

The common contribution is not one cross-holder scale. It is the action of selecting and orienting characteristics for one subject, receiving use, horizon, and opportunity question, then returning their substantive meanings and evidence to direct owners.

In opportunity construction, use the characterization to vary opportunity-generating dimensions and specify finite candidate changes. In advising, use it to recover premises that can reverse a comparison or recommendation.

## DOCA.1.CHR:11 - SoTA-Echoing {#sota-echoing}

**Practice question.** How should practitioners replace a development maturity label or isolated score with a characterization that can guide a finite opportunity decision without inventing one universal scale?

**Best-known line for this pattern.** FPF [`C.16`](https://raw.githubusercontent.com/ailev/FPF/main/FPF-Spec.md) supplies the strongest current measurement chain: exact measurand or subject, Characteristic, Scale, method, model, calibration, dated Work, attributed result, uncertainty, and bounded later use. [`C.11.CRC`](https://raw.githubusercontent.com/ailev/FPF/main/FPF-Spec.md) supplies the strongest current finite-change orientation: actual `S0`, finite `Δ`, realizable `S1`, complete result/resource/affected-System/distributional/protected coordinates, interactions, transition basis, uncertainty, and option effects. This pattern **adapts** those lines at `DOCA.1.CHR:4.2`–`4.7` by selecting only characteristics that can change one development inquiry and by returning holder-specific meaning and evidence outward.

**Serious alternative or default.** A maturity model or composite readiness score is faster to communicate and may be adequate when its construct, scale, weighting, evidence, and decision use are already qualified. As a default across unlike holders, it hides scale legality, trade-offs, protected coordinates, and transfer. At comparable entry effort, the selected multi-coordinate characterization preserves more decision-relevant information, at the cost of a less compact headline and possible indeterminate result.

For organization and campaign cases, [ISO 56008:2024](https://www.iso.org/standard/78485.html) is a current opportunity/innovation measurement source and supports explicit measurement and portfolio review. It is an organization-scope comparator, not a universal person, AI, or engineered-system characterization Method and not effectiveness evidence.

**Source roles and limits.** `C.16` and `C.11.CRC` are the current best-known FPF lines for measurement and finite contribution comparison. ISO 56008 is a bounded normative comparator. Holder, domain, safety, professional, legal, and evidence practices supply the actual characteristic meanings and results; this pattern does not outrank them.

**Reopen condition.** Reopen this stance if a current alternative demonstrates a lower-burden characterization that preserves subject/configuration identity, scale and uncertainty, the complete coordinate set, protected conditions, holder-specific ownership, and local reopenability, or if a relied-on measurement or finite-comparison pattern changes those obligations.


## DOCA.1.CHR:End {#end}
