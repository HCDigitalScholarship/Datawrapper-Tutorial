# Haverford College Libraries Digital Scholarship  
## Datawrapper Tutorial  

### About Datawrapper  

Datawrapper is a web-based tool for creating interactive data visualizations in a variety of formats. It supports commonly used chart types such as bar, column, line, and pie charts, as well as scatter plots and choropleth maps. It is one of the most intuitive and accessible data visualization tools for beginners, with a robust library of tutorials and step-by-step instructions.

Datawrapper also includes several built-in features to improve accessibility, such as the ability to add alt text for images and tools for selecting high-contrast, colorblindness-safe palettes. It can even run color blindness tests on your completed visualizations.

---

### How to Use Datawrapper  

#### 1. Prepare your data  

Before uploading data, it must be cleaned and structured in a way that the software can interpret. This step often takes the most time regardless of the visualization tool. We recommend using Excel or Google Sheets for basic data cleaning. For more advanced options, see the [TriCo DS Committee’s Tidy(ish) Data tutorial](#).

Datawrapper also provides a detailed tutorial walking through the process of preparing your data for upload using a sample data set from the World Bank (e.g., urban population data).

**Tips for cleaning your data:**
- Make a duplicate of your data file and rename it to indicate that it has been edited. Naming conventions like `raw_data`, `data_original`, and `data_edited` can help.
- Remove extra rows above the header. These often appear in downloaded Excel files and will interfere with chart generation.
- Unmerge cells in any double-row headers.  
  - *In Excel:* Select the cells → “Home” tab → “Merge & Center” → “Unmerge Cells.”  
  - *In Google Sheets:* Select the cells → “Format” → “Merge cells” → “Unmerge.”
- Delete metrics like €, $, %, etc., from your data cells. You can add them back in Datawrapper during chart creation.
- Rename your column headers using clear, descriptive titles. Avoid abbreviations that won’t be meaningful to outside readers.

> **Note:** You can skip this step and experiment using one of Datawrapper’s sample datasets (e.g., Global CO₂ emissions) while you learn the tool.

---

#### 2. Create an account  
- Visit [https://www.datawrapper.de](https://www.datawrapper.de)  
- Click “Sign up” and create a free account using your email or Google login.

---

#### 3. Upload your data to Datawrapper  
Upload your data using one of the following options:  
- Paste your data directly  
- Upload a `.CSV` or `.XLSX` file  
- Connect to Google Sheets  
- Link to an external data source

---

#### 4. Check and describe your data  
Make sure that Datawrapper is interpreting your data correctly. Datawrapper automatically identifies data types:  
- **Blue** = numbers  
- **Green** = dates  
- **Black** = text  
- **Red** = errors (e.g., empty cells or unrecognized formats)

---

#### 5. Visualize your data  
Select the type of chart you’d like to create. Datawrapper will display previews of each type so you can get a sense of what the final output will look like.

---

#### 6. Refine your data  
From this window, you can:
- Limit your visualization to custom ranges  
- Adjust the size of the graph, its color, and labels

---

#### 7. Annotate your data  
From this window, you can:
- Add a custom title, description, and notes  
- Add alt text  
- Link out to your data source

---

#### 8. Adjust your layout  
From this window, you can:
- Customize the layout of your visualization  
- Adjust the pixel size  
- Run various color blindness and accessibility tests

---

#### 9. Share your visualization  

There are a few ways to share your visualization:

**Static exports:**  
- If you’d like to export a static copy of your visualization, you do not need to publish it. Simply select export as a PNG file.

**Embeds and published links:**  
- If you’d like to embed your completed visualization on a website or social media platform, you’ll need to publish it first. This option provides:
  - Direct links to your published visualization  
  - Embed codes (`<iframe>`) that can be embedded onto a website  

> For more info, see Datawrapper’s [tutorial on how to share and embed visualizations](https://blog.datawrapper.de/embedding/).

---

### General Accessibility Guidelines for Data Visualization  

While there are no universal standards, the following general guidelines provide a useful framework:

- Add a thorough description in HTML to convey the meaning of the visualization  
- Supplement alt text with a link to the raw data  

**Alt text writing formula (Amy Cesal):**  
> \[chart type\] of \[data type\] where \[reason for including chart\] with a \[link to data source\]

**How to add alt text in HTML:**  
- Use: `<img alt="your description">`  
- When possible, include a long description using `longdesc="your long description"`  

---

### Accessibility Resources for Datawrapper  
- Lisa Muth, [A detailed guide to colors in data vis style guides](https://blog.datawrapper.de/colorguides/)
- Lisa Muth, [It’s time for a more sophisticated color contrast check for data visualizations](https://blog.datawrapper.de/color-contrast/)
- [Accessibility in Datawrapper](https://blog.datawrapper.de/accessibility/)

---

### Related Data Visualization Resources  
- [Writing about data sets](https://docs.google.com/document/d/1B534SiW1MH888NUnSRJeEWVXZmWAbQ7g-Uk-eXewM6E/edit?tab=t.0)  
- [Working with Data Toolkit](https://docs.google.com/document/d/1Uz0KFp7KJIofC6NGq4j3rvyoLVUk2ly_6lEnF7x1l2E/edit?tab=t.0)  
- [Datawrapper Tutorial](https://docs.google.com/document/d/1Sy5in9etjkSHbh7SusszphfYbHAfNblKjEQKeI8Dw98/edit?tab=t.0) (Google docs version of this tutorial)


