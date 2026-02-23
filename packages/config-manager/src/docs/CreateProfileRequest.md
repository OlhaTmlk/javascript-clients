# CreateProfileRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | **boolean** | Remote host configuration enabled state | [default to undefined]
**compliance** | **boolean** | Remote configuration status for running Compliance data collection | [default to undefined]
**insights** | **boolean** | Remote configuration status for running Insights data collection | [default to undefined]
**remediations** | **boolean** | Remote configuration status for running Remediation playbooks | [default to undefined]

## Example

```typescript
import { CreateProfileRequest } from './api';

const instance: CreateProfileRequest = {
    active,
    compliance,
    insights,
    remediations,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
