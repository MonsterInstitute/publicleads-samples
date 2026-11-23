# PublicLeads — free masked samples of local business lists

Masked 25-row samples of [PublicLeads](https://www.publicleads.com) business lists: local businesses taken from public Google Business
Profiles, with business name, city, website domain, Google rating and review count kept, and phone, email and street
address masked. Each folder is one list (one trade, one city) with its own README.

| Sample | Rows | Full list |
|---|---|---|
| [Dentists in Toronto, Ontario, Canada](toronto-dentists/) | 25 of 332 | https://www.publicleads.com/dentists/canada/ontario/toronto |
| [Plumbers in Houston, Texas, USA](houston-plumbers/) | 25 of 77 | https://www.publicleads.com/plumbers/usa/texas/houston |
| [Dentists in Los Angeles, California, USA](los-angeles-dentists/) | 25 of 162 | https://www.publicleads.com/dentists/usa/california/los-angeles |

Every list on PublicLeads (trades × cities, states / provinces and countries — USA, Canada, Australia): https://www.publicleads.com/browse

## Columns

| Column | What it holds |
|---|---|
| business_name | The business's public Google Business Profile name |
| category | The trade |
| city, state_province, country | Location (ISO country code) |
| postal_prefix | First 3 characters of the postal / ZIP code (street address removed) |
| phone_masked | Phone number, last 2 digits only |
| email_masked | Email, first letter and top-level domain only (blank: no email found) |
| email_type | Business (shared/role address) or Personal (a named person's address) |
| website_domain | The business's website domain |
| google_rating, review_count | Google rating and number of reviews |
| email_check | Valid (the mailbox answered a check), Catch-all (the server accepts every address) or Unverified |
| audit_date | When the email was last checked |

Masking: no full email, phone number or street address is in any file here.

How the data is collected and refreshed: https://www.publicleads.com/about
What is in a full list file (columns, formats): https://www.publicleads.com/guides/what-is-in-a-lead-list-file-excel-and-csv
Responsible use: https://www.publicleads.com/compliance
A listed business can correct or remove its listing: https://www.publicleads.com/your-business

## Licence

This **sample file** is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — reuse it with the
credit "PublicLeads (publicleads.com)". The full lists are sold under the PublicLeads terms: https://www.publicleads.com/terms
