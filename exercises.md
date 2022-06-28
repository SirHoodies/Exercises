    function pattern(num){
        var lastNum = ""
        for(i=1;i<=num;i++){
            console.log(lastNum + i)
            lastNum += i + ' '
        }
    }
    console.log(pattern(8));

----------------------------------------------------------------------------------------------------------------------------------------------------------------

    function powerTo(num,power){
        var res = 1 //
        for(let i = 0; i < power; i++){
            res = res*num
        }
        return res
    }   
    console.log(powerTo(2,10));

----------------------------------------------------------------------------------------------------------------------------------------------------------------

    var numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20]
    delArr = (deleteElement(numbers,2))

    function printEven(array){
        for(i=0;i<array.length;i++){
            if(array[i]%2==0){
                console.log(array[i]);
            }
        }
    }

    function deleteElement(array,num){
        for(i=0;i<array.length;i++){
            if(array[i] == num){
                array.splice(i,1);
            }
        }
        return array;
    }


    console.log(printEven(numbers));
    console.log(delArr);
    
   ----------------------------------------------------------------------------------------------------------------------------------------------------------------

    array = [5, 4, 3, 2, 1, 7]

    var value = 0;
    var ans = 0;

    for(var i = 0; i < array.length; i++ ){
            value = array[i];
            ans += value
    }
    console.log(ans);
    
   ----------------------------------------------------------------------------------------------------------------------------------------------------------------

    function respond(userAns){
        switch(userAns){
            case "red":
                console.log("We bloods cuz")
                break;
            case "blue":
                console.log("We crippin' in dis hoe")
                break;
            case "green":
                console.log("We the green gizmos (cause idk how to spell leprechun)")
                break;
        }
    }

    console.log(respond('blue'));
    
   ----------------------------------------------------------------------------------------------------------------------------------------------------------------
