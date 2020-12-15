# devtools403

Run `npm start`, open Chrome's network tab in DevTools and refresh to see that sometimes Chrome reports 304 and sometimes 200, but Wireshark confirms that the server always sends 304.

Depending on your luck, you might need to refresh a lot (over 10 times) to see this, sometimes you see it immediately.
