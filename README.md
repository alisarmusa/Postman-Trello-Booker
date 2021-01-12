# Booker Jenkins Execute Shell:
newman run "https://api.getpostman.com/collections/13710890-786edaa2-945d-4dd3-a684-72a63d833044?apikey=PMAK-5ffb4c6af1a6050052d6a69d-1a125ef088964235a146ad78ef221a42d5" --environment "https://api.getpostman.com/environments/13710890-24a1451c-a387-4679-b376-baaf8b6f0b8c?apikey=PMAK-5ffb4c6af1a6050052d6a69d-1a125ef088964235a146ad78ef221a42d5" --reporters cli,junit -reporter-junit-export "newman/BookerTests.xml"

# Trello Jenkins Execute Shell:
newman run "https://api.getpostman.com/collections/13710890-25be40ca-d77d-41ab-8c5a-3b85eb563b75?apikey=PMAK-5ffb4c6af1a6050052d6a69d-1a125ef088964235a146ad78ef221a42d5" --environment "https://api.getpostman.com/environments/13710890-1bd7a224-0c40-4232-b747-26d4308fec0d?apikey=PMAK-5ffb4c6af1a6050052d6a69d-1a125ef088964235a146ad78ef221a42d5" --reporters cli,junit -reporter-junit-export "newman/TrelloTests.xml"
