 **********   GET '/'       ***********
  - display Find a dJam Session, and Create a dJam Session buttons


 ***********   GET '/hosts/:id'  ***********
  - shows a particular host profile
  - shows my sessions, friends, previous dJam Sessions I've hosted or used.
  - if I am this host, shows editing options

 ********** POST '/hosts' **********
  - to create new host

 ********** GET '/sessions' **********
  - display list of sessions with filter options:
    - recently created
    - near me (geolocation)
    - hosted by my friends
    - popular now
  - display search bar (session name, host name, id)

 ********** GET '/sessions/new' **********
  - display New Session form + options:
    - Session Name
    - Session Password (optional)
    - Public?
    - Can users repeat
      - if so, how often?
    - populate Session with music from dJam community curated playlists?
    - populate Session with music from local storage?
    - Invite my Facebook friends (or people attending an event)

 ********** POST '/sessions' **********
  - to create new session

 ********** GET '/sessions/:id' **********
 - displays a session
 - if I am the host, displays links to host options, veto options

