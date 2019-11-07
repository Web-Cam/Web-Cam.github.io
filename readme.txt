This webpage is supposed to demonstrate a basic concept of ordering something.
In this case, the items being showcased to order are food that is supposed
to be delivered to the customer's house.

On the first page the home page is showcased which shows what items can be bought.
Under each item shows the name and how much is currently being ordered.
Clicking the add button increases the quantity of how much is being ordered,
and it also allows the remove button to be used.
The remove button decreases the amount of the item above it.
If the item counter reaches 0, then its remove button goes away unless it has at least
one item.

The cart button takes the user to the next page to review what they selected to buy.

All of the buttons have some some customized effects added to them from CSS to provide
a bit flair. The main reason I used them was so I can get a better feel for some
CSS features.

The next page is shopping cart page and it gives the option to either go back to home 
page, which clears the user's selected amounts, or proceed to checkout.

The fieldset feature was also implemented to provide a somewhat better look.

The checkout page uses HTML form to receive the user data.
Submitting the form takes the user to the final page which confirms their order.

The first two pages doesn't use HTML to recieve data as I wanted to try some other
features with CSS, but the Checkout page does use forms.

It would have been more efficent for the final page to use PHP when trying to retrieve
the user data, but wasn't able to at the time to setup a PHP client and server, so 
I used javscript to retrieve the data and turned to data into strings that was trimmed
so it can spit out information showing it was recieved. The only thing shown as proof
of retrieval was the user's first name.