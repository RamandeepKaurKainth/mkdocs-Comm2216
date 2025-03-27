
## Overview
Components in **Figma** are reusable design elements (like buttons or icons) that save time and keep your project consistent. This section will walk you through creating a component, editing it, and using it across your design. By the end, you’ll have a reusable button component ready to streamline your workflow.

## What You'll Need

* A **Figma** file open (from the previous section or a new one).
* Basic familiarity with **Rectangle Tool (R)** and **Text Tool (T)**

## Steps to Create and Use Components

* **Open** Figma in your browser or desktop app and log into your account.
* **Create** a new frame by selecting the **Frame Tool (F)** from the toolbar, then clicking and dragging on the canvas. Set the size to a preset like *iPhone 13* (in the right-hand properties panel) or use custom dimensions (e.g., 375x812px).
![image](assests/FrameToolbar.png "Frame Toolbar")
* **Draw** a button shape using the **Rectangle Tool (R)**. Click on the canvas and drag to create a rectangle (e.g., 200x50px). In the properties panel, set the Fill color to a hex value like `#007BFF` (a nice blue).
* **Add** text to your button with the **Text Tool (T)**. Click inside the rectangle, type “Click Me,” and adjust the font size to 16px and weight to bold in the properties panel.
* **Select** both the rectangle and text by holding `Shift` and clicking each element, or dragging a selection box around them.
* **Convert** these elements into a component by pressing `Cmd + Alt + K` (Mac) or `Ctrl + Alt + K` (Windows), or clicking **Create Component** in the top bar. The selection will turn blue, indicating it’s now a component.
* **Name** your component in the Layers panel (on the left). Right-click the component (labeled something like Component_1), select Rename, and type “Primary Button.”
* **Edit** the master component to refine it. Double-click the component, then adjust the corner radius to 8px (in the properties panel) or change the text to “Submit.” These changes will apply everywhere the component is used.
* **Use** an instance of the component by dragging it from the Assets panel (left sidebar) onto your canvas. Place it below the original to test it out.
* **Update** the master component again—select it, change the Fill color to `#0056B3` (a darker blue), and watch the instance update automatically.

!!! info "Info"
    *Shortcut Tip: Press `Alt` (Windows) or `Option` (Mac) while dragging an instance to duplicate it quickly.*

!!! warning "Warning"
    *Don’t edit an instance’s core structure (e.g., deleting the rectangle) unless you detach it first by right-clicking and selecting Detach Instance. This avoids breaking the link to the master component.*

## Adding Graphics
* ![New frame created for your design (highlighted in yellow).](images/screenshot1.png)
* ![Button converted into a component (highlighted in yellow with blue outline).](images/screenshot2.png)
* ![Master component updated to a darker blue (highlighted in yellow), with the instance matching automatically.](images/screenshot3.png)

## Conclusion

Success! You’ve created a reusable **Primary Button** component and learned how to update it across your design. Components are powerful for keeping your project consistent—think of them as your design’s building blocks. Next, try creating variants (e.g., hover or disabled states) or move to the prototyping section!

!!! success "Success"
    Your button component is ready! It’s now in your Assets panel for reuse. Celebrate by dragging a few more instances onto your canvas.
