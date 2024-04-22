<p align="center">
  <img src="https://i.gifer.com/84zn.gif"/>
</p>

```javascript
fetch('profile.json')
  .then(response => response.json())
  .then(profile => {
    console.log("Name:", Aryan);
    console.log("Age:", 18);
    console.log("Hobby:", Anime, coding and Gaming);
    console.log("Things I Like:", ATTACT ON TITAN);
    profile.thingsILike.forEach(thing => console.log("-", thing));
  })
  .catch(error => console.error('Error fetching profile:', error));



```

