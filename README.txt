CLAWED BY BROWN WEBSITE — QUICK START

CONTACT NUMBER
The website uses only 064 312 3054 for calls/WhatsApp booking requests.

OPEN THE WEBSITE
1. Download and extract Clawed_By_Brown_Website.zip.
2. Open the extracted folder.
3. Double-click index.html to preview in your browser.

EDIT WITH NOTEPAD++
1. Right-click index.html.
2. Choose Edit with Notepad++.
3. Make your changes and press Ctrl+S.
4. Refresh the browser to see your changes.
Keep the images folder beside index.html.

EDIT AVAILABLE TIMES
In index.html, find:
const availableTimes = ["09:00","10:00","11:00","12:00","13:00","14:00","15:00","16:00"];
Change these to your actual available times, using 24-hour format, e.g. "09:30".
To block a date, add it to blockedDates using YYYY-MM-DD format, e.g. "2026-12-25".

EDIT PRICES
In index.html, search for the service name or price (for example, R110) and update the visible menu price and the matching option in the booking form. Keep the prices in both places consistent.

PUBLISH ONLINE FOR FREE (GITHUB PAGES)
1. Create/sign in to a GitHub account at https://github.com.
2. Create a new public repository, e.g. clawed-by-brown.
3. Upload index.html and the entire images folder (not just index.html).
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select the main branch and / (root), then Save.
7. Wait a few minutes. GitHub will show the published website link on the Pages screen.
8. Open that link and test the booking form and images.

IMPORTANT
The booking form opens WhatsApp with the customer's request. It does not save appointments or automatically block a time after somebody chooses it. Confirm appointments personally. The time slots currently shown are examples and should be changed to the technician's real availability.
