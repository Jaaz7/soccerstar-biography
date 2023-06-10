# Ronaldinho Gaúcho's Biography

Soccerstar Biography's purpose is to show the client's biography and deliver a way for the player to be contacted.
This website hopes to inform the public about the history of the player and his several accomplishments thorought the clubs he performed.<br>
## Landing Page<br>
It consists two sections depicting different parts of Ronaldinho's life and an introduction to both his accomplishments and a backstory to his early life.
There's also an embbeded google maps widget to display the city he was born for context.
![Screenshot from 2023-06-09 19-26-13](https://github.com/Jaaz7/soccerstar-biography/assets/130407877/707f6301-2d71-4a5a-bffd-76159ba03d27)
## The Website<br>
It consists of 10 pages that are easy to navigate. They aim to shed more knowledge about the professional life of the player
<img src="https://github.com/Jaaz7/soccerstar-biography/assets/130407877/00ce705a-1f71-4f3e-b437-3495603b60f8" width=80% height=80%>


## Features
- **Responsive navigation bar**
  - The navigation bar stays fixed in the center of the page and allows the user the navigate through the pages without having to click "back".
  - Has a smooth transition & animation for an eye-catching user experience for PC users.
  - It has a contact button which will link to a form where the player can be contacted.
## <img src="https://github.com/Jaaz7/soccerstar-biography/assets/130407877/fd846b58-15c8-4587-99e2-c05ce68db77c" width=50% height=50%>

- **The Contact Form**
  - It consists of a way for the player to be contacted for bussiness inquiries.
  - The name, email and subject input fields are required to submit.
  - the email input field requires an email for the submission to work.
  - Features is a reset button.
  - Redirects to a symbolic "thank you" page after submission.
## <img src="https://github.com/Jaaz7/soccerstar-biography/assets/130407877/51794a10-3f3b-4d0f-8b5e-a5de9ebf7e98" width=80% height=80%>
<img src="https://github.com/Jaaz7/soccerstar-biography/assets/130407877/0daf3ef9-6b1d-490f-a095-6aeb8c1447aa" width=30% height=30%><br>
- **The Footer**
  - The footer consists of quick anchors to the player's socials with the icons of respective platform.
<img src="https://github.com/Jaaz7/soccerstar-biography/assets/130407877/4324a0a3-34fb-4950-8b7e-4b5f63426307" width=100% height=100%>

## Features left to Implement
- A search button with a magnifying glass icon that will redirect to any part of the website.

## Testing

- I built this website for PC first before media queries for mobile responsiveness. The majorities of the issues appeared with the dropdown menu.<br>
The dropdown menu was coded to work on the following:<br>
An opacity and transform animation that transitioned into the dropdown menu to appear. Frst thing I weanted to fix was that the dropdown menu wouldn't disappear when the button was clicked again so I used a pointer-events workarout for that.
- Second major issue was that this dropdown menu wasn't working on touchscreens, the links wouldn't direct to other pages likes it worked o PC.
So after a lot of testing, I decided to redo a whole new dropdown menu only for touchcreens using @media(pointer:course), which instead of a button it consists of a hidden checkbox input that looks like a button.
- I also created another media query for the website to work on mobile with good resizing.

- The website passed within the following validating websites:
    <br>HTML
        <br>No errors were returned when passing through the official W3C [validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjaaz7.github.io%2Fsoccerstar-biography%2F)
    <br>CSS
        <br>No errors were found when passing through the official (Jigsaw) [validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjaaz7.github.io%2Fsoccerstar-biography%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
        
## Deployment

The site was deployed to GitHub pages.

- The live link can be found here - https://jaaz7.github.io/soccerstar-biography/

## Credits
- I was inspired by Kyle's amazing CSS tutorials, this is his [youtube](https://www.youtube.com/@WebDevSimplified).

## Content
- All content information was taken from Ronaldinho's official [wikipedia](https://en.wikipedia.org/wiki/Ronaldinho) page.

## Media
Links to the image sources:
- https://www.irishmirror.ie/sport/soccer/soccer-news/ronaldinho-returns-paris-saint-germain-9722489
- https://www.pinterest.com.mx/pin/ronaldinho-of-barcelona-brings-the-ball-forward-during-the-primera--77546424820517378/
- https://www.pinterest.com.mx/pin/988399449450273239/
- http://www.chinadaily.com.cn/english/doc/2004-12/21/content_401992_3.htm
- https://www.pinterest.com.mx/pin/128141551884280455/
- https://www.pinterest.com.mx/pin/1112107701707665584/
- https://brazilfooty.com/wp-content/uploads/2011/04/flaRonaldinho_ramos_0204201106.jpg
- https://www.chinadaily.com.cn/sports/2013-07/12/content_16767414.htm
- https://futboljobs.com/blog/la-supercompensacion-tactica-en-el-futbol/
