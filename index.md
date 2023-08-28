# Design concept

## Abstract

The main idea of this prototype is to provide a comprehensive sketch for the app, enabling developers to understand the required functionality that the software must encompass. It also illustrates the intended user interface design, including navigation flows through the app and key features. Additionally, it outlines how information should be presented and highlights the technical capabilities of the software.


## Prototype


### Welcome 

The welcome page of the prototype features a centrally positioned logo. In the background, a painting is displayed with a semi-transparent pattern overlay. The corners of the page are gently rounded, intended for use in the subsequent page's animations. This design was implemented to convey a visual representation of the software's purpose and concept.


### Take a picture 

The page consist of header with logo and menu button. The main part represents simulation of the user expierence in the musueum and take a picture button. After Taping on the take a picure button , it made a simulation of photoaparat flash after gives a selection of picture which was analyed by the software. 
After clicking on one of them it will redirect to the focus picture part.
 

### Focus picture part

The page includes a header with a new option allowing the user to return to the stage where they can take a photo. The middle section features the selected picture accompanied by an info frame box.

The Info Box comprises a Title, representing the picture's name in a 30px font size. Adjacent, in a slightly smaller 24px font size, are details such as the artist's name, year of production, and painting technique. These details are presented using a two-color gradient with a 1.5px stroke in the primary color.

The lower half of the page showcases a picture selected from a similar artist. This inclusion encourages the user to scroll down, leading them to discover similar pictures through the 'categories.'

By dragging the page downward, a scrolling animation is triggered, transitioning the user to the artist category(it was choosen as an initial cathegory).


### Categories

There are four categories by which you can search for similar pictures. Each category consists of five headers with similar functionality as before (a back button that directs you to the focused picture page, a logo that navigates to the beginning of the app, and a menu button). The picture is prominently displayed in full-screen mode.

The info frame box and Categories bar are located in the footer section of the page. The Categories bar has four buttons: 'Same Color', 'Artist', 'Same Epoch', and 'Objects'.

After a delay of 800 milliseconds, orange dots appear on the picture, marking the objects in the image. The animation transforms grey circles into small orange circles, creating a pop-up effect. Clicking on these points triggers an animation that displays the text description of the object; a second click redirects the user to the object category. Each category consists of a list with corresponding images and the same functionality. As an option, users can close the info box frame using the cross button in the top-right corner. To reopen the info box, the info icon will appear after the info box is closed. Additionally, to add a picture to the 'Favorite Collection,' there is a heart-shaped button in the top-right corner.

The animation between images resembles the scrolling effect seen on TikTok. When scrolling down, the recent picture moves upward, and the next one appears. Using the 'Smart Animation' option, the header, info box, and categories bar remain visually in the same place. This design choice enhances visual accuracy and a native feel.

As the user scrolls down, instead of the logo in the header, the picture navigation bar appears. This navigation bar assists the user in navigating through the images, providing greater flexibility for a large number of pictures. Clicking on an image in the navigation bar redirects the user to the selected image.

The animation between categories involves clicking on one of the bar's buttons. The recent picture animates into a round frame in the navigation bar in the header. When returning to the previous category, the recent picture in the navigation bar smoothly transitions back to its focused size.

The recent picture where the user is situated serves as the key image from which the categories begin their analysis of similarity.

### Menu 

The menu consists of five buttons of similar sizes, bordered by a 2px-wide stroke between them. Each button has an icon and a following text description. When clicking on the 'Recent Picture' button, it triggers an accordion animation. This animation expands a large image frame on the left and a line of smaller circular frames of images on the right. This feature helps the user navigate through their favorite pictures that they took while using the app.

The 'Favorite' button displays the pictures that the user has added to their favorites list, aiding in navigating through the pictures the user liked during their use of the app.

The footer contains technical settings, such as a color mode switcher and a language option button. The bottommost button, labeled 'Terms of Use,' redirects to the next page with information. It functions similarly to the 'About' page in terms of its functionality.

### Navigation 

The user has the ability to navigate through the entire range of app functionalities by using the header section. Returning to the initial is facilitated by clicking on the logo. The menu bar remains accessible from any point within the app. Should the user wish to capture another image, this can be accomplished in just two clicks – first by accessing the menu and then selecting the "Take a Picture" button. The arrangement of page elements is designed to ensure that the user can access all tools within the app with a maximum of two clicks, thereby enhancing the user-friendliness of the software.



<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/833721849?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Zoomland - Gameplay"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Taking a picture
