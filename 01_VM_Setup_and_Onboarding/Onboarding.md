# Microsoft Defender for Endpoint – Onboarding (Part 1)

These steps follow Part 1 of the provided onboarding instructions.

## 📝 Onboarding Process
1. Download onboarding package from Microsoft 365 Defender Portal.
2. Extract or run the onboarding script based on OS type.
3. Confirm successful onboarding:

## ✔ Verification Steps

### KQL Query:
```kusto
DeviceInfo
| where DeviceName == "matt-threat-hun"
| project DeviceName, OnboardingStatus, OSPlatform
