# Architecture Patterns

## Common Integration Styles Used
1. **CRM as System of Engagement** + Ticketing as System of Action
2. **ERP / Loyalty as System of Record** for transactional data
3. Middleware / iPaaS or native connectors for synchronisation
4. Event-driven updates for near real-time customer context

## Design Decisions
- Prefer native or low-code connectors first
- Push complex transformation logic to a controlled middle layer when needed
- Always include data quality checks before critical handoffs
