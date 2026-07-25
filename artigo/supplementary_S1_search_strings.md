# Supplementary File S1 — Complete Search Strings

**Manuscript:** Speech Analytics and Natural Language Processing Applied to Clinical Communication: A Scoping Review
**Authors:** Rafael Baena Neto, Fabrício Evangelista dos Santos, Lucas Kenzo Terazzin Ida, Murilo Nogueira Minutti, Vicente Idalberto Becerra Sablón
**Target journal:** Artificial Intelligence in Medicine (Elsevier)

> ⚠️ **DRAFT — NOT SUBMISSION-READY.** Sections marked `[PENDING CONFIRMATION]` below still require the exact adapted syntax used in Web of Science, Scopus, and EBSCO/CINAHL. Do not upload this file to Editorial Manager until those sections are completed and this notice is removed.

---

## 1. Overview

Six search strategies were formulated: five thematic strings addressing specific conceptual axes of the review, plus one comprehensive unified string combining all major constructs. PubMed/MEDLINE was searched using all six strategies. The remaining five databases (Scopus, Web of Science, EBSCO/CINAHL, Cochrane Library, and Google Scholar) were searched using the five thematic strings only, with query syntax adapted to each platform's field codes and operators while preserving the conceptual scope of each string.

General filters applied across all databases: publication period January 2014 to July 2026; articles published in English, Spanish, or Portuguese.

---

## 2. PubMed/MEDLINE (Primary Database — all 6 strategies)

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

### Unified General String (all axes combined)
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

## 3. Cochrane Library (5 thematic strings — as executed)

> Per the review team's search log, only **String 1** was executed in Cochrane Library, adapted to the platform's field-code syntax. Cochrane Library's focus on controlled trials and intervention reviews meant the remaining purely technical strings (Axes B, D, and the NLP/review-focused String 5) would not have returned relevant records within this database's scope.

### String 1 (adapted)
```
("natural language processing"):ti,ab,kw
AND
(symptom* OR "patient-reported symptoms"):ti,ab,kw
AND
("electronic health records" OR "patient-centered"):ti,ab,kw
```

**Result:** 399 records.

---

## 4. Google Scholar (5 thematic strings, `allintitle:` filter)

> Google Scholar's 256-character query limit precluded execution of nested strings; the `allintitle:` operator was used to constrain matches to the title field only.

### String 1
```
allintitle: "natural language processing" symptoms ("electronic health records" OR "patient-centered")
```

### String 2
```
allintitle: ("clinical information extraction" OR "named entity recognition") ("medical free text" OR review)
```

### String 3
```
allintitle: ("doctor-patient communication" OR "patient-clinician relationship") ("shared decision-making" OR outcomes)
```

### String 4
```
allintitle: ("vocal biomarkers" OR "speech analytics") ("clinical practice" OR SUS)
```

### String 5 (focused on existing systematic reviews)
```
allintitle: "Applying natural language processing" OR "Identifying Topics" OR "Automatic speech recognition"
```

**Result:** 278 records.

---

## 5. Web of Science (5 thematic strings) — [PENDING CONFIRMATION]

**Result:** 1,719 records.

*Adapted syntax (TS= field tags) to be confirmed with the search team before this file is finalised.*

---

## 6. Scopus (5 thematic strings) — [PENDING CONFIRMATION]

**Result:** 1,580 records.

*Adapted syntax (TITLE-ABS-KEY field tags) to be confirmed with the search team before this file is finalised.*

---

## 7. EBSCO/CINAHL (5 thematic strings) — [PENDING CONFIRMATION]

**Result:** 586 records.

*Adapted syntax (EBSCOhost field codes) to be confirmed with the search team before this file is finalised.*

---

**Total records identified across all six databases:** 5,621
(Web of Science: 1,719; Scopus: 1,580; PubMed/MEDLINE: 1,059; EBSCO/CINAHL: 586; Cochrane Library: 399; Google Scholar: 278)
