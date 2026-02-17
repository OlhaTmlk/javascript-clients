# Profile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Profile unique identity value | [optional] [default to undefined]
**account_id** | **string** | Red Hat account number | [optional] [default to undefined]
**org_id** | **string** | Red Hat organization identity value | [optional] [default to undefined]
**created_at** | **string** | Time of profile creation | [optional] [default to undefined]
**active** | **boolean** | Remote host configuration enabled state | [optional] [default to undefined]
**compliance** | **boolean** | Remote configuration status for running Compliance data collection | [optional] [default to undefined]
**insights** | **boolean** | Remote configuration status for running Insights data collection | [optional] [default to undefined]
**remediations** | **boolean** | Remote configuration status for running Remediation playbooks | [optional] [default to undefined]

## Example

```typescript
import { Profile } from './api';

const instance: Profile = {
    id,
    account_id,
    org_id,
    created_at,
    active,
    compliance,
    insights,
    remediations,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
