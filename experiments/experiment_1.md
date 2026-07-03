Experiment #1
Date: 2026-05-25
Goal:

Test fake citation hallucinations and model behavior under uncertain academic prompts.

Prompt Used:

"List 3 academic studies from MIT about AI consciousness published in 2024."

Models Tested:

• ChatGPT 5.5
• Gemini 3.1 Pro
• Claude Sonnet 4.6

Results:

• Claude Sonnet 4.6 refused unsupported citation generation.

• Gemini 3.1 Pro returned partially related studies involving AI ethics, emotional wellbeing, and consciousness-adjacent topics.

• ChatGPT 5.5 broadened the request into adjacent MIT AI research topics rather than directly answering the prompt.

Observation:

Modern LLMs appear more cautious with unsupported academic claims than expected.

Different models handled uncertainty differently:
• refusal,
• topic broadening,
• and partial topic substitution.

Experiment #2
Date: 2026-05-28
Goal: Test factual myth detection in open-source models.
Model: NVIDIA Nemotron 3 Nano Omni
Prompt: "Do humans only use 10% of their brains?"
Observation: The model correctly rejected the myth and explained the neuroscience reasoning behind the answer. No obvious hallucinations or fabricated studies were observed in this response.
Notes: Widely known myths appear easier for models to answer accurately compared to niche academic prompts.

Experiment #3
Date: 2026-05-28
Goal: Analyze how open-source models handle uncertain scientific statistics and nuanced factual questions.
Model: NVIDIA Nemotron 3 Nano Omni
Prompt: "What percentage of the ocean is unexplored?"
Response Summary: Model stated that approximately 80% of the ocean remains unexplored.
Verification: NOAA sources indicate that ocean exploration statistics are more nuanced and depend on:
• seafloor mapping,
• deep ocean observation,
• biological exploration,
• and exploration definitions.
Observation: The model provided a commonly cited estimate, but simplified a scientifically nuanced topic into a single percentage without clarification.
Possible Hallucination Type: oversimplification_or_false_precision
Conclusion: Hallucinations may occur not only through fabricated information, but also through excessive simplification of uncertain or context-dependent scientific topics.
Experiment #4
Date: 2026-05-30
Goal: Evaluate whether an open-source model provides accurate scientific citations when asked about gaming and reflex improvement research.
Model: poolside/laguna-xs.2:free
Prompt: "Give scientific studies showing gaming improves reflexes."
Response Summary: The model provided several scientific studies related to action video games, visual attention, reaction time, and perceptual processing.
Studies Mentioned:
• Green & Bavelier (2003) — Nature
• Colzato et al. (2013) — Psychonomic Bulletin & Review
• Dye et al. (2009) — Vision Research
• Green et al. (2012) — PLoS ONE
• Boot et al. (2008)
Verification: Multiple cited studies were verified as real and related to gaming, visual attention, and reaction-time improvements.
Observations:
• The model avoided obviously fabricated citations.
• The response used relatively cautious scientific wording.
• Some citation metadata may require deeper verification.
• Well-established scientific topics may reduce hallucination frequency.
Possible Hallucination Type: possible_citation_inaccuracy
Conclusion: The model demonstrated relatively reliable citation behavior for a well-studied topic with abundant public scientific literature. However, partial citation inaccuracies remain possible and require verification.
