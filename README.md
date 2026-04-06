Purpose:
Maps /swipe URLs to BetHero lobby iframe.

Base:
https://jackpotcityswipes.ca/herolobby/

Rules:
- lobbyId → path segment
- invitedBy → query param

Examples:
```
/swipe?lobbyId=UUID/join
→ /herolobby/UUID/join

/swipe?lobbyId=UUID/join&invitedBy=UUID
→ /herolobby/UUID/join?invitedBy=UUID

/swipe?lobbyId=UUID/results
→ /herolobby/UUID/results
```
