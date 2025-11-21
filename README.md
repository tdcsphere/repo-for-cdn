# 🚀 Hosting Your Assets with JSDELIVR (Completely Free CDN)

This guide provides simple steps to serve your repository files as a free Content Delivery Network (CDN) using JSDELIVR.

---

## Steps to Use Free CDN from JSDELIVR

Follow these steps to generate and use your JSDELIVR CDN link:

1.  ### **Upload Your Files**
    * Navigate to your repository.
    * Use the **`+ Add file`** dropdown and select **`Upload files`** to add the content you wish to serve via the CDN (e.g., CSS, JS, images).

2.  ### **Access the File's Page**
    * Once uploaded, click on the specific file you want to link to. This will take you to its dedicated viewing page within the repository.

3.  ### **Obtain the GitHub URL**
    * Copy the complete URL displayed in your browser's address bar. This is the direct path to the file on GitHub.

4.  ### **Generate the CDN Link**
    * Visit the official JSDELIVR GitHub tool: **[jsdelivr.com/github](https://www.jsdelivr.com/github)**.
    * Paste the copied GitHub file URL into the input field on the JSDELIVR page.

5.  ### **Implement the CDN Link**
    * Copy the generated JSDELIVR URL (it will typically start with `cdn.jsdelivr.net/gh/...`).
    * Use this link in your web projects to reference your CDN assets.

---

## 💡 Quick Tip: Manual Link Generation

You can also construct the JSDELIVR link manually using the following format:

`https://cdn.jsdelivr.net/gh/USERNAME/REPO_NAME@BRANCH_NAME/PATH/TO/FILE`

* **Example:** If your file is at `tdcsphere/repo-for-cdn/main/assets/style.css`, the CDN link would be:
    `https://cdn.jsdelivr.net/gh/tdcsphere/repo-for-cdn@main/assets/style.css`
