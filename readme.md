## MRN Revisionable for COINS

### Changes

#### Schema
All calls to `getTable()` are prefixed with a call to `getSchemaName`. This allows each schema to have its own revisions table.

#### Removal of `updated_at`
This colummn seems unnecessary.