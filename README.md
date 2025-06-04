# GenAi-Lab-Work


A comprehensive collection of Jupyter notebooks demonstrating various AI and machine learning concepts, with a focus on Google's Gemini AI, multimodal applications, and prompt engineering techniques.

## 📋 Repository Contents

### Core Notebooks

| Notebook | Description | Version |
|----------|-------------|---------|
| `intro_gemini_curl-v2.0.0.ipynb` | Introduction to Gemini API using cURL commands | v2.0.0 |
| `intro_genai_sdk-v1.0.0.ipynb` | Getting started with Google's Generative AI SDK | v1.0.0 |
| `intro_multimodal_use_cases-v2.0.0.ipynb` | Exploring multimodal AI applications and use cases | v2.0.0 |
| `intro_prompt_design-v2.0.0.ipynb` | Comprehensive guide to prompt engineering and design | v2.0.0 |
| `inspect_rich_documents_w_gemini_multimodal...` | Advanced document analysis using Gemini's multimodal capabilities | Latest |

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Google Cloud account (for Gemini API access)
- Required Python packages (see Installation section)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/SimranShaikh20/GenAi-Lab-Work.git
cd <repository-name>
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Set up your Google Cloud credentials:
```bash
export GOOGLE_API_KEY="your-api-key-here"
```

## 📚 Tutorial Overview

### 1. Gemini API Basics (`intro_gemini_curl-v2.0.0.ipynb`)
- Learn how to interact with Gemini API using cURL
- Understand API endpoints and request/response formats
- Practice basic text generation and analysis

### 2. Generative AI SDK (`intro_genai_sdk-v1.0.0.ipynb`)
- Introduction to Google's Generative AI Python SDK
- Setting up authentication and client configuration
- Basic text generation and conversation examples

### 3. Multimodal Applications (`intro_multimodal_use_cases-v2.0.0.ipynb`)
- Explore text, image, and audio processing capabilities
- Learn about multimodal prompt engineering
- Practical examples of combining different media types

### 4. Prompt Design Fundamentals (`intro_prompt_design-v2.0.0.ipynb`)
- Best practices for crafting effective prompts
- Understanding prompt structure and optimization
- Advanced techniques for better AI responses

### 5. Document Analysis (`inspect_rich_documents_w_gemini_multimodal...`)
- Advanced document processing with Gemini
- Extract insights from complex document formats
- Multimodal analysis of rich media documents

## 🛠️ Usage

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to the desired notebook and open it

3. Follow the step-by-step instructions in each notebook

4. Modify and experiment with the code examples

## 📋 Requirements

Create a `requirements.txt` file with the following dependencies:

```
google-generativeai>=0.3.0
jupyter>=1.0.0
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.5.0
pillow>=8.3.0
requests>=2.26.0
python-dotenv>=0.19.0
```

## 🔧 Configuration

### API Setup

1. Obtain a Google AI API key from [Google AI Studio](https://makersuite.google.com/app/apikey)

2. Set your API key as an environment variable:
```bash
export GOOGLE_API_KEY="your-actual-api-key"
```

3. Or create a `.env` file in the project root:
```
GOOGLE_API_KEY=your-actual-api-key
```

## 📖 Learning Path

For beginners, we recommend following this sequence:

1. **Start with SDK Basics** → `intro_genai_sdk-v1.0.0.ipynb`
2. **Learn API Fundamentals** → `intro_gemini_curl-v2.0.0.ipynb`
3. **Master Prompt Design** → `intro_prompt_design-v2.0.0.ipynb`
4. **Explore Multimodal Capabilities** → `intro_multimodal_use_cases-v2.0.0.ipynb`
5. **Advanced Document Processing** → `inspect_rich_documents_w_gemini_multimodal...`

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues or have questions:

1. Check the notebook comments and documentation
2. Review the [Google AI documentation](https://ai.google.dev/)
3. Open an issue in this repository
4. Join our community discussions

## 🎯 Use Cases

These notebooks are perfect for:

- **Students** learning AI and machine learning concepts
- **Developers** integrating Gemini into applications
- **Researchers** exploring multimodal AI capabilities
- **Content Creators** optimizing AI-generated content
- **Business Professionals** understanding AI applications

## 🔄 Updates

This repository is actively maintained. Check the commit history for the latest updates and improvements to each notebook.

## 🏷️ Tags

`artificial-intelligence` `machine-learning` `gemini-ai` `google-ai` `multimodal` `prompt-engineering` `jupyter-notebooks` `python` `tutorials` `generative-ai`

---

**Happy Learning!** 🚀

For questions or feedback, please don't hesitate to reach out or open an issue.