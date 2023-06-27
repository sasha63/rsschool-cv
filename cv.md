# Alexandra Asipchuk
![фото](./photo.png)

### About me
System analyst in SKB Kontur. Writing clear and simple reqiurements for developers. Using user story, use cases, BPMN, UML and text.

### Software skills
Confluence, YT, postman, insomnia, slack, git

### Code's examples
```
function solution(number){
  
  const calcDevidedBy3And5 = (number) => {
    
    if (number < 0) return 0;
    
    let sum = 0;
    
    for (let i = 0; i < number; ++i) {
        if (i % 3 === 0 || i % 5 === 0) {
            sum += i;
        }
    }
    
    return sum;
}

return calcDevidedBy3And5(number);
  
}
```
