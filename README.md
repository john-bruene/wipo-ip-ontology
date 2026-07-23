# WIPO IP Ontology (draft)

Draft OWL/RDFS ontology for comparing national intellectual property laws
against WIPO treaty minimum standards. Work in progress, part of a PhD
project (Law, Science and Technology, University of Bologna) on
neuro-symbolic AI for IP law compliance monitoring, supervised by
Prof. Monica Palmirani.

**Status: draft, not a finished or validated model.** Built following the
MeLOn methodology, reusing FRBR (`frbr:`) for the document layer and the
LegalRuleML metamodel (`lrmlmm:`) for the statement layer.

## Files

- `ontology_draft.ttl` — schema (TBox): classes and properties only, no
  country-specific data.
- `examples.ttl` — worked examples (ABox): Ireland, India, Kenya, used to
  validate the schema against real statute text.
- `docs/` — generated documentation (Widoco: reference sections + embedded
  WebVOWL visualization). Enable via Settings > Pages > Deploy from branch
  > `main` / `docs` for a browsable version.

## Reused vocabularies

- FRBR Core (`http://purl.org/vocab/frbr/core#`)
- LegalRuleML Metamodel (`http://docs.oasis-open.org/legalruleml/ns/v1.0/metamodel#`)
- Right/exception vocabulary cross-checked against Delgado et al., IPROnto
  (JURIX 2003) and García & Gil, Copyright Ontology (JURIX 2008)

## Status / license

Draft, unpublished research. Not for citation or reuse without permission.
