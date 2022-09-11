# Changelog

## Apibara 0.3.3

### Added

 - Add configuration from prefixed environment variables


## Apibara 0.3.2

### Added

 - Update compatibility with StarkNet 0.10


## Apibara 0.3.1

### Added

 - Include transaction hash in events.


## Apibara 0.3.0

### Added

 - Support EVM-compatible networks.

### Changed

 - Support configurable networks. Now developers can specify local test networks.

### Fixed

 - More reliable connection handling.
 - Graceful indexer shutdown.


## Apibara 0.2.0

### Changed

 - Send `BlockHeader` with `NewEvents`.
 - Send crate version to clients on connect.
 - Use `starknet-rs` to connect to StarkNet.
 - Indexer state is updated when a block range has no events in it.

### Fixed

 - Detect chain reorganizations and send reorganization message to clients.


## Apibara 0.1.2 (2022-06-30)

### Added

 - Support multiple filters per indexer


## Apibara 0.1.1 (2022-06-28)

### Added

 - Manage indexers
 - Stream block events to indexers
 - Index data from StarkNet