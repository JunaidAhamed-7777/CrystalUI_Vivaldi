# Crystal UI for Vivaldi

```txt
								With Love  ⣠⣶⣶⣶⣦⠀⠀
								⠀⠀⣠⣤⣤⣄⣀⣾⣿⠟⠛⠻⢿⣷⠀
								⢰⣿⡿⠛⠙⠻⣿⣿⠁⠀⠀⠀⣶⢿⡇
								⢿⣿⣇⠀⠀⠀⠈⠏⠀⠀⠀ By Junaid
								⠀⠻⣿⣷⣦⣤⣀⠀⠀⠀⠀⣾⡿⠃⠀
								⠀⠀⠀⠀⠉⠉⠻⣿⣄⣴⣿⠟⠀⠀⠀
								⠀⠀⠀⠀⠀⠀⠀⣿⡿⠟⠁⠀⠀⠀⠀
```

A custom CSS theme for Vivaldi focused on a transparent-glassy interface inspired from iOS.

This theme adds:
- Frosted glass effects across the UI
- Transparent side panels
- Glassy active tabs
- Cleaner Speed Dial navigation
- Reduced borders and separators
- A more seamless desktop aesthetic

---

# Features

## Address Bar Glass Effect
- Transparent main bar
- Blur applied using `backdrop-filter`
- Removes default borders and shadows

## Speed Dial Cleanup
- Transparent Speed Dial navigation
- Custom active indicator styling
- Removes unnecessary separator lines

## Sidebar / Panel Styling
- Fully transparent panel container
- Frosted blur effect on side panels
- Cleaner icon bar appearance

## Tab Styling
- Active tabs receive:
  - Black translucent tint
  - Blur effect
  - Subtle top highlight

## UI Simplification
Removes:
- Default borders
- Separator lines
- Shadow clutter
- Address bar bottom line

---

# Known Issue

When hovering over Speed Dial navigation, the widget folder may appear unfocused.

Cause:
- Vivaldi internally applies an "inactive" state while hovering/editing navigation components.

The mainbar and header are seamless at the top left corner but the seam is more visible as we go from left -> right
Cause:
- Probably how vivaldi samples the wallpaper, I have tried to modify the brightness and tried using background:linear-gradient{to right, but it is showing no signs of getting fixed

---


# File Structure

```txt
.
├── vivaldi_styling.css
└── README.md
```

---

# Screenshots

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/bba2e8c6-19e4-4a0d-b69b-96b1c8802ca5" />
<img width="1919" height="1025" alt="image" src="https://github.com/user-attachments/assets/1e744d47-1166-485b-afb1-8d92f55bc3c2" />


# Credits
Built by Junaid

Special thanks to a very special Moo who gave me an amazing playlist to listen to while debugging this CSS file,
I'd have lost my mind without your help <3

---

# License

MIT License
