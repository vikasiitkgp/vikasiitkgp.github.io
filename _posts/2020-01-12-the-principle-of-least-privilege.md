---
layout: post
title: The Principle of Least Privilege
categories: [Technology, Security, Data-Protection]
---

The principle of least privilege is the idea that at any user, program, or process should have only the bare minimum privileges necessary to perform its function. For example, a user account created for pulling records from a database doesn’t need admin rights, while a programmer whose main function is updating lines of legacy code doesn’t need access to financial records. The principle of least privilege can also be referred to as the principle of minimal privilege (POMP) or the principle of least authority (POLA). Following the principle of least privilege is considered a best practice in information security.

The principle of least privilege works by allowing only enough access to perform the required job. In an IT environment, adhering to the principle of least privilege reduces the risk of attackers gaining access to critical systems or sensitive data by compromising a low-level user account, device, or application. Implementing the principle of least privilege helps contain compromises to their area of origin, stopping them from spreading to the system at large.

The principle of least privilege can be applied to every level of a system. It applies to end users, systems, processes, networks, databases, applications, and every other facet of an IT environment. Below are just a few examples of how the principle can work (or fail) in practice.

**User Account with Least Privilege:** With the principle of least privilege, an employee whose job is to enter info into a database only needs the ability to add records to that database. If malware infects that employee’s computer or if the employee clicks a link in a phishing email, the malicious attack is limited to making database entries. If that employee has root access privileges however, the infection can spread system-wide.

**Using Just in Time Least Privilege:** A user who only rarely needs root privileges should work with reduced privileges the rest of the time. To increase traceability, that user can retrieve root access credentials from a password vault as needed. Using disposable credentials tightens the security achieved by just in time least privilege.

## Benefits
There are many benefits of implementing the principle of least privilege.

1. Better security
2. Minimized attack surface
3. Limited malware propagation
4. Better stability
5. Improved audit readiness

## Best Practices
1. Conduct a privilege audit. Check all existing accounts, processes, and programs to ensure that they only have the permissions required to do the job.
2. Start all accounts with least privilege. The default for all new account privileges should be set as low as possible. Only add specific higher-level powers as needed to perform the job.
3. Enforce the separation of privileges. Separate admin accounts from standard accounts, and higher level system functions from lower ones.
4. Use just in time privileges. Wherever possible, restrict raised privileges only to moments when they are needed. Implement on expiring privileges and one-time-use credentials.
5. Make individual actions traceable. User IDs, one-time passwords, monitoring, and automatic auditing can make it easier to track and limit damage.
6. Make it regular. Auditing privileges regularly prevents a situation where older users, accounts, and processes accumulate privileges over time, whether they still need those things or not.