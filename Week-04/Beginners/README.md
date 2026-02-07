# Week 04 – Enhanced Dream Portfolio (CSS Mastery Part 2)
**MEGA TEAM Frontend Track – 2026**

**Goal**  
Take your Week 03 portfolio and transform it into a **visually stunning, professional-looking website** using **only pure CSS** (Lessons 17–38 from Elzero CSS course).  
No Flexbox, no Grid, no frameworks — just pure classic CSS mastery.

### Project Name
`enhanced-dream-portfolio`

### Required CSS Concepts (Must use every single one at least once)
| #   | Concept / Property                   | Suggested Usage Example                                   |
|-----|--------------------------------------|------------------------------------------------------------|
| 17–21 | Text properties (color, shadow, align, decoration, transform, spacing, indent, overflow, wrap) | Hero title with text-shadow + uppercase, paragraph with letter-spacing & word-break |
| 22  | Inheritance                          | Set font-family on body/html and override only when needed |
| 23–25 | @font-face OR Google Fonts + font-size (rem/em/vw), weight, style | Use Google Fonts (e.g., Poppins + Roboto Mono)            |
| 26  | cursor                               | cursor: pointer on links, cursor: help on info icons      |
| 27  | float + clear                        | Float profile image left in About section + clear after   |
| 28  | calc()                               | width: calc(100% - 100px), font-size: calc(1.5rem + 1vw)  |
| 29  | opacity                              | Overlay on hero image or semi-transparent cards           |
| 30–31 | position (relative, absolute, fixed) + top/left/right/bottom + z-index | Fixed navbar (z-index: 100), absolute "Back to top" button |
| 32  | List styling                         | Remove bullets, custom bullet with ::before, horizontal nav |
| 33  | Table styling                        | Experience/Education table with styled thead, zebra rows  |
| 34  | Pseudo-classes (:hover, :focus, :active, :first-child, :nth-child, etc.) | Hover effects, zebra table rows with :nth-child(odd)      |
| 35–37 | Pseudo-elements (::before, ::after, ::first-letter, ::first-line, ::selection) | Icons before links, decorative lines, drop-cap in About, custom selection color |
| 38  | Vendor prefixes (optional but recommended) | -webkit- for text-stroke or backdrop-filter if used       |

### Minimum Design Requirements
- Fixed navigation bar at the top (scrolls with user)
- Hero section with big title (text-shadow + transform on hover)
- Circular profile picture with border + subtle shadow
- About section: floated image + text with proper clearing
- Skills section: custom list (no bullets) with ::before icons
- Experience/Education as beautifully styled table
- Hover/active/focus states on all interactive elements
- Smooth color selection highlight (::selection)
- Responsive feel using max-width + calc() + viewport units

### Project Structure
```
enhanced-dream-portfolio/
├── index.html
├── style.css
├── assets/
│   └── images/
└── README.md
```

### README.md Must Include
1. Live demo link (GitHub Pages / Netlify)
2. Before & After screenshots (Week 03 vs Week 04)
3. Table showing exactly where you used each required concept (use the table above and fill it)
4. Short note about your favorite pseudo-element usage

### Bonus (Get Legendary Status)
- Drop-cap first letter in About section (::first-letter)
- Custom checkbox/radio using ::before/::after
- Smooth hover transition on cards/links
- Creative use of text-shadow with multiple shadows

### Deadline
**Next Saturday – 11:59 PM Cairo Time**

This is your chance to make something you're genuinely **proud to show in interviews**.  
Make it beautiful. Make it clean. Make it YOU.

Good luck, future frontend legends!  
**Mahmoud Ramadan**  
Frontend Mentor – MEGA TEAM
