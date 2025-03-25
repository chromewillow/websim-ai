# WebSimAI Explorer

A Flask-based web simulation environment that allows users to explore an imaginary internet powered by AI. This project uses various AI backends (Google AI, LM Studio, and OpenRouter) to generate dynamic content based on user-provided URLs.

## Features

- Modern browser-like interface
- Multiple AI backend support (Google AI, LM Studio, OpenRouter)
- Dynamic content generation based on URLs
- Secure configuration management
- Interactive URL-based navigation

## Security Improvements

Recent security enhancements include:
- Removed hardcoded API keys from source code
- Implemented secure environment variable handling
- Added `.env` file support for configuration
- Fixed HTTP-Referer configuration for OpenRouter

## Setup

1. Clone the repository:
```bash
git clone https://github.com/chromewillow/websim-ai.git
cd websim-ai
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file:
```bash
# .env
OPENROUTER_API_KEY=your_api_key_here
PORT=5001
```

4. Run the application:
```bash
python main.py openrouter
```

## Configuration

The application supports three AI backends:
- Google AI (`google`)
- LM Studio (`lmstudio`)
- OpenRouter (`openrouter`)

Set the appropriate environment variables based on your chosen backend:
- `GOOGLE_AI_API_KEY` for Google AI
- `OPENROUTER_API_KEY` for OpenRouter

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT License