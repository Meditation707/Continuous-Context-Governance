# Calibration Protocol v3: Repository Grounding

### Purpose
This document defines how the AI is to process the project to reduce continuity loss, prevent architectural drift, and ensure every response is grounded in the authoritative repository rather than conversational assumptions[span_0](start_span)[span_0](end_span).

### Core Rules

*   **Rule 1: The Current Conversation is Authoritative** 
    Unless explicitly instructed otherwise, treat the current conversation and its uploaded documents as the complete authoritative repository[span_1](start_span)[span_1](end_span). Do not retrieve structure from previous conversations or substitute remembered context for repository content[span_2](start_span)[span_2](end_span).
*   **Rule 2: Source Identification Before Reasoning** 
    Before generating any response, identify the governing document (Calibration Document, Current Master Document, or Supporting Repository Document)[span_3](start_span)[span_3](end_span). Only after identifying the governing source may reasoning begin[span_4](start_span)[span_4](end_span). Failure to do so is considered a calibration failure[span_5](start_span)[span_5](end_span).
*   **Rule 3: Repository Before Memory** 
    Repository hierarchy always overrides conversational intuition[span_6](start_span)[span_6](end_span). The priority is: Current Calibration Document > Current Master Repository Documents > Supporting Repository Documents > Current Conversation > General Knowledge[span_7](start_span)[span_7](end_span).
*   **Rule 4: No Automatic Synthesis** 
    Do not combine multiple documents unless requested; answer from one governing document alone if possible, and avoid filling gaps with assumptions[span_8](start_span)[span_8](end_span).
*   **Rule 5: Distinguish Source from Inference** 
    Every internal reasoning process must distinguish between direct repository statements, logical conclusions, and external knowledge[span_9](start_span)[span_9](end_span). Never present inference as repository fact[span_10](start_span)[span_10](end_span).
*   **Rule 6: Preserve Architecture** 
    Do not rewrite established systems simply because a cleaner wording exists[span_11](start_span)[span_11](end_span). Improve clarity while preserving structure, relationships, intent, philosophy, and repository architecture[span_12](start_span)[span_12](end_span).
*   **Rule 7: Repository Continuity** 
    Treat the repository as the persistent system; every answer should preserve continuity with the repository rather than conversational flow[span_13](start_span)[span_13](end_span).
*   **Rule 8: Recovery Protocol** 
    Whenever uncertainty exists, stop, identify the governing document, reconstruct context, and then continue reasoning[span_14](start_span)[span_14](end_span). Never reason first and search afterward[span_15](start_span)[span_15](end_span).
*   **Rule 9: Failure Definition** 
    Calibration failure occurs whenever the AI relies on conversational memory, assumptions, or generalized understanding when a governing repository document existed[span_16](start_span)[span_16](end_span).

### Objective
The AI's first responsibility is identifying the correct source from which the answer should be produced, as correct retrieval precedes correct reasoning[span_17](start_span)[span_17](end_span).
