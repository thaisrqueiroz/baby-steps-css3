# Baby Steps with HTML5 & CSS3 

## 🎨 About the project

A beginner-friendly project to practice basic HTML5 and CSS3 styling through web mockups. This project also includes a Docker setup for easy deployment.

![Html and CSS3](/assets/readme/html5-css3.png)
![Letters and background colours](/assets/readme/colores-letras-fondos.png)
![Gradient](/assets/readme/colores-degradado.png)

## 🛠️ Tools Used
- Visual Studio Code (Integrated development environment (IDE))
- HTML5 (Structure)
- CSS3 (Styling)
- Docker (Containerization)

## 📋 Project Overview
- Replicated pre-designed layouts with text and icons.
- Practiced multi-column designs with custom fonts and colors.
- Experimented with background colors.
- Docker integration for containerized deployment.

## 🚀 How to Run with Docker
Requirements:
> Install Docker desktop in your device. [Docker Desktop Download](https://docs.docker.com/desktop/)

1. Clone the repository from GitHub:

```
git clone https://github.com/thaisrqueiroz/baby-steps-css3.git
```

2. Build an image from the Dockerfile.
```
docker build -t <image-name> -f <dockerfile-name> .
```
For example:

```
docker build -t baby-steps-css -f Dockerfile
```

3. Run the image to start the container.
```
docker run -p 8080:80 --name <container-name> <image-name>
```
For example:
```
docker run -d -p 8080:80 --name baby-steps-css baby-steps-css
```

4. Open in your browser the port 8080:
> [Open the port](http://localhost:8080)


## 📂 Project Structure

```
├── index.html          (Main HTML) file
├── styles.css          (CSS styles)
├── Dockerfile          (Docker) configuration
└── assets/             (Folder for images)
```

## 💡 What I Learned
- HTML/CSS: Layouts, columns and color schemes.
- Docker: Image building, containerization, and port mapping.