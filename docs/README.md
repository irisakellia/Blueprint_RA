# Robotic Arm

A 3D robotic arm designed and modeled in Blender, demonstrating realistic joint movement and mechanical structure.

## Overview

This project features a detailed 3D model of a robotic arm created entirely in Blender. The design showcases realistic mechanical components, including multiple joints, a gripper end-effector, and proper pivot points for animation. The model demonstrates professional 3D modeling techniques and serves as both an educational resource and a foundation for further robotic arm development.

## Originality Note

This robotic arm design features a unique combination of:

- **Modular joint system** with realistic servo motor housings
- **Custom gripper mechanism** with articulated fingers
- **Industrial aesthetic** with brushed metal textures and LED indicators
- **Optimized geometry** for both 3D printing and animation
- **Professional lighting setup** for high-quality renders

## Tools Used

- **Blender 3.6+** - Primary 3D modeling and animation software
- **Cycles Renderer** - Advanced ray-tracing for photorealistic renders
- **Eevee Renderer** - Real-time rendering for quick previews
- **Python Scripting** - Custom automation for repetitive tasks
- **UV Mapping** - Professional texture unwrapping techniques

## How to Recreate

### Opening the Model

1. Download and install Blender 3.6 or later
2. Open `robotic_arm.blend` from the `/models` directory
3. Ensure all file paths are relative (recommended for portability)

### Rendering the Model

1. **Camera Setup**: The scene includes a pre-configured camera
2. **Lighting**: Three-point lighting system is already set up
3. **Materials**: All materials use Cycles-compatible shaders
4. **Render Settings**:
   - Resolution: 1920x1080 (Full HD)
   - Samples: 256 (for final renders)
   - Engine: Cycles (recommended)

### Animation

1. Switch to **Animation Workspace**
2. Use the **Timeline** to scrub through keyframes
3. Joint rotations are parented for realistic movement
4. Export animations using **File > Export > FBX** or **Alembic**

## Render Previews

### Front View

![Front Render](render_front.png)
_Front perspective showing the complete robotic arm assembly_

### Side View

![Side Render](render_side.png)
_Side profile highlighting the joint articulation and proportions_

### Animation Demo

![Animation Demo](robotic_arm_demo.mp4)
_Demonstration of the robotic arm's range of motion and gripper operation_

## File Structure

```
Robotic-Arm/
├── models/
│   ├── robotic_arm.blend      # Main Blender project file
│   ├── robotic_arm.obj        # Wavefront OBJ export
│   └── robotic_arm.stl        # 3D printing ready STL
│   └── robotic_arm.mtl        # 3D printing ready mtl
├── renders/
│   ├── render_front.png       # Front view render
│   ├── render_side.png        # Side view render
│   └── robotic_arm_demo.gif   # Animation demonstration
└── docs/
    ├── README.md              # This file
    ├── BOM.csv                # Bill of Materials
    └── journal.md             # Development log
```

## Credits

- **Base Model**: Original design based on 075-robot.blend model
- **Metal Textures**: AmbientCG (CC0 License) - https://ambientcg.com
- **Lighting Setup**: Inspired by professional product photography techniques
- **Joint Mechanics**: Based on real-world robotic arm specifications

## Technical Specifications

- **Polygon Count**: ~15,000 faces (optimized for real-time)
- **Texture Resolution**: 2048x2048 (4K ready)
- **Animation Frames**: 120 frames (5 seconds at 24fps)
- **File Size**: ~25MB (Blend file with textures)

## License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## Future Enhancements

- [ ] Add inverse kinematics (IK) rigging
- [ ] Create assembly/disassembly animation
- [ ] Add more gripper variations
- [ ] Implement physics simulation
- [ ] Create VR/AR compatible exports
