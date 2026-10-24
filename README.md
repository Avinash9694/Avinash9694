<p align="center">
  <a href="https://avinash9694.github.io"><img src="assets/banner.svg" alt="Avinash Sahu — Software Developer · React, TypeScript, Rust, Cloud" width="100%"></a>
</p>

<p align="center">
  <a href="https://avinash9694.github.io"><img src="https://img.shields.io/badge/Portfolio-avinash9694.github.io-6366f1?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://avinash9694.github.io/Avinash_Sahu_Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-1f2937?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume"></a>
  <a href="https://www.linkedin.com/in/A-v-i-n-a-s-h/"><img src="https://img.shields.io/badge/LinkedIn-Avinash%20Sahu-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:avinashsahu1994@gmail.com"><img src="https://img.shields.io/badge/Email-avinashsahu1994%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

I build web and desktop software that stays correct when the network, the third-party API or the user misbehaves. Four-plus years across React, TypeScript, Node and Rust, lately on a Tauri + React + Rust desktop app that scans AWS and Azure estates, surfaces findings and runs AI-assisted playbooks: Cognito and OAuth auth, Lexical rich text, DynamoDB telemetry that survives offline, and Jira, Linear and Slack integrations.

## Selected work

Every project is deployed, tested and open source. Most started as a problem at work: an IAM policy I did not trust, an SSE stream that silently renamed an event, a Terraform diff too noisy to review.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/iam-policy-analyzer/"><img src="assets/iam-policy-analyzer.webp" alt="IAM Policy Analyzer screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/iam-policy-analyzer/">IAM Policy Analyzer</a> · <a href="https://github.com/Avinash9694/iam-policy-analyzer">source</a></h3>
      <p>Paste an AWS IAM policy, get a 0–100 risk score and ranked findings: wildcards, privilege-escalation paths such as PassRole + Lambda, public principals, missing MFA/TLS conditions, each with a copyable fix. Deny statements mark what they neutralise. Runs entirely in the browser.</p>
      <p><code>React</code> <code>TypeScript</code> <code>AWS IAM</code> <code>Static analysis</code> <code>112 tests</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/cloud-audit-mcp/"><img src="assets/cloud-audit-mcp.webp" alt="Cloud Audit MCP Server docs screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/cloud-audit-mcp/">Cloud Audit MCP Server</a> · <a href="https://github.com/Avinash9694/cloud-audit-mcp">source</a></h3>
      <p>Fourteen read-only AWS posture checks across S3, EC2, RDS, IAM and CloudTrail, exposed as Model Context Protocol tools for Claude and Cursor. A credential-free fixture mode for demos, and a test that fails if any mutating SDK command is ever imported.</p>
      <p><code>TypeScript</code> <code>MCP</code> <code>AWS SDK v3</code> <code>Zod</code> <code>99 tests</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/sse-stream-inspector/"><img src="assets/sse-stream-inspector.webp" alt="SSE Stream Inspector screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/sse-stream-inspector/">SSE Stream Inspector</a> · <a href="https://github.com/Avinash9694/sse-stream-inspector">source</a></h3>
      <p>Parse, replay and diff Server-Sent Events streams. Flags the same event arriving under two spellings with different payload shapes, shape drift, duplicate or regressing ids, long silences and missing terminal frames. Web Worker parsing and a virtualised timeline handle 10k frames.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Web Workers</code> <code>107 tests</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/iac-diff-viewer/"><img src="assets/iac-diff-viewer.webp" alt="IaC Diff Viewer screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/iac-diff-viewer/">IaC Diff Viewer</a> · <a href="https://github.com/Avinash9694/iac-diff-viewer">source</a></h3>
      <p>Resource-level semantic diff of CloudFormation and Terraform documents with risk tagging and plain-English reasons. The engine is a Rust crate compiled to a 300 KB WebAssembly module, so nothing leaves the browser.</p>
      <p><code>Rust</code> <code>WebAssembly</code> <code>React</code> <code>Terraform</code> <code>115 tests</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/Ecommerce-APP/"><img src="assets/Ecommerce-APP.webp" alt="Northline storefront screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/Ecommerce-APP/">Northline storefront</a> · <a href="https://github.com/Avinash9694/Ecommerce-APP">source</a></h3>
      <p>Full-stack e-commerce: an Express + MongoDB API with JWT auth, stock-enforcing carts and an order status machine, and a React storefront whose data layer swaps between the real API and an in-browser demo adapter, so it runs on GitHub Pages without a server.</p>
      <p><code>React</code> <code>Express</code> <code>MongoDB</code> <code>TanStack Query</code> <code>133 tests</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/TasteOfIndiaHub/"><img src="assets/TasteOfIndiaHub.webp" alt="Taste of India Hub screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/TasteOfIndiaHub/">Taste of India Hub</a> · <a href="https://github.com/Avinash9694/TasteOfIndiaHub">source</a></h3>
      <p>Recipe site rebuilt from Create React App to Vite + TypeScript: ingredient search with chef, region, diet and difficulty facets over Zod-validated data, persistent ingredient checklists, and Firebase auth that is lazy-loaded and degrades gracefully.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Tailwind CSS</code> <code>Firebase</code> <code>46 tests</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/3D-Virtual-Environment/"><img src="assets/3D-Virtual-Environment.webp" alt="3D Virtual Environment screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/3D-Virtual-Environment/">3D Virtual Environment</a> · <a href="https://github.com/Avinash9694/3D-Virtual-Environment">source</a></h3>
      <p>Walkable three.js world: pick one of three animated avatars and explore with WASD or an on-screen joystick behind a third-person spring camera. The original 35 MB scene was compressed to 486 KB with a reproducible glTF pipeline.</p>
      <p><code>three.js</code> <code>TypeScript</code> <code>WebGL</code> <code>glTF</code> <code>59 tests</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://avinash9694.github.io/Laundry-cart-frontend/"><img src="assets/Laundry-cart-frontend.webp" alt="Laundry Cart screenshot" width="100%"></a>
      <h3><a href="https://avinash9694.github.io/Laundry-cart-frontend/">Laundry Cart</a> · <a href="https://github.com/Avinash9694/Laundry-cart-frontend">frontend</a> · <a href="https://github.com/Avinash9694/Laundry-cart-backend">API</a></h3>
      <p>Order management for a laundry service: a four-step garment and wash-type wizard with a live price breakdown, order history with a status timeline, and an Express/Mongoose API that owns pricing and validates every input with Zod.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Express</code> <code>MongoDB</code> <code>100 tests</code></p>
    </td>
  </tr>
</table>

## Stack

<p>
  <img src="https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61dafb" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-0f172a?style=flat-square&logo=tailwindcss&logoColor=38bdf8" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
  <img src="https://img.shields.io/badge/MongoDB-47a248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Tauri-24c8db?style=flat-square&logo=tauri&logoColor=white" alt="Tauri">
  <img src="https://img.shields.io/badge/WebAssembly-654ff0?style=flat-square&logo=webassembly&logoColor=white" alt="WebAssembly">
  <img src="https://img.shields.io/badge/AWS-232f3e?style=flat-square&logo=amazonwebservices&logoColor=ff9900" alt="AWS">
  <img src="https://img.shields.io/badge/DynamoDB-4053d6?style=flat-square&logo=amazondynamodb&logoColor=white" alt="DynamoDB">
  <img src="https://img.shields.io/badge/Cognito%20%2F%20OAuth%202.0-dd344c?style=flat-square&logo=auth0&logoColor=white" alt="Cognito and OAuth">
  <img src="https://img.shields.io/badge/Vitest-6e9f18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/MCP-111827?style=flat-square&logo=anthropic&logoColor=white" alt="Model Context Protocol">
</p>

## How I work

- **Correctness first.** Every async path has loading, empty and error states, and a failure is logged where someone will read it.
- **Tests on the logic that matters**, not on the framework. The projects above carry 770 automated tests between them.
- **A history a reviewer can follow.** Small conventional commits, one coherent step each.

<p align="center"><sub>Portfolio: <a href="https://avinash9694.github.io">avinash9694.github.io</a> · Resume: <a href="https://avinash9694.github.io/Avinash_Sahu_Resume.pdf">PDF</a></sub></p>
