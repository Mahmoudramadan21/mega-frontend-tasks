# TypeScript Mastery Challenge – Part 2  
Lessons #16 – #25 | Learn TypeScript In Arabic 2022

![TypeScript](https://img.shields.io/badge/TypeScript-5.5+-blue.svg?style=flat-square&logo=typescript)
![Level](https://img.shields.io/badge/Level-AdvancedLevel-success?style=flat-square)
![Status](https://img.shields.io/badge/Status-Ready-green)

## Challenge Overview
Build a **Console-Based User & Role Management System** using **pure TypeScript** (no HTML/CSS/JS in the browser — everything runs in Node.js).

This project proves you fully understand **lessons #16 to #25**:
- `void` & `never`
- `enum` (numeric + string)
- Type Assertions
- Union & Intersection Types
- Objects + Interfaces
- Interface Methods, Reopening, and Extending

Keep it **simple, clean, and 100% type-safe**.

## Project Structure
```
ts-challenge-part2/
├── src/
│   ├── enums.ts          # Lessons #17–#18
│   ├── assertions.ts     # Lesson #19
│   ├── unions.ts         # Lesson #20
│   ├── objects.ts        # Lesson #21
│   ├── interfaces.ts     # Lessons #22–#25
│   └── main.ts           # Mini Project: User Manager
├── dist/                 # Auto-generated
├── tsconfig.json
├── package.json
└── README.md
```

## Required tsconfig.json
```json
{
  "compilerOptions": {
    "target": "ES2022",
    "module": "commonjs",
    "outDir": "./dist",
    "rootDir": "./src",
    "strict": true,
    "esModuleInterop": true
  }
}
```

## Tasks (All Required)

### 1. enums.ts – Lessons #17 & #18
```ts
// TODO: Create Role enum (Admin = 1, Moderator, User)
// TODO: Create Direction enum with string values ("up" | "down" | "left" | "right")
// TODO: Create const enum Status with values Pending, Approved, Rejected
```

### 2. assertions.ts – Lesson #19
```ts
// TODO: Use type assertion to tell TS that document.getElementById returns HTMLInputElement
// TODO: Use "as" and angle-bracket syntax (both ways)
// TODO: Show a case where assertion is required
```

### 3. unions.ts – Lesson #20
```ts
// TODO: Create type ID = string | number
// TODO: Create type Status = "loading" | "success" | "error"
// TODO: Create intersection type AdminUser = User & { permissions: string[] }
```

### 4. objects.ts – Lesson #21
```ts
// TODO: Create object with full type annotation (no interface yet)
// TODO: Optional properties, readonly, index signatures
```

### 5. interfaces.ts – Lessons #22–#25
```ts
// TODO: Declare interface User { id: number; name: string; email: string }
// TODO: Add method login(): void
// TODO: Reopen the interface (add isActive?: boolean)
// TODO: Create interface Moderator extends User { banUser(userId: number): boolean }
// TODO: Create interface Admin extends Moderator { deleteUser(userId: number): never }
```

### 6. main.ts – Mini Project: User Manager
```ts
// You must use everything you created above

// Requirements:
// 1. Define a User type using interface + extension
// 2. Use Role enum for user roles
// 3. Create function that never returns (e.g., throw error)
// 4. Create function with void return (e.g., logUser)
// 5. Use type assertion when getting data from "API"
// 6. Use union types for flexible parameters
// 7. Create at least 3 users with different roles
// 8. Show admin deleting a user → call function that returns never

// Final output should look like:
// User: Ahmed (Admin) logged in
// Moderator: Sara banned user 3
// Admin: Ali deleted user 5 → Error: Cannot delete root user!
```

## Expected Output (Example)
```bash
$ npx ts-node src/main.ts

User: Ahmed (Role: Admin) → logged in
Moderator: Sara banned user 3 → true
Admin: Ali tried to delete user 1 → Error: Cannot delete root user!
```

## Submission Checklist

- [ ] All files compile with **zero errors** (`tsc --noEmit`)
- [ ] `strict: true` is enabled
- [ ] Every lesson #16–#25 is used and commented
- [ ] Clean console output
- [ ] Screenshot of **no compile errors**
- [ ] Live repo + link

## How to Run
```bash
npm install -g typescript ts-node
tsc --watch
# or
npx ts-node src/main.ts
```

## Author
MEGA TEAM Member  
Mahmoud Ramadan
Following "Learn TypeScript In Arabic 2022" by Elzero Web School

## Final Words
This challenge is **deliberately simple** so you can focus on **understanding the types**, not fighting complex logic.

When you finish this cleanly →  
You are officially **TypeScript Mid-Level Ready** and can move to classes, generics, and modules with full confidence.

Good luck, future TypeScript master!

#MEGA_TEAM #TypeScript