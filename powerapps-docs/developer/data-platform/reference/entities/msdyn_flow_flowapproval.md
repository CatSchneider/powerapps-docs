---
title: "Flow Approval (msdyn_flow_flowapproval) table/entity reference (Microsoft Dataverse)"
description: "Includes schema information and supported messages for the Flow Approval (msdyn_flow_flowapproval) table/entity with Microsoft Dataverse."
ms.date: 08/30/2024
ms.service: powerapps
ms.topic: reference
author: phecke
ms.author: pehecke
search.audienceType: 
  - developer
---

# Flow Approval (msdyn_flow_flowapproval) table/entity reference

Microsoft Flow data attached to an approval.

## Messages

The following table lists the messages for the Flow Approval (msdyn_flow_flowapproval) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Assign`<br />Event: True |`PATCH` /msdyn_flow_flowapprovals(*msdyn_flow_flowapprovalid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `ownerid` property. |<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
| `Create`<br />Event: True |`POST` /msdyn_flow_flowapprovals<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: True |`DELETE` /msdyn_flow_flowapprovals(*msdyn_flow_flowapprovalid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `GrantAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
| `IsValidStateTransition`<br />Event: False |<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
| `ModifyAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
| `Retrieve`<br />Event: True |`GET` /msdyn_flow_flowapprovals(*msdyn_flow_flowapprovalid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /msdyn_flow_flowapprovals<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `RetrievePrincipalAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
| `RetrieveSharedPrincipalsAndAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
| `RevokeAccess`<br />Event: True |<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType /> |<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
| `SetState`<br />Event: True |`PATCH` /msdyn_flow_flowapprovals(*msdyn_flow_flowapprovalid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) the `statecode` and `statuscode` properties. |<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
| `Update`<br />Event: True |`PATCH` /msdyn_flow_flowapprovals(*msdyn_flow_flowapprovalid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: True |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /msdyn_flow_flowapprovals(*msdyn_flow_flowapprovalid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|

## Properties

The following table lists selected properties for the Flow Approval (msdyn_flow_flowapproval) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Flow Approval** |
| **DisplayCollectionName** | **Flow Approvals** |
| **SchemaName** | `msdyn_flow_flowapproval` |
| **CollectionSchemaName** | `msdyn_flow_flowapprovals` |
| **EntitySetName** | `msdyn_flow_flowapprovals`|
| **LogicalName** | `msdyn_flow_flowapproval` |
| **LogicalCollectionName** | `msdyn_flow_flowapprovals` |
| **PrimaryIdAttribute** | `msdyn_flow_flowapprovalid` |
| **PrimaryNameAttribute** |`msdyn_flow_flowapproval_name` |
| **TableType** | `Standard` |
| **OwnershipType** | `UserOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_flow_flowapproval_approval](#BKMK_msdyn_flow_flowapproval_approval)
- [msdyn_flow_flowapproval_flowculture](#BKMK_msdyn_flow_flowapproval_flowculture)
- [msdyn_flow_flowapproval_flowid](#BKMK_msdyn_flow_flowapproval_flowid)
- [msdyn_flow_flowapproval_flowname](#BKMK_msdyn_flow_flowapproval_flowname)
- [msdyn_flow_flowapproval_flownotificationuri](#BKMK_msdyn_flow_flowapproval_flownotificationuri)
- [msdyn_flow_flowapproval_flowrunsequenceid](#BKMK_msdyn_flow_flowapproval_flowrunsequenceid)
- [msdyn_flow_flowapproval_name](#BKMK_msdyn_flow_flowapproval_name)
- [msdyn_flow_flowapproval_sendflowemail](#BKMK_msdyn_flow_flowapproval_sendflowemail)
- [msdyn_flow_flowapproval_sendflowpush](#BKMK_msdyn_flow_flowapproval_sendflowpush)
- [msdyn_flow_flowapprovalId](#BKMK_msdyn_flow_flowapprovalId)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)

### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|---|---|
|Description|**Sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_msdyn_flow_flowapproval_approval"></a> msdyn_flow_flowapproval_approval

|Property|Value|
|---|---|
|Description|**The linked approval.**|
|DisplayName|**Approval**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_approval`|
|RequiredLevel|ApplicationRequired|
|Type|Lookup|
|Targets|msdyn_flow_approval|

### <a name="BKMK_msdyn_flow_flowapproval_flowculture"></a> msdyn_flow_flowapproval_flowculture

|Property|Value|
|---|---|
|Description|**The locale set by logic apps when the approval was created.**|
|DisplayName|**Flow Localization Culture Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_flowculture`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_flow_flowapproval_flowid"></a> msdyn_flow_flowapproval_flowid

|Property|Value|
|---|---|
|Description|**The logic apps id of the flow.**|
|DisplayName|**Flow Id**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_flowid`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_flow_flowapproval_flowname"></a> msdyn_flow_flowapproval_flowname

|Property|Value|
|---|---|
|Description|**The name of the flow.**|
|DisplayName|**Flow Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_flowname`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_flow_flowapproval_flownotificationuri"></a> msdyn_flow_flowapproval_flownotificationuri

|Property|Value|
|---|---|
|Description|**The logic apps callback to resume the flow once the approval completes.**|
|DisplayName|**Flow Notification URI**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_flownotificationuri`|
|RequiredLevel|None|
|Type|String|
|Format|Url|
|FormatName|Url|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2048|

### <a name="BKMK_msdyn_flow_flowapproval_flowrunsequenceid"></a> msdyn_flow_flowapproval_flowrunsequenceid

|Property|Value|
|---|---|
|Description|**The sequence id of the flow run.**|
|DisplayName|**Flow Run Sequence Id**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_flowrunsequenceid`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_flow_flowapproval_name"></a> msdyn_flow_flowapproval_name

|Property|Value|
|---|---|
|Description|**The name of the flow approval.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_name`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_msdyn_flow_flowapproval_sendflowemail"></a> msdyn_flow_flowapproval_sendflowemail

|Property|Value|
|---|---|
|Description|**Whether to send system-generated email notifications for the approval.**|
|DisplayName|**Send Flow Email Notification**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_sendflowemail`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_flow_flowapproval_msdyn_flow_flowapproval_sendflowemail`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_flow_flowapproval_sendflowpush"></a> msdyn_flow_flowapproval_sendflowpush

|Property|Value|
|---|---|
|Description|**Whether to send system-generated push notifications for the approval.**|
|DisplayName|**Send Flow Push Notification**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapproval_sendflowpush`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`msdyn_flow_flowapproval_msdyn_flow_flowapproval_sendflowpush`|
|DefaultValue|True|
|True Label|Yes|
|False Label|No|

### <a name="BKMK_msdyn_flow_flowapprovalId"></a> msdyn_flow_flowapprovalId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Flow Approval**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`msdyn_flow_flowapprovalid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|---|---|
|Description|**Date and time that the record was migrated.**|
|DisplayName|**Record Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overriddencreatedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|---|---|
|Description|**Owner Id**|
|DisplayName|**Owner**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ownerid`|
|RequiredLevel|SystemRequired|
|Type|Owner|
|Targets|systemuser, team|

### <a name="BKMK_OwnerIdType"></a> OwnerIdType

|Property|Value|
|---|---|
|Description|**Owner Id Type**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridtype`|
|RequiredLevel|SystemRequired|
|Type|EntityName|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the Flow Approval**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_flow_flowapproval_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 192350000<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 192350003<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Flow Approval**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`msdyn_flow_flowapproval_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|192350000|Label: **Created**<br />State:0<br />TransitionData: None|
|192350001|Label: **WaitingForApproval**<br />State:0<br />TransitionData: None|
|192350002|Label: **NotifyingFlow**<br />State:0<br />TransitionData: None|
|192350003|Label: **Completed**<br />State:1<br />TransitionData: None|

### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Time Zone Rule Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`timezoneruleversionnumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|

### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|---|---|
|Description|**Time zone code that was in use when the record was created.**|
|DisplayName|**UTC Conversion Time Zone Code**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`utcconversiontimezonecode`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|


## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** and **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)

### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who created the record.**|
|DisplayName|**Created By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was created.**|
|DisplayName|**Created On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who created the record.**|
|DisplayName|**Created By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who modified the record.**|
|DisplayName|**Modified By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was modified.**|
|DisplayName|**Modified On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who modified the record.**|
|DisplayName|**Modified By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|---|---|
|Description|**Name of the owner**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridname`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

|Property|Value|
|---|---|
|Description|**Yomi name of the owner**|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owneridyominame`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

|Property|Value|
|---|---|
|Description|**Unique identifier for the business unit that owns the record**|
|DisplayName|**Owning Business Unit**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`owningbusinessunit`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|businessunit|

### <a name="BKMK_OwningTeam"></a> OwningTeam

|Property|Value|
|---|---|
|Description|**Unique identifier for the team that owns the record.**|
|DisplayName|**Owning Team**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owningteam`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|team|

### <a name="BKMK_OwningUser"></a> OwningUser

|Property|Value|
|---|---|
|Description|**Unique identifier for the user that owns the record.**|
|DisplayName|**Owning User**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`owninguser`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|---|---|
|Description|**Version Number**|
|DisplayName|**Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`versionnumber`|
|RequiredLevel|None|
|Type|BigInt|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [business_unit_msdyn_flow_flowapproval](#BKMK_business_unit_msdyn_flow_flowapproval)
- [lk_msdyn_flow_flowapproval_createdby](#BKMK_lk_msdyn_flow_flowapproval_createdby)
- [lk_msdyn_flow_flowapproval_createdonbehalfby](#BKMK_lk_msdyn_flow_flowapproval_createdonbehalfby)
- [lk_msdyn_flow_flowapproval_modifiedby](#BKMK_lk_msdyn_flow_flowapproval_modifiedby)
- [lk_msdyn_flow_flowapproval_modifiedonbehalfby](#BKMK_lk_msdyn_flow_flowapproval_modifiedonbehalfby)
- [msdyn_flow_approvalrelationship_flowapprovals](#BKMK_msdyn_flow_approvalrelationship_flowapprovals)
- [owner_msdyn_flow_flowapproval](#BKMK_owner_msdyn_flow_flowapproval)
- [team_msdyn_flow_flowapproval](#BKMK_team_msdyn_flow_flowapproval)
- [user_msdyn_flow_flowapproval](#BKMK_user_msdyn_flow_flowapproval)

### <a name="BKMK_business_unit_msdyn_flow_flowapproval"></a> business_unit_msdyn_flow_flowapproval

One-To-Many Relationship: [businessunit business_unit_msdyn_flow_flowapproval](businessunit.md#BKMK_business_unit_msdyn_flow_flowapproval)

|Property|Value|
|---|---|
|ReferencedEntity|`businessunit`|
|ReferencedAttribute|`businessunitid`|
|ReferencingAttribute|`owningbusinessunit`|
|ReferencingEntityNavigationPropertyName|`owningbusinessunit`|
|IsHierarchical||
|CascadeConfiguration|Archive: `Restrict`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_flow_flowapproval_createdby"></a> lk_msdyn_flow_flowapproval_createdby

One-To-Many Relationship: [systemuser lk_msdyn_flow_flowapproval_createdby](systemuser.md#BKMK_lk_msdyn_flow_flowapproval_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_flow_flowapproval_createdonbehalfby"></a> lk_msdyn_flow_flowapproval_createdonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_flow_flowapproval_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_flow_flowapproval_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_flow_flowapproval_modifiedby"></a> lk_msdyn_flow_flowapproval_modifiedby

One-To-Many Relationship: [systemuser lk_msdyn_flow_flowapproval_modifiedby](systemuser.md#BKMK_lk_msdyn_flow_flowapproval_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_msdyn_flow_flowapproval_modifiedonbehalfby"></a> lk_msdyn_flow_flowapproval_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_msdyn_flow_flowapproval_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_flow_flowapproval_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_msdyn_flow_approvalrelationship_flowapprovals"></a> msdyn_flow_approvalrelationship_flowapprovals

One-To-Many Relationship: [msdyn_flow_approval msdyn_flow_approvalrelationship_flowapprovals](msdyn_flow_approval.md#BKMK_msdyn_flow_approvalrelationship_flowapprovals)

|Property|Value|
|---|---|
|ReferencedEntity|`msdyn_flow_approval`|
|ReferencedAttribute|`msdyn_flow_approvalid`|
|ReferencingAttribute|`msdyn_flow_flowapproval_approval`|
|ReferencingEntityNavigationPropertyName|`msdyn_flow_flowapproval_approval`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `RemoveLink`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_owner_msdyn_flow_flowapproval"></a> owner_msdyn_flow_flowapproval

One-To-Many Relationship: [owner owner_msdyn_flow_flowapproval](owner.md#BKMK_owner_msdyn_flow_flowapproval)

|Property|Value|
|---|---|
|ReferencedEntity|`owner`|
|ReferencedAttribute|`ownerid`|
|ReferencingAttribute|`ownerid`|
|ReferencingEntityNavigationPropertyName|`ownerid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_team_msdyn_flow_flowapproval"></a> team_msdyn_flow_flowapproval

One-To-Many Relationship: [team team_msdyn_flow_flowapproval](team.md#BKMK_team_msdyn_flow_flowapproval)

|Property|Value|
|---|---|
|ReferencedEntity|`team`|
|ReferencedAttribute|`teamid`|
|ReferencingAttribute|`owningteam`|
|ReferencingEntityNavigationPropertyName|`owningteam`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_user_msdyn_flow_flowapproval"></a> user_msdyn_flow_flowapproval

One-To-Many Relationship: [systemuser user_msdyn_flow_flowapproval](systemuser.md#BKMK_user_msdyn_flow_flowapproval)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`owninguser`|
|ReferencingEntityNavigationPropertyName|`owninguser`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [msdyn_flow_flowapproval_AsyncOperations](#BKMK_msdyn_flow_flowapproval_AsyncOperations)
- [msdyn_flow_flowapproval_BulkDeleteFailures](#BKMK_msdyn_flow_flowapproval_BulkDeleteFailures)
- [msdyn_flow_flowapproval_DuplicateBaseRecord](#BKMK_msdyn_flow_flowapproval_DuplicateBaseRecord)
- [msdyn_flow_flowapproval_DuplicateMatchingRecord](#BKMK_msdyn_flow_flowapproval_DuplicateMatchingRecord)
- [msdyn_flow_flowapproval_MailboxTrackingFolders](#BKMK_msdyn_flow_flowapproval_MailboxTrackingFolders)
- [msdyn_flow_flowapproval_PrincipalObjectAttributeAccesses](#BKMK_msdyn_flow_flowapproval_PrincipalObjectAttributeAccesses)
- [msdyn_flow_flowapproval_ProcessSession](#BKMK_msdyn_flow_flowapproval_ProcessSession)
- [msdyn_flow_flowapproval_SyncErrors](#BKMK_msdyn_flow_flowapproval_SyncErrors)

### <a name="BKMK_msdyn_flow_flowapproval_AsyncOperations"></a> msdyn_flow_flowapproval_AsyncOperations

Many-To-One Relationship: [asyncoperation msdyn_flow_flowapproval_AsyncOperations](asyncoperation.md#BKMK_msdyn_flow_flowapproval_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_flow_flowapproval_BulkDeleteFailures"></a> msdyn_flow_flowapproval_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure msdyn_flow_flowapproval_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_flow_flowapproval_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_flow_flowapproval_DuplicateBaseRecord"></a> msdyn_flow_flowapproval_DuplicateBaseRecord

Many-To-One Relationship: [duplicaterecord msdyn_flow_flowapproval_DuplicateBaseRecord](duplicaterecord.md#BKMK_msdyn_flow_flowapproval_DuplicateBaseRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`baserecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_DuplicateBaseRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_flow_flowapproval_DuplicateMatchingRecord"></a> msdyn_flow_flowapproval_DuplicateMatchingRecord

Many-To-One Relationship: [duplicaterecord msdyn_flow_flowapproval_DuplicateMatchingRecord](duplicaterecord.md#BKMK_msdyn_flow_flowapproval_DuplicateMatchingRecord)

|Property|Value|
|---|---|
|ReferencingEntity|`duplicaterecord`|
|ReferencingAttribute|`duplicaterecordid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_DuplicateMatchingRecord`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_flow_flowapproval_MailboxTrackingFolders"></a> msdyn_flow_flowapproval_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder msdyn_flow_flowapproval_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_flow_flowapproval_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_flow_flowapproval_PrincipalObjectAttributeAccesses"></a> msdyn_flow_flowapproval_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess msdyn_flow_flowapproval_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_flow_flowapproval_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_flow_flowapproval_ProcessSession"></a> msdyn_flow_flowapproval_ProcessSession

Many-To-One Relationship: [processsession msdyn_flow_flowapproval_ProcessSession](processsession.md#BKMK_msdyn_flow_flowapproval_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_msdyn_flow_flowapproval_SyncErrors"></a> msdyn_flow_flowapproval_SyncErrors

Many-To-One Relationship: [syncerror msdyn_flow_flowapproval_SyncErrors](syncerror.md#BKMK_msdyn_flow_flowapproval_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`msdyn_flow_flowapproval_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.msdyn_flow_flowapproval?displayProperty=fullName>