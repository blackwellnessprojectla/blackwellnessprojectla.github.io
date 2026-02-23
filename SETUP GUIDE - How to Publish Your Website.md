# BWP-LA Website — How to Publish & Maintain

This guide walks you through publishing your website for free on GitHub Pages. No coding required — just following the steps.

---

## STEP 1: Add Your Hero Photo

Before publishing, add your hero photo to the images folder.

1. Go to: `BWP-LA Website/assets/images/`
2. Copy your best photo from the Photo Album folder into this folder
3. Rename it exactly: `hero.JPG` (capital J, P, G — exactly as written)

**Recommended photo**: Use the `hero.JPG` file already in your Photo Album folder — it looks great as a header image.

If you want to use a different photo, open `index.html` in any text editor (like Notepad or TextEdit), find this line:
```
src="assets/images/hero.JPG"
```
And change `hero.JPG` to whatever you named your photo file.

---

## STEP 2: Create a Free GitHub Account

1. Go to **github.com**
2. Click "Sign up" and create an account (free)
3. Choose a username — something like `blackwellnessprojectla`

---

## STEP 3: Create Your Repository

A "repository" is just a folder on GitHub where your website lives.

1. After signing in, click the **+** button (top right) → "New repository"
2. Name it exactly: `blackwellnessprojectla.github.io`
   - ⚠️ Important: The name must match your GitHub username exactly
   - If your username is `bwp-la`, name the repo `bwp-la.github.io`
3. Set it to **Public**
4. Click "Create repository"

---

## STEP 4: Upload Your Files

1. In your new repository, click "uploading an existing file" (or "Add file" → "Upload files")
2. Upload **all the files** inside your `BWP-LA Website` folder:
   - `index.html`
   - `styles.css`
   - `mission.html`
   - `what-we-do.html`
   - `events.html`
   - `support.html`
   - `contact.html`
3. For the images folder, you may need to drag the entire `assets` folder in, or upload images separately into an `assets/images/` path
4. Click "Commit changes" (green button)

---

## STEP 5: Your Website is Live!

Within 1–2 minutes, your website will be live at:

```
https://[your-github-username].github.io
```

For example: `https://blackwellnessprojectla.github.io`

---

## HOW TO UPDATE YOUR WEBSITE

### To change text on any page:
1. Open the `.html` file in a text editor (Notepad on Windows, TextEdit on Mac)
2. Find the text you want to change (use Ctrl+F or Cmd+F to search)
3. Edit the text
4. Save the file
5. Go back to GitHub, click the file, click the pencil icon (edit), paste in your updated content, and click "Commit changes"

### To add a new event:
Open `events.html` and find this comment:
```
<!-- HOW TO ADD AN EVENT: Copy one of the event-full blocks below... -->
```
Copy one of the `<div class="event-full">` blocks, paste it above the others, and update the month, year, title, and description.

### To update your hero photo:
Replace `assets/images/hero.JPG` with a new photo (keep the same filename), then re-upload to GitHub.

### To add a new photo to any page:
Add an `<img>` tag like this where you want the photo to appear:
```html
<img src="assets/images/YOURPHOTONAME.jpg" alt="Description of photo" style="width:100%; border-radius:12px; margin:20px 0" />
```

---

## CUSTOM DOMAIN (Optional — when you're ready)

If you want your website to be at `blackwellnessprojectla.org` (or similar) instead of the github.io address:

1. Purchase a domain from Namecheap, Google Domains, or similar (~$12/year)
2. In your GitHub repository, go to Settings → Pages
3. Under "Custom domain," enter your domain
4. Follow GitHub's instructions to connect the domain

---

## COMMON QUESTIONS

**Q: What if my images don't show up?**
A: Make sure the image file is in the `assets/images/` folder and the filename (including capitalization) matches exactly what's in the HTML file.

**Q: Can I have a private website just for my team?**
A: GitHub Pages requires the repository to be public for free hosting. If you want a password-protected internal site, consider Notion (see your Notion Workspace Guide) or a free tool like Glitch.com.

**Q: How do I add a Donate button that actually works?**
A: Set up a free account at Zeffy.com (no fees for nonprofits), PayPal Giving Fund, or Cash App. Then replace the donate button link in `support.html` with your donation page link.

**Q: Do I need to know coding?**
A: Not really! The files are designed so you can change text without understanding code. Just be careful to only change text between `>` and `<` symbols — don't delete or change the surrounding tags.

---

## YOUR WEBSITE FILES AT A GLANCE

| File | What it contains |
|------|-----------------|
| `index.html` | Your homepage — the first thing visitors see |
| `mission.html` | Who you are, your values, and 2024 impact |
| `what-we-do.html` | Your 4 programs in detail |
| `events.html` | Upcoming and past events |
| `support.html` | Volunteer, donate, partner, sponsor |
| `contact.html` | Contact page with FAQ |
| `styles.css` | All the visual design (colors, fonts, layout) |
| `assets/images/` | Folder for all your photos |

---

*Made for Black Wellness Project LA — 2026*
