# Iryna Shyrshova

<img src="./images/photo.jpg" alt="photo" style="width:300px;height:auto;">

## Personal information

**Address**: Ukraine, Kharkiv

**Email**: renniesheppard@gmail.com

**Phone**: (+380)66-823-53-99

**LinkedIn**: [iryna-shyrshova](https://www.linkedin.com/in/iryna-shyrshova-27968880)

**GitHub**: [Rennie](https://github.com/IRIKA)

**Discord**: renniesheppard

---

## Summary

I'm C# .NET full-stack developer. I live and breathe programming. I develop and gain new knowledge. My goal is to find a great team and an interesting project.

---

## Key skills

- OOP, SOLID and Clean code principles
- Languages: C#, Angular, JavaScript, TypeScript
- Markup: HTML, CSS
- .NET Technologies: ASP.NET MVC/WebAPI, Entity Framework, LINQ
- Databases: Microsoft SQL Server, PostgreSQL, MySQL, MongoDB
- Unit and Integration Testing
- Demonstrated ability to: design REST API, create features for users with varying levels of access, design interface function
- Software Development Methodologies: Kanban, SCRUM

---

## Soft skills

- great team player, effective communicator and problem solver
- strong analytical skills, responsible and goal-oriented
- self-organized and have good time management skills
- have excellent active listening skills
- resistant to stress and conflicts

---

## Code examples

The function formats the date with/without time, with/without time zone.

**Accepts parameters**: **date, onlyDate, default is False, withTimeZone, default is False.**

**Returns**: **formatted date.**

```
function getFormatedDate(date, onlyDate = false, withTimeZone = false) {
    let year = date.getFullYear();
    let month = (date.getMonth() + 1).toString();
    let day = date.getDate().toString();
    let formattedDate = `${year}-${month.padStart(2, '0')}-${day.padStart(2, '0')}`;
    if (onlyDate) {
        return formattedDate;
    }
    let hour = ("0" + date.getHours()).slice(-2);
    let minute = ("0" + date.getMinutes()).slice(-2);
    let second = ("0" + date.getSeconds()).slice(-2);
    if (withTimeZone) {
        let timezone = date.getTimezoneOffset() / 60;
        let formattedTime = `${hour}-${minute}-${second}`;
        formattedDate = `${formattedDate}-${formattedTime}-GMT${timezone}`;
    } else {
        let ms = ("00" + date.getMilliseconds()).slice(-3);
        formattedDate = `${formattedDate}T${hour}${minute}${second}.${ms}`;
    }
    return formattedDate;
}
```

---

## Work experience

### University program

**Title**: "Catch moment"

**Description**: An online platform for storing and viewing photo albums. You can view photos uploaded by other members of the platform or create your own albums. You can rate your favorite photos by liking them.

### EPAM SYSTEMS

**Title**: "Game store"

**Description**: An online store selling computer games. Here you can find games of any genre suitable for different platforms. You can also read customer reviews and share your own impressions.

### EPAM SYSTEMS

**Title**: "Recipe Platform Project"

**Description**: An online platform where users can share and discover new recipes. The platform allows users to upload their own recipes, browse and search for recipes uploaded by other users, rate and review recipes, and create a list of favorite recipes.

---

## Education:

2001-2006 Kharkiv Institute of Finance KNTEU. Speciality: finance

---

## Additional qualification:

- C# courses
- Angular courses

---

## Languages:

- Ukrainian - Native speaker
- English - B1
