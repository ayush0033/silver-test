# Shuffle 2.0.3 - Enhancements in Branding, SSO Role Tracking, and Workflow Execution

<img width="809" alt="Screenshot 2025-05-08 at 7 28 28 PM" src="https://github.com/user-attachments/assets/19b80458-d167-4437-bbd5-ce6f6ea4ec4f" />

## ✅ Important updates

* **AI Agent Enhancements**: Implemented a decision rerun system for AI Agents, ensuring all decision actions execute within a single workflow execution. This improves the reliability and consistency of AI-driven processes.

  <img width="701" alt="AI_Agent_Enhancements" src="https://github.com/user-attachments/assets/02fd993d-4ec2-4952-b943-0f3bfdd50068" />

* **[Debug UI for AI Agents](https://shuffler.io/docs/extensions#ai-agents)**: Developed a debug user interface to facilitate troubleshooting and monitoring of AI Agent activities, enhancing transparency and ease of debugging.

  <img width="850" alt="Debug_UI_for_AI_Agents" src="https://github.com/user-attachments/assets/8895f732-0c0a-46a4-856c-0a523338f6c6" />


* **API Key Management for Notifications**: Stabilized the API key management system to support notification functionalities, providing a more secure and efficient way to handle API keys.

## 🚀 Features
* **Documentation Updates**: Updated [`extensions.md`](https://shuffler.io/docs/extensions) to reflect new features and changes, ensuring that documentation stays current with the latest system capabilities.
* Updated [branding details](https://shuffler.io/admin?admin_tab=branding) for partners to enhance customization options.
* Made multi-tenant workflows automatically activate apps in child organizations.
* Added support for tracking user roles on login and organization changes for [SSO providers](https://shuffler.io/admin?admin_tab=sso).

---

## 🐞 Bug Fixes

* **Workflow Page Crash Fix**: Resolved an issue causing the workflow page to crash in on-premise deployments, improving system stability.

* **AI Agent Execution Stability**: Addressed multiple edge cases in AI Agent execution to prevent failures and ensure smooth operation.

* **Distribution Issue Edge Case**: Fixed a specific edge case related to distribution issues, enhancing the robustness of the system under various conditions.
  
* Corrected a public workflow loading issue in regional failures by falling back to the main region.

* Fixed problems related to app and workflow run limits, allowing adjustments from parent to sub-organisations.

---

## 🔧 Other Updates

* **[Helm Chart Adjustments](https://github.com/Shuffle/Shuffle/tree/main/functions/kubernetes/charts/shuffle)**: Removed unnecessary container ports from the Orborus component in the Helm chart, streamlining deployment configurations.

* **Worker Response Information**: Enhanced the worker component to provide more detailed information in responses, aiding in debugging and monitoring.

* **Python Apps Simplification**: Performed multiple simplifications and rebuilds of Python applications to improve maintainability and performance.

* **Documentation Enhancements**: Made several updates to documentation files, including [`configuration.md`](https://shuffler.io/docs/configuration), [App Certificate](https://shuffler.io/docs/configuration#app-certificates), ect. to provide clearer guidance and reflect recent changes.

* Minor updates to the [billing page](https://shuffler.io/admin?admin_tab=billingstats) for improved user experience.

* Updated [pricing](https://shuffler.io/pricing) and [open-source articles](https://shuffler.io/articles/Shuffle_Open_Source) for clarity and accuracy.
