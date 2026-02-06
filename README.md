# Has Donald Trump Got a Nobel Prize? 🏆

A beautiful, modern web application that answers the burning question: **Has Donald Trump received a Nobel Prize?**

The app queries the official Nobel Prize API in real-time to provide a definitive answer backed by actual data.

![Modern UI](https://img.shields.io/badge/UI-Modern-blueviolet)
![Glassmorphism](https://img.shields.io/badge/Design-Glassmorphism-ff69b4)
![API](https://img.shields.io/badge/Data-Nobel%20Prize%20API-gold)

## ✨ Features

- **Real-time verification** - Fetches live data from the official Nobel Prize API
- **Super modern UI** - Glassmorphism design with smooth animations
- **Responsive** - Works perfectly on desktop, tablet, and mobile
- **No dependencies** - Pure HTML, CSS, and JavaScript
- **Instant results** - Get the answer in seconds

## 🎨 Design Highlights

- Animated gradient background with floating orbs
- Frosted glass (glassmorphism) UI elements
- Smooth transitions and micro-interactions
- Clean, modern typography using Inter font
- Pulse indicators and loading animations
- Statistical data visualization

## 🚀 Live Demo

Simply open `trump-nobel-checker.html` in any modern web browser!

## 📋 How It Works

1. The app connects to `http://api.nobelprize.org/2.1/laureates`
2. It searches through all Nobel Prize laureates in the database
3. It checks for any variation of "Donald Trump" in the records
4. It displays a clear **YES** or **NO** answer with supporting data

The search covers all six Nobel Prize categories:
- Physics
- Chemistry  
- Medicine
- Literature
- Peace
- Economic Sciences

## 🛠️ Installation

No installation required! Just download and open:

```bash
# Clone the repository
git clone https://github.com/yourusername/trump-nobel-checker.git

# Open the HTML file
open index.html
```

## 💻 Technical Details

- **No frameworks** - Pure vanilla JavaScript
- **No build process** - Works right out of the box
- **API**: Nobel Prize API v2.1
- **Browser support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## 📊 What the App Shows

### If Found (Hypothetical):
- ✅ Confirmation message
- Full name of the laureate
- Prize category
- Year awarded
- Official motivation

### If Not Found (Current Reality):
- ❌ Clear "NO" answer
- Total number of laureates searched
- Verification timestamp
- Detailed explanation

## 🎯 Use Cases

- Fact-checking claims
- Educational demonstrations
- Understanding API integration
- Modern web design reference
- Quick verification tool

## 🔧 Customization

Want to check for someone else? Just modify the search array in the JavaScript:

```javascript
const trumpVariations = [
    'donald trump',
    'trump, donald',
    'd. trump',
    'donald j. trump',
    'donald john trump'
];
```

Replace with any name you want to search for!

## 📱 Screenshots

The app features:
- Animated gradient background
- Glassmorphic cards
- Real-time data statistics
- Smooth loading states
- Clear visual answers

## 🌐 API Reference

This project uses the official Nobel Prize API:
- **Endpoint**: `http://api.nobelprize.org/2.1/laureates`
- **Documentation**: [NobelPrize.org API](https://www.nobelprize.org/about/developer-zone-2/)
- **No API key required**
- **Free to use**

## ⚡ Performance

- Lightweight: ~15KB total size
- Fast loading: < 1 second
- Efficient API calls: Single request
- No external dependencies

## 🤝 Contributing

Feel free to fork this project and make it your own! Some ideas:
- Add more search variations
- Include historical Nobel Prize statistics
- Add a search input for any name
- Implement caching for faster results
- Add dark mode toggle

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Credits

- Data source: [NobelPrize.org](https://www.nobelprize.org/)
- Design inspiration: Modern glassmorphism trends
- Font: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts

## ❓ FAQ

**Q: Is this data accurate?**  
A: Yes! The app pulls directly from the official Nobel Prize API maintained by the Nobel Foundation.

**Q: How often is the data updated?**  
A: The API is updated by the Nobel Foundation and reflects the official records.

**Q: Can I use this for other people?**  
A: Absolutely! Just modify the search terms in the code.

**Q: Does this work offline?**  
A: No, it requires an internet connection to fetch data from the Nobel Prize API.

**Q: Why did you make this?**  
A: To demonstrate modern web design, API integration, and provide a factual, verifiable answer to a common question.

---

**Made with ❤️ and modern web technologies**

*Answer: No, Donald Trump does not have a Nobel Prize (as of the latest API data).*
