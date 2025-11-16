```markdown
# TypeScript Mastery Challenge - MEGA TEAM

## Description
This challenge tests your **full understanding** of **"Learn TypeScript in Arabic 2022"** lessons **#01 to #15**.

You will build a **console-based "Task Manager"** using:
- VS Code + Terminal
- `tsc --watch`
- Strict type checking
- All concepts from the 15 lessons

---

## Concepts Covered
- **Setup & Intro (#01–#04)**
  - Install TypeScript, `tsc`, `tsconfig.json`, watch mode
  - Static vs Dynamic typing (why TS catches bugs early)

- **Types & Variables (#05, #14)**
  - Type annotations, `any`, literal types

- **Arrays (#06–#07)**
  - Typed arrays, multidimensional arrays

- **Functions (#08–#11)**
  - Annotations, optional/default/rest params, arrow/anon functions

- **Type Aliases (#12–#13)**
  - Simple + advanced (unions, objects)

- **Tuples (#15)**
  - Fixed-length typed arrays

---

## Project Structure
```
/TypeScript-Mastery-Challenge
│
├─ src/
│   ├─ variables.ts       # TODOs for #05, #14
│   ├─ arrays.ts          # TODOs for #06–#07
│   ├─ functions.ts       # TODOs for #08–#11
│   ├─ typeAliases.ts     # TODOs for #12–#13
│   ├─ tuples.ts          # TODOs for #15
│   └─ main.ts            # Mini project (Task Manager)
│
├─ dist/                  # Auto-generated
├─ tsconfig.json
└─ README.md              # Your answers + screenshots
```

---

## Task Instructions

### 1. **Setup (#01–#04)**
```bash
npm install -g typescript
tsc --init
```
Edit `tsconfig.json`:
```json
{
  "compilerOptions": {
    "strict": true,
    "outDir": "./dist",
    "rootDir": "./src",
    "target": "ES2020",
    "module": "commonjs"
  },
  "watch": true
}
```

In `main.ts`, add comment:
```ts
// Static typing catches: let x: string = 123; // Compile error
// Dynamic (JS) would fail at runtime
```

---

### 2. **Complete Each File with TODOs**

#### `src/variables.ts`
```ts
// TODO #1: Declare with type annotations
// TODO #2: Use 'any' once + explain why avoid it
// TODO #3: Use literal type 'low' | 'medium' | 'high'
```

#### `src/arrays.ts`
```ts
// TODO #4: Typed array: string[]
// TODO #5: Multidimensional: number[][]
// TODO #6: Push/pop with type safety
```

#### `src/functions.ts`
```ts
// TODO #7: Function with return type
// TODO #8: Optional + default param
// TODO #9: Rest parameter
// TODO #10: Arrow function + forEach
```

#### `src/typeAliases.ts`
```ts
// TODO #11: Simple type alias
// TODO #12: Advanced: object with union/literal
```

#### `src/tuples.ts`
```ts
// TODO #13: Create tuple [string, number, boolean]
// TODO #14: Return tuple from function
```

---

### 3. **Mini Project: `main.ts`**

```ts
import { TaskInfo } from './typeAliases';

// TODO #15: Define TaskStatus (literal) and Task (type alias)
// TODO #16: tasks: Task[], taskHistory: [number, string, TaskStatus][][]
// TODO #17: taskSummary: [number, number, number]

// TODO #18: addTask(title, status = 'pending', ...tags): Task
// TODO #19: updateTask(id, newTitle?, newStatus?)
// TODO #20: addMultipleTasks(...titles): Task[]
// TODO #21: Use arrow: tasks.forEach(task => ...)

// TODO #22: Update summary tuple
// TODO #23: Run: add 3 tasks, update 1, log history + summary
```

---

### 4. **Testing**
```bash
tsc --watch
node dist/main.js
```
Output must show:
- Tasks list
- History log
- Summary counts `[2, 1, 0]`

---

### 5. **README.md Updates**
Add:
- What is TypeScript? (your words)
- Screenshot of **no compile errors**
- How you used `tsc --watch`

---

## Evaluation (100 Points)

| %   | Criteria |
|-----|--------|
| 20% | Setup + `tsconfig` + no errors |
| 20% | Variables + `any` + literals |
| 20% | Arrays + multidimensional |
| 20% | Functions (all param types + arrow) |
| 10% | Type aliases |
| 10% | Tuples |
| +Bonus | Filter by status, clean output |

---

## Author
- MEGA TEAM Frontend Mentor: **Mahmoud Ramadan**

---

## License
For **educational use only** within MEGA TEAM.
```

---

### `tsconfig.json`
```json
{
  "compilerOptions": {
    "strict": true,
    "outDir": "./dist",
    "rootDir": "./src",
    "target": "ES2020",
    "module": "commonjs"
  }
}
```

---

### `src/variables.ts` → `tuples.ts`

Example:
```ts
// src/variables.ts
// TODO #1: string, number, boolean
// TODO #2: any + comment
// TODO #3: literal type
```

---

### `src/main.ts`
```ts
// TODO: Import from typeAliases
// TODO: Define types
// TODO: Declare arrays + tuple
// TODO: Write all functions
// TODO: Run demo
```