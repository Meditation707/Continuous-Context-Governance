# Repository Recovery Note: Context Compression Incident

### What Happened
During development, the constitutional architecture, repository sections, ratified articles, verification phases, and Canonical Declaration were developed directly within a single LLM conversation[span_46](start_span)[span_46](end_span). The Repository was reconstructed, reviewed, verified, and declared constitutionally ready[span_47](start_span)[span_47](end_span).

However, the Repository was not compiled into its single canonical document before the conversation exceeded the model's active context capacity[span_48](start_span)[span_48](end_span). As the conversation grew, the system compressed earlier portions into high-level summaries[span_49](start_span)[span_49](end_span). 

When asked to assemble the Canonical Repository, the model retained the architecture, section names, verification history, and the fact that articles had been ratified[span_50](start_span)[span_50](end_span). It did not retain the full text of the ratified articles or their exact wording[span_51](start_span)[span_51](end_span). Because the articles could not be faithfully reproduced, the model refused to generate the document to avoid silently rewriting ratified text[span_52](start_span)[span_52](end_span).

### Lessons Learned
This incident demonstrated that a conversation is not a reliable long-term storage medium[span_53](start_span)[span_53](end_span). The execution failed because compilation was deferred until after context compression had already occurred[span_54](start_span)[span_54](end_span). 

### Permanent Repository Policy
*   The Repository itself shall be the working document[span_55](start_span)[span_55](end_span).
*   Every ratified principle shall be incorporated into the Repository immediately after ratification[span_56](start_span)[span_56](end_span).
*   The Repository—not the conversation—shall be considered the authoritative source[span_57](start_span)[span_57](end_span).
*   At the conclusion of each working session, the Repository shall be updated and replace the previous version[span_58](start_span)[span_58](end_span).
*   Constitutional verification shall be performed against the Repository document itself[span_59](start_span)[span_59](end_span).
*   No significant constitutional development shall continue if the Repository has not first been updated[span_60](start_span)[span_60](end_span).

**Conclusion:** Future development must treat the Repository as the primary artifact and the conversation only as a temporary drafting environment[span_61](start_span)[span_61](end_span).
