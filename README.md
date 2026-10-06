# Pillars to CEP Alignment

A whiteboard activity for Santa Ana College Guided Pathways subcommittees. Participants:

1. Choose the pillar subcommittee that most closely aligns with their work.
2. Drag 1 or 2 College Educational Plan (CEP) goals under the pillar and explain why each relates.
3. Drag the related CEP objectives onto the flow chart and give an example for each.
4. Name 3 people, positions, and/or programs whose input could contribute to the subcommittee.
5. Download their whiteboard as a PDF.

Everything runs in the browser. Answers are kept only in that browser (so a refresh doesn't lose work) and are never sent anywhere. Participants share their PDF with the facilitator.

## Put it on GitHub Pages

1. Create a new repository on GitHub (public, or private on a plan that allows Pages).
2. Upload `index.html` (and this README) to the root of the repository.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Editing the content

The pillars, goals, and objectives are listed near the top of the `<script>` section in `index.html` (`PILLARS` and `GOALS`). Edit the text there and upload the file again. The final question is the `CONTRIB_Q` line, and the objective prompt is the `EX_Q` line.

The page loads its fonts from Google Fonts and the PDF tool (jsPDF) from cdnjs, so participants need an internet connection.
