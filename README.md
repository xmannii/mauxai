<svg width="400" height="200" viewBox="0 0 400 200" fill="none" xmlns="http://www.w3.org/2000/svg"

<rect width="400" height="200" fill="black" />
<path d="M193.761 90.4802C193.761 89.7335 193.699 89.0179 193.575 88.3335C193.512 87.649 193.326 87.0579 193.015 86.5602C192.766 86.0002 192.361 85.5646 191.801 85.2535C191.304 84.8802 190.588 84.6935 189.655 84.6935C189.157 84.6935 188.628 84.7868 188.068 84.9735C187.57 85.0979 187.104 85.3468 186.668 85.7202C186.481 85.3468 186.357 85.0046 186.295 84.6935C186.295 84.3202 186.295 83.9779 186.295 83.6668V82.8268C186.295 80.8357 187.166 79.1868 188.908 77.8802C190.65 76.5735 192.921 75.9202 195.721 75.9202C199.081 75.9202 201.664 76.9468 203.468 79.0002C205.335 80.9913 206.268 83.9468 206.268 87.8668V123.333H205.708C201.975 123.333 199.05 122.462 196.935 120.72C194.819 118.916 193.761 116.053 193.761 112.133V90.4802ZM172.481 75.9202H173.508C176.744 75.9202 179.45 76.7913 181.628 78.5335C183.868 80.2757 184.988 83.0446 184.988 86.8402V123.333H184.428C182.997 123.333 181.566 123.147 180.135 122.773C178.766 122.4 177.49 121.809 176.308 121C175.188 120.129 174.255 119.04 173.508 117.733C172.824 116.365 172.481 114.685 172.481 112.693V75.9202ZM215.041 90.4802C215.041 89.7335 214.979 89.0179 214.855 88.3335C214.792 87.649 214.606 87.0579 214.295 86.5602C214.046 86.0002 213.641 85.5646 213.081 85.2535C212.584 84.8802 211.868 84.6935 210.935 84.6935C210.437 84.6935 209.908 84.7868 209.348 84.9735C208.85 85.0979 208.384 85.3468 207.948 85.7202C207.699 85.2224 207.575 84.6624 207.575 84.0402C207.575 81.8624 208.321 79.9646 209.815 78.3468C211.308 76.729 213.548 75.9202 216.535 75.9202C220.081 75.9202 222.788 76.9468 224.655 79.0002C226.584 80.9913 227.548 83.9468 227.548 87.8668V123.333H226.988C223.255 123.333 220.33 122.462 218.215 120.72C216.099 118.916 215.041 116.053 215.041 112.133V90.4802Z" fill="white" /> </svg>

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
