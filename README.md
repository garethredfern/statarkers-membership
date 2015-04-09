Statarkers Membership
=====================
This is a set of base files to get you going with Statamic membership. They can be used easily with the [Statarkers Theme](https://github.com/statamicthemes/statarkers-theme) but it is not required.

## Installing
1. Download the zip.
2. Replace the member folder in `_config/bundles` with the member folder provided.
3. Add the member folder into your theme partials folder (`_themes/statarkers/partials`).
4. Add the member folder into your theme templates folder (`_themes/statarkers/templates`).
5. Add the emails folder into your theme templates folder (`_themes/statarkers/templates`).
6. Replace/copy the `_config/routes.yaml` file into your `_config folder`.
7. Add the following settings to you your `settings.yaml` file.
  - `_email_handler:`
  - `_email_sender: example@example.com #change this to your email`
8. Add the following settings to your _config/bundles/member/member.yaml file.
  - `reset_password_subject: Reset Your Password`
  - `reset_password_text_email: emails/reset_password_text`
  - `reset_password_html_email: emails/reset_password_html`

Once you have the routes set up you do not need to have content pages set up in your main `_content` folder. For more information on routes see the [Statamic documentation](http://statamic.com/learn/advanced-features/routes).

Visit the following pages in your site to see the examples (taken from the routes.yaml file):

- /member/login
- /member/update:
- /member/register
- /member/dashboard
