# 1 Enterprise Systems

`\1 Enterprise Systems`

* [Study Case](../README.md)
  * [**1 Enterprise Systems**](../1%20Enterprise%20Systems/README.md)
    * [API Application](../1%20Enterprise%20Systems/API%20Application/README.md)
    * [Single Page Application](../1%20Enterprise%20Systems/Single%20Page%20Application/README.md)
      * [Dynamic Diagram](../1%20Enterprise%20Systems/Single%20Page%20Application/Dynamic%20Diagram/README.md)
      * [Extended Docs](../1%20Enterprise%20Systems/Single%20Page%20Application/Extended%20Docs/README.md)

---

[Study Case (up)](../README.md)

- [API Application](../1%20Enterprise%20Systems/API%20Application/README.md)

- [Single Page Application](../1%20Enterprise%20Systems/Single%20Page%20Application/README.md)

---

![diagram](https://www.plantuml.com/plantuml/svg/0/ZLJ1Jjj04BqZyG_JLAg2r2O7Ukg90A60KZ0u4UefcjX3icAzw-xi9ash_djdrx45X4hDnV7kctbltipuX3qw7ofzUF1EcKA7ac3bVSrVXaE7cy5I-LLO12PNMEF9-45Xgo6MJg5Pwr27uTddJvb6usVV9aEDdjZBqVnCqAWCkK6TaXyUJ4RVRsVJ-SFLz78-6NyTtvptZ-9vHewjwMDPAVCHUgFuX9aGzk8RH6gmZ-1N1BnbJvNyHGyhP403AKonT-Yj0sSrzIHhde3pyK_Vv-EOvY67_3WbhF2NDP2hgjO4kGJXKfxarggWmQlOSY4H-TqatJU2xabgLDQWXdFq2AV8Us7yWrlEktoVz2vG-2Vbvib9m8DrJmrV_gnaHsprMcmeLbG6JINKpXR4J9pIT8bERJ0bkcsVef2nzCtLJd5hOEy8VXyUWFowBlKt66bf0QEwrgf8DKR-i_VYSWc3c_4KBXnMj15fyUASj19Fk6cCbu02TYEI8kAnr6kT1svA1LPcAVNNqN7iM9BqbsAuZcho1fv5-2jLrxX6Bfog6wwHMGQDxZgPdJcxLYN9T6ZzXWg6ns2AfeNARy7RD68CQuKHhXnin8Q5inivVaCSrYgsDBlwRwiwHQ_yU2aayYDSvxStmylfD0DXs7KryilSfHurrhJcj-hYRRffnCdsSBAfJPRl0TDQjBYBQVOSa9AasRydB1a-mCOfMMpnQW_Mp7eM5bhn2YePHcbNqlqdIa-uPhFJXBMCdQXdWAQqXDXTf6Le6CH_3XMzOEWWIUkiBkNh0zwHFBhLs5buGgPCtw6_)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.