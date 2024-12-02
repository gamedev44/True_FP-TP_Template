# **True First-Person & Third-Person Template**

## **Overview**
This template is a powerful and flexible starting point for Unreal Engine 5.4 + Projects and Beyond, eliminating the need for separate first-person and third-person templates. It provides a **true first-person experience with full-body awareness**, including **spine/lean rotational movement**, and a smooth **camera switch system**. 

Features include:
- **C#Sharp> Supported Scripting:** Currently its not being Used But Within the Plugins Folder theres a C# Plugin Enabling the usage of C# in Unreal Engine it Simply Needs Compiling to Start Using it you can find it here: ```"True_FP-TP_Template\Plugins\UnrealSharp\Source\Source.generated.sln".```
- **True First Person Camera:** Immersive First Person Camera System with Full Anti-Wall Collision made From Scratch.
- **Improved Follow Camera:** Tweaked and Improved the Third Person Follow Camera's Camera Boom Offset Settings and added Full Anti-Wall Collision and Smooth Lag to make it Look and Function Better.
- **Toggle First/Third-Person Modes:** Press `V` (keyboard) or the **left D-pad** (controller) to seamlessly switch perspectives.
- **Fully Networked Server Replication:** Built with Later Potential Usage for Multiplayer in Mind Making sure that True Spine Movement is Replicated.

Upcoming Features in v1.5 Planned for Completion on (12/15/2024):
- **Planned Updates:** 
  - **Crouch System**
  - **Top-Down Camera Option**
  - **Professionally Styled Menus:** Main menu, pause menu, and UI with starter textures and brushes.
  - **Simple AI System:** Basic Ai NPC's With Navigation and Simple Sight Awareness behavior.

---

## **Getting Started**

### **Requirements**
Before cloning the repository, ensure you have **Git LFS (Large File Storage)** installed and set up on your system.

1. **Create a New Folder**  
   Choose a location for your project, then create and name a new folder.

2. **Open Terminal/Command Prompt in the Folder**  
   - Navigate to the newly created folder.
   - Open it in **Windows File Explorer**, click the **address bar**, type `cmd`, and press **Enter**.

3. **Initialize Git LFS**
   Run the following command to set up Git LFS:
   ```bash
   git lfs install
   ```

4. **Clone the Repository**  
   Run this command to clone the template into your folder:
   ```bash
   git clone https://github.com/gamedev44/True_FP-TP_Template.git
   ```

5. **Navigate to the Cloned Repository Folder**  
   Once cloned, go to the repository folder where the project resides.

---

## **Git LFS Setup**
Ensure the repository is configured correctly by running these commands **in the repository folder**:

1. **Initialize Git LFS (again, just to ensure proper setup):**
   ```bash
   git lfs install
   ```

2. **Fetch All LFS Files:**
   ```bash
   git lfs fetch --all
   ```

3. **Check Out LFS Files:**
   ```bash
   git lfs checkout
   ```

4. **Pull Any Remaining LFS Files:**
   ```bash
   git lfs pull
   ```

Once these steps are complete, the project is ready to use.

---

## **Usage**
1. Open the Uproject in **Unreal Engine (5.4.4)**.
2. Explore and modify the full-body first-person and third-person systems to suit your needs.
3. Test the smooth camera switching (`V` key or **left D-pad**).
4. Look forward to planned updates, including menus, UI systems, and a basic AI framework.

---

## **Support & Contributions**
If you encounter any issues or have ideas for improvements, feel free to open an issue or contribute to the repository!