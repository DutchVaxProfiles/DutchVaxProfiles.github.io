# Dutch Vaccination Profiles

Website for the project "Understanding heterogeneity in vaccination decisions":
https://dutchvaxprofiles.github.io/

## Editing content

Most homepage text is in `_data/` as YAML files:

- `_data/site.yml`: introduction, method diagram, map text, and ZonMw grant details
- `_data/survey_profiles.yml`: 12 profile descriptions, profile cards, figure captions, and Table 2 values
- `_data/map_groups.yml`: Study 2 mapped profile group descriptions
- `_data/lessons.yml`: practitioner and researcher lessons
- `_data/team.yml`: team members, links, roles, and photos
- `_data/outputs.yml`: papers, preregistrations, map explorer, and code/material links

The homepage itself (`index.md`) only lists the page sections. The reusable HTML
blocks live in `_includes/`.
