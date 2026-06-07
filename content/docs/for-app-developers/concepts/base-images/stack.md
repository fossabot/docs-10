
+++
title="Stack (deprecated)"
aliases=[
  "/docs/concepts/components/stack",
  "/docs/using-pack/stacks/"
]
weight=99
+++

A stack (deprecated) is the grouping together of the build and run base images, represented by a unique ID.

<!--more-->

As of Platform API 0.12 and Buildpack API 0.10, stacks are deprecated in favor of existing constructs in the container image ecosystem such as operating system name, operating system distribution, and architecture.

For more information, see

* Platform API 0.12 [migration guide](/docs/for-platform-operators/how-to/migrate/platform-api-0.11-0.12/)
* Buildpack API 0.10 [migration guide](/docs/for-buildpack-authors/how-to/migrate/buildpack-api-0.9-0.10/)
* [Build image](/docs/for-app-developers/concepts/base-images/build/) concept
* [Run image](/docs/for-app-developers/concepts/base-images/run/) concept
* [Target data](/docs/for-buildpack-authors/concepts/targets/)

> `pack stack suggest` is also deprecated. Use `pack builder suggest` to find
> recommended builders that use current base images.
