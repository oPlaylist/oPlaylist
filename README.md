oPlaylist
=========

The official Open Playlist Protocol specification.

Abstract
=======
Music services has their own playlist services. The problem today is that when people switch music service they lost all playlists.
I want to create a specification of a open protocol for playlist storage.

Resolvers
=====
Any people can host an own playlist service, an Open Playlist Server. The server implements an REST api according to the following specification

    GET /users/<user_id> <-- Returns the user id
    GET /playlists/playlist <-- Returns the XSPF specification of the playlist
    GET 
