Kubewarden is a policy engine for Kubernetes. It helps with keeping your Kubernetes clusters secure 🔐 and compliant ✔️

Kubewarden policies can be written using regular programming languages or Domain Specific Languages (DSL).

Policies are compiled into [WebAssembly](https://webassembly.org/) modules that are then distributed using traditional [container registries](https://landscape.cncf.io/card-mode?category=container-registry&grouping=category).

## Getting Started 📚

Take a look at our [documentation](https://docs.kubewarden.io) 📖
Stay up to date by reading our [official blog](https://www.kubewarden.io/blog/) 📣 and by following us on [Twitter](https://twitter.com/kubewarden).

Get in touch with us on Slack: join the [`kubewarden` channel](https://kubernetes.slack.com/?redir=%2Fmessages%2Fkubewarden) hosted by the official Kubernetes workspace 👨‍💻 💬 👩‍💻

## Enforcing Policies 🔒

Discover ready to use policies by visiting the [Policy Hub](https://artifacthub.io/packages/search?kind=13&sort=relevance&page=1) 📦

Don't forget to take a look at [`kwctl`](https://github.com/kubewarden/kwctl), our handy multi-purpose tool for managing policies 🛠️ 🧰

## Writing policies 📝

Interested in writing a new policy?
  1. Checkout the step-by-step tutorials inside of our [documentation](https://docs.kubewarden.io) 📖
  1. Add [`kwctl`](https://github.com/kubewarden/kwctl) to your toolbox 🛠️ 🧰
  1. Pick one of the languages from below

| Language | Project Template | SDK | Validation | Mutation | Maturity |
|----------|------------------|-----|------------|----------|----------|
| Rust     | [:octocat:](https://github.com/kubewarden/rust-policy-template) | [:octocat:](https://github.com/kubewarden/policy-sdk-rust) | ✔️ | ✔️ | 🔝 |
| Go ([TinyGo](https://tinygo.org/)) | [:octocat:](https://github.com/kubewarden/go-policy-template) | [:octocat:](https://github.com/kubewarden/policy-sdk-go) | ✔️ | ✔️ | ↗️ |
| Swift | [:octocat:](https://github.com/kubewarden/swift-policy-template) | [:octocat:](https://github.com/kubewarden/policy-sdk-swift) | ✔️ | ✔️ | ↗️ |
| Rego - Open Policy Agent | [:octocat:](https://github.com/kubewarden/opa-policy-template) | [Rego built-ins](https://www.openpolicyagent.org/docs/latest/policy-reference/#built-in-functions) | ✔️ | ❌ | 🔝 |
| Rego - Gatekeeper | [:octocat:](https://github.com/kubewarden/gatekeeper-policy-template) | [Rego built-ins](https://www.openpolicyagent.org/docs/latest/policy-reference/#built-in-functions) | ✔️ | ❌ | 🔝 |
| DotNet     |❌  | [:octocat:](https://github.com/kubewarden/policy-sdk-rust) | ✔️ | ✔️ | ↗️  |


Can't find your favorite language? 🔍 Reach out to us and let's have a chat!

## Useful GitHub tags :octocat: 🏷️

Use these tags to find repositories over **all** GitHub 🗺️ 🌌

| Purpose | Tag |
|---------|-----|
| Policy Template | [`kubewarden-policy-template`](https://github.com/topics/kubewarden-policy-template) |
| Policy | [`kubewarden-policy`](https://github.com/topics/kubewarden-policy) |

## Contributing 🙌

That's fantastic news! 🥳

Other than our [policy templates](https://github.com/topics/kubewarden-policy-template), [policy SDKs](https://github.com/topics/kubewarden-policy-sdk) and [policies](https://github.com/topics/kubewarden-policy), we have the following "core" projects:

| Project | Scope | Language |
|---------|---------|--------|
| [`kubewarden-controller`](https://github.com/kubewarden/kubewarden-controller/contribute) | Kubernetes integration point| Go |
| [`policy-server`](https://github.com/kubewarden/policy-server/contribute) | Run Kubewarden policies | Rust |
| [`kwctl`](https://github.com/kubewarden/kwctl/contribute) | Kubewarden policy multi-purpose cli tool | Rust |




