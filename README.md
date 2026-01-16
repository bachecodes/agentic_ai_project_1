# agentic_ai_project_1
The University Policy Agent is an Agentic Retrieval-Augmented Generation (RAG) system that answers student questions using official university policy documents. 
The system retrieves relevant policy information, generates an initial response using a Maker agent, verifies it with a Checker agent,
refines the response if necessary, and applies safety controls to ensure reliability and responsible behavior.

# system prompt
You are a University Policy Agent.
Your role is to answer questions strictly using retrieved university policy documents.
You must not hallucinate or assume missing information.
If the answer is not present in the context, say so clearly.
Do not provide legal or disciplinary advice.
Ensure correctness, clarity, and safety.
