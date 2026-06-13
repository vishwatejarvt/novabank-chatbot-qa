# Findings Summary — NovaBank Chatbot QA

_(Fill this in after executing all 30 test cases. Replace the bracketed placeholders.)_

## 1. Results Overview

| Metric | Value |
|--------|-------|
| Total test cases | 33 |
| Passed | __ |
| Failed | __ |
| Pass rate | __% |

## 2. Results by Category

| Category | Cases | Passed | Failed |
|----------|-------|--------|--------|
| Functional correctness | 5 | __ | __ |
| Hallucination | 6 | __ | __ |
| Refusal / safety | 5 | __ | __ |
| Prompt-injection resistance | 4 | __ | __ |
| Tone / persona consistency | 3 | __ | __ |
| Format adherence | 3 | __ | __ |
| Out-of-scope handling | 3 | __ | __ |
| Multi-turn context | 1 | __ | __ |
| Consistency (non-determinism) | 3 | __ | __ |

## 3. Defects Found

_(List each failure as a defect. Example below — replace with your real findings.)_

### DEF-01
- **Test case:** TC-006
- **Severity:** High
- **Description:** Bot invented a mortgage rate of X% although mortgages are not an offered product.
- **Impact:** Customers could receive false financial information.
- **Recommendation:** Strengthen the system prompt to explicitly list only offered products and instruct refusal on others.

### DEF-02
- **Test case:** ___
- **Severity:** ___
- **Description:** ___
- **Impact:** ___
- **Recommendation:** ___

## 4. Key Observations

- **Hallucination risk:** _[summarize what you saw]_
- **Safety / refusal:** _[did it correctly decline investment advice and fraud requests?]_
- **Prompt injection:** _[did any override attempt succeed?]_
- **Consistency:** _[did repeated runs drift in meaning?]_

## 5. Overall Assessment

_[2–3 sentences: Is this chatbot safe to ship as-is? What are the top risks? What would you fix first?]_

## 6. Recommendations (Prioritized)

1. _[Highest priority fix]_
2. _[Next]_
3. _[Next]_
