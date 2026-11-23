# Helpdesk Knowledge Base — Troubleshooting Articles

These **10 draft articles** cover the issues documented in the simulation. They have been edited into consistent **problem / checks / escalation** formats. They are reference guidance, **not records of verified fixes or production deployment**.

Security-sensitive guidance has been reviewed: disabling antivirus or firewalls, bypassing access controls, and requesting user passwords are **not** recommended troubleshooting shortcuts.

## 01. Application Not Responding

**Category:** Software Issues  
**Reported issue:** An application freezes or becomes unresponsive.

**Suggested diagnostic checks**

- Record the application name, error text, and whether other applications are affected.
- Check CPU, memory, and available disk space; capture any relevant application or system errors.
- If necessary, end the unresponsive process after checking for unsaved work.
- Check for approved updates and test a restart; consider repair or reinstall through the approved software process.

**Escalation:** Escalate repeated crashes, suspected malware, or failures affecting multiple users.

---

## 02. Software Installation Failure

**Category:** Software Issues  
**Reported issue:** An authorized application fails to install.

**Suggested diagnostic checks**

- Capture the installer name, version, exact error message, and installation log if available.
- Verify device compatibility, storage, and the authenticity of the installation source.
- Confirm software approval and required permissions before attempting an elevated installation.
- Retry with a verified installer or follow the approved deployment method.

**Escalation:** Escalate persistent installer errors or security software alerts. Do not disable endpoint protection to bypass installation failures.

---

## 03. Computer Freezing

**Category:** Hardware Issues  
**Reported issue:** A workstation freezes or stops responding.

**Suggested diagnostic checks**

- Record frequency, recent changes, affected applications, and any error codes.
- Review resource usage, device temperature, and Windows reliability or event logs.
- Run approved memory and disk health checks; inspect driver and update history.
- Back up important data before any disruptive repair or operating-system reinstall.

**Escalation:** Escalate signs of hardware failure, recurring crashes, or possible malicious activity.

---

## 04. Printer Paper Jam

**Category:** Hardware Issues  
**Reported issue:** A printer repeatedly reports a paper jam.

**Suggested diagnostic checks**

- Identify the printer model and consult the manufacturer's safe paper-jam procedure.
- Check paper alignment, tray loading, and visible obstructions after the device is safe to inspect.
- Remove jammed paper carefully without forcing rollers or internal components.
- Restore covers and run a test print to determine whether the fault persists.

**Escalation:** Escalate repeated jams, damaged rollers, or components requiring service.

---

## 05. No Internet Connection

**Category:** Network Issues  
**Reported issue:** A workstation cannot reach expected network resources or websites.

**Suggested diagnostic checks**

- Determine whether the issue affects one device, one network segment, or multiple users.
- Check link/Wi-Fi state and collect IP address, gateway, and DNS configuration.
- Test local gateway reachability, DNS resolution, and an approved destination to isolate the fault.
- Review relevant network and endpoint security alerts without disabling protective controls.

**Escalation:** Escalate gateway, DHCP, DNS, ISP, or wider network faults with the collected test results.

---

## 06. Shared Drive Access Denied

**Category:** Network Issues  
**Reported issue:** A user cannot open a shared network drive.

**Suggested diagnostic checks**

- Confirm the network connection and the exact share path or mapped drive.
- Record the error and determine whether access previously worked.
- Verify identity, group membership, and access permissions through authorized administration channels.
- Test the approved connection method without granting unnecessary privileges.

**Escalation:** Escalate missing authorization, permission changes, or storage-service outages.

---

## 07. Slow Internet Connection

**Category:** Network Issues  
**Reported issue:** A user reports slow or inconsistent network performance.

**Suggested diagnostic checks**

- Confirm the scope, timing, connection type, and affected services.
- Collect approved speed or latency tests and inspect local bandwidth consumption.
- Check Wi-Fi signal quality or wired link status and compare with other users.
- Record findings and avoid changing shared network equipment without approval.

**Escalation:** Escalate persistent congestion, packet loss, or suspected provider problems.

---

## 08. VPN Connection Failure

**Category:** Network Issues  
**Reported issue:** A user cannot establish a VPN session.

**Suggested diagnostic checks**

- Verify that ordinary internet connectivity works and record the VPN client error.
- Confirm the correct VPN profile, client version, and approved authentication flow.
- Check whether MFA prompts, account restrictions, or a VPN service outage are involved.
- Review relevant client logs and retry according to organizational guidance.

**Escalation:** Escalate authentication failures, account lockouts, or VPN service incidents; never request passwords or MFA codes.

---

## 09. Email Access Failure

**Category:** Accounts & Access  
**Reported issue:** A user cannot access their mailbox.

**Suggested diagnostic checks**

- Determine whether the issue affects webmail, desktop client, or mobile access.
- Check service health, network connectivity, and the exact sign-in error.
- Review account status and MFA requirements through authorized support procedures.
- If needed, test an approved sign-in or client reconfiguration without exposing credentials.

**Escalation:** Escalate suspected account compromise, suspicious sign-ins, or organization-wide outages.

---

## 10. Password Reset Request

**Category:** Accounts & Access  
**Reported issue:** A user reports being unable to sign in.

**Suggested diagnostic checks**

- Confirm the account and verify the requester's identity using the approved process.
- Direct the user to the organization's approved self-service reset flow when available.
- For assisted resets, follow authorized access-management procedures and require MFA as applicable.
- Record the action taken without storing the password or sensitive authentication information.

**Escalation:** Escalate identity-verification failures, suspicious reset requests, or compromised accounts.

---

