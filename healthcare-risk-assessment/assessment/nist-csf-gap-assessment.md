# NIST CSF 2.0 Gap Assessment

Maturity scale: **1 Initial, 2 Developing, 3 Defined, 4 Managed.**
Target for a small clinic: **3 across all functions.**

| Function | Current | Target | Gap |
|---|---|---|---|
| Govern (GV) | 1 | 3 | 2 |
| Identify (ID) | 2 | 3 | 1 |
| Protect (PR) | 2 | 3 | 1 |
| Detect (DE) | 1 | 3 | 2 |
| Respond (RS) | 1 | 3 | 2 |
| Recover (RC) | 2 | 3 | 1 |

## Findings by Function

### Govern
- No written security policies or assigned security owner.
- Risk is not reviewed by leadership.
- **Fix:** Name a security lead. Approve policies. Review risk twice a year.

### Identify
- Assets are tracked in an informal spreadsheet.
- No formal risk assessment before this one.
- Vendor risk is not reviewed.
- **Fix:** Keep the asset inventory current. Repeat this assessment yearly. Add a vendor review.

### Protect
- MFA is used on some accounts, not all.
- Patching is irregular.
- No security training for staff.
- Many staff have more access than they need.
- **Fix:** Enforce MFA. Patch monthly. Train staff. Apply least privilege.

### Detect
- No central logging or alerting.
- Nobody reviews logs.
- **Fix:** Turn on email and endpoint alerts. Review key logs weekly.

### Respond
- No incident response plan.
- Staff do not know who to call.
- **Fix:** Adopt the incident response policy. Run one tabletop exercise.

### Recover
- Backups run nightly.
- Restores have never been tested.
- All backups are online, so ransomware could reach them.
- **Fix:** Test restores quarterly. Keep one offline copy.
