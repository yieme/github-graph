# github-graph

Graphic trends of top GitHub Repo's

## Components

- ```github-graph``` frontend adapted from firereader
- ```github-graph-data``` static data (future: updated daily)
- ```github-graph-repos``` get top repo's service
- ```github-graph-info```  get info on repo's
- ```github-graph-wayback``` get historic info on repo's
- ```github-graph-data-update``` update public data

## Firebase

- ```/who/``` array of owners: {name:gh-name, star:count, project:count }
- ```/prj/{owner}``` for owners array of projects: { name: gh-project, desc: description, star:latest-count }
- ```/stat/{owner}/{project}``` for project array of statistics: { date: yymmdd, star:count }
