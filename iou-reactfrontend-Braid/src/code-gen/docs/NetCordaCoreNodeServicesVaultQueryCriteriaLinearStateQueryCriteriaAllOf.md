# OpenapiJsClient.NetCordaCoreNodeServicesVaultQueryCriteriaLinearStateQueryCriteriaAllOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**participants** | [**[NetCordaCoreIdentityAbstractParty]**](NetCordaCoreIdentityAbstractParty.md) |  | [optional] 
**uuid** | **[String]** |  | [optional] 
**externalId** | **[String]** |  | [optional] 
**status** | **String** |  | [optional] 
**contractStateTypes** | **[String]** |  | [optional] 
**relevancyStatus** | **String** |  | [optional] 
**exactParticipants** | [**[NetCordaCoreIdentityAbstractParty]**](NetCordaCoreIdentityAbstractParty.md) |  | [optional] 
**constraintTypes** | **[String]** |  | [optional] 
**constraints** | [**[NetCordaCoreNodeServicesVaultConstraintInfo]**](NetCordaCoreNodeServicesVaultConstraintInfo.md) |  | [optional] 
**externalIds** | **[String]** |  | [optional] 



## Enum: StatusEnum


* `UNCONSUMED` (value: `"UNCONSUMED"`)

* `CONSUMED` (value: `"CONSUMED"`)

* `ALL` (value: `"ALL"`)





## Enum: RelevancyStatusEnum


* `RELEVANT` (value: `"RELEVANT"`)

* `NOT_RELEVANT` (value: `"NOT_RELEVANT"`)

* `ALL` (value: `"ALL"`)





## Enum: [ConstraintTypesEnum]


* `ALWAYS_ACCEPT` (value: `"ALWAYS_ACCEPT"`)

* `HASH` (value: `"HASH"`)

* `CZ_WHITELISTED` (value: `"CZ_WHITELISTED"`)

* `SIGNATURE` (value: `"SIGNATURE"`)




