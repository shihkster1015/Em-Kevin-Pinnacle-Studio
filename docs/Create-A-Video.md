---
layout: default
title: Create A Movie
nav_order: 3
---

# Task One: Create A Video 
{: .no_toc } 
In this section you will be able to create your first movie by using the different features in Pinnacle. Your movie will 
be made up of imported, edited, and enhanced audio and visual files. At the end, you can export your movie. This section will guide you through the importing, editing and exporting basics. 

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## Introduction 

## Task 1.1 Create A Movie

1.  Open Pinnacle and select [File] > [New] > [Movie].  
This will guide you to the main page where you can visualize your new movie. If you are unfamiliar
with the Pinnacle Studio layout and conventions, review them [here.](/index.md) 

2.  Create a new project bin by selecting the ![BOX](images/box_icon.png) icon.  
This project bin will help organize your files. 

3.  Type the name for your new project and click [Okay].  
This project is now ready to import the video and audio you want to use for your movie. 

4.  To import your media select the “Quick Import” icon.  

![Quick Imports](images/importFiles.png)

5.	Now your files are ready to use, drag your video to the first A/V Track at the beginning of the track.  
    

## Task 1.2 Trim A File

There are **two** ways to trim a audio or video file once it has been placed on the track. 


Here we're setting up the UI Components landing page that is available at `/docs/ui-components`, which has children and is ordered second in the main nav.

### Menu Adjust
{: .text-gamma }
1. To ajust the duration of a audio/video clip, simply right click the media on the track to reveal an options menu. 

2. Select [Duration]

3. Adjust to desired length 

#### Track Adjust 
{: .text-gamma }

1. To adjust the duration of a clip directly on the track, drag the edges of the clip file directly

IMAGE HERE 

## Menu Adjust 

Sometimes you will want to create a page with many children (a section). First, it is recommended that you keep pages that are related in a directory together... For example, in these docs, we keep all of the written documentation in the `./docs` directory and each of the sections in subdirectories like `./docs/ui-components` and `./docs/utilities`. This gives us an organization like:


On the parent pages, add this YAML front matter parameter:
-  `has_children: true` (tells us that this is a parent page)

#### Example
{: .no_toc }

```yaml
---
layout: default
title: UI Components
nav_order: 2
has_children: true
---
```

Here we're setting up the UI Components landing page that is available at `/docs/ui-components`, which has children and is ordered second in the main nav.

### Adgust One 
{: .text-gamma }

On child pages, simply set the `parent:` YAML front matter to whatever the parent's page title is and set a nav order (this number is now scoped within the section).

#### Example
{: .no_toc }

```yaml
---
layout: default
title: Buttons
parent: UI Components
nav_order: 2
---
```

The Buttons page appears as a child of UI Components and appears second in the UI Components section.

### AAdjust Two 

By default, all pages with children will automatically append a Table of Contents which lists the child pages after the parent page's content. To disable this auto Table of Contents, set `has_toc: false` in the parent page's YAML front matter.

#### Example
{: .no_toc }

```yaml
---
layout: default
title: UI Components
nav_order: 2
has_children: true
has_toc: false
---
```


## Task 1.3 Delete A File 

1. Deleting 

---

## Task 1.4 Export and Share Your Movie

---
