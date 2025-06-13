# 🌞 Solar-Powered Steam Generator for Rural Electricity

This project aims to develop a **low-cost, solar-powered steam generator** that can be used to produce electricity in **rural or off-grid areas**. The system works by focusing sunlight using a **parabolic reflector** to heat water into **pressurized steam**, which can later be used to drive a small turbine or power generator.

## 🛠️ Project Status

**✅ Parabolic Dish Modeling (Completed)**  
The first milestone — creating an accurate 3D model of the **parabolic concentrator dish** — is complete. The model was created in **FreeCAD**, and the `.FCStd` file is included in this repository.

Next steps include:
- Designing the **receiver coil** to be placed at the focus point
- Simulating heat transfer and steam generation
- Prototyping with real-world materials
- Integrating **automation (ESP32)** and pressure regulation

## 📁 Files Included

- `parabolic_dish.FCStd` — FreeCAD model of the concentrator dish
- (Coming soon) Thermal simulation files, receiver designs, physical testing data

## 🔍 Design Highlights

- Parabolic curve based on the equation:  
 `y = 0.005x^2,   with  f = 0.5 m`
- Created using **B-spline sketching**, revolved around central axis in FreeCAD
- Geometry fixes included resolving:
  - Open wire profile errors
  - Axis intersection during revolution
  - Sketch translation issues inside FreeCAD’s Sketcher

## 🎯 Why This Project?

Rural electrification still remains a challenge in many parts of the world. This project is an attempt to explore **clean, small-scale energy systems** that can be:
- Built with **affordable materials**
- Powered entirely by the **sun**
- Repaired or scaled locally

## 🔧 Tools & Technologies

- `FreeCAD` (3D modeling)
- `ESP32` (for future automation)
- `Python / Arduino` (planned control system)
- `Blender / Fusion` (optional renders)
- Basic thermal physics, solar tracking (planned)

## 📸 Preview

![Parabola Dish Slice Graph Plot](./document/parabola%20slice.png)
*A screenshot of the graph for plotting the curve of the parabola.*

![Parabolic Dish Render](./document/Screenshot%202025-06-09%20171413.png)  
*A render of the completed 3D parabolic reflector model.*

## 📌 Roadmap

- [x] Design and model parabolic reflector
- [ ] (Fixing potential issues and reiterating)
- [ ] Build physical prototype using reflective surface
- [ ] Boil water and measure steam output
- [ ] Develop pressure control + safety system
- [ ] Add small-scale turbine or generator

## 🤝 Contributions & Feedback

This project is in its early phase — if you're working on similar renewable energy solutions or want to collaborate, feel free to open an issue or connect with me on [LinkedIn](www.linkedin.com/in/husainlokii).

## 📜 License

This project is open-sourced under the **MIT License**.

---

