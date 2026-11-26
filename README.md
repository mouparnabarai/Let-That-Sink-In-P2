# Interactive 3-Panel A3 Comic Book

An interactive, responsive single-page comic book application crafted to exact **A3 dimensions** (297 mm × 420 mm, $1 : \sqrt{2} \approx 1.414$ aspect ratio) featuring:

1. **Vertical 3-Panel Comic Layout**:
   - **Panel 1 (Top)**: Close-up of roti/phulka cooking and puffing on the cast-iron tawa with rising steam.
   - **Panel 2 (Middle)**: Wide kitchen scene of cooking by the stove against cyan cabinetry.
   - **Panel 3 (Bottom)**: Domestic dining table scene with the family waiting, eating, and anticipating the fresh meal.

2. **Click-to-Play Animation Engine**:
   - Panels start in a frozen/paused state with a stylish vintage comic **"▶ CLICK TO PLAY GIF"** badge.
   - Clicking a panel starts its animation and reveals dynamic comic sound effects (`TSSSSSS!`, `FLIP!`, `SNIFFF...`) and motion effects (rising steam, cooking sparks, flicker, and aroma trails).
   - Clicking again freezes/pauses the panel.
   - **Swap with Custom GIFs**: Supports dropping in your original animated `.gif` files via the **"📁 Replace with GIFs"** toolbar drawer or dragging `.gif` files directly into each panel.

3. **Realistic Corner-Drag Page Turn Effect**:
   - Grab the **bottom-right** or **top-right** corner and drag leftward to peel and turn the page with authentic paper curl physics, crease highlights, underside shading, and soft cast shadows.
   - If released past ~35% of the page width, it smoothly completes the page turn with a synthesized paper rustle sound effect (Web Audio API) revealing **Page 2: Behind-the-Scenes Storyboard & Sketchbook**.
   - If released earlier, it springs back smoothly.
   - From Page 2, drag the **bottom-left** corner or click **"Flip Back"** to turn back to Page 1.
   - Quick one-click turn supported via the **"📖 Turn Page"** button in the top bar.

4. **Keyboard Shortcuts**:
   - <kbd>Space</kbd>: Play / Pause all panels
   - <kbd>→</kbd>: Turn to Page 2
   - <kbd>←</kbd>: Turn back to Page 1

---

## Running the Application
The app is currently running live at:
**[http://localhost:8088](http://localhost:8088)**

To restart the server at any time:
```bash
ruby -run -e httpd . -p 8088
```
Or open [index.html](file:///Users/mouparnabarai/Documents/Antigravity%20P2/index.html) directly in any web browser.
