# Satyajit Sahoo | Portfolio

Static portfolio site (plain HTML, CSS and JavaScript). No build step.

## Put it on GitHub Pages

1. Create a new repository on GitHub. For a root URL, name it `YOUR-USERNAME.github.io`.
2. Unzip this folder on your computer.
3. In the repository click **Add file > Upload files**, then drag in EVERYTHING inside the unzipped folder
   (`index.html`, `.nojekyll`, the `assets` folder). Dragging the `assets` folder keeps its sub-folders.
   Click **Commit changes**.
4. Go to **Settings > Pages**. Under **Build and deployment** choose **Deploy from a branch**,
   pick branch `main` and folder `/ (root)`, then **Save**.
5. Wait a minute or two. Your site is live at `https://YOUR-USERNAME.github.io`.

Tip: if the `.nojekyll` file does not show up in your file picker (names starting with a dot can be hidden),
it is optional. The site works without it.

## Your photo

`photo.jpg` (800x1000, 4:5 portrait) is already included next to `index.html`.
To change it, replace that file and keep the name `photo.jpg`. Use a 4:5 portrait image for the best fit.

## Company logos

The four employer logos are already included in `assets/logos/companies/`
(`jindal-stainless.png`, `ey.png`, `merino-consulting.png`, `innomatics.png`).
To change one, replace the file and keep the same name.

## Folder layout

```
index.html
photo.jpg
assets/
  favicon.svg
  logos/
    tech/        languages, engines and tools (Python, Spark, Databricks, Delta Lake, SAP, Power BI ...)
    azure/       Azure services (Data Factory, IoT Hub, Event Hubs, Key Vault, Monitor ...)
    fabric/      Microsoft Fabric items (Lakehouse, Eventhouse, Event Streams, Activator ...)
    concepts/    neutral icons for ideas (Medallion, ETL/ELT, CI/CD ...)
    companies/   employer logos (PNG)
```

See `assets/logos/CREDITS.md` for icon sources.
