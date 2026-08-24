# Gallery Corp
## Access Control Standard

| Field | Detail |
|---|---|
| **Standard ID** | STD-001 |
| **Parent Policy** | POL-001 — Access Control Policy |
| **Version** | 1.0 |
| **Status** | Draft |
| **Owner** | Information Security Team |
| **Review Date** | August 24, 2027 |

## 1. MFA Requirements
1.1 Acceptable MFA methods: TOTP authenticator apps (e.g., Google Authenticator, Authy),
    hardware security keys (FIDO2/WebAuthn).

1.2 SMS-based OTP is not an acceptable MFA method for systems classified Critical or High.

1.3 MFA must be enforced at the identity provider level, not optionally enabled.

## 2. Password Requirements
2.1 Minimum password length: 14 characters.

2.2 Passwords must not be reused within the last 12 cycles.

2.3 Passwords must be checked against a known-breached credential list at creation
    (e.g., using the HaveIBeenPwned API or equivalent).

## 3. Access Provisioning

3.1 All access requests must be submitted via the approved ticketing system and approved
    by the relevant line manager before provisioning.

3.2 Privileged accounts must be provisioned separately from standard user accounts.
    Admin accounts must follow the naming convention: adm-[username].

3.3 Service accounts must be documented in the service account register with a named owner.

## 4. Access Reviews

4.1 Access reviews must be completed every 6 months for standard accounts and every
    3 months for privileged accounts.

4.2 Review evidence (sign-off records) must be retained for a minimum of 2 years.

## 5. Leavers

5.1 All access for leavers must be disabled within 4 hours of HR notification and
    permanently removed within 5 business days.
