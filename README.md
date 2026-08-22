# dinput8_wrapper_ignore_triggers
This is a simple DirectInput8 wrapper which ignores the analog triggers of controllers like the DualShock 4 (PS4) and/or DualSense (PS5).

Triggers can still be used as buttons, but they will only be digital not analog.

This is an issue for some games like the Ys Series where analog triggers are mixed up with the analog stick.

Tested with Steam/GOG version games of the following:
- Prince of Persia: The Sands of Time
- Ys Origin
- Ys I & II Complete+
- Ys: The Oath in Felghana
- Ys VI: The Ark of Napishtim.

Steam Input must be disabled for testing.

# Install
Simply copy the dinput8.dll to the same folder where the game executable is.

# Logging
Use the Environmental Variable `DINPUT8_LOG_ENABLE=true`. It will generate a `dinput8-wrapper.log` file after closing the game.

# Preview
<img width="1500" height="650" alt="Ys Analog Drift Before and After" src="https://github.com/user-attachments/assets/cff012aa-2fd6-47af-8884-cea8b912e468" />
