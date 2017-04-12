---
# Intro to Automation & Orchestration
Presented by
Pier-Luc Charbonneau
p.charbonneau@f5.com
---
# Why
---
The engineer that made the expensive mistake meant to execute a command intended to remove only a small number of servers running one of the S3 subsystems. “Unfortunately, one of the inputs to the command was entered incorrectly and a larger set of servers was removed than intended,”
---
# Solution
---
To prevent similar issues from occurring in the future, the AWS team modified its tool for removing capacity to prevent it from removing too much capacity too quickly and to prevent capacity from being removed when any subsystem reaches its minimum required capacity.
---
# Procedure to create virtual server
1. Make sure team requesting the VIP has authorization
2. Verify that the IP address of the VIP is not taken by another application which is on the same subnet
3. Create virtual servers, pools, etc.
4. Repeat x times over the course of a week (while still doing your job as efficiently as possible)
---

| --- | --- |
| #Imperative Model |  f            |
| Imperative – What we’ve done for years (scripting, iRules, etc.) Imperative methodology implies that you define the flow of an operation implicitly. It also implies that domain-specific knowledge is required to interact with the system. | Content Cell  |
What domain-specific knowledge is required to make this sandwich? 

<table>
  <tr>
  <th><h1>Imperative Model</h1></th>
  </tr>
  <tr>
    <td>Imperative – What we’ve done for years (scripting, iRules, etc.) Imperative methodology implies that you define the flow of an operation implicitly. It also implies that domain-specific knowledge is required to interact with the system.</td>
    <td>Smith</td>
  </tr>
  <tr>
  <th>What domain-specific knowledge is required to make this sandwich?</th>
  <th></th>
  </tr>
</table>
