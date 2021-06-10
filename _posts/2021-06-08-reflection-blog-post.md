---
layout: post
title: Project Reflection
---
I am immensely grateful I had the chance to take PIC 16B this quarter. I feel that I have learned a lot from this class thanks to my peers, who contribute a lot of interesting ideas, and Phil, who is an amazing professor.

The journey to creating a long-term project was difficult, but I am glad that I
had this experience. Jaya and Stancy were great teammates who were hardworking and creative, and I can say this has been the best group project experience I have ever had thanks to them. I am also very proud of what we were able to accomplish, even though we only worked on our project for about six weeks!

### Overall, what did you achieve in your project?
Our group, The Travelers, managed to create a functioning web-app that contains all of the tourist attractions, hotels, and restaurants in LA. The user is able to enter keywords to lookup location recommendations, as well as plan travel routes depending on where they want to go and how long they plan to stay.

### What are two aspects of your project that you are especially proud of?
- I am proud of the fact that all three of us took the time to learn something that was completely new and not in the PIC 16B curriculum. For me, that happened to be geocoding, getting route data using requests, and using that route data to get distance/duration data and also plot routes on interactive maps. At first, I didn't even know if it was possible to accomplish these things because it's tough getting this kind of data without having to pay for some services, but I'm glad it worked out because I think it's a pretty cool feature of our project.
- I also love that we were able to create a functioning web-app that the user can interact with. This is thanks to the efforts of Jaya and Stancy, who were able to combine the different pieces of our project into a final presentable. We originally didn't know if we would have the time to create such a final product, but I'm happy we were able to do it!

### What are two things you would suggest doing to further improve your project?
- There are some cases in which the web-app either breaks or it shows an output that is not the most elegant way of handling it. I'm specifically referring to the fact that some addresses simply cannot be found using OpenStreetMap and in the case of entering a greater number of days than attractions, the web-app shows an empty map on days where the user doesn't go anywhere. The first issue would have to be addressed either by creating a better function to "clean" the addresses, or by creating dataframes that contain the name of the attraction, since those sometimes work in OSM. For the second issue, we would have to find some way of making the output less specific, since currently the web-app must output a map.
- Another thing that would be cool to implement is the ability to travel to other places outside of LA. Since our project only targets locations in LA, it limits the number of users who can actually use the web-app for travel planning. To make the web-app more accessible, we would probably need to adjust our webscraping method to be more efficient, since it currently takes a long time to scrape all the TripAdvisor locations in LA.

### How does what you achieved compare to what you set out to do in your proposal?
- We accomplished nearly all of our objectives in our proposal, and we also included additional features as well. The only thing we were not able to accomplish was allowing the user to specify what city they wanted to travel to, since webscraping for all possible cities would take too long.

### What are three things you learned from the experience of completing your project? Data analysis techniques? Python packages? Git + GitHub? Etc?
- I learned how to use a bunch of different Python packages, such as Geopy, Folium, and Polyline. I think I got pretty good at figuring out how to use them from reading the documentation.
- I got better at using Git/GitHub for version control.
- I learned how to set realistic goals and think in an agile mindset.
- I got valuable experience working with a team on a long-term project.

### How will your experience completing this project will help you in your future studies or career? Please be as specific as possible.
- Through this project, I now have experience taking an idea and bringing it to life. I've learned how to pace myself and set realistic goals, and this is something I think will be useful for any sort of project I take on in the future.
- I also think learning on the fly was something I got better at through this project, which will also be valuable for jobs where I might not know how to do everything beforehand.
- I don't know exactly what my career goals are yet, since I've only just completed my first year in college. I hope that whatever I decide to do, it includes a little bit of Computer Science in it. This project helped me realize that though I might not be completing a CS degree and I might not become a SWE, I still enjoy coding and CS and I want to keep learning.

Thanks to everyone in PIC 16B for a great quarter, and I hope that I can share more classes with you all in the future!

Please check out Jaya and Stancy's blog posts to see their perspective on our group project:
https://jren99.github.io/traveller-project-reflection/
https://stancyzhang.github.io/Reflection-Blog-Post/
