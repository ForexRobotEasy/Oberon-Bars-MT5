# Oberon Bars MT5

Oberon Bars MT5 is a unique forex software developed for professional traders. This code represents a sample implementation of Oberon Bars MT5 and is not the official product developed by ForexRobotEasy. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of Oberon Bars MT5, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-oberon-bars-mt5-unique-forex-software-for-professional-traders/).

## Code Description

The code consists of several sections and functions that provide the necessary functionality for Oberon Bars MT5. Below is a description of each section and function:

### Expert Initialization Function - OnInit()

The `OnInit()` function is called when the expert advisor is initialized. It performs the following tasks:
- Initializes trading functions.
- Initializes symbol data for customization.
- Initializes repeat symbols functionality.
- Installs multiple instances of Oberon Bars MT5 with different settings.
- Sets M trading condition compatibility.

### Expert Deinitialization Function - OnDeinit(const int reason)

The `OnDeinit()` function is called when the expert advisor is deinitialized. It performs the following tasks:
- Deinitializes trading functions.
- Deinitializes symbol data.
- Deinitializes repeat symbols functionality.
- Uninstalls multiple instances of Oberon Bars MT5.
- Clears M trading condition compatibility.

### Expert Tick Function - OnTick()

The `OnTick()` function is called on every tick of the market. It executes the trading functions for each block. The number of blocks is defined by the `BLOCKS` constant.

### Initialize Trading Functions - InitTradeFunctions()

The `InitTradeFunctions()` function initializes the trading functions required for the expert advisor. This section contains the code for initializing trading functions.

### Initialize Symbol Data - InitSymbolData()

The `InitSymbolData()` function initializes the symbol data required for customization. This section contains the code for initializing symbol data.

### Initialize Repeat Symbols Functionality - InitRepeatSymbols()

The `InitRepeatSymbols()` function initializes the functionality for handling repeat symbols. This section contains the code for initializing repeat symbols functionality.

### Install Multiple Instances of Oberon Bars MT5 - InstallMultipleInstances()

The `InstallMultipleInstances()` function installs multiple instances of Oberon Bars MT5 with different settings. This section contains the code for installing multiple instances.

### Set M Trading Condition Compatibility - SetMTradingCondition()

The `SetMTradingCondition()` function sets the M trading condition compatibility. This section contains the code for setting M trading condition compatibility.

### Deinitialize Trading Functions - DeinitTradeFunctions()

The `DeinitTradeFunctions()` function deinitializes the trading functions. This section contains the code for deinitializing trading functions.

### Deinitialize Symbol Data - DeinitSymbolData()

The `DeinitSymbolData()` function deinitializes the symbol data. This section contains the code for deinitializing symbol data.

### Deinitialize Repeat Symbols Functionality - DeinitRepeatSymbols()

The `DeinitRepeatSymbols()` function deinitializes the functionality for handling repeat symbols. This section contains the code for deinitializing repeat symbols functionality.

### Uninstall Multiple Instances of Oberon Bars MT5 - UninstallMultipleInstances()

The `UninstallMultipleInstances()` function uninstalls multiple instances of Oberon Bars MT5. This section contains the code for uninstalling multiple instances.

### Clear M Trading Condition Compatibility - ClearMTradingCondition()

The `ClearMTradingCondition()` function clears the M trading condition compatibility. This section contains the code for clearing M trading condition compatibility.

### Execute Block Trading Function - ExecuteBlockTrading(const int blockIndex)

The `ExecuteBlockTrading()` function executes the block trading function for a specific block index. This section contains the code for executing block trading function.

## Disclaimer

This code is provided as a sample implementation of Oberon Bars MT5. ForexRobotEasy is not the official developer of this product. We only show the sample code that can work as described in the product. To find the official developer of Oberon Bars MT5, please refer to MQL5. For detailed reviews and trading results of Oberon Bars MT5, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-oberon-bars-mt5-unique-forex-software-for-professional-traders/).
