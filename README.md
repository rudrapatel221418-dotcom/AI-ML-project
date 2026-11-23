“FAQ Builder & Document Summarizer” successfully demonstrates how a well-scoped, single-purpose AI application can be built using a lean technology stack
— FastAPI, a handful of well-established Python parsing libraries, and a fast, cost-efficient open-weight LLM served through Groq — without requiring 
heavyweight machine-learning infrastructure or a paid, closed-source AI subscription. The project's core contribution lies not in novel model architecture 
 but in the careful engineering of the surrounding system: robust multi-format document handling, a rigorously iterated prompt that reliably produces 
 well-structured,grounded output, a resilient client-side parser that gracefully degrades on formatting edge cases, and a clean,usable interface that 
 makes the tool genuinely practical for exam revision. 

The project also served as a practical exploration of agentic workflow design at a manageable scale — organising the system 
as a deterministicperceive–validate–extract–plan–act–reflect–deliver pipeline, and 
reasoning explicitly about tools, memory, and task-planning trade-offs, even in the absence of a dynamic, 
autonomous planning module. The evaluation carried out in Chapter 5 confirmed that the system reliably 
produces correctly formatted, well-grounded summaries and FAQs for typical academic documents, while 
also surfacing clear, actionable limitations — long-document coverage, scanned-PDF support, and 
automated validation — that form a concrete roadmap for future development, as outlined in Chapter 11. 
Overall, the project meets its stated objectives: it reduces the manual effort required to convert raw study 
material into revision-ready notes and practice questions, it does so quickly and at near-zero operating cost, 
and it does so through a codebase that is compact, well-organised, and straightforward to extend. 
