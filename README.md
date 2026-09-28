# RS_Tools
A series of tools/codebooks useful for certain archival requirements - formatting, transcribing, pagination

All code is in Python.

The "collab version" refers to a python notebook that if downloaded in Google Collab can work with both Google Drive and OneDrive in the browser. Files that only have "collab versions" require the Google T4 GPU to run machine learning on.

"command line version" is not written in cdm prompt - it refers to a python notebook that can be called by cmd prompt. 

## Current Limitations

Currently two things limit the use of both Seaweed and the paginator. At this stage Collab CLI cannot be used to call, through cmd prompt, the use of T4 GPU - this is currently only workable on linux and macOS. The goal however would not be to run this on cloud-based processing but to run it entirely locally. The limitation in this case is hardware.

## The Point

The argument: If the Seaweed transcription pipeline and paginator are comparable to the performance of flagship models provided by JSTOR, or Transkribus then the cost of their subscriptions is worth far less than previously thought.

If this is true, the suggested course of action might be: Divert funds which are used for subscriptions to browser based AI-usage (primarily llms) to building local hardware able to run open source marchine learning code (mainly slms, ocrs and vlms). The expected cost of this local hardware will be less than the cost of a single subscription - including physical maintenance costs for a term of 4 years (estimated off of the cost of tier 3 JSTOR Stewardship Subscription).

Other benefits include: 
- Locating environmental impact of using AI tools within the Royal Society Premise's Energy/Heating impact.
- Data Privacy: reducing cloud-based data-handling means greater data security and safety. Operations will not be dependent upon external providers.


## Included in this repository:
1. An image resizer/contrast (collab version)
2. An image resizer/contrast (command line version)
3. A PDF toolkit (collab version)
4. A PDF toolkit (command line version)
5. Seaweed: Automated Resizer and Transcription Tester (collab version)
7. Paginator (collab version)
9. Transcribus API (command line version)

