# GMS Viber Admin Template Management Demo

Interactive admin-side prototype for managing Viber templates.

## Scope

The MVP keeps the admin experience focused on operational lookup and inspection.

### Admin filters

- Customer Name
- Reseller Name
- Viber ID

The filters are dependent, so customer/reseller selection narrows the available Viber IDs.

### Template table

The table intentionally uses the same core fields as the customer-side Viber template experience:

- Template Name
- Template ID
- Status
- Category
- Language
- Creation Date
- Actions

### Template details

Use the row action to expand a template and inspect:

- Customer Name
- Reseller Name
- Viber ID
- Service ID
- Creator
- Last Modified
- Status Note
- Message Body
- Variables and moderation examples
- Viber message preview

### Template statuses

- Approved
- Pending
- Declined

## Prototype notes

This is a static UX prototype using sample data. It does not connect to GMS or Viber production APIs.

Open `index.html` directly in a browser to run the demo.