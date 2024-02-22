#### Whats Improved
- Added `Version` as a configuration parameter.
- Added `Update Allow or Block List` action.
- Added `Decode Behaviour File String` parameter to `Get Job Behaviour` action.

#### Whats Fixed
- Fixed a bug where `File > FortiSandbox > Enrichment` playbook failed if indicator doesn't have a file.
- Fixed a bug where `URL > FortiSandbox > Enrichment` playbook failing with error message as "Invalid params provided :: Parameters JSON Data have either blank value or not provided Connector :: cyops_utilitiesV3.2.6" 
- Fixed a bug where `Submit File` action failed if file IRI is provided as input in Indicator ID or Attachment IRI parameter.