# DOCA.1.CHR - Characterize the Development Subject and Intended Change {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Development Opportunity Construction and Development-Direction Advising Principles Framework* (2026-09-29), `Engineering DPF Suite/DEVELOPMENT-OPPORTUNITY-CONSTRUCTION-AND-DEVELOPMENT-DIRECTION-ADVISING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** DPF pattern
>
> **Status:** Released; evolving
>
> **Normativity:** Normative unless marked informative.

## DOCA.1.CHR:0 - Use This When {#use-this-when}

Which characteristics would actually change this development inquiry?

Use this pattern when a person, organization, community arrangement, AI configuration, engineered system, facility, research programme, episteme, or another subject is described by a maturity label, Method list, role name, benchmark, dashboard, or one score, but the opportunity depends on more specific current, intended, protected, or unknown characteristics. The first useful result is a bounded development-facing characterization with the unknown or limitation that matters to this inquiry. A measurement, comparison, or source request is a continuation only when its obtainable contribution warrants the whole burden.

Use it after `DOCA.1` when the subject, receiving use, and horizon were still loose, or enter directly when those are already clear. It can serve either opportunity construction or bounded advising. It does not diagnose every property of the subject, choose a direction, prove capability, authorize intervention, or establish that development occurred.

**Cheap exit.** Reuse an existing characterization when it covers the same subject and configuration, receiving use, horizon, characteristic meanings and scales, evidence window, protected conditions, and current question. If one domain practice already supplies the complete adequate characterization, use that result directly and retain its qualification.

**Ordinary non-use boundary.** Do not build a characterization merely because a dashboard exists. If no characteristic could change the next action, stop. Characterizations of populations, lineages, cultures, organizations, people, AI models, and engineered systems rely on different domain owners and evidence; similar metric labels do not justify transfer.

## DOCA.1.CHR:1 - Problem Frame {#problem-frame}

Development talk often compresses a subject into “junior,” “mature,” “ready,” “high potential,” “advanced,” “safe,” or a composite score. A list of methods or technologies can create the same illusion: possession or use is treated as a characteristic of the subject and then as proof of useful change.

A development opportunity needs a more selective account. The practitioner must know which characteristics can reverse the worthwhile problem, proposed contribution, supported direction, reachability claim, portfolio position, advice, or protected condition. The account must preserve distinct result, resource, affected-System or distributional, and explicitly protected coordinates rather than hiding them inside a single attractive number.

This pattern governs that inquiry-relative characterization. Measurement, diagnosis, capability, architecture, safety, financial, legal, professional, organizational, engineering, research, and other domain claims retain their direct owners.

## DOCA.1.CHR:2 - Problem {#problem}

Without a development-facing characterization:

- a maturity word hides several unlike scales and value directions;
- a score is reused without its subject, characteristic, scale, method, uncertainty, or time stance;
- the intended condition is described without a current baseline;
- one desired gain suppresses resource use, affected-System consequences, distributional effects, or protected conditions;
- person evidence is transferred to an organization or AI configuration;
- architecture characteristics are applied when architecture is not the bearer;
- an unknown premise is silently converted to a favorable reading; and
- a later change cannot be traced to the smallest affected opportunity claim.

The resulting direction may sound specific while remaining unmeasurable, incomparable, or unsafe to rely on.

## DOCA.1.CHR:3 - Forces {#forces}

| Force | Tension to preserve |
| --- | --- |
| Selectivity | The account should include only characteristics that can change the inquiry, but omitted protections can reverse the answer. |
| Cross-holder form | A common characterization move aids reuse, while characteristic meanings and evidence remain holder-specific. |
| Readability | A few ordinary claims should guide action, but scales, polarity, uncertainty, and time stance cannot disappear when relied on. |
| Direction | Intended change needs an orientation, while *development* and *maturity* do not establish that higher is better. |
| Multiple coordinates | Comparison needs a complete decision-relevant set without forcing all coordinates onto one scale. |
| Current evidence | A provisional inquiry may proceed with unknowns, while stronger reachability or advice must not launder them into facts. |
| Recognition and assurance | A well-formed characterization can still rely on weak measurement, transfer, or source evidence. |

## DOCA.1.CHR:4 - Solution {#solution}

Build the smallest characteristic account that can change this inquiry, and expose every material unknown or protected coordinate.

### DOCA.1.CHR:4.1 - Bind the characterization to one subject, use, and horizon {#bind-the-characterization-to-one-subject-use-and-horizon}

Name the exact subject and configuration. For an AI case, distinguish model, data, scaffold, tools, oversight, access, and surrounding operating arrangement when their differences matter. For an organization, name the organization or bounded arrangement rather than treating its chart or provider as the subject. For a person, name the person and relevant later-Work context.

State the receiving use, horizon, scenarios, and evidence window. A characterization for today's incident-review Work is not automatically valid for a future management role. A model benchmark in one configuration does not characterize another configuration with the same product label.

If those boundaries are missing, use `DOCA.1` and return only after they are adequate for the current question.

### DOCA.1.CHR:4.2 - Select characteristics by decision difference {#select-characteristics-by-decision-difference}

For each candidate characteristic, ask: if its current reading, intended reading, polarity, or uncertainty were different, could the worthwhile problem, contribution, direction, reachability, protection, advice, or next question change?

Keep it when the answer is yes. Otherwise omit it from the working account, while naming any intentionally unsearched area whose omission could reverse the result.

Start from several directions when useful:

- the receiver's required result or acceptance expectation;
- resources and burdens needed to obtain it;
- consequences for affected Systems or groups;
- conditions that must not worsen;
- the subject's current limitations or enabling strengths;
- prerequisites, complements, constraints, interactions, and transition conditions; and
- uncertainty or information whose resolution could change the next action.

A generic capability, maturity, readiness, quality, or performance catalogue is a source of questions, not an automatic closed set.

### DOCA.1.CHR:4.3 - Define each selected characteristic and reading {#define-each-selected-characteristic-and-reading}

For every selected characteristic, state in ordinary language:

1. what exact subject or relation bears it;
2. what the characteristic means for this receiving use;
3. its scale or admissible levels and any unit;
4. polarity—higher-is-better, lower-is-better, target-is-best, or no simple order;
5. time stance and evidence window;
6. current reading and uncertainty, or `unknown`;
7. intended, threshold, exploratory, or comparison reading;
8. explicitly protected reading or boundary when current;
9. source, method, and qualification needed for reliance; and
10. the next claim that this reading can change.

Use [`C.16`](https://raw.githubusercontent.com/ailev/FPF/main/FPF-Spec.md) when a value, score, sensor indication, rating, or comparison must be made interpretable as a measurement. A label, dashboard tile, method description, or evidence link is not the measurement result or the actual subject state.

### DOCA.1.CHR:4.4 - Orient the complete comparison coordinate set {#orient-the-complete-comparison-coordinate-set}

When a finite candidate change is current, use [`C.11.CRC`](https://raw.githubusercontent.com/ailev/FPF/main/FPF-Spec.md) to compare an actual or relied-on configuration `S0`, finite change `Δ`, and realizable candidate configuration `S1` under the same boundary, horizon, scenarios, constraints, interactions, transition basis, evidence window, and receiving decision.

Keep four coordinate families visible:

- **result coordinates:** what useful results may improve, worsen, or remain unchanged;
- **resource coordinates:** time, attention, capital, computation, energy, materials and other consumed means;
- **affected-System and distributional coordinates:** consequences for other Systems, groups, services, or environments and how gains and burdens are distributed; and
- **explicitly protected coordinates:** values that may not be silently exchanged for a gain elsewhere.

State required authority separately as a condition for proceeding. Include the time, fees or other resources needed to obtain or maintain permission when they matter, without treating permission itself as a consumed quantity.

Do not hide one family inside another or average incomparable scales. A Pareto-improvement claim is warranted only when the declared complete set has no worsening coordinate and at least one improving coordinate under the same basis. Otherwise use only supported language such as `beneficial`, `harmful`, `dominated`, `non-dominated`, or `indeterminate`. None of these selects the direction.

### DOCA.1.CHR:4.5 - Return characteristic meaning and evidence to direct owners {#return-characteristic-meaning-and-evidence-to-direct-owners}

Use the practice that owns the substantive characteristic:

- human capability and representative later-Work evidence remain with current HCD and capability patterns;
- organization contribution, positions, assignments, arrangements, culture, and change remain with current organization and strategy practices;
- AI/model evaluation, data, safety, security, oversight, and deployment claims remain with their direct engineering and governance owners;
- service, flow, reliability, safety, and operability remain with operations, engineering, safety, and domain practices as applicable;
- architecture characteristics use `C.32.ACS` or `C.32.ACE` only when architecture is the bearer;
- measurement meaning and work use `C.16`; and
- evidence reliance, provenance, and currentness use their direct FPF owners.

Record an available MethodDescription as a way a result might be obtained, not as the result. Mark a source-qualified unknown when measurement, access, or currentness is insufficient.

When a reading was established for a different bearer or configuration, rely on it only when the direct practice that owns the receiving characteristic supplies a qualified transfer basis covering the receiving bearer and configuration, characteristic meaning, scale, intended use, evidence window, and uncertainty. Without that basis, keep the receiving reading `unknown` and limit the affected opportunity claim. This can finish a useful characterization. Use A.15.9 and C.11.DUA to select an evidence request only when its obtainable contribution warrants formulation, qualification, supplier Work, delivery, interpretation, delay, and displaced work.

### DOCA.1.CHR:4.6 - Write the bounded characterization {#write-the-bounded-characterization}

Use ordinary prose first. This compact form can carry a characterization across a multi-practice handoff:

```text
DevelopmentFacingCharacterization@Context:
  subjectAndConfiguration:
  receivingUse:
  horizonScenariosAndEvidenceWindow:
  selectedCharacteristics:
    - characteristicAndBearer:
      meaningForThisUse:
      scaleUnitPolarityAndTimeStance:
      currentReadingAndUncertainty:
      intendedOrExploratoryReading:
      protectedReadingOrBoundary:
      directOwnerAndSource:
      affectedOpportunityClaim:
  completeCoordinateSet:
    resultCoordinates:
    resourceCoordinates:
    affectedSystemOrDistributionalCoordinates:
    explicitlyProtectedCoordinates:
  materialUnknowns:
  selectedFurtherContributionIfNeeded:
  stopOrReopenCondition:
```

Include only fields that serve the receiving use; an inactive request needs no field or explanation. This local form is not a universal characteristic space, measurement result, diagnosis, criterion verdict, capability profile, decision, or authorization. Several selected characteristics may use different scales and result epistemes.

### DOCA.1.CHR:4.7 - Choose the next truthful result {#choose-the-next-truthful-result}

Return one of these outcomes:

- an adequate characterization ready for opportunity search or construction;
- a worthwhile obtainable measurement or evidence request tied to one affected claim;
- a comparison question with the complete coordinate set;
- a narrower characterization that supports only part of the opportunity;
- a blocker because a protected or decision-reversing reading is unavailable;
- an explicit unknown that limits the answer while the supported characterization remains useful; or
- a stop because the existing characterization already serves the receiving use.

Continue to `DOCA.2` when material opportunity-generating dimensions are now visible, to `DOCA.4` when a direction needs a finite characteristic change and support configuration, to `DOCA.5` when joint reachability is current, or to `DOCA.7` when a formed advice question needs an admissible relationship. These are conditional continuations, not a fixed order.

### DOCA.1.CHR:4.8 - Reopen the smallest affected scope {#reopen-the-smallest-affected-scope}

Reopen when the subject or configuration, receiving use, horizon, scenario, characteristic meaning, scale, polarity, measurement method, evidence window, protected condition, or decision-relevant unknown changes. Trace that change to the smallest affected opportunity, comparison, or advice claim.

Do not discard unaffected readings merely because one characteristic changed. Do not retain a composite maturity score when its underlying meaning or weighting changed.

### DOCA.1.CHR:4.9 - What changes in practice {#what-changes-in-practice}

The practitioner replaces “more mature,” “AI-ready,” “senior,” or “platform-capable” with the characteristics that alter this inquiry. Current, intended, protected, and unknown readings stay distinct. Missing evidence limits the affected reading; a worthwhile further contribution becomes a directed request. Later comparison retains benefits, burdens, affected Systems, distribution, and protections on their own scales.

## DOCA.1.CHR:7 - Conformance Checklist {#conformance-checklist}

A conforming characterization or companion account:

1. **MUST** identify the subject and configuration, receiving use, horizon, scenarios, and evidence window.
2. **MUST** select each characteristic by an explicit way it can change the current inquiry or a protected condition.
3. **MUST** state the bearer, meaning, Scale or levels, Unit when applicable, polarity, and time stance for every relied-on characteristic.
4. **MUST** distinguish current, intended or exploratory, protected, and unknown readings.
5. **MUST** keep result, resource, affected-System or distributional, and explicitly protected coordinate families visible when finite comparison is current.
6. **MUST NOT** force incomparable coordinates into one scalar or assert Pareto improvement without a complete oriented set under one basis.
7. **MUST** identify the direct owner, source, qualification, and uncertainty for every decision-reversing reading.
8. **MUST NOT** use a MethodDescription, dashboard, benchmark, source link, or tool output as proof that measurement Work or a result exists.
9. **MUST** return each missing premise as a bounded request, unknown, narrower claim, blocker, or stop.
10. **MUST** retain a next measurement, comparison, pattern, direct-owner use, or local reopen condition only where it changes the recipient's continuation or interpretation. A sufficient direct characterization creates no further-work or omission-record obligation.
11. **MUST NOT** present the characterization as a chosen direction, recommendation, programme, authorization, performed Work, or observed effect.
12. **SHOULD** make the first useful result readable without requiring the compact form.

## DOCA.1.CHR:9 - Consequences {#consequences}

Practitioners gain a characterization that is smaller than a full diagnosis yet strong enough to guide opportunity construction, source requests, finite comparison, or advice. Several scales and unknowns can coexist without pretending to be one score. Protected conditions become visible before selection, and later premise changes can reopen only the claims that depended on them.

The cost is that a familiar word such as *maturity* may unfold into several claims with different owners and evidence windows. Some apparently precise numbers become conditional or unusable. Completing the account may require measurements or specialist results that the current inquiry cannot afford.

This pattern improves the integrity of the inquiry, not the subject itself. It supplies no measurement Work, capability, diagnosis, direction choice, intervention, assurance, or observed effect.

## DOCA.1.CHR:12 - Relations {#relations}

- **Receives from:** `DOCA.1` the subject, receiving use, horizon, protected conditions, posture, and effort boundary when those were not already adequate.
- **Uses:** `C.16` for relied-on measurement claims and `C.11.CRC` for finite configuration-relative contribution comparison.
- **Prepares:** `DOCA.2` by exposing opportunity-generating characteristics and relevant unsearched dimensions.
- **Constrains:** `DOCA.3` and `DOCA.4` by making the receiving problem, contribution, finite change, and protections inspectable.
- **Supplies premises to:** `DOCA.5`, `DOCA.6`, `DOCA.7`, and `DOCA.8` without establishing reachability, portfolio admission, advising admissibility, or refresh outcome.
- **Returns to:** HCD or capability owners for human results; organization, strategy, engineering, operations, AI/model, safety, legal, professional, research, evidence, measurement, or other direct owners for their characteristics and conclusions.
- **Does not imply:** one maturity scale, beneficial development, a chosen direction, recommendation, programme, WorkPlan, performed Work, assurance, or effect.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): FPF spec://ai.lev/fpf-spec/contract/C-16#root and spec://ai.lev/fpf-spec/contract/C-11-CRC#root; qualified holder meanings and evidence. @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-doca/contract/DOCA-1#root @status:spec/done

#source spec://ai.lev/fpf-eng-doca/source/DOCA-1-CHR
