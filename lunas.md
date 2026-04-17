Got it — here’s your **full README.md**, restored to the richer/original detail but with **clean formatting, consistent numbering (A–E, steps), no emojis**, and **B2 properly consolidated**.

---

# Meta Quest 3 – Setup & LUNAS VR Application Guide

This guide covers the **full setup process**, from first-time headset configuration to deploying and using the LUNAS VR application.

---

## Prerequisites

Ensure you have the following before starting:

* A laptop (VR-ready recommended)
* Meta Quest 3
* Meta Horizon app (for first-time setup)
* Meta Horizon Link (installed on laptop)
* Meta Horizon account

---

# Section A: First-Time Setup (Headset & Connection)

---

### A1. Initial Headset Setup

* Set up your Meta Quest headset using the mobile app
  👉 [Setup Guide Link](link)

---

### A2. Learn Controller Basics

* Familiarize yourself with the Quest controllers, especially:

  * Trigger button
  * Grip button
  * Thumbstick
    👉 [Controller Guide Link](link)

---

### A3. Set Up Boundary (Guardian)

* Define your play area boundary inside the headset to ensure safe usage
  👉 [Boundary Setup Guide](link)

---

### A4. Install Meta Horizon Link

* Download and install Meta Horizon Link
  👉 [Download Link](link)

* Log in using your Meta Horizon account

* Complete the initial setup

---

### A5. Configure General Settings

Go to **Settings → General**:

* Enable **Unknown Sources**
* Under **OpenXR Runtime**:

  * Click **“Set Meta Horizon as active”**
  * Ensure the button becomes greyed out (this confirms activation)

---

### A6. Enable Developer Features

Go to **Settings → Developer**:

* Enable:

  * Developer Runtime Features
  * Passthrough over Meta Horizon Link

---

### A7. Connect Headset to Laptop

* Connect your headset using:

  * Air Link (Wireless), or
  * Link Cable (Wired)
    👉 [Connection Guide Link](link)

---

### A8. Verify Connection

* Wear the headset
* You should see:

  * A white environment with floor and ceiling gridlines

---

# Section B: Spatial Anchor & Placement System

---

### B1. Spatial Anchor

A **Spatial Anchor** defines where the Mixed Reality (MR) content appears in your physical environment.

* It determines where the virtual content is placed relative to the real world
* For example:

  * If you place the anchor in the middle of a room, the MR content will remain in the middle of that room
* The content will stay fixed in that position, even as you move around

**What You Will See in the App:**

* A rectangular frame
* Corner and edge strokes
* A central area displaying:

  * Company logo
  * Instructional text

👉 [Learn more about Spatial Anchors](link)

---

### B2. Placement System (2-Point System)

The Placement System defines how the spatial anchor is initialized.

For this application, a **2-point placement system** is used, especially important for collaborative multiplayer experiences to ensure all users see synchronized content.

---

#### B2.1 How It Works

* **Point 1 (First Placement):**

  * Defines the **center (pivot)** of the spatial anchor
  * Determines the position of the content in the real-world environment

* **Point 2 (Second Placement):**

  * Defines the **orientation (north direction)** of the spatial anchor
  * Controls how the content is rotated

---

#### B2.2 Example (Orientation)

The direction between Point 1 and Point 2 determines how the content is oriented:

* If you place:

  * Point 1 in front of you (on the floor)
  * Point 2 directly above Point 1

  → The spatial anchor and text will appear **upright**, as the “north” direction is facing **away from you**

* If you place:

  * Point 1 in front of you (on the floor)
  * Point 2 directly below Point 1

  → The spatial anchor and text will appear **upside down**, as the “north” direction is facing **towards you**

Key Insight:

* The second point controls **orientation**, not position

---

#### B2.3 Best Practice

* Physically mark the 2 points in the real-world environment (e.g. tape on the floor)
* This ensures:

  * Consistent placement
  * Easier setup
  * Better synchronization across users

---

#### B2.4 Adjusting the Spatial Anchor

After placing the anchor:

* Use the **Grip button** to:

  * Grab and move the anchor

* A UI menu will appear for fine adjustments:

  * Altitude (up and down)
  * Yaw / Rotation (clockwise and counter-clockwise)
  * Lateral movement (forward, backward, left, right)

---

#### B2.5 Important for Multiplayer

* Avoid excessive manual or fine adjustments
* Adjustments can cause **desynchronization between users**

Recommended:

* Use consistent 2-point placement instead of manual corrections

---

# Section C: Deploying the Application

---

### C1. Prepare the Application

* Ensure you have downloaded the LUNAS VR app
* Extract it to your desired location

---

### C2. Prepare Your System

* Ensure Meta Horizon Link is running on your laptop
* Ensure the Meta Quest 3 is:

  * Turned on
  * Paired with your laptop

---

### C3. Connect Headset

* Connect your headset using:

  * Air Link, or
  * Link Cable
* Refer to Section A7

---

### C4. Verify Connection

* Wear the headset
* Confirm you see the white grid environment

---

### C5. Launch the Application

* Go back to your laptop
* Run the LUNAS VR application

---

### C6. Load into the App

* Wear your headset
* You should see:

  * The environment change
  * The application loading

---

### C7. Anchor Placement (Inside the App)

You will see the instruction:

> “Air Pinch toward the floor to set the Position of the Anchor”

---

### C8. Place Point 1 (Center / Pivot)

* Use your controller
* Point toward the floor in front of you
* Press the Trigger button

---

### C9. Place Point 2 (Orientation)

* Place the second point

---

### C10. Anchor Appears

* The spatial anchor will appear
* Observe its placement and orientation

---

### C11. Adjust Placement (Optional)

* Use the Grip button to move the anchor
* Use the UI menu for fine adjustments if needed

---

### C12. Confirm Placement

* Press Confirm once you are satisfied

---

### C13. Start Using the Application

* The content will appear
* You can now use the application

---

# Section D: LUNAS App User Manual

---

### D1. Basic Interaction

* Use the Trigger button to:

  * Interact with UI
  * Select buttons
  * Confirm actions

---

### D2. Access Menu (Wrist UI)

1. Hold both controllers
2. Position your left controller in front of you
3. Rotate your wrist so the inner side is facing you

* A “Menu” or “Settings” button will appear

4. Use your right controller:

   * Point at the button
   * Press the Trigger button

* This opens the Settings Menu

---

### D3. Re-anchor Feature

* Located inside the Settings Menu

**Use when:**

* Content is misaligned or incorrectly positioned

**Function:**

* Resets the spatial anchor
* Re-initiates placement (refer to Section B)

Best Practice:

* Use Re-anchor instead of excessive manual adjustment

---

# Section E: Troubleshooting

---

### E1. App Launched but No Content in Headset

**Likely Cause:**
Headset is not connected to the laptop

**Solution:**

1. Close the app
2. Ensure Meta Horizon Link is running
3. Reconnect the headset
4. Verify white grid environment
5. Relaunch the app

---

### E2. Unable to Connect Headset to Laptop

**Option 1: Restart Meta Horizon Link**

* Go to Settings → General
* Click “Restart Meta Horizon Link”
* Wait ~30 seconds

---

**Option 2: Restart OVRService**

1. Press CTRL + SHIFT + ESC
2. Go to Services tab
3. Find OVRService
4. Right-click → Restart

---

**Option 3: Restart Laptop**

* If both methods fail

---

### E3. Experience is Not Smooth

**Likely Cause:**
Weak connection between headset and laptop

**Solution:**

* If using Air Link, switch to Link Cable (wired connection)

---

## Final Notes

* Always verify connection before launching the app
* Use wired connection for stability during demos or training
* Restart Meta Horizon Link if unexpected issues occur

---

If you want, I can next turn this into:

* A **client-facing manual (less technical wording)**
* Or a **visual guide with diagrams for spatial anchor (very useful for training sessions)**
