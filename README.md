Add Luna animation and status update functionality for Lily58 keymap

- Implemented luna.h and luna.c for managing character animations based on key events.
- Integrated WPM (words per minute) tracking to adjust animations accordingly.
- Enhanced OLED display to show the current layer and animation state.
- Added rules.mk to configure keymap features
- Updated keymap.c to incorporate Luna's processing and animation logic.
- Fix QK_MACRO_2 reliability with delays

Activate RGB layer on simultaneous FN+NAV hold without update_tri_layer_state, resulting in consistent access without issues.

Add custom keycodes for German umlauts and adjust navigation layer layout
