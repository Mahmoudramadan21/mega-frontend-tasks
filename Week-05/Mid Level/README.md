# Week 05 – Live Greeting Card Maker (Simple DOM Project)
**MEGA TEAM Frontend Track – Mid Level 2026**

### Goal
Build a small interactive page that creates a greeting card from user input.  
Use **only** JavaScript concepts from Lessons #79 to #97.

### Project Name
`greeting-card-maker`

### What You Need to Build
**Form fields:**
- Input → Name
- Textarea → Message
- Input type="color" → Card background color
- Button → Create Card

**After clicking Create:**
- Show one card below the form containing:
  - Heading: "Hello, [Name]!"
  - Paragraph: the message
  - Background color = selected color

**Extra button:** Clear Card (hide or remove the card)

### Required JavaScript Concepts – Use each at least once

| Lesson(s) | Concept                               | Simple Place to Use It                              |
|-----------|---------------------------------------|-----------------------------------------------------|
| #079–082  | Objects (create, dot/bracket, nested) | Card data object: `{ name, message, color }`        |
| #083      | this keyword                          | Optional – inside object method if needed           |
| #084–085  | Object.create / Object.assign         | Create default card template                        |
| #086–088  | DOM select / content / attributes     | `getElementById`, `textContent`, `.value`           |
| #089      | createElement + append / prepend      | Build card `<div>`, `<h2>`, `<p>` dynamically       |
| #091      | Deal with children                    | Optional – loop over form children                  |
| #092      | DOM Events                            | `addEventListener('click')` on button               |
| #093      | preventDefault + basic validation     | Stop form submit + check if name is empty           |
| #094      | Event simulation                      | `nameInput.focus()` when page loads                 |
| #095      | classList                             | `card.classList.add('hidden')` / `.remove()`        |
| #096      | CSS styling via JS                    | `card.style.backgroundColor = colorValue`           |
| #097      | before / after / prepend / remove     | Add error message before form or remove card        |

### Minimum Requirements Checklist
- [ ] Create card only when button is clicked
- [ ] Show error message (append to page) if name is empty
- [ ] Use `classList` to show / hide the card
- [ ] Change card background using `.style`
- [ ] Store form data in a JavaScript object
- [ ] Clear / hide card when pressing "Clear" button

### Folder Structure
```
greeting-card-maker/
├── index.html
├── style.css          (basic card style + .hidden { display: none; })
├── js/
│   └── main.js
└── README.md
```

### What to Submit
- Live demo link
- Screenshot (form + one example generated card)
- This table filled with where you used each concept
- One short sentence:  
  "The DOM method I liked most this week was ________________."

**Deadline:** Saturday – 11:59 PM Cairo Time

Small project – big learning.  
Focus on clean code and comments.  
You got this! 💪

**Mahmoud Ramadan**  
Frontend Mentor – MEGA TEAM
