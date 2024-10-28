# Step 2: Variables and Arithmetic

## 2.1: First Operation
First, given variables `damage` and `number_of_hits`, print the total damage dealt.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Step 1 Code goes here */

    /** Step 2.1 */
    int damage = 4; // Comment this line when using the next line
    // double damage = 2.5; // Uncomment this line to try it with a decimal
    int number_of_hits = 3;

    // TODO Print the total damage dealt
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
    
  12 (if using int) <br>
  7.5 (if using double)

  </div>
</details>
<br>

## 2.2: More Operations
Next, given variables `opponent_health`, `opponent_damage`, `opponent_shield`, `player_health`, `player_damage`, and `player_shield`, calculate the damage dealt by the opponent on the player. Damage dealt is calculated as `damage - shield`. Store the damage dealt in a variable called `damage_dealt`. Subtract this damage from the player's health and print their new health to console.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Step 1 & 2.1 Code goes here */
    // TODO: Print a Welcome Message Here

    /** Step 2.2 */
    double player_health = 40;
    int player_damage = 10;
    int player_shield = 3;
    double opponent_health = 50;
    int opponent_damage = 8;
    int opponent_shield = 6;

    int damage_dealt = 0; // TODO: Calculate the damage dealt
    // TODO: Subtract the damage from the player's health and print it to console
  }

}
```

<details>
  <summary>Expect Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
  35.0
  </div>
</details>
<br>

## 2.3: Integer Division
Calculate the number of hits it will take to defeat the opponent. You may NOT use any imports. Use casting and integer division.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Step 1, 2.1 & 2.2 Code goes here */

    /** Step 2.3 */
    // TODO: Calculate and print the number of hits needed to defeat the opponent. Do NOT use any imports.
  }

}

```

<details>
  <summary>Expected Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
  13
  </div>
</details>
<br>

## 2.4: Update a variable
You received a powerbuff! Increase the player's damage by 30%. Then, calculate the opponent's new health if the player deals a hit.

```java
/** Main.java */

public class Main {
  
  public static void main(String[] args) {
    /** Step 1, 2.1, 2.2 & 2.3 Code goes here */

    /** Step 2.4 */
    // TODO: Increase the player's damage by 30%. Only use multiplication.
    // TODO: Calculate and print the opponent's new health after the player deals a hit
  }

}
```

<details>
  <summary>Expected Output</summary>

  <div style="border: 1px solid #ddd; padding: 10px; margin-top: 10px; border-radius: 5px; background-color: #f9f9f9;">
  43.0
  </div>
</details>
<br>