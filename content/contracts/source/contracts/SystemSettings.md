# SystemSettings

## Description

**Source:** [contracts/SystemSettings.sol](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol)

## Architecture

### Libraries

- [SafeMath](/contracts/source/libraries/SafeMath) for `uint`
- [SafeDecimalMath](/contracts/source/libraries/SafeDecimalMath) for `uint`

### Inheritance Graph

```mermaid
graph TD
    SystemSettings[SystemSettings] --> MixinSystemSettings[MixinSystemSettings]
    MixinSystemSettings[MixinSystemSettings] --> MixinResolver[MixinResolver]
    MixinResolver[MixinResolver] --> Owned[Owned]

```

## Constants

### `MAX_EXCHANGE_FEE_RATE`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L37)</sub>

**Type:** `uint256`

### `MAX_FEE_PERIOD_DURATION`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L23)</sub>

**Type:** `uint256`

### `MAX_ISSUANCE_RATIO`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L19)</sub>

**Type:** `uint256`

### `MAX_LIQUIDATION_DELAY`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L33)</sub>

**Type:** `uint256`

### `MAX_LIQUIDATION_PENALTY`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L29)</sub>

**Type:** `uint256`

### `MAX_LIQUIDATION_RATIO`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L27)</sub>

**Type:** `uint256`

### `MAX_MINIMUM_STAKE_TIME`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L40)</sub>

**Type:** `uint256`

### `MAX_TARGET_THRESHOLD`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L25)</sub>

**Type:** `uint256`

### `MIN_FEE_PERIOD_DURATION`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L22)</sub>

**Type:** `uint256`

### `MIN_LIQUIDATION_DELAY`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L34)</sub>

**Type:** `uint256`

### `RATIO_FROM_TARGET_BUFFER`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L31)</sub>

**Type:** `uint256`

## Constructor

### `constructor`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L44)</sub>

??? example "Details"

    **Signature**

    `(address _owner, address _resolver)`

    **Visibility**

    `public`

    **State Mutability**

    `nonpayable`

## Views

### `aggregatorWarningFlags`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L122)</sub>

??? example "Details"

    **Signature**

    `aggregatorWarningFlags() returns (address)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `debtSnapshotStaleTime`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L118)</sub>

??? example "Details"

    **Signature**

    `debtSnapshotStaleTime() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `exchangeFeeRate`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L110)</sub>

??? example "Details"

    **Signature**

    `exchangeFeeRate(bytes32 currencyKey) returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `feePeriodDuration`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L77)</sub>

??? example "Details"

    **Signature**

    `feePeriodDuration() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `issuanceRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L69)</sub>

??? example "Details"

    **Signature**

    `issuanceRatio() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `liquidationDelay`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L88)</sub>

??? example "Details"

    **Signature**

    `liquidationDelay() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `liquidationPenalty`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L101)</sub>

??? example "Details"

    **Signature**

    `liquidationPenalty() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `liquidationRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L95)</sub>

??? example "Details"

    **Signature**

    `liquidationRatio() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `minimumStakeTime`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L114)</sub>

??? example "Details"

    **Signature**

    `minimumStakeTime() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `priceDeviationThresholdFactor`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L63)</sub>

??? example "Details"

    **Signature**

    `priceDeviationThresholdFactor() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `rateStalePeriod`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L106)</sub>

??? example "Details"

    **Signature**

    `rateStalePeriod() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `targetThreshold`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L82)</sub>

??? example "Details"

    **Signature**

    `targetThreshold() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `tradingRewardsEnabled`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L128)</sub>

??? example "Details"

    **Signature**

    `tradingRewardsEnabled() returns (bool)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `waitingPeriodSecs`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L56)</sub>

??? example "Details"

    **Signature**

    `waitingPeriodSecs() returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

## Restricted Functions

### `setAggregatorWarningFlags`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L246)</sub>

??? example "Details"

    **Signature**

    `setAggregatorWarningFlags(address _flags)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., Valid address must be given)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L247)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [AggregatorWarningFlagsUpdated](#aggregatorwarningflagsupdated)

### `setDebtSnapshotStaleTime`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L241)</sub>

??? example "Details"

    **Signature**

    `setDebtSnapshotStaleTime(uint256 _seconds)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [DebtSnapshotStaleTimeUpdated](#debtsnapshotstaletimeupdated)

### `setExchangeFeeRateForSynths`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L219)</sub>

??? example "Details"

    **Signature**

    `setExchangeFeeRateForSynths(bytes32[] synthKeys, uint256[] exchangeFeeRates)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., Array lengths dont match)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L223)

    **Modifiers**

    * [onlyOwner](#onlyowner)

### `setFeePeriodDuration`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L159)</sub>

??? example "Details"

    **Signature**

    `setFeePeriodDuration(uint256 _feePeriodDuration)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., value < MIN_FEE_PERIOD_DURATION)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L160)

    * [require(..., value > MAX_FEE_PERIOD_DURATION)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L161)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [FeePeriodDurationUpdated](#feeperioddurationupdated)

### `setIssuanceRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L153)</sub>

??? example "Details"

    **Signature**

    `setIssuanceRatio(uint256 _issuanceRatio)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., New issuance ratio cannot exceed MAX_ISSUANCE_RATIO)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L154)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [IssuanceRatioUpdated](#issuanceratioupdated)

### `setLiquidationDelay`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L178)</sub>

??? example "Details"

    **Signature**

    `setLiquidationDelay(uint256 time)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., Must be less than 30 days)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L179)

    * [require(..., Must be greater than 1 day)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L180)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [LiquidationDelayUpdated](#liquidationdelayupdated)

### `setLiquidationPenalty`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L205)</sub>

??? example "Details"

    **Signature**

    `setLiquidationPenalty(uint256 penalty)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., penalty > MAX_LIQUIDATION_PENALTY)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L206)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [LiquidationPenaltyUpdated](#liquidationpenaltyupdated)

### `setLiquidationRatio`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L189)</sub>

??? example "Details"

    **Signature**

    `setLiquidationRatio(uint256 _liquidationRatio)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., liquidationRatio > MAX_LIQUIDATION_RATIO / (1 + penalty))](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L190)

    * [require(..., liquidationRatio < MIN_LIQUIDATION_RATIO)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L198)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [LiquidationRatioUpdated](#liquidationratioupdated)

### `setMinimumStakeTime`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L235)</sub>

??? example "Details"

    **Signature**

    `setMinimumStakeTime(uint256 _seconds)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., stake time exceed maximum 1 week)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L236)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [MinimumStakeTimeUpdated](#minimumstaketimeupdated)

### `setPriceDeviationThresholdFactor`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L144)</sub>

??? example "Details"

    **Signature**

    `setPriceDeviationThresholdFactor(uint256 _priceDeviationThresholdFactor)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [PriceDeviationThresholdUpdated](#pricedeviationthresholdupdated)

### `setRateStalePeriod`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L213)</sub>

??? example "Details"

    **Signature**

    `setRateStalePeriod(uint256 period)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [RateStalePeriodUpdated](#ratestaleperiodupdated)

### `setTargetThreshold`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L168)</sub>

??? example "Details"

    **Signature**

    `setTargetThreshold(uint256 _percent)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Requires**

    * [require(..., Threshold too high)](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L169)

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [TargetThresholdUpdated](#targetthresholdupdated)

### `setTradingRewardsEnabled`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L134)</sub>

??? example "Details"

    **Signature**

    `setTradingRewardsEnabled(bool _tradingRewardsEnabled)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [TradingRewardsEnabled](#tradingrewardsenabled)

### `setWaitingPeriodSecs`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L139)</sub>

??? example "Details"

    **Signature**

    `setWaitingPeriodSecs(uint256 _waitingPeriodSecs)`

    **Visibility**

    `external`

    **State Mutability**

    `nonpayable`

    **Modifiers**

    * [onlyOwner](#onlyowner)

    **Emits**

    * [WaitingPeriodSecsUpdated](#waitingperiodsecsupdated)

## Events

### `AggregatorWarningFlagsUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L266)</sub>

**Signature**: `AggregatorWarningFlagsUpdated(address flags)`

### `DebtSnapshotStaleTimeUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L265)</sub>

**Signature**: `DebtSnapshotStaleTimeUpdated(uint256 debtSnapshotStaleTime)`

### `ExchangeFeeUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L263)</sub>

**Signature**: `ExchangeFeeUpdated(bytes32 synthKey, uint256 newExchangeFeeRate)`

### `FeePeriodDurationUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L257)</sub>

**Signature**: `FeePeriodDurationUpdated(uint256 newFeePeriodDuration)`

### `IssuanceRatioUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L256)</sub>

**Signature**: `IssuanceRatioUpdated(uint256 newRatio)`

### `LiquidationDelayUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L259)</sub>

**Signature**: `LiquidationDelayUpdated(uint256 newDelay)`

### `LiquidationPenaltyUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L261)</sub>

**Signature**: `LiquidationPenaltyUpdated(uint256 newPenalty)`

### `LiquidationRatioUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L260)</sub>

**Signature**: `LiquidationRatioUpdated(uint256 newRatio)`

### `MinimumStakeTimeUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L264)</sub>

**Signature**: `MinimumStakeTimeUpdated(uint256 minimumStakeTime)`

### `PriceDeviationThresholdUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L255)</sub>

**Signature**: `PriceDeviationThresholdUpdated(uint256 threshold)`

### `RateStalePeriodUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L262)</sub>

**Signature**: `RateStalePeriodUpdated(uint256 rateStalePeriod)`

### `TargetThresholdUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L258)</sub>

**Signature**: `TargetThresholdUpdated(uint256 newTargetThreshold)`

### `TradingRewardsEnabled`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L253)</sub>

**Signature**: `TradingRewardsEnabled(bool enabled)`

### `WaitingPeriodSecsUpdated`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.35.0-ovm/contracts/SystemSettings.sol#L254)</sub>

**Signature**: `WaitingPeriodSecsUpdated(uint256 waitingPeriodSecs)`
