## Print string of odd length in ‘X’ format
## Code
```
import java.util.Scanner;

public class longestpalindromesubstring{
    public static void main(String[] args) {
        // Scanner sc=new Scanner(System.in);
        String s="12345";
        int l=s.length();
        for(int i=0;i<l;i++){
            int j=l-1-i;
            for(int k=0;k<l;k++){
                if(k==i||k==j){
                    System.out.print(s.charAt(k));
                }
                else{
                    System.out.print(" ");
                }
            }
            System.out.println("");
        }


    }
}
```
## Output:
![image](https://github.com/user-attachments/assets/8f4877a8-017d-45ec-bc43-005674ae1e90)
