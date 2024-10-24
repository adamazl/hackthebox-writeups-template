# HackTheBox Writeups - GitHub Pages Template

This repository contains a simple template for hosting HackTheBox writeups on GitHub Pages. It uses basic HTML and Tailwind CSS for styling and provides a clean, responsive layout for displaying writeups for ethical hacking challenges. Whether you're documenting your own security labs or sharing them with others, this template offers an easy way to host your writeups online without the need for complex setups.

## Features
- Clean and responsive design using Tailwind CSS.
- Basic HTML structure for easy customization.
- Ready-to-use navigation bar and footer.
- Template for individual writeups in regular HTML format.
  
## How to Deploy on GitHub Pages

Follow these steps to deploy your writeups on GitHub Pages:

1. **Fork or Clone the Repository**:
   - Clone this repository or fork it to your own GitHub account using:
     ```bash
     git clone https://github.com/adamazl/hackthebox-writeups-template.git
     ```

2. **Add Your Writeups**:
   - Add each writeup as an individual HTML file (e.g., `writeup1.html`) in the repository.
   - Update the `index.html` file to link to your new writeups.

3. **Push Changes to GitHub**:
   - Once you've added your content, push the changes to your GitHub repository:
     ```bash
     git add .
     git commit -m "Added writeup1"
     git push origin main
     ```

4. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click on the **Settings** tab.
   - Scroll down to the **GitHub Pages** section.
   - Under **Source**, select the `main` branch (or `master` if that's your default) and the `/ (root)` folder.
   - Click **Save**.
   - After a few minutes, your site will be live at `https://your-username.github.io/your-repository-name`.

5. **Access Your Site**:
   - Visit the URL provided by GitHub Pages to see your live site.

## Example URL
`https://adamazl.github.io/hackthebox-writeups/`
