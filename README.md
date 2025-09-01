# AI-Powered 3D PyGame Visualizer 

A Streamlit-based project showcasing **R1's** abilities to generate and visualize PyGame code from natural language prompts. Powered by **DeepSeek** for reasoning, **OpenAI GPT-4o** for code extraction, and automated browser agents for execution and visualization via **Trinket.io**.

## Features

* **Natural-language to PyGame code**: Describe what you want, and the system generates it.
* **DeepSeek Reasoning**: Processes the prompt to produce logic and a code foundation.
* **OpenAI Extraction**: Refines and cleans the code into executable form.
* **Trinket.io Automation**: Browser agents navigate, input code, run it, and display visuals.
* **Streamlit Frontend**: A sleek, interactive UI to streamline the experience.
* **Modular Agents**: Separate agents handle:

  * Navigation to Trinket.io
  * Code input
  * Execution
  * Visualization rendering

---

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/codewith-ram/Ai_3d_pygame.git
   cd Ai_3d_pygame
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Secure your API keys:

   * **DeepSeek**: register and get your API key from their platform.
   * **OpenAI**: sign up and obtain your API key on OpenAI.

4. Launch the app:

   ```bash
   streamlit run ai_3dpygame_r1.py
   ```

5. Interact: A browser window will open. Follow the provided URL to enter descriptions and generate 3D PyGame visualizations!

---

## How It Works

1. **User Input**: Enter a natural language description of your desired PyGame scene.
2. **DeepSeek Reasoning**: Generates structured logic and initial code based on your input.
3. **Code Refinement**: OpenAI GPT-4o cleans and formats the logic into runnable Python code.
4. **Visualization Pipeline**:

   * **Agent A**: Opens Trinket.io in a browser.
   * **Agent B**: Inserts the cleaned code.
   * **Agent C**: Runs the code.
   * **Agent D**: Captures and displays the visual output.
5. **UI Layer**: Streamlit ties everything together—input, backend processing, and output display in one interface.

---

## Contributing

Feel free to open issues or submit pull requests to improve features like:

* Supporting new PyGame functionalities.
* Enhancing DeepSeek-OpenAI integration.
* Improving automation robustness.
* Adding tests, logging, or error handling.

---

## Contact

Built with ❤️ by **codewith-ram**. Got feedback or questions? Open an issue or get in touch through GitHub.
