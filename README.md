# 📬 Angular Contact Form

This is a clean, responsive, and accessible contact form built using Angular 19 with standalone component architecture. It showcases how to build forms with validation, reactive form handling, and dynamic user feedback.

---

## 🔧 What I Built

I developed a standalone `ContactFormComponent` that allows users to submit contact details with real-time validation and conditional success/error messages using:

* Angular CLI 19.1.x
* Standalone component architecture
* Reactive Forms with `FormBuilder`
* Built-in Angular validators (e.g., `required`, `email`, `minLength`)
* Success and error status rendering
* Accessible HTML form elements

---

## 💡 Key Features

✅ Real-time validation and feedback
✅ Built-in Angular reactive form handling
✅ Success/error messages on form submit
✅ Custom error styling using `ngClass`
✅ Form is disabled until valid
✅ Clean SCSS design with accessibility best practices

---

## 🧱 Technologies Used

* Angular 19 (standalone component)
* TypeScript for form logic
* Reactive Forms Module (`FormGroup`, `FormBuilder`, `Validators`)
* HTML5 inputs with ARIA support
* SCSS for styling and layout
* Angular directives (`*ngIf`, `[formGroup]`, `[formControlName]`)
* Event binding with `(ngSubmit)`

---

## 📸 Screenshot

![Contact Form Screenshot](public/contact-form-screenshot.png)

---

## 📁 Project Structure

```
src/
└── app/
    └── contact-form/
        ├── contact-form.component.ts       # Form logic and state handling
        ├── contact-form.component.html     # Form UI template
        └── contact-form.component.scss     # Styles for form and responsiveness
```

---

## 🚀 Running the Project

Ensure Angular CLI is installed globally:

```bash
npm install -g @angular/cli
```

Install dependencies and run the development server:

```bash
npm install
ng serve
```

Navigate to `http://localhost:4200` in your browser to view the form.
