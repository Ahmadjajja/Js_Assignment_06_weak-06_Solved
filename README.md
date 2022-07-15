# Js_Assignment_06_weak-06_Solved

console.log(" Write a js program to find length of a string.");
console.log("_STRING_HANDLINGQ_NO_1__");
 var fullName="ahmad jajja";
 console.log("fullName length=>",fullName.length);

 console.log(" Write a js program to copy one string to another string");
 console.log("_STRING_HANDLINGQ_NO_2__");
 var fullName="ahmad jajja";
 var secondName=fullName.slice(6,11);
 console.log("fullName =>",fullName);
 console.log("copied string(secondName) =>",secondName);

console.log("Write a js program to concatenate two strings.");
console.log("_STRING_HANDLINGQ_NO_3__");
 var firstName="Ahmad";
 var secondName="Sultan";
 console.log("firstName =>",firstName);
 console.log("secondName =>",secondName);
console.log("fullName =>",firstName.concat(secondName));

console.log("Write a js program to compare two strings");
console.log("_STRING_HANDLINGQ_NO_4__");
var day="FridaY";
console.log("day=>",day);
if(day.toLowerCase()==="friday"){
    console.log("yes,today is friday");
}else{
    console.log("NO,today is not friday");
}

console.log("Write a js program to convert lowercase string to uppercase");
console.log("_STRING_HANDLINGQ_NO_5__");
var lowerCaseString="friday";
console.log("lowerCaseString=>",lowerCaseString);
console.log("upperCaseString=>",lowerCaseString.toUpperCase());


console.log(" Write a js program to convert uppercase string to lowercase.");
console.log("_STRING_HANDLINGQ_NO_6__");
var upperCaseString="FRIDAY";
console.log("upperCaseString=>",upperCaseString);
console.log("lowerCaseString=>",upperCaseString.toLowerCase());

console.log("Write a js program to toggle case of each character of a string.");
console.log("_STRING_HANDLINGQ_NO_7__");
var string="@Learn With Naveed Sarwar786$",string2=" ";
console.log("string before toggle case=>",string);
for (let index = 0,character; index < string.length; index++) {
    character=string.charAt(index);
    if (character==='a'||character==='b'||character==='c'||character==='d'||character==='e'||character==='f'||character==='g'||character==='h'||character==='i'||character==='j'||character==='k'||character==='l'||character==='m'||character==='n'||character==='o'||character==='p'||character==='q'||character==='r'||character==='s'||character==='t'||character==='u'||character==='v'||character==='w'||character==='x'||character==='y'||character==='z') {
        string2=string2.concat(character.toUpperCase());
    } else if (character==='A'||character==='B'||character==='C'||character==='D'||character==='E'||character==='F'||character==='G'||character==='H'||character==='I'||character==='J'||character==='K'||character==='L'||character==='M'||character==='N'||character==='O'||character==='P'||character==='Q'||character==='R'||character==='S'||character==='T'||character==='U'||character==='V'||character==='W'||character==='X'||character==='Y'||character==='Z') {
        string2=string2.concat(character.toLowerCase());      
    } else {
        string2=string2.concat(character);
    }
        
}
console.log("string after toggle case=>",string2);

console.log(" Write a js program to find total number of alphabets, digits or special character in a string.");
console.log("_STRING_HANDLINGQ_NO_8__");
var string="@Learn With Naveed Sarwar786$",noOfAlphabets=0,noOfDigits=0,noOfSpecialCharacters=0;
console.log(string);
for (let index = 0,character; index < string.length; index++) {
    character=string.charAt(index);
    if (character==='a'||character==='b'||character==='c'||character==='d'||character==='e'||character==='f'||character==='g'||character==='h'||character==='i'||character==='j'||character==='k'||character==='l'||character==='m'||character==='n'||character==='o'||character==='p'||character==='q'||character==='r'||character==='s'||character==='t'||character==='u'||character==='v'||character==='w'||character==='x'||character==='y'||character==='z'||character==='A'||character==='B'||character==='C'||character==='D'||character==='E'||character==='F'||character==='G'||character==='H'||character==='I'||character==='J'||character==='K'||character==='L'||character==='M'||character==='N'||character==='O'||character==='P'||character==='Q'||character==='R'||character==='S'||character==='T'||character==='U'||character==='V'||character==='W'||character==='X'||character==='Y'||character==='Z') {
        noOfAlphabets++;
    } else if (character==='1'||character==='2'||character==='3'||character==='4'||character==='5'||character==='6'||character==='7'||character==='8'||character==='9') {
        noOfDigits++;      
    } else {
        noOfSpecialCharacters++;
    }
        
}
    console.log("noOfAlphabets=>",noOfAlphabets);
    console.log("noOfDigits=>",noOfDigits);
    console.log("noOfSpecialCharacters=>",noOfSpecialCharacters);

console.log("9. Write a js program to count total number of vowels and consonants in a string");
console.log("_STRING_HANDLINGQ_NO_9__");
var string="Learn With Naveed Sarwar",noOfConsonants=0,noOfWowels=0;
console.log(string);
for (let index = 0,character; index < string.length; index++) {
    character=string.charAt(index);
    if (character==='b'||character==='c'||character==='d'||character==='f'||character==='g'||character==='h'||character==='j'||character==='k'||character==='l'||character==='m'||character==='n'||character==='p'||character==='q'||character==='r'||character==='s'||character==='t'||character==='v'||character==='w'||character==='x'||character==='y'||character==='z'||character==='B'||character==='C'||character==='D'||character==='F'||character==='G'||character==='H'||character==='J'||character==='K'||character==='L'||character==='M'||character==='N'||character==='P'||character==='Q'||character==='R'||character==='S'||character==='T'||character==='V'||character==='W'||character==='X'||character==='Y'||character==='Z') {
        noOfConsonants++;
    } else if (character==='a'||character==='e'||character==='i'||character==='o'||character==='u'||character==='A'||character==='E'||character==='I'||character==='O'||character==='U') {
        noOfWowels++;      
    }
        
}
    console.log("noOfConsonants=>",noOfConsonants);
    console.log("noOfWowels=>",noOfWowels);

console.log("Write a js program to count total number of words in a string");
console.log("_STRING_HANDLINGQ_NO_10__");
var string="Learn With Naveed Sarwar",totalNoOfWords=1;
console.log(string);
for (let index = 0,character; index < string.length; index++) {
    character=string.charAt(index);
    if (character===' ') {
        totalNoOfWords++;
    }
}
    console.log("totalNoOfWords=>",totalNoOfWords);

console.log("Write a js program to find reverse of a string.");
console.log("_STRING_HANDLINGQ_NO_11__");
var string="Learn With Naveed Sarwar",string2=" ";
console.log("string before reversing=>",string);
for (let index =string.length-1,character; index >= 0; index--) {
    string2=string2.concat(string.charAt(index))
}
    console.log("string after reversing=>",string2);

console.log("Write a js program to check whether a string is palindrome or not.");
console.log("_STRING_HANDLINGQ_NO_12__");
var string="Animal loots foliated detail of stool lamina.",stringInNormalOrder="",stringInReverseOrder="";
console.log(string);
 for (let index = 0,character; index < string.length; index++) {
    character=string.charAt(index);
    if (character==='a'||character==='b'||character==='c'||character==='d'||character==='e'||character==='f'||character==='g'||character==='h'||character==='i'||character==='j'||character==='k'||character==='l'||character==='m'||character==='n'||character==='o'||character==='p'||character==='q'||character==='r'||character==='s'||character==='t'||character==='u'||character==='v'||character==='w'||character==='x'||character==='y'||character==='z'||character==='A'||character==='B'||character==='C'||character==='D'||character==='E'||character==='F'||character==='G'||character==='H'||character==='I'||character==='J'||character==='K'||character==='L'||character==='M'||character==='N'||character==='O'||character==='P'||character==='Q'||character==='R'||character==='S'||character==='T'||character==='U'||character==='V'||character==='W'||character==='X'||character==='Y'||character==='Z') {
        stringInNormalOrder=stringInNormalOrder.concat(character);
    } else if (character==='1'||character==='2'||character==='3'||character==='4'||character==='5'||character==='6'||character==='7'||character==='8'||character==='9') {
        stringInNormalOrder=stringInNormalOrder.concat(character);
    }
        
}
for (let index =string.length-1,character; index >= 0; index--) {
    character=string.charAt(index);
    if (character==='a'||character==='b'||character==='c'||character==='d'||character==='e'||character==='f'||character==='g'||character==='h'||character==='i'||character==='j'||character==='k'||character==='l'||character==='m'||character==='n'||character==='o'||character==='p'||character==='q'||character==='r'||character==='s'||character==='t'||character==='u'||character==='v'||character==='w'||character==='x'||character==='y'||character==='z'||character==='A'||character==='B'||character==='C'||character==='D'||character==='E'||character==='F'||character==='G'||character==='H'||character==='I'||character==='J'||character==='K'||character==='L'||character==='M'||character==='N'||character==='O'||character==='P'||character==='Q'||character==='R'||character==='S'||character==='T'||character==='U'||character==='V'||character==='W'||character==='X'||character==='Y'||character==='Z') {
        stringInReverseOrder=stringInReverseOrder.concat(character);
       } else if (character==='1'||character==='2'||character==='3'||character==='4'||character==='5'||character==='6'||character==='7'||character==='8'||character==='9') {
        stringInReverseOrder=stringInReverseOrder.concat(character);
 }
        
}
if (stringInNormalOrder.toLowerCase()===stringInReverseOrder.toLowerCase()) {
    console.log("Yes,string is palindrome");
} else {
    console.log("No,string is not palindrome");
}

console.log("Write a js program to reverse order of words in a given string");
console.log("_STRING_HANDLINGQ_NO_13__");
var string="Animal loots foliated detail of stool lamina",string2=" ",string3=" ",stringInReverseOrder="",stringOfreverseOrderOfWords="";
console.log("string before reversing order of words=>",string);
var arr=string.split(" ");
for (let index = 0; index < arr.length; index++) {
    string2=arr[index];
    for (let index =string2.length-1; index >= 0; index--) {
        string3=string3.concat(string2.charAt(index))
    }
    arr[index]=string3;
    string3="";
}
console.log("string after reversing order of words=>",arr.join(" "));

console.log("Write a js program to find first occurrence of a character in a given string");
console.log("_STRING_HANDLINGQ_NO_14__");
var character='n',string="learn with naveed sarwar";
console.log("string=>",string);
console.log("character=>",character);
for (let index = 0; index < string.length; index++) {
    if (string.charAt(index)===character) {
        console.log("index of first occurance of character in string=>",index);
        break;
    }
    
}


console.log("Write a js program to find last occurrence of a character in a given string.");
console.log("_STRING_HANDLINGQ_NO_15__");
var character='n',string="learn with naveed sarwar";
console.log("string=>",string);
console.log("character=>",character);
for (let index = string.length-1; index >=0 ; index--) {
    if (string.charAt(index)===character) {
        console.log("index of last occurance of character in string=>",index);
        break;
    }
    
}


console.log("Write a js program to search all occurrences of a character in given string.");
console.log("_STRING_HANDLINGQ_NO_16__");
var character='r',string="learn with naveed sarwar",counter=0,indexPlaces="";
console.log("string=>",string);
console.log("character=>",character);
for (let index = 0; index < string.length; index++) {
    if (string.charAt(index)===character) {
        counter++;
        indexPlaces=indexPlaces+" "+index;
    }  
}
console.log("character occurances times=>",counter);
console.log("indexPlaces=>",indexPlaces);

console.log("Write a js program to count occurrences of a character in given string.");
console.log("_STRING_HANDLINGQ_NO_17__");
var character='r',string="learn with naveed sarwar",counter=0,indexPlaces="";
console.log("string=>",string);
console.log("character=>",character);
for (let index = 0; index < string.length; index++) {
    if (string.charAt(index)===character) {
        counter++;
    }  
}
console.log(character,"-",counter);


console.log("Write a js program to find highest frequency character in a string.");
console.log("_STRING_HANDLINGQ_NO_18__");
var string="learn with naveed sarwar",counter=0,arr=[],highFrequencyArrayIndex=0,highFrequencyCharacter='';
console.log("string=>",string);
for (let i = 0; i < string.length; i++) {
    character=string.charAt(i);
    for (let index = 0; index < string.length; index++) {
        if (string.charAt(index)===character) {
            counter++;
        }    
    } 
    arr[i]=counter;
    counter=0;   
}
for (let index = 0; index < string.length; index++) {
    if (arr[index]>=highFrequencyArrayIndex) {
        highFrequencyArrayIndex=arr[index];
        highFrequencyCharacter=string.charAt(index);
    }
}
// console.log(arr);
console.log(highFrequencyCharacter,":",highFrequencyArrayIndex);

console.log("Write a js program to find lowest frequency character in a string");
console.log("_STRING_HANDLINGQ_NO_19__");
var string="learn with naveed sarwar",counter=0,arr=[],highFrequencyArrayIndex,highFrequencyCharacter='';
console.log("string=>",string);
for (let i = 0; i < string.length; i++) {
    character=string.charAt(i);
    for (let index = 0; index < string.length; index++) {
        if (string.charAt(index)===character) {
            counter++;
        }    
    } 
    arr[i]=counter;
    counter=0;   
}
highFrequencyArrayIndex=arr[arr.length-1];
for (let index = 0; index < string.length; index++) {
    if (arr[index]<=highFrequencyArrayIndex) {
        highFrequencyArrayIndex=arr[index];
        highFrequencyCharacter=string.charAt(index);
    }
}
// console.log(arr);
console.log(highFrequencyCharacter,":",highFrequencyArrayIndex);

console.log("Write a js program to count frequency of each character in a string.");
console.log("_STRING_HANDLINGQ_NO_20__");
var string="ahmad",counter=0,arr=[],highFrequencyArrayIndex=0,highFrequencyCharacter='';
console.log("string=>",string);
for (let i = 0; i < string.length; i++) {
    character=string.charAt(i);
    for (let index = 0; index < string.length; index++) {
        if (string.charAt(index)===character) {
            counter++;
        }    
    } 
    if (string.charAt(i)!=" ") {
        arr[i]=counter;
        console.log(string.charAt(i),":",arr[i]);
        
    }   
    counter=0;  
}

console.log("Write a js program to remove first occurrence of a character from string.");
console.log("_STRING_HANDLINGQ_NO_21__");
var string="learn with naveed sarwar",character='a';
var arr=string.split("");
console.log("string=>",string);
console.log("character=>",character);
for (let index = 0; index < string.length; index++) {
    if (string.charAt(index)===character) {
        arr.splice(index,1);
        break;
    }
    
}
console.log("stringAfterRemovingFirstOccuranceOfCharacter=>",arr.join(""));



console.log("Write a js program to remove last occurrence of a character from string.");
console.log("_STRING_HANDLINGQ_NO_22__");
var string="learn with naveed sarwar",character='a';
var arr=string.split("");
console.log("string=>",string);
console.log("character=>",character);
for (let index =string.length-1; index>=0 ; index--) {
    if (string.charAt(index)===character) {
        arr.splice(index,1);
        break;
    }
    
}
console.log("stringAfterRemovingLastOccuranceOfCharacter=>",arr.join(""));

console.log(" Write a js program to remove all occurrences of a character from string.");
console.log("_STRING_HANDLINGQ_NO_23__");
var string="learn with naveed sarwar",character='a';
var arr=string.split("");
console.log("string=>",string);
console.log("character=>",character);
for (let index =string.length-1; index>=0 ; index--) {
    if (string.charAt(index)===character) {
        arr.splice(index,1);
        // break;
    }
    
}
console.log("stringAfterRemovingAllOccuranceOfCharacter=>",arr.join(""));

console.log("Write a js program to remove all repeated characters from a given string.");
console.log("_STRING_HANDLINGQ_NO_24__");
var string="",arr=string.split(""),counter=0;
console.log("string=>",string);
for (let index = 0; index < string.length; index++) {
    for (let i = 0; i < arr.length; i++) {
        if (string.charAt(index)===arr[i]) {
            if (counter>0&&string.charAt(index)!=" ") {
                arr.splice(i,1);
            }
            counter++;
        }
        
    }
    counter=0;
}
console.log("stringAfterRemovingAllRepeatedCharacters=>",arr.join(""));


console.log("Write a js program to replace first occurrence of a character with another in a string.");
console.log("_STRING_HANDLINGQ_NO_25__");
var string="learn with naveed sarwar",occuranceCharacter='a',replacingCharacter='v';
var arr=string.split("");
console.log("string=>",string);
console.log("occuranceCharacter=>",occuranceCharacter);
console.log("replacingCharacter=>",replacingCharacter);
for (let index = 0; index < string.length; index++) {
    if (string.charAt(index)===occuranceCharacter) {
        arr[index]=replacingCharacter;
        break;
    }
    
}
console.log("stringAfterReplacingFirstOccuranceOfCharacter=>",arr.join(""));

console.log("Write a js program to replace last occurrence of a character with another in a string.");
console.log("_STRING_HANDLINGQ_NO_26__");
var string="learn with naveed sarwar",occuranceCharacter='a',replacingCharacter='v';
var arr=string.split("");
console.log("string=>",string);
console.log("occuranceCharacter=>",occuranceCharacter);
console.log("replacingCharacter=>",replacingCharacter);
for (let index =string.length-1; index>=0 ; index--) {
    if (string.charAt(index)===occuranceCharacter) {
        arr[index]=replacingCharacter;
        break;
    }
    
}
console.log("stringAfterReplacingLastOccuranceOfCharacter=>",arr.join(""));

console.log("Write a js program to replace all occurrences of a character with another in a string.");
console.log("_STRING_HANDLINGQ_NO_27__");
var string="learn with naveed sarwar",occuranceCharacter='a',replacingCharacter='v';
var arr=string.split("");
console.log("string=>",string);
console.log("occuranceCharacter=>",occuranceCharacter);
console.log("replacingCharacter=>",replacingCharacter);
for (let index =string.length-1; index>=0 ; index--) {
    if (string.charAt(index)===occuranceCharacter) {
        arr[index]=replacingCharacter;
    }
    
}
console.log("stringAfterReplacingLastOccuranceOfCharacter=>",arr.join(""));

console.log("Write a js program to find first occurrence of a word in a given string");
console.log("_STRING_HANDLINGQ_NO_28__");
var string="Naveed sir is good trainer but ahmad is also good student thatswhy result will be good";
var arr=string.split(" "),occuranceIndex,occuranceWord="good",string2;
console.log("string=>",string);
console.log("occuranceWord=>",occuranceWord);
occuranceIndex=string.indexOf(occuranceWord);
console.log("startingIndexOfFirstOccurrenceOfWord=>",occuranceIndex);

console.log("Write a js program to find last occurrence of a word in a given string.");
console.log("_STRING_HANDLINGQ_NO_29__");
var string="Naveed sir is good trainer but ahmad is also good student thatswhy result will be good";
var arr=string.split(" "),occuranceIndex,occuranceWord="good";
console.log("string=>",string);
console.log("occuranceWord=>",occuranceWord);
occuranceIndex=string.lastIndexOf(occuranceWord);
console.log("startingIndexOfLastOccurrenceOfWord=>",occuranceIndex);


console.log("Write a js program to search all occurrences of a word in given string.");
console.log("_STRING_HANDLINGQ_NO_30__");
var string="Naveed sir is good trainer but ahmad is also good student thatswhy result will be good";
var arr=string.split(" "),occuranceIndex=0,occuranceWord="good",counter=0;
console.log("string=>",string);
console.log("occuranceWord=>",occuranceWord);
for (let index = 0; index < string.length; index++) {
    if (arr[index]===occuranceWord) {
        counter++;
        occuranceIndex=string.indexOf(arr[index],occuranceIndex)
        console.log("index of occurance",counter,"=>",occuranceIndex);
        occuranceIndex++;
    }
    
}


console.log("Write a js program to count occurrences of a word in a given string.");
console.log("_STRING_HANDLINGQ_NO_31__");
var string="Naveed sir is good trainer but ahmad is also good student thatswhy result will be good";
var arr=string.split(" "),occuranceIndex=0,occuranceWord="good",counter=0;
console.log("string=>",string);
console.log("occuranceWord=>",occuranceWord);
for (let index = 0; index < string.length; index++) {
    if (arr[index]===occuranceWord) {
        counter++;
    }  
}
console.log("word's occurrences=>",counter,"times");

console.log("Write a js program to remove first occurrence of a word from string.");
console.log("_STRING_HANDLINGQ_NO_32__");
var string="Naveed sir is good trainer but ahmad is also good student thatswhy result will be good";
var arr=string.split(" "),occuranceIndex=0,occuranceWord="good";
console.log("string=>",string);
console.log("occuranceWord=>",occuranceWord);
for (let index = 0; index < arr.length; index++) {
    if (arr[index]===occuranceWord) {
        arr.splice(index,1);
        break;
    }
}
console.log("stringAfterRemovingFirstOccuranceOfWord=>",arr.join(" "));

console.log("Write a js program to remove first occurrence of a word from string.");
console.log("_STRING_HANDLINGQ_NO_33__");
var string="Naveed sir is good trainer but ahmad is also good student thatswhy result will be good";
var arr=string.split(" "),occuranceIndex=0,occuranceWord="good";
console.log("string=>",string);
console.log("occuranceWord=>",occuranceWord);
for (let index =string.length-1; index>=0 ; index--) {
    if (arr[index]===occuranceWord) {
        arr.splice(index,1);
        break;
    }
}
console.log("stringAfterRemovingLastOccuranceOfWord=>",arr.join(" "));

console.log("Write a js program to remove all occurrence of a word in given string.");
console.log("_STRING_HANDLINGQ_NO_34__");
var string="Naveed sir is good trainer but ahmad is also good student thatswhy result will be good";
var arr=string.split(" "),occuranceIndex=0,occuranceWord="good";
console.log("string=>",string);
console.log("occuranceWord=>",occuranceWord);
for (let index = 0; index < arr.length; index++) {
    if (arr[index]===occuranceWord) {
        arr.splice(index,1);
    }
}
console.log("stringAfterRemovingAllOccuranceOfWord=>",arr.join(" "));

console.log("Write a js program to trim leading white space characters from given string.");
console.log("_STRING_HANDLINGQ_NO_35__");
var string=" ahmad jajja ";
console.log("string=>",string);
console.log("stringAfterTrimLeadingWhiteSpace=>",string.trimLeft());

console.log(" Write a js program to trim trailing white space characters from given string.");
console.log("_STRING_HANDLINGQ_NO_36__");
var string=" ahmad jajja ";
console.log("string=>",string);
console.log("stringAfterTrimTrailingWhiteSpace=>",string.trimRight());

console.log("Write a js program to trim both leading and trailing white space characters from given string.");
console.log("_STRING_HANDLINGQ_NO_37__");
var string=" ahmad jajja ";
console.log("string=>",string);
console.log("stringAfterTrimLeadingAndTrailingWhiteSpace=>",string.trim());

console.log(" Write a js program to remove all extra blank spaces from given string.");
console.log("_STRING_HANDLINGQ_NO_38__");
var string=" ahmad jajja ",arrayLength;
var arr=string.split(" ");
console.log("string=>",string);
arrayLength=arr.length
for (let i = 0; i < arrayLength; i++) {
    for (let index = 0; index < arrayLength; index++) {
        if (arr[index]===""||arr[index]===" ") {
            arr.splice(index,1);
        }
    }
    
}
console.log("stringAfterRemovingExtraBlankSpaces=>",arr.join(" "));

console.log("_shukur alhamdulillah string handling over after 3 night working__");





















console.log(" Write a js program to read and print elements of array.");
console.log("_ARRAY_HANDLINGQ_NO_01__");
var arr=["ahmad","sultan","jajja","programmer"];
console.log("array=>",arr);
for (let index = 0; index < arr.length; index++) {
    console.log("element at index",index,"=>",arr[index]);
}

console.log(" Write a js program to print all negative elements in an array.");
console.log("_ARRAY_HANDLINGQ_NO_02__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56];
console.log("array=>",arr);
for (let index = 0; index < arr.length; index++) {
    if (arr[index]<0) {
        console.log("Negative element at index",index,"=>",arr[index]);  
    }
}

console.log("Write a js program to find sum of all array elements.");
console.log("_ARRAY_HANDLINGQ_NO_03__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],sum=0;
console.log("array=>",arr);
for (let index = 0; index < arr.length; index++) {
        sum=sum+arr[index];
}
console.log("sum of all array elements=>",sum);  

console.log("Write a js program to find maximum and minimum element in an array.");
console.log("_ARRAY_HANDLINGQ_NO_04__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],min=0,max=0;
console.log("array=>",arr);
for (let index = 0; index < arr.length; index++) {
    if (arr[index]>max) {
        max=arr[index];    
    }
    if (min>arr[index]) {
        min=arr[index];
    }
}
console.log("maximum element in an array is=>",max);  
console.log("minimum element in an array is=>",min); 

console.log("Write a js program to find second largest element in an array.");
console.log("_ARRAY_HANDLINGQ_NO_05__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],secondmax=0,max=0;
console.log("array=>",arr);
for (let index = 0; index < arr.length; index++) {
    if (arr[index]>max) {
        max=arr[index];    
    }
}
for (let index = 0; index < arr.length; index++) {
    if (arr[index]>secondmax&&arr[index]!=max) {
        secondmax=arr[index];    
    }
}
console.log("second maximum element in an array is=>",secondmax);  


console.log(" Write a js program to count total number of even and odd elements in an array.");
console.log("_ARRAY_HANDLINGQ_NO_06__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],oddCounter=0,evenCounter=0;
console.log("array=>",arr);
for (let index = 0; index < arr.length; index++) {
    if (arr[index]%2===0) {
        evenCounter++;
    }else if (arr[index]%2!=0) {
        oddCounter++;    
    }
}
console.log("even elements=>",evenCounter,"times");  
console.log("odd elements=>",oddCounter,"times");


console.log("Write a js program to count total number of negative elements in an array.");
console.log("_ARRAY_HANDLINGQ_NO_07__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],negativeCounter=0;
console.log("array=>",arr);
for (let index = 0; index < arr.length; index++) {
    if (arr[index]<0) {
        negativeCounter++;  
    }
}
console.log("negative elements=>",negativeCounter,"times");

console.log("Write a js program to copy all elements from an array to another array.");
console.log("_ARRAY_HANDLINGQ_NO_08__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],anotherArr;
console.log("array=>",arr);
anotherArr=arr.slice(0,arr.length);
console.log("Another array=>",anotherArr);


console.log("Write a js program to insert an element in an array.");
console.log("_ARRAY_HANDLINGQ_NO_09__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],insertingElement=50;
console.log("array=>",arr);
console.log("insertingElement=>",insertingElement);
arr.splice(3,0,insertingElement)
console.log("array after inserting element =>",arr);

console.log(" Write a js program to delete an element from an array at specified position.");
console.log("_ARRAY_HANDLINGQ_NO_10__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],deletionPosition=5;
console.log("array=>",arr);
console.log("deletionPosition=>",deletionPosition);
for (let index = 0; index < arr.length; index++) {
    if (index+1===deletionPosition) {
        arr.splice(index,1);
        break;
    }
}
console.log("array after deleting element at specified position=>",arr);

console.log("Write a js program to count frequency of each element in an array.");
console.log("_ARRAY_HANDLINGQ_NO_11__");
var arr=[5,6,3,523,5,-4,-2,4,-5,2,5,-5,-7542,56],counter=0;
console.log("array=>",arr);
for(let i = 0; i < arr.length; i++) {
        for (let index = 0; index < arr.length; index++) {
           if (arr[i]===arr[index]) {
            counter++;    
           }
           
        }
        console.log(arr[i],":",counter) 
        counter=0;
}
console.log(" Write a js program to print all unique elements in the array.");
console.log("_ARRAY_HANDLINGQ_NO_12__");
var arr=[5,6,3,523,5,-4],counter=0;
console.log("array=>",arr);
for (let i = 0; i < arr.length; i++) {
    for (let index = 0; index < arr.length; index++) {
        if (arr[i]===arr[index]) {
            counter++;
        }
        
    }
    if (counter==1) {
        console.log(arr[i]);
    }
    counter=0;
}

console.log(" Write a js program to count total number of duplicate elements in an array.");
console.log("_ARRAY_HANDLINGQ_NO_13__");
var arr=[5,6,3,523,5,-4,523,10,5,6,8,11,11,11,12,12,12],counter=0,duplicateElementCounter=0;
console.log("array=>",arr);
for (let i = 0; i < arr.length; i++) {
    for (let index = 0; index < arr.length; index++) {
        if (arr[i]===arr[index]) {
            counter++;
        }
        
    }
    if (counter==2) {
        duplicateElementCounter++;
    }
    counter=0;
}
console.log(duplicateElementCounter/2);


console.log(" Write a js program to delete all duplicate elements from an array.");
console.log("_ARRAY_HANDLINGQ_NO_14__");
var arr=[1,2,3,4,4,5,5,6,7,7,8,9,9,10],counter=0,tempIndex;
console.log("array=>",arr);
for (let i = 0; i < arr.length; i++) {
    for (let index = 0; index < arr.length; index++) {
        if (arr[i]===arr[index]) {
            counter++;
            if (counter===2) {
                tempIndex=index;
            }
        }
        
    }
    if (counter==2) {
        arr.splice(i,1);
        arr.splice(tempIndex-1,1);
    }
    counter=0;
    tempIndex=0;
}
console.log("array after removing all duplicate elements=>",arr);

console.log("Write a js program to merge two array to third array.");
console.log("_ARRAY_HANDLINGQ_NO_15__");
var arr1=[1,2,3];
var arr2=[4,5,6];
var arr3=[];
arr3=arr1.concat(arr2);
console.log("array 1=>",arr1);
console.log("array 2=>",arr2);
console.log("array 3=>",arr3);

console.log("Write a js program to merge two array to third array.");
console.log("_ARRAY_HANDLINGQ_NO_16__");
var arr1=[1,2,3,4];
console.log("array 1=>",arr1);
console.log("array 1=>",arr1.reverse());

console.log("Write a js program to put even and odd elements of array in two separate array.");
console.log("_ARRAY_HANDLINGQ_NO_17__");
var arr1=[1,2,3,4,7,5,3,3],evenArray=[],oddArray=[],evenIndexCounter=0,oddIndexCounter=0;
console.log("array 1=>",arr1);
for (let index = 0; index < arr1.length; index++) {
    if (arr1[index]%2===0) {
        evenArray[evenIndexCounter]=arr1[index];
        evenIndexCounter++;
    } else {
        oddArray[oddIndexCounter]=arr1[index];
        oddIndexCounter++;
    }
    
}
console.log("Odd array=>",oddArray);
console.log("even array=>",evenArray);

console.log(" Write a js program to search an element in an array.");
console.log("_ARRAY_HANDLINGQ_NO_18__");
var arr1=[1,2,3,4,7,5,3,3],element=23,counter=0;
console.log("element=>",element);
console.log("array 1=>",arr1);
for (let index = 0; index < arr1.length; index++) {
    if (arr1[index]===element) {
        counter++;
        console.log("element",element,"is at index=>",index);
    }
    if (counter===0) {
        console.log("element",element,"is nothing found in array");
    }
}

console.log(" Write a js program to search an element in an array.");
console.log("_ARRAY_HANDLINGQ_NO_19__");
var arr1=[1,2,3,4,7,5,3,3,0,-5,-7];
console.log("array 1=>",arr1);
arr1.sort();
console.log("array 1=>",arr1);

console.log(" Write a js program to sort even and odd elements of array separately.");
console.log("_ARRAY_HANDLINGQ_NO_20__");
var arr1=[1,2,3,4,7,5,3,3],evenArray=[],oddArray=[],evenIndexCounter=0,oddIndexCounter=0;
console.log("array 1=>",arr1);
for (let index = 0; index < arr1.length; index++) {
    if (arr1[index]%2===0) {
        evenArray[evenIndexCounter]=arr1[index];
        evenIndexCounter++;
    } else {
        oddArray[oddIndexCounter]=arr1[index];
        oddIndexCounter++;
    }
    
}
oddArray.sort();
evenArray.sort();
console.log("Odd array after sorting=>",oddArray);
console.log("even array after sorting=>",evenArray);


console.log("Write a js program to left rotate an array.");
console.log("_ARRAY_HANDLINGQ_NO_21__");
var arr1=[1,2,3,4,7,5,3,3],leftRotationTime=3;
console.log("leftRotationTime",leftRotationTime);
console.log("array",arr1);
for (let index = 0; index < leftRotationTime; index++) {
    arr1.shift();
}
console.log("array after",leftRotationTime,"left rotations=>",arr1);

console.log("Write a js program to right rotate an array.");
console.log("_ARRAY_HANDLINGQ_NO_22__");
var arr1=[1,2,3,4,7,5,3,3],rightRotationTime=3;
console.log("rightRotationTime",rightRotationTime);
console.log("array",arr1);
for (let index = 0; index < rightRotationTime; index++) {
    arr1.pop();
}
console.log("array after",rightRotationTime,"rightrotations=>",arr1);

console.log("+++++++++++++++++++++++++++++++++++++++++++");
console.log("===========================================");
console.log("_________Assignment_6_completed____________");
console.log("===========================================");
console.log("+++++++++++++++++++++++++++++++++++++++++++");
