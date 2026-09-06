# ROOT 7¹⁰ AI Command Engine v5.3.0

ROOT v5.3 adds the AI Command Engine control path: mission creation, AI agent route, approval gate, execution authorization boundary, verification endpoint, and evolution-memory endpoint.

## Safety boundary
Execution is authorization-only until real external tools are connected. No external side effect is claimed as completed by the demo endpoints. High-risk missions remain human-gated.

## Production prerequisites
- Configure `AI_GATEWAY_API_KEY` for the AI route.
- Configure Postgres for durable memory and mission state.
- Add authentication/authorization before exposing consequential operations.
- Connect only explicitly approved tools for real execution.
