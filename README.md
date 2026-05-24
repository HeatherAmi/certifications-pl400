# Certifications: PL-400 Power Platform Developer

Bite-size, follow-along projects to help you prepare for the **Microsoft PL-400: Power Platform Developer** certification, and to build real, practical skills in Power Platform development.

Every project is self-contained, comes with a written step-by-step guide, and has a matching short video on YouTube. Videos are kept to around 15 minutes each so you can follow along in focused sessions.

## Who this is for

- Anyone preparing for the PL-400 certification exam
- Power Platform makers wanting to move into developer-level skills
- Trainers and team leads looking for ready-made teaching content
- Developers new to the Microsoft Power Platform

## Before you start

You will need a Power Platform environment with Dataverse enabled, and a set of developer tools installed. If you do not have these yet, complete the relevant modules in my [foundation-setup](https://github.com/HeatherAmi/foundation-setup) repo first.

Minimum requirements:
- A Microsoft 365 tenant with Power Platform licences
- A Dataverse-enabled environment (a developer environment is fine)
- Visual Studio 2022 (Community Edition is fine) for plug-in projects
- Visual Studio Code for PCF and connector projects
- Power Platform CLI (PAC CLI)
- Node.js (for PCF projects)
- XrmToolBox with Plugin Registration Tool

## The project series

Projects run from simple to complex. Each one builds on skills from the previous, but you can also jump straight to a specific topic if you prefer.

| # | Project | Skills | Status |
|---|---------|--------|--------|
| 01 | [Hello Dataverse](projects/01-hello-dataverse) | Dataverse tables, model-driven apps, solutions | In progress |
| 02 | [Account Auto-Numbering Plug-in](projects/02-account-autonumber-plugin) | C# plug-ins, Plugin Registration Tool, tracing | Planned |
| 03 | [Canvas App Expense Tracker](projects/03-canvas-expense-tracker) | Canvas apps, Power Fx, Dataverse connector | Planned |
| 04 | [Form Validation with JavaScript](projects/04-form-validation-js) | JS web resources, form events, Xrm.WebApi | Planned |
| 05 | [Rating Star PCF Control](projects/05-pcf-rating-star) | PCF, TypeScript, Fluent UI | Planned |
| 06 | [Approval Flow with Adaptive Cards](projects/06-approval-flow) | Power Automate, expressions, Teams connector | Planned |
| 07 | [Weather Custom Connector](projects/07-weather-connector) | Custom connectors, OpenAPI, Postman | Planned |
| 08 | [Azure Function and Webhook](projects/08-azure-function-webhook) | Webhooks, Function Apps, async patterns | Planned |
| 09 | [Service Bus Integration](projects/09-service-bus) | Service Bus, async plug-ins, queues | Planned |
| 10 | [End-to-End Capstone](projects/10-capstone) | Canvas + Connector + Function + Webhook + Dataverse + ALM | Planned |

## Project structure

Every project folder follows the same layout:

```
projects/NN-project-name/
├── README.md           Overview, prerequisites, learning outcomes, video links
├── trainee-guide.md    Full step-by-step guide for following along
├── solution/           Downloadable managed and unmanaged solutions
├── src/                Any source code (plug-ins, PCF, scripts)
└── assets/             Screenshots and supporting images
​```



## How to use this repo

**Option 1: Follow along.** Open the project README, watch the videos, and build it yourself using the trainee guide.

**Option 2: Skip ahead.** Download the managed solution from the `solution/` folder and import it into your environment.

**Option 3: Teach with it.** Everything here is MIT licensed. Fork it, adapt it, use it in your own training. A credit back is appreciated but not required.

## Conventions used throughout

- Publisher: **Heather Ami Digital**
- Publisher prefix: **had**
- All custom tables and columns use the `had_` prefix
- Solution names use **PascalCase** with no spaces
- Code is commented thoroughly so it can be read as documentation

## YouTube

[youtube.com/@HeatherAmiDigital](https://www.youtube.com/@HeatherAmiDigital)

## Status

This repo is being built out project by project. Check the table above for current status.

## Licence

Content in this repository is shared under the [MIT Licence](LICENSE). Use it, adapt it, share it.

