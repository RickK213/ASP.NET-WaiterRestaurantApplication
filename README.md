<h1>Welcome to Waiter</h1>
<h3><em>Add yourself to the list and avoid the wait</em></h3>
<p>Waiter is an app that allows diners to view and join restaurant wait lists built as my group capstone project for devCodeCamp. Waiter was built in 1 week using ASP.NET MVC5 and Entity Framework. Waiter implements 4 APIs:</p>
<ul>
	<li><strong>Google Maps API</strong> &mdash; <em>for geolocating and searching addresses and displaying maps</em></li>
	<li><strong>Stripe API</strong> &mdash; <em>for processing payments and managing paid subscriptions</em></li>
	<li><strong>Twilio API</strong> &mdash; <em>for sending and receiving text messages</em></li>
	<li><strong>OpenWeather API</strong> &mdash; <em>for getting current weather conditions for use in analytics</em></li>
</ul>
<h3>Waiter's Key Features:</h3>
<h4>For Diners:</h4>
<ul>
	<li>Diners can search for restaurants based on their current location or an address they provide, view the stated and average wait times and "WaitRate" for each restaurant. The "WaitRate" is a rating based on diner satisfaction with actual vs. stated wait times for each restaurant.</li>
	<li>Diners can quickly judge if a wait time is short or long via contextual colors on the map display (i.e. red marker is long wait, green marker is short wait, blue marker is about average).</li>
	<li>Diners can add their party to the wait list with the restaurant they choose.</li>
	<li>Diners receive notification via text message when their table is ready.</li>
	<li>Diners can see their actual wait time vs. stated wait time via text message and reply with a "WaitRate" to rate their experience accordingly. A sample message is "Bel Air Cantina had a table ready for you X minutes earlier than stated. Did you enjoy your wait experience? Reply 'y' or 'n'"</li>
	<li>Diners can view estimated wait times based on historical wait data, day of week and weather analytics.</li>
</ul>
<h4>For Restaurant Managers:</h4>
<ul>
	<li>Managers sign up for Waiter and provide their address so diners can find their restaurant.</li>
	<li>Managers pay for a monthly or annual subscription to Waiter using their credit card.</li>
	<li>Managers can temporarily remove their restaurant from search results if they are on vacation or under construction.</li>
	<li>Managers set the grace period (in minutes) before a diner is considered a "no-show" and they are removed from the wait list.</li>
	<li>Managers set the number of people on the wait list ahead of each diner before they are sent a notification that their table is nearly ready.</li>
	<li>Managers can view how many table visits their restaurant had on a particular day, how many were added at the host stand, and how many were added via Waiter. This information is displayed in a convenient bar chart.</li>
</ul>
<h4>For Restaurant Employees:</h4>
<ul>
	<li>Employees can easily update the wait list &amp; wait time from the host stand.</li>
	<li>Diners are automatically removed from their wait list due to a no-show after the restaurant's grace period expires.</li>
	<li>Employees can easily notify customers via text when their table is available.</li>
</ul>
<p>To view a demo of Waiter, visit <a href="http://www.rickkippert.com">rickkippert.com</a></p>