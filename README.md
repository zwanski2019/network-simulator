# Network Fundamentals Simulator

An interactive, browser-based simulator designed to help students and professionals visualize and understand core network concepts. Explore common network topologies, compare hub vs. switch behavior, and see how transmission modes affect data flow—all without installing any software.

## 🚀 Features

* **Topology Simulation**: Visualize Star, Bus, Ring, and Mesh networks.
* **Device Behavior**: Compare how a Hub (broadcast) vs. a Switch (learned forwarding) handles traffic in a Star topology.
* **Transmission Modes**: Animate Simplex, Half‑Duplex, and Full‑Duplex communication between two nodes.
* **Lightweight & Standalone**: Pure HTML, CSS, and JavaScript—no dependencies or build steps.

## 📁 Project Structure

```bash
network-simulator/
├── network_simulation.html   # Main interactive simulator page
├── README.md                 # Project documentation and instructions
├── LICENSE                   # MIT License
└── .gitignore                # Files to ignore in Git
```

## 🖥️ Getting Started

### Prerequisites

* A modern web browser (Chrome, Firefox, Edge, Safari).

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/network-simulator.git
   ```
2. **Navigate into the folder**

   ```bash
   cd network-simulator
   ```
3. **Open the simulator**

   * Double‑click `network_simulation.html`, or
   * Serve it via a local HTTP server:

     ```bash
     # Python 3
     python3 -m http.server 8000
     open http://localhost:8000/network_simulation.html
     ```

## 🌐 Deploying with GitHub Pages

1. Push the repository to GitHub under the name `network-simulator`.
2. In your repository’s **Settings > Pages**, select the **main** branch and `/ (root)` folder.
3. Save; the simulator will be available at:

   ```
   ```

https\://<your-username>.github.io/network-simulator/network\_simulation.html

```

## 🎓 How to Use

1. **Choose a topology** from the dropdown to see nodes and links drawn automatically.  
2. **Select a device type** (Hub or Switch), pick source/destination nodes, and click **Send Packet** to observe traffic behavior.  
3. **Switch transmission modes** (Simplex, Half‑Duplex, Full‑Duplex) and click **Transmit** to animate packet flow.

Use this tool to demonstrate how different network designs and devices impact performance, reliability, and traffic flow.

## 🔧 Customization

- **Add more nodes** by editing the `starCoords` array in the JavaScript.  
- **Adjust styling** via the `<style>` section in the HTML.  
- **Extend the simulator** to include VLANs, QoS, or other advanced features.

## 📚 References

- Kurose, J. F., & Ross, K. W. (2017). *Computer Networking: A Top-Down Approach* (7th ed.). Pearson.  
- Tanenbaum, A. S., & Wetherall, D. J. (2011). *Computer Networks* (5th ed.). Pearson.  
- Bombal, D. (n.d.). *Network basics, topologies, and devices* [YouTube videos].

## 📝 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

```
