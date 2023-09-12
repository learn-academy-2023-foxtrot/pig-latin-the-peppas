// add a condition that determines if the first letter of a string is a vowel, and if so adds the word "way" 
      // input: string stored in variable eachWord
      // output: string with "way" added to the end
      // process: if the first letter of eachWord equals the first value within vowelsArray, add "way" to the end of string eachWord
     if (eachWord[0] === vowelsArray[0]) {
      return eachWord + "way"
     }