# Booker Jenkins Execute Shell:
newman run "https://api.getpostman.com/collections/:uid?apikey=APIKEY" \
--environment "https://api.getpostman.com/environments/:uid?apikey=APIKEY" \
--reporters cli,junit \
-reporter-junit-export "newman/BookerTests.xml"

# Trello Jenkins Execute Shell:
newman run "https://api.getpostman.com/collections/:uid?apikey=APIKEY" \
--environment "https://api.getpostman.com/environments/:uid?apikey=APIKEY" \
--reporters cli,junit \
-reporter-junit-export "newman/TrelloTests.xml"
