### ArrayList

in BaekJoon p10871

```java
import java.util.ArrayList;
import java.util.Scanner;

/*
    BAEKJOON 10871번 X보다 작은 수
    https://www.acmicpc.net/problem/10871
*/

public class Main {

  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    // 코드를 작성하세요.

    int N = scanner.nextInt();
    int X = scanner.nextInt();

    ArrayList<Integer> array = new ArrayList<>();

    for(int i = 0; i < N; i++){
      int input = scanner.nextInt();
      if(input < X)
        array.add(input);
    }
    for(int i = 0; i < array.toArray().length; i++){
      System.out.printf("%d ", array.get(i));
    }
    System.out.printf("\n");
  }
}
```


1. ArrayList는 정적인 일반 배열보다 동적으로 작동하기 때문에 데이터를 넣고 빼고 가져오는것이 편리하다.
2. ArrayList<Integer> array = new ArrayList<>(); //선언으로 사용가능
3. add(), get()과 같은 여러가지 제어 메소드가 존재하고 이를 활용하면 배열다루기가 쉽다


* []와 <>의 차이는 정적과 동적 배열의 차이이다.
