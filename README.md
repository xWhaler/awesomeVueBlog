Portfolio Blog
 Built with Go (Gin Gonic), Vue, and TailwindCSS, the site showcases blog posts, projects, and professional experience.


🔧 Features
📰 Blog rendering with Markdown support

🗂️ Dynamic project listing from GitHub API

📘 Vue-powered frontend with responsive TailwindCSS UI

🧠 RAG/AI Engineering project highlights

📇 Profile card with live status and skills

🔒 Secure routing and scalable Go backend

🛢️ MariaDB Integration for Content Storage

## 📁 Project Structure

<h5>
main.go # Gin Gonic entry point

templates/ # HTML templates (index, base, posts, about, etc.)


static/ # Static assets (CSS, images, icons)

handlers/ # Route handlers for each page

models/ # DB models for posts and metadata

views/ # Vue components (for hybrid rendering)

README.md # You are here

Copy
Edit

 
</h5>



<img src="https://github.com/user-attachments/assets/afafd7ae-b708-40bb-b0ac-1c4bda3a86eb" style="width: 600px; height: 450px;"></img>

##  🚀 Running the App
1. Prerequisites:

Go 1.20+

Node.js (for Vue build, if used)

MariaDB with a database named content containing tables like all_posts

### Replace database name "content" and table name "all_posts" with your credentials. 
##### Also modify the connection string for the db to use your specified database.


## 3. Run the server:
```
go run main.go
```
4. Access via:
```
http://localhost:8080
```
📦 Deployment
Reverse proxy with Caddy or Nginx recommended
```
Set GIN_MODE=release in production
```
Optional: Use Docker for containerized deployment


☕ Support
If you enjoy the content or find the guides helpful:


