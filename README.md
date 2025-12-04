### *Effort develops ability.*

>* Embrace Challenges
>* Value Effort Over Innate Talent
>* Seek and Learn from Feedback

```js
    const alexProfile = { 
      name: "Alex",
      wishes: "Have a beautiful day!", 
      hobbies: ["reading", "spending quality time", "learning new things"],
      contact: "test@test.test"
    };

    alexProfile.greeting = `Hi Friends! You can call me ${alexProfile.name}.`;

    const htmlOutput = `
      <p>--- ${alexProfile.name}'s Introduction ---</p>
      
      <strong>${alexProfile.greeting}</strong><br>

      I love:<br>
      <ul>
        <li>${alexProfile.hobbies.join('</li><li>')}</li>
      </ul>

      Feel free to contact me at: <strong>${alexProfile.contact}</strong><br>

      <br>
      <em>${alexProfile.wishes}</em><br>
    `;
    
    document.getElementById('profile-output').innerHTML = htmlOutput;
```
