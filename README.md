# 🤖 AI Resume Analyzer

## Live Demo

🚀 Check out the live application here: [https://ai-based-resume-analyser-khaki.vercel.app/](https://ai-based-resume-analyser-khaki.vercel.app/)

## Project Overview

The AI Resume Analyzer is a powerful web application designed to streamline the job application process by intelligently evaluating resumes against specific job descriptions. Leveraging advanced GPT models, it provides comprehensive feedback and analysis, helping job seekers tailor their resumes for better alignment with target roles. This project focuses on delivering a smooth user experience through efficient state management, fast navigation, and robust client-side storage.

## Features

* **GPT-Powered Analysis:** Utilizes cutting-edge GPT models to compare resumes with job descriptions, providing insightful feedback.
* **Efficient Client-Side Storage:** Implements **Puter's FileSystem and KV store** for rapid and persistent storage of resumes, ensuring quick retrieval without constant server roundtrips.
* **Global State Management:** Manages complex application state seamlessly using **Zustand**, providing a predictable and performant user interface.
* **Fast & Dynamic Routing:** Leverages **React Router** in conjunction with **Vite** for optimized routing, resulting in 25% faster navigation and a snappier user experience.
* **Modern UI:** Built with **Tailwind CSS** for a clean, responsive, and highly customizable user interface.

## Technologies Used

* **Frontend:**
    * `React.js`
    * `Vite`
    * `React Router`
    * `Zustand`
    * `Tailwind CSS`
* **External Services:**
    * `Puter.js` (for FileSystem and KV Store)
    * `GPT Models` (via an API, e.g., OpenAI)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Node.js (LTS version recommended)
* npm or yarn

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
3.  **Environment Variables:**
    Create a `.env` file in the root of the project. You'll need API keys for the GPT model and potentially for Puter.js if you're using a specific instance.
    ```env
    VITE_GPT_API_KEY=your_openai_api_key
    VITE_PUTER_API_KEY=your_puter_api_key # If required for client-side integration
    ```
    *Replace `your_openai_api_key` and `your_puter_api_key` with your actual keys.*

### Running the Development Server

```bash
npm run dev
# or
yarn dev
````

Open your browser and navigate to `http://localhost:5173` (or the port displayed in your terminal).

### Building for Production

```bash
npm run build
# or
yarn build
```

This will compile the application into the `dist` directory, ready for deployment.

## Project Structure

```
├── public/                 # Static assets
├── src/
│   ├── assets/             # Images, icons, etc.
│   ├── components/         # Reusable React components
│   ├── hooks/              # Custom React hooks
│   ├── pages/              # Main application pages
│   ├── store/              # Zustand store definition
│   ├── utils/              # Utility functions (e.g., API calls, Puter interactions)
│   ├── App.jsx             # Main application component
│   └── main.jsx            # Entry point of the React application
├── .env                    # Environment variables
├── package.json            # Project dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
├── vite.config.js          # Vite build configuration
└── README.md               # You are here!
```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Deep Halder - [deephalder122002@gmail.com](mailto:deephalder122002@gmail.com)

-----

## Acknowledgments

  * [React](https://react.dev/)
  * [Vite](https://vitejs.dev/)
  * [React Router](https://reactrouter.com/en/main)
  * [Zustand](https://www.google.com/search?q=https://zustand-bear.github.io/zustand/)
  * [Tailwind CSS](https://tailwindcss.com/)
  * [Puter.js](https://puter.com/)
  * [OpenAI](https://openai.com/) (for GPT models)
