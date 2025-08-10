# BlurryLoading

![](./src/BlurryLoading.gif)

✅This project is an **HTML + CSS + JavaScript** based animation example where the background image gradually becomes less blurry as the page loads, and the text opacity changes at the same time.

## ✨ Features

- 🎯 **Dynamic blur**: Blur decreases as loading progresses.
- 🌗 **Opacity transition**: Text opacity fades from 100% to 0%.
- ⚡ **Lightweight & fast**: Built with just HTML, CSS, and JS.
- 📱 **Responsive design**: Works on all screen sizes.

## 🛠️ Technologies Used

- 🖋 **HTML5** – Structure
- 🎨 **CSS3** – Styling and animations
- 🧠 **JavaScript (Vanilla)** – Manages loading progress and the scale function

## 📜 Key Code

```javascript
function scale(number, inMin, inMax, outMin, outMax) {
  return ((number - inMin) * (outMax - outMin)) / (inMax - inMin) + outMin;
}

