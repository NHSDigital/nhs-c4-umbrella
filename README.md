# nhs-c4-umbrella
The project pulls in all the LikeC4 repos from across the organisation and deploys to a single static web site.

For more information on likeC4 [https://likec4.dev/].

To add your diagrams, add the repo as a submodule: git submodule add https://github.com/nhsuk/nhsuk.c4-diagrams.git nhsuk

Add a `likec4.config.json` file to your project, containing

``` json
{
  "$schema": "https://likec4.dev/schemas/config.json",
  "name": "Name of your project here",
  "title": "NHS.UK C4 Diagrams",
  "projects": [
   
  ]
}
```

`name` is used as the project name.
