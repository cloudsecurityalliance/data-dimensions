# data-dimensions

The following are examples of data dimensions for adminsitrative control of a cloud service. We need to break this up into things like:

1. Attacker/Defender/Administrator/User/etc views
2. How is it measured? Yes/No/List of items/free form/etc?
3. Grouping and splitting them up a bit to get major categories (e.g. Logging vs Reporting)
4. Determining how much they matter, and which depend on each other (does this matter?)

## 2FA/MFA

### Capabilities
Is 2FA/MFA supported? Yes/No?
Are multiple methods (e.g.: SMS/TOTP/HOTP/Custom mobile app/FIDO) supported? Yes/No? Which ones?
Are multiple instances of a method supported? Yes/No?

### Enforcement
Is enforcement of 2FA/MFA supported? Yes/No?
Is enforcement of specific types (enable/disable) supported? Yes/No?

### Administration automation
Can you change multiple accounts using the web interface? (e.g. multiple select)
Can you change multiple accounts using a CSV upload?
Can you change multiple accounts using scripting/API?

### Reporting
Can you see which users have 2FA/MFA enabled?
Can you schedule reports to be generated and sent out?
Can you see what kind of 2FA/MFA is enabled and how many (e.g. 1 or 2 or 3 hardware keys?)

### Logging
Logging of 2FA/MFA usage
Logging of 2FA/MFA changes (registration/removal/etc)

### Recovery process
Recovery codes?
Recovery by email/phone/social ID?

## Logging

Most cloud vendors log, but not all make raw logs or processed logs available, or some may only do so at various price points (e.g. "Enterprise" accounts)

Are raw logs available?
Length of log retention?
Can logs be easily downloaded? Multiple clicks/etc?
Is there an API for log access?
Are there documents for the log data and format? Can you do mappings of e.g. user-id to the account name/email address?
