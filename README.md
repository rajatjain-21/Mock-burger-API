# Mock Burger API


Hello everyone! In this, I have made my own mock version of an API and deploy it onto **heroku** in just a few easy steps. This is a super stripped down version, so has no routing/controllers. This is thanks to the https://github.com/typicode/json-server​ package. Where you can get a mock REST API with zero coding in less than 30 seconds.

For those of you wishing to check it out live visit [here](https://dummy-burger-api.herokuapp.com/)

A lot of you are wondering if you can interact with this database. Yes you can. You can make GET, POST, PUT, DELETE etc requests to it. You can even get an individual burger. For example if I want to get the Tribute Burger, which has an ID of 0, I would write: 

```
fetch('https://dummy-burger-api.herokuapp.com/')
  .then(response => response.json())
  .then(data => console.log(data));
```

* Twitter: https://twitter.com/rajat_codes
* Instagram: https://instagram.com/javascript_to_the_rescue