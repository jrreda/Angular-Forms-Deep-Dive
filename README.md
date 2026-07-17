# Angular Forms Deep Dive

A small Angular 18 project demonstrating how to build and validate a signup
form with reactive forms.

## Topics covered

- Standalone Angular components
- Reactive forms with `FormGroup` and `FormControl`
- Nested form groups for passwords, names, and addresses
- Checkbox collections with `FormArray`
- Built-in validators for required fields, email addresses, and minimum lengths
- A custom cross-field validator for matching passwords
- Form submission and reset handling

## Form structure

The signup form collects:

- Email address
- Password and password confirmation
- First and last name
- Address details
- User role
- Discovery sources
- Terms and conditions acceptance

## Getting started

### Prerequisites

- Node.js
- npm

### Installation

```bash
npm install
```

### Development server

```bash
npm start
```

Open [http://localhost:4200](http://localhost:4200). The application reloads
automatically when source files change.

## Available scripts

- `npm start` — start the development server
- `npm run build` — create a production build in `dist/`
- `npm run watch` — rebuild when source files change
- `npm test` — run the unit tests with Karma and Jasmine

## Main implementation

The reactive signup form is defined in
`src/app/auth/signup/signup.component.ts`, and its controls are connected to the
template in `src/app/auth/signup/signup.component.html`.
