---
title: "GPT-3 model Prompt Engineering - Django Web App POC"
layout: "simple"
date: 2022-06-01
summary: 
  <ul>
  <li> This Django project uses OpenAI's GPT-3 model to suggest skills for a given role. It's designed to help users discover relevant skills for specific job roles, making it a valuable tool for career development and job preparation. </li>
  <li> It's designed to help users discover relevant skills for specific job roles, making it a valuable tool for career development and job preparation. </li>
  </ul>
topics: [generative ai, natural language processing, django, web app, prompt engineering]
# description: ""
_build:
  render: "false"
  list: "local"
---

# GPT-3 model Prompt Engineering - Django Web App POC

## Table of Contents

- [Description](#description)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

The MachineLearning_ChatGPT_SkillsSuggester is a Django project that uses OpenAI's GPT-3 model to suggest skills for a given role. It's designed to help users discover relevant skills for specific job roles, making it a valuable tool for career development and job preparation.

![alt text](https://vrajeshtrichy.github.io/website/images/portfolio/p6_fig_01.png "Results for AI Engineer")

---

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python: Your project requires Python. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/MachineLearning_ChatGPT_SkillsSuggester.git
   ```

2. Navigate to the project directory:

   ```bash
   cd MachineLearning_ChatGPT_SkillsSuggester
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure your OpenAI API key in `settings.py`. Replace `YOUR_API_KEY` with your actual API key.

   ```python
   # settings.py
   OPENAI_API_KEY = 'YOUR_API_KEY'
   ```

---

## Usage

To use the MachineLearning_ChatGPT_SkillsSuggester, follow these steps:

1. Start the Django development server:

   ```bash
   python manage.py runserver
   ```

2. Open a web browser and go to [http://localhost:8000](http://localhost:8000).

3. Enter a job role in the input field and click the "Submit" button.

4. The application will use GPT-3 to suggest three skills related to the given role.

---
### API Details
Model: text-davinci-003

---

### Demo

#### Home Page
![alt text](https://vrajeshtrichy.github.io/website/images/portfolio/p6_fig_02.png "Searching")

#### For: "AI Engineer"

![alt text](https://vrajeshtrichy.github.io/website/images/portfolio/p6_fig_03.png "Results for AI Engineer")

#### For: "Communications Officer"

![alt text](https://vrajeshtrichy.github.io/website/images/portfolio/p6_fig_04.png "Results for Communications Officer")

---

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add your feature"
   ```

4. Push to your forked repository:

   ```bash
   git push origin feature/your-feature
   ```

5. Open a pull request, explaining your changes and improvements.

---

## License

This project is licensed under the MIT License