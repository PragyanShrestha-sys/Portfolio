# Portfolio Website - Praygan Shrestha

A modern, responsive portfolio website showcasing projects and contact information.

## Setup Instructions

1. **Add Your Profile Image**
   - Place your profile image in the root directory
   - Name it `profile.jpg` (or update the image path in `index.html` if using a different name/format)
   - Supported formats: JPG, PNG, JPEG

2. **Email Configuration**
   - The contact form is configured to send emails to: `yoshiwhale1@gmail.com`
   - Make sure your XAMPP server has PHP mail functionality enabled
   - For local testing, you may need to configure PHP's `php.ini` file with SMTP settings
   - For production, consider using a service like PHPMailer with SMTP

3. **Running the Website**
   - Start your XAMPP server
   - Place the project files in `htdocs/Portfolio`
   - Access via: `http://localhost/Portfolio`

## Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Projects section with 6 template examples
- ✅ Contact form with email functionality
- ✅ Modern UI with animations
- ✅ Mobile-friendly hamburger menu

## File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
├── send-email.php      # PHP email handler
├── profile.jpg         # Your profile image (add this)
└── README.md           # This file
```

## Customization

- Update social media links in the hero section
- Modify project cards with your actual projects
- Adjust colors in `styles.css` (CSS variables at the top)
- Update contact information as needed

## Notes

- The PHP mail function requires proper server configuration
- For production, consider using SMTP or a service like SendGrid/Mailgun
- Test the contact form to ensure emails are being sent correctly


