Creating a bot that generates an interesting podcast about a specific topic that it is given
for long drives.

The podcast episode should be about 30 minutes in length. The topic will be anything. 

Will use the huggingface microsoft VibeVoice api https://github.com/microsoft/VibeVoice
and python openai library

    TODO: Would be cool to also find an ai sound generator that you could enter a description of a sound effect into or music
            and it would play that as a layered sound or generated effect

Topic ideas: 
    - History
    - Creative Story Telling
    - Science facts
    - Video game lore
    - etc

The podcast will be saved as a file and added to a user's library, kind of like a music listening app, where the user
can come back later to listen to it again if they wish.


If the user enjoys a certain topic, can ask to generate a similar episode of a related or similar topic.

There will be a button for generating a podcast with a prompt:

    - tell me something interesting about ____ time in History
    - tell me a relaxing story about a peaceful adventure
    - tell me all about the development of this scientific fact

The podcasts will be organized into different playlists for the user, creating ease of finding them again later
The users can also share the podcasts with their friends, as all podcasts can be stored in general database of them


Proof of concept could look like the following steps:

1) using python and openai library, we can generate a script for 30 minutes of interesting story telling about a topic of 5 minutes
    to start

2) we use chat gpt to write a script. then we use a voice ai to read that script. 

3) we save the voice file and the script that it read in a database or somehow.
