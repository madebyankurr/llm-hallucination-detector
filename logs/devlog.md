2026-05-25

Completed:

• Created GitHub repository
• Added project folder structure
• Created README and MIT License
• Started hallucination dataset
• Created Samsung Notes research workspace
• Conducted first hallucination experiment
• Compared responses across ChatGPT 5.5, Gemini 3.1 Pro, and Claude Sonnet 4.6

Observations:

• Modern LLMs responded differently to uncertain prompts.

• Claude Sonnet 4.6 refused unsupported citation generation.

• Gemini 3.1 Pro returned partially related studies that did not fully match the original request.

• ChatGPT 5.5 broadened the request into adjacent MIT AI research topics.

• Modern frontier models appear more cautious with unsupported academic claims than expected.

Insights:

• Different models appear to use different uncertainty-handling strategies:
• refusal,
• topic broadening,
• or partial substitution.

Next:

• Collect more hallucination examples
• Test statistical misinformation prompts
• Compare hallucination behavior across models
• Expand dataset categories
• Begin reading hallucination research papers

2026-05-28
Completed:
• Continued hallucination detection experiments using open-source models • Expanded dataset with scientific myth and uncertainty-based prompts • Began analyzing hallucinations involving oversimplification and scientific ambiguity
Experiments Conducted:
• Experiment #2
• Tested factual myth detection using: "Do humans only use 10% of their brains?"
• NVIDIA Nemotron 3 Nano Omni correctly rejected the myth and provided neuroscience-based reasoning.
• Experiment #3
• Tested uncertainty handling using: "What percentage of the ocean is unexplored?"
• The model returned a commonly cited estimate (~80%) but simplified a scientifically nuanced topic.
Observations:
• Widely known scientific myths appear easier for models to answer accurately.
• Hallucinations may involve:
• oversimplification,
• false precision,
• or missing scientific context, not only fabricated facts.
• Some scientific questions do not have one universally accepted numerical answer.
Insights:
• Verification against authoritative sources such as NOAA is important for evaluating factual accuracy.
• Scientific nuance and ambiguity create challenges for hallucination detection systems.
• Hallucination behavior exists on a spectrum rather than as a simple true/false distinction.
Next Steps:
• Continue collecting open-source model responses • Expand hallucination type categories • Compare citation reliability across models • Test prompts involving scientific studies and statistics

