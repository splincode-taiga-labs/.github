<div align="center">
  <img
    src="./assets/banner.webp"
    width="100%"
    alt="Taiga Labs — independent tooling and experiments for Angular and Taiga UI"
  />

  <h2>Build better Angular experiences.</h2>

  <p>
    Independent developer tools, testing utilities, integrations, and experiments<br />
    for the <a href="https://angular.dev/">Angular</a> and
    <a href="https://taiga-ui.dev/">Taiga UI</a> ecosystem.
  </p>

  <p>
    <a href="#-featured-projects"><strong>Explore projects</strong></a>
    &nbsp;·&nbsp;
    <a href="#-quick-start"><strong>Quick start</strong></a>
    &nbsp;·&nbsp;
    <a href="https://github.com/orgs/splincode-taiga-labs/repositories"><strong>All repositories</strong></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Angular-developer%20tools-0D9488?style=flat-square&logo=angular&logoColor=white" alt="Angular developer tools" />
    <img src="https://img.shields.io/badge/Taiga%20UI-community%20projects-1D2939?style=flat-square" alt="Taiga UI community projects" />
    <img src="https://img.shields.io/badge/Focus-DX%20%C2%B7%20Testing%20%C2%B7%20AI-DB7F68?style=flat-square" alt="Developer experience, testing, and AI" />
  </p>
</div>

---

## ✨ Featured projects

A small collection of practical tools built to make Angular development, debugging, and testing easier.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧪 <a href="https://github.com/splincode-taiga-labs/taiga-ui-playwright">Taiga UI Playwright</a></h3>
      <p><strong>Component testing without the repetitive selectors.</strong></p>
      <p>Locator-first Playwright helpers for Taiga UI components, with an interactive harness catalog and version-specific v4/v5 compatibility guidance.</p>
      <p>
        <a href="https://splincode-taiga-labs.github.io/taiga-ui-playwright/">Harness explorer</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/splincode-taiga-labs/taiga-ui-playwright#install">Install</a>
      </p>
      <a href="https://www.npmjs.com/package/@taiga-ui-labs/playwright"><img src="https://img.shields.io/npm/v/%40taiga-ui-labs%2Fplaywright?style=flat-square&logo=npm" alt="Playwright npm version" /></a>
    </td>
    <td width="50%" valign="top">
      <h3>🧩 <a href="https://github.com/splincode-taiga-labs/taiga-ui-jetbrains-plugin">Taiga xUI Community</a></h3>
      <p><strong>Taiga UI knowledge, directly inside your IDE.</strong></p>
      <p>Project-aware JetBrains tooling for design tokens, icon previews, Angular API documentation, inspections, and navigation.</p>
      <p>
        <a href="https://splincode-taiga-labs.github.io/taiga-ui-jetbrains-plugin/">Live demo</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/splincode-taiga-labs/taiga-ui-jetbrains-plugin">Plugin &amp; docs</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/splincode-taiga-labs/taiga-webmcp">Taiga WebMCP</a></h3>
      <p><strong>Make Angular interfaces accessible to browser AI agents.</strong></p>
      <p>Experimental, opt-in helpers for semantic filtering, sorting, selection, pagination, and read-only operations using shared application state.</p>
      <p>
        <a href="https://github.com/splincode-taiga-labs/taiga-webmcp#api">Explore the API</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/splincode-taiga-labs/taiga-webmcp#safety-and-compatibility">Compatibility &amp; safety</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📝 <a href="https://github.com/splincode-taiga-labs/taiga-signal-forms">Taiga UI × Signal Forms</a></h3>
      <p><strong>Explore Angular Signal Forms compatibility.</strong></p>
      <p>A live control-by-control lab showing how Taiga UI works with Angular's Signal Forms, including support levels and known limitations.</p>
      <p>
        <a href="https://splincode-taiga-labs.github.io/taiga-signal-forms/">Open compatibility lab</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/splincode-taiga-labs/taiga-signal-forms#control-matrix">Support matrix</a>
      </p>
    </td>
  </tr>
</table>

## 🔌 Libraries & integrations

<table>
  <tr>
    <td valign="top" width="68%">
      <h3><a href="https://github.com/splincode-taiga-labs/taiga-dadata">Taiga DaData</a></h3>
      <p>Typed DaData API integration for Angular and Taiga UI: address, name, organization, bank, and email suggestions, with reactive search helpers.</p>
      <p>
        <a href="https://splincode-taiga-labs.github.io/taiga-dadata/">Live demo</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/splincode-taiga-labs/taiga-dadata#установка">Getting started</a>
      </p>
    </td>
    <td valign="middle" align="center">
      <a href="https://www.npmjs.com/package/@taiga-ui-labs/dadata"><img src="https://img.shields.io/npm/v/%40taiga-ui-labs%2Fdadata?style=flat-square&logo=npm" alt="DaData npm version" /></a>
    </td>
  </tr>
</table>

## 🚀 Quick start

Install the tools you need in your own Angular project:

```bash
# Component testing with Playwright
npm install --save-dev @taiga-ui-labs/playwright

# Typed DaData integration
npm install @taiga-ui-labs/dadata
```

Writing Taiga UI tests with an AI coding agent? The Playwright repository also includes a reusable agent skill:

```bash
npx skills add splincode-taiga-labs/taiga-ui-playwright --skill taiga-ui-playwright
```

<sub>Compatibility varies by Taiga UI version and component. Check each project's README before adopting it.</sub>

## 🧪 Demos & prototypes

Small reference implementations exploring onboarding flows with Angular, AG Grid, and Taiga UI.

| Project | What it explores |
| :--- | :--- |
| [AG Grid + Taiga UI onboarding](https://github.com/splincode-taiga-labs/agrid-taiga-onboarding) | Guided onboarding without a separate tour library |
| [Onboarding with ngx-ui-tour](https://github.com/splincode-taiga-labs/agrid-taiga-onboarding-ngx-tour) | Tour lifecycle managed through `ngx-ui-tour-tui-hint` |
| [Multiple onboarding flows](https://github.com/splincode-taiga-labs/agrid-taiga-onboarding-multiple) | Multiple independent onboarding experiences in one interface |

## 🤝 Contribute & explore

These projects grow through real use cases, bug reports, and community feedback. Pick a repository, check its documentation, and open an issue or pull request.

**[Browse all repositories](https://github.com/orgs/splincode-taiga-labs/repositories)** · **[Explore upstream Taiga UI](https://github.com/taiga-family/taiga-ui)**

---

<div align="center">
  <sub>Made for better developer experience, accessible interfaces, and maintainable Angular applications.</sub>
  <br /><br />
  <sub><strong>Independent community initiative.</strong> These projects are unofficial and are not affiliated with or endorsed by the Taiga UI maintainers, Pineopticone, or T-Bank. Third-party names and trademarks belong to their respective owners.</sub>
</div>
