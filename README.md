# Multi Event Countdown Timer | WebApp

MultiEventCountdownTimer is a modern, responsive one-page webapp that lets you manage multiple countdowns and stopwatches with real-time audio and visual alerts. All data is stored locally and can be imported/exported as JSON—no backend, no dependencies, no build step.

---

## 📺 Live Demo

https://bocaletto-luca.github.io/MultiEventCountdownTimer/index.html

---

## 🚀 Features

- **Multiple Events**  
  • Create unlimited countdown timers and stopwatches  
  • Name each event for easy identification  

- **Real-Time Alerts**  
  • Audio beep when a countdown reaches zero  
  • Card flashes green for 10 seconds as a visual cue  

- **JSON Import / Export**  
  • Export your entire event list as a JSON file  
  • Import a JSON file to restore or replace events  

- **Responsive Design**  
  • Mobile-first layout using CSS Grid & Flexbox  
  • Single HTML/CSS/JavaScript file, zero external libraries  

- **GPLv3 Licensed**  
  • Open-source under the GNU General Public License v3.0  

---

## 📁 Repository

https://github.com/bocaletto-luca/MultiEventCountdownTimer

---

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)

### Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/bocaletto-luca/MultiEventCountdownTimer.git
   ```
2. Open `index.html` in your browser  

---

## 🎯 Usage

1. **Add an Event**  
   - Enter an event name.  
   - Choose **Countdown** or **Stopwatch**.  
   - For countdowns, set a target date & time.  
   - Click **Add Event**.  

2. **Manage Events**  
   - **Delete**: remove an event.  
   - **Start/Pause** (stopwatches only): toggle timing.  
   - **Reset** (stopwatches only): clear elapsed time.  

3. **Alerts**  
   - Countdown timers beep when they hit zero.  
   - The event card flashes green for 10 seconds.  

4. **Import / Export**  
   - Click **Export JSON** to download your events.  
   - Click **Import JSON** and select a previously exported file to restore events.  

---

## 🧰 Technologies

- HTML5 & CSS3 (Grid, Flexbox, Custom Properties)  
- Vanilla JavaScript (ES6)  
- Web Audio API for beep alerts  
- LocalStorage for data persistence  
- No external libraries or build tools  

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository  
2. Create a new branch  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your fork  
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request on GitHub  

---

## 📄 License

This project is licensed under the [GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html).

---

## 👤 Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
- Live Demo: https://bocaletto-luca.github.io/MultiEventCountdownTimer/index.html
