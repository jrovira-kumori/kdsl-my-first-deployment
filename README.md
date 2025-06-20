# My First Kumori DSL Application Example

This repository contains a simple "Hello Kumori" application, designed as a minimal example to get started with Kumori DSL. It demonstrates the basic structure of a `kdsl` project, including component contracts, implementations, services, and a top-level deployment.

> [!NOTE]
> Last tested with `kdsl` version `0.0.1-alpha.8`

## Files in This Repository

* `kumori.mod.json`: The module manifest file for this `kdsl` project.
* `component.h.kumori`: Defines the **contract (interface)** for the `EchoServer` component.
* `component.kumori`: Provides the **implementation** details for the `EchoServer` component.
* `deployment.kumori`: Contains the top-level `my-first-deployment` definition, orchestrating the `EchoServer` with specific configuration and resource requests.
