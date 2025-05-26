

# 🖼️ Image Slider (Pure HTML, CSS & JavaScript)

A simple and beautiful responsive image slider (carousel) built using HTML, CSS, and JavaScript. This slider supports manual navigation via arrows as well as automatic transitions every few seconds.

## 📸 live  Demo : https://yuvashree9542.github.io/Image-Slidershow/ 
![Image](https://github.com/user-attachments/assets/5fcee9d8-1ebe-4805-8cae-8cd2a2320577)

## ✨ Features

* Responsive image slider layout
* Auto-play functionality (every 3 seconds)
* Smooth sliding animation
* Manual controls (previous/next arrows)
* Easy to customize with your own images

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/image-slider.git
cd image-slider
```

### 2. File Structure

```
image-slider/
├── index.html
└── images/
    ├── waterfall1.jpeg
    ├── waterfall2.jpeg
    ├── ...
```

### 3. Run the Project

Just open the `index.html` file in any modern web browser.

## 🛠️ Customization

* **Add or remove slides:**
  Modify the HTML inside the `.slides` container to include your own images.

* **Change interval time:**
  Adjust the timing in the `setInterval` function in JavaScript:

  ```js
  setInterval(autoSlide, 3000); // Change 3000 to your preferred interval (in ms)
  ```

* **Change arrow position or design:**
  Modify the CSS classes `.arrow.left` and `.arrow.right`.

## 🧠 Technologies Used

* HTML5
* CSS3 (Flexbox, Transitions)
* Vanilla JavaScript

## 📜 License

This project is licensed under the [MIT License](LICENSE).

