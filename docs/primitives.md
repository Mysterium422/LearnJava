# Step 3: More Primitives

## Step 3.1
Given `opponent_health`, determine if the opponent is dead. Store this value in a boolean variable called `opponent_alive`.
Print this value to console.
Set `opponent_health` to 0. Recalculate `opponent_alive`.
Print this new value to console.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 2 Code goes here */

    /** Step 3.1 */
    // TODO: Set a boolean variable called opponent_alive. Print to console.
    // TODO: Set opponent_health to 0. Recalculate opponent_alive. Print to console.
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
    
  true <br>
  false

  </div>
</details>
<br>

## Step 3.2
Given a new opponent with `opponent2_health`, print if there is any enemy alive. Use the `or` operator.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 3.1 Code goes here */

    /** Step 3.2 */
    double opponent2_health = (((15 + 25) * 5 / (25 - 15)) - (5 * 3) + (5 / 3) + ((25 - 5) * 3 / (3 + 5) * 2) - ((25 * 5 / (3 + 5)) - (15 * 25 / (15 + 25)) + (3 * 3) % (5 * 3))) + (((15 + 25) * 5 / (25 - 15)) - (5 * 3) + (5 / 3) * 0 - 10);
    // TODO: Determine if this opponent is dead using code. Then, print whether there is any enemy alive. Use the 'or' operator.
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
    
  false

  </div>
</details>
<br>

## Step 3.3
Given a third opponent with `opponent3_health`, print to console whether all opponents are dead. Use the `not` and the `and` operators.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 3.2 Code goes here */

    /** Step 3.3 */
    double opponent3_health = (((7 * 3) + (5 * 2) - (4 / 2) + (6 % 5)) - (2 * 1) + (8 - 8) * (9 / 3)) - ((12 / 3) * 2 - (15 - 10) * (2 - 2) + (3 * 1) % (7 - 5));
    // TODO: Determine if this opponent is dead using code. Print the result to console. Then, print if all enemies are dead. Use 'and' and 'not' operators.
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
    
  false

  </div>
</details>
<br>

## Step 3.4
Create a char variable called `opponent_tier`. Set this variable to 'B'. 

The enemy has grown stronger! Increment this variable and print to console. Does that make sense?
Try subtracting 2 from the variable and printing it to console. Given what the previous change, does this make more sense what might be going on?
Lastly, to confuse you just a little bit more, subtract 1 more and print to console. Find why this is the output.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 3.3 Code goes here */

    /** Step 3.4 */
    // TODO: Create a char variable called opponent_tier which is set to 'B'.
    // TODO: Increment the variable and print to console.
    // TODO: Subtract 2 from the variable and print to console.
    // TODO: Subtract 1 more from the variable and print to console.
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
    
  C <br>
  A <br>
  @

  </div>
</details>
<br>