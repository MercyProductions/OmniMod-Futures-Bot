# Configuration reference

Generated from `new-bots/futures/.env.example`. Copy the template, never another person's `.env`. Template defaults are starting settings, not account/risk recommendations. Read its comments and source before changing a safety control.

| Variable | Template default | Role |
| --- | --- | --- |
| `DISCORD_TOKEN` | your own value; optional when its source is disabled | Private credential from your own account/application. |
| `DISCORD_CLIENT_ID` | your own value; optional when its source is disabled | Your own server/application/account identifier. |
| `DISCORD_GUILD_ID` | your own value; optional when its source is disabled | Your own server/application/account identifier. |
| `DISCORD_CHANNEL_ID` | your own value; optional when its source is disabled | Your own server/application/account identifier. |
| `DISCORD_DELIVERY_MODE` | bot | Runtime, data-source, cost, review or safety setting; see template comments. |
| `SCAN_TIMEOUT_MINUTES` | 20 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_SOURCE` | manual | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_POSITION_MARK_SOURCE` | manual | Runtime, data-source, cost, review or safety setting; see template comments. |
| `DATABENTO_API_KEY` | your own value; optional when its source is disabled | Private credential from your own account/application. |
| `DATABENTO_DATASET` | GLBX.MDP3 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_CONTRACT_DISCOVERY_ENABLED` | false | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_CONTRACT_DISCOVERY_SCOPE` | dataset | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_CONTRACT_DISCOVERY_CACHE` | data/futures-contract-discovery.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_CONTRACT_DISCOVERY_CACHE_MINUTES` | 360 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_DISCOVERY_ENABLED` | false | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_DISCOVERY_CACHE` | data/futures-activity-screen.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_MAX_CANDIDATES` | 20 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_MAX_CONTRACTS_PER_ROOT` | 1 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_LOOKBACK_MINUTES` | 30 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_MAX_BAR_AGE_MS` | 180000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_ANALYSIS_ENABLED` | false | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_REVIEW_FILE` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ACTIVITY_MAX_ANALYSIS` | 10 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_SCAN_COST_USD` | 0 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_DATA_MAX_AGE_SECONDS` | 180 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_FILE` | examples/futures.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_DAY_SESSION_FILE` | examples/day-session.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_TREND_DATA_SOURCE` | manual | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_H1_LOOKBACK_DAYS` | 7 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_H1_MIN_BARS` | 50 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_H1_CACHE` | data/futures-h1-history.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_CATALYST_SOURCE` | manual | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FINNHUB_API_KEY` | your own value; optional when its source is disabled | Private credential from your own account/application. |
| `FUTURES_DAY_DATA_SOURCE` | manual | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_PRIMARY_SIGNAL_MAX_AGE_MS` | 300000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `OMNIMOD_SIGNAL_RESEARCH_PATH` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `OMNIMOD_FORWARD_SHADOW_STATE_DIR` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `MAX_FUTURES` | 36 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `MAX_FUTURE_AGE_MINUTES` | 30 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_QUOTE_AGE_MS` | 5000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_OPEN_MARK_AGE_MS` | 300000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_POSITION_QUOTE_AGE_MS` | 5000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_TRANSPORT_LAG_MS` | 2000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_LIVE_QUOTE_TIMEOUT_MS` | 8000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_LIVE_SESSION_TIMEOUT_MS` | 30000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MIN_ENTRY_BOOK_SIZE` | 1 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_SPREAD_PCT` | 0.05 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_TRADE_RISK_PCT` | 0.25 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_TOTAL_OPEN_RISK_PCT` | 1 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_GROSS_EXPOSURE_PCT` | 500 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_DAILY_LOSS_PCT` | 1 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MIN_REWARD_RISK` | 1.5 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_MAX_INITIAL_MARGIN_PCT` | 25 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_DELIVERY_ENTRY_BUFFER_HOURS` | 24 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_ROUND_TRIP_FEES_PER_CONTRACT` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FUTURES_SLIPPAGE_RESERVE_PER_CONTRACT` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `PAPER_ACCOUNT_EQUITY_USD` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `OMNIMOD_EMERGENCY_STOP` | true | Runtime, data-source, cost, review or safety setting; see template comments. |
| `OMNIMOD_LIVE_TRADING_ENABLED` | false | Runtime, data-source, cost, review or safety setting; see template comments. |
| `TRADING_RISK_STATE_PATH` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `SCAN_INTERVAL_MINUTES` | 15 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `DISCORD_ALERT_COOLDOWN_MINUTES` | 60 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `DISCORD_WEBHOOK_USERNAME` | OmniMod Futures | Runtime, data-source, cost, review or safety setting; see template comments. |
| `DISCORD_WEBHOOK_AVATAR_URL` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `DISCORD_WEBHOOK_URL` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `PAPER_MONITOR_INTERVAL_SECONDS` | 0 | Runtime, data-source, cost, review or safety setting; see template comments. |
