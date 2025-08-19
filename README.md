# Show Pips Indicator for MetaTrader 4 & 5

A real-time position monitoring indicator that displays current pip profit/loss and time remaining until candle close. Essential tool for active traders to monitor performance without switching windows.

## Description

Real-time pip tracker showing current profit/loss and candle countdown for MT4/MT5. Color-coded display (blue profit/red loss) with customizable position. Perfect for scalping, day trading, and position monitoring. Combines pip tracking with precise timing for optimal trade management. Educational tool with risk warnings included.

The Show Pips indicator provides real-time monitoring by displaying:
- **Current Pip P&L**: Live calculation of profit/loss in pips for all open positions
- **Candle Countdown**: Time remaining until current candle closes
- **Color-Coded Display**: Automatic color change based on profit (blue) or loss (red)
- **Position Tracking**: Works with both buy and sell positions simultaneously
- **Clean Interface**: Automatically hides when no positions are open

This essential trading tool works on both MetaTrader 4 and MetaTrader 5 platforms, helping traders stay informed about their position performance and timing.

## Features

- ✅ Compatible with both **MetaTrader 4** and **MetaTrader 5**
- ✅ **Real-time pip tracking** for all open positions
- ✅ **Combined candle countdown** timer
- ✅ **Color-coded display** (profit/loss indication)
- ✅ **Multiple position support** (sums all positions)
- ✅ **Customizable positioning** (Upper Left or Upper Right)
- ✅ **Customizable colors** for profit and loss
- ✅ **Automatic cleanup** when no positions open
- ✅ **Works on all timeframes** and instruments
- ✅ **Non-intrusive display** that doesn't block chart analysis

## Installation

### For MetaTrader 5:
1. Download the `.mq5` file
2. Copy to: `MT5 Data Folder/MQL5/Indicators/`
3. Restart MT5 or refresh Navigator
4. Find "Show Pips" in Custom Indicators
5. Drag and drop onto your chart

### For MetaTrader 4:
1. Download the `.mq4` file
2. Copy to: `MT4 Data Folder/MQL4/Indicators/`
3. Restart MT4 or refresh Navigator
4. Find "Show Pips" in Custom Indicators
5. Drag and drop onto your chart

## Parameters

| Parameter | Default | Options | Description |
|-----------|---------|---------|-------------|
| `TextPosition` | UpperLeft | UpperLeft, UpperRight | Position of display on chart |
| `ProfitColor` | DodgerBlue | Any color | Text color when in profit |
| `LossColor` | Red | Any color | Text color when in loss |

## Display Format

**Color Coding:**
- 🔵 **Blue Text**: When account is in profit
- 🔴 **Red Text**: When account is in loss
- **No Display**: When no positions are open

## How It Works

### Pip Calculation
1. **Buy Positions**: (Current Price - Open Price) / Point Value
2. **Sell Positions**: (Open Price - Current Price) / Point Value
3. **Multiple Positions**: Sums pips from all open positions
4. **Real-time Updates**: Updates with every price tick

### Time Calculation
- **Standard Timeframes**: Shows HH:MM:SS format
- **Weekly/Monthly**: Shows "XD & HH:MM:SS" format
- **Real-time Countdown**: Updates every second

### Display Logic
- **Shows Only When Trading**: Appears only with open positions
- **Automatic Cleanup**: Removes display when all positions closed
- **Color Adaptation**: Changes color based on account profit/loss

## Trading Applications

### Position Monitoring
- **Real-time Tracking**: Monitor pip movement without switching windows
- **Quick Assessment**: Instant visual feedback on position performance
- **Multi-position View**: See combined performance of all trades

### Timing Decisions
- **Exit Timing**: Plan exits based on candle close timing
- **Entry Refinement**: Time new entries around candle formations
- **Risk Management**: Monitor both profit and time for decisions

### Scalping Strategies
- **Pip Targets**: Track progress toward pip goals
- **Quick Exits**: Monitor for rapid exit opportunities
- **Session Management**: Track performance during trading sessions

### Day Trading
- **Intraday Monitoring**: Keep track of daily pip performance
- **Candle Strategies**: Time trades around candle closes
- **Performance Tracking**: Real-time feedback on trading decisions

## Visual Display

### Format Examples
- **Profit Example**: `Current candle pip(s): +15  ||  Time to close: 00:02:30`
- **Loss Example**: `Current candle pip(s): -8  ||  Time to close: 00:05:15`
- **Large Profit**: `Current candle pip(s): +150  ||  Time to close: 00:01:45`

### Positioning
- **Upper Left**: Standard position (x=10, y=30)
- **Upper Right**: Alternative position for chart layouts
- **Font**: Arial, size 14 for optimal readability

## Use Cases by Trading Style

### Scalping
- Monitor small pip movements in real-time
- Quick decision making on exits
- Track session pip accumulation

### Day Trading
- Manage intraday positions effectively
- Time entries/exits around candle closes
- Monitor daily pip targets

### Swing Trading
- Track position development over time
- Manage longer-term positions
- Monitor weekly/monthly timeframes

### News Trading
- Monitor rapid pip movements during news
- Quick assessment of position impact
- Real-time profit/loss tracking

## Compatibility

| Platform | Version | Status |
|----------|---------|---------|
| MetaTrader 4 | Build 1380+ | ✅ Supported |
| MetaTrader 5 | Build 3440+ | ✅ Supported |
| All Timeframes | M1 to MN1 | ✅ Compatible |
| All Instruments | Forex, Stocks, Crypto, Commodities | ✅ Compatible |
| Position Types | Buy, Sell, Multiple | ✅ Compatible |

## Performance Features

- **Minimal CPU Usage**: Efficient calculation methods
- **Real-time Updates**: Updates with every tick
- **Memory Efficient**: Automatic object cleanup
- **Non-blocking**: Doesn't interfere with other indicators

## Usage Tips

### Best Practices
1. **Position appropriately** to avoid blocking important price levels
2. **Choose contrasting colors** for better visibility against chart background
3. **Use with stop losses** as this only shows unrealized P&L
4. **Monitor regularly** during active trading sessions

### Optimization
- **Color Selection**: Choose colors that stand out on your chart theme
- **Position Placement**: Place where it won't interfere with analysis
- **Timeframe Consideration**: More useful on shorter timeframes for active trading

## Version History

- **v1.05** - Enhanced stability and MT4/MT5 compatibility
- **v1.04** - Improved position tracking and pip calculation
- **v1.03** - Added automatic cleanup functionality
- **v1.02** - Enhanced color coding and display formatting
- **v1.01** - Initial release

## Technical Requirements

### Minimum System Requirements
- MetaTrader 4 (Build 1380+) or MetaTrader 5 (Build 3440+)
- Windows 7/8/10/11 or compatible system
- 10MB available storage space
- Active trading account with position access

## Advanced Features

### Multi-Position Support
- Automatically sums pips from all open positions
- Handles both buy and sell positions correctly
- Updates in real-time as positions change

### Intelligent Display
- Only appears when positions are open
- Automatically removes when all positions closed
- Adapts to different timeframe formats

### Color Intelligence
- Uses account profit status for color determination
- Provides instant visual feedback
- Customizable for personal preferences

## Risk Warning

⚠️ **Important Disclaimer**: 
- Trading involves substantial risk of loss
- This indicator shows unrealized profit/loss only
- Past performance doesn't guarantee future results
- Always use proper risk management
- Never risk more than you can afford to lose
- Pip profits can quickly turn to losses
- Use stop losses and position sizing
- This tool is for educational purposes only
- Consider seeking professional financial advice


## Support & Resources

- 🌐 **Website**: [TradingFinder.com](https://tradingfinder.com)
- 📊 **More Indicators**: [MT4/MT5 Products](https://tradingfinder.com/products/indicators/)
- 📚 **Trading Education**: Available on our website


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

**Developed by TFLab | TradingFinder.com**  
*Empowering traders with professional-grade technical analysis tools*
