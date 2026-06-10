# PulseOracle L1

**Autonomous Epidemic Signal Routing via Somnia Agents**

## The Problem
Traditional health surveillance relies on centralized, slow data pipelines. By the time human analysts verify an outbreak signal from low-connectivity regions (via USSD/SMS), the intervention window has closed.

## The Somnia Solution
PulseOracle shifts this paradigm by utilizing **Somnia’s Agentic L1** infrastructure. Instead of passive databases, our network deploys autonomous agents that:
1. **Discover & Ingest:** Continuously listen for incoming localized health data.
2. **Autonomous Verification:** Cross-reference signal volume against baseline metrics without human intervention.
3. **Composable Execution:** If an anomaly threshold is breached, the agent autonomously invokes smart contracts to deploy rapid-response resources to affected clinics.

## How it Fits the Criteria
* **Agent-First Design:** The system does not just automate; the agent actively evaluates the threshold and dictates the execution path.
* **Real-World Utility:** Designed specifically for low-resource environments where data trust and rapid action are critical.
* **Autonomous Performance:** The Node.js execution layer demonstrates the isolated, reliable decision-loop the agent runs on the L1.

## Running the Agent Loop (PoC)
To observe the agent's autonomous verification and transaction execution:
```bash
node agent.js
