# Changelog

## [1.0.2] (23.09.2026)

### Added

- SPI clk of ADS A and ADS B are now disconnected when their respective CS is not low. This is done with MUX U5 (SN74AUP2G125YZPR).

### Fixed

- Unintended clear of the data ready signal of ADS A and B fixed by clk disconnection.


## [1.0.1] (14.05.2026)

### Added

### Changed

- Clock source of ADS1298 is fixed to external oscillator
- Pin from board-to-board connector nRF_P0.05 is not used anymore for clk source selection

## [1.0.0] (03.07.2025)
- Inital version
