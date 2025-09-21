# Adding Screenshot to GitHub Repository Front Page

## Quick Steps:

### 1. Upload Your Screenshot
1. Go to: https://github.com/beingarjun/resume-to-cover-letter
2. Navigate to the `screenshots/` folder
3. Click **"Add file"** → **"Upload files"**
4. Upload your screenshot as `app-interface.png`
5. Commit with message: "Add app interface screenshot for demo"

### 2. Verify Display
Once uploaded, your screenshot will automatically appear on the main README because it's already referenced as:
```markdown
![App Interface](screenshots/app-interface.png)
```

## Alternative: Save Screenshot Locally

If you want to save the screenshot locally first:

1. **Take Screenshot**: 
   - Windows: `Win + Shift + S` (Snipping Tool)
   - Or right-click browser → "Save image as..."

2. **Save to Folder**:
   ```
   Resume to Cover Letter/
   └── screenshots/
       └── app-interface.png  ← Save here
   ```

3. **Commit and Push**:
   ```bash
   git add screenshots/app-interface.png
   git commit -m "Add app interface screenshot for demo"
   git push
   ```

## Expected Result:

Your GitHub repository front page will show:

```
# Resume to Cover Letter Generator

A free, locally-running Streamlit app that converts your resume into tailored cover letters using open-source AI models.

## Live Demo

[YOUR SCREENSHOT WILL APPEAR HERE]

*Professional interface showing Hugging Face API integration, smart upload guidance, and comprehensive feature set*
```

This will make your repository immediately impressive to visitors and potential investors!

## Pro Tips:

- **High Quality**: Ensure screenshot is clear and readable
- **Full Interface**: Show the complete app interface
- **Professional**: Clean browser, no personal info visible
- **Optimal Size**: GitHub displays images well up to 1920px wide