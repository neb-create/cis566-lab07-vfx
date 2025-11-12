# VFX Lab Submission - Nico Kong

Final effect video:

https://private-user-images.githubusercontent.com/180119095/513529787-366e89a5-143a-455c-9dab-fafa00115051.mp4?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjI5Nzk2OTUsIm5iZiI6MTc2Mjk3OTM5NSwicGF0aCI6Ii8xODAxMTkwOTUvNTEzNTI5Nzg3LTM2NmU4OWE1LTE0M2EtNDU1Yy05ZGFiLWZhZmEwMDExNTA1MS5tcDQ_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUxMTEyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MTExMlQyMDI5NTVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZDNlNGU2MTQwNTI2ZDAwMzUxMGNmZjMyN2U4ODIyZmYzMGNmN2JkZWI0ZGFjM2YwZTQxYTFhMDAyYjNiMTc3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.4fP3YoPrk0eh18rBDcqiDhXhQe8pc5Cm5Rh5jxdjjC4

# Assignment Description

In this lab, you’ll create a **simple disintegration effect** in Houdini using procedural masking, noise, and animation techniques. You’ll learn how to build and animate a mask, apply it to geometry to break it apart over time, and enhance the result with deformation and motion for a visual effects-style look.

Start by setting up a test geometry (like Crag or Squab) and remesh it for consistent topology. Create a **mask attribute** using bounding boxes, distances, and turbulent noise to define where disintegration happens. Animate the mask values over time to control the effect’s spread. Then, use point operations (like **Point Split**, **Attribute VOPs**, and scaling transforms**) to fragment and fade geometry procedurally. Add extra layers of **noise-based deformation** or movement to make the effect more dynamic—try using time-based 3D noise for subtle flicker or dissolving motion.

Once the effect looks good, render it out with **Karma** over 1–80 frames and export your animation through MPlay using FFmpeg.  

---

**Submission:**  
Submit both your Houdini `.hip` file and the rendered animation video (`.avi`). The render should clearly show the disintegration evolving over time and demonstrate control over masking, animation, and procedural effects.
