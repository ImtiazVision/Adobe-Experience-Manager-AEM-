  - **Immutable Content Packages** : are immutable and are stored in the repository. They may be checked into Git and deployed through Cloud Manager.

  - **Mutable Content Packages** : Typically, mutable material is committed to an AEM project using Maven archetypes. Service users, directories, node kinds, customizable templates, and scripts, among other things, are all included in the content.

  - **Content Package Structure** : Deployments must include a single Experience Manager package that includes code, configuration, and baseline content. Because the experience manager demands a separation of content and code, a single content package cannot be deployed to both applications and runtime editable regions of the repository such as content, conf, home, and so on.
