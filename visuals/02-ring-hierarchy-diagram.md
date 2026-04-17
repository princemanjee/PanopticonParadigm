# System Privilege Hierarchy - Ring Architecture Diagram

## Description
A technical diagram illustrating the x86 CPU privilege ring hierarchy from Ring 3 (User Space) down to Ring -3 (Intel Management Engine). The diagram shows how each descending ring grants deeper hardware access and less user visibility, culminating in Ring -3 where the Intel ME operates as an autonomous subsystem with full memory and network access, entirely outside the user's control or awareness. This visual supports Section 2.1 of the paper on hardware-level subversion.

## Placement
Section 2: Hardware-Level Subversion - alongside the discussion of Intel ME and AMD PSP as architectural backdoors.

## Gemini Image Generation Prompt
Render in a glassmorphism aesthetic throughout: use frosted glass panels with backdrop blur effects, semi-transparent layers with visible depth, subtle light borders that catch highlights, soft diffused shadows behind panels, and a layered floating composition with elements at different depth planes. Use translucent fills rather than solid colors for all major surfaces.

A clean, precise technical diagram showing the x86 CPU privilege ring hierarchy as concentric circles viewed from above, with each ring rendered as a frosted glass layer with translucent fills and subtle luminous borders. Seven concentric rings, from outermost to innermost:

Ring 3 (outermost) - labeled "Ring 3: User Applications" - colored bright green (#4CAF50), representing the layer where users operate. Label includes "Browsers, Email, Apps."

Ring 2 - labeled "Ring 2: Device Drivers" - colored yellow-green (#8BC34A). Label includes "Hardware interface layer."

Ring 1 - labeled "Ring 1: Device Drivers (privileged)" - colored yellow (#FFC107). Label includes "Direct hardware access."

Ring 0 - labeled "Ring 0: OS Kernel" - colored orange (#FF9800). Label includes "Full system control, memory management."

Ring -1 - labeled "Ring -1: Hypervisor / VMM" - colored deep orange (#FF5722). Label includes "Controls all VMs and OS instances."

Ring -2 - labeled "Ring -2: SMM (System Management Mode)" - colored red-orange (#E64A19). Label includes "Invisible to OS, firmware-level."

Ring -3 (innermost) - labeled "Ring -3: Intel ME / AMD PSP" - colored deep red (#B71C1C) with a faint pulsing glow effect. Label includes "Autonomous subsystem. Full memory/network access. Runs independent OS (MINIX). Operates even when system is powered off."

On the right side, include a vertical arrow pointing downward labeled "Increasing Access / Decreasing Visibility" with gradient from green to red. Add a small legend box in the corner: "Green = User Control, Red = State/Vendor Access, User Invisible."

Style: Glassmorphism technical diagram suitable for an academic paper. Dark background (#1a1a2e). White text labels. Each ring rendered as a frosted glass panel with translucent fills, backdrop blur, and subtle luminous borders. Soft diffused shadows between layers create visible depth. Floating composition with rings at different depth planes. Professional and precise.

## Specifications
- Dimensions: 1200 x 1200 pixels (square)
- Style: Glassmorphism - technical diagram with frosted glass layers, translucent fills, backdrop blur, and floating depth composition
- Color Palette: Green (#4CAF50) through yellow (#FFC107) through orange (#FF9800) to deep red (#B71C1C) gradient. Dark background (#1a1a2e), white text (#FFFFFF)
- Format: PNG
- Notes: The rings must be clearly labeled and legible. The gradient from green (user control) to red (state access) is the key visual metaphor. Ring -3 should visually stand out as the most critical and most hidden layer. Consider adding a small lock icon or eye icon at Ring -3 to emphasize surveillance capability.
- Glassmorphism Rendering: Each ring should use frosted glass with backdrop blur, allowing inner rings to show through with a blurred effect. Borders should be subtle and luminous. Color fills should be translucent rather than opaque. Soft diffused shadows behind each ring create depth separation.
