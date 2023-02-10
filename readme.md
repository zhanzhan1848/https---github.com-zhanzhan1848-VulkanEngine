# Kohi Engine

Thanks for Travis Vroman (youtube: https://www.youtube.com/playlist?list=PLv8Ddw9K0JPg1BEO-RS-0MYs423cvLVtj). This is a greate tutorial for C and VulkanAPI.

# .plan
Kohi will be a 3D engine from the start, with most of it built from scratch with explanations along the way. The series starts off as more of a tutorial to get up and running, with explanations becoming higher level as things progress to keep the pacing up.

## .platform support
Windows and Linux are both supported from the start, with native (non-GLFW) Mac support to be added in the future. Android and iOS runtime support may also be added down the road.

You will need to have Clang and the Vulkan SDK installed:
 - Clang: https://releases.llvm.org/download.html
 - Vulkan SDK: https://vulkan.lunarg.com/
 - GLFW: https://www.glfw.org/ (macOS only)

See the setup videos in the series for Windows or Linux for details.

## .roadmap
 - Fully 3D engine with various lighting models and material types available (Basic 3d lighting, Physically-Based Rendering, etc.)
 - Cross-platform support (Windows and Linux to start, with Mac forthcoming)
 - Multiple rendering backends:
   - Vulkan first
   - Eventually adding OpenGL and DirectX and potentially Metal
 - Suite of editor tools
 - Asset/Game Code hot-reload support
 - Physics
 - 2D/3D Sound
 - Full-fledged UI system
 - Event system
 - Standard Keyboard/Mouse input along with eventual GamePad input

## .goal
The goal here is simple, to have a game engine capable of making games. Once the project is far enough along, this will be done as a series on my YouTube channel as well.
