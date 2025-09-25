# first-repository
random name generator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script> 
    
    rand=Math.random()
    
    if(rand<0.33){
        first="Crazy"
    }
    else if(rand>=0.33&&rand<=0.66){
        first="Amazing"
    }
    else{
        first="Fire"
    }
      rand2=Math.random()
    if(rand2<0.33){
        second="engine"
    }
    else if(rand2>=0.33&&rand2<=0.66){
        second="Foods"
    }
    else{
        second="Garments"
    }
      rand3=Math.random()
    if(rand3<0.33){
        third="Bros"
    }
    else if(rand3>=0.33 && rand3<=0.66){
        third="Limited"
    }
    else{
       third="Hub"
    }
    console.log(first+second+third)

    </script>
</body>
</html>
