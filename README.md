# cameramount

# 📷 3D Printed Stereo Camera Mount

This project features a custom-designed stereo camera mount built for use with a Raspberry Pi and stereo vision cameras in autonomous vehicle applications. Designed in **SolidWorks** and validated using **Finite Element Analysis (FEA)**, the mount is optimized for **FDM 3D printing** using **PLA**.

## 🛠️ Features

- **Supports**: Raspberry Pi + stereo vision camera pair
- **Material**: PLA (Polylactic Acid) for lightweight durability
- **Mounting**: Multiple slots for precise alignment and secure fit
- **Load Validation**: FEA simulations in SolidWorks ensure mechanical stability
- **Manufacturing Method**: Fused Deposition Modeling (FDM)

## 🧪 Simulation Results

| Metric              | Value          |
|---------------------|----------------|
| Max Displacement    | 0.0146 mm      |
| Von Mises Stress    | 0.445 MPa      |
| Yield Strength (PLA)| ~60 MPa        |
| Factor of Safety    | 112            |

## 📸 Gallery

| Displacement | Rendered View |
|--------------|----------------|
| ![Displacement](./mount1.jpg) | ![Render](./mount2.jpg) |

## 📦 Tools Used

- **SolidWorks** (CAD + FEA)
- **FDM 3D Printer**
- **Raspberry Pi**
- **Stereo Vision Cameras**

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/pranav15102/cameramount.git

2. Open the provided SolidWorks files to explore/edit the model.

3. Use the STL files to 3D print the mount with PLA material.
