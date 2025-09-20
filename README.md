function checkNumber(){
    let number=document.getElementById("num").value;
    let resultText="";
    if(number > 0){
        resultText="Number is Positive";
    } else if (number < 0 ){
        resultText="Number is Negative";
    } else{
        resultText="Number is zero";
    }
    document.getElementById("result").innerText=resultText;

}
