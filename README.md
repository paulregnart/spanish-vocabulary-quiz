# Spanish Vocabulary Quiz 🇪🇸

An interactive Spanish vocabulary quiz that tests users from easy to intermediate levels.

## Features

- ✅ 20 progressive questions (easy → intermediate)
- ✅ Multiple choice format (no typing required)
- ✅ Instant feedback on answers
- ✅ Score tracking
- ✅ Beautiful, responsive design
- ✅ Mobile-friendly

## How to Deploy to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. **Create a new GitHub repository** (or use an existing one)

2. **Initialize git and push the code:**
   ```bash
   cd spanish_club
   git init
   git add .
   git commit -m "Add Spanish vocabulary quiz"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **main** branch
   - Click **Save**
   - Your quiz will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Option 2: Add to Existing Repository

If you want to add this as a subfolder to an existing repo:

1. Copy the `spanish_club` folder to your repository
2. Commit and push the changes
3. Access it at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/spanish_club/`

## Local Testing

Simply open `index.html` in any web browser:

```bash
open index.html
```

Or use a local server:
```bash
# Python 3
python3 -m http.server 8000

# Then visit: http://localhost:8000
```

## Quiz Structure

- **Questions 1-12:** Easy level (basic vocabulary like greetings, colors, numbers)
- **Questions 13-20:** Intermediate level (more complex vocabulary and phrases)

## Customization

To add or modify questions, edit the `questions` array in the JavaScript section of `index.html`:

```javascript
const questions = [
    {
        question: "Your question here?",
        options: ["Option 1", "Option 2", "Option 3", "Option 4"],
        correct: 0, // Index of correct answer (0-3)
        difficulty: "easy" // or "intermediate"
    },
    // Add more questions...
];
```

## Technologies Used

- Pure HTML5
- CSS3 (with modern gradients and animations)
- Vanilla JavaScript (no dependencies!)

## License

Free to use and modify for educational purposes.

---

**Built for Spanish learners** 📚 **Ready to deploy** 🚀
