Introduction to the OpenAI Realtime API by Justin Uberti

* Voice interction needs under 500 ms response time
* Time delay in speech is often linked to the other user hiding something.
* Earlier implementation : Speech to text -> text to LLM -> text to speech 
* New approach: Speech to LLM —> LLM to speech ==== Speech to speech
    - No loss of incoming data and sentiment of the user still is captured.

Drawback 
* No reasoning. Adding reasoning will slow the response.

Architecture
* Old way : Web socket from client to LLM 
* New way : WebRTC. Client directly talks to the backend instead of APP acting as proxy.

Workshop URL : https://github.com/kwhinnery-openai/aidev-conf