# Urban-Gardening-Advisor

**Provide tips and guidance on how to grow plants, vegetables, or flowers in small spaces like apartments or balconies.**  
Urban-Gardening-Advisor is a chatbot specifically designed to assist users with gardening-related inquiries. By feeding data about various gardening suggestions into a large language model (LLM), this chatbot provides insightful information and advice for gardening care, plant identification, and maintenance.

## Features
- **User-friendly interface** for answering gardening-related questions.
- **Comprehensive repository** of gardening information.
- **Personalized guidance and recommendations** based on user inputs.

## Installation
To get started with Urban-Gardening-Advisor, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/gorav-max/Urban-Gardening-Advisor.git
    cd Urban-Gardening-Advisor
    ```

2. **Install the Gaia Node:**

    Run the command below:

    ```bash
    curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
    ```

3. **Update the config.json file** to run with a small language model:

    ```bash
    gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json
    ```

4. **Start the node:**

    ```bash
    gaianet start
    ```

## How to Use
1. Open your web browser and navigate to the generated link.
2. Start interacting with the chatbot by typing your gardening-related questions.
