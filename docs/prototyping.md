## Overview
Prototyping in **Figma** turns your static designs into interactive experiences. In this guide, you’ll create a button interaction—linking a button to another frame with a smooth transition—to test and share a clickable prototype. By the end, you’ll have a working prototype showcasing a button’s behavior.

## Steps to Prototype a Button Interaction

1. **Open** Figma in your browser or desktop app and log into your account with a file containing at least two frames (e.g., a home screen and a next screen).
2. **Switch** to prototyping mode by clicking the **Prototype** tab in the top-right corner, next to the Design tab.
3. **Select** your button (e.g., the **Primary Button** from earlier) on the first frame. A small circular **Prototype Node** will appear on its right edge.
4. **Link** the button to the second frame by dragging the **Prototype Node** (right edge) to the destination frame. A blue connector line will appear.  
   ![image](assets/PrototypeNode.png "Prototype Node") <!-- Placeholder; add actual image -->
5. **Set** the trigger in the properties panel (right side). Choose **On Click** from the dropdown to make the button clickable.
6. **Choose** an action in the properties panel. Select **Navigate To** and ensure the second frame is the destination (it should auto-populate).
7. **Add** animation by picking **Smart Animate** in the properties panel. Set duration to 300ms and easing to **Ease In** for a smooth transition.  
>!!! success "Success"  
       Your button interaction is live! Click it in preview to see the magic.
8. **Preview** the prototype by clicking the play button (▶) labeled **Present** in the top-right corner. Test the button’s click to confirm it works.
9. **Adjust** the flow if needed. Back in the **Prototype** tab, tweak the animation (e.g., change to **Instant**) or offset the destination frame’s position (e.g., 50px down) in the properties panel.  
>!!! warning "Warning"  
       *Avoid editing the button instance’s structure (e.g., deleting its shape) without detaching it first. Right-click and select Detach Instance to prevent breaking the master component.*
10. **Share** your prototype by clicking **Share** (top-right), copying the link, or scanning the QR code in preview mode for mobile testing.  
>!!! info "Info"  
     *Shortcut Tip: Hold `Alt` (Windows) or `Option` (Mac) while dragging to duplicate frames quickly.*  
 >!!! warning "Animation Performance Warning"  
    *Heavy animations like Smart Animate can lag in complex prototypes. Test on multiple devices and keep it simple.*

## Conclusion
You’ve crafted a clickable button prototype in Figma, bringing your design to life with smooth interactions! This skill helps you test ideas and share them effectively. Check out the Glossary for key terms or Troubleshooting if you hit any snags!