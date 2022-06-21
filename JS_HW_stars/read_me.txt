HW_1* 
Задания с разным количеством звездочек:)
1*:
Преобразовать написанный код в 26-33 пунктах в функцию, принимающую на вход возраст.
Пример: const checkAge = function(age) {
Ваши преобразования
}
Вывести в консоль результат работы функции с возрастами 17, 18, 61

2*:
Преобразовать задание 1* таким образом, чтобы первым делом в функции проверялся тип данных. И если он не Number - кидалась ошибка.

3**:
Преобразовать 2* таким образом, чтобы значение '2' (строка в которой лежит ТОЛЬКО ЦИФРА) пропускалось, преобразовываясь в number

4***:
Преобразовать задание 3* таким образом, чтобы возраст вводится используя функцию prompt в привязанной верстке
******************************************************************************************************************
******************************************************************************************************************



//1*:
//Преобразовать написанный код в 26-33 пунктах в функцию, принимающую на вход возраст.
//Пример: const checkAge = function(age) {
//Ваши преобразования
//}
//Вывести в консоль результат работы функции с возрастами 17, 18, 61

 const age2 = 18;
  const age3 = 60;

  const checkAge = function(age) {
    if (age < age2){
       console.log("You don't have access cause your age is " + age + " It's less then " +age2)
    }else if (age >= age2 && age < age3) { 
        console.log("Welcome  !")
    }else if (age > age3) {
        console.log("Keep calm and look Culture channel")
    } else{
        console.log("Technical work")
    }
} 

checkAge(17)
checkAge(18)
checkAge(61)

//You don't have access cause your age is 17 It's less then 18
//Welcome  !
//Keep calm and look Culture channel

//***********************************************************************************************

//2*:
//Преобразовать задание 1* таким образом, чтобы первым делом в функции проверялся тип данных. И если он не Number - кидалась ошибка.

 const age2 = 18;
  const age3 = 60;

  const checkAge = function(age) {
if(typeof age == 'number'){
    if (age < age2){
       console.log("You don't have access cause your age is " + age + " It's less then " +age2)
    }else if (age >= age2 && age < age3) { 
        console.log("Welcome  !")
    }else if (age > age3) {
        console.log("Keep calm and look Culture channel")
    } else{
        console.log("Technical work")
    }
} else console.log('Not a intiger value')
	}
checkAge(17)
checkAge(18)
checkAge(60)
checkAge(61)
checkAge('aaa')
checkAge('20')

//You don't have access cause your age is 17 It's less then 18
//Welcome  !
//Technical work
//Keep calm and look Culture channel
//Not a intiger value
//Not a intiger value

//*****************************************************************************************************

//3**:
//Преобразовать 2* таким образом, чтобы значение '2' (строка в которой лежит ТОЛЬКО ЦИФРА) пропускалось, преобразовываясь в number

const age2 = 18;
const age3 = 60;

const checkAge = function(age) {
    age = Number (age)
    console.log (age)
if(age && !isNaN (age)) {
  if (age < age2){
     console.log("You don't have access cause your age is " + age + " It's less then " +age2)
  }else if (age >= age2 && age < age3) { 
      console.log("Welcome  !")
  }else if (age > age3) {
      console.log("Keep calm and look Culture channel")
  } else{
      console.log("Technical work")
  }
} else console.log('Not a intiger value')
  }
checkAge(17)
checkAge(18)
checkAge(60)
checkAge(61)
checkAge('aaa')
checkAge('20')
checkAge(' ')

// 17
// You don't have access cause your age is 17 It's less then 18
// 18
// Welcome  !
// 60
// Technical work
// 61
// Keep calm and look Culture channel
// NaN
// Not a intiger value
// 20
// Welcome  !
// 0
//  Not a intiger value

//***********************************************************************************************
//4***:
//Преобразовать задание 3* таким образом, чтобы возраст вводится используя функцию prompt в привязанной верстке

//Save (Задания 3*) as file: "js_hw_1_stars_3_web.js"
//Create html file "JS_hw_1_stars_4_web.html"
//Enter:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script src="./js_hw_1_web.js"></script>
</body>
</html>

//Save file.

//***********************************************************************************************
