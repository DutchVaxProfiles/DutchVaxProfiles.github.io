# Dutch Vaccination Profiles

Website for the project "Understanding heterogeneity in vaccination decisions":
https://dutchvaxprofiles.github.io/

## Editing content

Most homepage text is in `_data/` as YAML files:

- `_data/site.yml`: introduction, method diagram, map text, and ZonMw grant details
- `_data/survey_profiles.yml`: 12 vaccination decision profile descriptions, profile cards, figure captions, and Table 2 values
- `_data/map_groups.yml`: Study 2 mapped profile group descriptions
- `_data/lessons.yml`: practitioner and researcher lessons
- `_data/team.yml`: team members, links, roles, and photos
- `_data/outputs.yml`: papers, preregistrations, map explorer, and code/material links

The homepage itself (`index.md`) only lists the page sections. The reusable HTML
blocks live in `_includes/`.

## Editing `_data/site.yml`

Open `_data/site.yml` in a text editor. Most edits only require changing the
words inside quotation marks.

- `subtitle`: the small line under the site name in the navigation bar
- `hero`: the introduction text, top buttons, and short ZonMw funding note
- `method`: the "Method in brief" text, four method boxes, and green buttons
- `map`: the Study 2 map title, explanation, note, and iframe link
- `funder`: the ZonMw grant details shown in the funder block and footer
- `partners`: the partner/funder logo files, links, and alt text

Try not to change the labels on the left side of each line, such as `title:`,
`text:`, `href:`, or `logo:`. Change the text after the colon instead. Keep the
indentation as it is; YAML uses spaces to understand which lines belong
together.
