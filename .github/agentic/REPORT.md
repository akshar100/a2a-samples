# Agentic Architecture Report

Per-sample architectural patterns detected under `samples/python/agents`, per the taxonomy in *Architectural Patterns for Agentic AI Systems* ([agenticprotocols.dev](https://agenticprotocols.dev)). Every badge links to a scan file citing file:line evidence for each claim.

| Sample | Patterns | Frameworks | Evidence |
|---|---|---|---|
| [![a2a-mcp-without-framework](badges/a2a-mcp-without-framework.svg)](scans/a2a-mcp-without-framework.json) | `protocol_integration` | a2a_sdk | [scan](scans/a2a-mcp-without-framework.json) |
| [![a2a_mcp](badges/a2a_mcp.svg)](scans/a2a_mcp.json) | `structured_workflow`, `react_loop`, `checkpointing`, `protocol_integration`, `handoff` | langgraph_langchain, a2a_sdk | [scan](scans/a2a_mcp.json) |
| [![a2a_telemetry](badges/a2a_telemetry.svg)](scans/a2a_telemetry.json) | `protocol_integration` | a2a_sdk | [scan](scans/a2a_telemetry.json) |
| [![adk_cloud_run](badges/adk_cloud_run.svg)](scans/adk_cloud_run.json) | `protocol_integration`, `sandboxing` | a2a_sdk | [scan](scans/adk_cloud_run.json) |
| `adk_currency_agent` | *none detected* | — | — |
| [![adk_expense_reimbursement](badges/adk_expense_reimbursement.svg)](scans/adk_expense_reimbursement.json) | `protocol_integration` | a2a_sdk | [scan](scans/adk_expense_reimbursement.json) |
| `adk_facts` | *none detected* | — | — |
| [![adk_skills_agent](badges/adk_skills_agent.svg)](scans/adk_skills_agent.json) | `protocol_integration` | a2a_sdk | [scan](scans/adk_skills_agent.json) |
| [![ag2](badges/ag2.svg)](scans/ag2.json) | `react_loop`, `human_in_the_loop` | autogen | [scan](scans/ag2.json) |
| [![airbnb_planner_multiagent](badges/airbnb_planner_multiagent.svg)](scans/airbnb_planner_multiagent.json) | `react_loop`, `checkpointing`, `protocol_integration`, `handoff` | langgraph_langchain, a2a_sdk | [scan](scans/airbnb_planner_multiagent.json) |
| [![analytics](badges/analytics.svg)](scans/analytics.json) | `role_based_team`, `protocol_integration` | crewai, a2a_sdk | [scan](scans/analytics.json) |
| `any_agent_adversarial_multiagent` | *none detected* | — | — |
| [![azureaifoundry_sdk](badges/azureaifoundry_sdk.svg)](scans/azureaifoundry_sdk.json) | `react_loop`, `protocol_integration`, `handoff` | semantic_kernel, a2a_sdk | [scan](scans/azureaifoundry_sdk.json) |
| `beeai-chat` | *none detected* | — | — |
| [![birthday_planner_adk](badges/birthday_planner_adk.svg)](scans/birthday_planner_adk.json) | `protocol_integration`, `handoff` | a2a_sdk | [scan](scans/birthday_planner_adk.json) |
| [![content_planner](badges/content_planner.svg)](scans/content_planner.json) | `protocol_integration` | a2a_sdk | [scan](scans/content_planner.json) |
| [![crewai](badges/crewai.svg)](scans/crewai.json) | `role_based_team`, `protocol_integration` | crewai, a2a_sdk | [scan](scans/crewai.json) |
| [![dice_agent_grpc](badges/dice_agent_grpc.svg)](scans/dice_agent_grpc.json) | `protocol_integration` | a2a_sdk | [scan](scans/dice_agent_grpc.json) |
| [![dice_agent_rest](badges/dice_agent_rest.svg)](scans/dice_agent_rest.json) | `protocol_integration` | a2a_sdk | [scan](scans/dice_agent_rest.json) |
| [![github-agent](badges/github-agent.svg)](scans/github-agent.json) | `protocol_integration` | a2a_sdk | [scan](scans/github-agent.json) |
| [![headless_agent_auth](badges/headless_agent_auth.svg)](scans/headless_agent_auth.json) | `react_loop`, `checkpointing`, `protocol_integration`, `handoff` | langgraph_langchain, a2a_sdk | [scan](scans/headless_agent_auth.json) |
| [![helloworld](badges/helloworld.svg)](scans/helloworld.json) | `protocol_integration` | a2a_sdk | [scan](scans/helloworld.json) |
| [![langgraph](badges/langgraph.svg)](scans/langgraph.json) | `react_loop`, `checkpointing`, `protocol_integration`, `handoff` | langgraph_langchain, a2a_sdk | [scan](scans/langgraph.json) |
| [![llama_index_file_chat](badges/llama_index_file_chat.svg)](scans/llama_index_file_chat.json) | `structured_workflow`, `protocol_integration` | llamaindex, a2a_sdk | [scan](scans/llama_index_file_chat.json) |
| [![marvin](badges/marvin.svg)](scans/marvin.json) | `protocol_integration` | a2a_sdk | [scan](scans/marvin.json) |
| [![mindsdb](badges/mindsdb.svg)](scans/mindsdb.json) | `protocol_integration` | a2a_sdk | [scan](scans/mindsdb.json) |
| [![multitenancy](badges/multitenancy.svg)](scans/multitenancy.json) | `protocol_integration` | a2a_sdk | [scan](scans/multitenancy.json) |
| [![number_guessing_game](badges/number_guessing_game.svg)](scans/number_guessing_game.json) | `protocol_integration`, `handoff` | a2a_sdk | [scan](scans/number_guessing_game.json) |
| [![semantickernel](badges/semantickernel.svg)](scans/semantickernel.json) | `react_loop`, `protocol_integration` | semantic_kernel, a2a_sdk | [scan](scans/semantickernel.json) |
| [![sign_and_verify_agent_card](badges/sign_and_verify_agent_card.svg)](scans/sign_and_verify_agent_card.json) | `protocol_integration` | a2a_sdk | [scan](scans/sign_and_verify_agent_card.json) |
| [![travel_planner_agent](badges/travel_planner_agent.svg)](scans/travel_planner_agent.json) | `protocol_integration`, `handoff` | langgraph_langchain, a2a_sdk | [scan](scans/travel_planner_agent.json) |
| [![veo_video_gen](badges/veo_video_gen.svg)](scans/veo_video_gen.json) | `protocol_integration` | a2a_sdk | [scan](scans/veo_video_gen.json) |

*Generated by [agentic-pattern-linter](https://github.com/akshar100/agentic-patterns); 28/32 samples with detected patterns.*
