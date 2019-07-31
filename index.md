# [LIFE EXPECTANCY (CS 498 Final Project)](https://bin0212.github.io/Narrative_Visualization/src/page1)

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Bin0212/Narrative_Visualization/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Bin0212/Narrative_Visualization/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

#################
## Messaging
In this narrative visualization, **life expectancies** in the selected 10 countries are the main focus. The messages I want to convey are how the life expectancies are different among countries, between genders, and how it is related to the GDP per Capita in these countries. 

## Narrative Structure
My narrative visualization follows the **interactive slideshow** structure. There is an author directed path through the visualization of life expectancy differences and its relationship with GDP per Capita. In this path, viewers can drill down into more details in each slide. For example, in the slide discussing about life expectancy differences, viewers can explore male life expectancy differences between 2000 and 2012, female life expectancy between 2000 and 2012, and life expactancy by gender in 2012 by clicking different slide numbers (i.e. scene 2-1. scene 2-2. and scene 2-3). In the slide discussing life expectancy relationship with GDP per Capita, viewers can also switch the relationship between male and female by clicking different slide numbers (i.e. scene 3-1, and scene 3-2). If viewers are not interested in the details, they can continue by clicking the "next" button in each page.  

## Visual Structure
For all the scenes in this narrative visualization, same background color, chart background color, scene layout (i.e. one chart followed by some descriptions), chart and text centering are used for visualization consistency. Scene titles, axises, and legends are provided in all scenes to help viewers understand the data better. Slide numbers as well as "back" and "next" buttons are also provided to help viewers navigate between scenes.

In the first scene discussing about life expectancy differences, there are three sub-scenes. In scene 2-1 and scene 2-2, grouped line charts are rendered. Same color sets are used in lines and legends to help viewer transition between scenes and be aware that the countries are the same between scenes. Annotations with labels and circles are rendered together with the charts to urge the viewer to focus on the important parts of the data in each scene. In scene 2-3. a grouped bar chart is rendered along with annotations to help viewers to focus. 

In the second scene discussing life expectancy relationship with GDP per Capita, there are two sub-scenes. In scene 3-1 and scene 3-2, grouped scatter plots are rendered. Again, same color sets are used in points and legends to help viewer transition between scenes. Annotations with labels and arrows are also provided to help view to focus on those important part of the charts.

## Scenes
There are four main scenes including the opening and closing scenes in my narratuve visualization. They all share the same scene template. The opening and closing scenes serve as the starting and ending point for the visualization part. The second scene discussing about life expectancy differences have three sub-scenes for viewers to explore. The third scene discussing life expectancy relationship with GDP per Capita have two sub-scenes for viewers to explore. The second scene is ordered before the third scene because the second one is a more general analysis over the life expentancy itself while the third one digs more into the detailed relationships. It is more natural to provide an overview of the analysis before starting the details.  

## Annotations
I used the d3-annotation library made by Susie Lu for annotations which follows a template (color, font, line width, etc.) in different types of annotations. Important findings (e.g. life expectancy increases as GDP per Capita increases) to convey the messaging are pointed out in charts by annotations. By helping viewers to focus on important trends, annotations support the messaging. Annotations change within one major scene but do not change in any sub-scenes. Because in major scenes, there are multiple findings I want to highlight among different sub-scenes which annotation changes are needed while observations in any sub-scenes can be shown directly without any change.

## Parameters
The slide number (e.g. scene 2-1, scene 2-2, etc) is the parameter that control the state. The states of the narrative visualization include scene 2-1, scene 2-2, scene 2-3, scene 3-1. and scene 3-2. The state and scene are defined by the numbers after the word "scene". For example, parameter "scene 3-1" indicates it is the third scene and first state. Current slide number is in black color and other available slide numebrs are in gray color. 

## Triggers
The slide number, "back" buttom and "next" buttom are the triggers that connect user actions to changes of the narrative visualization states. Current slide number is in black color and other available slide number triggers are in gray color to inform viewers that they are able to switch between sub-scenes. When available, "back" buttom and "next" buttom are shown at the bottom of the page as red rectangels and white text to inform viewers that they are able to move backward or foward between scenes. 
