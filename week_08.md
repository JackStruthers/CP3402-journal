# Week 8
## Learning Activities
This week I spent time finding, setting up and learning how to use the GitHub updater plugin. I also spent time with Kazuki learning how to use sass and compiling that SASS into CSS to make visible changes on our websites.

## Resources and Links
https://docs.understrap.com/#/understrap-child/npm     
https://github.com/afragen/git-updater    
 

## Estimated hours
I spent about 2 hours learning about these topics.

## Content Insights
After creating both the staging and main site I wanted a way for the team to be able to auto update the theme for each from a specific branch of our repository. I found the tool in the link above and got to testing this out with Kazuki. We ran into the issue of whatever changes we were pushing it seemingly would not update the website. To trouble shoot this we used another WordPress plugin that lets you download the themes on the website easily. After we download the theme, we tested to see if the changes we made were being pushed to the website when using the auto updater. We could see the code we changed so we knew the auto updates were working. This was a success. The next task for the two of us was learning how to use node.js to correctly compile that SASS. We found that the command "npm run watch" did not seem to compile our code. After looking at the Understrap website a bit longer we found the "npm run dist" command. Provided we used a new terminal with VS this worked. It would correctly compile our SASS in the way we needed. The live sites updated to the new themes. This means we can now actually easily create our website.

## Career/Employability/Learning Insights
Learning how to use a tool that auto updates a theme from a certain GitHub repo is a great skill to have. These auto updates allow for testing without having to upload a file manually every time you make some sort of difference. This saves a lot of time in the long run as even if this process took you thirty seconds to do usually, you would still have to do this quite a few times. SASS also seems to be a useful tool as many different elements that would usually make going through an entire CSS file painful once you have a lot of content are broken into separate files. This separation makes finding specific parts of the styling much easier to do and using node.js commands it can compile itself into CSS.

