# 🌿 Alice Storyteller 📚

A smart cultural storytelling web application that generates immersive stories from different cultures around the world. Built with vanilla HTML, CSS, and JavaScript for educational and cultural preservation purposes.

## ✨ Features

### 🌍 Multi-Cultural Stories
- **7 Cultural Backgrounds**: Indian, African, European, Native American, East Asian, Middle Eastern, Latin American
- **5 Story Types**: Folk Tales, Myths & Legends, Moral Stories, Historical Fiction, Animal Fables
- **Authentic Content**: Culturally accurate stories with traditional themes

### 🎨 Rich Visual Experience
- **Dynamic Art Styles**: Watercolor, Digital Art, Oil Painting, Pencil Sketch, Minimalist Vector
- **Auto-Generated Images**: Visual scenes that match your story content
- **Responsive Design**: Beautiful UI that works on all devices

### 🔊 Audio Narration
- **Text-to-Speech**: Built-in narration using Web Speech API
- **Multi-Language Support**: English, Hindi, Spanish, French, Japanese
- **Storytelling Pace**: Optimized speech rate for immersive listening

### 📝 Interactive Features
- **Editable Stories**: Modify and customize generated content
- **Save & Export**: Download stories as text files
- **Copy to Clipboard**: Easy sharing functionality
- **Real-time Suggestions**: Cultural recommendations based on selections

## 🚀 Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- Internet connection (for image generation)

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start generating stories!

```bash
# If using a local server (optional)
python -m http.server 8000
# or
npx serve .
```

## 🎯 How to Use

1. **Select Culture**: Choose from 7 different cultural backgrounds
2. **Pick Story Type**: Select the type of story you want to hear
3. **Choose Language**: Pick your preferred narration language
4. **Set Art Style**: Select visual style for story illustrations
5. **Add Custom Topic** (Optional): Specify a particular theme or character
6. **Generate**: Click "Generate Story" and watch the magic happen!

### Story Controls
- **🔊 Play Narration**: Listen to your story with text-to-speech
- **🖼️ New Image**: Generate a fresh visual for your story
- **💾 Save File**: Download your story as a text file
- **📋 Copy**: Copy story text to clipboard

## 🏗️ Project Structure

```
alice-storyteller/
├── index.html          # Main application file
├── README.md          # Project documentation
└── assets/            # (Future: images, fonts, etc.)
```

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic structure and accessibility
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: No frameworks, pure JS functionality
- **Web Speech API**: For text-to-speech narration
- **Picsum Photos**: Placeholder images (can be replaced with AI image generation)

### Key Components
- **Story Database**: Pre-written cultural stories organized by type
- **Dynamic UI**: Responsive controls and real-time feedback
- **Audio System**: Web Speech API integration with language support
- **File Export**: Client-side file generation and download

## 🎨 Customization

### Adding New Stories
Edit the `storyDatabase` object in the JavaScript section:

```javascript
const storyDatabase = {
    "your_culture": {
        "story_type": [
            { 
                title: "Your Story Title", 
                content: "Your story content here..." 
            }
        ]
    }
};
```

### Styling
Modify CSS custom properties in the `:root` selector:

```css
:root {
    --primary-color: #8B4513;    /* Main theme color */
    --accent-color: #DAA520;     /* Accent highlights */
    --bg-color: #FDFBF7;        /* Background */
    /* ... more variables */
}
```

## 🌟 Future Enhancements

- [ ] Integration with AI APIs (OpenAI, Anthropic) for dynamic story generation
- [ ] Real AI image generation (DALL-E, Midjourney API)
- [ ] User accounts and story collections
- [ ] Social sharing features
- [ ] More cultural backgrounds and languages
- [ ] Audio recording and playback
- [ ] Story rating and feedback system

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Add Stories**: Contribute authentic cultural stories
2. **Improve Translations**: Help with language accuracy
3. **Enhance UI/UX**: Suggest design improvements
4. **Bug Reports**: Report issues and bugs
5. **Feature Requests**: Suggest new functionality

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📜 Cultural Sensitivity

This project aims to respectfully represent diverse cultures. We strive for:
- **Authenticity**: Stories based on traditional folklore and values
- **Respect**: Avoiding stereotypes and cultural appropriation
- **Education**: Promoting cultural understanding and appreciation
- **Accuracy**: Researched content with cultural context

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Aditya Singh Rajput** 🧿
- Built for educational and cultural preservation
- Passionate about technology and storytelling

## 🙏 Acknowledgments

- Traditional storytellers and cultural historians
- Open source community for tools and inspiration
- Cultural communities for sharing their heritage
- Web Speech API and modern browser capabilities

---

*"Every culture has stories that deserve to be told and preserved for future generations."*

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check the browser console for error messages
- Ensure your browser supports Web Speech API
- Verify internet connection for image loading

**Happy Storytelling! 📚✨**
