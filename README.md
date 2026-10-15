# IFDD - Integration of Federated Data Domains

<img src="https://github.com/ifdd-de/overview/blob/86e82f11f71d806bffa829e1b3d24abfb7a3ac96/brand/assets/ifdd-monogram-light-512.png" alt="IFDD" width="96" align="right">

Most integration projects start by building a place where all the data is supposed
to end up. IFDD starts from the opposite assumption: **the data stays where it is
produced, and integration happens through shared meaning instead of shared storage.**

---

## The idea in three sentences

- **Domains keep their data.** Every domain — a team, a system, a person — publishes
  its own records from its own endpoint and stays responsible for them.
- **A shared schema replaces a shared system.** Records are validated against a
  published LinkML schema and served as JSON-LD, so a YAML file, a Django service and
  an ERP system can take part in the same federation.
- **Identity is separate from location.** Identifiers are permanent addresses; hosts
  are operational addresses that may change. That separation is what makes the whole
  federation survive reorganisation.
