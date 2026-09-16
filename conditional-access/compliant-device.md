# Compliant Device Conditional Access

## Policy
Require-Compliant-Device

## Test Scope
Corporate-Users or a dedicated test group.

## Grant Control
Require device to be marked as compliant.

## Expected Flow

User
→ Sign-in
→ MFA
→ Device compliance evaluation
→ Allow when compliant
→ Block/deny when requirements are not met

## Safety
Test with a non-privileged test account before expanding scope.
