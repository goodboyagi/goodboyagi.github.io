# Greeting Card Generator

An AI-powered greeting card generator that creates personalized cards using generative AI technology.

## 🎯 About

This project uses advanced language models and image generation to create unique, personalized greeting cards. Users can input their message, select a style, and generate beautiful cards for any occasion.

## 🚀 Features

- **AI-Powered Text Generation**: Creates personalized messages using language models
- **Style Selection**: Multiple card styles and themes
- **Customizable Content**: User-defined messages and preferences
- **High-Quality Output**: Professional-looking greeting cards
- **Easy Sharing**: Export and share generated cards

## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: OpenAI API / Hugging Face
- **Image Generation**: DALL-E / Stable Diffusion
- **Backend**: Python (Flask/FastAPI)
- **Deployment**: GitHub Pages / Vercel

## 📁 Project Structure

```
greeting-card-generator/
├── frontend/           # Web interface
├── backend/            # AI processing and API
├── models/             # AI model configurations
├── assets/             # Images, styles, templates
├── docs/               # Documentation
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Node.js (for frontend development)
- API keys for AI services

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/goodboyagi/greeting-card-generator.git
   cd greeting-card-generator
   ```

2. **Set up the backend**:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. **Set up the frontend**:
   ```bash
   cd frontend
   npm install
   ```

4. **Configure environment variables**:
   ```bash
   cp .env.example .env
   # Edit .env with your API keys
   ```

5. **Run the application**:
   ```bash
   # Backend
   python app.py
   
   # Frontend (in another terminal)
   npm start
   ```

## 🎨 Usage

1. **Select a card style** from available templates
2. **Enter your message** or let AI generate one
3. **Customize the design** with colors and fonts
4. **Generate your card** using AI
5. **Download or share** the final result

## 🔧 Configuration

### Environment Variables

- `OPENAI_API_KEY`: Your OpenAI API key
- `HUGGINGFACE_TOKEN`: Hugging Face API token
- `FLASK_ENV`: Development/production environment

### API Endpoints

- `POST /api/generate-text`: Generate card text
- `POST /api/generate-image`: Generate card images
- `GET /api/styles`: Get available card styles

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Live Demo**: [Coming Soon]
- **Main Website**: [goodboyagi.com](https://goodboyagi.com)
- **GitHub**: [github.com/goodboyagi/greeting-card-generator](https://github.com/goodboyagi/greeting-card-generator)

---

**Built with ❤️ by Good Boy AGI** 