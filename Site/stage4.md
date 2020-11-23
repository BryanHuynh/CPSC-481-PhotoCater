<a href="https://bryanhuynh.github.io/CPSC-481-Project">- Phase one</a>    <a href="https://bryanhuynh.github.io/CPSC-481-Project/Site/stage2">- Phase two </a>    <a href="https://bryanhuynh.github.io/CPSC-481-Project/Site/stage3">- Phase three </a>    <a href="https://bryanhuynh.github.io/CPSC-481-Project/Site/stage5">- Phase Five</a>


 

# STAGE FOUR 

### Members (Team F/TUT03): 

#### Bryan Hyunh
#### Don McEachern
#### Ryan Liew
#### Sajid Choudhry
#### Sarina Zohdi 

![title_img](img/stage4/PhotocatorLogo.png)

### Project Description: 

Photocator is a photography landmark social media web application. It focuses on bringing together those individuals that seek to share unique and well-curated photographs of various landmarks around the world. Users will be able to identify themselves with a unique account, which they can then use to upload photographs to the website, as well as share those photographs to external social media applications. The users will provide detailed information about the photograph, including the location (longitude and latitude), date, and time of day. Users can also use a map like graphical user interface (similar to Google Maps) to view landmarks as pins on the map, that they can click on to find out further information about others’ uploaded landmark photographs, that can be filtered to find exactly what you are looking for. Users will also be able to view their own uploaded landmarks through this interface. 

## Tasks prototyped: 

### Vertically: 

- Uploading and sharing photos 

- Social Media Linkage 

- Finding Photos and landmarks 

- Editing User Profile 

### Horizontally: 

- Logging in to the website with a Photocator account 

- Adding friends (All social media platforms) 

- Leaving a review on a location or commenting on a photo 

- Read reviews or comments on a location 

- Users can edit and customize their own profile 

- An accessibility tab is there to accommodate Users with unique needs 

- Add a new location 

- Users can go to other user’s or friend’s social media or profile to see more photos by that user 

- Filtering pins based off different tags 


 

## Heuristic Evaluations: 

### Process:  

For the evaluators, we basically looked at each test individually and ran a series of user tasks to complete while keeping these rules in mind. From there, we decide whether the rule was violated or applied, and we kept examples for each rule that we decided to report. After all rules were finished testing, the evaluators came together and created one final heuristic table, which was the final table. 

For the reviewers, once receiving the table, the reviewers analyzed each problem and decided to give each problem a rating based on this table: 

| Rating | Description |
|---|---|
| 0 | Doesn’t seem to be a usability problem |
| 1 | Cosmetic Problem |
| 2 | Minor usability problem |
| 3 | Major usability problem |
| 4 | Usability Catastrophe |

From there, the reviewers gave a brief description on why they think that the problem was received that rating. 

### Findings: 

We found many problems that we thought we wouldn’t encounter when prototyping this application. For example, we found that the icons we chose can be ambiguous to some users and that sometimes they do the same function when they shouldn’t have. We also found some problems with usability, for example undoing posted comments, when prototyping we never found or thought of this problem. In conclusion, this heuristic evaluation pointed out user errors that we did not come across when prototyping. This heuristic evaluation showed us that there are many problems to consider when prototyping because they can be hard to detect. 

### Reflection: 

Going back there are many things that we are proud of and many minor details that we could look to improve. Looking at things that works well, we put a lot of detail and discussions about what we wanted our site to look like and how the feel of the page should be. Because of this we accomplished many of our rules of thumb as a result. 

In addition to this, there are many minor details that we overlooked because of it being a small design or us looking at this from the perspective as an experienced user. These minor things being like modifying/deleting comments or having error messages for invalid photos when posting. In terms of limitations of Figma, we felt that its use was too static and as a result there were too many states that we must consider so we streamlined like making it to ensure sanity and consistency. For example, for our accessibility tab, we felt that there were too many things we would need to change for it to be fully functional like increasing text size and style. A huge problem we had was with the states of the like button, since clicking on it would require a new page, so we had to through all the combinations as a result for that page. In addition, being able to have a toggle button for dark mode was unable to be implemented because we wanted a toggle button to change sides in addition to swapping to dark, but a button can only do one action. Going back, we would have prevented those problems had we used adobe XD that supports these features. 


## *APPENDIX* 

### Heuristic Evaluation Documents 

 

#### Evaluator: Ryan 

| Rule of Thumb | Is this rule being applied? How so? | Is this rule violated? How so? | How can this rule further improve usability, utility and desirability? |
|---|---|---|---|
| Visibility of system status | Because our system is currently static here is no need for the application of progress bars. || We could apply a progress bar to photos when they are loading in for the user as they are trying to upload a photo, so they know that the photo is loading and not just empty. In addition to a progress bar for uploading photo so they know when they can exit out the page. |
| Match between system and the real world | Yes, all icons that were used match the icons that match the real world. For example, when viewing the descriptions of the photos each category is associated with their exact icon that matches the real world. | Yes, in the nav bar some of the icons are ambiguous to show what that button does. For example, the upload photo button is a plus sign. These icons do not match the real world. | Using these rules, this will help increase usability because it will be easier for users to identify what these buttons do, and it will increase desirability because if these buttons are easily distinguishable it will make user workflow more effortless. |
| User control and freedom | Yes, in our pages, we support a ‘back’ button for users to go to a previous page just in case they went to a page they did not desire. | Yes, when you post a comment on someone’s picture, there is no option to undo that comment. | Using these rules this will help users prevent doing tasks that they did not mean to do. This will increase desirability because it will help users prevent doing undesirable tasks. |
| Consistency and standards | When starting this project, we made sure to standardize our buttons. In addition, these buttons would function in the same way on other pages. For example, All the uses of the back-button work in similar manners where they will close the overlay or return to the previous page. | In our system we have a back button that can either function to close the overlay or return to the previous screen. While this isn’t a major issue, it would be more clear for the user if we had separate button styles differing the two. | Through this we were able to easily help the user in achieving their task. From the start when the user clicks on a button and find another button of the same style, they can rest assured that the button will act in that situation the same way. |
| Error prevention | Yes this rule is being applied. When looking at the Photo upload and the edit profile forms, the user is prompted multiple times to make sure that the actions that they are taking are in fact what they intended. We also gray out buttons to prevent users from clicking on the button before a certain action. For example, when uploading a photo we gray out the confirm button until someone selects a photo. | Yes, when adding a comment we don’t check with the user before posting that they wanted to post what they wrote, so say the user accidentally presses the Enter key early they might post something they either didn’t mean to. | By maintaining error prevention we can help the user represent themselves the way they best want to by prompting them to make sure that they are entering the correct information. |
| Recognition rather than recall | Yes, this rule is being applied. We ensure that one would know where in the action they are by labelling everything and having arrows to point to the actions one would have to do, to ensure a task in completed. For example, if one wanted to upload a photo, that action has instructions all along the way like having a label that says “click here” when they need to put their location in the map. | No, we do not violate this example. | Through these steps and instructions that a user would have to take in order to complete a task it ensures that they do not miss any important steps and making it easier for the user to use our website application. | 
| Flexibility and efficiency of use | If a user knew of a location that they wanted to find photos at they could use that term in our search system to find a gallery of photos speeding up the user's ability to find photos that they want. | For our system currently, there is no way for a user to speed up whatever task they want. For example, if they wanted to find a specific photo, they will always need to find that pin on the map and find the photo in the gallery. | For further functionality we could have decided that we wanted to add a system allowing the user to find photos that they will see before to a separate gallery for quick navigation. |
| Aesthetic and minimalist design | Yes, we use the same design pallet across all our different screens and overlays. By using the common colours to represent buttons the user knows that they have options to interact with the display. | no. | By maintaining a consistent theme across the application User’s being to develop a sense of familiarity to help them navigate through the app and perform the actions that they are looking to do without needing more training or information about what some button on the page does. |
| Helps users recognize, diagnose and recover from errors | No, this rule is not being applied. | We do not contain any error messages for the user just in case they click on the wrong button. |By applying these rules this will help users fix their problems and it will prevent them from doing it again, this increases usability and desirability for the users because it helps users learn how to use the application properly. Also providing further assistance on a step that they missed so that they can go back and correct that error. |
| Help and documentation | Yes, when uploading a photo, we explicitly provide information on what to do to complete the task. When uploading we provide information on the pages for the user. For example, the first page is for uploading a photo and there is message that says it, and when choosing a location there is button that says “click here” to tell users what to do. | No, when signing up for the website our sign up requires putting in an email except we do not give an example or a template for it. We could’ve put a placeholder example into the text field. | This will help users complete these tasks will full information on how to complete them properly without any errors or undesirable outcomes.  |
 

#### Evaluator: Don 

| Rule of Thumb | Is this rule being applied? How so? | Is this rule violated? How so? | How can this rule further improve usability, utility and desirability? |
|---|---|---|---|
| Visibility of system status | No, we do not implement anything here due to the nature of the application, there is no loading screens or anything progressive that requires progress tracking | Yes, For the user after they log into the system there is no information as to what screen they are on or what they are supposed to do. | By giving more information to the user they might have a better idea as to what page they are on in the app. While to the developers it is more apparent what the home screen is we could give more information to the user so that they know what they are being presented with on the screen to at least let them know they are on the home page for example. |
| Match between system and the real world | Yes, by highlighting on the screen after they have added a new photo where they put that photo, they know that the new pin on the screen is one that they had added. |Yes, When the user goes to view on the pin the exact location of a photo there is no information telling them that this is a different screen so they might go looking on this chart for more pins to interact with when they are in a mode that is about reflecting where the photo exactly was taken. |By making sure that the user knows exactly where they are by giving them more information like a little window telling them which mode, they are in they might feel less lost and confused when looking around for more pins should they have changed modes from seeking pins. |
| User control and freedom | Yes, When the user is adding a new photo, they have the option to leave should they decide not to upload the photo without closing the application. | Yes, we have a few screens like viewing friends and the accessibility tab that we should have the ability to leave in multiple ways, but the user must click on the Close button to leave | By allowing the user to simply click to navigate away from a overlay it can help them feel less corned when navigating the page. |
| Consistency and standards | Yes, by using common colours to denote actionable buttons and areas where you can upload photos or add text the users know just from looking at the different buttons that something on the screen is a possible action that they can take. | Yes, by in some windows having the ability to click away from the overlay to close and in others not allowing that we are not being consistent about the different ways that the user can leave an action or go to a different screen. | By making it so that either all of the overlays have a “out of frame” exit the user will not become frustrated should they click on the outside of a overlay and they don’t exit. |
| Error prevention |---| Yes, when uploading a new photo if the user clicks on the next button when either selecting a photo and they have not made their choice the system does nothing. | It should maybe let the user know that there is no selection made and should address this before moving on. This will help the user avoid errors. |
| Recognition rather than recall | Yes, when looking at the photo’s page we use little icons to help the user recognize what each piece of information is conveying. | |This rule is used so that on each page the icons with the text can help them find the information that they are looking for faster without having to try and remember where to find certain pieces of information. They simply can look at the icons and know whats there. |
| Flexibility and efficiency of use |---|Yes, In our application we have no information about keyboard shortcuts to maybe speed things up for the more advanced user like pressing the ‘s’ key on the home screen to quickly access the search function.  | By adding these features to the app it might speed things up for the user novice and expert alike. Though it is worth mentioning that these are missing at the moment because of limitations with Figma and might be something of a note for the Team should this be fully implemented on the front and backend, not just a prototype. |
| Aesthetic and minimalist design | Yes, we keep things simple throughout the app with colourful and easy to read buttons for navigation and do not have anything on the display through any of the overlays that’s over stimulating for the user. | Yes, sometimes depending on the actions taken by the user there can be a lot of different overlays on the screen, while they are all simple in their own design over crowding can cause confusion. | By using a simple and clean design implemented consistently the confusion that the user might run into will be reduced. |
| Helps users recognize, diagnose and recover from errors |---| Yes, there is no error message for the user should they try to enter a photo without picking a location for where the photo was taken | By implementing a error message for the user when they fail to pick a location and they try to upload their photo, or even when they fail to do this for selecting a photo in the first place, we can cut down on the time wasted by the user when they are trying to advance in the upload process. |
| Help and documentation | Yes we don’t anywhere in the application have a help page should a user want more information about what a screen does | Should the buttons and the page fail to explain to the user what each page and overlay does through their implementation having a help button would be good to give an explanation to the user should they wonder about what some page does. |
 

#### Evaluator: Sarina 

| Rule of Thumb | Is this rule being applied? How so? | Is this rule violated? How so? | How can this rule further improve usability, utility and desirability? |
|---|---|---|---|
| Visibility of system status | In the current state of our prototype, and the limitations of Figma, we do not have a system to have the user wait for system responses.  | Because our prototype is currently static there isn’t anything dynamic happening, we do not have a need to implement any system to have the user wait as the system generates a response. | Because our system primarily is a server for photos that can by hundreds of Mb large, it would be beneficial, if not critical, that we have a system that indicates to the user to wait for the image to load. |
| Match between system and the real world | Yes, the system does real-world language and icons that one would see in any other app or website. We also use real-world language that any user would understand. Also using text when a user is hovering over an icon that might be unfamiliar.  | Yes, we have one icon that is a smiley face and that represent the accessibility tab, which is not a common icon that a user would see normally, so they would have to hover over the icon to see what it does. | This rule is very helpful as the user does not have to learn how to use the web application as every icon is easy to follow and familiar. |
| User control and freedom | | Yes, we should have the option to undo a comment if you accidentally posted the wrong comment. | Yes, this is important because the user should be able to have the freedom to leave a certain page without having to do undesirable tasks. |
| Consistency and standards | Yes, by using consistent colour schemes we can help the user better identify buttons and navigate the page easier.   | Yes, we violate in not all of our overlays have the ability to exit them from clicking elsewhere on the page.  | By making sure we follow our own design rules there will not be any cases where the user runs into a situation where they are stuck because they are trying to perform an action that works somewhere else but not on their current overlay.  |
| Error prevention | Yes, we ensure that the user is happy with the location and picture that they have chosen by giving them multiple chances to confirm they have the correct info.  | Yes, when you want to logout, it does not give you a warning before you do so. Just in case you accidentally press that logo.  | This is essential because there could be a human mistake somewhere along the way and it is important to make sure they can fix the mistake without any reprucutions.  |
| Recognition rather than recall | By using common colours we use the user’s previous knowledge of what items on the screen are buttons, so they are immediately attracted to the screens controls | No, we do not violate this example.  | This makes the application very desirable because it minimizes the user's memory load by giving clear instructions instead of them having to memorize each step along the way.  |
| Flexibility and efficiency of use | Yes, we have multiple ways of closing certain overlays  | Yes, there are ways that we could implement to speed up the process of the user experience like selecting a profile photo, they would always have to go through their gallery of photos to select a profile photo. | This is very desirable because it speeds up the process for the user.   |
| Aesthetic and minimalist design | Yes, we try and keep everything very minimalistic by trying to use icons in most places and only using one-word explanations for what each icon means when a user hovers over the icon. We also try and use different colors for different tasks like marking their location on the map when uploading a photo to indicate the new place they are marking.  | No, we do not violate this example.  | This helps the user understand what they are doing and makes everything most visually appealing and easy to follow.   |
| Helps users recognize, diagnose and recover from errors | No, we do not have any error messages that would prompt a user to go back and fix a mistake.  | Yes, currently we do not have any error messages built in in case a user tried to upload a photo without adding a location, the system would just not let them upload that photo and would not tell them what the issue is.  | This rule is very helpful to provide clarify for the user and direct them if they made a mistake somewhere along a task. |
| Help and documentation | Yes, we have prompts on the map when uploading a photo telling the user to click on the location they searched for.  | Yes, we do not have a help navigator or frequently asked questions section on the website.  | If we add more places for user’s to gather more information about how to use the website they might find the website more approachable. |

### Reviewer’s Findings 

We will use this table for severity ratings:

| Rating | Description |
|---|---|
| 0 | Doesn’t seem to be a usability problem |
| 1 | Cosmetic Problem |
| 2 | Minor usability problem |
| 3 | Major usability problem |
| 4 | Usability Catastrophe |
 

### Problem 1: Ambiguous icons 

#### Rating: 1 

- These icons due pose an issue since it makes it harder for the user to complete specific tasks since, these icons are ambiguous. However, this does not destroy any functionality on doing tasks in our prototype 

### Problem 2: Error messages 

#### Rating: 2 

- This problem is rated a 2 because although it is important to ensure the user completes all tasks required to uploading a photo, they will not be allowed to continue to the next step if a certain step is not done. Although it is important for the user to know exactly where they went wrong so that they can go back and fix the issue. 

### Problem 3: No undo on comments 

#### Rating: 3 

- This problem is rated a 3 because since there is no way for a user to undo a comment, they might not be able to remove something that they did not mean to post either because it was not complete, or it was not something that they meant to say. This also reduces the User’s ability to be free when using the app since they might be hesitant to post something since there either might be an unintentional error, or they cannot take something back that they did not mean. 

### Problem 4: Back button  

#### Rating: 2 

- The back button, functions as a back button and an exit button. However, this can cause some issues with users, because they may want to go back and not exit. This does not destroy functionality with the prototype but makes it more difficult for the users’ workflow. 


## References for images: 


- https://www.bing.com/images/search?view=detailV2&ccid=oMaV%2bwoc&id=49A9D590B5520B1641BB276DBE18C10931E93627&thid=OIP.oMaV-wocex1CB8WgkAiLVAHaD0&mediaurl=https%3a%2f%2fimages.dailyhive.com%2f20171126133316%2funtitled-05261.jpg&exph=553&expw=1072&q=Calgary+Tower+On+Fire&simid=608025012837615758&ck=7838923664DF49BC16C381A29CE8A72E&selectedIndex=51&FORM=IRPRST&ajaxhist=0 

- https://www.bing.com/images/search?view=detailV2&ccid=IZ6raqqL&id=76C2C6283AEBE684DC63735DD19128D84AF2DA0C&thid=OIP.IZ6raqqLNRGX2HfscMjAeQHaE8&mediaurl=https%3a%2f%2fc1.staticflickr.com%2f5%2f4033%2f4230157281_504c1f547b_b.jpg&exph=683&expw=1024&q=Calgary+Tower+Inside&simid=608030884076455083&ck=E28D723BABD887C6F9AA690A8E5D6FA4&selectedIndex=0&FORM=IRPRST&ajaxhist=0 

- https://www.bing.com/images/search?view=detailV2&ccid=mBCUFHpT&id=986485846E63CD134B115C1E1AC616DE7E08D8F8&thid=OIP.mBCUFHpTTfupvjJ9jV2XvgHaHa&mediaurl=https%3a%2f%2fi.pinimg.com%2f736x%2ff1%2f83%2f05%2ff18305b9f35ed1d1dfffb1dd576cc1aa--hdr-photography-calgary.jpg&exph=612&expw=612&q=Calgary+Tower+On+Fire&simid=608005376238683314&ck=B81A4DE697DD2483B7A71D638678FF77&selectedIndex=0&FORM=IRPRST&ajaxhist=0 

- https://www.cbc.ca/news/canada/calgary/peace-bridge-maintenance-1.5602417 

- https://www.reddit.com/r/Calgary/comments/9eh0oy/peace_bridge_at_midnight/ 

- https://www.bigstockphoto.com/image-115973417/stock-photo-peace-bridge%2C-calgary 

- https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.shutterstock.com%2Fsearch%2Fcalgary%2Brain&psig=AOvVaw24C2jSzwlMFz-VsxY6hz_B&ust=1605319811049000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKC18cK4_uwCFQAAAAAdAAAAABAD 

- https://www.pinterest.ca/pin/541346817708570720/ 

- https://www.calgary.ca/csps/parks/locations/downtown-parks/devonian-gardens.html 

- https://uhdwallpapers.org/wallpaper/girl-taking-pictures-at-sunset_87798/1920x1080/ 

- http://www.shotsbypeter.com/blog/?p=12778 

- https://www.waltersgroupinc.com/project/the-bow/ 

- https://www.tetratech.com/en/projects/the-beautiful-bow-calgary-alberta 

 