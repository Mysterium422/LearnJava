# Step 4: Control Flow 1

## Step 4.1
Let's start writing some actual logic in our code. Write an if statement where if at least one enemy is dead, then it prints `An enemy is dead` to console.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 3 Code goes here */

    /** Step 4.1 */
    // TODO: Implement 4.1 here
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
  An enemy is dead
  </div>
</details>
<br>

## Step 4.2
Next, let's check if a specific enemy, enemy 2, is dead. If it has less than or equal to 0 health, then print that `Enemy 2 has died`.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 4.1 Code goes here */

    /** Step 4.2 */
    // TODO: Implement 4.2 here
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
  Enemy 2 has died
  </div>
</details>
<br>

## Step 4.3
Let's check our own health. If it's above 35, print `Health is stable`. If it's less than 0, print `You have died.` Else print `Crtical Warning: Health is low`.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 4.2 Code goes here */

    /** Step 4.3 */
    // TODO: Implement 4.3 here
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
  Crtical Warning: Health is low
  </div>
</details>
<br>

## Step 4.4
Now try a new control method, a switch statement. Given an action (char), use a Switch statement to print the full name of the action.

- A: Attack
- S: Strengthen
- W: Weaken
- H: Heal
- Otherwise print Invalid

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Steps 1 - 4.3 Code goes here */

    /** Step 4.4 */
    char action = ((10 * 10) - (2 * 5) + (4 * 3) - 2) + (15 - 12 - 4 * 4);
    // TODO: Implement 4.4 here
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
  Weaken
  </div>
</details>
<br>
