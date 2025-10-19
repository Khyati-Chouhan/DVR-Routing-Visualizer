# DVR Routing Visualizer

**DVR Routing Visualizer** is an interactive web-based simulator for the **Distance Vector Routing (DVR)** algorithm. It provides an intuitive visual interface to understand how routing tables are formed and updated dynamically across nodes in a network. The simulator supports **loop-prevention techniques**, **link failure simulation**, and **step-by-step visualization** of route propagation — making it a powerful educational and debugging tool for network learners and engineers.

The project demonstrates a deep understanding of **Computer Networks**, **Graph Algorithms**, and **Frontend Development** using modern web technologies. It enables real-time exploration of how changes in topology affect routing decisions in distributed systems.

**Live Demo:** [https://dvr-cn.vercel.app/](https://dvr-cn.vercel.app/)

---

## Project Goal

Routing algorithms form the backbone of data communication networks. However, their distributed and iterative nature can make them challenging to visualize and debug.

The goal of this project is to:
- Simulate **Distance Vector Routing** in a clear, interactive interface.  
- Visualize **routing table updates** in real time.  
- Demonstrate **loop prevention** and **split horizon techniques**.  
- Allow users to **add/remove nodes or links dynamically**.  
- Provide a hands-on learning platform for **Computer Networks** courses and labs.

---

## Tech Stack

- **Frontend:** React, Next.js, Tailwind CSS  
- **State Management:** React Hooks / Context API  
- **Visualization:** D3.js (for dynamic graph rendering)  
- **Deployment:** [Vercel](https://vercel.com)  
- **Language:** JavaScript / TypeScript  

---

## Key Features

- **Dynamic Topology:** Add or remove nodes and links interactively.  
- **Routing Table Visualization:** Observe live table updates for each node.  
- **Loop Prevention:** Implements split horizon and triggered updates.  
- **Failure Simulation:** Test route recalculation after link or node failures.  
- **Step-by-Step Execution:** Visualize DVR iterations in slow motion for learning clarity.  

---

## How to Setup (Locally)


 Clone the Repository
```bash
git clone https://github.com/Khyati-Chouhan/DVR-Routing-Visualizer.git
cd DVR-Routing-Visualizer
```
Install Dependencies
```bash
npm install
```
Run the Development Server
```bash
npm run dev
```
Open in Browser
```bash
http://localhost:3000
```
## How to Deploy


Build the Project
```bash
npm run build
```
Start Production Server
```bash
npm start
```
Deploy easily on [Vercel](https://vercel.com), [Netlify](https://www.netlify.com), or [Render](https://render.com) for production use.  
You can access the live deployment here → [https://dvr-cn.vercel.app/](https://dvr-cn.vercel.app/)


