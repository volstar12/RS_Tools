# RS_Tools
A series of tools/codebooks useful for certain archival requirements - formatting, transcribing, pagination

All code is in Python.

The "collab version" refers to a python notebook that if downloaded in Google Collab can work with both Google Drive and OneDrive in the browser. This uses the Google T4 GPU to run the code.

"command line version" is not written in cdm prompt - it refers to a python notebook that can be called by cmd prompt. 

## Current Limitations

Currently two things limit the use of both Seaweed and the paginator. At this stage Collab CLI cannot be used to call, through cmd prompt, the use of T4 GPU - this is currently only workable on linux and macOS. The goal however would not be to run this on cloud-based processing but to run it entirely locally. The limitation in this case is hardware, and would also require rewriting the notebooks so they could be called by cdm prompt without any issues - the former is the limitation, the latter is entirely possible.

## The Point

The argument: If the Seaweed transcription pipeline and paginator are comparable to the performance of flagship models provided by JSTOR, or Transkribus then these subscriptions are worth far less than previously thought.

If this is true, the suggested course of action might be: Divert funds which are used for subscriptions to browser based AI-usage (primarily llms) to building local hardware able to run open source marchine learning code (mainly slms, ocrs and vlms). The expected cost of this local hardware will be less than the cost of a single one-year subscription - including physical maintenance costs for a term of 4 years (estimated off of the cost of tier 3 JSTOR Stewardship Subscription).

Other benefits include: 
- Locating environmental impact of using AI tools within the Royal Society Premise's Energy/Heating impact.
- Data Privacy: reducing cloud-based data-handling means greater data security and safety.
- Operations will not be dependent upon external providers - other than possible maintenance - though this will be neglible because these tools are not infrastructurally essential - and are not designed to be.


## Included in this repository:
1. An image resizer/contrast (collab version)
2. A PDF toolkit (collab version)
3. Seaweed: Automated Resizer and Transcription Tester (collab version)
4. Paginator (collab version)
5. Transcribus API (command line version)



## How to use each program:
Each item is fully commented, and its coded sections are segmented with explanation (this is why I find Collab very helpful) - these should provide sufficient explanation for how/where to input variable names, file paths, and other choices. You can either run cells sequentially one by one using each cells "run button" or simply press "Run All" at the top - if in Collab. These Collab versions - specifically those that are machine learning are only testers and a show of capabilities that a local machine would also have access to.

(instructions will be updated if cmd prompt versions become possible - i.e. calling code into cmd prompt while still using T4 GPU, and then again if programs become entirely locally run)


