# Pine Script v6 Course | دورة Pine Script

An Arabic-friendly learning repository that moves from Pine Script fundamentals to practical TradingView indicators and strategy prototypes.

مستودع تعليمي عملي يبدأ من أساسيات Pine Script v6 وينتقل تدريجيًا إلى بناء مؤشرات واستراتيجيات قابلة للتجربة على TradingView.

## Learning outcomes | مخرجات التعلم

By working through the examples, learners practice:

- Pine v6 script structure, inputs, plots, conditions, and alerts.
- Trend and momentum tools such as EMA, RSI, and MACD.
- Liquidity zones, market structure, and risk-aware signal design.
- Strategy construction and responsible backtest interpretation.
- Debugging compile errors and documenting repainting/live-bar behavior.

## Repository map | محتويات المستودع

| Area | Purpose |
|---|---|
| `session-1` | Guided introductory examples and early exercises. |
| Root `*.pine` files | Larger practical indicators and strategy projects. |
| `ai-dynamic-liquidity-engine-v2.pine` | Liquidity-engine project with a valid Pine filename. |
| `ultimate-scalping-pro-v2.6.pine` | Scalping strategy research example. |

The repository currently contains **16 Pine scripts**. The empty placeholder `indicator.txt` was removed, and the extensionless liquidity project was renamed to a standard `.pine` file so editors and automated checks recognize it correctly.

## Suggested learning path | المسار المقترح

1. Start with script declarations, inputs, and plots in `session-1`.
2. Add conditional colors, signals, and alerts.
3. Study EMA/RSI confirmation and distinguish closed-bar logic from live-bar behavior.
4. Review liquidity and structure concepts in the larger projects.
5. Run strategies on more than one symbol and timeframe.
6. Record commission, slippage, sample size, drawdown, and out-of-sample results before drawing conclusions.

## Running an example

1. Open a `.pine` file and copy it into the TradingView Pine Editor.
2. Confirm that the version declaration is `//@version=6` where applicable.
3. Select the intended symbol and timeframe.
4. Click **Add to chart** and review any compile message.
5. Treat a successful compile as software validation only—not proof of profitability.

## Project status

This is an evolving educational repository. Examples may have different levels of completeness and should be reviewed in sequence. Automated checks validate Pine declarations and local documentation links on every push and pull request.

For fully documented TradingView screenshots and test reports, visit the [EGX indicators and strategies repository](https://github.com/Alaamo7/pine-script-indicators). For a concise five-project showcase, see the [Pine Script portfolio](https://github.com/Alaamo7/pine-script-portfolio).

## License and disclaimer

The material is available for portfolio viewing and personal education. Redistribution, resale, modification, or commercial use requires written permission; see [LICENSE](LICENSE). Nothing in this repository is financial advice, and historical results do not guarantee future performance.
