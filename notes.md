ok this one is fun.

few days ago, the infosec community had fun with OpenIA (https://chat.openai.com/chat), lot of pep send ctf problem and such, and the results were actually quite good .

so i tried to ask for regular expression for basic vulnerability like command injection, local file include.

![a1](https://user-images.githubusercontent.com/28728543/205108599-f9d13c07-ce75-421e-acfb-b24f46b23c51.png)


and OMG that was so good, plus github just implemented the ability to search code with regular expression, so here we are :)

for this one i was using :

```
/system\s*\([^)]*[^\s]*\$_GET\[[^"')]*/ 
```

and look at that, first fucking page

![image](https://user-images.githubusercontent.com/28728543/205108883-de1701ed-36bf-471a-afae-44a1ddced7a2.png)

![image](https://user-images.githubusercontent.com/28728543/205108938-e2861f60-0822-4fa7-9e84-0774eb2a9a17.png)

so shodan this 

![image](https://user-images.githubusercontent.com/28728543/205109004-926feb25-3b1e-4712-b730-3537f174850e.png)

and tadaaa ..

![image](https://user-images.githubusercontent.com/28728543/205109254-9a4cd1f1-f96d-4af6-82e1-5ba636074921.png)

![image](https://user-images.githubusercontent.com/28728543/205109586-6d3af156-56a6-4064-a017-a9ae2b54a4c4.png)

