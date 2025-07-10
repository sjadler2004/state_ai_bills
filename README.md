# state_ai_bills

`bill_texts` contains scrapes of the bills available on the NCSL's website and flagged by them as AI-relevant, as of June 30, 2025. When multiple versions of the bill are available, the JSON contains each version, with a flag for which version is the latest, which is the version used for analysis purposes. I plan to come back and also add my analysis and code.

`analyze_bills_async_final.ipynb` is the code to analyze a single bill or the full set of bills. The results of my analysis are in `results/ai_relatedness_results.json` (how AI-related are the bills) and `results/ai_requirements_results.json` (how much the bill imposes specific requirements on AI developers, analyzed on the subset of AI-related bills, i.e., 6/10 AI-relatedness or higher).
