---
description: Scaffolding a new Agent UI project with Vite and React
---

<!-- @format -->

Follow these steps to quickly create a web-based portal for a new agent.

1.  **Ask the user for the project name.**
2.  **Create the project directory.**
    // turbo
3.  **Run the Vite scaffold command.**
    `bash
    npx create-vite@latest . --template react
    `
    // turbo
4.  **Install base dependencies.**
    ```bash
    npm install
    ```
5.  **Create a `start.sh` for easy access.**
    ```bash
    echo "#!/bin/bash\nnpm run dev" > start.sh
    chmod +x start.sh
    ```
6.  **Notify the user that the UI is ready.**
