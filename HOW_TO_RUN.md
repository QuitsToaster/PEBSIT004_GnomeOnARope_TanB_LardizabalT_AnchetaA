Here you go — the **complete `STEPS_TO_RUN.md`** in ready-to-paste GitHub Markdown format:

````markdown
# Steps to Run Gnome on a Rope / Gnomes Well

## Opening in Unity Editor
1. **Clone or Download the Repository**  
   ```bash
   git clone https://github.com/QuitsToaster/PEBSIT004_GnomeOnARope_TanB_LardizabalT_AnchetaA.git
````

Or download as ZIP → extract to a local folder.

2. **Open in Unity Hub**

   * Launch **Unity Hub**.
   * Click **Add Project from Disk**.
   * Select the folder where the repository was cloned/extracted.

3. **Open the Main Scene**

   * In the Unity Editor, go to:
     `Assets/Scenes/MainScene.unity`

4. **Run the Game in Editor**

   * Press the **Play ▶️ button** on the top bar to start the game.

---

## Building a Playable Version

1. In Unity, go to:
   `File > Build Settings`
2. Select your target platform (Windows, Mac, Linux).
3. Add the `MainScene.unity` scene to the build list.
4. Click **Build and Run**.
5. The game executable will be created in the chosen folder.

---

## Running the Built Game

* **Windows:** Double-click the generated `.exe` file.
* **Mac:** Open the generated `.app` bundle.
* **Linux:** Run the generated executable:

  ```bash
  ./GnomeOnARope.x86_64
  ```

---

## Minimum System Requirements

* **OS:** Windows 10 / macOS 11 / Ubuntu 20.04 or later
* **CPU:** Intel i5 (4th Gen) / AMD Ryzen 3 or better
* **RAM:** 8 GB
* **GPU:** NVIDIA GTX 960 / AMD Radeon R9 280 or better
* **Storage:** 1 GB free space
* **Unity Editor (if running from source):** Unity 2021.3.5f1 (LTS)

---

## External Libraries / Plugins

* **Cinemachine** (Unity Package Manager) – Version 2.8.9
* **Input System** (Unity Package Manager) – Version 1.3.0

Both are available directly via Unity Package Manager:

* In Unity Editor → `Window > Package Manager` → search and install.



