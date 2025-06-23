# 🐶 Dog Image Gallery Web App

A simple, lightweight web app that fetches and displays random dog images using the **Dog CEO Dog API**.  
Users can load random images, search for specific dog breeds, and refresh the gallery dynamically.

---

## 📸 Features

- Fetches **5 random dog images** on page load.
- **Search by breed** (e.g., `husky`, `pug`, `labrador`).
- **Refresh button** to load a new set of random images.
- Clean, responsive UI built with **HTML, CSS, and Vanilla JavaScript**.
- Deployed easily using **GitHub Pages** / **Vercel**.

---

## 📦 Tech Stack

- **HTML**
- **CSS**
- **JavaScript**
- **Dog CEO Dog API** ([https://dog.ceo/dog-api/](https://dog.ceo/dog-api/))

---

## 🚀 How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/dog-gallery.git
   cd dog-gallery
````

2. **Open `index.html` in your browser**
   Or deploy it online via GitHub Pages or Vercel.

3. **Features on the page**

   * Enter a dog breed name in the input (e.g., `bulldog`) and click **Search Breed**.
   * Click **Load Random Dogs** to display new random images.

---

## 📚 How It Works

* Uses the **Dog CEO API** endpoint:

  * `https://dog.ceo/api/breeds/image/random/5` → Fetch 5 random images
  * `https://dog.ceo/api/breed/{breed}/images/random/5` → Fetch 5 images by breed
* Dynamically updates the DOM using JavaScript by creating `img` elements.
* Displays images using **Flexbox** layout for responsiveness.

---

## 🌐 Live Demo
![image](https://github.com/user-attachments/assets/30cc6a02-f731-4c01-a3c4-4195c7a6c264)

![image](https://github.com/user-attachments/assets/1b5254e5-95df-4274-916e-9e4787b0f302)



---

## 📌 License

This project is open-source and free to use.

```

---

## 📌 Notes:
- Replace `your-username` with your actual GitHub username.
- You can add a `screenshot.png` of your app and link it in the README too for extra polish.
