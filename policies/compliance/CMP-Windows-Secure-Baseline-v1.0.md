# CMP - Windows - Secure Baseline - v1.0

## Objective
Define minimum compliance requirements for Windows endpoints in an enterprise environment.

## Scope
Windows 10 and Windows 11 corporate-managed devices.

## Compliance Requirements
- TPM required
- Secure Boot enabled
- BitLocker enabled
- Minimum supported OS version
- Screen lock enforced

## Engineering Rationale
This baseline balances security enforcement with user experience and operational stability.

## Validation Steps
- Confirm device is enrolled and checking in
- Verify BitLocker encryption status
- Confirm Secure Boot and TPM presence

## Common Failure Scenarios
- Unsupported hardware (TPM missing or disabled)
- Device not checking in to management service
- Conflicting legacy policies

## Troubleshooting Notes
- Force device sync and re-evaluate compliance
- Review assignment scope and exclusions
- Validate hardware prerequisites
