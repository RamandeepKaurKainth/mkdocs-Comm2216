# Troubleshooting Guide

## 1. Frame Tool Doesn’t Show Presets Like iPhone 13
- **Symptoms**: When selecting the Frame Tool (F), no device options (e.g., iPhone 13) appear in the properties panel.
- **Solution**: Ensure you’ve selected the Frame Tool (F) from the Toolbar, not the Artboard Tool. In the right sidebar, under "W" and "H" fields, click the dropdown to see presets like iPhone 13.

## 2. Component Doesn’t Appear in Assets Panel
- **Symptoms**: After creating a component (e.g., Primary Button), it’s not visible in the Assets Panel for reuse.
- **Solution**: Check the Layers Panel (left sidebar) to confirm it’s a component (blue diamond icon). Switch to the Assets tab (next to Layers) or restart Figma if it’s still missing.

## 3. Auto Layout Won’t Adjust Button and Text Together
- **Symptoms**: Applying Auto Layout (Shift + A) to a button and text doesn’t align or space them as expected.
- **Solution**: Select both the rectangle and text, group them (`Ctrl + G` or `Cmd + G`), then apply Auto Layout to the frame containing them. Adjust padding in the right sidebar.

## 4. Prototype Link Doesn’t Trigger on Click
- **Symptoms**: In Prototype mode, clicking the button doesn’t move to the linked frame.
- **Solution**: Switch to the Prototype tab, select the button, and drag the Prototype Node (circle) to the destination frame. Set the interaction to "On Click" and test with the Present button.

## 5. Changes to Component Don’t Update Instances
- **Symptoms**: Editing the master component (e.g., changing the color to `#0056B3`) doesn’t affect instances on the canvas.
- **Solution**: Ensure you’re editing the master component (blue outline in Layers Panel), not an instance. If the instance was detached, recreate it by dragging from the Assets Panel.

## 6. Shapes Disappear When Moving Them
- **Symptoms**: Dragging a rectangle or circle moves it off-screen or makes it vanish.
- **Solution**: Check the Layers Panel to see if it’s still listed—it might be behind another frame. Use the Move Tool (V) and arrow keys to nudge it back into view.

## 7. Text Size or Font Won’t Change
- **Symptoms**: Adjusting font size (e.g., to 16px) or weight (e.g., bold) in the properties panel has no effect.
- **Solution**: Double-click the text layer with the Text Tool (T) to enter edit mode, then apply changes in the right sidebar. Ensure no overrides from an instance are blocking edits.

## 8. Smart Animate Looks Choppy or Doesn’t Work
- **Symptoms**: Prototype transitions with Smart Animate are jerky or don’t animate as expected.
- **Solution**: Ensure elements (e.g., button shapes) have the same layer name in both frames. Simplify the design by reducing overlapping effects like shadows or gradients.

## 9. Overlay Won’t Center in Prototype
- **Symptoms**: An overlay (e.g., a modal) appears off-screen or misaligned when previewed.
- **Solution**: In the Prototype tab, select the overlay frame, choose "Overlay" in the interaction settings, and set its position to "Center" or adjust manually with X/Y coordinates.

## 10. Can’t Share Prototype Link
- **Symptoms**: Clicking the Share button doesn’t generate a clickable link or QR code.
- **Solution**: Check your file’s permissions (top-right Share button > "Anyone with the link can view"). Save the file first if it’s new, then try sharing again.