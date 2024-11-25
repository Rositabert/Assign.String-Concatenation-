public class StringConcatenate {
    public static void main(String[] args) {
        String String1 = "Good";
        String String2 = "Morning";
        
        // Using the concatenate algorithm
        String result = concatenate(String1, String2);
        
        // Print the result
        System.out.println(result);  // Output: GoodMorning
    }

    // Concatenate function
    public static String concatenate(String String1, String String2) {
        String result = "";  // Initialize an empty result string
        
        // Concatenate String1
        for (int i = 0; i < String1.length(); i++) {
            result += String1.charAt(i);
        }
        
        // Concatenate String2
        for (int i = 0; i < String2.length(); i++) {
            result += String2.charAt(i);
        }
        
        return result;  // Return the concatenated result
    }
}
