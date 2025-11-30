# Week 3 – Advanced TypeScript OOP + Generics  
Final TypeScript Mastery Challenge

**MEGA TEAM Frontend Track – Advanced Level 2025**

You’ve reached the final frontier of TypeScript (lessons #26 → #38).  
This is the last TypeScript challenge before we jump into Next.js 15 + real production projects.

### Challenge Goal
Build a **complete, type-safe, object-oriented Task Management System** using **everything** you learned from lesson #26 to #38 — with zero `any`, full strict mode, and professional code structure.

This project combines:
- Interfaces (final touches)
- Classes (full OOP)
- Access modifiers & parameter properties
- Getters/Setters
- Static members
- Abstract classes
- Polymorphism
- Generics (functions, classes, interfaces)

### Project Name
**TaskFlow Pro** – A mini task manager with users, tasks, and teams (console + optional HTML UI)

### Project Structure
```
taskflow-pro/
├── src/
│   ├── interfaces/
│   │   └── index.ts
│   ├── models/
│   │   ├── User.ts
│   │   ├── Task.ts
│   │   └── Team.ts
│   ├── utils/
│   │   └── Logger.ts
│   ├── generics/
│   │   └── Repository.ts
│   └── main.ts                 ← Demo script
├── dist/
├── tsconfig.json
├── package.json
└── README.md
```

### Required tsconfig.json (strict mode ON)
```json
{
  "compilerOptions": {
    "target": "ES2022",
    "module": "commonjs",
    "outDir": "./dist",
    "rootDir": "./src",
    "strict": true,
    "noImplicitAny": true,
    "strictNullChecks": true,
    "esModuleInterop": true
  }
}
```

### You MUST Use Every Concept Below

| Lesson | Concept                            | Required In Project                                  |
|-------|------------------------------------|-------------------------------------------------------|
| #26   | Interface final discussion         | Merge declarations, hybrid types                     |
| #27   | Class type annotations             | Full class with typed properties                     |
| #28   | Access modifiers + param properties| `public`, `private`, `protected`, `readonly`        |
| #29   | Getters & Setters                  | Validate task title/description                      |
| #30   | Static members                     | `Task.nextId`, `User.totalUsers`                     |
| #31   | Class implements Interface        | `User implements Printable`                          |
| #32   | Abstract classes & members         | `abstract class BaseEntity`                          |
| #33   | Polymorphism & method override     | `AdminUser.overrideToString()`                       |
| #34–35| Generics (functions + multiple)    | `createEntity<T>()`, `findById<T>()`                 |
| #36   | Generic classes                    | `Repository<T extends BaseEntity>`                   |
| #37   | Generics + Interfaces              | `interface Store<T>`                                 |
| #38   | Mastering mindset                  | Clean, readable, production-like code                |

### Core Features to Implement

1. **Abstract Base Class**
   ```ts
   abstract class BaseEntity {
     abstract getInfo(): string;
   }
   ```

2. **Task Class** (with getter/setter, static counter, implements interface)

3. **User Hierarchy**
   - `User` (base)
   - `TeamMember extends User`
   - `Admin extends TeamMember` (overrides methods)

4. **Generic Repository**
   ```ts
   class Repository<T extends BaseEntity> {
     private items: T[] = [];
     add(item: T): void;
     findById(id: number): T | undefined;
     getAll(): T[];
   }
   ```

5. **Demo in main.ts**
   - Create tasks and users
   - Use generic repository for both Task and User
   - Show polymorphism (loop through mixed array and call `getInfo()`)
   - Trigger getter/setter validation
   - Use static members

### Expected Output Example
```bash
$ npx ts-node src/main.ts

[TaskFlow Pro] Total tasks created: 5
[TaskFlow Pro] Total users: 8

→ Task #1: "Build Login Page" | Priority: High | Assigned to: Mahmoud
→ Task #2: "Fix TypeScript Errors" | Priority: Critical | Assigned to: Sara

Admin Mahmoud deleted task #1
Repository<Task>: 4 tasks remaining
Repository<User>: 8 users

Polymorphism test:
• User: Ahmed (Team Member)
• User: Ali (Admin) → Can delete tasks
```

### README.md Must Include
1. Live repo link + GitHub Pages (optional HTML demo)
2. Screenshot of **zero TypeScript errors** in terminal
3. Table: “Where did I use lesson #XX?”

```markdown
| Lesson | Concept                  | File / Line                  |
|--------|--------------------------|------------------------------|
| #29    | Getter/Setter            | Task.ts → set title          |
| #36    | Generic Class            | Repository.ts                |
| #33    | Polymorphism             | main.ts → mixed loop         |
```

### Rules
- No `any` allowed anywhere
- `strict: true` must be enabled
- All files must compile cleanly
- Code must be clean, commented, and organized
- Bonus: Add a simple HTML UI that uses the same classes (transpiled)

### Deadline
**Friday – 12:00 AM (midnight) Cairo time**

### Rewards for Perfect Submissions
- Personal 1-on-1 code review (video call)
- Official **“TypeScript Advanced Master”** certificate
- Your name in MEGA TEAM Hall of Fame (forever)
- Priority in Next.js 15 project teams

When you finish this challenge cleanly —  
You are no longer learning TypeScript.  
You are **ready to write production-grade, enterprise-level code** in any company in the world.

This is the final boss of TypeScript in MEGA TEAM.  
Beat it.

**Mahmoud Ramadan**  
Lead Frontend Mentor – MEGA TEAM  
Student of Elzero Web School

#MEGA_TEAM #TypeScriptMaster #AdvancedLevel