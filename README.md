# AAAA
public class BreakBooleanDemo
{
     public static void main(String[ ] args)
     {
           int[ ] numbers = { 12, 13, 2, 33, 23, 31, 22, 6, 87, 16 };
           int key = 31;

           int i = 0;
           boolean found = false;    // set the boolean value to false until the key is found

          for ( i = 0; i < numbers.length; i++)
          {
                 if (numbers[ i ]  == key)
                {
                         found = true;      
                         break;
                 }
           }

          if (found)   //When found is true, the index of the location of key will be printed.
          {
                System.out.println("Found " + key + " at index " + i + ".");
          }
          else
          {
                System.out.println(key + "is not in this array.");
          }
      }
}
