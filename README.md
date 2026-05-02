# CV by Design — Website Project

Two standalone HTML pages, ready to deploy on Vercel or any static host.

## Files

- `resume-coaching-landing.html` — Main landing page for job seekers
- `coaches-landing.html` — Landing page targeting career coaches
- `jenny-photo.png` — Profile photo used in both pages

## Before deploying

### 1. Update the photo path
Both pages currently reference the photo as `/mnt/user-data/uploads/1771331191032.png`.

Once you add `jenny-photo.png` to your project, find and replace that path in both files:

**Find:** `/mnt/user-data/uploads/1771331191032.png`
**Replace with:** `./jenny-photo.png`

### 2. Update the contact email
Search for `hello@jennifersimonds.com` and replace with your preferred contact address if different.

### 3. Link the pages to each other (optional)
In `resume-coaching-landing.html` you can add a link to the coaches page in the nav or footer.
In `coaches-landing.html` the footer already links back to the client page via `resume-coaching-landing.html`.

## Deploying to Vercel

1. Open the project folder in Cursor
2. Push to a GitHub repo
3. Import the repo in Vercel — it will detect static files automatically
4. Set the root directory and deploy

Or drag and drop the folder into vercel.com/new for instant deployment.

## Fonts

Both pages load from Google Fonts (Playfair Display + Instrument Sans). No installation needed.
