# Tools and Libraries

- **[Microsoft AutoGen](https://github.com/microsoft/autogen)** — The general-purpose multi-agent conversation framework used to build the JCO-published virtual tumor board system (Wang, Mullick Chowdhury & Nazha, 2025); supports Coordinator/Reviewer-style role assignment directly applicable to tumor-board orchestration.
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — Role-based multi-agent orchestration framework (Coordinator + specialist "crew" agents) suited to modeling a fixed set of clinical specialties (oncologist, radiologist, pathologist) as distinct collaborating agents.
- **[LangGraph](https://github.com/langchain-ai/langgraph)** — Graph-based agent orchestration library for building stateful, multi-step agent workflows with explicit control flow — a good fit for the evidence-ledger/safety-governor style architecture used in TumorBoard (arXiv:2608.03190).
- **[MedAgents (code)](https://github.com/gersteinlab/MedAgents)** — Reference implementation of the role-playing, multi-round medical LLM collaboration framework described in Tang et al., 2024.
- **[MDAgents (code)](https://github.com/mitmedialab/MDAgents)** — Reference implementation of the adaptive solo/group LLM collaboration framework (MIT Media Lab), directly modeling the tiered complexity-based recruitment a real tumor board uses.
