# Sales Copilot

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## ?? Summary

Sales Copilot is an innovative AI-powered tool designed to streamline the sales process. It leverages CrewAI agents to automate tasks like lead research, email drafting, and sales strategy generation, helping sales teams close deals faster and more efficiently.

## ? Key Features

-   Automated lead research using custom tools (SerperDevTool, ScrapeWebsiteTool).
-   Personalized email drafting based on lead data and sales context.
-   Sales strategy suggestions tailored to individual leads.
-   Integration with external data sources for comprehensive insights.
-   User-friendly web interface built with Streamlit for easy interaction.
-   Utilizes powerful AI models via Langchain and OpenAI.

## ?? Technologies Used

-   ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
-   ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
-   ![CrewAI](https://img.shields.io/badge/-CrewAI-blueviolet)
-   ![LangChain](https://img.shields.io/badge/-LangChain-orange)
-   ![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
-   SerperDevTool (for web search)
-   ScrapeWebsiteTool (for website content extraction)

## ?? Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MaryamAli-2020/Sales-Copilot.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd Sales-Copilot
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up environment variables:**
    Create a file named `.env` in the root project directory.
    Add your API keys to this file:
    ```plaintext
    SERPER_API_KEY='YOUR_SERPER_API_KEY'
    OPENAI_API_KEY='YOUR_OPENAI_API_KEY'
    # OPENAI_MODEL_NAME='gpt-4o' # Optional: Specify model, defaults usually work
    ```
    *Replace `'YOUR_SERPER_API_KEY'` and `'YOUR_OPENAI_API_KEY'` with your actual keys.*

## ?? Usage

1.  **Run the Streamlit application:**
    ```bash
    streamlit run app.py
    ```

2.  **Interact with the Copilot:**
    -   Open your web browser and navigate to the local URL provided by Streamlit (usually `http://localhost:8501`).
    -   Enter the required information about the prospect (e.g., name, company, role) and the sales context (e.g., your product, sales goal) into the input fields on the web page.
    -   Click the "Start Sales Copilot" button.
    -   Observe the AI agents working through the research, analysis, and drafting process in the application's output area.

## ?? Screenshots & Demo

Here's a glimpse into the Sales Copilot application:

**Sales Copilot Dashboard:**
![Sales Copilot dashboard showing active tasks, timeline, and research tools.](https://github.com/MaryamAli-2020/Sales-Copilot/blob/main/Media/Copilot-in-use.png?raw=true)
*Sales Copilot dashboard showing active tasks, timeline, and research tools.*

**Agent Creation:**
![Creating the Agent.](https://github.com/MaryamAli-2020/Sales-Copilot/blob/main/Media/Agent.png?raw=true)
*Configuring the CrewAI agent for sales tasks.*

**Tool Configuration:**
![Creating the tools.](https://github.com/MaryamAli-2020/Sales-Copilot/blob/main/Media/Tools.png?raw=true)
*Setting up the tools (like search and scraping) for the agent.*

**Video Demo:**
[![Sales Copilot Demo Video](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://github.com/MaryamAli-2020/Sales-Copilot/blob/main/Media/Sales-Copilot-DEMO.mp4)
*[Watch the Demo Video Here](https://github.com/MaryamAli-2020/Sales-Copilot/blob/main/Media/Sales-Copilot-DEMO.mp4)*
*(Note: The video link above points directly to the mp4 file in the repository. You might need to download it to view.)*

## ?? Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeatureName`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeatureName`).
6.  Open a Pull Request.

Please open an issue first to discuss any major changes you would like to make. Ensure your code adheres to the project's style guidelines.

## ?? License

This project is open-source and licensed under the MIT License. See the [LICENSE](LICENSE) file for more details (if one exists in the repository, otherwise rely on the badge).

## ?? Repository Link

You can find the full source code and contribute to the project on GitHub:
[https://github.com/MaryamAli-2020/Sales-Copilot](https://github.com/MaryamAli-2020/Sales-Copilot)
