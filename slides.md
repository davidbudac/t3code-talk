# T3 Code

Coordinating agents across harnesses and machines

The hard part of running several agents is keeping track of them.

David Budac·Tuesday, 3 November 2026

---

# What T3 Code is

A control surface for the coding agents you already have.

- Desktop, web and phone, the same threads
- A server on each machine drives its agents
- Local or remote, over T3 Connect

---

# What it adds to the agent you already use

Claude Code, Codex and Cursor keep doing the work. T3 Code sits around them.

| Your agent in a terminal or an editor | With T3 Code |
| --- | --- |
| A window per agent. You go round and check each one. | **One inbox for every thread** Working threads fold away. A question or a finished run brings one back, and your phone buzzes. |
| You tidy up after the PR lands. | **Threads that close themselves** The PR is linked from the branch. When it merges, the thread settles. |
| One harness per session. A second opinion means copy and paste. | **Delegation across harnesses** A thread hands work to Codex, Claude Code or Cursor and gets the findings back. |
| SSH in and run the agent over there. | **Any of your machines, from any device** Pick the machine when you start a thread. Desktop, web or phone. Machines can call each other. |
| Files, previews and devices stay wherever the agent ran. | **The work follows the thread** Attachments land on the right machine; results open here. Projects clone across machines. |
| Automation means a shell script and cron. | **An interface for your other tools** MCP for outside agents, scheduled tasks, webhooks from GitHub. |

---

# An inbox for work that needs you

Send a task, forget it, and let it come back when it needs you.

---

# Delegation across harnesses

One thread does the work and asks two other harnesses to check it.

Example request:

> Implement cursor pagination, then have Codex and Cursor review it.

---

# Threads can coordinate across projects

Start simple: a thread in one repo can read a thread in another.

---

# T3 Code is a server you can connect to

The desktop app is only one of its clients.

---

# Your laptop can be the controller

Pick the machine. The repository, the tools and the agent stay there.

---

# How the machines reach each other

Every machine runs a server. Three ways to connect them.

---

# Files and projects move between machines

What the agent made over there is one click away here.

---

# Ask the Linux box for what this Mac cannot do

One request from this Mac to linuxbox.

Example request:

> Build the Linux release of mtkprof-desktop, run it under a virtual display, and attach a screenshot of the main window. Do not push.

---

# Other tools can drive the workspace

Each machine's server speaks MCP and takes schedules and webhooks.

- Other agents read and start threads over MCP
- Scheduled tasks run a prompt on a timer
- Webhooks start a task from a GitHub event
- A thread they start never gets more than the access you granted

---

# Rapid fire: context and interaction

- **Switch harness mid-thread** context handoff, in the model picker
- **HTML answers in chat** charts, tables, mockups; interactive
- **Attachments are files** real paths on the agent's machine, up to 100 per message
- **Window snapshots** with accessibility data, desktop only
- **One prompt, several models** a thread and a worktree each
- **/goal** keeps working across turns until done

---

# Rapid fire: running the workspace

- **Update every machine** providers, servers, app
- **Add a project to a machine** clone plus chosen .env files
- **Review and merge PRs** sorted by readiness
- **Watch a PR** wakes on checks and reviews
- **Usage and limits** resume at reset
- **T3 triage** your agent reads the logs

---

# What to take home

**Did you coordinate less?**

`curl -fsSL https://t3.codes/install.sh | sh` · github.com/pingdotgg/t3code · MIT · free · bring your own subscriptions
