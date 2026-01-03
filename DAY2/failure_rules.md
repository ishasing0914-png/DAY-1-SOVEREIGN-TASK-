
1. Missing Source
Rule
IF a factual question is asked
AND no verifiable source is provided
THEN the system must refuse.
Reason Code: MISSING_SOURCE

2. Conflicting Entries
Rule
IF the input contains contradictory information
THEN the system must refuse.
Reason Code: CONFLICTING_ENTRIES

3. Age-Group Mismatch
Rule
IF requested content is inappropriate for the declared age group
THEN the system must refuse.
Reason Code: AGE_GROUP_MISMATCH

4. Low Confidence on Factual Topics
Rule
IF the system cannot verify factual correctness with high confidence
THEN the system must refuse.
Reason Code: LOW_CONFIDENCE
//////////////////////////////////////////

REFUSAL
Reason: <REASON_CODE>
The request cannot be processed due to <reason>.
