Defaultizer
===

(Please forgive the name)

Just a little javascript function to make default parameters a lot easier. The example should hopefully speak for itself:


    var alert_my_age = d([21], function(age) {

      alert(age)

    })

    alert_my_age()   #=> Alerts 21
    alert_my_age(45) #=> Alerts 45
  
