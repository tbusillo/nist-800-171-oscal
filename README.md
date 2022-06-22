# NIST SP 800-171 rev.2 in OSCAL (unofficial)

The [Open Security Controls Assessment Language](https://pages.nist.gov/OSCAL/) (OSCAL) is a NIST/US Government effort to create, "machine-readable representations of control catalogs, control baselines, system security plans, and assessment plans and results". NIST has done some incredible work thus far, but their efforts have understandably been concentrated on baselines/catalogs for safeguarding Federal information systems (e.g., NIST 800-53 rev4/5).

This project attempts to translate NIST SP 800-171 revision 2 into OSCAL's format for control catalogs. Right now the baseline is only in JSON, but other adaptations (e.g., yaml) may be added in the future, but PRs are always welcome! 

In addition to the baseline itself, many of the sections (e.g., references, assessment objectives, etc.) have been isolated/normalized/cleaned up and are also provided in various JSON files. 