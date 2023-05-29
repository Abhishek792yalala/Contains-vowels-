# Contains-vowels-
Contains vowels

class StringContainsVowels {

    public static void main(String[] args) {

        System.out.println(stringContainsVowels("QWRTY")); // true

        System.out.println(stringContainsVowels("AEIOU")); // false

    }

    public static boolean stringContainsVowels(String input) {

        return input.toLowerCase().matches(".*[aeiou].*");

    }

}

/*

false

true

 */
