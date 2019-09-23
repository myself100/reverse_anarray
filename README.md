# reverse_anarray

package elclipse;
import java.util.*;
public class reverse {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a[]= {1,2,3,4,5};
		int n=a.length-1;
		for(int i=0;i<=n/2;i++) {
			int temp=a[n-i];                         //swapping array element
			a[n-i]=a[i];                     
			a[i]=temp;
		}
		System.out.print(Arrays.toString(a));  ////////convert array to string
	}
}
