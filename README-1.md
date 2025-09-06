# User Registration Form

## 📖 Project Description
A semantic, accessible **User Registration Form** built with HTML5 only (no CSS/JS), following best practices for structure, labels, and validation attributes. Repository includes documentation suitable for academic evaluation.

---

## 🎯 Purpose & Sections
The form collects the necessary details for account creation and is divided into sections:

1. **Personal Information** – name, date of birth, gender, nationality, occupation.
2. **Account Information** – email, username, password, confirm password.
3. **Contact Information** – phone, address, city, state/province, country.
4. **Preferences** – newsletter opt-in, preferred contact method.
5. **Profile** – profile photo, bio, website.
6. **Agreement** – required checkbox confirming Terms and Privacy Policy.
7. **Actions** – Submit and Reset buttons.

---

## 📂 Repository Structure
```
user-registration-form/
├── index.html   # HTML form implementation
└── README.md    # Documentation
```

---

## 🛠️ Implementation Notes
- `<fieldset>` and `<legend>` group fields semantically.
- `<label>` elements improve accessibility and are linked to inputs.
- Correct input types (`email`, `date`, `tel`, `url`, `file`) used for built-in validation.
- Attributes like `required`, `minlength`, `pattern`, `maxlength`, `autocomplete` add validation and usability.
- Accessible hints with `aria-describedby` for profile photo and bio fields.
- Reset button included for better form control.

---

## ▶️ How to Use
1. Download/clone repository.
2. Open `index.html` in a web browser.
3. Fill out required fields marked with `*`.
4. Submit with **Register** or clear with **Reset**.

---

## ✅ Standards Followed
- Semantic HTML5 structure.
- Accessibility best practices.
- No CSS or JS (focus on structure and functionality).
