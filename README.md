# VFX Lab Submission - Nico Kong



# Assignment Description

In this lab, you’ll create a **simple disintegration effect** in Houdini using procedural masking, noise, and animation techniques. You’ll learn how to build and animate a mask, apply it to geometry to break it apart over time, and enhance the result with deformation and motion for a visual effects-style look.

Start by setting up a test geometry (like Crag or Squab) and remesh it for consistent topology. Create a **mask attribute** using bounding boxes, distances, and turbulent noise to define where disintegration happens. Animate the mask values over time to control the effect’s spread. Then, use point operations (like **Point Split**, **Attribute VOPs**, and scaling transforms**) to fragment and fade geometry procedurally. Add extra layers of **noise-based deformation** or movement to make the effect more dynamic—try using time-based 3D noise for subtle flicker or dissolving motion.

Once the effect looks good, render it out with **Karma** over 1–80 frames and export your animation through MPlay using FFmpeg.  

---

**Submission:**  
Submit both your Houdini `.hip` file and the rendered animation video (`.avi`). The render should clearly show the disintegration evolving over time and demonstrate control over masking, animation, and procedural effects.
