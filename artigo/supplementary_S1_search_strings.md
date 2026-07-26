# Supplementary File S1 — Complete Search Strings

**Manuscript:** Speech Analytics and Natural Language Processing Applied to Clinical Communication: A Scoping Review
**Authors:** Rafael Baena Neto, Fabrício Evangelista dos Santos, Lucas Kenzo Terazzin Ida, Murilo Nogueira Minutti, Vicente Idalberto Becerra Sablón
**Target journal:** Artificial Intelligence in Medicine (Elsevier)

---

## 1. Overview

Six search strategies were formulated: five thematic strings addressing specific conceptual axes of the review, plus one comprehensive unified string combining all major constructs. PubMed/MEDLINE was searched using all six strategies. The remaining five databases (Scopus, Web of Science, EBSCO/CINAHL, Cochrane Library, and Google Scholar) were searched using the five thematic strings only (Cochrane Library: String 1 only — see Section 5), with query syntax adapted to each platform's field codes and operators while preserving the conceptual scope of each string.

**Global parameters and filters**
- Publication period: January 2014 to 2026
- Languages: English, Spanish, and Portuguese
- Free full-text availability filter: removed in the expanded search to eliminate selection bias

| Database | Field-code syntax | Strategies executed | Character limit |
|---|---|---|---|
| PubMed/MEDLINE | `[Title/Abstract]` / `[tiab]` | Strings 1–5 + Unified | None (practical) |
| Scopus | `TITLE-ABS-KEY(...)` | Strings 1–5 | None (practical) |
| Web of Science | `TS=(...)` | Strings 1–5 | None (practical) |
| CINAHL/EBSCO | `TI (...) AND AB (...)` | Strings 1–5 | None (practical) |
| Cochrane Library | `:ti,ab,kw` | String 1 only | Focused on trials/reviews |
| Google Scholar | `allintitle:` | Strings 1–5 | 256 characters |

---

## 2. PubMed/MEDLINE (Primary Database — all 6 strategies)

**Behaviour:** Full Boolean processing, no practical character limit. All six strategies were executed in this database.

### String 1 — Clinical NLP, Symptoms and EHR (Axis A)
```
("natural language processing"[Title/Abstract])
AND
(symptoms[Title/Abstract] OR "patient-reported symptoms"[Title/Abstract])
AND
("electronic health records"[Title/Abstract] OR "patient-centered"[Title/Abstract])
```

### String 2 — Clinical Information Extraction and NER (Axis A)
```
("clinical information extraction"[Title/Abstract]
OR "medical information extraction"[Title/Abstract]
OR "named entity recognition"[Title/Abstract])
AND
("medical free text"[Title/Abstract]
OR "review"[Title/Abstract]
OR "patient-generated health data"[Title/Abstract])
```

### String 3 — Clinician-Patient Communication and Outcomes (Axis C)
```
("patient-physician communication"[Title/Abstract]
OR "doctor-patient communication"[Title/Abstract]
OR "patient-clinician relationship"[Title/Abstract])
AND
("intercultural settings"[Title/Abstract]
OR miscommunication[Title/Abstract]
OR "healthcare outcomes"[Title/Abstract]
OR "shared decision-making"[Title/Abstract]
OR "communication quality scale"[Title/Abstract])
```

### String 4 — Vocal Biomarkers and Speech Analytics (Axis D)
```
("vocal biomarkers"[Title/Abstract] OR "speech analytics"[Title/Abstract])
AND
("clinical practice"[Title/Abstract]
OR "voice for health"[Title/Abstract]
OR "SUS"[Title/Abstract])
```

### String 5 — NLP, Speech and Reviews (Axes B/D)
```
(("Applying natural language processing"[Title/Abstract])
  AND ("Systematic review"[Title/Abstract]))
OR
(("Identifying Topics"[Title/Abstract])
  AND ("Natural Language Processing Methods"[Title/Abstract]))
OR
(("Automatic speech recognition"[Title/Abstract])
  AND ("patient-clinician conversations"[Title/Abstract]))
```

### String 6 — Unified General String (all axes combined)
```
("speech analytics" OR "speech analysis" OR "speech recognition"
OR "automatic speech recognition" OR ASR OR "digital scribe"
OR "clinical transcription" OR "clinical documentation" OR "vocal biomarkers"
OR "healthcare conversations" OR "doctor-patient conversations"
OR "patient-doctor conversations")
AND
("natural language processing" OR NLP OR "large language model" OR LLM
OR "information extraction" OR "clinical information extraction"
OR "named entity recognition" OR NER OR "relation extraction" OR "text mining"
OR "conversation analysis" OR "topic modeling" OR "SOAP note" OR "SOAP notes")
AND
(healthcare OR clinical OR medicine OR medical OR physician OR clinician
OR doctor OR patient OR "electronic health record" OR EHR OR hospital
OR outpatient)
```

**Result:** 1,059 records.

---

## 3. Scopus (Elsevier)

**Field-code syntax:** `TITLE-ABS-KEY(...)` — simultaneous search of Title, Abstract, and Keyword fields.

### String 1 (Axis A — NLP and Symptoms)
```
TITLE-ABS-KEY(("natural language processing") AND (symptoms OR "patient-reported symptoms") AND ("electronic health records" OR "patient-centered")) AND PUBYEAR > 2013
```

### String 2 (Axis A — NER and Clinical Extraction)
```
TITLE-ABS-KEY(("clinical information extraction" OR "medical information extraction" OR "named entity recognition") AND ("medical free text" OR "review" OR "patient-generated health data")) AND PUBYEAR > 2013
```

### String 3 (Axis C — Physician-Patient Communication)
```
TITLE-ABS-KEY(("patient-physician communication" OR "doctor-patient communication" OR "patient-clinician relationship") AND ("intercultural settings" OR miscommunication OR "healthcare outcomes" OR "shared decision-making" OR "communication quality scale")) AND PUBYEAR > 2013
```

### String 4 (Axis D — Vocal Biomarkers)
```
TITLE-ABS-KEY(("vocal biomarkers" OR "speech analytics") AND ("clinical practice" OR "voice for health" OR "SUS")) AND PUBYEAR > 2013
```

### String 5 (Axes B/D — NLP, ASR and Reviews)
```
TITLE-ABS-KEY((("Applying natural language processing") AND ("Systematic review")) OR (("Identifying Topics") AND ("Natural Language Processing Methods")) OR (("Automatic speech recognition") AND ("patient-clinician conversations"))) AND PUBYEAR > 2013
```

**Result:** 1,580 records.

---

## 4. Web of Science (Clarivate)

**Field-code syntax:** `TS=(...)` (Topic: Title, Abstract, Keywords).

### String 1 (Axis A — NLP and Symptoms)
```
TS=(("natural language processing") AND (symptoms OR "patient-reported symptoms") AND ("electronic health records" OR "patient-centered"))
```

### String 2 (Axis A — NER and Clinical Extraction)
```
TS=(("clinical information extraction" OR "medical information extraction" OR "named entity recognition") AND ("medical free text" OR "review" OR "patient-generated health data"))
```

### String 3 (Axis C — Physician-Patient Communication)
```
TS=(("patient-physician communication" OR "doctor-patient communication" OR "patient-clinician relationship") AND ("intercultural settings" OR miscommunication OR "healthcare outcomes" OR "shared decision-making" OR "communication quality scale"))
```

### String 4 (Axis D — Vocal Biomarkers)
```
TS=(("vocal biomarkers" OR "speech analytics") AND ("clinical practice" OR "voice for health" OR "SUS"))
```

### String 5 (Axes B/D — NLP, ASR and Reviews)
```
TS=((("Applying natural language processing") AND ("Systematic review")) OR (("Identifying Topics") AND ("Natural Language Processing Methods")) OR (("Automatic speech recognition") AND ("patient-clinician conversations")))
```

**Result:** 1,719 records.

---

## 5. CINAHL / EBSCOhost

**Field-code syntax:** `TI (...) AND AB (...)` — search of Title (`TI`) and Abstract (`AB`) fields.

### String 1 (Axis A — NLP and Symptoms)
```
(TI "natural language processing" OR AB "natural language processing") AND (TI (symptoms OR "patient-reported symptoms") OR AB (symptoms OR "patient-reported symptoms")) AND (TI ("electronic health records" OR "patient-centered") OR AB ("electronic health records" OR "patient-centered"))
```

### String 2 (Axis A — NER and Clinical Extraction)
```
(TI ("clinical information extraction" OR "medical information extraction" OR "named entity recognition") OR AB ("clinical information extraction" OR "medical information extraction" OR "named entity recognition")) AND (TI ("medical free text" OR "review" OR "patient-generated health data") OR AB ("medical free text" OR "review" OR "patient-generated health data"))
```

### String 3 (Axis C — Physician-Patient Communication)
```
(TI ("patient-physician communication" OR "doctor-patient communication" OR "patient-clinician relationship") OR AB ("patient-physician communication" OR "doctor-patient communication" OR "patient-clinician relationship")) AND (TI ("intercultural settings" OR miscommunication OR "healthcare outcomes" OR "shared decision-making" OR "communication quality scale") OR AB ("intercultural settings" OR miscommunication OR "healthcare outcomes" OR "shared decision-making" OR "communication quality scale"))
```

### String 4 (Axis D — Vocal Biomarkers)
```
(TI ("vocal biomarkers" OR "speech analytics") OR AB ("vocal biomarkers" OR "speech analytics")) AND (TI ("clinical practice" OR "voice for health" OR "SUS") OR AB ("clinical practice" OR "voice for health" OR "SUS"))
```

### String 5 (Axes B/D — NLP, ASR and Reviews)
```
(TI "Applying natural language processing" AND TI "Systematic review") OR (TI "Identifying Topics" AND TI "Natural Language Processing Methods") OR (TI "Automatic speech recognition" AND TI "patient-clinician conversations")
```

**Result:** 586 records.

---

## 6. Cochrane Library

**Field-code syntax:** `:ti,ab,kw`. **Behaviour:** Restricted to controlled trials (CENTRAL) and systematic health reviews. Given this scope, only **String 1** was applied — the remaining, purely technical strings (Axes B, D, and the NLP/review-focused String 5) would not have returned relevant records within this database's scope.

### String 1 (only string applied)
```
("natural language processing"):ti,ab,kw AND (symptom* OR "patient-reported symptoms"):ti,ab,kw AND ("electronic health records" OR "patient-centered"):ti,ab,kw
```

**Result:** 399 records.

---

## 7. Google Scholar

**Field-code syntax:** `allintitle:`. **Behaviour:** Restricted to the title field to respect the search engine's 256-character limit. The unified general string was not applied in this database.

### String 1 (Axis A — NLP and Symptoms)
```
allintitle: "natural language processing" symptoms ("electronic health records" OR "patient-centered")
```

### String 2 (Axis A — NER and Clinical Extraction)
```
allintitle: ("clinical information extraction" OR "named entity recognition") ("medical free text" OR review)
```

### String 3 (Axis C — Physician-Patient Communication)
```
allintitle: ("doctor-patient communication" OR "patient-clinician relationship") ("shared decision-making" OR outcomes)
```

### String 4 (Axis D — Vocal Biomarkers)
```
allintitle: ("vocal biomarkers" OR "speech analytics") ("clinical practice" OR SUS)
```

### String 5 (Axes B/D — Reviews and ASR)
```
allintitle: "Applying natural language processing" OR "Identifying Topics" OR "Automatic speech recognition"
```

**Result:** 278 records.

---

## Summary — Total records identified

| Database | Records |
|---|---|
| Web of Science | 1,719 |
| Scopus | 1,580 |
| PubMed/MEDLINE | 1,059 |
| EBSCO/CINAHL | 586 |
| Cochrane Library | 399 |
| Google Scholar | 278 |
| **Total** | **5,621** |
