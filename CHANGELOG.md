# Changelog

All notable changes to the ontology are documented here.
The format follows Keep a Changelog and the vocabulary uses semantic versioning.

## [2.0.0] - 2026-09-29

### Added
- **Rooftops and buildings:** seven activation types (blue, green, yellow, red, purple, orange and gray), defined by 10 rooftop functions, and building attributes such as construction era, material, height, location and primary use. The construction era is inferred from the construction year.
- **Urban context:** districts classified by function and density, and regions (Brussels, Dublin, Île-de-France, Mannheim, Mechelen and Rotterdam).
- **Owners:** 11 owner types, aligned with `foaf:Person` and `org:Organization`.
- **Urban challenges:** 47 challenges grouped into 10 themes, including climate adaptation, affordable housing, decarbonising energy systems, mobility and governance.
- **Incentives:** 56 incentive instrument types, classified by nature, function, funding source, allocation mechanism, obligation attachment and project stage, plus 12 defined classes computed from these facets.
- **Weighted associations:** `Rooftop_Challenge_Association`, `Owner_Rooftop_Association` and `Incentive_Owner_Association`, each carrying a degree between 0 and 1 (`has_degree`) and optionally a region (`defined_for_region`).

In total: 216 classes, 36 object properties, 3 data properties and 63 named individuals.
