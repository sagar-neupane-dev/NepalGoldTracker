# Nepal Gold Tracker 🏆

> A real-time gold and silver price tracker built specifically for the Nepali market.

Fetch live international spot prices, convert them to NPR/tola, and get a comprehensive breakdown of Nepal's tax structure including customs duty, luxury tax, and dealer margins. Prices update every 8 seconds with TradingView-style candlestick charts from 7 global exchanges.

**Live Demo:** [nepalgoldtracker.vercel.app](https://nepalgoldtracker.vercel.app)

---

## ✨ Features

- 📊 **Real-time Price Updates**: Live gold and silver prices refreshed every 8 seconds
- 💱 **Nepali Market Specific**: Automatic conversion to NPR/tola with accurate calculations
- 📈 **Interactive Charts**: TradingView-style candlestick charts for 7 global exchanges
- 🧮 **Complete Tax Breakdown**:
  - 10% Customs Duty
  - 2% Luxury Tax
  - Dealer Margins
- 💎 **Multi-Grade Support**: Accurate calculations for different gold purity grades
- ⚡ **Fast & Responsive**: Built on Next.js for optimal performance
- 🔄 **CI/CD Ready**: Deployed on Vercel with automated deployments

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **Frontend** | Next.js, JavaScript |
| **API Integration** | Kitco REST API |
| **Charts** | TradingView Finance Charts |
| **Deployment** | Vercel |
| **Version Control** | Git & GitHub |

---

## 📖 How It Works

### Price Calculation Flow

```
International Spot Price (from Kitco API)
         ↓
    USD to NPR Conversion
         ↓
    Per Tola Calculation
         ↓
    Tax & Duty Breakdown (10% + 2% + margin)
         ↓
    Final NPR/Tola Price
```

### Supported Metrics

- **Gold**: 24k, 22k, and 18k purity grades
- **Silver**: Direct conversion to NPR
- **Weight Units**: Grams, tola, and troy ounce calculations

---

## 💡 Key Implementation Details


### Unit Conversions

- **1 Tola** = 11.664 grams (Nepali standard)
- **1 Troy Ounce** = 31.1035 grams
- **1 USD to NPR** = Current exchange rate (API-driven)

### Chart Data Management

- Candlestick charts aggregate data from 7 global exchanges
- Supports multiple timeframes (1H, 4H, 1D, 1W)
- Real-time chart updates with smooth animations

---

## 📊 Project Statistics

- **Update Frequency**: Every 8 seconds
- **Supported Exchanges**: 7 global markets
- **Tax Categories**: 3 (customs, luxury, dealer margin)
- **Gold Grades**: 3 purity levels
- **Uptime**: 99%+ (Vercel deployment)

---

## 🎯 Use Cases

- 💰 **Jewelry Buyers**: Compare prices before purchasing gold
- 🏪 **Jewelry Retailers**: Real-time pricing for inventory management
- 📈 **Investors**: Track precious metal prices for portfolio decisions
- 💼 **Businesses**: Automated price feeds for websites/applications

---

## 🔄 Deployment

This project is deployed on **Vercel** with automatic CI/CD:

 Automated tests run (if configured)
 Build passes → Deploy to production
 Live at [nepalgoldtracker.vercel.app](https://nepal-gold-tracker.vercel.app/) 

---


### Bug Reports & Feature Requests

Found a bug or have a feature idea? Please open an [issue](https://github.com/sagar-neupane-dev/NepalGoldTracker/issues).

---


## 👨‍💻 About

Built by [Sagar Neupane](https://github.com/sagar-neupane-dev)

**Connect:**
- 🌐 [Portfolio](https://sagar-neupane.dev)
- 💼 [LinkedIn](https://linkedin.com/in/sagar-neupane)
- 🐙 [GitHub](https://github.com/sagar-neupane-dev)

---

## 🙏 Acknowledgments

- [Kitco](https://kitco.com) - Live precious metal price data
- [TradingView](https://www.tradingview.com) - Charting library
- [Vercel](https://vercel.com) - Hosting & deployment
- [Next.js](https://nextjs.org) - React framework


---

## 📸 Screenshots & Demo

Check out the live application: [nepalgoldtracker.qzz.io](https://www.nepalgoldtracker.qzz.io)

### Latest Updates

- ✅ Real-time price updates every 8 seconds
- ✅ USD and NPR global exchange charts
- ✅ Comprehensive tax breakdown
- ✅ Mobile responsive design
- ✅ Dark mode support

---
