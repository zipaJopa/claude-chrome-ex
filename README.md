# claude-chrome-ex
Claude 3.5 Chrome Extension Prompt

### Prompt
Hello! I want to create a chrome extension that uses the load unpacked feature in extension to create a custom chrome extension.

1. When the USER runs the extension, and executes a brower action by clicking on the extension icon. The extension will screenshot the current screen. Save the screenshot to a folder named img in the cwd, then process the image with gpt4-o API. USE the DOCS = (openai.txt) 

2. gpt-4o should identify what is the url of the webpage + a title or a small note on what is on the screen

3. The exentension should then create a small pop-up that show the gather info from the screen, and save the url with a title or the notes to a file.

4. This file can be displayed as a pop-up from the extension menu so the USER can look at the saved notes etc.

Can you help me get started on building this AI Agent step-by-step for me please?
