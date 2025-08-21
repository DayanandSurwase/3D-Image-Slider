# 3D Image Slider Component

A simple, modern 3D image slider built with **pure HTML and CSS**. This component leverages CSS transform properties to create a **cylindrical, rotating showcase of images**, making it perfect for portfolios, galleries, or hero sections on any website.

---

##  Features

-  3D Perspective  
  Uses CSS `perspective` and `transform` properties to create a realistic 3D rotation effect.

-  Pure CSS Animation  
  Smooth, seamless rotation using CSS keyframes—**no JavaScript required**.

-  Easily Customizable  
  Add or remove images by modifying `index.html` and updating the `--total` CSS variable.

-  Lightweight  
  Minimalist setup ensures fast load times with zero external dependencies.

---

##  Project Structure
```
.
├── static/
│ ├── black.jpg
│ ├── captain.jpg
│ ├── hulk.jpg
│ ├── ironman1.jpg
│ ├── ironman2.jpg
│ ├── loki.jpg
│ ├── luffy-zoro.jpg
│ ├── strange.jpg
│ ├── thor.jpg
│ └── spiderman1.jpg
├── index.html
└── main.css

```

##  How to Use

1. **Open `index.html`:**  
   Simply open the file in your web browser to view the 3D image slider.

2. **Add Your Own Images:**

   - Place new image files inside the `static/` directory.
   - In `index.html`, duplicate an existing `.model` `<div>` block for each new image.
   - Update the `style="--index:X"` attribute with the correct image index (starting from 0).
   - Modify the `style="--total:X"` property on the `.slides` container to reflect the total number of images.

---

##  Example Usage (HTML Snippet)

```html
<div class="slides" style="--total:10">
  <div class="model" style="--index:0"><img src="static/black.jpg" /></div>
  <div class="model" style="--index:1"><img src="static/captain.jpg" /></div>
  <!-- Add more images following this structure -->
</div>
``` 
## License

This project is open-source and free to use under the MIT License.

