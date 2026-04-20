# Appium (appium)
Appium is an open-source test automation framework governed by the OpenJS Foundation, designed to facilitate UI automation of many app platforms including mobile (iOS, Android), browser (Chrome, Firefox, Safari), desktop (macOS, Windows), and TV (Roku, tvOS, Android TV). It implements the W3C WebDriver protocol and provides an extensible ecosystem of drivers, clients, and plugins.

**URL:** [Visit APIs.json URL](https://appium.io/apis.json)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Android, Cross-Platform, iOS, Mobile Testing, Open Source, OpenJS Foundation, Test Automation, WebDriver

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Appium Server API
The main Appium server API that implements the W3C WebDriver protocol for mobile, web, desktop, and TV app automation. Supports session management, element interaction, actions, screenshots, and Appium-specific device commands.

**Human URL:** [https://appium.io/](https://appium.io/)

#### Tags:

 - Android, Automation, iOS, Mobile Testing, WebDriver

#### Properties

- [Documentation](https://appium.io/docs/en/latest/)
- [OpenAPI](openapi/appium-server-openapi.yaml)
- [GitHubRepository](https://github.com/appium/appium)
- [APIReference](https://appium.io/docs/en/latest/reference/)
- [JSONSchema - Session Info Schema](json-schema/appium-server-session-info-schema.json)
- [JSONSchema - Find Element Request Schema](json-schema/appium-server-find-element-request-schema.json)
- [JSONSchema - App ID Request Schema](json-schema/appium-server-app-id-request-schema.json)
- [JSONSchema - Action Sequence Schema](json-schema/appium-server-action-sequence-schema.json)
- [JSONSchema - Cookie Schema](json-schema/appium-server-cookie-schema.json)
- [JSONSchema - Error Response Schema](json-schema/appium-server-error-response-schema.json)

### Appium Inspector
Standalone GUI inspector for mobile apps that communicates with an Appium server, enabling visual element inspection and XPath generation for test authoring.

**Human URL:** [https://github.com/appium/appium-inspector](https://github.com/appium/appium-inspector)

#### Tags:

 - Debugging, GUI, Inspector, Mobile Testing

#### Properties

- [GitHubRepository](https://github.com/appium/appium-inspector)
- [SDK - Desktop App Downloads](https://github.com/appium/appium-inspector/releases)

### Appium UiAutomator2 Driver
The primary Appium driver for Android automation, backed by Google's UiAutomator2 framework. Supports Android 5.0+ devices and emulators.

**Human URL:** [https://github.com/appium/appium-uiautomator2-driver](https://github.com/appium/appium-uiautomator2-driver)

#### Tags:

 - Android, Automation, Driver, Mobile Testing

#### Properties

- [GitHubRepository](https://github.com/appium/appium-uiautomator2-driver)
- [Documentation](https://github.com/appium/appium-uiautomator2-driver#readme)

### Appium XCUITest Driver
The primary Appium driver for iOS and tvOS automation, backed by Apple's XCTest framework. Supports iOS 12+ and macOS Sequoia.

**Human URL:** [https://github.com/appium/appium-xcuitest-driver](https://github.com/appium/appium-xcuitest-driver)

#### Tags:

 - Automation, Driver, iOS, Mobile Testing, tvOS

#### Properties

- [GitHubRepository](https://github.com/appium/appium-xcuitest-driver)
- [Documentation](https://github.com/appium/appium-xcuitest-driver#readme)

## Common Properties

- [GettingStarted](https://appium.io/docs/en/latest/quickstart/)
- [GitHubOrganization](https://github.com/appium)
- [Documentation](https://appium.io/docs/en/latest/)
- [Support](https://discuss.appium.io/)
- [Slack](http://appium.slack.com)
- [StackOverflow](https://stackoverflow.com/questions/tagged/appium)
- [YouTube](https://www.youtube.com/c/AppiumConf)
- [ChangeLog](https://github.com/appium/appium/blob/master/CHANGELOG.md)
- [SDK - Python Client](https://github.com/appium/python-client)
- [SDK - Java Client](https://github.com/appium/java-client)
- [SDK - Ruby Client](https://github.com/appium/ruby_lib_core)
- [SDK - .NET Client](https://github.com/appium/dotnet-client)
- [Tools - MCP Server](https://github.com/appium/appium-mcp)

## Features

| Name | Description |
|------|-------------|
| Multi-Platform Support | Automate iOS, Android, Windows, macOS, web browsers, and TV platforms from a single framework |
| WebDriver Protocol | Implements the W3C WebDriver protocol for standard, cross-platform automation |
| Extensible Driver Architecture | Plugin-based driver system supports any platform through community and official drivers |
| Multiple Language Clients | Official client libraries for Python, Java, JavaScript, Ruby, .NET, and more |
| WebDriver BiDi Support | Supports the next-generation WebDriver BiDi bidirectional protocol |
| MCP Server | Model Context Protocol server for AI-assisted test automation |
| Inspector GUI | Visual app inspector for element discovery and XPath/accessibility ID generation |

## Use Cases

| Name | Description |
|------|-------------|
| Mobile App Testing | Automated functional and regression testing of iOS and Android native apps |
| Cross-Platform Test Suites | Single test codebase targeting multiple platforms and devices |
| CI/CD Integration | Running automated mobile tests in continuous integration pipelines |
| Web Automation | Browser automation on mobile and desktop via WebDriver |
| AI-Assisted Testing | Using the MCP server to enable AI agents to drive test execution |

## Integrations

| Name | Description |
|------|-------------|
| BrowserStack | Cloud device farm integration for running Appium tests on real devices |
| Sauce Labs | Cloud testing platform with Appium support for real and virtual devices |
| LambdaTest | Cloud test execution platform with Appium integration |
| TestNG | Java testing framework commonly used with Appium Java client |
| pytest | Python testing framework used with the Appium Python client |
| WebdriverIO | JavaScript test automation framework with built-in Appium support |
| Selenium Grid | Distributed test execution grid compatible with Appium sessions |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Appium Server API](openapi/appium-server-openapi.yaml)

### JSON Schema

- [Session Info Schema](json-schema/appium-server-session-info-schema.json)
- [Find Element Request Schema](json-schema/appium-server-find-element-request-schema.json)
- [App ID Request Schema](json-schema/appium-server-app-id-request-schema.json)
- [Action Sequence Schema](json-schema/appium-server-action-sequence-schema.json)
- [Cookie Schema](json-schema/appium-server-cookie-schema.json)
- [Error Response Schema](json-schema/appium-server-error-response-schema.json)

### JSON Structure

- [Session Info Structure](json-structure/appium-server-session-info-structure.json)
- [Find Element Request Structure](json-structure/appium-server-find-element-request-structure.json)
- [App ID Request Structure](json-structure/appium-server-app-id-request-structure.json)
- [Action Sequence Structure](json-structure/appium-server-action-sequence-structure.json)
- [Cookie Structure](json-structure/appium-server-cookie-structure.json)
- [Error Response Structure](json-structure/appium-server-error-response-structure.json)

### JSON-LD

- [Appium Server Context](json-ld/appium-server-context.jsonld)

### Examples

- [Session Info Example](examples/appium-server-session-info-example.json)
- [Find Element Request Example](examples/appium-server-find-element-request-example.json)
- [App ID Request Example](examples/appium-server-app-id-request-example.json)
- [Action Sequence Example](examples/appium-server-action-sequence-example.json)
- [Cookie Example](examples/appium-server-cookie-example.json)
- [Error Response Example](examples/appium-server-error-response-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Appium Server API](capabilities/shared/appium-server.yaml) — 7 operations for WebDriver protocol automation

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Mobile Test Automation](capabilities/mobile-test-automation.yaml) | Appium Server API | 7 | QA Engineer, Test Automation Engineer |

## Vocabulary

- [Appium Vocabulary](vocabulary/appium-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 10 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Appium Spectral Rules](rules/appium-spectral-rules.yml) — 26 rules across 8 categories enforcing Appium API conventions

## Maintainers

**FN:** Appium Contributors

**Email:** appium@googlegroups.com
