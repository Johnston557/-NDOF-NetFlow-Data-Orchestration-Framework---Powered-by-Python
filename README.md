# -NDOF-NetFlow-Data-Orchestration-Framework---Powered-by-Python
This framework help to create a combined single endpoint deploying supported framework, which is aiming at:
- Receive, resolve NetFlow [Akvorado]
- Store, wash NetFlow [ClickHouse]
- Visualize NetFlow [Grafana]
- Data Orchastration Framework [Python]
  - Receive requests in natural language form with webhook listener
  - Translate requests into framework supported "plan" request with LLM.
  - Execute "plan" with plan_orcheastrator to proceed different kinds of "actions": event, process, etc.
  - Generate analyze report and send to webhook robot [Feishu Customized Robot]
