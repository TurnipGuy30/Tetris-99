[First Page](README.md) | [Introduction](Intro.md) | Rules and Beginner Skills | [Intermediate Skills](Intermediate.md) | [Advanced Skills](Advanced.md) | [Other Information](Other.md)

# Rules and Beginner Skills

This is where everyone starts: the very basics.

## Tetriminoes

There are seven types of Tetriminoes (Tetris pieces), each made up of four joined blocks. They are named after the letters they look like:

<table>

<tr>
<th>Shape</th>
<th>Colour</th>
<th>Diagram</th>
</tr>

<tr>
<td>

<code>J</code>
</td>
<td>Blue</td>
<td>
<pre>J - -<br>J J J</pre>
</td>
</tr>

<tr>
<td>
<code>L</code>
</td>
<td>Orange</td>
<td>
<pre>- - L<br>L L L</pre>
</td>
</tr>

<tr>
<td>
<code>S</code>
</td>
<td>Green</td>
<td>
<pre>- S S<br>S S -</pre>
</td>
</tr>

<tr>
<td>
<code>Z</code>
</td>
<td>Red</td>
<td>
<pre>Z Z -<br>- Z Z</pre>
</td>
</tr>

<tr>
<td>
<code>O</code>
</td>
<td>Yellow</td>
<td>
<pre>O O<br>O O</pre>
</td>
</tr>

<tr>
<td>
<code>I</code>
</td>
<td>Cyan</td>
<td>
<pre>I I I I</pre>
</td>
</tr>

<tr>
<td>
<code>T</code>
</td>
<td>Purple</td>
<td>
<pre>- T -<br>T T T</pre>
</td>
</tr>

</table>

Mentally associating the colours with the shapes will be helpful as the game gets faster, as you will not have to look at the Mino to know the shape.

## Tetrimino Randomisation

Tetriminoes drop from the top of the **Matrix** by what is known as the **Bag Randomisation** method. Imagine a bag that hold seven Tetriminoes; one of each kind. Now, imagine one of those Minoes is pulled out of the bag at random, and drops. When that Mino is locked down, another is pulled out of the bag, and this repeats. When the bag is empty, you get a new bag, and another, and more until the game is over. This means that getting two of the same Mino in a row is rare, and three in eight is impossible.

## Tetrimino Notation

This guide will use the following notation for **Matrix** diagrams:

| Symbol | Meaning |
|:--|:--|
| `-` | empty slot |
| `X` | filled slot (non-specific) |
| `J`/`L`/`S`/`Z`/`O`/`I`/`T` | filled with Mino of that shape |

## Screen Layout

- The big rectangle in the centre of the screen is your **Matrix**. This is where you drop Tetriminoes, and where **Junk** appears.
- The vertical bar on the left shows how much **Junk** other players are sending you.
- The small boxes all around your **Matrix** are other player's **Matrices**.
- The box on the top-left is your **Hold Queue**; this is where your Held Minoes will be stored.
- The boxes on the top-right and going down make up the **Next Queue**. When your current Tetrimino is Locked Down, the Mino at the top of the **Next Queue** will drop.

## Controls

**Tetris 99** has very simple controls, however it can take a while to get used to constantly pressing various buttons.

| Button | Control |
|:--|:--|
| `Left`/`Right` | Move Tetrimino |
| `Down` | **Soft Drop** |
| `Up` | **Hard Drop** |
| `A` | Rotate Tetrimino clockwise |
| `B` | Rotate Tetrimino counterclockwise |
| `L`/`R` | Hold |

> The directional controls are related to the `D-Pad` by default, but they can be configured to the `Control Stick` (or Left Stick) in the **Options** menu.

- After Tetriminoes land on a surface, there is a window of time to move them before they **Lock Down** and the next Mino drops.
- **Soft Dropping** makes the Mino fall faster than normal.
- **Hard Dropping** a Mino makes it automatically drop and **Lock Down** in the location of the **Ghost Piece**. Always be careful with **Hard Drops**.
- Holding a Mino makes it go into the **Hold Queue**. Minoes in the **Hold Queue** can be held for as long as you want. If there is already a Mino in the **Hold Queue**, it gets swapped out. After **Holding** a Mino, you cannot **Hold** again until your current Mino is **Locked Down**. This means the **Hold Queue** must be used wisely.

## **Targeting**

You can use the `C-Stick` (or Right Stick) to choose your **Targeting** method. Your Target is who you send **Junk** to. The four options are **Random** (default), **Attackers**, **Badges**, and **K.Os**.

| Targeting | Description |
|:--|:--|
| `Random` | Randomly sends **Junk** to other players |
| `Attackers` | Sends **Junk** to players who have attacked you |
| `Badges` | Sends **Junk** to the player with the most **Badges** |
| `K.Os` | Sends **Junk** to the player who has defeated the most players |

## **Combos**

If you clear lines with many consequetive Tetriminoes, you gain a **Combo**. This **Combo** keeps going until you **Lock Down** a Mino without a **Line Clear**. The **Combo** is shown in the top-left of the screen.

## **T-Spins** & **T-Spin Singles**

When lowering a `T`-Mino into a tight spot like the following:

```
|- - - - - T - - -|
|- - - - T T - - -|
|- - - - - T - - -|
|- - S - - - - - -|
|- - S S - - L L -|
|- - J S - - - L -|
|- - J O O - T L -|
|- J J O O T T T -|
===================
```

You can spin the Mino inside the slot to fill the space and perform a T-Spin. In the above example, lower the Mino into the space, and press `B` (rotate counterclockwise) before the it **Locks Down**. This gives a pop-up on the left that says "**T-Spin**".

> Remember: a **T-Spin** only occurs when a `T`-Mino **Locks Down** in a position that it could only access by rotating.

If you manage to clear a line using this spun Mino, it's called a **T-Spin Single**.

## Clearing Multiple Lines & **Tetrises**

With so many kinds of Tetriminoes, it is sometimes easy to clear multiple lines at once. The best of these **Multi-Line Clears** is the **Tetris Line Clear**, commonly known as a **Tetris**. A **Tetris** is when four lines are cleared with a single Mino; this is only possible with the `I`-Mino, as this is the only Mino that can reach across four rows. Performing **Tetrises** can be tricky at first, but with practice they becomes second-nature.

**Tetrises** involve filling all but one column, each full to at least four rows. This can easily be done in the left or right 9 columns, leaving the one on the edge. Here's an example:

```
| I - - - - - - - - - |
| I - - - - - - - - - |
| I - - - - - - - - - |
| I - - - - - - - - - |
| - - - - - - - - - - |
| - J - - O O - Z - - |
| - J J J O O Z Z S S |
| - I I I I T Z S S L |
| - O O J T T T L L L |
| - O O J J J I I I I |
=======================
```

Like the **T-Spin**, this a very helpful technique. You can start using this strategy right away.

## Sending **Junk**

Clearing multiple lines at once sends more **Junk** to opponents.

| Lines cleared | **Junk** sent |
|:--|:--|
| 1 | 0 |
| 2 | 1 |
| 3 | 2 |
| 4 (**Tetris**) | 4 |

If you clear one, two, or three lines using a **T-Spin** (more on those later), it sends double the **Junk**. This means that a **T-Spin Triple** sends six lines, which is more than a **Tetris**!

---

> Practice:
> - **Hard Drops**
> - **Tetrises**

[Next Page: Intermediate Skills](Intermediate.md)
