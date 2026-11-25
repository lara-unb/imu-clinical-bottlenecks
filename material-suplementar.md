# Supplementary Material

Where Clinical Confidence Is Lost: Limiting Factors in the Measurement Chain of IMU-Based Human Movement Analysis

## S1. Search strings

### String A (2015–2026; articles and reviews; English in PubMed and Scopus)

**Scopus**

```
TITLE ( "inertial measurement unit*" OR "inertial sensor*" OR imu OR imus ) AND TITLE-ABS-KEY ( validity OR validation OR reliability OR "measurement error" OR "minimal detectable change" OR "clinically important difference" OR ( accuracy W/5 ( "motion capture" OR optoelectronic ) ) ) AND TITLE-ABS-KEY ( patient* OR stroke OR parkinson* OR "multiple sclerosis" OR "cerebral palsy" OR osteoarthritis OR arthroplasty OR "spinal cord injur*" OR rehabilitation ) AND TITLE-ABS-KEY ( gait OR kinematic* OR "joint angle*" OR "range of motion" ) AND PUBYEAR > 2014 AND PUBYEAR < 2027 AND DOCTYPE ( ar OR re ) AND LANGUAGE ( english )
```

**PubMed**

```
("inertial measurement unit*"[ti] OR "inertial sensor*"[ti] OR IMU[ti] OR IMUs[ti]) AND (validity[tiab] OR validation[tiab] OR reliability[tiab] OR "measurement error"[tiab] OR "minimal detectable change"[tiab] OR "clinically important difference"[tiab] OR "accuracy motion capture"[tiab:~5] OR "accuracy optoelectronic"[tiab:~5]) AND (patient*[tiab] OR stroke[tiab] OR parkinson*[tiab] OR "multiple sclerosis"[tiab] OR "cerebral palsy"[tiab] OR osteoarthritis[tiab] OR arthroplasty[tiab] OR "spinal cord injur*"[tiab] OR rehabilitation[tiab]) AND (gait[tiab] OR kinematic*[tiab] OR "joint angle*"[tiab] OR "range of motion"[tiab]) AND "journal article"[pt] AND 2015:2026[dp] AND english[la]
```

**IEEE Xplore** (Command Search; filters 2015–2026, Journals and Early Access; final version V3, narrowed from earlier versions)

```
("Document Title":IMU OR "Document Title":IMUs OR "Document Title":"inertial measurement unit" OR "Document Title":"inertial measurement units" OR "Document Title":"inertial sensor" OR "Document Title":"inertial sensors") AND ("Abstract":validity OR "Abstract":validation OR "Abstract":reliability OR "Abstract":"measurement error" OR "Abstract":"motion capture") AND ("Abstract":patients OR "Abstract":stroke OR "Abstract":Parkinson OR "Abstract":rehabilitation) AND ("Abstract":gait OR "Abstract":kinematics OR "Abstract":"joint angle")
```

### String B (2021–2026; articles; English; PubMed and Scopus only)

**Scopus**

```
TITLE-ABS-KEY ( "inertial measurement unit*" OR "inertial sensor*" OR imu OR imus OR "wearable sensor*" ) AND TITLE-ABS-KEY ( gait OR kinematic* OR "range of motion" OR "joint angle*" OR rehabilitation ) AND TITLE-ABS-KEY ( "randomi?ed controlled trial" OR "clinical trial" OR randomi?ed OR crossover OR "outcome measure*" ) AND PUBYEAR > 2020 AND PUBYEAR < 2027 AND DOCTYPE ( ar ) AND LANGUAGE ( english )
```

**PubMed**

```
("inertial measurement unit*"[tiab] OR "inertial sensor*"[tiab] OR IMU[tiab] OR IMUs[tiab] OR "wearable sensor*"[tiab]) AND (gait[tiab] OR kinematic*[tiab] OR "range of motion"[tiab] OR "joint angle*"[tiab] OR rehabilitation[tiab]) AND ("Randomized Controlled Trial"[pt] OR "Clinical Trial"[pt] OR randomized[tiab] OR randomised[tiab] OR crossover[tiab] OR "outcome measure*"[tiab]) AND 2021:2026[dp] AND english[la]
```

## S2. Records by database and string (exports of 13–15 November 2026)

| Database | String | Records |
| --- | --- | --- |
| PubMed | A | 200 |
| Scopus | A | 293 |
| IEEE Xplore | A | 40 |
| PubMed | B | 388 |
| Scopus | B | 490 |
| **Total** | | **1,411** |

Duplicates removed: 526 (by DOI, then PMID, then normalized title), leaving 885. Term filter (IMU, IMUs, inertial, wearable; records exclusive to String B only): 39 removed, 2 rescued, 848 screened.

## S3. Eligibility criteria applied in screening

**Included:** studies that measured human movement with IMUs as the main sensor and addressed validity, reliability, measurement error, the minimal detectable or clinically important change, or limitations affecting clinical confidence, in clinical or rehabilitation contexts.

**Conditional inclusion:** studies of healthy volunteers only if they addressed error, calibration, sensor attachment or processing relevant to clinical use; trials only if they reported on the quality of the IMU-based measure.

**Excluded:** IMUs used only as activity counters; animal, simulation or hardware-only studies; sport applications without a clinical or rehabilitation context.

## S4. Screening flow and priority

| Stage | n |
| --- | --- |
| Screened by title | 848 |
| Probable / doubtful / discard | 166 / 413 / 269 |
| Abstracts read (probable only) | 166 |
| Included / excluded after abstract (doubt excluded) | 138 / 28 |
| Priority among included: high / medium / low | 48 / 75 / 15 |
| High priority extracted from full text, used in the paper | 30 of 48 (25 primary, 5 reviews) |
| High priority extracted afterwards (not in the paper's counts) | 16 |
| High priority not obtained | 2 |

Title and abstract decisions by search string (records retrieved by String A, alone or with String B, versus String B alone):

| Stage | String A (alone or with B) | String B only | Total |
| --- | --- | --- | --- |
| Title: probable / doubtful / discard | 131 / 176 / 18 | 35 / 237 / 251 | 166 / 413 / 269 |
| Abstract: included / excluded | 114 / 17 | 24 / 11 | 138 / 28 |

Of the 28 records excluded after the abstract, 15 had been classed as doubtful and were excluded because of time constraints (all retrieved by String A only). Of the 413 doubtful titles (176 retrieved by String A, 237 only by String B), 412 were not read at abstract level; one was read during the check of records removed by the term filter and remained doubtful. The 412 were read later; see the next section.

**Priority rule.** The rule was formulated with the screening language model and approved by the author, and was applied as a judgement on each included record rather than computed from fields.

- **High:** reviews and studies that quantify a source of error at one stage of the measurement chain (positioning, calibration, fusion, MDC/SEM, drift) in a clinical population or, for studies of healthy participants only, when the quantified error concerns calibration, sensor placement or processing relevant to clinical use (conditional inclusion, S3).
- **Medium:** clinical validations reporting only ICC or RMSE.
- **Low:** healthy participants, no quantified error, or population not reported.

Two of the 48 high-priority records are healthy-participant studies admitted under the conditional clause. Only the high-priority records were selected for full-text extraction.

**Later screening of the 413 doubtful titles.** The 413 doubtful titles were screened afterwards at abstract level, in four parts.

- Part 1 (first author): 104 titles, 41 included, 59 excluded, 4 left doubtful. Twenty hidden controls (10 titles the LLM had classified probable, 10 discard) were added to this part to measure agreement between the first author and the LLM: Cohen's kappa 0.60 (observed agreement 16/20, expected by chance 50%; bootstrap 95% interval 0.21–0.90). With 20 controls the estimate is imprecise.
- Parts 2–4 (LLM alone, Claude Sonnet 5.5): 309 titles. Part 2: 38 included, 66 excluded (104). Part 3: 31 included, 73 excluded (104). Part 4: 36 included, 65 excluded (101). Total 105 included, 204 excluded. These decisions were not checked individually by the first author. The written criteria were drafted with the LLM from the first author's decisions on part 1 and approved by the first author.
- The 146 records included in the later screening (41 + 105) were not extracted.

**Criteria used in parts 2–4.** A literal rule, applied to title and abstract, with no "doubtful" category.

- Include when both hold: (I1) a wearable inertial sensor (IMU, accelerometer, gyroscope or magnetometer) measures human movement; (I2) the record reports validity (comparison with a reference such as optical motion capture) or reliability (test-retest, ICC, agreement) of the sensor-derived measure.
- Exclude when any holds: (E1) no inertial sensor (for example single camera, EMG only, instrumented treadmill); (E2) no validity or reliability measure (only use description, protocol or outcome reporting); (E3) not human movement (animal, no human participants); (E4) no usable abstract.
- Priority in parts 2–4: high when the title or abstract cites at least one kinematic descriptor (joint angle, angular velocity, range of motion or extension, step or stride length, turning velocity); medium otherwise. This descriptor-based priority is different from the error-based rule used for the first 166 records, and no extraction was done from parts 2–4.

**Use of AI.** An LLM (Claude Sonnet 5.5, Anthropic) was used for screening and extraction under the first author's protocol; see the Acknowledgment of the paper.
