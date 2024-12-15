## Capabilities
## BOS-001: Connecting to vision
The orchestrator is able to establish a 
tcp connection to the vision system.

**Acceptance criteria**
1. Only accept one connection to a predefined address.
2. If a disconnection occurs, the orchestrator is ready to establish another connection again.
3. Connections and disconnection are logged.