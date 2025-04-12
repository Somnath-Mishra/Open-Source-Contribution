# 💻 Contributions to Oppia

This document outlines my contributions to the [Oppia](https://github.com/oppia/oppia) open-source project. It includes bug fixes, test implementations, validation improvements, and transactional support for critical operations.

---

## ✅ Merged Pull Requests

|No. | PR Number | Title | Description |
|-----------|-----------|-------|-------------|
|1. | [#21184](https://github.com/oppia/oppia/pull/21184) | fix #20850 : Topic url fragment validation issue | Created a new URL fragment editor with the required functionality as a shared component using Angular and TypeScript. |
|2. | [#21205](https://github.com/oppia/oppia/pull/21205) | Fix #18795: Remove the function convert_millisecs_time_to_datetime_object and its uses | Removed the logic for converting datetime objects to milliseconds and vice versa to maintain consistency. |
|3. | [#21353](https://github.com/oppia/oppia/pull/21353) | fix #21017: Perform state schema migration on exp data obtained from cache | Added a function to migrate an exploration version to the current state obtained from the cache. |
|4. | [#21360](https://github.com/oppia/oppia/pull/21360) | fix #20332: Beam job to audit Topic and related to models to ensure they are valid | Implemented an Apache Beam job to validate relationships between data models. |
|5. | [#21772](https://github.com/oppia/oppia/pull/21772) | fix #19636: Beam job change user null bio to empty string in UserSettings model | Implemented an Apache Beam job to update corrupted data models on the server, resolving internal server errors. |
|6. | [#22190](https://github.com/oppia/oppia/pull/22190) | Fix part of #21646 :Add acceptance test for download any version of the exploration from the history tab | Wrote a Puppeteer-based acceptance test for exploration download by the editor. |

---

## 🕒 Opened Pull Requests

|No. | PR Number | Title | Description |
|-----------|-----------|-------|-------------|
|1. | [#21655](https://github.com/oppia/oppia/pull/21655) | Fix #20289: Make topic deletion logic transactional | Implementing topic deletion logic to be transactional. |
|2. | [#22115](https://github.com/oppia/oppia/pull/22115) | Fix part of #18973: Enable solution tab item selection input interaction | Enabling the solution tab for the Item Selection Input interaction. |
|3. | [#22150](https://github.com/oppia/oppia/pull/22150) | Fix part of #18973: Enable solution tab for multiple choice input interaction | Enabling the solution tab for the Multiple Choice Input interaction. |
|4. | [#22396](https://github.com/oppia/oppia/pull/22396) | add domain object and validate() method for ExplorationRightsModel  | Creating a domain object and validate() method for the ExplorationRightsModel, and refactoring the codebase so that the storage model is only accessed in the get and save methods in the service file, with the corresponding domain object used elsewhere. |

---

> ✨ For more details on each PR, please visit the linked pull request on GitHub.
