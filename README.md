Our Idea: 
App name: Campus Swap
Concept: Campus Swap is a university-exclusive marketplace that allows students to buy, sell, and exchange items with other students on campus. Students can list items they no longer need and discover affordable second-hand products offered by their university community.
Purpose
To make student essentials more affordable, reduce waste by giving unused items a second life, and make it easier for students to connect when trading items.
Target users
 University students who want to buy, sell, or exchange items such as textbooks, calculators, stationery, electronics, clothing, and accessories.
The real problem
Textbooks and dorm items are expensive and are often used for only one semester. Students end up overpaying at bookstores, or posting in scattered WhatsApp and Facebook groups where listings get buried, prices are unclear, and there is no way to know if a seller is trustworthy. CampusSwap puts everything in one trusted, searchable place.

Our Features
1.Listings: Create, edit, and delete an item with photos, price, condition, and category
2.Search and Filters: Find items by keyword, category, and price range
3.Chat:  Message a seller or buyer inside the app to arrange a deal
4.Ratings: Rate a seller or buyer after a deal and read others’ ratings
5.Items: Bookmark items and view them later in one page
6.Price Alerts: Get notified when a saved item drops in price or a wanted item is listed
7.Swap offers: Offer one of your items in exchange for another student’s item, and accept or decline offers
8.Accounts and Profiles: Sign up with a university email, log in, and edit your profile

Feature 1: Listings
By Hana Ahmed: 19001636
User story 1:
As a graduating student, I want to add several photos to my listing so that buyers can see the real condition of the item.
Acceptance criteria:
•	I can upload up to 5 photos, and they appear in the listing as a swipe able gallery.
•	Uploading a file that is not an image shows “Only image files are allowed”.
•	Trying to upload a sixth photo shows “You can add up to 5 photos”.

User story 2:
As a seller, I want to mark my item as sold so that buyers don’t contact me about it anymore.
Acceptance criteria:
•	Tapping “Mark as sold” changes the listing’s status to “Sold” and removes it from search results.
•	The sold listing stays visible in my profile under “Sold items”.
•	Tapping “Mark as sold” on a listing that is already sold is not possible, because the button is hidden.

Feature 2: Search and Filters
By Lilly Ramy: 20003488
User story 3:
As a student, I want to sort results by price or newest first so that I can find the best deal fast.
Acceptance criteria:
•	Choosing “Price: low to high” shows the cheapest items first.
•	Choosing “Newest” shows the most recently posted items first.
•	If the result list is empty, the sort options are hidden and “No items found” is shown.

User story 4:
As a student, I want to filter by item condition so that I only see items in the state I’m willing to buy.
Acceptance criteria:
•	Selecting “Like new” shows only items marked “Like new”.
•	I can select more than one condition at the same time, and the results include all of them.
•	If no items match the selected conditions, the page shows “No items found” with a “Clear filters” button.

Feature 3: Chat
By 
User story 5:
As a buyer, I want to send a photo in a chat so that I can ask about a specific part of the item.
Acceptance criteria:
•	Tapping the attachment icon lets me pick a photo, and it appears in the conversation after sending.
•	A file larger than 5 MB is rejected with “Photo is too large”.
•	A file that is not a photo is rejected with “Only photos can be sent”.

User story 6:
As a user, I want to block someone who sends unwanted messages so that I feel safe using the app.
Acceptance criteria:
•	Tapping “Block” in a conversation asks for confirmation, then stops that person from messaging me.
•	The blocked person cannot see that they were blocked and cannot start a new chat with me.
•	Tapping “Unblock” on my blocked list restores their ability to message me.

Feature 4: Ratings
By 
User story 7:
As a seller, I want to rate a buyer after a deal so that other sellers know if the buyer is reliable.
Acceptance criteria:
•	After marking an item as sold to a buyer, I can give that buyer 1-5 stars.
•	A rating is only allowed for deals I took part in, so the rating option does not appear for other users.
•	Submitting without choosing stars shows “Please select a rating”.

User story 8:
As a buyer, I want to write a short comment with my rating so that I can explain my experience.
Acceptance criteria:
•	I can add a comment of up to 200 characters when rating.
•	The comment appears on the seller’s reviews page with the date.
•	Typing more than 200 characters shows “Comment is too long” and blocks submission.

Feature 5: Saved items
By 
User story 9:
As a student, I want to organize my saved items into folders so that I can separate items for different courses.
Acceptance criteria:
•	Tapping “New folder” and entering a name creates an empty folder on my Saved page.
•	I can move a saved item into a folder, and it appears there.
•	Creating a folder with an empty name shows “Enter a folder name”.

User story 10:
As a student, I want to remove several saved items at once so that I can clean up my list quickly.
Acceptance criteria:
Selecting multiple items and tapping “Remove” asks for confirmation, then removes them all.
The removed items no longer appear on the Saved page.
Tapping “Remove” with no items selected shows “Select at least one item”.

Feature 6: Price alerts
By Retaj Mostafa: 19001253
User story 11:
As a student, I want to choose which price drop triggers my alert so that I’m not notified about tiny changes.
Acceptance criteria:
•	I can set an alert to trigger when the price falls below an amount I enter.
•	When the price falls below that amount, I receive a notification.
•	Entering a target price of zero or a negative number shows “Enter a valid price”.

User story 12:
As a student, I want to see and manage all my active alerts in one place so that I can stop ones I no longer need.
Acceptance criteria:
•	The alerts page lists each alert with its item name and target price.
•	Tapping “Delete” on an alert removes it and stops its notifications.
•	If I have no alerts, the page shows “No alerts yet”.

Feature 7: Swap offers
By Zeina Mohamed: 20005155
User story 13:
As a student, I want to add a cash top-up to a swap offer so that an uneven trade can still work.
Acceptance criteria:
•	When sending a swap offer, I can add an optional extra amount in EGP.
•	The other student sees the swap items and the extra amount in the offer.
•	Entering a negative amount shows “Enter a valid amount”.

User story 14:
As a student who sent an offer, I want to cancel my swap offer so that I can change my mind before it is accepted.
Acceptance criteria:
•	Tapping “Cancel offer” on a pending offer asks for confirmation, then removes it.
•	The other student is notified that the offer was cancelled.
•	An offer that has already been accepted cannot be cancelled, and the button is hidden.

Feature 8: Sign in
By Mariam Hamdy: 19001042
User story 15:
As a user who forgot my password, I want to reset it by email so that I can get back into my account.
Acceptance criteria:
•	Entering my registered email and tapping “Reset password” sends a reset link to that email.
•	Entering an email that is not registered shows “No account found with this email”.
•	After opening the link, a new password shorter than 8 characters shows “Password must be at least 8 characters”.

User story 16:
As a seller, I want to see my own profile with my listings and rating so that I can check how others see me.
Acceptance criteria:
•	My profile shows my name, photo, faculty, and average rating.
•	It lists all my active listings below.
•	If I have no listings, the profile shows “You haven’t posted anything yet”.

What makes Campus swap different?
A Feature That Makes Campus Swap Different Swap Without Spending: In addition to selling items for money, students can offer an item in exchange for another item. For example, one student could offer a statistics textbook in exchange for another student's scientific calculator. Students can send and accept swap requests through the app
<img width="468" height="637" alt="image" src="https://github.com/user-attachments/assets/18ea64cc-c9d7-456d-a99b-54b8271c9c29" />
# ICA_Project
