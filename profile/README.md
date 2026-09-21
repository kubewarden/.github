# Kubernetes security, from admission to runtime

Kubewarden is an open source security platform for Kubernetes: a set of complementary components to secure your workloads across the entire lifecycle. From admission, to runtime, and beyond.

Use the components you need, together or independently.

| Component                                                                   | What it does                                                                  | Status       | Repository                                                           |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------- |
| [Admission Controller](https://www.kubewarden.io/component/adm-controller/) | Stop unsafe workloads before they enter your cluster                          | Stable       | [`adm-controller`](https://github.com/kubewarden/adm-controller)     |
| [Network Enforcer](https://www.kubewarden.io/component/network-enforcer/)   | Discover network activity and secure the communication between your workloads | Experimental | [`network-enforcer`](https://github.com/kubewarden/network-enforcer) |
| [Runtime Enforcer](https://www.kubewarden.io/component/runtime-enforcer/)   | Control what can run inside your Kubernetes pods                              | Beta         | [`runtime-enforcer`](https://github.com/kubewarden/runtime-enforcer) |
| [SBOM Scanner](https://www.kubewarden.io/component/sbom-scanner/)           | Find vulnerabilities in the container images running inside your cluster      | Beta         | [`sbomscanner`](https://github.com/kubewarden/sbomscanner)           |

## Getting started

- [Documentation](https://docs.kubewarden.io)
- [Blog](https://www.kubewarden.io/blog/)
- [Community](https://www.kubewarden.io/#get-in-touch): social channels, Slack and the calendar of our monthly community meetings
- [kubewarden/community](https://github.com/kubewarden/community): governance, repository scopes and maturity levels of the project

## Admission Controller

The Admission Controller is an extensible, Kubernetes-native policy engine. Policies can allow a request, mutate its resources, or deny it.

Policies are written using regular programming languages (Rust, Go, ...) or Domain Specific Languages (Rego, CEL, ...). They are compiled into [WebAssembly](https://webassembly.org/) modules and distributed using standard OCI [container registries](https://landscape.cncf.io/card-mode?category=container-registry&grouping=category).

Discover ready to use policies on [ArtifactHub](https://artifacthub.io/packages/search?kind=13&sort=relevance&page=1).

Interested in writing your own policy? These resources will get you started:

- [Step-by-step tutorials](https://docs.kubewarden.io/admission-controller/latest/en/tutorials/writing-policies/index.html) inside of our documentation
- [Policy SDKs](https://github.com/kubewarden/community/#policies-sdks): overview of the Policy SDKs available, and their maturity level
- [Policy templates](https://github.com/kubewarden/community/#policies-templates): boilerplate code to help you get started

Use these GitHub topics to find policy repositories over **all** GitHub:

| Purpose         | Topic                                                                                |
| --------------- | ------------------------------------------------------------------------------------ |
| Policy          | [`kubewarden-policy`](https://github.com/topics/kubewarden-policy)                   |
| Policy SDK      | [`kubewarden-policy-sdk`](https://github.com/topics/kubewarden-policy-sdk)           |
| Policy Template | [`kubewarden-policy-template`](https://github.com/topics/kubewarden-policy-template) |

## Contributing

Check our [general CONTRIBUTING.md docs](https://github.com/kubewarden/community/blob/main/CONTRIBUTING.md).

Quick links to the core projects:

| Project                                                                         | Scope                          | Language |
| ------------------------------------------------------------------------------- | ------------------------------ | -------- |
| [`adm-controller`](https://github.com/kubewarden/adm-controller/contribute)     | Admission Controller           | Go, Rust |
| [`helm-charts`](https://github.com/kubewarden/helm-charts/contribute)           | Helm charts for all components | Helm     |
| [`network-enforcer`](https://github.com/kubewarden/network-enforcer/contribute) | Network Enforcer               | Go       |
| [`runtime-enforcer`](https://github.com/kubewarden/runtime-enforcer/contribute) | Runtime Enforcer               | Go       |
| [`sbomscanner`](https://github.com/kubewarden/sbomscanner/contribute)           | SBOM Scanner                   | Go       |
