# Student Registration Form

A clean, responsive student registration form with real-time client-side validation built using HTML, CSS, and JavaScript.

## Features

- **Modern UI Design**: Gradient background with teal color scheme and smooth transitions
- **Client-Side Validation**: Real-time form validation with helpful error messages
- **Responsive Layout**: Centered form layout that works across different screen sizes
- **Input Validation** for:
  - First name (minimum 3 characters)
  - Roll number (must start with "PG")
  - Father's name (required field)
  - Gender selection (required)
  - Department selection (at least one required)
  - Course selection (required)
  - Email format validation
  - Mobile number (exactly 10 digits)

## Form Fields

The registration form includes the following fields:

- **Student Name**: First and Last name inputs
- **Roll Number**: Text input with PG prefix validation
- **Father's Name**: Required text input
- **Date of Birth**: Separate DD, MM, YYYY inputs
- **Mobile Number**: 10-digit validation
- **Email**: Valid email format required
- **Password**: Secure password input
- **Gender**: Radio button selection (Male/Female)
- **Departments**: Multiple checkbox selection (Computer Science, Electronics, Mechanical, Civil)
- **Course**: Dropdown selection (BSc, BCA, BCom)
- **City**: Text input
- **Address**: Textarea for detailed address

## Validation Rules

- **First Name**: Must be at least 3 characters long
- **Roll Number**: Must start with "PG"
- **Father's Name**: Cannot be empty
- **Gender**: Must select one option
- **Departments**: Must select at least one department
- **Course**: Must select a course from dropdown
- **Email**: Must be a valid email format
- **Mobile Number**: Must be exactly 10 digits

## Technologies Used

- **HTML5**: Structure and form elements
- **CSS3**: Styling with gradients, transitions, and modern design
- **JavaScript**: Form validation and error handling

## Color Scheme

- Primary: `#0d9488` (Teal)
- Background: Gradient from `#ccfbf1` to `#ffffff`
- Text: `#1f2937` (Dark gray)
- Headings: `#1e5e59` (Dark teal)

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/student-registration-form.git
   ```

2. Open `index.html` in your web browser

3. Fill out the form fields

4. Click Submit - the form will validate all fields before submission

5. Fix any validation errors shown in red text below each field

## File Structure

```
student-registration-form/
│
├── index.html          # Main HTML file with embedded CSS and JavaScript
└── README.md          # Project documentation
```

## Screenshots


<img width="957" height="905" alt="image" src="https://github.com/user-attachments/assets/962cac47-4735-432d-83be-cf1685952ab9" />

## Known Issues

- Email validation regex variable `emailPattern` is referenced but not defined in the JavaScript
- Form submission doesn't actually send data anywhere (no backend integration)
- Date of Birth fields are separate text inputs without proper validation



