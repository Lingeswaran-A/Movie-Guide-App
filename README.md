# 🎬 Movie Guide App

A sleek and responsive Movie Guide App that allows users to search for any movie and instantly fetch its **Poster**, **Rating**, **Storyline**, and **Cast details** using the OMDB API (https://www.omdbapi.com/).

## ✨ Features

- 🔍 **Real-Time Movie Search** by name  
- 🖼️ Movie **Poster Display**  
- ⭐ IMDB **Ratings**  
- 📖 **Plot Summary**  
- 👨‍🎤 Full **Cast Listing**  
- 🎭 Genre and runtime details  
- 📱 Fully **Responsive UI**

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript  
- **API:** OMDB API  
- **Styling:** Responsive design with CSS Flex/Grid


## 🧠 How It Works

1. User enters a movie name in the search bar.  
2. JavaScript constructs a request to the **OMDB API** with the provided movie name.  
3. Upon successful fetch, the app dynamically renders:
   - 🎞️ Poster
   - 🏷️ Title & Year
   - ⭐ IMDB Rating
   - 🎭 Genre & Runtime
   - 📖 Plot and 👥 Cast
   

## 🔑 API Reference

This project uses the free OMDB API(https://www.omdbapi.com/) to fetch movie data.
- Get your API key from: [OMDb API Key Signup](http://www.omdbapi.com/apikey.aspx)
- Replace the key in `key.js`

# 🚧 To Run Locally
Clone the repository:

```git clone https://github.com/Lingeswaran-A/Movie-Guide-App.git```


Navigate to the project folder:

```cd Movie-Guide-App```


Add your OMDB API key to key.js:

```key = "your_omdb_api_key";```
Open index.html in your browser.


✅ No backend or build tools needed — it's 100% front-end!


# 📄 License
This project is licensed under the MIT License.
