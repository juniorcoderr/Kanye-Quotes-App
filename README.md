## Kanye Says... 🎤💬

A fun and simple Python app built with Tkinter that fetches and displays **random Kanye West quotes** using the Kanye REST API! 😎 When you click the button, a new inspirational (or hilarious) Kanye quote pops up, all wrapped up in a cool UI. 🚀✨

### Features 🌟:
- **Fetch Random Quotes**: Get a new Kanye quote with a click of a button! 📝
- **Interactive UI**: Built using Tkinter, a popular GUI toolkit in Python. 🖥️
- **Customizable Look**: Set your own background and Kanye image to make it uniquely yours. 🎨
- **User-Friendly**: Simple interface with a button to load quotes. 🔘

### Concepts Used 🤓:
- **Tkinter**: Used to create the graphical user interface (GUI). Tkinter provides widgets like buttons, labels, and canvases for building interactive applications. 🖼️
- **Requests**: The `requests` library is used to send an HTTP request to the **Kanye REST API** to fetch random quotes. 🌐
- **Canvas Widget**: The Tkinter `Canvas` widget is used to draw and display images (background & Kanye's image) and text (Kanye’s quote). 🎨🖼️
- **Button Widget**: The button allows users to fetch a new quote with a single click, making the app interactive. 🔘

### **What is an API?** 🌐💡
- **API (Application Programming Interface)**: An API is a way for different software programs to communicate with each other. Think of it as a messenger that allows one program to ask another program for data or services.
  
  In this app, the **Kanye REST API** is a web service that provides random quotes from Kanye West. The Python script sends a request to the API, asking for a new quote. The API responds with the data (the quote), and the app displays it in the GUI. 

- **How does it work here?**:
  1. **Request**: When you click the button, the app sends an HTTP request using the `requests` library to the API URL (`https://api.kanye.rest`).
  2. **Response**: The API sends back a JSON response containing the quote.
  3. **Display**: The app extracts the quote from the response and displays it on the screen.

APIs are everywhere! 🌍 They're the backbone of many modern applications, allowing them to interact with external services to get data, send information, or perform tasks. 🖥️🔗

### Requirements 📋:
- Python 3.x 🐍
- `requests` library for making API requests 📦
- Tkinter (usually comes with Python, so no install needed) 💻

### How to Run 🚀:
1. Install the required libraries:
   ```bash
   pip install requests
   ```
2. Make sure you have the `background.png` and `kanye.png` image files in the same directory as the script. (You can replace these with your own images! 🖼️)
3. Run the script:
   ```bash
   python kanye_says.py
   ```

Enjoy some wisdom from Kanye West and get inspired! 🎤💬🔥
