# Section B: Spatial Anchor & Placement System

## B1. Spatial Anchor

A Spatial Anchor defines where the Mixed Reality (MR) content appears in your physical environment.
- It determines where the virtual content is placed relative to the real world
- For example:
    - If you place the anchor in the middle of a room, the MR content will remain in the middle of that room
- Content remains fixed in position  
- Moves relative to your environment  

In-app appearance:
- Rectangular frame  
- Corner and in between corner strokes
- Innoveam Logo and some text

[Learn more about Spatial Anchor](https://developers.meta.com/horizon/documentation/unity/unity-spatial-anchors-overview/)

---

## B2. Placement System (2-Point System)

### B2.1 How It Works
The Placement System defines how the spatial anchor is initialized.

For this application, a 2-point placement system is used, especially important for collaborative multiplayer experiences to ensure all users see synchronized content.

- Point 1 → Center (pivot)  
- Point 2 → Orientation (north direction)  

---

### B2.2 Example

- Point 1 in front + Point 2 above  
→ Upright (north away from you)

- Point 1 in front + Point 2 below  
→ Upside down (north toward you)

Key Insight:
- Point 1 control the placement of the spatial anchor while point 2 controls the orientation  

---

### B2.3 Best Practice

- Mark both points physically on the real world environment
- Ensures easy and consistent setup in the event the app crash or disconnected

---

### B2.5 Adjusting Anchor

- Use Grip button to manualy move the anchor
- For fine tuning, there will be a UI menu to adjust:
  - Altitude/Height (Up, down) 
  - Rotation/Yaw (Clockwise, Counter-clockwise) 
  - Lateral (Forward, Backward, Left, Right)

### B2.6 Multiplayer Note

- Avoid excessive adjustment to prevents desynchronization  

## You have completed this section
- You can move to the next section [Section C](C-deployment.md)