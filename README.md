# Email Site Reminders

**Email Site Reminders** is a Backdrop CMS module that sends periodic email reports to site administrators. These reports can include:

- A list of unpublished content
- Available module and theme updates
- New user registrations
- Recently published content
- Recent comments
- Optional HTML formatting
- Custom email subject lines
- Configurable send frequency (daily, weekly, or monthly)

## Features

- Configurable recipient list (multiple emails allowed)
- Send test email anytime
- Admin UI at `/admin/config/content/email-site-reminders`
- Integrates with Backdrop's cron system

## Installation

1. Download and place the `email_site_reminders` folder in your `modules/custom` directory.
2. Enable the module from the Modules page.
3. Visit the settings page to configure options.

## Configuration Options

- Send frequency: daily, weekly, or monthly
- Email format: plain text or HTML
- Sections to include: unpublished content, updates, recent comments, new users, etc.
- Custom subject line
- Manual test email option

## GitHub Repository

<https://github.com/stpaultim/email_site_reminders>

## Maintainer

Tim Erickson ([@stpaultim](https://github.com/stpaultim))

## License

This module is released under the GPL-2.0-or-later license.
