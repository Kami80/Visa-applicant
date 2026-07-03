# University Admission & Visa Tracker

A simple public website for tracking university admission progress, Universitaly confirmation dates, visa appointment dates, and student visa experiences.

The website is designed for students who are going through the Italian university admission and student visa process and want to compare timelines, share updates, and learn from other applicants' experiences.

---

## Website Pages

### 1. Dashboard

The main dashboard shows the submitted admission and visa timeline data.

On this page, users can see:

- Total number of submissions
- Number of universities represented
- Number of programs represented
- Number of students with visa appointments
- University name
- Program name
- Universitaly confirmation date
- Visa appointment date

Users can also:

- Search records
- Filter records
- Sort the table
- Switch between light and dark mode
- Refresh the page to see the newest data

The dashboard is meant to give a quick overview of the admission and visa timeline for the student group.

---

### 2. Visa Experiences

The Visa Experiences page is used for sharing detailed visa appointment and visa result experiences.

This page may include:

- University name
- Program name
- Universitaly confirmation date
- Visa appointment date
- Visa issue or received date
- Visa status
- Whether the applicant had an interview
- Interview questions, if any
- Documents checked by the embassy or consulate
- Appointment duration
- Practical advice for future applicants
- A written explanation of the visa experience

This page is useful for students who want to understand what usually happens during the visa appointment and what documents or questions may be important.

Each experience is based on student-submitted information. It should be used as a helpful reference, not as official legal or embassy guidance.

---

### 3. Blog

The Blog page contains guide-style posts about the admission and visa process.

Blog posts may explain topics such as:

- Universitaly validation
- Student visa deadlines
- Pre-enrolment steps
- Type D study visa information
- Permit of stay after arriving in Italy
- How to write a useful visa experience

The blog is intended to help students understand the process more clearly and avoid common misunderstandings.

For official rules, users should always check the relevant embassy, consulate, Universitaly, and Visa for Italy websites.

---

## How to Submit Data

Users can submit their information through the **Submit Data** button on the website.

After submitting the form, the information is saved in the connected Google Sheet. The website reads from that sheet and updates automatically.

Depending on the browser and connection, new data may appear after:

- Refreshing the page
- Waiting for the automatic sync
- Checking that the Google Form submission was completed successfully

Please submit information carefully and avoid duplicate or incorrect entries.

---

## How to Use the Dashboard

### Search

Use the search box to find records by:

- University name
- Program name
- Confirmation date
- Visa appointment date
- Visa status or experience text, depending on the page

### Filters

Use filters to narrow the results. Filters may include:

- University
- Program
- Visa status
- Interview status
- Visa received or pending status

### Sorting

Some table columns can be sorted by clicking the column title.

### Dark Mode

Use the theme button to switch between light mode and dark mode.

---

## Important Notes for Users

This website is a community tracker. It is not an official embassy, consulate, university, or government website.

The information shown on the website is based on user-submitted data. Dates and experiences may vary depending on:

- University
- Program
- Embassy or consulate
- Applicant nationality
- Document completeness
- Appointment availability
- Individual case conditions

Always confirm official requirements through official sources before making decisions.

---

## Privacy Reminder

Users should avoid submitting sensitive personal information.

Do not submit:

- Passport number
- National ID number
- Home address
- Bank account details
- Private financial documents
- Phone number, unless the form specifically requires it and the data manager confirms how it is used
- Any information you do not want to be publicly visible

Visa experiences should be written in a helpful but privacy-conscious way.

---

## Troubleshooting

### The page is not showing data

Possible reasons:

- The Google Sheet is not published or accessible
- The internet connection is unstable
- The browser blocked the data request
- The column names in the Google Sheet were changed
- The page is being opened directly from the computer instead of through a web server or GitHub Pages

Recommended fixes:

- Refresh the page
- Open the website through the GitHub Pages link
- Make sure the Google Sheet is shared or published correctly
- Check that the column names match the website code

### My submitted data is not visible

Possible reasons:

- The website has not refreshed yet
- The Google Form submission was incomplete
- The data was entered in a different sheet tab
- The submitted row contains missing required fields

Try refreshing the page or checking the form submission again.

### The website looks broken on mobile

Try:

- Refreshing the page
- Opening it in another browser
- Clearing browser cache
- Checking that the latest version of the files was uploaded to GitHub

---

## For Website Maintainers

The website is a static GitHub Pages site. It does not require a backend server.

Recommended file structure:

```text
project-root/
├── index.html
├── visa-experience.html
├── blog.html
└── README.md
```

To publish the site on GitHub Pages:

1. Upload all files to the repository root.
2. Go to **Settings**.
3. Open **Pages**.
4. Select **Deploy from branch**.
5. Choose the `main` branch and `/root` folder.
6. Save and wait for GitHub Pages to publish the site.

If using GitHub Actions, make sure only one Pages deployment runs at a time to avoid deployment conflicts.

---

## Google Sheet Requirements

The website depends on a connected Google Sheet.

The main dashboard should include columns such as:

- University name
- Program name
- Universitaly confirmation date
- Visa appointment date

The Visa Experiences page can support additional columns such as:

- Visa received date
- Visa status
- Interview status
- Interview questions
- Checked documents
- Appointment duration
- Advice
- Visa experience text

If column names are changed in the Google Sheet, the website code may need to be updated so it can read the correct data.

---

## Disclaimer

This website is for informational and community-support purposes only.

It does not replace official information from:

- Italian embassies or consulates
- Universitaly
- Visa for Italy
- Universities
- Government immigration authorities

Users are responsible for checking official sources before making decisions about admission, visa applications, travel, or immigration procedures.
