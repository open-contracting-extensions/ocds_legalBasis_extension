# Legal basis

Adds properties in Tender with information on the legal basis of the procedure.

## Legal context

In the European Union, this extension's fields correspond to [eForms BT-01 (Procedure Legal Basis) and BT-09 (Cross Border Law)](https://github.com/eForms/eForms). See [OCDS for the European Union](http://standard.open-contracting.org/profiles/eu/master/en/) for the correspondences to Tenders Electronic Daily (TED).

## Example

```json
{
  "tender": {
    "crossBorderLaw": "Italian procurement legislation",
    "legalBasis": {
      "id": "32014L0025",
      "scheme": "CELEX"
    }
  }
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

## Changelog

This extension was originally discussed as part of the [OCDS for EU profile](https://github.com/open-contracting-extensions/european-union/issues) and in [pull requests](https://github.com/open-contracting-extensions/ocds_contractTerms_extension/pulls?q=is%3Apr+is%3Aclosed).
