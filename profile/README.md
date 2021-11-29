# About Kubewarden

Kubewarden is a policy engine for Kubernetes. It makes possible to
keep Kubernetes clusters secure and compliant by enforcing user
defined policies.

Kubewarden policies can be written using regular programming
languages or even Domain Specific Languages (DSL).

Policies are compiled into WebAssembly modules that are then
distributed using traditional container registries.

## Getting started

The best place to start your journey with Kubewarden is our [official documentation](https://docs.kubewarden.io).

You can stay up to date about the Kubewarden project by reading our [official blog](https://www.kubewarden.io/blog/)
and by following us on [Twitter](https://twitter.com/kubewarden).

Finally, don't forget to discover ready to use policies by visiting the
[Policy Hub](https://hub.kubewarden.io).

## Getting in touch

You can interact with the Kubewarden developers and the whole community
on Slack. You can find us by joining the [`kubewarden` channel](https://kubernetes.slack.com/?redir=%2Fmessages%2Fkubewarden)
hosted by the official Kubernetes workspace.

## Getting involved

The [Kubewarden](https://github.com/kubewarden) organization on
GitHub has quite some repositories associated. Don't be scared,
this section will guide you through them.

### Policy templates

We provide template repositories that can be used to quickly scaffold
new Kubewarden policies.

The repositories feature working code and automation to build, test and release
the final policy.

These repositories follow the `<language>-policy-template` naming convention.
They can be easily found by using the
[`kubewarden-policy-template` GitHub Tag](https://github.com/topics/kubewarden-policy-template).

### Policies

The source code of the policies maintained by the Kubewarden developers can be
found inside of the repositories following the `<policy topic>-policy` naming convention.
All the policies replacing Kubernetes Pod Security Policies (aka PSP) follow
the `<policy-topic>-psp-policy` naming convention.

All the policy reposotories can be easily found by using the
[`kubewarden-policy` GitHub Tag](https://github.com/topics/kubewarden-policy).

> **Note well:** this can return results outside of the `kubewarden` GitHub organization.


