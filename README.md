# invertdpyramid.java
public class Invertedpyramid{
  
  /**
   * Main method - entry point of the program
   * @param args command line arguments (not used)
   */
  public static void main(String[] args){
    
   // Define the number of rows for the inverted pyramid
    int rows = 5;
    
  // Outer loop: controls the number of rows, starting from max rows down to 1
    // i starts at 5 and decrements until it reaches 1
    for (int i = rows; i >= 1; i--){
      
   // Inner loop: prints stars for each row
      // Number of stars in each row equals the current value of i
      // Row 1: 5 stars, Row 2: 4 stars, Row 3: 3 stars, etc.
      for(int j = 1; j <= i; j++){
        System.out.print("*"); // Print star without newline
      }
      
  // Move to next line after completing each row
      System.out.println();
    }
  }
}
