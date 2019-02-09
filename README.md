# Exchange
Exchange anything to anything.

Pair = quote asset + base asset.

Roles: traders/clients OR users.

## Model:
Ads OR Requests.

### Ads (clients/traders)
Traders update every minute manually or via API and fight for best prices always keeping prices cheap.
Clients see best price at any moment.

### Requests (clients/traders = users)
Traders wait for requests and then fight for prices. (Updating, matching, notifying).
Clients wait for the best price to appear.

### Languages
EN, RU


## Information flow
Database > Bot / API > Web

### Bot (Telegram)
Source: Database

### API (WebSocket)
Source: Database

### Web (JS, Design)
Source: API
