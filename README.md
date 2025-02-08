# 🚀 Tour Planner Application

## 🌍 Overview
The **Tour Planner Application** helps you plan your trips by finding the shortest path between two tourist destinations using **Dijkstra's Algorithm**. It provides travel options such as **Bus**, **Flight**, and **Train** to make your journey comfortable, efficient, and customizable based on your preferences.

## 🛠️ Features
- **Shortest Path Calculation:** Find the shortest path between two tourist destinations using **Dijkstra's Algorithm**.
- **Multiple Travel Options:** Choose your mode of travel: **Bus**, **Flight**, or **Train**.
- **Interactive Graph Visualization:** Visual representation of cities and travel paths with an intuitive graph interface.
- **Dynamic Travel Distance Calculation:** Get travel distances and times for each path type.
- **Real-Time Updates:** See results dynamically as you interact with the application.

## 🖥️ Technologies Used
This project is built with:

- **Dijkstra's Algorithm** 📏 for calculating the shortest path
- **JavaScript** 💻 for core logic
- **vis.js** 🔮 for network visualization
- **HTML** 🏗️ for the web structure
- **CSS** 🎨 for styling the user interface

## 🛣️ How It Works
1. **Graph Representation:** 
   - Cities are represented as nodes.
   - Travel options (bus, flight, train) are represented as edges between the nodes.
   - Each edge has a weight (distance/time) that defines the travel time or distance for that option.

2. **Dijkstra's Algorithm:** 
   - The algorithm computes the shortest path between the source and destination cities considering all travel options (bus, flight, or train).
   - The path may vary depending on the selected mode of transport.

3. **Travel Options:** 
   - **Bus:** Represented by orange-colored edges. A slower, more affordable option.
   - **Flight:** Represented by green-colored edges. A faster travel option.
   - **Train:** Represented by different colors, providing a balance between speed and affordability.



## 📥 Setup & Installation

Clone the repository and run the application:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm install

# Step 4: Run the project.
npm start
```

4. **Interactive UI:**
   - Users input their **source** and **destination** cities.
   - The application calculates the shortest path and provides travel time/distance for each available option.
   - The graph visualizes the selected route and the edges representing the travel modes.
 
