Describe: pigLatin()

Test: "It will recognize words that begin with a vowel."
Code: pigLatin("awesome")
Expected Output: "a"

Test: "It will iterate over the letters of a word until it finds a vowel"
Code: pigLatin("psychology");
Expected Output: "psych"

Test: "It will recognize words that begin with "qu"."
Code: pigLatin("quasr");
Expected Output: true

Test: "It will add 'way' to the end of words that begin with a vowel."
Code: pigLatin("a");
Expected Output: "away"

Test: "If the word begins with a consonant, move all of the first consecutive consonants to the end and add 'ay'.
Code: pigLatin("code")
Expected Output: "odecay"

Test: "It will move "q" and "u" to then end of a word that includes "qu" as it's first consonants and add 'ay'."
Code: pigLatin("quiet");
Expected Output: "ietquay"

Test: "It will recognize words that start with vowel, consonant, and "qu" regardless of capitalization"
Code: pigLatin("CODE");
Expected Output: "odecay"

Test: "It will recognize words that start with vowel, consonant, and "qu" regardless of inconsistent capitalization"
Code: pigLatin("CoDe");
Expected Output: "odecay"



