# Contour ![Build and Test Pull Request](https://github.com/projectcontour/contour/workflows/Build%20and%20Test%20Pull%20Request/badge.svg) [![Go Report Card](https://goreportcard.com/badge/github.com/projectcontour/contour)](https://goreportcard.com/report/github.com/projectcontour/contour) ![GitHub release](https://img.shields.io/github/release/projectcontour/contour.svg) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Slack](https://img.shields.io/badge/slack-join%20chat-e01563.svg?logo=slack)](https://kubernetes.slack.com/messages/contour) [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/4141/badge)](https://bestpractices.coreinfrastructure.org/projects/4141)


![Contour is fun at parties!](contour.png)

## Overview

Contour is an Ingress controller for Kubernetes that works by deploying the [Envoy proxy](https://www.envoyproxy.io/) as a reverse proxy and load balancer.
Contour supports dynamic configuration updates out of the box while maintaining a lightweight profile.

Contour also introduces a new ingress API ([HTTPProxy](/site/docs/main/httpproxy.md)) which is implemented via a Custom Resource Definition (CRD).
Its goal is to expand upon the functionality of the Ingress API to allow for a richer user experience as well as solve shortcomings in the original design.

## Prerequisites

Contour requires Kubernetes version 1.16 or later, for [v1 Custom Resource Definition support](https://kubernetes.io/blog/2019/09/18/kubernetes-1-16-release-announcement/#custom-resources-reach-general-availability).

RBAC must be enabled on your cluster.

## Get started

Getting started with Contour is as simple as one command.
See the [Getting Started](https://projectcontour.io/getting-started) document.

## Troubleshooting

If you encounter issues, review the Troubleshooting section of [the docs](https://projectcontour.io/docs), [file an issue](https://github.com/projectcontour/contour/issue), or talk to us on the [#contour channel](https://kubernetes.slack.com/messages/contour) on the Kubernetes Slack server.

## Contributing

Thanks for taking the time to join our community and start contributing!

- Please familiarize yourself with the [Code of Conduct](/CODE_OF_CONDUCT.md) before contributing.
- See [CONTRIBUTING.md](/CONTRIBUTING.md) for information about setting up your environment, the workflow that we expect, and instructions on the developer certificate of origin that we require.
- Check out the [open issues](https://github.com/projectcontour/contour/issues).
- Join our Kubernetes Slack channel: [#contour](https://kubernetes.slack.com/messages/contour/)
- Join the **Contour Community Meetings** - [schedule, notes, and recordings can be found here](https://projectcontour.io/community)

## Roadmap

See [Contour's roadmap](https://github.com/projectcontour/community/blob/main/ROADMAP.md) to learn more about where we are headed.

## Changelog

See [the list of releases](https://github.com/projectcontour/contour/releases) to find out about feature changes.
