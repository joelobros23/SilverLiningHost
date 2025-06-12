# Project Plan: SilverLiningHost

**Description:** A simple and intuitive web hosting platform built with Ruby on Rails, focusing on ease of use and essential features.


## Development Goals

- [ ] Install and configure Tailwind CSS and Simple Form.
- [ ] Customize Devise views (sign up, login, etc.) to utilize Tailwind CSS for styling.
- [ ] Modify the Domain model to belong to a User (add association and foreign key).
- [ ] Implement authorization logic to ensure users can only manage their own domains using `before_action` filters in the Domains controller.
- [ ] Add a 'Manage Domains' link to the navigation that only appears when a user is logged in.
- [ ] Implement domain name validation to prevent duplicate domain names within a single user's account.
- [ ] Enhance the Domain scaffold to use Simple Form for better form handling and UI consistency.
- [ ] Implement basic domain status management (Active, Suspended, Expired) with a status update feature.
- [ ] Implement logic to send email reminders to users before their domain expiration date using Action Mailer.
- [ ] Add a simple pricing page to display different hosting plans.
- [ ] Add a dashboard showing a summary of the user's domains, active plans and other relevant data.
- [ ] Secure the platform by implementing strong password policies and input validation to prevent common web vulnerabilities.
