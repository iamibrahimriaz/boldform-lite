=== BoldForm Lite ===
Contributors: themewant, maha25
Tags: forms, contact form, form builder, drag and drop, gutenberg
Requires at least: 6.3
Tested up to: 7.0
Requires PHP: 7.4
Stable tag: 1.1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Lightweight drag-and-drop form builder for WordPress with shortcode, Gutenberg block, Elementor widget, AJAX submissions, and email integrations.

== Description ==

**BoldForm Lite** is a powerful yet lightweight form builder for WordPress. Build any kind of form using a visual drag-and-drop editor, embed it anywhere with a shortcode, Gutenberg block, or Elementor widget, and manage every submission right inside your WordPress dashboard.

Whether you need a simple contact form, a multi-field registration form, or a survey with conditional logic — BoldForm Lite has you covered with zero bloat.

* [Live Demo](https://themewant.com/plugins/boldform) | [Documentation](https://documentation.themewant.com/docs/boldform-user-guide/) | [Support](https://themewant.com/support/) | [Community](https://www.facebook.com/groups/themewant)

---

= Core Features =

**Drag & Drop Form Builder**
Build forms visually without writing a single line of code. Drag fields from the sidebar, reorder them, and configure each one instantly.

**AJAX Form Submission**
Forms submit without a full page reload, giving visitors a smooth, fast experience.

**Entries Management**
Every submission is stored in your WordPress database. View, filter, read, and delete entries from the BoldForm > Entries page. Mark entries as read, unread, or spam.

**Email Notifications**
Automatically send an admin notification on every submission. Configure a custom "From" name, reply-to address, subject, and message body. Test email delivery directly from the settings panel.

**Reports & Analytics**
A built-in reports dashboard shows total forms, total entries, and per-form performance stats using the browser's native HTML5 Canvas chart — no external library required.

**Export & Import**
Export all forms, a single form with its entries, or global settings as a JSON file. Import everything back with one click — great for moving between environments.

**Multi-Step Forms**
Divide long forms into steps using the Section Break field. Display a progress bar, step indicators, or headings. Fully style the Next/Previous buttons and progress colors.

**Conditional Logic**
Show or hide any field based on the visitor's previous answers. Supports AND/OR logic rules per field.

**Form Templates**
Start from a pre-built template instead of a blank form. Pick a template during form creation and customise from there.

**Translation Ready**
All strings are internationalised using the `boldform-lite` text domain, ready for translation with any standard WordPress translation workflow.

**Multisite Compatible**
Tables are created automatically for each new subsite when the plugin is network-activated.

---

= Form Fields =

**Standard Fields**
* Text
* Email
* Number
* Textarea
* Phone
* URL
* Numeric

**Choice Fields**
* Select (single or multi-select with custom dropdown)
* Multi Select
* Checkbox
* Radio Button
* Country

**Date & Time**
* Date picker (powered by Flatpickr)
* Time picker

**Rating & Range**
* Star Rating
* Slider / Range

**Input Helpers**
* Input Mask (formatted text input)

**Layout & Content**
* Section Break (multi-step divider)
* Paragraph / Static Text
* HTML Editor
* Terms & Conditions

**File & Media**
* File Upload (configurable max size, stored in WordPress uploads)

**Address & Identity**
* Name (structured first / middle / last name)
* Address (structured address field)

---

= Embedding Options =

* **Shortcode** — `[boldform id="123"]`
* **Gutenberg Block** — Insert the BoldForm block in any page or post
* **Elementor Widget** — Full widget with rich styling controls in the Elementor editor

---

= Spam Protection =

* **Honeypot** — Invisible hidden field catches bots automatically, no setup required
* **Google reCAPTCHA v2** — Checkbox challenge; requires a site key and secret key from Google
* **hCaptcha** — Privacy-friendly alternative to reCAPTCHA; requires keys from hCaptcha
* **Math Captcha** — Simple arithmetic challenge, works out of the box with no API keys

---

= Email Marketing Integrations =

Connect forms to email marketing platforms and automatically add subscribers on submission.

* **Mailchimp** — Add contacts to any audience list with email, first name, and last name mapping
* **Brevo (formerly Sendinblue)** — Add contacts to any Brevo list with field mapping

Configure connections under **BoldForm > Settings > Integrations**, then assign a connection to each form.


---

= BoldForm Pro — Coming Soon =

BoldForm Pro extends Lite with advanced features for professionals and agencies:

**Advanced Form Fields**
* Signature field
* Image Choice field
* Repeater field (multi-instance rows)
* Calculation field
* Auto-Populate field
* Geolocation field
* Product, Quantity, Custom Amount, and Order Summary fields

**Multi-Page Forms**
Advanced multi-step forms with save-and-resume, step validation, and conditional page routing.

**Payments**
Accept one-time and recurring payments directly inside your forms:
* Stripe (credit/debit cards)
* PayPal (checkout redirect)
* Payment calculator with custom pricing rules

**Advanced Analytics**
Detailed per-form analytics: submission trends, field abandonment rates, conversion tracking.

**Scheduling**
Open and close forms automatically on a date/time schedule.

**Webhooks**
Send form data to any external URL via HTTP POST on each submission.

**Automation Integrations**
* Zapier
* Make (formerly Integromat)
* Pabbly Connect

**CRM & Email Marketing (Pro)**
* ActiveCampaign
* ConvertKit
* AWeber
* GetResponse
* MailerLite
* HubSpot
* Zoho CRM
* FluentCRM
* Help Scout

**Productivity & Storage**
* Google Sheets — Append a row to any spreadsheet on each submission
* Google Drive — Save uploaded files directly to a Drive folder
* Dropbox — Save uploaded files to a Dropbox folder

**Messaging & Notifications**
* Slack — Post a rich message to any channel via incoming webhook
* Discord — Post to a Discord channel
* Telegram — Send a message to a bot or channel
* Microsoft Teams — Post a card to a Teams channel

**Conditional Logic (Pro)**
Advanced conditional rules with multi-field dependencies, page-level conditions, and email routing logic.

---

== Installation ==

1. Upload the plugin files to `/wp-content/plugins/boldform-lite/`, or install via **Plugins > Add New** in the WordPress admin.
2. Activate the plugin through the **Plugins** screen.
3. Go to **BoldForm** in the admin sidebar and create your first form.
4. Copy the shortcode shown in the form editor and paste it on any page, or use the Gutenberg block / Elementor widget.

---

== Frequently Asked Questions ==

= How do I display a form? =

Three options: paste `[boldform id="123"]` into any page or post, use the **BoldForm** Gutenberg block, or drag the **BoldForm** widget into any Elementor layout.

= Where can I see form submissions? =

Go to **BoldForm > Entries** in the WordPress admin. Click any row to see the full submission detail.

= Does the plugin store submissions in the database? =

Yes. Every submission is stored in a custom table so you always have a permanent record, independent of email delivery.

= Can I send a notification email to the person who submitted the form? =

Admin notifications are included in the Lite version. User (submitter) notifications are part of the email routing system; configure the recipient email to the field that collects the user's address.

= How do I enable spam protection? =

Go to **BoldForm > Settings > Captcha**. Choose your preferred provider (Honeypot is always active). Enter API keys for reCAPTCHA or hCaptcha if you select those.

= Is BoldForm multisite compatible? =

Yes. When the plugin is network-activated, it automatically creates the necessary database tables for each new subsite.

= Does it work with Elementor? =

Yes. BoldForm registers a native Elementor widget with full styling controls for fields, labels, buttons, and more — all editable within the Elementor panel.

= Will there be a Pro version? =

Yes, BoldForm Pro is currently in development. It will add payments (Stripe, PayPal), advanced field types, more integrations, scheduling, webhooks, and more. See the **BoldForm Pro — Coming Soon** section above for the full list.

---

== Screenshots ==

1. Add New Form
2. Drag & Drop Builder
3. Form Preview
4. Form Confirmation Settings
5. Form Global Settings
6. Form Analytics
7. Form Integration
8. Form View On Page

---

== Bundled Libraries ==

All JavaScript and CSS assets are bundled locally within the plugin directory. No scripts or styles are loaded from a CDN or any remote server except for the explicitly documented external services listed below.

**Bundled third-party libraries:**

* **Flatpickr** (`assets/js/flatpickr.min.js`, `assets/css/flatpickr.min.css`) — MIT License — https://github.com/flatpickr/flatpickr
  Local copy used for the date and time picker fields. Not fetched from any CDN.

**First-party scripts:**

* `assets/js/sortable.js` — a small first-party drag-and-drop helper written for this plugin (used for field ordering in the builder). It is original BoldForm code, not the third-party SortableJS library, and is GPL-licensed with the rest of the plugin.

The submissions chart on the Reports page is rendered using the browser's native HTML5 Canvas API. No external charting library is loaded.

---

== External Services ==

This plugin can optionally connect to the following third-party services. No data is transmitted to any external service unless you have explicitly enabled and configured that service in BoldForm settings.

= Google reCAPTCHA =

Protects forms from spam and bot submissions.

When a page containing a reCAPTCHA-enabled form is loaded, Google's reCAPTCHA script is loaded from Google's servers. On submission, the plugin sends the reCAPTCHA token and the visitor's IP address to Google's verification API.

* Data sent: reCAPTCHA response token, visitor IP address
* When: Each form submission with reCAPTCHA enabled
* Condition: Only when "Google reCAPTCHA" is selected in BoldForm > Settings > Captcha and valid keys are entered
* Service provider: Google LLC
* Terms of Service: https://policies.google.com/terms
* Privacy Policy: https://policies.google.com/privacy

= hCaptcha =

Privacy-friendly alternative for spam protection.

When a page with an hCaptcha-enabled form is loaded, the hCaptcha script is loaded from hCaptcha's servers. On submission, the token and visitor IP are sent to hCaptcha's verification API.

* Data sent: hCaptcha response token, visitor IP address
* When: Each form submission with hCaptcha enabled
* Condition: Only when "hCaptcha" is selected in BoldForm > Settings > Captcha and valid keys are entered
* Service provider: Intuition Machines, Inc.
* Terms of Service: https://www.hcaptcha.com/terms
* Privacy Policy: https://www.hcaptcha.com/privacy

= Mailchimp =

Adds subscribers to a Mailchimp audience on form submission.

* Data sent: Email address, and optionally first name and last name (only fields you map)
* When: Each submission of a form with an active Mailchimp integration
* Condition: Only when a Mailchimp connection with a valid API key is configured under BoldForm > Settings > Integrations
* Service provider: The Rocket Science Group LLC (Mailchimp)
* Terms of Use: https://mailchimp.com/legal/terms/
* Privacy Policy: https://mailchimp.com/legal/privacy/

= Brevo (formerly Sendinblue) =

Adds contacts to a Brevo list on form submission.

* Data sent: Email address, and optionally first name and last name (only fields you map)
* When: Each submission of a form with an active Brevo integration
* Condition: Only when a Brevo connection with a valid API key is configured under BoldForm > Settings > Integrations
* Service provider: Brevo SAS
* Terms of Use: https://www.brevo.com/legal/termsofuse/
* Privacy Policy: https://www.brevo.com/legal/privacypolicy/

---

== Privacy ==

When a visitor submits a form, BoldForm Lite stores the submission in your site's own database (no data is sent anywhere unless you have configured one of the external services listed above). Each stored entry includes:

* The values the visitor entered in the form fields (which may include personal data such as name, email address, phone number, address, and any uploaded files).
* The submitter's IP address and browser user-agent string, recorded for spam-prevention and auditing.
* The logged-in user ID, when the form is submitted by a logged-in user.

Entries are retained until you delete them. You can remove individual entries (or all of them) from **BoldForm > Entries** at any time. If you enable "Remove all data on uninstall" in the settings, all stored forms and entries are deleted when the plugin is uninstalled.

BoldForm Lite integrates with WordPress's built-in privacy tools: under **Tools > Export Personal Data** and **Tools > Erase Personal Data**, an administrator can export or erase the form entries associated with a given email address to help fulfil data-subject requests.

---

== Changelog ==

= 1.1.0 =
New features:
* New: Dual-handle range slider — an opt-in "Dual range (min–max)" mode renders two handles with a filled track and validates the selected range on submit.
* New: Greatly expanded Style tab with live preview — field, label, and submit-button styling update instantly beside the controls, with Normal/Hover/Focus/Checked state tabs across every section, selectable Design Themes, gradient backgrounds, a styled file-upload drop-zone, sub-field label styling, container alignment and max-width, and per-device (desktop/tablet/mobile) responsive values.
* New: Help & Support page with links to the User Guide, Developer Guide, Support, Community, Leave a Review, and Request a Feature.
* New: "Mark as Spam" entry action and a Spam filter tab on the Entries screen.
* New: The BoldForm logo now appears throughout the admin — the sidebar menu icon adapts to your admin colour scheme, and the mark replaces the generic placeholder icon in the topbar, form builder, Reports, and the empty Forms state.

Privacy (GDPR):
* Privacy: A personal-data exporter and eraser are registered with WordPress's privacy tools, keyed on the submitter's email address, so site owners can fulfil data export and erasure requests for form entries.
* Privacy: readme now documents what data is stored, how long it is kept, and how to export or erase it.

Security:
* Security: Integration API keys (Mailchimp, Brevo) are never written into page HTML; the builder receives only the connection id, name, type, and status, and the stored key is preserved when the field is left blank.
* Security: File uploads are re-validated on the server — SVG/SVGZ files are rejected, the size cap is enforced against the real on-disk bytes, and an explicit MIME allowlist is verified instead of trusting the filename.
* Security: Stronger SVG sanitization now strips `<a>`, `<style>`, SMIL animation tags, and namespaced `href` attributes, failing closed on files that cannot be parsed.
* Security: Settings import drops uninstall flags, all SMTP fields, and any key, secret, or password values before merging an uploaded file.
* Security: Form save sanitizes every field and option by type, de-duplicates field IDs, and caps the number of rows, columns, fields, and options.
* Security: Integrations dispatch only to explicitly active connections, and a connection with no API key can no longer be enabled.
* Security: The Mailchimp list ID is constrained to its expected grammar before use (SSRF hardening), and the settings option no longer autoloads SMTP passwords and captcha secret keys on every page.
* Security: Database errors are only surfaced when WP_DEBUG is enabled, so production never leaks raw SQL details.

Accessibility:
* Accessibility: Star-rating fields are fully keyboard and screen-reader operable (radiogroup, roving tabindex, arrow/Home/End/Space/Enter, per-star labels, visible focus ring).
* Accessibility: The custom dropdown supports in-listbox keyboard navigation (Arrow/Home/End/Enter/Escape) with an active-option highlight.
* Accessibility: On submit, validation errors are announced and associated with their fields (aria-invalid, aria-describedby, role="alert"), and focus moves to the first invalid field; choice and name groups gain role="group" with proper labelling.
* Accessibility: The builder announces row and field add/delete/duplicate actions to screen readers.

Performance:
* Performance: CSV export now streams in bounded batches instead of loading every entry into memory, so large exports no longer risk a memory spike (the output is identical).
* Performance: Each form is loaded once per request, so embedding the same form multiple times on a page no longer repeats the query.

Improvements:
* Improve: The forms list now matches WordPress-native list tables, with sortable column headers, a synced select-all checkbox, and native-styled bulk and filter controls.
* Improve: Builder canvas polish — clearer field hover and selected states, an accordion Style tab, a full-width Settings tab, a topbar that reflows before overlapping on narrow screens, and an improved shortcode copy button.
* Improve: An editing overlay now covers the canvas while the builder loads an existing form, so it no longer flashes the empty "Start building" placeholder.
* Improve: Conditional Logic condition rows wrap cleanly on narrow builder panels and small screens.
* Improve: The field library is drag-only — fields clone onto the canvas and the palette is never a drop target.
* Improve: Slider, star-rating, and field styling now follow the form's design theme; star rating defaults to a consistent size.
* Improve: Refreshed the Forms admin screen — the action notice ("Form moved to trash", etc.) is now a modern alert in the page header, the empty state has a styled "Add New Form" button, the top spacing is tightened, and the form builder sits flush with no left gap.
* Improve: Redesigned the form Preview screen header into a single toolbar with an Exit button, a clear "Form Preview" title, and a click-to-copy shortcode pill.
* Improve: Redesigned the Choose Column Layout dialog with guided layout cards, hover/focus highlighting, and a clearer header and hint.
* Improve: Trimmed redundant builder controls — the duplicate "Add Row" panel-header button and a stray file-input sample in the Style-tab preview.

Fixes:
* Fix: Forms are no longer submitted for real when rendered in an editor or preview — the Gutenberg block preview, the Elementor editor, and the admin Preview Form screen.
* Fix: Numeric min/max/step bounds and dual-slider ranges are now enforced on the server, not just shown as input hints.
* Fix: A required dropdown no longer silently submits its first option; an empty placeholder option is emitted and empty required selects are rejected server-side.
* Fix: Forms embedded more than once on a page now get unique element IDs, so labels and widgets target the correct instance.
* Fix: Checkbox, radio, and dropdown selected states now follow the form's design-theme colour instead of always showing the default teal.
* Fix: Each field's configured maximum file size is honoured instead of a fixed 2 MB cap, and rich-content fields render their formatting correctly.
* Fix: Multi-part (Name, Address) and multi-select values now render consistently across the email notification, admin entry view, CSV export, entries list, and the privacy data export — no more "John, , Doe" names or gappy addresses — and multi-line text keeps its line breaks in the email body.
* Fix: Mailchimp contacts are upserted (PUT) instead of POSTed, resolving the "Member Exists" error on repeat submissions.
* Fix: Removed the non-functional Brevo "Tags" field and pre-select the form's email field when a connection is assigned.
* Fix: Restored the `boldform_field_library` filter so add-ons can register custom field types again.
* Fix: Email fields are validated with `is_email()`, duplicate-entry detection honours each field's own ID, and client-side conditional-logic operators match the server evaluator exactly.
* Fix: The BoldForm block inspector now shows only Form Settings; the duplicate Container, Layout, Labels, Input, Button, and Error style panels (already covered by the builder's Style tab) were removed.
* Fix: The BoldForm block form preview keeps its styling when Hide Labels or Hide Placeholders is enabled.
* Fix: Admin topbar CSS now loads correctly on the Help & Support page, and the topbar wraps correctly when many nav items are present.
* Fix: Elementor widget cleanup — removed duplicate/dead controls, fixed focus-state label colours not applying, made the Checkbox/Radio Size control work against the visible field, and converted the Terms checkbox radius to a per-corner control.

Compatibility:
* Update: Tested up to WordPress 7.0; minimum supported version is now WordPress 6.3.
* Update: The Gutenberg block was upgraded to Block API version 3 for the WordPress 6.3+ iframed editor, and its in-editor preview is now styled.

Developer:
* Dev: New `boldform_integration_dispatched` action fires after each integration dispatch with the integration type, connection ID, the API response (array or WP_Error), and the entry ID.
* Dev: Lifecycle cleanup — the integration-dispatch cron is cleared on deactivation, and stored connections plus migration flags are removed on opted-in uninstall.

= 1.0.2 =
* Improve: Rewrote the readme with the full feature list, integration documentation, and a "Pro coming soon" section.
* Improve: Minor admin and Elementor widget polish. Documentation and packaging maintenance release — no changes to form rendering or submission behaviour.

= 1.0.1 =
* Fix: Buttons now include an accessible `aria-label` so screen readers announce the button text correctly.
* Fix: Select fields now include `aria-label`, `aria-haspopup`, and `aria-controls` attributes for full WCAG compliance.
* Fix: Native select element is correctly hidden when the custom dropdown is active, eliminating the duplicate-box display bug.
* Fix: Version constant updated to match plugin header, resolving asset versioning and remote file loading issues.
* Add: Separate Button Margin control in Elementor targeting the button element directly.
* Add: Restored missing Elementor widget settings for Section Break and Terms & Conditions sections.

= 1.0.0 =
* Initial release.

== Upgrade Notice ==

= 1.1.0 =
Security hardening, accessibility improvements, and GDPR export/erase support, plus the live style preview and Elementor refinements. Recommended for all users.
