# BMAD Method - Cursor Instructions

## Activating Agents

BMAD agents are installed in `.cursor/rules/bmad/` as MDC rules.

### How to Use

1. **Reference in Chat**: Use `@_bmad/{module}/agents/{agent-name}`
2. **Include Entire Module**: Use `@_bmad/{module}`
3. **Reference Index**: Use `@_bmad/index` for all available agents

### Examples

```
@_bmad/core/agents/dev - Activate dev agent
@_bmad/bmm/agents/architect - Activate architect agent
@_bmad/core - Include all core agents/tasks
```

### Notes

- Rules are Manual type - only loaded when explicitly referenced
- No automatic context pollution
- Can combine multiple agents: `@_bmad/core/agents/dev @_bmad/core/agents/test`
