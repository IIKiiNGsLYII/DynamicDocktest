// ==WindhawkMod==
// @id              dynamicdock
// @name            DynamicDock
// @description     For Ultrawide Monitors: Force the taskbar to follow your mouse when it touches the edge and your icons will be centered on your mouse. Works with default and modded taskbars.
// @version         1.0
// @author          IIKiiNGsLYII
// @include         explorer.exe
// @architecture    x86-64
// @compilerOptions -lole32 -loleaut32 -lruntimeobject -luuid
// ==/WindhawkMod==

// ==WindhawkModReadme==
/*
# DynamicDock

Best for use with ultrawide monitors, but works on any monitor. Instead of the taskbar popping up in the middle of the screen, 
the taskbar appears or slides the icons to your mouse **right where your mouse touches the screens edge**.

This is still the real Windows taskbar, so everything works like normal: jump lists (right-click), hover thumbnails, badges, drag and drop, the tray and the clock.

## Bottom taskbars (works with auto-hide or always visible)
1. If you want to use with auto hide.
    1a. Confirm or turn on **Automatically hide the taskbar** in Windows Settings > Personalization > Taskbar > Taskbar behaviors > Select "Automatically hide the taskbar" from the menu.
    1b. Otherwise, this mod works with the default bottom taskbar that is always visible. Be sure to toggle the bottom taskbar setting that keeps the full width of the bar active in the "Bottom Taskbar" setting.
2. Keep **Taskbar alignment** on **Center**.
3. Move the mouse to the bottom edge of the screen anywhere: the bar opens under it or simply slides the icons to your mouse with the default taskbar.
- **Keep in mind** that taskbars change widths based on the amount of icons in the bar. Some additional adjustments may be required as the total taskbar pixel count changes to maintain functionality and spacing as you desire.

## Top taskbar
1. In Windows Settings > Personalization > Taskbar > Taskbar behaviors, set **Taskbar position** to **Top**.
2. In DynamicDock's settings, toggle **Top taskbar ON** and turn on to turn on **Taskbar is at the top of the screen**.
3. Touch the top edge of the screen anywhere: the app icons slide under the mouse.
- The taskbar itself stays full width across the top (Windows can't auto-hide it there), and the tray and clock
  stay at the right edge. Only the row of app icons moves, so nothing collapses or leaves empty space.
- The center zone, limits, edge distance and smooth movement work the same. The icons never slide under the tray.
- The **Tray and clock** and **Rounded corners** settings are for the compact bottom bar only and are ignored for the top taskbar option.

## Full-width bottom taskbar
Prefer the taskbar to stay full width at the bottom too? Turn on **Keep the bottom taskbar full width** (in the
**Bottom taskbar** section). The taskbar then works like the top one: it pops up full width with Widgets in the
left corner and the tray and clock at the right edge, and only the app icons slide to the mouse.

## Compatibility
- Works with the **default Windows 11 taskbar** and with the **Windows 11 Taskbar
  Styler** mod (DynamicDock moves the bar; the styler keeps deciding how it looks).
- Settings marked **(default taskbar only)** change the look of the plain Windows
  taskbar. When Taskbar Styler or a similar mod restyles the taskbar, those
  settings are skipped so they don't fight that mod's look.
- Other taskbar mods (icon size, clock customization, auto-hide instant show,
  thumbnail reorder) can be used alongside it. *Taskbar auto-hide instant show*
  is recommended: it removes Windows' delay before the taskbar pops up.
- Windows 11 only.  

## Troubleshooting (Try this if things are not working correctly)
- **The bar doesn't move, or the taskbar looks stuck in a moved position:** turn
  DynamicDock off and on again in Windhawk. If that doesn't fix it, restart
  Explorer: open Task Manager, search for **Windows Explorer**, right-click **Windows Explorer** and choose
  **Restart**. This rebuilds the taskbar from scratch (it also closes open File
  Explorer windows). You may need to tap your windows key on the keyboard for the taskbar to reappear. Then return to windhawk and toggle your mods on/off as needed to function properly.
- After installing or updating the mod, the first touch of the screen edge can
  take a moment while DynamicDock finds the taskbar.
- To report a problem, turn on **Debug logging** on the mod's Advanced tab,
  reproduce it, and share the lines from the mod's log. You should see logs being created as you tap the screen edge in different places.
*/
