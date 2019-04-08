## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| contracts/PlanSubscriptionManager_flat.sol | 84afdf3b6d21f8b52dc5833fef9fb833a1d5836d |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **SafeMath** | Library |  |||
| └ | mul | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | add | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
||||||
| **Math** | Library |  |||
| └ | max | Internal 🔒 |   | |
| └ | min | Internal 🔒 |   | |
| └ | average | Internal 🔒 |   | |
||||||
| **Ownable** | Implementation |  |||
| └ | \<Constructor\> | Internal 🔒 | 🛑  | |
| └ | owner | Public ❗️ |   |NO❗️ |
| └ | isOwner | Public ❗️ |   |NO❗️ |
| └ | renounceOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | transferOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | _transferOwnership | Internal 🔒 | 🛑  | |
||||||
| **IERC20** | Interface |  |||
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
||||||
| **Address** | Library |  |||
| └ | isContract | Internal 🔒 |   | |
||||||
| **SafeERC20** | Library |  |||
| └ | safeTransfer | Internal 🔒 | 🛑  | |
| └ | safeTransferFrom | Internal 🔒 | 🛑  | |
| └ | safeApprove | Internal 🔒 | 🛑  | |
| └ | safeIncreaseAllowance | Internal 🔒 | 🛑  | |
| └ | safeDecreaseAllowance | Internal 🔒 | 🛑  | |
| └ | callOptionalReturn | Private 🔐 | 🛑  | |
||||||
| **ECDSA** | Library |  |||
| └ | recover | Internal 🔒 |   | |
| └ | toEthSignedMessageHash | Internal 🔒 |   | |
||||||
| **BokkyPooBahsDateTimeLibrary** | Library |  |||
| └ | _daysFromDate | Internal 🔒 |   | |
| └ | _daysToDate | Internal 🔒 |   | |
| └ | timestampFromDate | Internal 🔒 |   | |
| └ | timestampFromDateTime | Internal 🔒 |   | |
| └ | timestampToDate | Internal 🔒 |   | |
| └ | timestampToDateTime | Internal 🔒 |   | |
| └ | isValidDate | Internal 🔒 |   | |
| └ | isValidDateTime | Internal 🔒 |   | |
| └ | isLeapYear | Internal 🔒 |   | |
| └ | _isLeapYear | Internal 🔒 |   | |
| └ | isWeekDay | Internal 🔒 |   | |
| └ | isWeekEnd | Internal 🔒 |   | |
| └ | getDaysInMonth | Internal 🔒 |   | |
| └ | _getDaysInMonth | Internal 🔒 |   | |
| └ | getDayOfWeek | Internal 🔒 |   | |
| └ | getYear | Internal 🔒 |   | |
| └ | getMonth | Internal 🔒 |   | |
| └ | getDay | Internal 🔒 |   | |
| └ | getHour | Internal 🔒 |   | |
| └ | getMinute | Internal 🔒 |   | |
| └ | getSecond | Internal 🔒 |   | |
| └ | addYears | Internal 🔒 |   | |
| └ | addMonths | Internal 🔒 |   | |
| └ | addDays | Internal 🔒 |   | |
| └ | addHours | Internal 🔒 |   | |
| └ | addMinutes | Internal 🔒 |   | |
| └ | addSeconds | Internal 🔒 |   | |
| └ | subYears | Internal 🔒 |   | |
| └ | subMonths | Internal 🔒 |   | |
| └ | subDays | Internal 🔒 |   | |
| └ | subHours | Internal 🔒 |   | |
| └ | subMinutes | Internal 🔒 |   | |
| └ | subSeconds | Internal 🔒 |   | |
| └ | diffYears | Internal 🔒 |   | |
| └ | diffMonths | Internal 🔒 |   | |
| └ | diffDays | Internal 🔒 |   | |
| └ | diffHours | Internal 🔒 |   | |
| └ | diffMinutes | Internal 🔒 |   | |
| └ | diffSeconds | Internal 🔒 |   | |
||||||
| **ISubscriptionManager** | Interface |  |||
| └ | isCancelled | External ❗️ |   |NO❗️ |
| └ | isActive | External ❗️ |   |NO❗️ |
| └ | nextPaymentTimestamp | External ❗️ |   |NO❗️ |
| └ | getSubscription | External ❗️ |   |NO❗️ |
| └ | execute | External ❗️ | 🛑  |NO❗️ |
| └ | cancel | External ❗️ | 🛑  |NO❗️ |
||||||
| **IDelegatedSubscriptionManager** | Implementation | ISubscriptionManager |||
| └ | cancel | External ❗️ | 🛑  |NO❗️ |
| └ | getActionHash | Public ❗️ |   |NO❗️ |
| └ | getSigner | Public ❗️ |   |NO❗️ |
||||||
| **IEnumerableSubscriptionManager** | Implementation | ISubscriptionManager |||
| └ | subscriberSubscriptionCount | External ❗️ |   |NO❗️ |
| └ | subscriberSubscriptionByIndex | External ❗️ |   |NO❗️ |
| └ | subscriptionCount | External ❗️ |   |NO❗️ |
| └ | subscriptionByIndex | External ❗️ |   |NO❗️ |
||||||
| **SubscriptionManager** | Implementation | Ownable, ISubscriptionManager, IDelegatedSubscriptionManager, IEnumerableSubscriptionManager |||
| └ | \<Constructor\> | Internal 🔒 | 🛑  | |
| └ | isCancelled | External ❗️ |   |NO❗️ |
| └ | isActive | External ❗️ |   |NO❗️ |
| └ | nextPaymentTimestamp | External ❗️ |   |NO❗️ |
| └ | getSubscription | External ❗️ |   |NO❗️ |
| └ | cancel | External ❗️ | 🛑  |NO❗️ |
| └ | cancel | External ❗️ | 🛑  |NO❗️ |
| └ | executeBatch | External ❗️ | 🛑  |NO❗️ |
| └ | getActionHash | Public ❗️ |   |NO❗️ |
| └ | getSigner | Public ❗️ |   |NO❗️ |
| └ | execute | Public ❗️ | 🛑  |NO❗️ |
| └ | subscriberSubscriptionCount | Public ❗️ |   |NO❗️ |
| └ | subscriberSubscriptionByIndex | Public ❗️ |   |NO❗️ |
| └ | subscriberSubscriptionRange | External ❗️ |   |NO❗️ |
| └ | subscriptionCount | Public ❗️ |   |NO❗️ |
| └ | subscriptionByIndex | Public ❗️ |   |NO❗️ |
| └ | subscriptionRange | External ❗️ |   |NO❗️ |
| └ | _validateSubscriptionState | Internal 🔒 |   | |
| └ | _cancel | Internal 🔒 | 🛑  | |
| └ | _create | Internal 🔒 | 🛑  | |
| └ | _replayGuard | Internal 🔒 | 🛑  | |
| └ | _getPeriodUnitHash | Internal 🔒 |   | |
| └ | _removeFromArrayAndSwap | Private 🔐 | 🛑  | |
| └ | _paginate | Private 🔐 |   | |
||||||
| **PlanSubscriptionManager** | Implementation | SubscriptionManager |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | SubscriptionManager |
| └ | addPlan | External ❗️ | 🛑  | delegatedOwner |
| └ | removePlan | External ❗️ | 🛑  | delegatedOwner |
| └ | setActive | External ❗️ | 🛑  | delegatedOwner |
| └ | create | Public ❗️ | 🛑  |NO❗️ |
| └ | _validateSubscriptionState | Internal 🔒 |   | |
| └ | _addPlan | Internal 🔒 | 🛑  | |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
