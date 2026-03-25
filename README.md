# Lunera
Lunera-AI Prompt and Rendering App for Mac and Windows
Lunera
Lunera is a hybrid AI prompt generation and image rendering platform designed to give creators full control over how AI-generated images are built, styled, and refined.

It combines fast cloud-based generation with powerful local workflows, allowing both beginners and advanced users to create high-quality results with precision.
Overview
Lunera operates in two core modes:
Cloud Mode (Gemini)
- Fast image generation with no setup
- Supports reference images for guided outputs
- Ideal for rapid prototyping and finished visuals
Local Mode (ComfyUI)
- Full control over rendering pipelines
- Supports SDXL and Flux workflows
- Offline generation with advanced customization
- Designed for high-end and production-level workflows
Key Features
Prompt Builder
- Structured prompt system for consistent results
- Control over style, tone, realism, and composition
- Copy-ready prompts for reuse across engines
Style Library
- Hundreds of curated base styles
- Organized into clear categories
- Includes photorealistic, cinematic, artistic, and specialty styles
Reference Image Support
- Upload multiple images to guide outputs
- Maintain identity, pose, and composition
- Ideal for character creation and branding
Preview System
- Multi-image preview panel
- Rapid iteration and comparison
- Optimized for fast visual feedback
Advanced Face Swap (Local Mode)
Lunera integrates advanced face swap workflows using ReActor:

- High-accuracy identity matching
- Multi-face targeting support
- Adjustable swap strength and restoration
- Designed to match direct ComfyUI output quality
Recommended Settings
- Swap Model: inswapper_128.onnx
- Restore Model: codeformer-v0.1.0.pth
- Restore Visibility: 0.5
- CodeFormer Weight: 0.5
- Target Node Hint: target
- Source Node Hint: source, face, a
System Requirements
macOS
- macOS 13+ (Ventura or newer)
- Apple Silicon (M1 or newer)
- 16 GB RAM minimum (32–64 GB recommended)
- 20 GB free storage (100+ GB recommended)
Windows
- Windows 10/11 (64-bit)
- 16 GB RAM minimum
- NVIDIA GPU recommended (RTX 3060+)
- 8 GB VRAM minimum (12–24 GB recommended)
Installation
macOS
1. Download the .dmg file from the Releases page
2. Open the DMG
3. Drag Lunera.app into Applications
4. Launch the app

Note: The macOS build is signed and notarized.
Windows
1. Download the .exe installer or .zip
2. Run the installer or extract the ZIP
3. Launch Lunera
Getting Started
Cloud Mode
1. Enter your Gemini API key
2. Select a base style
3. Enter your prompt
4. Upload reference images (optional)
5. Click Render
Local Mode (ComfyUI)
1. Install and run ComfyUI
2. Ensure it is running at http://127.0.0.1:8188
3. Enable Local Mode in Lunera
4. Load your workflow JSON
5. Click Render Local
Licensing
- One-time purchase
- License key required after trial
- Each license tied to purchase
File Output
Generated images are saved to:
~/Pictures/Lunera/
Use Cases
- AI-generated artwork and illustrations
- Character creation
- Marketing visuals
- Etsy / merch design
- Concept art
Support
Website: https://www.scenemethere.com
Email: support@scenemethere.com
Philosophy
Most AI tools generate images.
Lunera is built to direct them.
