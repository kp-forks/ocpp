# Change log

## 2.1.0 (2025-07-14)
* [#701](https://github.com/mobilityhouse/ocpp/pull/701) Bump jinja2 from 3.1.4 to 3.1.5 by @dependabot
* [#703](https://github.com/mobilityhouse/ocpp/pull/703) chore(deps): apply minor and patch updates by @jerome-benoit
* [#710](https://github.com/mobilityhouse/ocpp/pull/710) Updating examples by @a-alak
* [#711](https://github.com/mobilityhouse/ocpp/pull/711) bugfix: Update status field for UpdateFirmware in OCPI 2.2.1 call_result by @a-alak
* [#725](https://github.com/mobilityhouse/ocpp/pull/725) docs: Revise README for clarity and keep minimal data by @jainmohit2001
* [#726](https://github.com/mobilityhouse/ocpp/pull/726) docs: Added new sphinx docs by @jainmohit2001
* [#727](https://github.com/mobilityhouse/ocpp/pull/727) fix: Add requirements for Sphinx documentation build by @jainmohit2001
* [#728](https://github.com/mobilityhouse/ocpp/pull/728) Feat/ocpp21 by @mlitre
* [#734](https://github.com/mobilityhouse/ocpp/pull/734) Fix build-backend setting by @hikinggrass

## 2.1.0-rc.1 (2025-07-02)
* [#701](https://github.com/mobilityhouse/ocpp/pull/701) Bump jinja2 from 3.1.4 to 3.1.5 by @dependabot
* [#703](https://github.com/mobilityhouse/ocpp/pull/703) chore(deps): apply minor and patch updates by @jerome-benoit
* [#710](https://github.com/mobilityhouse/ocpp/pull/710) Updating examples by @a-alak
* [#711](https://github.com/mobilityhouse/ocpp/pull/711) bugfix: Update status field for UpdateFirmware in OCPI 2.2.1 call_result by @a-alak
* [#725](https://github.com/mobilityhouse/ocpp/pull/725) docs: Revise README for clarity and keep minimal data by @jainmohit2001
* [#726](https://github.com/mobilityhouse/ocpp/pull/726) docs: Added new sphinx docs by @jainmohit2001
* [#727](https://github.com/mobilityhouse/ocpp/pull/727) fix: Add requirements for Sphinx documentation build by @jainmohit2001
* [#728](https://github.com/mobilityhouse/ocpp/pull/728) Feat/ocpp21 by @mlitre
* [#734](https://github.com/mobilityhouse/ocpp/pull/734) Fix build-backend setting by @hikinggrass

## 2.0.0 (2024-12-09)
- [#621](https://github.com/mobilityhouse/ocpp/pull/621) Bump black from 22.12.0 to 24.3.0 by @dependabot
- [#693](https://github.com/mobilityhouse/ocpp/pull/693) ci: ensure the matching poetry version is used by @jerome-benoit
- [#687](https://github.com/mobilityhouse/ocpp/pull/687) Finalize hand over to new maintainers. by @OrangeTux
- [#681](https://github.com/mobilityhouse/ocpp/pull/681) chore: Add code of conduct, contributing, security and support docs. by @ajmirsky
- [#680](https://github.com/mobilityhouse/ocpp/pull/680) feat: Matching OCPP 2.0.1 payload types to OCPP 2.0.1 json schema by @ajmirsky
- [#648](https://github.com/mobilityhouse/ocpp/pull/648) Use dataclasses for ChargingProfile usage by @jerome-benoit
- [#694](https://github.com/mobilityhouse/ocpp/pull/694) breaking change: remove deprecated Action items and update docs by @drc38
- [#690](https://github.com/mobilityhouse/ocpp/pull/690) test: Unit test for RemoteStartTransaction nested dataclass by @ajmirsky
- [#698](https://github.com/mobilityhouse/ocpp/pull/698) chore: Updated imports for v16 datatypes, call and call_result files by @jainmohit2001
- [#699](https://github.com/mobilityhouse/ocpp/pull/699) feat: Remove deprecated dataclass by @jainmohit2001
- [#665](https://github.com/mobilityhouse/ocpp/pull/665) chore: Updated Python setup action to version v5 by @jainmohit2001
- [#663](https://github.com/mobilityhouse/ocpp/pull/663) bugfix: Changed total_cost type from Optional[int] to Optional[float] by @jainmohit2001
- [#667](https://github.com/mobilityhouse/ocpp/pull/667) feat: Added optional logger param to ChargePoint class by @jainmohit2001
- [#686](https://github.com/mobilityhouse/ocpp/pull/666) bugfix: Handling UnicodeDecodeError in unpack function by @jainmohit2001
- [#668](https://github.com/mobilityhouse/ocpp/pull/668) chore: Update CODEOWNERS by @jainmohit2001
- [#652](https://github.com/mobilityhouse/ocpp/pull/652) add executor to validate_payload by @drc38
- [#629](https://github.com/mobilityhouse/ocpp/pull/629) fix typo for InternalError in exceptions.py by @hhuseyinpay
- [#679](https://github.com/mobilityhouse/ocpp/pull/679) Add issue templates by @mdwcrft
- [#686](https://github.com/mobilityhouse/ocpp/pull/686) Update readme - ocpp 2 edition 3 is supported by @wafa-yah
- [#678](https://github.com/mobilityhouse/ocpp/pull/678) Disable threads if messages.ASYNC_VALIDATION = False by @astrand
- [#685](https://github.com/mobilityhouse/ocpp/pull/685) Test with python 3.13 by @drc38
- [#673](https://github.com/mobilityhouse/ocpp/pull/673) chore: Added inactive issue workflow by @jainmohit2001
- [#315](https://github.com/mobilityhouse/ocpp/pull/315) Allow to skip schema validation in `ChargePoint.call()`. Thanks [@esiebert](https://github.com/esiebert)!
- [#642](https://github.com/mobilityhouse/ocpp/pull/642) Fix serializing of "ocpp_csms_url".
- [#631](https://github.com/mobilityhouse/ocpp/pull/631) Fix publishing to Pypi.
- [#573](https://github.com/mobilityhouse/ocpp/issues/635) Fix serialization of types that contain a collection of items.


## 2.0.0-rc.4 (2025-01-02)
- [#621](https://github.com/mobilityhouse/ocpp/pull/621) Bump black from 22.12.0 to 24.3.0 by @dependabot
- [#693](https://github.com/mobilityhouse/ocpp/pull/693) ci: ensure the matching poetry version is used by @jerome-benoit
- [#687](https://github.com/mobilityhouse/ocpp/pull/687) Finalize hand over to new maintainers. by @OrangeTux
- [#681](https://github.com/mobilityhouse/ocpp/pull/681) chore: Add code of conduct, contributing, security and support docs. by @ajmirsky
- [#680](https://github.com/mobilityhouse/ocpp/pull/680) feat: Matching OCPP 2.0.1 payload types to OCPP 2.0.1 json schema by @ajmirsky
- [#648](https://github.com/mobilityhouse/ocpp/pull/648) Use dataclasses for ChargingProfile usage by @jerome-benoit
- [#694](https://github.com/mobilityhouse/ocpp/pull/694) breaking change: remove deprecated Action items and update docs by @drc38
- [#690](https://github.com/mobilityhouse/ocpp/pull/690) test: Unit test for RemoteStartTransaction nested dataclass by @ajmirsky
- [#698](https://github.com/mobilityhouse/ocpp/pull/698) chore: Updated imports for v16 datatypes, call and call_result files by @jainmohit2001
- [#699](https://github.com/mobilityhouse/ocpp/pull/699) feat: Remove deprecated dataclass by @jainmohit2001

## 2.0.0-rc.3 (2024-12-09)
- [#665](https://github.com/mobilityhouse/ocpp/pull/665) chore: Updated Python setup action to version v5 by @jainmohit2001
- [#663](https://github.com/mobilityhouse/ocpp/pull/663) bugfix: Changed total_cost type from Optional[int] to Optional[float] by @jainmohit2001
- [#667](https://github.com/mobilityhouse/ocpp/pull/667) feat: Added optional logger param to ChargePoint class by @jainmohit2001
- [#686](https://github.com/mobilityhouse/ocpp/pull/666) bugfix: Handling UnicodeDecodeError in unpack function by @jainmohit2001
- [#668](https://github.com/mobilityhouse/ocpp/pull/668) chore: Update CODEOWNERS by @jainmohit2001
- [#652](https://github.com/mobilityhouse/ocpp/pull/652) add executor to validate_payload by @drc38
- [#629](https://github.com/mobilityhouse/ocpp/pull/629) fix typo for InternalError in exceptions.py by @hhuseyinpay
- [#679](https://github.com/mobilityhouse/ocpp/pull/679) Add issue templates by @mdwcrft
- [#686](https://github.com/mobilityhouse/ocpp/pull/686) Update readme - ocpp 2 edition 3 is supported by @wafa-yah
- [#678](https://github.com/mobilityhouse/ocpp/pull/678) Disable threads if messages.ASYNC_VALIDATION = False by @astrand
- [#685](https://github.com/mobilityhouse/ocpp/pull/685) Test with python 3.13 by @drc38
- [#673](https://github.com/mobilityhouse/ocpp/pull/673) chore: Added inactive issue workflow by @jainmohit2001

## 2.0.0-rc.2 (2024-06-18)

- [#315](https://github.com/mobilityhouse/ocpp/pull/315) Allow to skip schema validation in `ChargePoint.call()`. Thanks [@esiebert](https://github.com/esiebert)!

## 2.0.0-rc.1 (2024-06-01)

## BREAKING ##
- [#642](https://github.com/mobilityhouse/ocpp/pull/642) Fix serializing of "ocpp_csms_url".

## 2.0.0-rc.0 (2024-05-22)

- [#631](https://github.com/mobilityhouse/ocpp/pull/631) Fix publishing to Pypi.

## BREAKING ##
- [#573](https://github.com/mobilityhouse/ocpp/issues/635) Fix serialization of types that contain a collection of items.

## 1.0.0 (2024-04-05)

- [#573](https://github.com/mobilityhouse/ocpp/issues/573) Introduce Experimental Module For v2.1
- [#547](https://github.com/mobilityhouse/ocpp/pull/547) Feat: Handle recursively serializing a dataclasses as a dictionary Thanks [@MacDue](https://github.com/MacDue)
- [#601](https://github.com/mobilityhouse/ocpp/issues/601) Fix case conversion for soc in non "State of Charge" context
- [#523](https://github.com/mobilityhouse/ocpp/issues/523) The serialisation of soc to SoC should not occur in camel case if it is existing at the beginning of a field
- [#515](https://github.com/mobilityhouse/ocpp/issues/515) Update Readthedocs configuration
- [#602](https://github.com/mobilityhouse/ocpp/issues/602) Correct v2g serialisation/deserialisation
- [#557](https://github.com/mobilityhouse/ocpp/issues/557) OCPP 2.0.1 Wrong data type in CostUpdated total_cost
- [#564](https://github.com/mobilityhouse/ocpp/issues/564) Add support For Python 3.11 and 3.12
- [#583](https://github.com/mobilityhouse/ocpp/issues/583) OCPP v1.6/v2.0.1 deprecate dataclasses from calls and call results with the suffix 'Payload'
- [#590](https://github.com/mobilityhouse/ocpp/pull/336) snake_to_camel_case url to URL does not get converted correctly
- [#591](https://github.com/mobilityhouse/ocpp/issues/591) Camel_to_snake_case doesn't handle v2x correctly
- [#593](https://github.com/mobilityhouse/ocpp/issues/593) Update tests to use Call and CallResult without the suffix Payload
- [#435](https://github.com/mobilityhouse/ocpp/issues/435) Typo in CostUpdated Action
- [#577](https://github.com/mobilityhouse/ocpp/issues/577) v2.0.1 AttributeType Enum Corrections
- [#340](https://github.com/mobilityhouse/ocpp/issues/340) 2.0.1 dataclasses have a incorrect types that don't match carnality
- [#519](https://github.com/mobilityhouse/ocpp/issues/519) Typo in v201.enums.StatusInfoReasonType.invaild_schedule
- [#510](https://github.com/mobilityhouse/ocpp/issues/510) v2.0.1 UnitOfMeasureType - Enums missing and update docstring to allow use for variableCharacteristics
- [#508](https://github.com/mobilityhouse/ocpp/issues/508) Exception - OccurrenceConstraintViolationError doc string correction
- [#613](https://github.com/mobilityhouse/ocpp/issues/613) Typo correction in v201.enums.StatusInfoReasonType.value_too_hight -> value_too_high
- [#622](https://github.com/mobilityhouse/ocpp/issues/622) Fix typo in OCPP 2.0.1 enum Action.cost_updated

## 1.0.0-rc.1 (2024-02-14)

- [#573](https://github.com/mobilityhouse/ocpp/issues/573) Introduce Experimental Module For v2.1
- [#547](https://github.com/mobilityhouse/ocpp/pull/547) Feat: Handle recursively serializing a dataclasses as a dictionary Thanks [@MacDue](https://github.com/MacDue)
- [#601](https://github.com/mobilityhouse/ocpp/issues/601) Fix case conversion for soc in non "State of Charge" context
- [#523](https://github.com/mobilityhouse/ocpp/issues/523) The serialisation of soc to SoC should not occur in camel case if it is existing at the beginning of a field
- [#515](https://github.com/mobilityhouse/ocpp/issues/515) Update Readthedocs configuration
- [#602](https://github.com/mobilityhouse/ocpp/issues/602) Correct v2g serialisation/deserialisation
- [#557](https://github.com/mobilityhouse/ocpp/issues/557) OCPP 2.0.1 Wrong data type in CostUpdated total_cost
- [#564](https://github.com/mobilityhouse/ocpp/issues/564) Add support For Python 3.11 and 3.12
- [#583](https://github.com/mobilityhouse/ocpp/issues/583) OCPP v1.6/v2.0.1 deprecate dataclasses from calls and call results with the suffix 'Payload'
- [#590](https://github.com/mobilityhouse/ocpp/pull/336) snake_to_camel_case url to URL does not get converted correctly
- [#591](https://github.com/mobilityhouse/ocpp/issues/591) Camel_to_snake_case doesn't handle v2x correctly
- [#593](https://github.com/mobilityhouse/ocpp/issues/593) Update tests to use Call and CallResult without the suffix Payload
- [#435](https://github.com/mobilityhouse/ocpp/issues/435) Typo in CostUpdated Action
- [#577](https://github.com/mobilityhouse/ocpp/issues/577) v2.0.1 AttributeType Enum Corrections
- [#340](https://github.com/mobilityhouse/ocpp/issues/340) 2.0.1 dataclasses have a incorrect types that don't match carnality
- [#519](https://github.com/mobilityhouse/ocpp/issues/519) Typo in v201.enums.StatusInfoReasonType.invaild_schedule
- [#510](https://github.com/mobilityhouse/ocpp/issues/510) v2.0.1 UnitOfMeasureType - Enums missing and update docstring to allow use for variableCharacteristics
- [#508](https://github.com/mobilityhouse/ocpp/issues/508) Exception - OccurrenceConstraintViolationError doc string correction

## DEPRECATED ##
- [#599](https://github.com/mobilityhouse/ocpp/issues/599) v1.6 Action Enum members corrected IMPORTANT SEE UPGRADE PATH [#599](https://github.com/mobilityhouse/ocpp/issues/599)
- [#579](https://github.com/mobilityhouse/ocpp/issues/579) v2.0.1 Action enums corrected - IMPORTANT SEE UPGRADE PATH [#579](https://github.com/mobilityhouse/ocpp/issues/579)

## BREAKING ##
- [#574](https://github.com/mobilityhouse/ocpp/issues/574) Remove v1.6 deprecated enum members - IMPORTANT see upgrade path [#574](https://github.com/mobilityhouse/ocpp/issues/574)
- [#498](https://github.com/mobilityhouse/ocpp/issues/498) Remove support for OCPP 2.0 - IMPORTANT SEE UPGRADE PATH [#498](https://github.com/mobilityhouse/ocpp/issues/498)

## 0.26.0 (2024-01-17)

- [#544](https://github.com/mobilityhouse/ocpp/issues/544) ocpp/charge_point.py - Pass `Call.unique_id` to the `on` and `after` routing handlers.
- [#559](https://github.com/mobilityhouse/ocpp/issues/559) Update project dependencies as of 22-12-2023
- [#447](https://github.com/mobilityhouse/ocpp/issues/447) v16, v201 - Make formatting of enums in py3.11 consistent with earlier Python versions
- [#421](https://github.com/mobilityhouse/ocpp/issues/421) Type of v16.datatypes.SampledValue.context is incorrect 

## 0.25.0 (2024-01-08)

- [#366](https://github.com/mobilityhouse/ocpp/issues/366) Fix type hint of OCPP 1.6 ChangeConfiguration.value
- [#431](https://github.com/mobilityhouse/ocpp/issues/431) Attributes with 'v2x' are serialized as 'V2x', but should be serialized as 'V2X'
- [#554](https://github.com/mobilityhouse/ocpp/issues/554) OCPP 2.0.1 Edition 2 Errata 2023-12 document added
- [#548](https://github.com/mobilityhouse/ocpp/issues/548) OCPP 2.0.1 MessageInfoType attribute name correction
- [#300](https://github.com/mobilityhouse/ocpp/issues/300) OCPP 2.0.1 add reference components and variables
- [#518](https://github.com/mobilityhouse/ocpp/issues/518) OCPP 2.0.1 add additional reason codes from v1.3

## 0.24.0 (2023-12-07)


- [#539](https://github.com/mobilityhouse/ocpp/issues/539) feat: Add ChargePoint._handle_call return value. Thanks [@wafa-yah](https://github.com/wafa-yah)
- [#266](https://github.com/mobilityhouse/ocpp/issues/266) fix: Central System documentation link.
- [#516](https://github.com/mobilityhouse/ocpp/issues/516) OCPP 2.0.1 add additional security events from v1.3.
- [#537](https://github.com/mobilityhouse/ocpp/pull/537) Fix DataTransfer data types. Thanks [@mdwcrft](https://github.com/mdwcrft)

## 0.23.0 (2023-11-30)

- [#531] Feat: Add 1.6 security extension datatypes. Thanks [@proelke](https://github.com/proelke)
- [#528](https://github.com/mobilityhouse/ocpp/issues/528) v2.0.1 CertificateHashDataChainType childCertificateHashData requires the default of None.
- [#510](https://github.com/mobilityhouse/ocpp/issues/510) v2.0.1 UnitOfMeasureType - Enums missing and update docstring to allow use for variableCharacteristics.
- [#508](https://github.com/mobilityhouse/ocpp/issues/508) Exception - OccurrenceConstraintViolationError doc string correction.
- [#511](https://github.com/mobilityhouse/ocpp/issues/511) 2.0.1 Units of Measure update to match Appendix 2. Standardized Units Of Measure

## 0.22.0 (2023-11-03)

- [#493](https://github.com/mobilityhouse/ocpp/issues/493) Reduce use of NotSupportedError in favor of NotImplementedError. Thanks [drc38](@https://github.com/drc38).
- [#278](https://github.com/mobilityhouse/ocpp/pull/278) Fix types for attributes of OCPP 1.6's type `IdTagInfo`. Thanks [@chan-vince](https://github.com/chan-vince)
- [#504](https://github.com/mobilityhouse/ocpp/pull/504) Add missing tech_info attribute to v2.0.1 EventDataType. Thanks [@LokiHokie](https://github.com/LokiHokie)
- [#381](https://github.com/mobilityhouse/ocpp/issues/381) Add FormationError and OccurrenceConstraintViolationError.
- [#373](https://github.com/mobilityhouse/ocpp/issues/373) v201.datatypes.ChargingNeedsType.request_energy_transfer is mistyped
- [#207](https://github.com/mobilityhouse/ocpp/issues/207) v16/schemas/StopTransaction.json missing "Hertz"

## 0.21.0 (2023-10-19) 

- [#492] Minor fixes _handle_call doc string  - Thanks @drc38
- [#485](https://github.com/mobilityhouse/ocpp/issues/485) Update documents for 2.0.1 to lastest; removed 2.0 docs
- [#412](https://github.com/mobilityhouse/ocpp/issues/412) Add default value to 1.6 AuthorizationData datatype, id_tag_info
- [#141](https://github.com/mobilityhouse/ocpp/issues/141) Add to docs OCPP 1.6 Security White Paper Ed 2

## 0.20.0 (2023-10-10) 

- [#471](https://github.com/mobilityhouse/ocpp/issues/471) Fix `ImportError` when using jsonschema 4.19.0 or higher.
- Fix import error in v201 example. Thanks [@Shiwei-Shen](https://github.com/Shiwei-Shen)!
- Update Poetry to 1.5.1 in CI.

## 0.19.0 (2023-04-26)

- [#438] feat: add optional param for passing an unique_id to call method. Thanks [@santiagosalamandri](https://github.com/santiagosalamandri)
- [#420] fix: type hint child_certificate_hash_data type. Thanks [@santiagosalamandri](https://github.com/santiagosalamandri)

## 0.18.0 (2023-03-22)

- [#434](https://github.com/mobilityhouse/ocpp/issues/407) Add custom_data attribute to payload-related dataclasses. [@will-fs](https://github.com/will-fs)

## 0.17.0 (2023-01-04)

- [#413](https://github.com/mobilityhouse/ocpp/issues/407) Add enum for OCPP 1.6 ConfigurationKey. Thansks [@isabelle-tmh](https://github.com/isabelle-tmh) and [@lbbrhzn](https://github.com/lbbrhzn)
- [#407](https://github.com/mobilityhouse/ocpp/issues/407) Fix build that publishes release to pypi.

## 0.16.0 (2023-01-04)

- [#401](https://github.com/mobilityhouse/ocpp/issues/401) Fix serialization error when receiving invalid inbound Call.
- [#402](https://github.com/mobilityhouse/ocpp/issues/402) Update development dependencies.
- [#382](https://github.com/mobilityhouse/ocpp/issues/382) Added missing ' (single quote) to error message. Thanks [@BIGduzy](https://github.com/BIGduzy)
- [#374](https://github.com/mobilityhouse/ocpp/issues/374) Run tests in CI build that builds package and releases it to Pypi. Thanks [@aysauchoa](https://github.com/aysauchoa)
- [#384](https://github.com/mobilityhouse/ocpp/issues/384) Include OCPP message that causes OCPPError. Thanks [@klimaschkas](https://github.com/klimaschkas)
- [#385](https://github.com/mobilityhouse/ocpp/issues/385) Integrate black and isort. Thanks [@proelke](https://github.com/proelke)
- [#331](https://github.com/mobilityhouse/ocpp/issues/331) Add missing variant to OCPP 2.0.1 enum DataType.password_string. Thanks [@mdwcrft](https://github.com/mdwcrft)
- [#332](https://github.com/mobilityhouse/ocpp/issues/332) Update OCPP 2.0.1 ConnectorType enum variants introduced in errata. Thanks [@mdwcrft](https://github.com/mdwcrft)
- [#379](https://github.com/mobilityhouse/ocpp/issues/379) Fix typo in OCPP 2.0.1 attribute FirmwareType.retrieve_data. Thanks [@mdwcrft](https://github.com/mdwcrft)
- [#369](https://github.com/mobilityhouse/ocpp/issues/369) Make sure that CI use latest Python 3.10 release. Thanks [@adamchainz](https://github.com/adamchainz)
- [#353](https://github.com/mobilityhouse/ocpp/issues/343) Fix typo in OCPP 2.0.1 enum variant MessageTrigger.sign_v2g_certificate. Thanks [@proelke](https://github.com/proelke)
- [#359](https://github.com/mobilityhouse/ocpp/issues/359) Add enum for OCPP 2.0.1's SecurityEvent. Thanks [@proelke](https://github.com/proelke)

## 0.15.0 (2022-05-11)

- [#306](https://github.com/mobilityhouse/ocpp/issues/306) Fix type hint `ocpp.v201.datatypes.MeterValueType.sampled_value`. Thanks [@Shadowsith](https://github.com/Shadowsith)
- [#328](https://github.com/mobilityhouse/ocpp/issues/324) Add missing attribute `ocpp.v201.dataypes.SampledValueType.measurand`.Thanks [@maurerle](https://github.com/maurerle)
- [#335](https://github.com/mobilityhouse/ocpp/issues/335) Improve Exception handling and CallError responses. Thanks [@proelke](https://github.com/proelke)
- [#316](https://github.com/mobilityhouse/ocpp/issues/333) Drop Python 3.6 support and update jsonschema to 4.4. Thanks [@laysauchoa](https://github.com/laysauchoa)

## 0.14.1 (2022-03-08)

- [#316](https://github.com/mobilityhouse/ocpp/issues/316) Fix definition of `GetVariableResultType.variable`. Thanks [@HugoJP1](https://github.com/HugoJP1)

## 0.14.0 (2022-03-03)

- [#312](https://github.com/mobilityhouse/ocpp/issues/312) Raise `TypeConstraintViolationError` instead of `ValidationError` when value exceeds length limit. Thanks [@tmh-grunwald-markus](https://github.com/tmh-grunwald-markus)

## 0.13.1 (2022-02-02)

The tag 0.13.0 was created, but the build to publish the release failed to pypi failed.
Therefore, 0.13.0 is not listed in this CHANGELOG.md

- [#293](https://github.com/mobilityhouse/ocpp/issues/293) Add missing attributes to `GetVariableResultType`. Thanks [@proelke](https://github.com/proelke)
- [#294](https://github.com/mobilityhouse/ocpp/issues/294) Improved error handling when schema validation fails. Thanks [@joaomariord](https://github.com/joaomariord)

## 0.12.1 (2022-01-17)

- [#289](https://github.com/mobilityhouse/ocpp/issues/289) Fix bug in `remove_nones()` when processing `str`.

## 0.12.0 (2022-01-12)

- [#272](https://github.com/mobilityhouse/ocpp/issues/272) Improve `remove_nones` so it handles nested data structures better. Thanks [@proelke](https://github.com/proelke)
- [#287](https://github.com/mobilityhouse/ocpp/issues/287) Add enum StatusCodeInfoType. Thanks [@proelke](https://github.com/proelke)
- [#288](https://github.com/mobilityhouse/ocpp/issues/288) Fixed typos in attributes. Thanks [@mdwcrft](https://github.com/mdwcrft)

## 0.11.0 (2021-11-26)

- [#250](https://github.com/mobilityhouse/ocpp/issues/250) Add v1.6 data types
- [#268](https://github.com/mobilityhouse/ocpp/issues/268) Move from CircleCI to Github Actions.
- [#270](https://github.com/mobilityhouse/ocpp/issues/270) Changes badges to reflect move to Github Action

## 0.10.1 (2021-11-18)

- [#252](https://github.com/mobilityhouse/ocpp/issues/252) Fix CI build.
- [#259](https://github.com/mobilityhouse/ocpp/issues/259) Fix typo on `Action.SetMonitoringBase`. Thanks [@shaikhasif15752](https://github.com/shaikhasif15752)

## 0.10.0 (2021-09-16)

- [#249](https://github.com/mobilityhouse/ocpp/issues/249) Remove depreciated function `get_schema_code()`. Thanks [@proelke](https://github.com/proelke)
- [#240](https://github.com/mobilityhouse/ocpp/issues/240) Add OCPP v2.0.1 data types. Thanks [@proelke](https://github.com/proelke)

## 0.9.0 (2021-09-02)

- Fix limit array in meterValue and sampledValue. Thanks [@laysauchoa](https://github.com/laysauchoa)
- [#141](https://github.com/mobilityhouse/ocpp/issues/141) Add security enhancement for OCPP 1.6. Thanks [@villekr](https://github.com/villekr)
- [#217](https://github.com/mobilityhouse/ocpp/issues/217) Fix parsing of floats in GetCompositeSchedule response. Thanks [@laysauchoa](https://github.com/laysauchoa)
- [#223](https://github.com/mobilityhouse/ocpp/issues/223) Fix type DataTransferPayload.status. Thanks [@laysauchoa](https://github.com/laysauchoa)

## 0.8.3 (2021-04-21)

- [#200](https://github.com/mobilityhouse/ocpp/issues/200) Add context to `asyncio.TimeoutError`s raised by `ocpp.ChargePoint.call()`.

## 0.8.2 (2021-04-21)

- [#167](https://github.com/mobilityhouse/ocpp/issues/167) Fix OCPP 2.0.1 call payloads for `RequestStartTransactionPayload` and `RequestStopTransactionPayload`.

## 0.8.1 (2020-11-14)

- [#114](https://github.com/mobilityhouse/ocpp/issues/114) Make casing of `ocpp.v16.enums`'s attributes consistent. Thanks [@tropxy](https://github.com/tropxy)
- [#147](https://github.com/mobilityhouse/ocpp/issues/147) Fix type hint for `ocpp.v16.call.ChangeAvailabilityPayload`. Thanks [@laysauchoa](https://github.com/laysauchoa)
- [#150](https://github.com/mobilityhouse/ocpp/issues/150) Log in to Docker hub to prevent being rate limited.
- [#154](https://github.com/mobilityhouse/ocpp/issues/154) Speed up handling of `Call`s by caching `Draft4Validator` instances.

## 0.8.0 (2020-10-27)

- [#104](https://github.com/mobilityhouse/ocpp/issues/104) Allow `CallError`s to be catched. Thanks [@tmh-azinhal](https://github.com/tmh-azinhal)
- [#142](https://github.com/mobilityhouse/ocpp/issues/142)[#143](https://github.com/mobilityhouse/ocpp/issues/143) Add support for OCPP 2.0.1. Thanks [@tropxy](https://github.com/tropxy)
- [#137](https://github.com/mobilityhouse/ocpp/issues/137) Fix generation route map when using `@property`. Thanks [@fa1k3n](https://github.com/fa1k3n)

## 0.7.2 (2020-10-17)

- [#127](https://github.com/mobilityhouse/ocpp/issues/127) Fix type hints of enums.
- [#130](https://github.com/mobilityhouse/ocpp/issues/130) Fix possible deadlock when using `@after()` handlers.
- [#131](https://github.com/mobilityhouse/ocpp/issues/131) Add CI support for Python 3.9. Thanks [@laysauchoa](https://github.com/laysauchoa)!

## 0.7.1 (2020-09-18)

- [#117](https://github.com/mobilityhouse/ocpp/issues/117) Fix handling of async `@after()` handlers.

## 0.7.0 (2020-09-13)

- [#95](https://github.com/mobilityhouse/ocpp/issues/95) Remove use of deprecated `asyncio.coroutine()`. Thanks [@laysauchoa](https://github.com/laysauchoa)!
- [#105](https://github.com/mobilityhouse/ocpp/issues/105) Implement `__str__()` for all exceptions. Thanks [@laysauchoa](https://github.com/laysauchoa)!
- [#110](https://github.com/mobilityhouse/ocpp/issues/110) Subclass OCPP 1.6 enums from `str` and `enum.Enum`.
- [#113](https://github.com/mobilityhouse/ocpp/issues/113) Use OCPP 1.6 enums as type hints in calls and call results.

## 0.6.4 (2020-03-22)

- [#76](https://github.com/mobilityhouse/ocpp/issues/76) Fix names of 2 OCPP OCPP 2.0 call payloads.

## 0.6.3 (2020-02-26)

- Add links to source and documentation in Pypi. [@adamchainz](https://github.com/adamchainz)

## 0.6.2 (2020-02-21)

- [#71](https://github.com/mobilityhouse/ocpp/issues/71) Add unit Hertz. [@bengarrett1971](https://github.com/bengarrett1971)

## 0.6.1 (2020-02-19)

- [#68](https://github.com/mobilityhouse/ocpp/issues/68) Fix validation of SetChargingProfile

## 0.6.0 (2020-02-10)

- [#63](https://github.com/mobilityhouse/ocpp/issues/63) Remove spaces after separators before sending message
- [#65](https://github.com/mobilityhouse/ocpp/issues/65) `ocpp.ChargePoint.call()` doesn't validate the messages

## 0.5.1 (2019-12-06)

- [#57](https://github.com/mobilityhouse/ocpp/issues/57) Implement errata v4 for OCPP 1.6. Thanks [@darander](https://github.com/darander)

## 0.5.0 (2019-12-03)

- [#54](https://github.com/mobilityhouse/ocpp/issues/54) Add option to `@on()` to skip schema validation

## 0.4.4 (2019-11-21)

- [#43](https://github.com/mobilityhouse/ocpp/issues/43) Fix validation of 3 OCPP v1.6 payloads containing floats

## 0.4.3 (2019-11-18)

- [#50](https://github.com/mobilityhouse/ocpp/issues/50) Fix RuntimeError when using ocpp.charge_point.ChargePoint.call

## 0.4.2 (2019-11-18)

- [#46](https://github.com/mobilityhouse/ocpp/issues/46) Fix potential deadlock
- [#48](https://github.com/mobilityhouse/ocpp/issues/48) Make ocpp.v16.call.ReserveNowPayload.parent_id_tag optional

## 0.4.1 (2019-11-11)

- [#37](https://github.com/mobilityhouse/ocpp/issues/37) Add Python 3.8 support
- Several fixes of typos and type hints in v16 dataclasses

## 0.4.0 (2019-10-29)

- [#29](https://github.com/mobilityhouse/ocpp/issues/29) Add OCPP 2.0 support

## 0.3.2 (2019-09-30)

- [#27](https://github.com/mobilityhouse/ocpp/issues/27) Fix possible dead lock when running `@after()` handler.

## 0.3.1 (2019-09-23)

- An invalid 0.3.0 release has been uploaded to pypi.org. pypi.org doesn't
  allow reuploading a new release using the same file names. Therefore a new
  release had to be made.

## 0.3.0 (2019-09-23)

** Backwards incompatible change with ocpp <= 0.2.2. **

- [#26](https://github.com/mobilityhouse/ocpp/issues/26) Pass request payload to `@after()` handler.

## 0.2.2 (2019-08-29)

- [#21](https://github.com/mobilityhouse/ocpp/issues/21) Fix several type hints

## 0.2.1 (2019-07-31)

### Bug fixes

- [#14](https://github.com/mobilityhouse/ocpp/issues/14) Fix typo in attribute of call.StartTransactionPayload
- [#16](https://github.com/mobilityhouse/ocpp/issues/16) Fix attributes of call.StopTransaction
- [#18](https://github.com/mobilityhouse/ocpp/issues/18) Fix typo in attribute of call.RemoteStopTransaction

## 0.2.0 (2019-06-07)

### Improvements

- [#5](https://github.com/mobilityhouse/ocpp/issues/5) Add support for Python 3.6 and move to Poetry

## 0.1.1 (2019-05-31)

### Improvements

- [#3](https://github.com/mobilityhouse/ocpp/issues/3) Add CircleCI integration.

### Bug fixes

- [#1](https://github.com/mobilityhouse/ocpp/issues/1) Add JSON schema's to distribution.

## 0.1.0 (2019-05-26)

- Initial release.
