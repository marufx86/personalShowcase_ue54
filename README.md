# Unreal Engine 5 Portfolio Repository

Welcome to my Unreal Engine 5 portfolio repository! This collection showcases my development skills and creative implementations within Unreal Engine 5, highlighting a variety of features and techniques I've designed and built.

---

## Showcase Highlights

### 1. **Medieval-Inspired Character Models**
   - **Description:** Enhanced 3D character models for both male and female characters, inspired by the aesthetic of medieval-themed series.
   - **Details:** These models feature updated textures, animations, and rigging to deliver a high-quality, immersive experience.
   - ![image](https://github.com/user-attachments/assets/e4273cb7-db1c-4f73-8df9-d0dca55bc9b8)
   - ![image](https://github.com/user-attachments/assets/7325c715-0cfd-46b4-824b-fd48122781ee)

---

### 2. **Custom Slider and Progress Bar Hybrid Widget**
   - **Description:** A unique UI widget that combines the functionality of a slider and a progress bar, offering a more interactive user experience.
   - **Demonstration:** Check out the **"WidgetSlider"** level to see this widget in action.
   - **Location:** The widget blueprint (**WBP_SliderWithProgress**) and related assets are located in the **'UI'** folder.
   - ![image](https://github.com/user-attachments/assets/adf98420-d962-49b1-bd0b-c0751be7e773)

---

### 3. **Dynamic Widget Spawning at Mouse Cursor Location**
   - **Description:** A system for dynamically spawning and manipulating widgets based on the mouse cursor's position.
   - **Features:**
     - Press **'C'** to spawn a widget at the current mouse pointer location.
     - Press **'C'** again to spawn a new widget at the updated pointer location.
     - Hold **'C'** to move the widget dynamically with the mouse pointer.
     - Press **'X'** to hide the widget.
   - **Location:** Explore the **BP_My_Character** blueprint and **WBP_SpawnAtMouse** widget to see the implementation.
   - ![Untitled design](https://github.com/user-attachments/assets/16e4b3af-d4e0-4fd9-8fef-e3db0ff3f757)

---

### 4. **Click Widget Button to Change Image**
   - **Description:** A versatile widget button that toggles between two states changing an image and triggering actions.
   - **Use Cases:** Ideal for scenarios like character actions (sit/stand, fly/normal, walk/run) or toggling states (on/off).
   - **Functionality:** Clicking the button switches the image and state, and clicking again reverts it to its original form.
   - **YouTube Demo:** https://youtu.be/ZgktskVlHRs
   - ![Screenshot 2025-01-16 025323](https://github.com/user-attachments/assets/7a0cabce-88f5-441a-860c-d47c6c3f99ff)
   - ![Screenshot 2025-01-16 025337](https://github.com/user-attachments/assets/77d525a2-fd8f-4ed5-8533-409ac1627e76)

---

### 5. **Multiplayer Widget Value Replication System**
   - **Description:** A sophisticated voting system demonstrating real-time widget value replication across multiple clients in a multiplayer environment.
   - **Features:**
     - Interactive voting widget displaying two map options: **Jungle** and **Desert**.
     - Each map has its own dedicated vote button.
     - Real-time vote count synchronization across all connected clients.
     - Successfully tested with 4 simultaneous clients (Client 1, Client 2, Client 3, Client 4).
   - **Technical Achievement:** Widget value replication is notoriously challenging in Unreal Engine, and this implementation showcases a robust solution for synchronizing UI data across networked players.
   - **Functionality:** When any player votes for a map, the vote count instantly updates for all other players, ensuring everyone sees the same voting results in real-time.
   - **YouTube Demo:** https://youtu.be/ZgktskVlHRs

---

### 6. **3D Space Widget Button Interaction**
   - **Description:** An advanced implementation of interactive UI widgets placed directly in 3D world space, allowing players to interact with buttons as physical objects in the game environment rather than traditional 2D screen overlays.
   - **Technical Implementation:** The widget is embedded within a BP Actor and placed directly in the level, enabling full interaction capabilities including hover effects, button presses, and other interactive states.
   - **Features:**
     - Widgets exist as physical objects in 3D space that players can approach and interact with.
     - Full support for hover states, pressed states, and visual feedback.
     - Maintains all standard widget interaction functionality in a 3D environment.
   - **Use Cases:**
     - **Door Controls:** Interactive panels for opening/closing doors or activating mechanisms.
     - **Interactive Panels:** Control stations, computer terminals, or machinery interfaces.
     - **Item Information Displays:** Informational kiosks, product displays, or museum exhibits.
     - **Environmental Interactions:** Elevator buttons, vending machines, or any in-world interactive elements.
   - **Location:** Check the **WBP_ButtonInteraction** widget and BP_Door in the project files.
   <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d25446d5-3714-4143-b1dd-19affdf71771" />


---

This repository is a testament to my passion for game development and my ability to create innovative, interactive, and visually appealing experiences in Unreal Engine 5. Feel free to explore the content and reach out with any questions or feedback!

---

## Repository Structure

- **/UI**: Contains all UI-related assets, including the **WBP_SliderWithProgress**, **WBP_SpawnAtMouse**, **WBP_ButtonInteraction**, and multiplayer voting widget blueprints.
- **/Characters**: Includes the medieval-inspired character models and related assets.
- **/Maps**: Features demonstration levels such as **"WidgetSlider"** to showcase the implemented features.

---

## How to Use

1. Clone the repository to your local machine.
2. Open the project in Unreal Engine 5.4
3. Navigate to the respective folders or levels to explore the showcased features.

---
