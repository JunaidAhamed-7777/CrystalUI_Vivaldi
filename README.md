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

# Known Issues

When hovering over Speed Dial navigation, the widget folder may appear unfocused.

Cause:
- Vivaldi internally applies an "inactive" state while hovering/editing navigation components.

Fix:
- Easiest fix is to turn theme blur down to zero (Settings -> Themes -> Select Your Theme -> Editor -> Settings)
- The CSS file already gives a blur to header

The mainbar, panel and header have been tried to make as seamless as possible but the seam will be more prominent depending on what wallpaper is used

Cause:
- Probably how vivaldi samples the wallpaper, I have tried to modify the brightness and tried using background:linear-gradient{to right ...}, but vivaldi samples panel, mainbar and header blur differently so it seems impossible to find a consistent fix for all wallpapers. 

---


# File Structure

```txt
.
├── vivaldi_styling.css
└── README.md
```

---

# Screenshots

<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/208afd4e-785d-4b5c-bd2f-1dda9557c8f3" />
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/bfa6ba22-6bfe-4fef-a771-226871447dba" />

# Credits
Built by Junaid

Special thanks to a very special Moo who gave me an amazing playlist to listen to while debugging this CSS file,
I'd have lost my mind without your help <3
