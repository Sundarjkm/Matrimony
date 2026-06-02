EC Matrimony — site template
=============================

Folder layout:
    ECMatrimony.html      ← open this in any browser
    photos/
        photo1.jpg        ← your candidate 1
        photo2.jpg        ← your candidate 2
        ...

How to fill in candidates:
1. Drop your portrait JPGs into the photos/ folder, named photo1.jpg ...
2. Open ECMatrimony.html in a text editor (Notepad, VS Code, anything).
3. Find the line that starts:    const profiles = [
4. Edit each block:
     id, name, age, height, type (bride/groom), nri (true/false),
     edu, job, company, income, district, rasi, star, caste, sub, lang,
     avatar (emoji fallback), avClass (av-1..av-6 background colour), desc.
5. Save the file and refresh the page in your browser.

To add more than 10 candidates: copy any block in the array, paste it below,
change the id to EC0011 / EC0012 / ... and the photo path to photo11.jpg etc.
