<p align="center">
  <img src="logo.png" alt="Hermeum" width="500" />
</p>

<p align="center">
  <strong>An open platform for creating fully autonomous Hermes agents that work on your team's behalf.</strong>
</p>

<p align="center">
  <a href="https://docs.hermeum.app">Documentation</a>
  ·
  <a href="https://discord.gg/ZW44yyCAHP">Discord Community</a>
</p>

---

Hermeum turns the open-source
[Hermes agent](https://hermes-agent.nousresearch.com/docs) into a managed
platform. Describe what your agent should do, and Hermeum gives you a working
agent you can chat with, deploy, and iterate on.

## Highlights

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="assets/agents-list.png" alt="Agents list — running agents with status and created timestamps" width="480" />
      <br /><em>Agents list</em>
    </td>
    <td width="50%" align="center" valign="top">
      <img src="assets/create-agent.png" alt="Create agent — chat on the left generates the agent config YAML on the right" width="480" />
      <br /><em>Create by chat</em>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="assets/agent-detail.png" alt="Agent detail — webhook endpoint, soul, and verified config" width="480" />
      <br /><em>Agent detail</em>
    </td>
    <td width="50%" align="center" valign="top">
      <img src="assets/session-monitoring.png" alt="Session monitoring — live transcript beside a filterable stream of session events" width="480" />
      <br /><em>Session monitoring</em>
    </td>
  </tr>
</table>

- **Tailor agents by chat** — describe the behaviour you want in natural language
- **Reusable templates** — codify the agent shapes your team relies on
- **Shared env sets** — reuse credentials across agents without re-entry
- **Session monitoring** — inspect every agent session as a live transcript
  beside a stream of telemetry events (model calls, tool calls, errors)
- **Kubernetes-native** — agents are reconciled by the
  [Hermes Agent Operator](https://github.com/hermeum/hermes-agent-operator)

## Repositories

| Repository | Description |
| --- | --- |
| [hermeum](https://github.com/hermeum/hermeum) | The Hermeum platform — app, docs, shared components, and Helm chart |
| [hermes-agent-operator](https://github.com/hermeum/hermes-agent-operator) | Kubernetes operator that reconciles `HermesAgent` custom resources into running pods |

## Documentation

Full documentation is at **[docs.hermeum.app](https://docs.hermeum.app)**.

## License

Hermeum is released under [AGPL-3.0-or-later](https://github.com/hermeum/hermeum/blob/main/LICENSE).
