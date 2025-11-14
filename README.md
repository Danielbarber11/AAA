# 👨‍🍳 The Virtual Chef - AI Recipe Generator

Generate creative, personalized recipes with the power of artificial intelligence. Simply describe your ingredients or dietary preferences, and our AI chef will create unique recipes tailored just for you.

## 🌟 Features

- **AI-Powered Recipe Generation**: Uses Google Gemini 2.5 to create original recipes
- **Hebrew Interface**: Full right-to-left (RTL) language support with beautiful Hebrew typography
- **Search Integration**: AI can search the web for real-time ingredient information
- **Smart Actions**:
  - Shorten recipes for quick viewing
  - Find ingredient substitutions
  - Get alternative recipe variations
- **Accessibility Features**:
  - High contrast mode for better visibility
  - Adjustable text size
  - Link highlighting
  - ARIA-compliant interface
- **Recipe Library**: Quick-access buttons for popular recipes
- **Mobile Responsive**: Works seamlessly on desktop and mobile devices

## 🚀 Live Demo

Visit the live site: [The Virtual Chef](https://danielbarber11.github.io/AAA/)

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **AI Engine**: Google Gemini 2.5 Flash Preview API
- **Hosting**: GitHub Pages
- **Language Support**: Hebrew (RTL), English fallback

## 📖 How to Use

1. **Visit the Site**: Open [The Virtual Chef](https://danielbarber11.github.io/AAA/) in your browser
2. **Accept Terms**: Read and accept the disclaimer
3. **Enter Your Request**: Type a recipe request (e.g., "recipes with eggs", "vegan dishes")
4. **Get Your Recipe**: The AI will generate a custom recipe with ingredients and instructions
5. **Customize**:
   - Click "Shorten" for a quick version
   - Click "Find Substitution" to replace an ingredient
   - Click "Get Variation" for an alternative recipe

## 🔐 API Key Configuration

The application uses Google Gemini API. The API key is securely stored in localStorage during the first page load.

### Development

For local development, you need:
- A valid Google Gemini API key ([Get one here](https://ai.google.dev/))
- The key will be automatically initialized on page load
- For deployment, ensure your GitHub Pages domain is whitelisted in your Google API Console

## 🎨 Customization

All styling uses Tailwind CSS. To customize:
1. Edit the CSS classes in the `<style>` section of `index.html`
2. Modify the recipe pool in the `RECIPE_POOL` constant
3. Adjust the system prompt in the `callGeminiApi()` function

## 📱 Browser Support

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

For issues or suggestions, please open an issue or contact the maintainer.

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Developer

Created with ❤️ for Hebrew-speaking users who love cooking and AI

---

**Keywords**: Recipe Generator, AI Chef, Hebrew, Gemini API, Cooking Assistant, Recipe Search