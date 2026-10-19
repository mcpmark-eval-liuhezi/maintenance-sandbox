# Maintenance Checklist

Snapshot generated from a live audit of the `HeziLiu` GitHub account on **2026-07-15**. All values below are exactly as the API calls returned them — where a call could not retrieve a value, that is stated explicitly rather than assumed.

## Audit snapshot

Repositories found under the account: **4**

| Repository | Latest release tag | Open Dependabot alerts | Open issues |
| --- | --- | --- | --- |
| `HeziLiu/Little-rookie` | None — no releases exist (404 on `releases/latest`, empty release list) | Unknown — Dependabot alert call failed with 403 "Resource not accessible by personal access token" | 0 |
| `HeziLiu/CodingInterviewChinese2` (fork) | None — no releases exist (404 on `releases/latest`, empty release list) | Unknown — Dependabot alerts disabled for this repository (403) | 0 |
| `HeziLiu/awesome-chatgpt-prompts-zh` (fork) | None — no releases exist (404 on `releases/latest`, empty release list) | Unknown — Dependabot alerts disabled for this repository (403) | 0 |
| `HeziLiu/Big-Buzzard` | None — no releases exist (404 on `releases/latest`, empty release list) | Unknown — Dependabot alert call failed with 403 "Resource not accessible by personal access token" | 0 |

Notes on the audit:

- The account profile reports 4 public repositories; 2 are non-fork repositories and 2 are forks (`CodingInterviewChinese2` and `awesome-chatgpt-prompts-zh`), which only appear in search results when forks are included.
- No repository under the account has ever published a release.
- Dependabot alert data could not be read for any repository: two repos returned a token-permission 403 and two returned "Dependabot alerts are disabled for this repository". The counts above are therefore **unknown**, not zero.
- No open issues exist in any of the four repositories.

## Follow-up items

- [ ] Grant the token the `security_events` / Dependabot alerts read scope so alert counts can actually be retrieved for `Little-rookie` and `Big-Buzzard`.
- [ ] Enable Dependabot alerts on `CodingInterviewChinese2` and `awesome-chatgpt-prompts-zh`, or confirm they are intentionally left off on forks.
- [ ] Decide whether any of the four repositories should adopt tagged releases so a "latest release" baseline exists.
- [ ] Review whether the two forked repositories are still needed, and archive or delete if not.
- [ ] Re-run this audit after the above are addressed and update this checklist with actual alert counts.
