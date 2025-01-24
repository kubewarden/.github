Kubewarden is a policy engine for Kubernetes. It helps with keeping your Kubernetes clusters secure 🔐 and compliant ✔.

Kubewarden policies can be written using regular programming languages or Domain Specific Languages (DSL).

Policies are compiled into [WebAssembly](https://webassembly.org/) modules that are then distributed using traditional [container registries](https://landscape.cncf.io/card-mode?category=container-registry&grouping=category).

## Getting Started 📚

Check our first-stop [kubewarden/community](https://github.com/kubewarden/community) 👋 repository for information about the organization of the project.

Take a look at our [documentation](https://docs.kubewarden.io) 📖
Stay up to date by reading our [official blog](https://www.kubewarden.io/blog/) 📣 and by following us on [Bluesky](https://bsky.app/profile/kubewarden.bsky.social) or [Mastodon](https://hachyderm.io/@kubewarden).

Get in touch with us on Slack: join the [`kubewarden` channel](https://kubernetes.slack.com/?redir=%2Fmessages%2Fkubewarden) hosted by the official Kubernetes workspace 👨‍💻 💬 👩‍💻

## Enforcing Policies 🔒

Discover ready to use policies by visiting [ArtifactHub](https://artifacthub.io/packages/search?kind=13&sort=relevance&page=1) 📦

Don't forget to take a look at [`kwctl`](https://github.com/kubewarden/kwctl), our handy multi-purpose tool for managing policies 🛠️ 🧰

## Writing policies 📝

Interested in writing a new policy?

Kubewarden allows you to write policies using a variety of programming languages, including Rust, Go, Rego, CEL and others.

These are some useful resources to get you started:
 - [Step-by-step tutorials](https://docs.kubewarden.io/tutorials/writing-policies) inside of our documentation 📖
 - [Policy SDK](https://github.com/kubewarden/community/#policies-sdks): overview of the Policy SDKs available, and their maturity level 📚
 - [Policy templates](https://github.com/kubewarden/community/#policies-templates): boilerplate code to help you get started 🚀  

## Useful GitHub tags :octocat: 🏷️

Use these tags to find repositories over **all** GitHub 🗺️ 🌌

| Purpose | Tag |
|---------|-----|
| Policy Template | [`kubewarden-policy-template`](https://github.com/topics/kubewarden-policy-template) |
| Policy | [`kubewarden-policy`](https://github.com/topics/kubewarden-policy) |
| Policy SDK | [`kubewarden-policy-sdk`](https://github.com/topics/kubewarden-policy-sdk) |

## Contributing 🙌

That's fantastic news! 🥳

Check our [general CONTRIBUTING.md docs](https://github.com/kubewarden/community/blob/main/CONTRIBUTING.md).

Quick links to "core" projects:

| Project | Scope | Language |
|---------|---------|--------|
| [`kubewarden-controller`](https://github.com/kubewarden/kubewarden-controller/contribute) | Kubernetes integration point| Go |
| [`policy-server`](https://github.com/kubewarden/policy-server/contribute) | Run Kubewarden policies | Rust |
| [`kwctl`](https://github.com/kubewarden/kwctl/contribute) | Kubewarden policy multi-purpose cli tool | Rust |
