| Name               | Type                                           | Slot | Offset | Bytes | Contract                                                     |
|--------------------|------------------------------------------------|------|--------|-------|--------------------------------------------------------------|
| strategyBeacon     | contract IBeacon                               | 0    | 0      | 20    | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| deployedStrategies | mapping(contract IERC20 => contract IStrategy) | 1    | 0      | 32    | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| isBlacklisted      | mapping(contract IERC20 => bool)               | 2    | 0      | 32    | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| __gap              | uint256[48]                                    | 3    | 0      | 1536  | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| _initialized       | uint8                                          | 51   | 0      | 1     | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| _initializing      | bool                                           | 51   | 1      | 1     | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| __gap              | uint256[50]                                    | 52   | 0      | 1600  | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| _owner             | address                                        | 102  | 0      | 20    | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| __gap              | uint256[49]                                    | 103  | 0      | 1568  | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| pauserRegistry     | contract IPauserRegistry                       | 152  | 0      | 20    | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| _paused            | uint256                                        | 153  | 0      | 32    | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
| __gap              | uint256[48]                                    | 154  | 0      | 1536  | src/contracts/strategies/StrategyFactory.sol:StrategyFactory |
