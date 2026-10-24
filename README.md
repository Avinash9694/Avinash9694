# Avinash Sahu

Software developer in Hyderabad. React, TypeScript, Node and Rust, with a bias toward software that stays correct when the network, the third-party API or the user misbehaves.

Currently a lead contributor on a Tauri + React + Rust desktop app that scans AWS and Azure estates, surfaces findings and runs AI-assisted playbooks: Cognito and OAuth auth, Lexical rich text, DynamoDB telemetry that survives offline, and Jira, Linear and Slack integrations.

**Portfolio:** [avinash9694.github.io](https://avinash9694.github.io) · **Resume:** [PDF](https://avinash9694.github.io/Avinash_Sahu_Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/A-v-i-n-a-s-h/) · avinashsahu1994@gmail.com

## Selected work

Every project below is deployed, tested and open source. Each one started as a real problem from work.

| Project | What it does | Stack |
| --- | --- | --- |
| [IAM Policy Analyzer](https://avinash9694.github.io/iam-policy-analyzer/) · [source](https://github.com/Avinash9694/iam-policy-analyzer) | Paste an AWS IAM policy, get ranked findings: wildcards, privilege-escalation paths, public principals, missing conditions, each with a copyable fix. Runs entirely in the browser. 112 tests. | React · TypeScript · AWS IAM |
| [Cloud Audit MCP Server](https://avinash9694.github.io/cloud-audit-mcp/) · [source](https://github.com/Avinash9694/cloud-audit-mcp) | 14 read-only AWS posture checks exposed as Model Context Protocol tools for Claude and Cursor, with a credential-free fixture mode. A test enforces that only List/Describe/Get calls exist. 99 tests. | TypeScript · MCP · AWS SDK v3 |
| [SSE Stream Inspector](https://avinash9694.github.io/sse-stream-inspector/) · [source](https://github.com/Avinash9694/sse-stream-inspector) | Parse, replay and diff Server-Sent Events streams. Catches the same event arriving under two spellings with different payloads, shape drift, id gaps and missing terminals. 107 tests. | React · TypeScript · Web Workers |
| [IaC Diff Viewer](https://avinash9694.github.io/iac-diff-viewer/) · [source](https://github.com/Avinash9694/iac-diff-viewer) | Resource-level semantic diff of CloudFormation and Terraform documents with risk tagging. Rust engine compiled to a 300 KB WebAssembly module. 115 tests. | Rust · WebAssembly · React |
| [Northline storefront](https://avinash9694.github.io/Ecommerce-APP/) · [source](https://github.com/Avinash9694/Ecommerce-APP) | Full-stack e-commerce: Express + MongoDB API with JWT auth, stock-enforcing carts and an order status machine, plus a React storefront that runs in demo mode without a server. 133 tests. | React · Express · MongoDB |
| [Laundry Cart](https://avinash9694.github.io/Laundry-cart-frontend/) · [source](https://github.com/Avinash9694/Laundry-cart-frontend) | Order wizard with live pricing, order history and status timeline for a laundry service; API in a [sibling repo](https://github.com/Avinash9694/Laundry-cart-backend). 100 tests. | React · TypeScript · Express |
| [Taste of India Hub](https://avinash9694.github.io/TasteOfIndiaHub/) · [source](https://github.com/Avinash9694/TasteOfIndiaHub) | Recipe site with ingredient search, facets, persistent checklists and Firebase auth, rebuilt from Create React App to Vite + TypeScript. 46 tests. | React · TypeScript · Firebase |
| [3D Virtual Environment](https://avinash9694.github.io/3D-Virtual-Environment/) · [source](https://github.com/Avinash9694/3D-Virtual-Environment) | Walkable three.js world: pick an avatar, explore with WASD or touch, third-person spring camera. 35 MB scene compressed to 486 KB. 59 tests. | three.js · TypeScript · WebGL |

## How I work

- Correctness first: every async path has loading, empty and error states, and failures are logged where someone will read them.
- Tests on the logic that matters, not on the framework.
- Small, conventional commits with a history a reviewer can follow.
