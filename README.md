#  Thisiskaysis - Portfolio Task
​
[My portfolio site](https://thisiskaysis.github.io)
​
## Project Requirements

### Content
 Add a short paragraph describing the features below. What aesthetic and technical choices did you make? 
- [x] At least one profile picture
- [x] Biography (at least 100 words)
- [x] Contact Form
- [x] "Projects" section
- [x] Links to external sites, e.g. GitHub and LinkedIn.

I wanted to create a website that felt more creative and showed my personality a little. The background image combines my loves of anime, the night sky, and feels a little ethereal. The girl sitting on the right feels like me - looking up to the stars, dreaming about possibilities, manifesting ideas. I knew I wanted to use purples, greens, blues being my favourite colours - and once I decided on background image I wanted to make each section blend using opacity. I noticed that it may make the text harder to read, so I added hover effects (contrast) to help with readability.

The icon choices also needed to fit the theme - I chose to add links to Github, LinkedIn, Facebook and Instagram *(although I will probably delete the social media at a later stage - I just wanted more than 2 for aesthetics!)*.

The projects section is currently blank, but I will have content to put here soon! I struggled mostly with condensing my ideas into something cohesive, creating a website that is easy and pretty to use, but not over-the-top.
​
### Technical
 Add a short paragraph describing the features below. What strategies or design decisions did you work from? 
- [x] At least 2 web pages.
- [x] Version controlled with Git
- [x] Deployed on GitHub pages.
- [x] Implements responsive design principles.
- [x] Uses semantic HTML.

I chose to create 4 pages - index, about, projects, contact.

I used the template of my_first_website as a basis to work from, changing and adapting it as I learnt new skills each week. I controlled all versions with Git, committing changes frequently and working on branches for any new details or ideas, then merging to main.

With **responsiveness**, I first started with positioning my articles stacked in a column for smaller, phone-sized screens (below 768px). I then added media queries to expand to a row, 3 wide, for larger screens (above 768px).

I noticed there was a "weird area" in the middle of these sizes, where the articles started to condense and look far too skinny below 1040px. So I made a third media query, to target width between 768px and 1040px, which sets the first 2 articles in a row, and the third article beneath them spanning the entire width of both articles.

I added contrast(200%) on phone & tablet screens for readability since hover effects won't work.

I tried to use **semantic HTML** through the entire code, however I had to use < div > once in order to get my hero text animation working - I tried to use < ul > and < li > but couldn't get the animation to function *(troubleshooting that... fun times)*.

### Bonus (optional)
 Add a short paragraph describing the features below, if you included any. 
- [x] Different styles for active, hover and focus states.
- [ ] Include JavaScript to add some dynamic elements to your site. (Extra tricky!)

I **loveeeee** hover effects! I used many hover effects through my website:
- **On articles:** contrast 150% for better readability.
- **On buttons:** transform scale and translateY + box-shadow to add raise effect, as well as colour change.
- **On < nav > menu:** colour change, pointer change.
- **On social media icons:** transform scale.
​
### Screenshots
> Please include the following:
> - The different pages and features of your website on mobile, tablet and desktop screen sizes (multiple screenshots per page and screen size).
> - The different features of your site, e.g. if you have hover states, take a screenshot that shows that.  
> 
> You can do this by saving the images in a folder in your repo, and including them in your readme document with the following Markdown code: 

####  image_title_goes_here 
![Put a description of your image here](./relative_path_to_file)

[] 4 pages full size
[] 4 pages mobile size
[] 4 page tablet size

[x] article hover state
[x] button hover state
[x] social hover state
[x] nav hover state