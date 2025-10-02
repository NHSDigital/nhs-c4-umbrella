# nhs-c4-umbrella
The project pulls in all the LikeC4 repos from across the organisation and deploys to a single static web site.

For more information on likeC4 [https://likec4.dev/].

To add your diagrams, add the repo as a submodule: git submodule add https://github.com/nhsuk/nhsuk.c4-diagrams.git nhsuk

Add a flikec4.config.json to your project, containing

{
  "$schema": "https://likec4.dev/schemas/config.json",
  "name": "The NHS Website",
  "title": "NHS.UK C4 Diagrams",
  "projects": [
   
  ]
}

Name is used as the Project.
