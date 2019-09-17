- title : Efforts-Tracking
- description : Tracking of the efforts
- author : Marko Apfel
- theme : night
- transition : default

***
- id: NewTools

### New tools

- FsReveal
- DocFX
- Slack

***

## Introduced FsReveal

- to provide fancy presentations
- neutralized the tWiki presentation from the past
- started to host that version at  
  [http://mapfel.github.io/wiki-presentation](http://mapfel.github.io/wiki-presentation)
- which is the same as  
  [http://blog.apfel.space/wiki-presentation/](http://blog.apfel.space/wiki-presentation/)
- it can be used as the template for company specific presentations
- redirecting of the sub domain was made in the past  
  → have to figure out how 

***
- id : DocFx.2019-09

## DocFX

- Microsoft developed documentation tool
- open source successor of SHFB
- allows easily mix code documentation with additional content  
  (e.g. XML Comments, API documentation (OAS), tutorials,...)
- great support for .NET Core projects

---

### Mix XML Comment with Wiki

- currently the XML Comments are merged together with Wiki content
- it is done inside the `docfx.json` file

![](./images/2019-09.Documentation.03.png)


### Host the DocFX output via GitHub Pages

- used the `apm1grb` account to host the **DocFX** output 
- you can find here: [https://apm1grb.github.io/](https://apm1grb.github.io/)
- technically the content of the `_site` folder was included in an own repo

![](./images/2019-09.Documentation.02.png)


### Use Git Submodules to link source code together with Wiki content and DocFX pimped source code XML Comments

- realized as sub modules
- checkout of the Wiki repo below `doc` folder 
- checkout of "`_site`-repo" below `doc` folder 
- needs awareness about workflows  
  (when the pull Wiki and to push "`_site`-repo")

---

### Provide complete XML Comments

- completely documented all public and protected interfaces
- re-introduced GhostDoc in toolset

![](./images/2019-09.Documentation.01.png)

***

## Slack

- cloud-based set of team collaboration software tools and online services
- Slack = "Searchable Log of All Conversation and Knowledge."
- Most famous platform

---

- created a workspace, prepared some channels
- invited SM, FM

![](./images/2019-09.Tools.Slack.01.png)

---

### Contact with colleagues in AC

- alternative platform: **Mattermost**
- on-prem possible & open source
- not really adopted there

***
- id : Wiki.2019-09

## BVMS UI Automation Wiki

- started to create a project Wiki
- based on Azure DevOps (Git & Markdown)
- capture knowledge about the BVMS UI Automation
- provide SMM, SDS,...

---

### Start with some basic knowledge

![](./images/2019-09.Wiki.01.png)

***
- id : EvaluationUiAutomation.2019-07

## Evaluate UI Automation Frameworks

