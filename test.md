# Shuffle Release Summary

**Period:** April 5, 2025 – May 5, 2025

---

## 🚀 Features

* **AI Agent Enhancements**: Implemented a decision rerun system for AI Agents, ensuring all decision actions execute within a single workflow execution. This improves the reliability and consistency of AI-driven processes.

* **Debug UI for AI Agents**: Developed a debug user interface to facilitate troubleshooting and monitoring of AI Agent activities, enhancing transparency and ease of debugging.

* **API Key Management for Notifications**: Stabilized the API key management system to support notification functionalities, providing a more secure and efficient way to handle API keys.

* **Documentation Updates**: Updated `extensions.md` to reflect new features and changes, ensuring that documentation stays current with the latest system capabilities.
* Updated branding details for partners to enhance customization options.
* Made multi-tenant workflows automatically activate apps in child organizations.
* Added support for tracking user roles on login and organization changes for SSO providers.

---

## 🐞 Bug Fixes

* **Workflow Page Crash Fix**: Resolved an issue causing the workflow page to crash in on-premise deployments, improving system stability.

* **AI Agent Execution Stability**: Addressed multiple edge cases in AI Agent execution to prevent failures and ensure smooth operation.

* **Distribution Issue Edge Case**: Fixed a specific edge case related to distribution issues, enhancing the robustness of the system under various conditions.
  
* Corrected a public workflow loading issue in regional failures by falling back to the main region.

* Fixed problems related to app and workflow run limits, allowing adjustments from parent to sub-organisations.

---

## 🔧 Other Updates

* **Helm Chart Adjustments**: Removed unnecessary container ports from the Orborus component in the Helm chart, streamlining deployment configurations.

* **Worker Response Information**: Enhanced the worker component to provide more detailed information in responses, aiding in debugging and monitoring.

* **Python Apps Simplification**: Performed multiple simplifications and rebuilds of Python applications to improve maintainability and performance.

* **Documentation Enhancements**: Made several updates to documentation files, including `configuration.md`, App Certificate and `2.0.2.md`, to provide clearer guidance and reflect recent changes.

* Minor updates to the billing page for improved user experience.

* Updated pricing and open-source articles for clarity and accuracy.
