



# RepoLens AI 🔍

An AI-powered GitHub repository analyzer that runs in Google Colab, providing deep insights into code structure, development patterns, and team dynamics through automated analysis and interactive Q&A.

![RepoLens AI_ Intelligent GitHub Repository Analysis Platform - visual selection (3)](https://github.com/user-attachments/assets/330767fa-af12-4ef9-b610-6766fd5c8362)



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nihalnihalani/RepoLens-AI-/blob/main/RepoLens_AI.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🌟 Overview

RepoLens AI is a powerful tool that combines the accessibility of Google Colab with advanced AI analysis capabilities to help you understand GitHub repositories better. Perfect for developers, researchers, and teams looking to gain insights into codebases.



## 🚀 Features



- **Cloud-Based Analysis**: Run directly in Google Colab - no local setup required
- **Comprehensive Repository Analysis**: Analyze code structure, patterns, and organization
- **Development Insights**: Track commit patterns, team dynamics, and project health
- **Interactive Q&A**: Ask follow-up questions about the analysis using AI
- **Visual Reports**: Get clear, formatted insights with markdown support
- **AI-Powered Understanding**: Leverages Google's Gemini Pro for intelligent analysis

## 📋 Prerequisites

![ok](https://github.com/user-attachments/assets/16e1b051-cd7b-424b-bb23-ce3c5785658d)



- Google Account (for accessing Google Colab)
- GitHub Personal Access Token
- Google Cloud Account with Gemini API Key

## 🚀 Quick Start

![RepoLens AI_ Intelligent GitHub Repository Analysis Platform - visual selection](https://github.com/user-attachments/assets/1d45e723-9df2-4ad7-aabe-37f5b2a67a19)


1. **Open in Colab**:
   - Click the "Open in Colab" badge above
   - Save a copy to your Google Drive

2. **Install Dependencies**:
   Run the following cells to set up the environment:
```python
!pip install gradio
!pip install pathlib
!pip install anthropic
!pip install tenacity
!pip install python-dotenv
!pip install PyGithub
!pip install pandas
```

3. **Set API Keys**:
```python
# Set your API keys in the notebook
GITHUB_TOKEN = "your_github_token"
GEMINI_API_KEY = "your_gemini_api_key"
```

## 💻 Usage

1. **Run All Cells**:
   - Execute all cells in order
   - Wait for the Gradio interface to initialize

2. **Access the Interface**:
   - Use the provided Gradio public URL
   - Or connect to the local URL if running on a pro Colab account

3. **Analyze Repositories**:
   - Enter any public GitHub repository URL
   - Click "Analyze" to start the analysis
   - View comprehensive insights
   - Ask follow-up questions using the chat interface

## 📊 Analysis Sections

![slo](https://github.com/user-attachments/assets/6285e50b-e5ac-45e5-8fc2-14cead773f1b)


- **Project Overview**: High-level metrics and project scope
- **Architecture**: Code organization and structure analysis
- **Development Practices**: Code quality and standards
- **Workflow Analysis**: Commit patterns and development cycles
- **Team Dynamics**: Collaboration and contribution analysis
- **Technical Insights**: Innovation and complexity assessment
- **Project Health**: Sustainability and maintenance metrics

## ⚙️ Configuration

### Required API Keys

1. **GitHub Personal Access Token**:
   - Go to GitHub Settings > Developer Settings > Personal Access Tokens
   - Generate a new token with `repo` scope
   - Add to the notebook's `GITHUB_TOKEN` variable

2. **Google Gemini API Key**:
   - Visit Google Cloud Console
   - Enable Gemini API
   - Create API credentials
   - Add to the notebook's `GEMINI_API_KEY` variable

## 🔧 Customization

Modify these variables in the notebook for customization:
```python
RELEVANT_EXTENSIONS = {
    ".py", ".js", ".ts", ".jsx", ".tsx", ".java", ".cpp", ".c", ".h",
    ".hpp", ".rb", ".php", ".go", ".rs", ".swift", ".kt"
}

# Adjust model parameters
generation_config = {
    "temperature": 1,
    "top_p": 0.95,
    "top_k": 40,
    "max_output_tokens": 8192,
}
```
## 📚 Use Cases

![use case](https://github.com/user-attachments/assets/374a290c-eacf-4568-a442-67516b6d002e)

### 1. Development Teams
- **Code Quality Assessment**
  - Analyze code patterns and architectural decisions
  - Identify potential technical debt and areas for improvement
  - Monitor development practices and standards adherence
  - Track team coding patterns and consistency

- **Team Performance Analysis**
  - Understand contribution patterns across the team
  - Identify peak productivity periods
  - Analyze code review practices and effectiveness
  - Monitor sprint velocity and development cycles

- **Project Health Monitoring**
  - Track repository growth and maintenance patterns
  - Analyze documentation coverage and quality
  - Monitor dependency management and updates
  - Assess technical debt accumulation

### 2. Project Managers
- **Resource Planning**
  - Identify areas requiring additional developer resources
  - Understand team capacity and workload distribution
  - Track project momentum and development velocity
  - Plan sprint allocations based on historical patterns

- **Progress Tracking**
  - Monitor milestone completion rates
  - Track feature development progress
  - Analyze sprint effectiveness
  - Identify bottlenecks in development workflow

### 3. Individual Developers
- **Repository Exploration**
  - Quick understanding of new codebases
  - Identify key components and dependencies
  - Understand coding patterns and standards
  - Learn from existing implementation patterns

- **Code Contribution**
  - Analyze existing patterns before contributing
  - Understand team coding preferences
  - Identify areas suitable for contribution
  - Learn project-specific best practices

### 4. Open Source Maintainers
- **Community Management**
  - Track contributor engagement
  - Monitor community growth
  - Analyze contribution patterns
  - Identify active and potential contributors

- **Project Maintenance**
  - Monitor repository health
  - Track issue resolution patterns
  - Analyze pull request patterns
  - Identify maintenance bottlenecks
 
## ⚡ Benefits

![benefits](https://github.com/user-attachments/assets/f21226cd-1c79-4404-9ce2-71553d77f917)


## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Submit a Pull Request with your improvements
4. Share your feedback and suggestions

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Google Colab for the free GPU resources
- Google Gemini for AI capabilities
- GitHub API for repository data access
- Gradio for the web interface

## 📞 Support

For support:
1. Check the [Issues](https://github.com/yourusername/repolens-ai/issues) section
2. Create a new issue with detailed description
3. Join our community discussions

## 🔮 Future Enhancements

![fuutuure](https://github.com/user-attachments/assets/c5e95873-2863-4b94-a6e7-0b0256d5c695)


- [ ] Add support for private repositories
- [ ] Implement custom analysis templates
- [ ] Add more visualization options
- [ ] Enable batch repository analysis
- [ ] Add export functionality for analysis results
- [ ] Integrate with more version control platforms

## 📚 Citation

If you use this tool in your research, please cite:

```bibtex
@software{repolens_ai,
  title = {RepoLens AI: AI-Powered GitHub Repository Analyzer},
  author = {Nihal Nihalani},
  year = {2025},
  url = {https://github.com/nihalnihalani/RepoLens-AI-}
}
```
