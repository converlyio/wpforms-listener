# WPForms Listener

Fires a dataLayer event each time WPForms accepts a submission, with AJAX on or off. Rejected entries are never counted, and your form settings stay exactly as they are.

## Setup

Follow the [setup guide](https://converly.io/gtm-templates/wpforms).

Fire this tag on All Pages so it can follow forms that reload the page. Then trigger your conversion tags on the custom event wpforms_form_submitted.

## Event

The listener sends wpforms_form_submitted. Use CE - WPForms Submitted as the custom event trigger.

## Script

The template loads https://gtm-templates.converly.io/wpforms-listener.js.

## Notes

Sends one wpforms_form_submitted event per accepted WPForms submission, with the form ID. It reads no personal data and doesn't change how your forms submit. Full setup guide at https://converly.io/gtm-templates/wpforms

## License

Apache License 2.0.
