
# Hotel Assist ChatBot

- I am working on the opportunity area in the Lifestyle domain by creating a ChatBot Assistant.
- Will make use of the **Azure QnA Maker** and create an initial Knowledge Base of frequently asked questions regarding hotel (chain).
- The ChatBot will provide customers will answer their questions,
  - Regarding accommodation - examples: early check-in or late check-out possibility, having extra guests in the room, cot/crib for the child.
  - Regarding Guidance - directions/map to the hotel, contact the help desk (number pops up)
  - Regarding GiftCards - buying gift points, redemption of giftcards
  - Contact - customer support, help desk or brand content managers (for influencers)
- Guests will get their answers in a conversational fashion in a professional fashion since QnA Maker provides the Personality feature.
- Chatbot will be added to a webpage, allowing it to be integrated with the Hotel Website. 

## Azure Services Used

We start by creating a Knowledge Base of question answer pairs on **QnA Maker**. Which is to be published and connected to a bot on **Azure Bot Service**. 

![This is an image](https://i.imgur.com/PXhzjK9.png)

We then embedd this bot to an <iframe> in an HTML Webpage to create a webpage. The benefit of having it on a webpage is that it can be easily added to an existing Hotel Website. 

We make use of **Azure Static Web Apps** Service to deploy our static webpage showcasing the Project Demo. 

![](https://i.imgur.com/Yc1zxv5.png)

**Azure Website Link** - https://ashy-island-00e80650f.1.azurestaticapps.net/

## Screenshots

Here the guest starts by writing Hello and the ChatBot greets back the user. The guest is replied with the Check-Out time of the Hotel when she asks "What time should I leave the hotel room?" 

![checkin qna](https://i.imgur.com/3qtJ8mx.png)

The guest can ask about complimentary breakfast and be informed of the breakfast menu. They can also ask of lunch and dinner room offerings and be guided to contact Room Service.

![breakfast](https://i.imgur.com/D5tSFV9.png)

## Example Questions that can be answered: 

**Accommodation:**

- Will I be charged for extra guests occupying my room?
- Can the hotel supply a cot or crib for my room when I travel with children?
- What is the check out time of the hotel?
- When can I check in to my room?
- How do I request an early check-in or late check-out with the hotel?
- I want my room cleaned up?
- Can I reserve more than one room at the time of booking?
- I want to contact the Help Desk? 

**Food:**

- Do you offer complimentary breakfast?
- What are the breakfast timings?
- What do you have for breakfast?
- I want food delivered to my room?
- What can I have for lunch/dinner?

**GiftCards:**

- Do you have any loyalty program?
- Do you offer GiftCards?
- How many points do I get for a night of stay?
- How do I check the balance on my GiftCard?
- How do I redeem my giftcard?
- Can I send my points to someone else?

**Pricing and Discounts** 
 
- Can I get a discount?
- Do you offer any student discount?
- What kind of prices do you offer?
- I am having trouble making an online reservation. Is there a toll free number I can call? 

**Brand Content and Other Information** 
- I am an influencer how can I contact the brand manager?
- I create brand content on youtube or tiktok or instagram?
- Is there a minimum age requirement to reserve a hotel room?
- How can I find the information I need?
- Where can I find maps and directions to my hotel?

## GitHub Pages 

The website is also hosted on GitHub Pages in case credit for Azure runs out. 
GitHub Pages: https://aryancr111.github.io/HotelAssist/

## Benefits 

- The ChatBot is available twenty four seven and easier to reach out to for answers to at any time of the day. 
- It faciliates self-service. A research shows that millenials would rather use a chatbot rather then talk to an individual. 
- Guests can get information that they need quickly with to the point answers. They needn't read up unecessary information or wall of text FAQ pages to get that one answer they need. 
- A ChatBot can server multiple guests at a time unburdening the Hotel HepDesk staff. 
- A bot is not subject to mood swings and human errs. It will answer professionally even when a user types "I hate you" in the message box since we added the *Professional* personality via Azure QnA Maker. 
- The NLP enabled chatbots can easily conduct sentiment analysis on the receiver’s data and can reply accordingly.
- Future scope of languages to be added across global hotel chains since Azure QnA Maker is available in 50 languages.  

