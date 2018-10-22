Lately, Spotify has been outputting my username as a specific number (probably meaning that is my ID) whenever I check my profile
or when I'm playing my Playlists and the service tells me who created it.

Assuming that Spotify runs these validations and processes in the python language...
```python
class User:
  ....
  name= John Doe

```
and assuming that my ID is the name of my object (meaning that the problem stems from omitting the output syntax of classes),
Spotify should output the following when it is necessary:
```python
print(User.name) #123456789.name instead of 123456789

```
This is just a hypothesis from my part but I hope that this is somewhat relevant to that "issue"
