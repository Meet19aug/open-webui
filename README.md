# Open WebUI (Formerly Ollama WebUI) 👋

![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
![GitHub forks](https://img.shields.io/github/forks/open-webui/open-webui?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/open-webui/open-webui?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/open-webui/open-webui)
![GitHub language count](https://img.shields.io/github/languages/count/open-webui/open-webui)
![GitHub top language](https://img.shields.io/github/languages/top/open-webui/open-webui)
![GitHub last commit](https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Follama-webui%2Follama-wbui&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

Open WebUI is an extensible, feature-rich, and user-friendly self-hosted WebUI designed to operate entirely offline. It supports various LLM runners, including Ollama and OpenAI-compatible APIs. For more information, be sure to check out our [Open WebUI Documentation](https://docs.openwebui.com/).

![Open WebUI Demo](./demo.gif)

## Features ⭐

- 🖥️ **Intuitive Interface**: Our chat interface takes inspiration from ChatGPT, ensuring a user-friendly experience.

- 📱 **Responsive Design**: Enjoy a seamless experience on both desktop and mobile devices.

- ⚡ **Swift Responsiveness**: Enjoy fast and responsive performance.

- 🚀 **Effortless Setup**: Install seamlessly using Docker or Kubernetes (kubectl, kustomize or helm) for a hassle-free experience.

- 🌈 **Theme Customization**: Choose from a variety of themes to personalize your Open WebUI experience.

- 💻 **Code Syntax Highlighting**: Enjoy enhanced code readability with our syntax highlighting feature.

- ✒️🔢 **Full Markdown and LaTeX Support**: Elevate your LLM experience with comprehensive Markdown and LaTeX capabilities for enriched interaction.

- 📚 **Local RAG Integration**: Dive into the future of chat interactions with the groundbreaking Retrieval Augmented Generation (RAG) support. This feature seamlessly integrates document interactions into your chat experience. You can load documents directly into the chat or add files to your document library, effortlessly accessing them using `#` command in the prompt. In its alpha phase, occasional issues may arise as we actively refine and enhance this feature to ensure optimal performance and reliability.

- 🔍 **RAG Embedding Support**: Change the RAG embedding model directly in document settings, enhancing document processing. This feature supports Ollama and OpenAI models.

- 🌐 **Web Browsing Capability**: Seamlessly integrate websites into your chat experience using the `#` command followed by the URL. This feature allows you to incorporate web content directly into your conversations, enhancing the richness and depth of your interactions.

- 📜 **Prompt Preset Support**: Instantly access preset prompts using the `/` command in the chat input. Load predefined conversation starters effortlessly and expedite your interactions. Effortlessly import prompts through [Open WebUI Community](https://openwebui.com/) integration.

- 👍👎 **RLHF Annotation**: Empower your messages by rating them with thumbs up and thumbs down, followed by the option to provide textual feedback, facilitating the creation of datasets for Reinforcement Learning from Human Feedback (RLHF). Utilize your messages to train or fine-tune models, all while ensuring the confidentiality of locally saved data.

- 🏷️ **Conversation Tagging**: Effortlessly categorize and locate specific chats for quick reference and streamlined data collection.

- 📥🗑️ **Download/Delete Models**: Easily download or remove models directly from the web UI.

- 🔄 **Update All Ollama Models**: Easily update locally installed models all at once with a convenient button, streamlining model management.

- ⬆️ **GGUF File Model Creation**: Effortlessly create Ollama models by uploading GGUF files directly from the web UI. Streamlined process with options to upload from your machine or download GGUF files from Hugging Face.

- 🤖 **Multiple Model Support**: Seamlessly switch between different chat models for diverse interactions.

- 🔄 **Multi-Modal Support**: Seamlessly engage with models that support multimodal interactions, including images (e.g., LLava).

- 🧩 **Modelfile Builder**: Easily create Ollama modelfiles via the web UI. Create and add characters/agents, customize chat elements, and import modelfiles effortlessly through [Open WebUI Community](https://openwebui.com/) integration.

- ⚙️ **Many Models Conversations**: Effortlessly engage with various models simultaneously, harnessing their unique strengths for optimal responses. Enhance your experience by leveraging a diverse set of models in parallel.

- 💬 **Collaborative Chat**: Harness the collective intelligence of multiple models by seamlessly orchestrating group conversations. Use the `@` command to specify the model, enabling dynamic and diverse dialogues within your chat interface. Immerse yourself in the collective intelligence woven into your chat environment.

- 🗨️ **Local Chat Sharing**: Generate and share chat links seamlessly between users, enhancing collaboration and communication.

- 🔄 **Regeneration History Access**: Easily revisit and explore your entire regeneration history.

- 📜 **Chat History**: Effortlessly access and manage your conversation history.

- 📬 **Archive Chats**: Effortlessly store away completed conversations with LLMs for future reference, maintaining a tidy and clutter-free chat interface while allowing for easy retrieval and reference.

- 📤📥 **Import/Export Chat History**: Seamlessly move your chat data in and out of the platform.

- 🗣️ **Voice Input Support**: Engage with your model through voice interactions; enjoy the convenience of talking to your model directly. Additionally, explore the option for sending voice input automatically after 3 seconds of silence for a streamlined experience.

- 🔊 **Configurable Text-to-Speech Endpoint**: Customize your Text-to-Speech experience with configurable OpenAI endpoints.

- ⚙️ **Fine-Tuned Control with Advanced Parameters**: Gain a deeper level of control by adjusting parameters such as temperature and defining your system prompts to tailor the conversation to your specific preferences and needs.

- 🎨🤖 **Image Generation Integration**: Seamlessly incorporate image generation capabilities using options such as AUTOMATIC1111 API (local), ComfyUI (local), and DALL-E, enriching your chat experience with dynamic visual content.

- 🤝 **OpenAI API Integration**: Effortlessly integrate OpenAI-compatible API for versatile conversations alongside Ollama models. Customize the API Base URL to link with **LMStudio, Mistral, OpenRouter, and more**.

- ✨ **Multiple OpenAI-Compatible API Support**: Seamlessly integrate and customize various OpenAI-compatible APIs, enhancing the versatility of your chat interactions.

- 🔑 **API Key Generation Support**: Generate secret keys to leverage Open WebUI with OpenAI libraries, simplifying integration and development.

- 🔗 **External Ollama Server Connection**: Seamlessly link to an external Ollama server hosted on a different address by configuring the environment variable.

- 🔀 **Multiple Ollama Instance Load Balancing**: Effortlessly distribute chat requests across multiple Ollama instances for enhanced performance and reliability.

- 👥 **Multi-User Management**: Easily oversee and administer users via our intuitive admin panel, streamlining user management processes.

- 🔗 **Webhook Integration**: Subscribe to new user sign-up events via webhook (compatible with Google Chat and Microsoft Teams), providing real-time notifications and automation capabilities.

- 🛡️ **Model Whitelisting**: Admins can whitelist models for users with the 'user' role, enhancing security and access control.

- 📧 **Trusted Email Authentication**: Authenticate using a trusted email header, adding an additional layer of security and authentication.

- 🔐 **Role-Based Access Control (RBAC)**: Ensure secure access with restricted permissions; only authorized individuals can access your Ollama, and exclusive model creation/pulling rights are reserved for administrators.

- 🔒 **Backend Reverse Proxy Support**: Bolster security through direct communication between Open WebUI backend and Ollama. This key feature eliminates the need to expose Ollama over LAN. Requests made to the '/ollama/api' route from the web UI are seamlessly redirected to Ollama from the backend, enhancing overall system security.

- 🌐🌍 **Multilingual Support**: Experience Open WebUI in your preferred language with our internationalization (i18n) support. Join us in expanding our supported languages! We're actively seeking contributors!

- 🌟 **Continuous Updates**: We are committed to improving Open WebUI with regular updates and new features.

## 🔗 Also Check Out Open WebUI Community!

Don't forget to explore our sibling project, [Open WebUI Community](https://openwebui.com/), where you can discover, download, and explore customized Modelfiles. Open WebUI Community offers a wide range of exciting possibilities for enhancing your chat interactions with Open WebUI! 🚀

## How to Install 🚀

> [!NOTE]  
> Please note that for certain Docker environments, additional configurations might be needed. If you encounter any connection issues, our detailed guide on [Open WebUI Documentation](https://docs.openwebui.com/) is ready to assist you.

### Quick Start with Docker 🐳

> [!WARNING]
> When using Docker to install Open WebUI, make sure to include the `-v open-webui:/app/backend/data` in your Docker command. This step is crucial as it ensures your database is properly mounted and prevents any loss of data.

> [!TIP]  
> If you wish to utilize Open WebUI with Ollama included or CUDA acceleration, we recommend utilizing our official images tagged with either `:cuda` or `:ollama`. To enable CUDA, you must install the [Nvidia CUDA container toolkit](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/) on your Linux/WSL system.

### Installation with Default Configuration

- **If Ollama is on your computer**, use this command:

  ```bash
  docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **If Ollama is on a Different Server**, use this command:

  To connect to Ollama on another server, change the `OLLAMA_BASE_URL` to the server's URL:

  ```bash
  docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

  - **To run Open WebUI with Nvidia GPU support**, use this command:

  ```bash
  docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:cuda
  ```

### Installation for OpenAI API Usage Only

- **If you're only using OpenAI API**, use this command:

  ```bash
  docker run -d -p 3000:8080 -e OPENAI_API_KEY=your_secret_key -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

### Installing Open WebUI with Bundled Ollama Support

This installation method uses a single container image that bundles Open WebUI with Ollama, allowing for a streamlined setup via a single command. Choose the appropriate command based on your hardware setup:

- **With GPU Support**:
  Utilize GPU resources by running the following command:

  ```bash
  docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

- **For CPU Only**:
  If you're not using a GPU, use this command instead:

  ```bash
  docker run -d -p 3000:8080 -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

Both commands facilitate a built-in, hassle-free installation of both Open WebUI and Ollama, ensuring that you can get everything up and running swiftly.

After installation, you can access Open WebUI at [http://localhost:3000](http://localhost:3000). Enjoy! 😄

### Other Installation Methods

We offer various installation alternatives, including non-Docker native installation methods, Docker Compose, Kustomize, and Helm. Visit our [Open WebUI Documentation](https://docs.openwebui.com/getting-started/) or join our [Discord community](https://discord.gg/5rJgQTnV4s) for comprehensive guidance.

### Troubleshooting

Encountering connection issues? Our [Open WebUI Documentation](https://docs.openwebui.com/troubleshooting/) has got you covered. For further assistance and to join our vibrant community, visit the [Open WebUI Discord](https://discord.gg/5rJgQTnV4s).

#### Open WebUI: Server Connection Error

If you're experiencing connection issues, it’s often due to the WebUI docker container not being able to reach the Ollama server at 127.0.0.1:11434 (host.docker.internal:11434) inside the container . Use the `--network=host` flag in your docker command to resolve this. Note that the port changes from 3000 to 8080, resulting in the link: `http://localhost:8080`.

**Example Docker Command**:

```bash
docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```

### Keeping Your Docker Installation Up-to-Date

In case you want to update your local Docker installation to the latest version, you can do it with [Watchtower](https://containrrr.dev/watchtower/):

```bash
docker run --rm --volume /var/run/docker.sock:/var/run/docker.sock containrrr/watchtower --run-once open-webui
```

In the last part of the command, replace `open-webui` with your container name if it is different.

### Moving from Ollama WebUI to Open WebUI

Check our Migration Guide available in our [Open WebUI Documentation](https://docs.openwebui.com/migration/).

## What's Next? 🌟

Discover upcoming features on our roadmap in the [Open WebUI Documentation](https://docs.openwebui.com/roadmap/).

## Supporters ✨

A big shoutout to our amazing supporters who's helping to make this project possible! 🙏

### Platinum Sponsors 🤍

- We're looking for Sponsors!

### Acknowledgments

Special thanks to [Prof. Lawrence Kim](https://www.lhkim.com/) and [Prof. Nick Vincent](https://www.nickmvincent.com/) for their invaluable support and guidance in shaping this project into a research endeavor. Grateful for your mentorship throughout the journey! 🙌

## License 📜

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details. 📄

## Support 💬

If you have any questions, suggestions, or need assistance, please open an issue or join our
[Open WebUI Discord community](https://discord.gg/5rJgQTnV4s) to connect with us! 🤝

## Star History

<a href="https://star-history.com/#open-webui/open-webui&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
  </picture>
</a>

---

Created by [Timothy J. Baek](https://github.com/tjbck) - Let's make Open WebUI even more amazing together! 💪


Run on: 
localhost:3000
