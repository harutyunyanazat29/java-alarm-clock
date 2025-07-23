# ⏰ Simple Java Alarm Clock

This is a **console-based Java alarm clock** that lets you:
- Set an alarm by typing a time (in `HH:mm:ss` format)
- See the real-time clock ticking in the terminal
- Play a sound (a `.wav` file) when the alarm time is reached
- Stop the alarm by pressing Enter

---

## 🛠️ Features

- Uses `java.time.LocalTime` for accurate time tracking
- Plays `.wav` audio with `javax.sound.sampled`
- Simple multithreaded design with a responsive user interface
- Minimal dependencies — just Java SE

---

## 📦 Files

| File          | Purpose                                 |
|---------------|------------------------------------------|
| `Main.java`   | Entry point of the app (alarm setup)     |
| `AlarmClock.java` | Background alarm logic & sound playback |
| `A Caring Friend.wav` | Alarm sound (you can replace it with any `.wav` file) |

---

## 💻 How to Install & Run Locally

### 🧾 Prerequisites

- Java **JDK 8 or higher** installed
- An IDE (like IntelliJ IDEA) or terminal setup for running Java
- A `.wav` sound file named `A Caring Friend.wav` in your root folder  
  (you can rename your favorite `.wav` file or download one)

### 📥 Installation Steps

#### 1. Clone or download the project

```bash
git clone https://github.com/your-username/java-alarm-clock.git
cd java-alarm-clock
