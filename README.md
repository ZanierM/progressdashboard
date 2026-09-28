# Year 12 Progress Dashboard

Turns each data drop's MIS marksheet export into a dashboard for the Year 12 team. It covers the three indicators (Attitude to Learning, Response to Feedback, Quality of Work, graded EX, GD or BE) and working-at grades against target grades.

## Privacy: read this first

- The page runs entirely in your browser. When you load an export, the file is read on your computer. **Nothing is uploaded, sent or stored online**, even when the page itself is hosted on GitHub.
- Your data is kept in one **workbook file** that you download with **Save workbook** and open again next time. Keep it somewhere secure, such as your school OneDrive, not on a USB stick or personal device.
- Closing the tab clears everything from the page. (There's an option in Settings to remember the data in the browser. Only use it on your own staff laptop.)
- The page itself contains no student data, so it's safe to host publicly. **Never upload exports or workbook files to the GitHub repository.**
- It's worth telling the DPO how you're using it. Because the data never leaves your device, it's the same as opening the export in Excel.

## What it shows

| View | What it's for |
|---|---|
| **Overview** | Headline figures, indicator breakdown against the last drop, a tutor-group comparison table, "All EX" students and the most improved. |
| **Students of concern** | Everyone who meets a concern rule, with the reasons. Filter by tutor group, then print, copy for email or download as CSV for sixth form meetings. |
| **Tutor groups** | One page per form, showing every student's subjects, indicators and grade against target. Print one form, or all seven with a page break between each, for tutors. |
| **Subjects** | Every subject side by side, then a student list for each one, to print for Heads of Department. |
| **Student profile** | One student across all subjects, with their history over every data drop. Useful for parent meetings. |

**Concern rules** (change them in Settings): 2+ BE grades; 2+ subjects 1 grade or more below target; any subject 2+ grades below target; 3+ indicator grades down since the last drop; working grade down in 2+ subjects.

The dashboard uses the school purple: dark purple for EX, light purple for GD and orange for BE. It is not a RAG rating.

## Each data drop (about 2 minutes)

1. Export the marksheet from the MIS as CSV or Excel. It needs student names (or surname and forename), tutor group, and the indicator and grade columns. An admission number or UPN is optional, but it helps link students across drops.
2. Open the dashboard, then **Open workbook** (your saved file).
3. Click **+ Add data drop** and choose the export. The dashboard matches the columns automatically. Check the subject names and measures, name the drop (e.g. "Assessment Report 1") and click **Add**.
4. Click **Save workbook** and replace the old file on OneDrive.

Both layouts of export work:
- **one row per student**, with columns like `Biology - Attitude to Learning`, `Biology - Working At Grade`, or
- **one row per student per subject**, with a `Subject` column.

A level grades (A* to U, with + or −), BTEC grades (D*, D, M, P) and numbers are all understood. Keep subject names the same between drops so that trends line up. The check step warns you if a subject name is new.

To see how it works first, click **Try the sample data** (174 made-up students). The `samples` folder shows both layouts.

## Setup

1. Create a GitHub repository (for example `y12-progress`) and upload `index.html`, `README.md` and the `samples` folder.
2. **Settings → Pages**, choose `main` and `/ (root)`, then save.

You can also run it without hosting: download the folder and double-click `index.html`. Everything works except the sample-data button, which needs the page to be hosted.

Tutor groups and tutors are preset (12A EOL, 12C EMH, 12D JZU/RH, 12L HHN, 12P GAI, 12R MPT, 12W NYE). You can change them in Settings.
