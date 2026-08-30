<p align="center">
  <img src="logo.png" alt="Hermeum" width="500" />
</p>

<p align="center">
  <strong>An open platform for creating tailored AI agents for your team.</strong>
</p>

<p align="center">
  <a href="https://docs.hermeum.app">Documentation</a>
  · <a href="https://github.com/hermeum/hermes-agent-operator">Operator</a>
</p>

---

Hermeum turns the open-source
[Hermes agent](https://hermes-agent.nousresearch.com/docs) into a managed
platform. Describe what your agent should do, and Hermeum gives you a working
agent you can chat with, deploy, and iterate on — all running on Kubernetes as
`HermesAgent` custom resources.

## Highlights

- **Tailor agents by chat** — describe the behaviour you want in natural language
- **Reusable templates** — codify the agent shapes your team relies on
- **Shared env sets** — reuse credentials across agents without re-entry
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