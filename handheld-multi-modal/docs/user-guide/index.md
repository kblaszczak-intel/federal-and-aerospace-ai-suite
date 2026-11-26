<!--
SPDX-FileCopyrightText: (C) 2026 Intel Corporation
SPDX-License-Identifier: Apache-2.0
-->

# Handheld (Soldier System) Blueprint

<!--hide_directive
<div class="component_card_widget">
  <a class="icon_github" href="https://github.com/open-edge-platform/federal-and-aerospace-ai-suite/tree/main/handheld-multi-modal">
     GitHub
  </a>
  <a class="icon_document" href="https://github.com/open-edge-platform/federal-and-aerospace-ai-suite/blob/main/handheld-multi-modal/README.md">
     Readme
  </a>
  <a class="icon_download" href="https://github.com/open-edge-platform/federal-and-aerospace-ai-suite/releases/download/fedaero-latest/handheld-multi-modal.zip">
     Download Package
  </a>
</div>
hide_directive-->

The Handheld Blueprint provides AI-enabled reference applications for handheld deployment
scenarios, optimized for Intel® edge hardware. The applications run on top of the Edge Node
Infrastructure software - an edge computing platform, which enables hardware acceleration
capabilities.

The main application is the [Handheld Multi-Modal Application](./multi-modal/index.md), a
multi-modal AI operator console that runs entirely on the device. See
[Reference Applications](./applications.md) for all available applications.

## Deployment and Usage

Follow these steps to deploy the Handheld (Soldier System) Blueprint:

1. [Install on Ubuntu](./infrastructure/installation-on-ubuntu.md) or [Customized Image](./infrastructure/customized-image.md) — Build the OS image, flash it to a bootable USB, and validate the provisioned platform.
2. [Install OEP SDKs](install-oep-sdks.md) — Verify hardware accelerators and install the OEP Vision AI SDK on the provisioned target.
3. [Reference Applications](applications.md) — Deploy and use the Handheld Multi-Modal Application or other applications.
4. [Benchmarks](benchmarks.md) — Benchmark AI workloads across the available hardware.

## AI Agent SKILLs

The Handheld Blueprint supports AI agent skills for GitHub Copilot and Claude Code, covering
both platform-level automation (image build, provisioning, power and thermal tuning) and
application-level pipeline generation with Intel DL Streamer. See
[AI Agent SKILLs](agents.md) for the available skills and how to use them.

<!--hide_directive
:::{toctree}
:hidden:

Infrastructure Setup <infrastructure-setup.md>
Reference Applications <applications.md>
Benchmarks <benchmarks.md>
AI Agent SKILLs <agents.md>
Install OEP SDKs <install-oep-sdks.md>
Release Notes <release-notes.md>

:::
hide_directive-->
