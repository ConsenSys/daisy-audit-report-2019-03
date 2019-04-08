## Mythril output via MythX

```
Reading contract contracts/PlanSubscriptionManager_flat.sol... done
Downloading Solidity version v0.5.4+commit.9549d8ff
Compiling contract contracts/PlanSubscriptionManager_flat.sol... done
Analyzing contract PlanSubscriptionManager... done
Report found 1 issues
Title: Floating Pragma
Severity: Medium
Head: A floating pragma is set.
Description: It is recommended to make a conscious choice on what version of Solidity is used for compilation. Currently any version equal or greater than "0.5.4" is allowed.
Source code:

contracts/PlanSubscriptionManager_flat.sol 1:0
--------------------------------------------------
pragma solidity ^0.5.4;
--------------------------------------------------

==================================================

Done
```