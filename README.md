A centralized repository for hosting public-facing static assets for projects managed by the **Georgia-Dev** team.

---

## 🎯 Purpose

The primary goal of this repository is to host static assets (images, logos, icons, etc.) that need to be referenced by external services or embedded in documentation where the source code repository is **internal** or **private**.

By hosting assets here, we ensure that services like Microsoft Teams, as well as public-facing documentation, can reliably access and render images without requiring authentication or access to our internal source code repositories.

## 🛠️ Usage

### How to Add a New Asset

1. **Clone the repository** to your local machine.

2. **Create a descriptive folder** for the asset if one doesn't already exist (e.g., `logos/`, `bot-icons/`).

3. **Add the asset** to the appropriate folder. Please use clear, descriptive filenames (e.g., `github-teams-bot-icon.png`).

4. **Commit and push** the new asset to the `main` branch.

### How to Get an Asset URL

To use an asset from this repository, you must use its **raw file URL**.

1. Navigate to the asset file on GitHub.com.

2. Click the **"Download"** button or right-click it and select **"Copy Link Address"**.

3. The resulting URL will be the raw content URL, which will look something like this:
   `https://raw.githubusercontent.com/KofileDev/georgia-public-assets/main/bot-icons/bot-icon.png`

## 🖼️ Example

To use an image from this repository in another project's `README.md` file, use the following Markdown syntax with the raw URL obtained above:

```markdown
![Bot Icon](https://raw.githubusercontent.com/KofileDev/georgia-public-assets/main/bot-icons/bot-icon.png)