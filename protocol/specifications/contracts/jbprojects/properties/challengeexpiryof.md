# challengeExpiryOf

Contract: [`JBProjects`](../)

Interface: [`IJBProjects`](../../../interfaces/ijbprojects.md)

**The timestamps after which each handle can be openly claimed.**

_A value of 0 means a handle isn't yet being challenged._

# Definition

```solidity
/** 
  @notice 
  The timestamps after which each handle can be openly claimed. 

  @dev
  A value of 0 means a handle isn't yet being challenged.

  _handle The handle to look for the challenge expiry of.
*/
mapping(bytes32 => uint256) public override challengeExpiryOf;
```

* `_handle` is the handle to look for the challenge expiry of.
* The resulting view function can be accessed externally by anyone.
* The resulting function overrides a function definition from the `IJBProjects` interface.
