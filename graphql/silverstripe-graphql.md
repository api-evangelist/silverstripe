# SilverStripe GraphQL API

SilverStripe CMS provides a GraphQL API via the optional `silverstripe/graphql` module. The schema is code-generated at build time from DataObject models configured in YAML. Types, queries, and mutations are derived automatically from SilverStripe DataObject classes (SiteTree, Page, File, Image, Member, Group, and custom models). The GraphQL module ships with CMS 6 as an optional feature and must be activated and built before use.

**Endpoint:** `https://yoursite.com/graphql` (configurable; default `graphql` path)

**Documentation:** https://docs.silverstripe.org/en/6/optional_features/graphql/

**Module Source:** https://github.com/silverstripe/silverstripe-graphql

## References

- Documentation: https://docs.silverstripe.org/en/6/optional_features/graphql/
- Working with DataObjects: https://docs.silverstripe.org/en/6/optional_features/graphql/working_with_dataobjects/
- Security & Authentication: https://docs.silverstripe.org/en/6/optional_features/graphql/security_and_best_practices/authentication/
- GitHub (graphql module): https://github.com/silverstripe/silverstripe-graphql
- GitHub (CMS models): https://github.com/silverstripe/silverstripe-cms
- GitHub (assets module): https://github.com/silverstripe/silverstripe-assets

## Notes

- Schema is generated at deploy time via `dev/graphql/build` or `sake dev/graphql/build`.
- All exposed types, queries, and mutations depend on YAML configuration. The SDL in `silverstripe-schema.graphql` documents the core built-in types and the default generated operations.
- Authentication uses CMS Member sessions (default) or HTTP Basic Auth (`Authorization: Basic <base64>`).
- Versioned content adds `stage` and `archiveDate` arguments to read queries when the Versioned extension is applied.
- Pagination follows the Relay connection pattern: `nodes`, `edges`, and `pageInfo` with `hasNextPage`, `hasPreviousPage`, `totalCount`.
- Filter operators: `eq`, `ne`, `contains`, `gt`, `lt`, `gte`, `lte`, `in`, `startswith`, `endswith`.
