Project description 2

Homepage:

The homepage will be simple. I like the design of copy.AI or gravity write. You can use their design. Here’s the website description:

“The First Free, Unlimited Halal AI Chat Assistant”

🚀 Halal AI Chat is a free, unlimited AI assistant that lets you chat with the world’s best AI model

🔹 Ethical & Halal AI – AI-generated content is filtered to align with Islamic principles.
🔹 Unlimited Free Access – No credit card or payment required. Just chat and generate.
🔹 Share & Learn – Save, organise, and share AI-generated Islamic content.

💡 Coming Soon: Faster AI, Audio, Video, Image, and specialised tools for specific niches.

👉 Start Chatting for Free Now!

Here’s a breakdown of our features:

**Functionality 1: we are going to use mistral which is an open source LLM model like mistral and we are going to use the 7B version I guess[ in case it is going to have five categories of tools and they are blog tool to YouTube tool, research tool, programming tool, general tool ]


When a new user signs up, they should automatically receive 20 free credits. These credits are given for opening a new account and allow users to create outputs using any of the blog, YouTube, or programming tools. Users can manually edit their outputs as much as they want, but if they want the AI to edit the response based on edit requirements, they’ll need another credit. After signing up, users will receive a notification about the free credits. Once used up, users can earn more credits, but more information about this is available on the pricing page. If users try to use any tool after exhausting their credits, they’ll receive a message indicating that they need to earn or renew credits. To do this, they should visit the pricing page for a detailed explanation.

Let’s move on to the website pages.

Here’s a quick overview of the pages I need you to design:

**Homepage:** I want a clean and professional homepage, but I’m open to ideas. Copy.AI and Gravity have great designs that I like. If you can follow their lead, that would be awesome. The homepage should include a section for our available features, such as our powerful AI models and upcoming tools. This information is available in the website description I sent earlier.

**About Us:** Create a page with a website description as content. Feel free to add other relevant information.

**Contact:** Design a standard contact page in case make a contact for and I am going to use supabase for this 
**Notifications:** Build a standard notification page with a matching colour palette to the website. I am going to use supabase for this .

**Profile:** just design a standard profile page. Add a menu to all pages, including this one. Some fields will be automatically filled in with registration information.

**Pricings:** it should only include the text below

We don’t follow traditional pricing. Instead, you’ll share our website and earn credits. You can use these credits to create content.

Here’s how it works:

Let’s say there are two users, user1 and user2. User1 shares our website with a unique link. When user1 gets this link, they get one credit because someone signed up using their link.

If user2 earns credits by sharing or watching ads, user1 gets the same amount of credit automatically. For example, if user2 shares with five people and gets five credits, user1 gets five credits too, even though they didn’t do anything. This is because user2 came from user1’s referral link.

One credit can generate content from any of our tools or platforms, like a token for creating a blog, video, or audio. You can have one output from any tool under any category.

Share our website with your unique link to earn unlimited credits and create unlimited content daily.

We aim to build a community of Halal content creators. Please share our website to help you find and create Halal information.

 dashboard:

Here’s an example dashboard with four sections:

- Total credits for generating content.
- Credits earned by referring the website.
- Credits earned by watching ads.
- Recent activity, including a list of content generated in the last two months.

The menu should be on the right side of the page and match the homepage’s colour palette.



Build a standard authentication page with best practices. If the page’s colour palette matches the website’s, do that for consistency. I’m using the free supabase authentication service.

Enable cookie settings and add terms and conditions and a privacy policy page. People will agree to them while signing up. Write the content in the terms and privacy policy pages, aligning it with my website. If you need more directions, create standard pages and follow best practices. Also add language changing option.

The chatbot interface can be simple and use a friendly . You can make the design  

Include input fields like a negative box for users to specify what they don’t want in the generated content, a word range (e.g., 1500 to 2500), and a tone (e.g., excited, professional). Add any other input fields you think are beneficial. Aim for maximum user satisfaction by providing all possible input fields so users can customise the content. Also, include output fields as desired, but keep in mind that the tool will generate text, so there should be enough manual editing options in the interface after generation about manual editing people is going to click on the content and they will be taken to a separate page which will be like Google Docs for editing the content. In case there will be a tool selection page and people can access that using the menu and in that page people can find the five categories of tools . People can choose any of the tool and then he will be redirected to that  tool interface and then he will start chatting and generating. There will be  five types of tools and they are blogging tool ,YouTube tool, research tool, developer tool, general tool . As you can understand all the tools interfaces will have some similarities like the colour palette as they belong to the same website but yes, they will have different also because they are different. 

Now, let’s move on to the back-end functionalities.


1. In the dashboard description, I mentioned three top sections and one for user credit sharing. Let’s say two users, user1 and user2, share the website. If user1 gets a unique link from user2, they get one credit for a user signing up. If user2 earns credits by sharing or watching ads, user1 gets the same. For instance, if user2 shares to five and gets five credits, user1 gets five without effort. One credit generates one output from any tool, like a blog, paragraph, story, or research paper. I need a mechanism for this. Let me know if you need external APIs or anything. It’d be better if you built it yourself.

2. We are going to use mistral from hugging face and I have gave the token for hugging face in the required file so you should check it and continue. 


3. Recent activities.. You may see in the dashboard and also in the chatbot interface that there is an option to see the Recent activities  and the Recent activities  should be saved so I need that mechanism at the back end also.

4. File Management. There should be an option in the menu and also after anyone generates any content from the tools he should see this option and it is called file management( at the menu) or save ( at the tool/chatbot interface) . He should be able to save the work or the content he generated and he should be able to create folders and files under these folders and he will also be able to create file without any folder and it is like a standard file manager or I should say not complex but yeah it's like a normal file manager. I also want a search engine there, which will help the user to search among the files and folders. There should be also filters in the search engine. In case he will use the filter to search only folders or to search only files across the whole file manager functionality ( Suppose someone searched for SS. And if he uses a filter to only see the files then he should see the file SS which is under a folder and he will also see any file which is close to his search keyword even if it is not under any folder. )  And user should be able to download a file or a folder separately. and if he wants to download all the files and folders then he will have an option in the dashboard called Export to CSV and if he downloads files separately as a file then he will have several options like PDF or PPT.


5. The chats or the conversations should be shareable and people should be able to mark some of them as favourite as they wish. You should handle this in both places frontend  and back end.


In short  this is like a simple website like ChatGPT but it will generate the content which is halal by the rules of Islam. For example, if someone enters a question and hits the create or  generate button then the AI will check the prompt that if it is halal or not if the user asked to generate something Haram then it will show the user a beautiful notification that your given prompt is Haram so I can't generate it and it will highlight the point that why it is Haram with a good explanation and the text highlighting where the problem caused . And when it will generate the content  It will also make sure that it is generating content which is halal by the rules of Islam. So in case there will be two layers of AI, actually I mean kind of that. First someone will give the prompt and the AI will validate it and when it will be authorised or I should say when  it will be validated then he will give the response. 



The  ai should be able to create files, pies, charts and tables as needed


6.  Another thing is that I guess I told you before that I want a menu and that menu should be in the top right corner of the navigation bar and visible in all the pages and this man who will contain all the pages of the website now there is a thing called dynamic URL routing. What I want is that there will be only three pages public which are about us ,contact us, pricing. Now suppose someone came to the homepage and he's not logged in and he clicked on the menu then he saw all the pages and he clicked on profile. Then he will be redirected to the login page and after logging in he will be redirected to the profile page directly.. now if he don't have any account then he can open one by signing up using email and password and the login page will contain link to the signup page and the signup page will contain link to the login page which is very standard. 

And yes, this is the hugging face access token or API key whatever I tell it               HUGGING_FACE_API_KEY=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

