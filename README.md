## ✨ Features

-   🌍 **Interactive Globe Visualization:** Dynamically displays World Cup data on a global map, likely showing host countries, team origins, or event progression.
-   ⏳ **Dynamic Timeline Control:** Allows users to navigate through different World Cup editions, observing changes and trends over time.
-   📊 **Comprehensive Data Display:** Presents detailed statistics and information about matches, teams, and players.
-   💡 **Contextual Tooltips:** Provides on-demand information for specific data points upon interaction.
-   📱 **Responsive Design:** Ensures an optimal viewing experience across various devices and screen sizes.

## 🖥️ Screenshots

<img width="1897" height="865" alt="image" src="https://github.com/user-attachments/assets/b67fae1e-6f34-4580-89dd-5047b718e283" />

<img width="1895" height="868" alt="image" src="https://github.com/user-attachments/assets/3b3e381d-6cac-44b1-8a61-29c3c8374b0a" />


## 🛠️ Tech Stack

**Frontend:**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white) <!-- Inferred from common data visualization practices -->

**Backend (Development Server & Local API):**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

**Deployment:**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## 🚀 Quick Start

### Prerequisites
To run the development server and access the local API, you need:
-   **Node.js** (LTS version recommended)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/is4r0/world-cup-in-motion.git
    cd world-cup-in-motion
    ```

2.  **No further dependency installation is required**
    This project primarily uses vanilla JavaScript, HTML, and CSS, served by a simple Node.js development server that uses built-in modules.

3.  **Start development server**
    ```bash
    node dev-server.js
    ```
    This will start the server on `http://localhost:3000`.

4.  **Open your browser**
    Visit `http://localhost:3000` to access the application.

## 📁 Project Structure

```
world-cup-in-motion/
├── api/                  # Contains local API data, e.g., data.json
│   └── data.json         # Raw World Cup data for visualization
├── assets/               # Static assets like images, icons, and potentially logo
├── css/                  # Stylesheets for the application
│   └── style.css         # Main application styles
├── js/                   # JavaScript files for interactive functionality
│   ├── main.js           # Core application logic and initialization
│   ├── globe.js          # Logic for the interactive globe visualization
│   ├── timeline.js       # Logic for the dynamic timeline component
│   └── utils.js          # Utility functions (inferred)
├── dev-server.js         # Custom Node.js development server
├── index.html            # Main entry point for the web application
└── README.md             # This README file
```

## 📚 API Reference

The application consumes data from a local API endpoint during development.

### Data Endpoint
-   **URL:** `/api/data`
-   **Method:** `GET`
-   **Description:** Retrieves all historical World Cup data in JSON format. This data is served directly from the `api/data.json` file.
-   **Example Response (Structure):**
    ```json
    // Example data structure from api/data.json (inferred)
    [
      {
        "year": 1930,
        "host_country": "Uruguay",
        "winner": "Uruguay",
        "runner_up": "Argentina",
        "matches": [
          // ... match details ...
        ],
        "teams": [
          // ... team details ...
        ]
      },
      // ... more World Cup editions ...
    ]
    ```

## 🤝 Contributing

We welcome contributions to enhance "World Cup in Motion"! If you have ideas for new features, improvements, or bug fixes, please open an issue or submit a pull request.

<div align="center">

**⭐ Star this repo if you find it helpful or interesting!**

Made with ❤️ by [is4r0](https://github.com/is4r0)

</div>

