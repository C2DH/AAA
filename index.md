The main idea of this prototype is to provide a comprehensive outline for the app's functionality, enabling developers to understand the required features that the software must encompass. It also illustrates the intended user interface design, including the navigation flows within the app and its key features. Additionally, it outlines how information should be presented and highlights the technical capabilities of the software.

Link to the project:
<div style="padding:56.25% 0 0 0;position:relative;">
<iframe style="position:absolute;top:0;left:0;width:100%;height:100%;"  src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FuMXXVLMVFnwfDe9R3KTw0B%2FAAA%3Ftype%3Ddesign%26node-id%3D494%253A1887%26mode%3Ddesign%26t%3DDQXwf0NkmaPSKFuY-1" allowfullscreen></iframe></div>

## Welcome 

The welcome page of the prototype features a centrally positioned logo. In the background, a painting is displayed with a semi-transparent pattern overlay. The corners of the page are gently rounded, intended for use in the subsequent page's animations. This design was implemented to convey a visual representation of the software's purpose and concept.

<div style="padding:120.47% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/858633439?h=1eb473f198&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:80%;" title="Screen Recording 2023-08-28 at 15.01.18"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Take a picture 

The page consist of header with logo and menu button. The main part represents simulation of the user expierence in the musueum and take a picture button. After Taping on the take a picure button , it made a simulation of photoaparat flash after gives a selection of picture which was analyed by the software. 
After clicking on one of them it will redirect to the focus picture part.
 

##  Visual Art Discovery

The page includes a header with a new option allowing the user to return to the stage where they can take a photo. The middle section features the selected picture accompanied by an info frame box.
The Info Box comprises a Title, representing the picture's name in a 30px font size. Adjacent, in a slightly smaller 24px font size, are details such as the artist's name, year of production, and painting technique. These details are presented using a two-color gradient with a 1.5px stroke in the primary color.

The lower half of the page showcases a picture selected from a similar artist. This inclusion encourages the user to scroll down, leading them to discover similar pictures through the 'categories.'

By dragging the page downward, a scrolling animation is triggered, transitioning the user to the artist category (it was choosen as an initial cathegory).

## Categories

There are four categories by which you can search for similar pictures. Each category consists of five headers with similar functionality as before (a back button that directs you to the rcent picture part, a logo that navigates to the beginning of the app, and a menu button). The picture is prominently displayed in full-screen mode.

The info frame box and Categories bar are located in the footer section of the page. The Categories bar has four buttons: 
`Same Colour`, `Artist`, `Same Epoch`, and `Objects`.

<div style="padding:120.47% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/858931251?h=a1c41428e9&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Screen Recording 2023-08-29 at 11.28.03"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Object recognition

After a delay of 800 milliseconds, orange dots appear on the picture, marking the objects in the image. The animation transforms grey circles into small orange circles, creating a pop-up effect. Clicking on these points triggers an animation that displays the text description of the object; a second click redirects the user to the object category.

<div style="padding:120.47% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/858927893?h=b3ac7f518c&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Animation through categories. AAA project"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Each category consists of a list with corresponding images and the same functionality. As an option, users can close the info box frame using the cross button in the top-right corner. To reopen the info box, the info icon will appear after the info box is closed. Additionally, to add a picture to the `Favorite Collection`, there is a heart-shaped button in the top-right corner.

The animation between images resembles the scrolling effect seen on TikTok. When scrolling down, the recent picture moves upward, and the next one appears. Using the `Smart Animation` option, the header, info box, and categories bar remain visually in the same place. This design choice enhances visual accuracy and a native feel.

As the user scrolls down, instead of the logo in the header, the picture navigation bar appears. This navigation bar assists the user in navigating through the images, providing greater flexibility for a large number of pictures. Clicking on an image in the navigation bar redirects the user to the selected image.

The animation between categories involves clicking on one of the bar's buttons. The recent picture animates into a round frame in the navigation bar in the header. When returning to the previous category, the recent picture in the navigation bar smoothly transitions back to its focused size.

The recent picture where the user is situated serves as the key image from which the categories begin their analysis of similarity.


## Menu 

The menu comprises five buttons, each of similar size and bordered by a 2px-wide stroke between them. Every button features an icon along with a corresponding text description. When the `Recent Picture` button is clicked, it initiates an accordion animation. This animation expands a large image frame on the left and a row of smaller circular image frames on the right. This feature assists users in navigating through their favorite pictures taken while using the app.

<div style="padding:120.33% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/858618290?h=486f7b032b&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:80%;" title="Screen Recording 2023-08-28 at 14.12.51"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

The `Favorite` button showcases the pictures that users have added to their favorites list, aiding in the navigation of images they appreciated during their app usage.

In the footer, you'll find technical settings such as a color mode switcher and a language option button. The bottommost button, labeled `Terms of Use`, redirects users to the next page containing relevant information. In terms of functionality, it operates similarly to the `About` page.



## Navigation 

The user has the ability to navigate through the entire range of app functionalities by using the header section. Returning to the initial is facilitated by clicking on the logo. The menu bar remains accessible from any point within the app. Should the user wish to capture another image, this can be accomplished in just two clicks – first by accessing the menu and then selecting the `Take a Picture` button. The arrangement of page elements is designed to ensure that the user can access all tools within the app with a maximum of two clicks, thereby enhancing the user-friendliness of the software.



--- 
