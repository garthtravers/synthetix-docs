# IIssuer

## Description

**Source:** [contracts/interfaces/IIssuer.sol](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol)

## Views

### `anySynthOrSNXRateIsInvalid`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L9)</sub>

??? example "Details"

    **Signature**

    `anySynthOrSNXRateIsInvalid() returns (bool)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `availableCurrencyKeys`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L11)</sub>

??? example "Details"

    **Signature**

    `availableCurrencyKeys() returns (bytes32[])`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `availableSynthCount`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L13)</sub>

??? example "Details"

    **Signature**

    `availableSynthCount() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `availableSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L15)</sub>

??? example "Details"

    **Signature**

    `availableSynths(uint256 index) returns (contract ISynth)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `canBurnSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L17)</sub>

??? example "Details"

    **Signature**

    `canBurnSynths(address account) returns (bool)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `collateral`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L19)</sub>

??? example "Details"

    **Signature**

    `collateral(address account) returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `collateralisationRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L21)</sub>

??? example "Details"

    **Signature**

    `collateralisationRatio(address issuer) returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `collateralisationRatioAndAnyRatesInvalid`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L23)</sub>

??? example "Details"

    **Signature**

    `collateralisationRatioAndAnyRatesInvalid(address _issuer) returns (uint256, bool)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `debtBalanceOf`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L28)</sub>

??? example "Details"

    **Signature**

    `debtBalanceOf(address issuer, bytes32 currencyKey) returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `getSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L49)</sub>

??? example "Details"

    **Signature**

    `getSynths(bytes32[] currencyKeys) returns (contract ISynth[])`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `issuanceRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L30)</sub>

??? example "Details"

    **Signature**

    `issuanceRatio() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `lastIssueEvent`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L32)</sub>

??? example "Details"

    **Signature**

    `lastIssueEvent(address account) returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `maxIssuableSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L34)</sub>

??? example "Details"

    **Signature**

    `maxIssuableSynths(address issuer) returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `minimumStakeTime`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L36)</sub>

??? example "Details"

    **Signature**

    `minimumStakeTime() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `remainingIssuableSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L38)</sub>

??? example "Details"

    **Signature**

    `remainingIssuableSynths(address issuer) returns (uint256, uint256, uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `synths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L47)</sub>

??? example "Details"

    **Signature**

    `synths(bytes32 currencyKey) returns (contract ISynth)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `synthsByAddress`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L51)</sub>

??? example "Details"

    **Signature**

    `synthsByAddress(address synthAddress) returns (bytes32)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `totalIssuedSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L53)</sub>

??? example "Details"

    **Signature**

    `totalIssuedSynths(bytes32 currencyKey, bool excludeEtherCollateral) returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `transferableSynthetixAndAnyRateIsInvalid`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L55)</sub>

??? example "Details"

    **Signature**

    `transferableSynthetixAndAnyRateIsInvalid(address account, uint256 balance) returns (uint256, bool)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

## External Functions

### `burnSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L73)</sub>

??? example "Details"

    **Signature**

    `burnSynths(address from, uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `burnSynthsOnBehalf`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L75)</sub>

??? example "Details"

    **Signature**

    `burnSynthsOnBehalf(address burnForAddress, address from, uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `burnSynthsToTarget`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L81)</sub>

??? example "Details"

    **Signature**

    `burnSynthsToTarget(address from)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `burnSynthsToTargetOnBehalf`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L83)</sub>

??? example "Details"

    **Signature**

    `burnSynthsToTargetOnBehalf(address burnForAddress, address from)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `issueMaxSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L69)</sub>

??? example "Details"

    **Signature**

    `issueMaxSynths(address from)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `issueMaxSynthsOnBehalf`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L71)</sub>

??? example "Details"

    **Signature**

    `issueMaxSynthsOnBehalf(address issueFor, address from)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `issueSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L61)</sub>

??? example "Details"

    **Signature**

    `issueSynths(address from, uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `issueSynthsOnBehalf`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L63)</sub>

??? example "Details"

    **Signature**

    `issueSynthsOnBehalf(address issueFor, address from, uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

### `liquidateDelinquentAccount`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/interfaces/IIssuer.sol#L85)</sub>

??? example "Details"

    **Signature**

    `liquidateDelinquentAccount(address account, uint256 susdAmount, address liquidator) returns (uint256, uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`
