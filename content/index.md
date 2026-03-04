---
seo:
  title: Sulala Developer Documentation
  description: Sulala Platform — Agent (local AI orchestration), Integrations (OAuth), and SulalaHub Store (skill registry).
---

::u-page-hero
#title
Sulala Platform

#description
Local AI orchestration, OAuth integrations, and a public skill store. :br Documentation for the Agent, Integrations service, and SulalaHub Store.

#links
  :::u-button
  ---
  color: neutral
  size: xl
  to: /getting-started/quick-start
  trailing-icon: i-lucide-arrow-right
  ---
  Get Started
  :::

  :::u-button
  ---
  color: neutral
  icon: i-lucide-plug
  size: xl
  to: /platform/integrations
  variant: outline
  ---
  Integrations
  :::

  :::u-button
  ---
  color: neutral
  icon: i-lucide-store
  size: xl
  to: /platform/store
  variant: outline
  ---
  Store
  :::
::

::u-page-section
#title
Documentation

#features
  :::u-page-feature
  ---
  icon: i-lucide-rocket
  to: /getting-started/quick-start
  ---
  #title
  [Getting Started]{.text-primary}
  
  #description
  Get the Agent, Integrations, and a skill from the Store running in under 10 minutes.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-cpu
  to: /platform/agent
  ---
  #title
  [Sulala Agent]{.text-primary}
  
  #description
  Local AI orchestration: gateway, file watcher, task scheduler, skills, and dashboard. Runs on 127.0.0.1:2026. See [CLI reference](/platform/cli-reference) for all commands.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-plug
  to: /platform/integrations
  ---
  #title
  [Integrations]{.text-primary}
  
  #description
  OAuth connections service. Connect Gmail, GitHub, Slack, and more once; the agent uses tokens via connectionId.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-store
  to: /platform/store
  ---
  #title
  [SulalaHub Store]{.text-primary}
  
  #description
  Public skill store: browse, install, and publish skills. Optional paid skills and creator accounts.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-terminal
  to: /platform/cli-reference
  ---
  #title
  [CLI Reference]{.text-primary}
  
  #description
  All Sulala Agent CLI commands: status, doctor, tasks, logs, skill list/install/uninstall/update, onboard, start/stop, init, update, version.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-book-open
  to: /guides/deployment
  ---
  #title
  [Guides]{.text-primary}
  
  #description
  Deployment, self-hosting, using the dashboard, concepts, glossary, privacy & data, limits, changelog, contribution, and get help.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-git-pull-request
  to: /guides/contribution-guide
  ---
  #title
  [Contribution Guide]{.text-primary}
  
  #description
  How to contribute — run from source, where to change code, lint and tests, and submitting skills, integrations, or docs.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-shield
  to: /guides/privacy-and-data
  ---
  #title
  [Privacy & Data]{.text-primary}
  
  #description
  What runs locally, what is sent to external services, and how credentials are stored.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-wrench
  to: /troubleshooting/common-issues
  ---
  #title
  [Troubleshooting]{.text-primary}
  
  #description
  Common issues and FAQ for the Agent, Integrations, and Store.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-message-circle
  to: /guides/get-help
  ---
  #title
  [Get Help]{.text-primary}
  
  #description
  Where to ask questions, report bugs, and join the community.
  :::
::

::u-page-section
#title
Platform components

#features
  :::u-page-feature
  ---
  icon: i-lucide-cpu
  to: /platform/agent
  ---
  #title
  [Sulala Agent]{.text-primary}
  
  #description
  Gateway, file watcher, task scheduler, AI orchestration (OpenAI, Claude, Gemini, Ollama), skills, and dashboard.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-plug
  to: /platform/integrations
  ---
  #title
  [Integrations]{.text-primary}
  
  #description
  Standalone OAuth server. Store tokens once; the agent and other apps use connections via connectionId.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-store
  to: /platform/store
  ---
  #title
  [SulalaHub Store]{.text-primary}
  
  #description
  Skill registry and catalog. Set SKILLS_REGISTRY_URL in the agent to browse and install skills.
  :::
::
