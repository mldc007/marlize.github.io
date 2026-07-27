# student-portfolio-template
# 🌟 Build Your Own Portfolio Website

Welcome! By the end of these steps you'll have a **real website, live on the internet**, with your own web address that you can share with anyone.

You don't need to install anything or know how to code. You'll do everything in your web browser, and the whole thing takes about **30 minutes**.

Here's what you'll end up with: a personal site showing your name, a bit about you, your projects, and how to contact you.

---

## What you need

- A computer with internet
- An email address
- That's it!

---

## Part 1 — Create your GitHub account

GitHub is the free website that will store your site and put it online.

1. Go to **[github.com](https://github.com)**.
2. Click **Sign up**.
3. Enter your email, create a password, and pick a **username**.
4. ⚠️ **Choose your username carefully** — it becomes part of your website address, and it's hard to change later. Pick something clean and professional, like your name (for example `maria-lopez`).
5. Follow the prompts to verify your email. You're in!

> 💡 Write your username down. You'll need it in the next step.

---

## Part 2 — Copy the template

Your teacher has a starter template. You're going to make your own personal copy of it.

1. Open the template link your teacher gave you.
2. Click the green **Use this template** button (near the top right), then choose **Create a new repository**.
3. In the **Repository name** box, type your username followed by `.github.io`.

   **This exact format matters.** If your username is `maria-lopez`, you type:

   ```
   maria-lopez.github.io
   ```

   (Use *your* username, not maria-lopez!)
4. Make sure it's set to **Public**.
5. Click **Create repository**.

🎉 You now have your own copy of the website files!

> ❓ **Why this name?** Naming it `yourusername.github.io` gives you a clean web address like `https://yourusername.github.io`. Any other name still works but gives you a longer, messier address.

---

## Part 3 — Turn your website on

Your files exist now, but the site isn't live yet. Let's flip the switch.

1. In your new repository, click the **Settings** tab (top of the page).
2. In the left menu, click **Pages**.
3. Under **Branch**, click the dropdown that says `None` and choose **main**.
4. Click **Save**.
5. Wait about **1–2 minutes**. GitHub is building your site.

Your website is now live at:

```
https://yourusername.github.io
```

Type that into your browser to see it! (If it's not there yet, wait another minute and refresh.)

Right now it shows the placeholder text. Next you'll make it yours.

---

## Part 4 — Meet your AI helper 🤖

Before you start editing, let's turn on a helper. GitHub has a built-in AI assistant called **Copilot**. It can explain the code to you, help you word things, suggest colors, and tell you what you're doing wrong.

### Opening it

1. Look for the **Copilot icon** in the top bar of any GitHub page (it looks like a small robot face 🤖). Click it.
2. A chat panel opens on the side. Type your question and press Enter.
3. If you're asked to enable Copilot, follow the prompts — GitHub offers a **free plan** that's plenty for this project. (If you're a student, you may also qualify for the free **GitHub Student Pack**.)

> 💡 Can't find the icon? Go to **[github.com/copilot](https://github.com/copilot)** directly.

### Try it right now

Open your repository, click on `index.html`, then open Copilot and ask:

```
Explain what this file does in simple terms, like I've never written code before.
```

Read the answer. Now you know what you're about to edit. 👍

### Good things to ask it

Copy these and change the details to fit you:

- **For your tagline:**
  `Suggest 5 short taglines for a student portfolio website. I'm in 10th grade, I like robotics and drawing, and I want to sound friendly but not cheesy.`

- **For your About section:**
  `Here are some rough notes about me: [your notes]. Turn them into two short, natural-sounding paragraphs for a portfolio "About Me" section.`

- **For colors:**
  `Give me six hex color codes that look good together for a calm, professional portfolio site. Explain which one should be the background and which should be the accent.`

- **When something breaks:**
  `My website layout looks broken after I edited this. What did I do wrong? Here's my code: [paste the section you changed]`

- **When you're just curious:**
  `What does the <section> tag do? Explain it like I'm 12.`

### 📏 Rules of the road

Copilot is a helper, not a replacement for you. Four things to remember:

1. **Keep your own voice.** A portfolio is about *you*. Let the AI draft something, then rewrite it in the way you'd actually talk. If it doesn't sound like you, it's not done yet.
2. **Never paste private information.** No home address, phone number, passwords, or anything you wouldn't put on the live site anyway.
3. **Check everything.** AI sounds confident even when it's wrong. After any change it suggests, commit it and look at your live site with your own eyes.
4. **Ask "why," not just "fix it."** Asking *"why did that break?"* teaches you something. Asking *"just fix it"* teaches you nothing. You'll get faster at this if you ask for explanations.

---

## Part 5 — Make it yours ✏️

Now the fun part: replacing the placeholder text with your own.

1. Go back to your repository's main page (click the **Code** tab).
2. Click the file named **`index.html`**.
3. Click the **pencil icon** (✏️, top right of the file) to start editing.
4. Look through the file for the notes that say **`✏️ FILL IN`**. Each one tells you exactly what to type. For example:
   - Find `Your Name` and type your real name over it.
   - Find the tagline and describe yourself in one line.
   - Fill in the "About" paragraphs.
   - Rename the projects and describe what you made.
   - Update the email and links.
5. **Don't worry about the code above the big banner** — that's just the design. You only edit the parts below the line that says *"EVERYTHING BELOW THIS LINE IS YOURS TO EDIT."*

> 🤖 **Stuck on wording?** This is the moment to use Copilot. Tell it what you actually did — *"I built a birdhouse and a website for my mom's bakery"* — and ask it to help you describe those.

### Saving your changes

When you're happy with an edit:

1. Scroll to the bottom of the editing page (or click the green **Commit changes** button, top right).
2. Click **Commit changes** again in the popup.
3. Wait about a minute, then refresh your live site. Your changes appear! 🎉

> 💡 "Commit" is just GitHub's word for **save**. Every time you commit, your live website updates automatically.

---

## Part 6 — Add Your Profile Photo 📸

Want to replace the emoji with a real photo of yourself? Follow these steps:

### Step 1: Prepare your photo
- Pick a clear, professional headshot or portrait photo
- The file should be named `profile.jpg` or `profile.png`
- **Good size:** Between 500×500 pixels and 2000×2000 pixels

### Step 2: Upload the photo to your repository
1. Go to your repository's main page (click the **Code** tab).
2. Click **Add file** (green button, top right).
3. Choose **Upload files**.
4. **Drag and drop** your photo, or click **choose your files** to select it.
5. In the **"Add files here"** section at the bottom, type: `assets/` before the filename to create a folder.
   - So if your file is `profile.jpg`, it becomes `assets/profile.jpg`
6. Click **Commit changes** (green button, bottom right).

### Step 3: Done! ✨
Your photo appears automatically in the circular avatar on your site. The website is already set up to use it!

> 💡 **Tips:**
> - Make sure the photo fills the whole frame (no tiny person in a giant background).
> - The photo will be circular on the website, so a square or portrait photo works best.
> - If you want to change the photo later, just upload a new `profile.jpg` and it replaces the old one.

---

## Part 7 — Keep improving it

You can edit `index.html` as many times as you want. Each time:

**Open `index.html` → click the pencil ✏️ → change something → Commit changes → refresh your site.**

Ideas to try:
- Change the colors! Near the top of the file there's a **color palette** — six lines with color codes like `#e8a63c`. Swap them for your favorite colors ([htmlcolorcodes.com](https://htmlcolorcodes.com)).
- Add or remove projects.
- 🤖 Ask Copilot for something new: *"How do I add a button that links to my Instagram?"* or *"How do I make my name bigger on phones?"* Try it, commit it, and see what happens. You can always undo it.

---

## 🆘 Something not working?

> 🤖 **Try this first:** open Copilot and describe the problem in plain English — *"my GitHub Pages site shows a 404 and I don't know why"* — and paste any error message you see. It's often the fastest way to fix it.

**My site shows a 404 / "page not found" error.**
Give it a few minutes — new sites can take up to 5 minutes the first time. Then check that in **Settings → Pages** the branch is set to **main**. Refresh.

**I don't see my changes.**
Make sure you clicked **Commit changes**. Then wait a minute and do a hard refresh (`Ctrl` + `Shift` + `R`, or `Cmd` + `Shift` + `R` on a Mac).

**The layout looks broken after I edited.**
You probably deleted a symbol by accident — like a `<`, `>`, or `"`. Undo your last change and try again, editing only the words, not the symbols around them. Or paste the section into Copilot and ask what went wrong.

**I can't find the `index.html` file.**
Make sure you're on the **Code** tab of your repository, not Settings.

**Copilot's suggestion made things worse.**
No problem — that happens. Undo your change (or edit it back), and tell Copilot what went wrong: *"That broke my page. Here's what it looks like now."* You're the one in charge; it's just a helper.

**My photo didn't show up.**
- Check that the file is named `profile.jpg` (lowercase, with the `.jpg` extension).
- Check that it's in the `assets/` folder (not just at the root of your repository).
- Wait a minute and refresh your browser with `Ctrl` + `Shift` + `R` (or `Cmd` + `Shift` + `R` on Mac).

---

## ✅ Checklist

- [ ] Created a GitHub account with a clean username
- [ ] Copied the template into a repo named `myusername.github.io`
- [ ] Turned on GitHub Pages (Settings → Pages → main → Save)
- [ ] Confirmed my site is live at `https://myusername.github.io`
- [ ] Opened Copilot and asked it at least one question about my code
- [ ] Replaced every `✏️ FILL IN` with my own words — in my own voice
- [ ] Committed my changes and saw them appear on my live site
- [ ] Added my profile photo to the `assets/` folder

When every box is checked, you have a finished, live portfolio website that's all yours. Share the link and be proud of it! 🚀
