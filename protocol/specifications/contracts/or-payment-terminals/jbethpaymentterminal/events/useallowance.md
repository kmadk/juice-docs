# UseAllowance

Emitted from:

* [`useAllowanceOf`](../write/useallowanceof.md)

# Definition

```solidity
event UseAllowance(
  uint256 indexed fundingCycleConfiguration,
  uint256 indexed fundingCycleNumber,
  uint256 indexed projectId,
  address beneficiary,
  uint256 amount,
  uint256 feeAmount,
  uint256 transferAmount,
  address caller
);
```

* `fundingCycleConfiguration` is the funding cycle configuration during which an allowance was used.
* `fundingCycleNumber` is the number of the funding cycle during which an allowance was used.
* `projectId` is the ID of the project whose allowance was used.
* `beneficiary` is the address whose received the allowance.
* `amount` is the amount of allowance that was used in terms of the funding cycle's currency.
* `feeAmount` is the amount of ETH protocol fees that were taken from the used allowance.
* `transferAmount` is the amount of ETH that was transfered to the beneficiary.
* `caller` is the address that issued the transaction within which the event was emitted.
