# handleOf

Contract: [`JBProjects`](../)

Interface: [`IJBProjects`](../../../interfaces/ijbprojects.md)

**The unique handle for each project.**

_Each project must have a handle._

# Definition

```solidity
/** 
  @notice 
  The unique handle for each project.

  @dev
  Each project must have a handle.

  _projectId The ID of the project to which the handle belongs.
*/
mapping(uint256 => bytes32) public override handleOf;
```

* `_projectId` is the ID of the project to which the handle belongs.
* The resulting view function can be accessed externally by anyone.
* The resulting function overrides a function definition from the `IJBProjects` interface.
