# Critical Insight Strategies Website

Rebuilt using the Grand Line Analytics framework with CIS content, branding, and color scheme.

## Site Structure

```
cis-website/
├── index.html          # Homepage with landing splash + hero
├── mission.html        # Mission, ethics & patient advocacy
├── founder.html        # Dr. Mary Herc - Clinical Leadership
├── services.html       # Specialties & Capabilities
├── facilities.html     # For Healthcare Facilities
├── pas.html            # For Physician Assistants
├── contact.html        # Contact & Deployment Requests form
├── favicon-32x32.png   # Favicon
└── assets/
    ├── cis-logo-transparent.png    # Main logo
    └── dr-mary-herc.png            # Founder photo
```

## Features

- **Landing Splash**: Animated entry screen with heartbeat/pulse effect (medical theme)
- **Dark/Light Theme Toggle**: Persists across pages via localStorage
- **Responsive Navigation**: Mobile hamburger menu
- **Consistent Design System**: CSS variables for colors, consistent components
- **Multi-page Structure**: Following GLA's page organization pattern

## Color Scheme

### Light Mode (Default)
- Background: `#0a1a2e` (deep navy blue)
- Accent: `#3B82F6` (bright blue)
- Text: `#C9D4E0` (light gray-blue)

### Dark Mode
- Background: `#030712` (near black)
- Accent: `#60A5FA` (lighter blue)
- Text: `#E5E7EB` (light gray)

## Required Assets

You need to add these images to the `assets/` folder:
1. `cis-logo-transparent.png` - Your main CIS logo
2. `dr-mary-herc.png` - Dr. Mary Herc's photo

## Deployment

1. Upload all files to your web server
2. Ensure the `assets/` folder contains your logo and photo
3. Update any form endpoints in `contact.html` if needed
4. Update Google Analytics ID if applicable

## Based On

Grand Line Analytics website framework - multi-page static site with:
- Session-based landing splash
- Theme toggle with localStorage persistence  
- Responsive design with mobile navigation
- Consistent header/footer across all pages
