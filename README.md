# Trading Dashboard

Personal options trading dashboard for ThinkorSwim account statements.

## Setup

1. Fork or clone this repo
2. Go to **Settings → Pages** in your GitHub repo
3. Set source to **Deploy from a branch → main → / (root)**
4. Your dashboard will be live at `https://yourusername.github.io/trading-dashboard`

## Usage

- Open the dashboard URL in any browser
- Drag and drop TOS Account Statement CSVs onto the upload zone
- Multiple files merge automatically (handles cross-month positions)
- Data persists in browser localStorage between visits

## Updating data each month

1. Export a new Account Statement from ThinkorSwim (Monitor → Account Statement → Export)
2. Open your dashboard URL
3. Drop the new CSV onto the upload zone alongside previous months

## Accounts

- **Individual Account** — taxable brokerage
- **Roth IRA** — tax-advantaged
- **Combined View** — both accounts overlaid on one equity curve

## Privacy

All data is processed locally in your browser. No data is sent to any server.
