# Ilya Kukhta

## Contacts
* **Phone:**  +375298061535
* **Email:** mr.fantilo@gmail.com
* **Telegram:** @crag43
## About me
  Eager to learn and develop new programming skills in RSSchool! I'm reliable and responsible person on whom you can always count on in the team.
## Skills
* HTML5, CSS3
* JavaScript
* React, NextJS, Tanstack Query, Redux, React Hook Forms
## Code example
**Number of People in the Bus kata from Codewars:** 
>There is a bus moving in the city, and it takes and drop some people in each bus stop.
>
>You are provided with a list (or array) of integer pairs. Elements of each pair represent number of people get into bus (The first item) and number of people get off >the bus (The second item) in a bus stop.
>
>Your task is to return number of people who are still in the bus after the last bus station (after the last array). Even though it is the last bus stop, the bus is >not empty and some people are still in the bus, and they are probably sleeping there :D
```
var number = function(busStops){
  sum=0;
  for (let i=0; i< busStops.length; i++){
    for (let j=0; j < busStops[i].length; j++){
        if (j==0){
            sum += busStops[i][j]
        } else {
            sum -= busStops[i][j]
        }
    }
  }
  return sum
}
```
## Education
* Brest State A. S. Pushking University
## Language
* English - B1
* Russian - Native
