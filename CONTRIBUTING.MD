# Contribution

Welcome! This guide will walk you through the steps to <mark style="color:blue;">**contribute**</mark> to our game servers' wiki on <mark style="color:blue;">**GitHub**</mark>.

## 📋 <mark style="color:blue;">Prerequisites</mark>

* Create a GitHub account: [Sign up for GitHub](https://github.com/join).
* Install Git on your computer: [Download Git](https://git-scm.com/downloads).
* Choose a simple and user-friendly editor like [Visual Studio Code](https://code.visualstudio.com/).

## ⚙️ Install and Configure Git

After installation, open your terminal and configure your name and email (the ones used for GitHub):

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

## 🚀 <mark style="color:blue;">Making a Contribution</mark>

### <mark style="color:blue;">1. Fork the Repository</mark>

* Go to the relevant wiki repository on GitHub.
* Click on the <mark style="color:blue;">**Fork**</mark> button in the top right to create a copy of the repository in your account.

### <mark style="color:blue;">2. Clone Your Fork Locally</mark>

Copy the link of your fork and run the following command in your terminal:

```bash
git clone https://github.com/YOUR-USERNAME/wiki-repository.git
cd wiki-repository
```

### <mark style="color:blue;">3. Create a New Branch</mark>

Create a branch for each topic you work on to keep contributions organized:

```bash
git checkout -b branch-name
```

Example:

```bash
git checkout -b add-new-guide
```

### <mark style="color:blue;">4. Edit the Wiki</mark>

* Use Visual Studio Code to edit markdown (.md) files.
* You can also create new files, for example, `how-to-play.md`.

Example of a simple markdown structure:

```markdown
# Main Title

## Subtitle

Your content here...

- Bullet point 1
- Bullet point 2

[Useful link](http://example.com)
```

### <mark style="color:blue;">5. Add Your Changes to Git</mark>

In your terminal, add and commit your changes:

```bash
git add .
git commit -m "Added a new guide on gameplay mechanics"
```

### <mark style="color:blue;">6. Push Your Contribution</mark>

Push your changes to GitHub:

```bash
git push origin branch-name
```

### <mark style="color:blue;">7. Open a Pull Request (PR)</mark>

* Go back to your fork on GitHub.
* Click on <mark style="color:blue;">**Compare & pull request**</mark>.
* Clearly describe your contribution and click <mark style="color:blue;">**Create pull request**</mark>.

## 💡 <mark style="color:blue;">Best Practices and Tips</mark>

* Be clear and concise in your explanations.
* Check spelling and grammar.
* Properly structure markdown pages.
* Use markdown previews in Visual Studio Code (Ctrl + Shift + V) before submitting.

## 🛠️ <mark style="color:blue;">Need Help?</mark>

Feel free to open an [issue](https://github.com/YOUR-REPOSITORY/issues) on GitHub if you need assistance or have questions.

Thank you for your contribution! ✨

