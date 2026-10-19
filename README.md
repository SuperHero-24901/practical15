# Login Studio — Uncontrolled Form

## Aim
Login Studio — a React practical built with Vite, React, React Router DOM where relevant, and Tailwind CSS v4.

## Concepts used
- React functional components and JSX
- Component-based UI and responsive utility-first styling
- React hooks
- Form state, validation, and interactive feedback where relevant

## Requirements
- Node.js 20.19+ or 22.12+ recommended
- npm

## Run the project
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```

Each practical is independent. Open its folder in VS Code and run the commands from that folder.


## Uncontrolled components and useRef
The input elements keep their own values in the DOM. `useRef()` stores references to those input elements; on submit, the code reads `usernameRef.current.value` and `passwordRef.current.value`. Unlike a controlled form, the field values are not copied into React state on every keystroke.

**Security warning:** showing a password after submission is only for this educational exercise. Never display, log, or store plaintext passwords in a real application. This demo does not authenticate users.
