# ISupplySchedule

## Description

**Source:** [contracts/interfaces/ISupplySchedule.sol](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/ISupplySchedule.sol)

## Views

### `isMintable`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/ISupplySchedule.sol#L9)</sub>

??? example "Details"

    **Signature**

    `isMintable() returns (bool)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `mintableSupply`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/ISupplySchedule.sol#L7)</sub>

??? example "Details"

    **Signature**

    `mintableSupply() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

## External Functions

### `recordMintEvent`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/ISupplySchedule.sol#L12)</sub>

??? example "Details"

    **Signature**

    `recordMintEvent(uint256 supplyMinted) returns (bool)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`
