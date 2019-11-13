0.10.0
-----------
**Diff**
- https://github.com/sellect/ups-ruby/compare/v0.10.0rc0...v0.10.0

**Updates**
- PR #6 - Support Multiple Reference Numbers
  - UPS stopped displaying the package description on shipping/return labels
    but they allow multiple reference numbers at the package level or the shipment level
    - "Shipment Level Reference Numbers are only allowed for shipments that are not US to US (origin\destination) or PR to PR (origin\destination)."
    - "Package Level Reference Numbers are only allowed for shipments that are US to US (origin\destination) or PR to PR (origin\destination)."

**Upgrade Notes/Breaking Changes**
- PR #6 - Support Multiple Reference Numbers
  - `ShipConfirmBuilder` method `add_reference_number` is now
    `add_reference_numbers`
  - see usage notes in README
    - https://github.com/sellect/ups-ruby/blob/0-10-stable/README.md#usage-note-reference-numbers

0.10.0rc0
-----------
Initial release of `0-10-stable` built at `v0.9.8`

**Diff**
- https://github.com/sellect/ups-ruby/compare/v0.9.8...v0.10.0rc0

0.9.8
-----------
**Diff**
- https://github.com/sellect/ups-ruby/compare/v0.9.7...v0.9.8

**Updates**
- PR #2 - update postal_code method to allow for empty postal code
  - in the case of countries like Ireland that do not require postal code
