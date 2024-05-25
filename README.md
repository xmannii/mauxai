
# Maux

## Overview
Maux is a Next.js application that integrates the most popular AI language models into a single, seamless chat interface. Utilizing the Vercel AI SDK, Maux provides a unified platform for interacting with diverse AI models, enhancing user experience with a versatile and powerful conversational tool.

## Features
- **Unified Chat Interface:** Interact with multiple AI language models in one place.
- **Next.js Framework:** Built with the robust and flexible Next.js framework.
- **Vercel AI SDK:** Seamlessly integrate and manage various AI models.
- **Extensible:** Easily add or remove AI models as needed.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Installation

1. **Clone the repository:**
    ```bash
    git clone git@github.com:xmannii/mauxai.git
    cd maux
    ```

2. **Install dependencies:**
    ```bash
    pnpm install
    ```

3. **Create a `.env.local` file:**
    ```bash
    touch .env.local
    ```
    Add your environment variables to `.env.local`:
    ```
   adjust the api keys based on the models you want to use. 
   OPENAI_API_KEY=YOUR-KEY
   GOOGLE_GENERATIVE_AI_API_KEY=YOUR-KEY
   GROQ_API_KEY=YOUR-KEY
    ```

4. **Run the development server:**
    ```bash
    pnpm dev
    ```

5. **Open your browser:**
    Visit [http://localhost:3000](http://localhost:3000) to see the application in action.

## Usage
1. **Select an AI Model:** Choose from the available AI language models in the chat interface.
2. **Start Chatting:** Type your message and receive responses from the selected AI model.
3. **Switch Models:** Easily switch between different AI models to compare responses and capabilities.

## Contributing
We welcome contributions! Please follow these steps to contribute:

1. **Fork the repository**
2. **Create a new branch:**
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Make your changes and commit them:**
    ```bash
    git commit -m 'Add some feature'
    ```
4. **Push to the branch:**
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Create a new Pull Request**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Next.js](https://nextjs.org/)
- [Vercel AI SDK](https://sdk.vercel.ai/)
- All contributors and open-source libraries that made this project possible.

## Contact
For questions or feedback,contact us at mani@maniw.space

---

Thank you for using Maux! We hope it enhances your AI interaction experience.
