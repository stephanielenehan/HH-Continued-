Return to course mid Jan 2024. 
New deployment 18.01.24
https://stephanielenehan.github.io/PP1-Handsome-Hounds/

To whom it may concern, I wish to respectfully acknowledge that whilst this submission is technically a resubmission, that it is wholly incomplete to date. I have effectively started over on the project and have based my new code mostly on the newer version of the Love Running walkthrough that has been added to the LMS. I last attempted the course prior to ADHD diagnosis and treatment over the last year during which time I did not code at all. 

Whilst I am disappointed not to have completed this project in time and will have to work hard to complete it now before final grading, I am nonetheless pleased with the development process so far and look forward to completing the project. I have chosen to leave the original code of my first attempt at the project in the repo and you will find it commented out below the code I am developing now. In order to be able to run the old code to remind myself of how it originally looked and functioned, I copied the old code into a second repo entitled test which can be seen below. 

https://stephanielenehan.github.io/test/

The original repo which I returned to with its complete commit history both old and new can be found under:

https://stephanielenehan.github.io/PP1-Handsome-Hounds/

My README.md is a work in progress with a mixture of notes on both the old version of the project and the new. 
Some aspects of the project have been changed altogether. This reflects a more coherent development process.

I have updated the font choices for two reasons: 1. I discovered that the original fonts that I chose are no longer available / supported. 2. In assessing the best fonts to use for accessibility I ensured to select new fonts that meet that criteria. 

I have changed the color scheme completely.  Whilst the old color scheme was "pretty", I have approached this version of the project from the perspective of accessibility. In particular with visual impairment in mind. The previous color scheme did not conform to the required contrast ratio. Whilst I changed various elements to different colors during the development process to enable me to understand layout, the two colors in use are blue and yellow to reflect this. As the rest of all my original content is still commented out the website currently looks quite bare. 

I have developed the header and nav bar from scratch this time around (using the new Love Running walkthrough for guidance) as opposed to the last nav bar which was attributed to someone else and I was barely able to understand, let alone create one myself. 

There is a definite issue with the overflow of my header and the content being pushed to the right off the screen (regardless of screen size).  I suspect the issue is related to positioning and width and have unfortunately not yet solved that but am determined to do so. 


Favicon 
That little picture or icon that appears on the brower tab. 

Working favicon on my site: (Light mode)

![image](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/56d9bdf8-ef88-4611-bfb2-447223bed615)

Working favicon on my site: (Dark mode)

![image](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/43eedabc-1faf-4659-b674-822aa3465b3d)



According to favicon.io "Some alternative names for favicon are browser icon, favorite icon, shortcut icon, tab icon, URL icon, and bookmark icon. The word favicon is short for “favorite icon” and originates from Internet Explorer’s “Favorites” feature which most modern browsers call “bookmarks”."

I have ensured to include the format of ICO along with PNG or SVG for several reasons:
- The ICO file format was developed by Microsoft and is the original file format for the favicon. The format is unique because it allows for multiple small images within the same file. This is advantageous because the small icons required for a favicon in ICO format (16x16, 32x32, and 48x48 pixels) can be scaled and optimized independently. At small dimensions you can’t rely on the browser to automatically resize your icon in an optimal way. 
- The ICO format is supported by all browsers and it’s the only format that IE5 through IE10 supports. Much as Microsoft Internet Explorer had been replaced by Microsoft Edge, as I am developing a site for optimum userability across multiple browsers I thought it would be remiss of me to select a format/s that definatly excluded compatability with Internet Explorer as according to Internet Explorer's own statistics as of 2023 they still had 28 million users worldwide.

 Why bother with a favicon?
- Brand recognition and association. 
  A favicon is used to help users visually identify websites, web pages, and web applications more easily within browser tabs, bookmarks, shortcuts, and address bars more easily. It’s important to have a favicon for your website for brand recognition so that your users can easily identify your site in their browser tabs and bookmarks.

Which favicon and why? 
- Lots of websites use their product or service logo as its favicon to stay consistent with the company's brand and maintain that association people have with a certain logo as a brand or product identification. 



 NOTE TO SELF: Match Favicon to Logo 
 I'm looking for: 
 - Something that shows up and stands out on a web brower tabs no matter what color it is (i.e. light or dark mode for white or black tabs?)
 (note to self - what color does a favicon turn in dark mode? black on black? avoid black or white?) 
  - Logos selected:
  insert image (Screenprint of Dog pawprint Icon 89239 (for use in README) from icons-icons)

WCAG source: (https://www.boia.org/) Bureau of Internet Accessibility. 
The Web Content Accessibility Guidelines (WCAG) is the international standard for digital accessibility. WCAG contains a number of success criteria that apply to icons.
This criterion requires the visual presentation of text and images of text to maintain a contrast ratio of at least 4.5:1. The contrast ratio refers to the difference in luminance (light) between a foreground element and its background. 

Many icons contain text, and users with vision disabilities may not be able to perceive text with a low contrast ratio. Even if an icon does not contain text, it’s a good idea to keep the icon within WCAG’s thresholds — remember, you’re including the icon because you want users to click on it. If the image is invisible to some people, it’s not doing its job.

NOTE TO SELF: Does a favicon support the equivilent of an alt description for screen readers and accessibility? 

NOTE TO SELF: 
Screenprint of related images on istock (shown on icon-icons.com)
 - Might be of use as related background images? Keep accessibility in mind. 


NOTE TO SELF: add section on accessibility testing. There is a link on https://www.boia.org/ to test website.
Test Favicon
Test all Icons
Test all logos
Test background images
Test fonts chosen and default back up fonts. 
 - Original fonts chosen  font-family: Verdana, Geneva, Tahoma, found to be now deleted or unsupported by Google fonts. 
 - New fonts chosen font-family: Roboto Flex, Roboto Mono.
Ref recommended on https://morningtrain.dk/en/examples-of-good-fonts/
We mostly use the following fonts:
Roboto
Lato
Ubuntu
Playfair
Open Sans
We mostly use these because:
They work well digitally, whereas other fonts may be better suited for print.
The shape of the letters makes them easy to read.
They are fairly neutral fonts, so they can fit many different use cases across industries.
All of the above-mentioned fonts belong to the so-called “Sans-serif” family.
This group of fonts does not have “feet”, making it easier to read on the web where feet can quickly consist of too few pixels and become unclear to the reader.
 - Dev notes on fonts: Lato, Roboto & Ubuntu proving extremely similar and hard to discern during initial implimentation. This may resolve with further dev by using different font sizes or weight. NOt ruling out will need to reselect another font. 

Test all links internal and external. 
Test all colour choices and combinations. 
and show all results and changes made where required and why.
 - Insert before & after pictures of new color scheme and explain why. i.e. accessibility top priority followed by appealing to general audience. Previous color scheme was pretty but not suitable for accessibility. Ref for new color choice based on https://www.perkins.org/resource/choosing-high-contrast-color-schemes-for-low-vision/


![Screenshot showing device toolbar Galaxy Fold (mobile first principle in action)](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/5010660f-b841-4775-8ff7-a9d29c9d947a)

![Screenshot dev progress of site on browser](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/9ad6366e-e6fa-4167-abb9-3295f04c90f2)

![Screenshot yellow on blue high contrast 100% accessibility on lighthouse](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/74263fd9-76b1-4019-98ac-54eb669641fc)

![Screenshot giving elements different colors to assist layout dev](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/f40740ac-1b8a-4960-9560-b2528527789f)

![Screenshot header layout progress (only working on larger screens) ](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/47012acb-7e33-43b8-978b-ab40deca96e1)

![Screenshot header layout on smaller screens still being cut off to the right](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/ee58f339-818e-4b46-a0f4-3f3278065d09)

![Screenshot media query tablet 768px   above, header still being cut off to the right](https://github.com/stephanielenehan/PP1-Handsome-Hounds/assets/35435182/9ce8d441-3196-458a-a3a4-48d7b048a305)









OLD README BELOW



# Handsome Hounds

![image](https://user-images.githubusercontent.com/35435182/181649092-9aa616ce-00f7-4837-aada-b11bdcd449cc.png) (consider naming convention of images e.g. landing page etc see notes in pasted template...i.e. ensure a clear file path)
![image](https://user-images.githubusercontent.com/35435182/181649176-d232a352-23bf-4326-81ab-a07a7b8c4620.png)

https://stephanielenehan.github.io/love-cinema/ (update HERE)


https://github.com/stephanielenehan/love-cinema (update HERE)

# Author: DEVELOPER_stephanielenehan

# Welcome to Handsome Hounds!
This is my website offering dog grooming which displays a welcome landing page, a gallery of photos of assorted dog breeds either freshly groomed or being groomed, an information panel of reasons to get your dog groomed, opening time and contact information, an enquiry & quote request form, and social media links. A 404 error page is also made to match the main web page and direct users back to the main page.  


# Wireframes
![image](https://user-images.githubusercontent.com/35435182/181641306-c0a254e0-d948-442f-ac51-10eda194bc54.png)

# Imagery 
![image](https://user-images.githubusercontent.com/35435182/181652289-d0bb73bf-a092-4ba4-a083-a4f8b728ab37.png)
![image](https://user-images.githubusercontent.com/35435182/181652566-88d33f38-e281-4a14-aba7-0ab2fb30a43e.png)
 - The imagery chosen reflects the variety of sizes and types of dog breeds catered for along with the variery of services offered (washing, cutting, brushing, nails). 
 - The imagery chosen shows happy healthy animal exhibiting positive results for both dogs and owners. 

# Styles
![image](https://user-images.githubusercontent.com/35435182/181653387-e923c718-b24e-42b0-8916-350145088406.png)
 - The color palette chosen reflects a bright positive background with easy to read text. 
 - The muted earthy tones contrast well against the blue background whilst reflecting the nuetral tones of dog's fur. 

# Features

## Header 
![image](https://user-images.githubusercontent.com/35435182/181688706-af07ee65-0be4-4cba-b97d-52b358b15844.png)
 - The header contains the display page title for the name of the business Handsome Hounds. 
 - The header contains navigation links as below detailed. 
 - The image used in the header is of a small shih Tzu being groomed. The image is a happy vibrant dog enjoying being groomed to demonstrate the overall aim and ethos of the website and reflects the alternative description of a : small Shih Tzu dog being groomed. 
 - The header contains a tag line under the main image to reinforce the mission of the website to provide grooming services for everything a dog needs: A customs cut from nose to butt. 

## Navigation
![image](https://user-images.githubusercontent.com/35435182/181650552-5b2ce4b6-c888-438d-94a3-25f8394bad95.png)
 - Navigation bar consists of tabs for HOME, PHOTOS, REASONS TO GET YOUR DOG GROOMED, OPENING TIMES, MAKE AN ENQUIRY and SOCIAL MEDIA.
 - Dev process: wording of 'PHOTOS' updated to 'GALLERY' as gallery implies more than photos if e.g. videos were added later. 
 - Dec process: wording of 'REASONS TO GET YOUR DOG GROOMED' updated to 'REASONS FOR GROOMING' as wording used was too long winded to say same thing and there would too many words to try and run onto the next line when condensed for mobile. 
 - Each tab on the navigation bar of the index.html page functions with an internal link to bring the user to the relevant place on the page. 
 - Each tab on the navigation bar of the 404.html page functions with an internal link to bring the user back to the landing page and to the relevant section in one click. 

## Body
- The body consists of 4 sections that each represent a user end point for provision of information or further action.

## Section : Photos  - The photos section is comprised of 6 images : 
![image](https://user-images.githubusercontent.com/35435182/181691854-0de6b01d-e25a-4e87-a9dc-c25ed1675064.png)
   - small Pomeranian dog freshly groomed
 
 
![image](https://user-images.githubusercontent.com/35435182/181691935-52b70db5-f6a8-4edb-96cc-c75e6f6709ae.png)
   - large dog having undercoat groomed out


![image](https://user-images.githubusercontent.com/35435182/181692030-7ef24247-4bca-4802-aaa1-3ee7e6258157.png)
   - freshly washed and dried black Labrador dog wearing red bandana around neck
   
   
![image](https://user-images.githubusercontent.com/35435182/181692091-42a39e39-6f3a-4492-b1eb-001d3735ca5a.png)
   - Three eight week old puppies being washed together in a large sink
   
   
![image](https://user-images.githubusercontent.com/35435182/181692199-26d22414-2fb5-4d30-9b68-2fce417085cf.png)
   - Two small pugs dogs,freshly groomed, one black and fawn, one all black
   
   
![image](https://user-images.githubusercontent.com/35435182/181692328-c5b73942-f983-461d-9537-efefaf8cebf6.png)
  - single dog paw showing freshly cut nails

## Section : Reasons  - The reason to get your dog groomed section is comprised of 5 statments that validate the reasons one might get their dog groomed
![image](https://user-images.githubusercontent.com/35435182/181694059-3234c905-eb0b-432f-aafe-ae8b415df16c.png)

  - Each reason links back to evidence shown in the afore mentioned photos section and is listed in the section right after the photos to reinforce this. 
![image](https://user-images.githubusercontent.com/35435182/181694164-303cd671-81e4-4560-bb82-b0c14fcd5df2.png)

## Section : Opening-Times - The opening times section shows the basic information one would need if they chose to contact or attend the dog grooming salon. 
 ![image](https://user-images.githubusercontent.com/35435182/181695439-69a4a992-5c3f-4a1a-9396-1e84337f0a54.png)

 
 - Opening and closing day along with their corresponding times.
  - Phone number for the dog grooming salon. 
  - Email address for the dog grooming salon. 
  - Physical address for the location of the dog grooming salon. 

## Section : Enquiry  - The enquiry section comprises of a form the user has to complete and submit with either their email address or their phone number in order to receive a quote back. 
![image](https://user-images.githubusercontent.com/35435182/181697960-e860b910-f1c4-4c97-a57a-442c347c18e2.png)

![image](https://user-images.githubusercontent.com/35435182/181697845-346c676e-6d7a-41f2-8fb0-ba1c0915e4b6.png)

   - The input area for the email address requires the correct format with an @ symbol and an appropriate message appears for the user beside the input area when this criteria is not met so as to indicate to the user to input the email address correctly. 

![image](https://user-images.githubusercontent.com/35435182/181698908-3c60141f-62fc-49cf-a67c-6e00662f3b51.png)

  - The input area for the phone number requires the correct format with numbers and an appropriate message appears for the user beside the input area when this criteria is not met so as to indicate to the user to input the phone number correctly. 



## Footer: - The footer contains :
![image](https://user-images.githubusercontent.com/35435182/181699496-dedad2c1-ce5e-426a-9cff-ea03dd22872c.png) 
  - Social media links for Instagram, Facebook and Twitter that follow the template of Coders Coffeehouse.
![image](https://user-images.githubusercontent.com/35435182/181717825-51f6278c-9eb5-4ce2-a483-caff2975cda7.png)
![image](https://user-images.githubusercontent.com/35435182/181717954-c7f51421-b37f-4308-9cff-54ac5adc5f12.png)
![image](https://user-images.githubusercontent.com/35435182/181718374-eecf0b52-c938-45e6-98c2-8f66b96acc65.png)
- Each social media link opens in a new page
- Copyright shown as a referal to the README containing fictional and attributed sources. 


# Testing
## CSS Validation
- style.css has been tested with CSS Validation https://jigsaw.w3.org/css-validator/validator and any error or warnings found corrected. 
![image](https://user-images.githubusercontent.com/35435182/181655143-5b4f4d27-0ccb-4f06-9cc4-1ddcd66b2c05.png)
 - CSS now validates without error. 
 
## HTML Validation
![image](https://user-images.githubusercontent.com/35435182/181655619-e73948d6-1d0a-4787-809e-f7e07a50e6db.png)
 - index.html has been tested  with HTML Validation https://validator.w3.org/nu/#textarea and any errors or warnings found corrected. 
![image](https://user-images.githubusercontent.com/35435182/181656109-9423c33d-8667-4e76-beb0-4139f0bd11ab.png)
 - index.html now validates withour error. 

![image](https://user-images.githubusercontent.com/35435182/181656239-f8408d9b-310f-490a-8f73-6ff5cefa9921.png)
 - 404.html has been tested with HTML Validation https://validator.w3.org/nu/#textarea and validates without error. 
 
## Manual Testing
write out feature and say how you checked it. 
 - how I tested it in bullet points 

 A typical debugging process might look like the following:
1.	A bug is identified either by a user or by a developer during testing/development.
2.	The developer (if the bug was reported by a user) tries to reproduce the bug and verifies that it exists.
3.	The developer starts at the moment of user input, first verifying that the input is received correctly.
4.	The developer follows the code line by line, displaying output along the way until he or she identifies a problem in a function imported from an external library.
5.	The developer Googles some information about the problem or visits the external library's documentation to verify he or she is using the function properly.
6.	The developer identifies a mistake in the way they were utilizing the external library and makes the appropriate changes to the code.
7.	The developer tests the same input again verifies the code is functioning correctly and the rest of the application has not been affected and then deploys the change.

Some questions you should get in the habit of asking yourself are:
1.	What did I expect to happen when the code was run?
2.	Precisely what happened when the code was run?
3.	Am I (or is the user) submitting the correct input?
4.	Do all the variables in use in the code have the correct values?
5.	Is the data I'm working with the correct data type?
6.	Are there any functions changing or mutating the data, the input, or the output before the final step of the code?
7.	What am I literally asking the computer to do, and is that actually what I want it to do?


## Accessibility
 - All images contain alt language to describe the images for screen readers. 
 - Social Media links open in a new tab with an aria-label to describe the link and advise that a new tab will open. 

## Responsiveness
 - Site tested with https://ui.dev/amiresponsive?url=https://stephanielenehan.github.io/love-cinema/
  ![image](https://user-images.githubusercontent.com/35435182/181722400-2b603cb3-60c4-42f8-9657-4cb21d362845.png)
 - The site is responsive on mobile, tablet and desktop. 

 




## credits 
### imagery 
- shih-tzu : https://pxhere.com/en/photo/678977
- pomeranian : https://pxhere.com/en/photo/802177
- large Dog undercoat removal : https://pxhere.com/en/photo/678974
- black labrador with red bandana : https://pxhere.com/en/photo/807386
- 3 puppies being washed : https://pxhere.com/en/photo/1055567
- 2-pugs-two-tone-and-black : https://pxhere.com/en/photo/1354939
- dog paw nails : https://pxhere.com/en/photo/847302

### content
- Reasons to get your dog groomed. Source for text from: https://milliespetservices.co.uk/reasons-groom-your-dog/
- A custom cut from Nose to Butt! Source: Tag line is copyright to Muttzforcutz.ie
- Welcome to Handsome Hounds Source: Handsome Hounds is the name of a shop in Portarlington, Co. Laois, Ireland

### styles
- Responsive Navigation based on Malia Havlicek's codepen: https://codepen.io/maliahavlicek/pen/LYeBwNY
- Color scheme from : https://visme.co/blog/website-color-schemes/  I have used no.3 Natural and Earthy #8D8741, #659DBD, #DAAD86, #BC986A, #FBEEC1. 



