<h1>Welcome to Waiter</h1>
<h3><em>Add yourself to the list and avoid the wait</em></h3>
<p>Waiter is an app that allows diners to view and join restaurant wait lists built as my group capstone project for devCodeCamp. Waiter was built in 1 week using ASP.NET MVC5 and Entity Framework. Waiter implements 3 APIs:</p>
<ul>
	<li><strong>Google Maps API</strong> &mdash; <em>for geolocating and searching addresses and displaying maps</em></li>
	<li><strong>Stripe API</strong> &mdash; <em>for processing payments and managing paid subscriptions</em></li>
	<li><strong>Twilio API</strong> &mdash; <em>for sending and receiving text messages</em></li>
	<li><strong>OpenWeather API</strong> &mdash; <em>for getting current weather conditions for use in analytics</em></li>
</ul>
<h3>Waiter's user stories:</h3>
<ol>
	<li>As a diner, I want to be able to search for restaurants based on my current location or an address I provide (Google Maps API), view the stated and average wait times and "WaitRate" for each restaurant. The "WaitRate" is a rating based on diner satisfaction with actual vs. stated wait times for each restaurant.</li>
	<li>As as a diner, I want to be able to quickly judge if a wait time is short or long via contextual colors on the map display (i.e. red marker is long wait, green marker is short wait, blue marker is about average).</li>
	<li>As a diner, I want to be able to add my party to the wait list with the restaurant I choose.</li>
	<li>As a restaurant manager, I want to be able to sign up for Waiter and provide my address so diners can find me.</li>
	<li>As a restaurant manager, I want to be able to pay for my monthly or annual subscription to Waiter using my credit card (Stripe API).</li>
	<li>As a restaurant manager I want to be able to remove my restaurant from all search results if my restaurant is under construction or on vacation, etc.</li>
	<li>As a restaurant manager, I want to be able to cancel my Waiter subscription.</li>
	<li>As a restaurant employee, I want to easily update the wait list from the host stand.</li>
	<li>As a restaurant employee, I want to have diners removed from our wait list due to a no-show after our restaurant's grace period expires.</li>
	<li>As a restaurant manager I want to be able to set the grace period (in minutes) before a diner is considered a "no-show" and they are removed from the wait list.</li>
	<li>As a restaurant employee I want to easily update our current wait time.</li>
	<li>As a restaurant employee, I want diners to be notified automatically when their table is nearly ready.</li>
	<li>As a restaurant manager, I want to be able to set the number of people on the wait list ahead of each diner before they are sent a warning notification.</li>
	<li>As a restaurant employee, I want to easily notify customers via text (Twilio API) when their table is available.</li>
	<li>As a diner, when I receive my notification that the my table is ready, I also want the option to click a link for directions (Google Maps API) to the restaurant.</li>
	<li>As a diner, I want to be able to see my actual wait time vs. stated wait time via text message and reply with a "WaitRate" to rate my experience accordingly. A sample message is "Bel Air Cantina had a table ready for you X minutes earlier than stated. Did you enjoy your wait experience? Reply 'y' or 'n'"</li>
	<li>As a diner, I want to be able to view estimated wait times based on historical wait data, day of week and weather (OpenWeather API).</li>
	<li>As a restaurant manager, I want to be able view how many table visits we had on a particular day, how many were added at the host stand, and how many were added via Waiter. This information is displayed on my manager dashboard in a convenient bar chart.</li>
</ol>
<p>To view a demo of Waiter, visit <a href="http://www.rickkippert.com">rickkippert.com</a></p>