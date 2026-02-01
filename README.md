# 💕 AlwaysMine - Valentine's Day Proposal Website

A beautiful, interactive Valentine's Day proposal website built with React and Vite. Features animated GIFs, music, and a playful "mouse stealer" component that makes saying "no" increasingly difficult!

## ✨ Features

- 🎵 **Dynamic Music** - Different songs for "Yes" and "No" responses
- 🎭 **Animated GIFs** - Cute animations that change based on user interaction
- 🖱️ **Mouse Stealer** - Playful component that "steals" the cursor when hovering over "No"
- 💖 **Floating Emojis** - Heart and sad emojis appear on button hover
- 🎨 **3D Background** - Beautiful Spline 3D scene
- 📱 **Responsive Design** - Works on all devices

## 🚀 Live Demo

[View Live Website](https://your-vercel-url.vercel.app)

## 🛠️ Technologies Used

- **React** - Frontend framework
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling
- **Spline** - 3D background animations
- **SweetAlert2** - Beautiful popup modals

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/ankitkumar565/AlwaysMine.git
cd AlwaysMine
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

## 🎯 How It Works

1. **Initial Question**: "Will you be my Valentine?"
2. **Yes Response**: Shows love animations and plays romantic music
3. **No Response**: 
   - Button text changes to increasingly desperate messages
   - Plays sad/rejection music
   - After multiple "No" clicks, activates mouse stealer
   - Eventually shows heartfelt popup messages

## 🎨 Customization

- **Music**: Replace audio files in `src/assets/AudioTracks/`
- **GIFs**: Update animations in `src/assets/GifData/`
- **Messages**: Modify button text and popup messages in `App.jsx`
- **Styling**: Customize colors and animations in Tailwind classes

## 📁 Project Structure

```
src/
├── assets/
│   ├── AudioTracks/     # Music files
│   ├── GifData/         # Animation GIFs
│   └── ...
├── Preloaders/          # Loading components
├── App.jsx              # Main component
├── MouseStealer.jsx     # Mouse stealing component
├── MarqueeProposal.jsx  # Scrolling text component
└── ...
```

## 🤝 Contributing

Feel free to fork this project and make it your own! Some ideas:
- Add more animations
- Include different music genres
- Create themed versions (Christmas, Birthday, etc.)
- Add more interactive elements



## 💝 Made with Love

Created with ❤️ by [Ankit](https://github.com/ankitkumar565)

---

⭐ If you liked this project, please give it a star on GitHub!
