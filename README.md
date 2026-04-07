<div align="center">
  <img src="assets/logo.png" alt="Map Logo" width="128" />
  <h1>🌍 Interactive 3D Web Map</h1>
  <p>Explore the Minecraft world interactively from your web browser!</p>
</div>

---

## 🚀 How to View the Map Locally

Modern web browsers have security restrictions (CORS) that prevent loading local files via `file://` protocol. To view the map locally on your machine, you must serve the directory using a simple local web server.

### Prerequisites
You need a basic web server running on your computer. Below are the easiest ways to start one, depending on what software you have installed.

#### Option 1: Python (Default on macOS / Linux)
Open your terminal, navigate to this folder, and run:
```bash
# For Python 3
python3 -m http.server 8000

# For Python 2
python -m SimpleHTTPServer 8000
```
Then, open your web browser and go to: [http://localhost:8000](http://localhost:8000)

#### Option 2: Node.js (npx)
If you have Node.js and npm installed, use `http-server`:
```bash
npx http-server -p 8000
```
Then, open your web browser and go to: [http://localhost:8000](http://localhost:8000)

#### Option 3: PHP
If you have PHP installed on your system:
```bash
php -S localhost:8000
```
Then, open your web browser and go to: [http://localhost:8000](http://localhost:8000)

---

## 🗺️ Map Data Overview
This map contains rendered data for different dimensions:
- **Overworld:** Available in `maps/overworld`
- **Nether:** Available in `maps/nether`
- **The End:** Available in `maps/end`

---

## 🌐 Hosting Online

### GitHub Pages
To host this map for free on GitHub Pages:
1. Create a new GitHub repository.
2. Push all the contents of this folder to the `main` or `master` branch.
3. Go to the repository **Settings** -> **Pages**.
4. Select the branch where your files are and save. Your map will be live shortly!

### Web Server (Apache / Nginx / Caddy)
Simply upload all the contents of this folder to your web server's public directory (e.g., `/var/www/html/`). No database or server-side scripting (like PHP) is strictly required to view the map.

---

*Note: The map viewer is powered by BlueMap or a similar web-based map renderer.*
