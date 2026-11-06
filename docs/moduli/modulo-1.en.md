# Module 1 — Welcome circle, binary, hardware teardown

**Theme (brochure):** welcome circle; binary logic from analog to digital; lab **“Let’s take it apart”**: learn the hardware by opening a phone.

!!! info "Our edition (Trento 2026/27)"
    - **Date:** Saturday 17 October 2026 · **Status:** **completed**
    - General logistics (venue, times, collaborators): [Calendar — Our edition](../calendario.md#edizione-trento).

**Facilitation:** at least **two adults** for the whole morning; phone opening and battery handling need trained adults.

### Typical schedule

| Block | Approximate time |
|-------|------------------|
| Part A — Welcome circle | 9:00–10:20 |
| Break | 10:20–10:40 |
| Part B — Binary logic (analog → digital) | 10:40–12:00 |
| Part C — Hardware lab | 12:00–13:20 |

**Audience (playbook):** the brochure edition is **12–15** with parents; this module recipe remains adaptable.

---

## Part A — Welcome circle

- **Welcome**, **expectations**, and **questions** from young people and adults.
- **Experience:** what do we already know about **digital technology**? What are we curious or worried about?
- Optional: **question box** for adults (anonymous questions for the facilitators).

### Circle questions

1. If you could invent a device, what would it do?
2. When you see a 3-year-old with a smartphone in hand, how do you feel?
3. In your opinion, how does a phone “know” where you touch the screen?
4. What would you like to ask whoever invented the internet or the smartphone?
5. Have you ever started something you then couldn’t stop?
6. Do you think we control our devices, or do they control us?

Questions 5 and 6 introduce the Disney short **Fantasia**, episode *The Sorcerer’s Apprentice*, to reflect on a force you can’t control.

## Break

## Part B — Binary logic, theory

*Sample schedule: 10:40–12:00 (80 min).*

Move from **analog to digital** with the main finger exercise, then the wave-and-grid metaphor on the board, and finally the exercise worksheets.

**Suggested timing (example, 80 min)**

| Block | Duration | Approximate time |
|-------|----------|------------------|
| Step 1 — Count in binary with one hand | 35 min | 10:40–11:15 |
| Step 2 — Copies drift apart | 25 min | 11:15–11:40 |
| Exercise sheets and wrap-up | ~20 min | 11:40–12:00 |

### Printable materials

PDFs to print for floor or table activities (cut out tokens if the sheet says so). The binary mat is for **Step 1**; the logic-gate mats are for the optional **extra** in Part B.

[:material-file-pdf-box: Download binary mat](modulo-1/files/tappetino-binario.pdf){ .md-button }
**Bit** (0/1) mat with tokens: to represent numbers and sequences in binary.

[:material-file-pdf-box: Download logic-gate mats](modulo-1/files/tappetini-porte-logiche.pdf){ .md-button }
Three pages of **mats** for logic gates (AND, OR, NOT, …) with tokens for inputs and output.

### Step 1 — Count in binary with one hand (0–31) (~35 min)

!!! important "Main exercise for Part B"
    The young people **experience** binary on their own fingers: five bits, numbers from 0 to 31, same logic as the tokens on the [binary mat](modulo-1/files/tappetino-binario.pdf).

Method inspired by *finger binary counting* as described on [Art of Memory — Finger Binary Counting](https://artofmemory.com/wiki/Finger_Binary_Counting/) (palm toward your face, fingers raised = **1** / on, fingers folded = **0** / off).

#### Finger values (one hand)

| Finger | Power of 2 | Value |
|--------|------------|-------|
| Thumb | 2⁰ | 1 |
| Index | 2¹ | 2 |
| Middle | 2² | 4 |
| Ring | 2³ | 8 |
| Pinky | 2⁴ | 16 |

The number is the **sum** of the values of the raised fingers. All raised = **31**; closed fist = **0**.

Explain to the young people: *“Each finger is a switch: up or down. The order you raise them doesn’t matter; what matters is **which** are up.”*

#### Mat and tokens

Align hand and mat: each finger matches a bit column; the 0/1 tokens on the mat repeat the same configuration. Have them try **3–4** numbers (e.g. 5, 10, 15) before going faster.

#### Table 0–31 (decimal, 5-bit binary, raised fingers)

Bits in order **pinky → thumb** (16, 8, 4, 2, 1), as on the mat.

| Dec | Binary | Raised fingers (ON) |
|-----|--------|---------------------|
| 0 | 00000 | closed fist |
| 1 | 00001 | thumb |
| 2 | 00010 | index |
| 3 | 00011 | thumb, index |
| 4 | 00100 | middle |
| 5 | 00101 | thumb, middle |
| 6 | 00110 | index, middle |
| 7 | 00111 | thumb, index, middle |
| 8 | 01000 | ring |
| 9 | 01001 | thumb, ring |
| 10 | 01010 | index, ring |
| 11 | 01011 | thumb, index, ring |
| 12 | 01100 | middle, ring |
| 13 | 01101 | thumb, middle, ring |
| 14 | 01110 | index, middle, ring |
| 15 | 01111 | thumb, index, middle, ring |
| 16 | 10000 | pinky |
| 17 | 10001 | thumb, pinky |
| 18 | 10010 | index, pinky |
| 19 | 10011 | thumb, index, pinky |
| 20 | 10100 | middle, pinky |
| 21 | 10101 | thumb, middle, pinky |
| 22 | 10110 | index, middle, pinky |
| 23 | 10111 | thumb, index, middle, pinky |
| 24 | 11000 | ring, pinky |
| 25 | 11001 | thumb, ring, pinky |
| 26 | 11010 | index, ring, pinky |
| 27 | 11011 | thumb, index, ring, pinky |
| 28 | 11100 | middle, ring, pinky |
| 29 | 11101 | thumb, middle, ring, pinky |
| 30 | 11110 | index, middle, ring, pinky |
| 31 | 11111 | thumb, index, middle, ring, pinky |

#### Progressive sequence in class

1. **Thumb and index only (0–3), ~8 min** — Count together from 0 to 3 several times. *“Now add just the middle finger and we’ll get to 7.”*
2. **Three fingers (0–7), ~7 min** — Repeat up to 7; then *“Does each new finger **double** how many numbers you can make?”*
3. **Five fingers (0–31), ~10 min** — Go up to 16 (pinky only), then 17, … up to 31. Celebrate **31** together.
4. **Pair games, ~7 min** — One shows fingers, the other says the number; then swap. Variant: one says a number, the other shows it.
5. **Quick round, ~3 min** — The facilitator calls random numbers; whoever answers first (correct hand) wins a symbolic point.

#### Circle questions (Step 1 wrap-up)

- With **five** fingers, how many distinct numbers can we make? Why is the maximum **31** and not 32?
- With **two hands** (ten fingers), how high can you go? *(1023 = 2¹⁰ − 1, as in the source.)*
- If we had a sixth “finger”, how many more numbers? What happens each time we add a bit?
- Keep these **bits** on or off in mind: in **Step 2** you’ll see the same idea as a “staircase” on the board.
- Eight bits make a **byte**: how many bytes do you need for a number larger than 31?

After **bits** on the fingers (Step 1), move on to **analog** and **digital** on the board.

### Step 2 — Copies drift apart (25 min)

#### Materials

- White and colored chalk
- Tracing paper / vellum with **coarse** and **fine** grids
- Tape
- Markers
- Clean squared paper

#### Part 1 — The wave and its copies (~7 min)

1. Ask a volunteer to draw a **wave** on the board with white chalk. You can say: *“Up and down, like an ocean wave, as regular as you can: two or three times from one side of the board to the other.”*
2. Draw two horizontal lines as **top and bottom limits**, so the wave stays in the space you’ll use with the grids.
3. A second student tries to **copy the same wave**, with a different color chalk, just above or below the first.
4. A third student does the same with a **third color**.

With all three waves visible, guide the group with these questions:

- Are they the same? **Where** are they most different?
- Everyone tried to copy perfectly. Why didn’t they succeed?
- If we tried a hundred times, would someone make it **identical**? How could we be sure?
- Is the first wave really perfectly regular? Did the first drawer want one peak higher than another?

**Infinity and precision**

- Where is the line **exactly**? Chalk has thickness. Is the wave in the center, on the top edge, or the bottom edge?
- How many points are on the wave between two of your fingers? Could you **count** them all?
- Could you describe this wave in words precisely enough that someone in another room draws **the exact same one**?

!!! abstract "Key idea (analog)"
    This is the **analog** world: the line moves without jumps, there are **infinitely** many possible points, and every copy adds a little **error**.

5. Erase the board. One student draws a **new wave** in white, still between the same limits: it will be the reference wave for the rest of the exercise.

#### Part 2 — The coarse grid (~8 min)

1. Tape the **coarse-grid** vellum over the wave.
2. One student traces the wave with a marker following one rule only: *“You can only move along the grid lines — up, down, left, or right.”*

Questions while they trace:

- Here the wave passes **between** two lines. Which do you follow? Who decides?
- Would another classmate have chosen the same line?

3. *(Recommended)* A second student copies the **staircase** onto clean squared paper by **counting squares**, without looking at the wave. The copies come out **identical**.

Group observations:

- What happened to the wave? What did it turn into?
- Where does the staircase lose the most: at the **peaks**, or in the middle? Why there?
- Does every “step” of the staircase have the same height? Why not? (The grid also captured hand tremor.)
- Is the staircase “wrong”, or just **different**?
- Chalk copies were never the same. Why did the staircase copies come out **equal**?
- What if the squares were taller than the whole wave?

#### Part 3 — The fine grid (~6 min)

1. Replace the coarse vellum with **fine-grid** vellum, still on the same wave.
2. One student traces it the same way, only along the lines.

Group observations:

- What changed compared to the coarse grid?
- Where does it still lose something?
- What did it cost us? (More squares, more choices, more work.)

!!! tip "Resolution"
    **Resolution** means how **fine** the grid is: the smaller the squares, the more the staircase looks like the wave — but the work increases.

#### Part 4 — How fine must it be to be perfect? (~4 min)

1. Place the two vellum sheets **side by side**, with the white wave still visible between them.

Questions to reach the final idea:

- How fine would the grid need to be before you can’t tell the staircase from the wave?
- If you see no difference, does that mean there **isn’t** any?
- Could the grid become so fine that it **is** the wave? What happens if we make it finer and finer, forever?
- If we zoomed in a lot on the finest staircase, what would you see?
- So: what would you rather send to someone far away — the wave or the staircase? Why?
- A computer “prefers” the staircase (or bits) to the continuous wave: link back to **Step 1**?

!!! abstract "Key idea (the digital compromise)"
    The staircase will **never** be the wave, but it can be good enough for our eyes and can be **copied exactly every time** — like the numbers 0–31 on the fingers in Step 1. That’s the compromise **digital** makes.

### Extra (optional) — Logic gates with the mats

??? tip "Extra"
    Use this block **only** if the group finishes the worksheets early (11:40–12:00) or if some young people ask for “another binary game”. It’s not required to reach Part C.

Print the [logic-gate mats](modulo-1/files/tappetini-porte-logiche.pdf) (three pages: **AND**, **OR**, **NOT**) and cut out the 0/1 tokens for inputs and output.

1. **NOT (one input):** one input token; the output is the opposite. *“If I put 1 here, what should come out? And if I put 0?”*
2. **AND (two inputs):** the output is 1 **only** if both inputs are 1. Try all four combinations on the mat.
3. **OR (two inputs):** the output is 1 if **at least** one input is 1.

In pairs or teams: an adult reads a sentence (*“Both parents say yes”* → AND; *“At least one wants ice cream”* → OR) and the young people set the tokens. Tie it to binary: *“Each input is a bit; the gate decides the output like a computer, one step at a time.”*

### George Boole and switches

In the nineteenth century **George Boole**, mathematician and teacher, showed that you can use algebra-like symbols to reason with only two values: **0** (off, no, false) and **1** (on, yes, true). You don’t need to memorize his biography: the useful idea is that **every switch** — or every raised finger in Step 1 — can only be in two positions.

Why is there no “2” in this world? In Boolean algebra **x² = x** (and, equivalently, **x(1 − x) = 0**): if x were 0 or 1, the equation holds; if x were 2 or ½, it doesn’t. It’s the same rule as the fingers: **up or down**, not “half raised”.

| Operation | How we think of it | With switches |
|-----------|-------------------|---------------|
| **AND** | Both must be 1 | Two switches **in series**: the lamp lights only if **x** and **y** are closed → **xy** |
| **OR** | At least one is 1 | Two switches **in parallel**: closing **x** or **y** is enough → **x + y − xy** (the formula avoids counting twice when both are 1) |

![AND circuit: switches in series](modulo-1/files/circuit-and.svg)

![OR circuit: switches in parallel](modulo-1/files/circuit-or.svg)

#### Wire-and-lamp lab (adults only for assembly)

**Materials**

- 1 × 1.5 V (AA) battery *or* 3 V battery pack with holder
- 2 toggle switches (or **normally open** push buttons)
- 1 × 1.5 V incandescent bulb *or* 1 LED with **series resistor** (≈330 Ω for 3 V)
- Single-core wire, electrical tape, 2 crocodile clips (optional)

**Safety** (as in [General rules](../regole-generali.md) and in Part C)

- **Adults only** connect the battery and handle wires; young people observe or operate switches under supervision.
- Use a **low-voltage** battery (1.5–3 V); **never** connect this lab to mains power.
- If you use an LED, **always** use a series resistor; if the bulb gets hot, disconnect and check the wiring.
- Exposed filaments or a hot battery: **disconnect the battery immediately**.

**Procedure (15–20 min)**

1. Build the **AND** circuit (switches in series) and try all four combinations of x and y.
2. Rewire as **OR** (parallel) and repeat.
3. Connect to the [PDF mats](modulo-1/files/tappetini-porte-logiche.pdf): *“When the lamp is on, which 0/1 token do we put on the output?”*

**Truth table — to complete (young people)**

| x | y | AND (xy) lamp | OR (x + y − xy) lamp |
|---|---|---------------|----------------------|
| 0 | 0 | | |
| 0 | 1 | | |
| 1 | 0 | | |
| 1 | 1 | | |

??? note "Truth table — solution (facilitators)"
    | x | y | AND (xy) | OR (x + y − xy) |
    |---|---|----------|-----------------|
    | 0 | 0 | 0 | 0 |
    | 0 | 1 | 0 | 1 |
    | 1 | 0 | 0 | 1 |
    | 1 | 1 | 1 | 1 |

*Idea and circuits inspired by the post from [@Math_files on X](https://x.com/Math_files) (MathFiles).*

---

## Part C — Let’s take it apart: open a phone to see the hardware {#parte-c-dentro-i-dispositivi}

*Sample schedule: 12:00–13:20.*

**Intent (brochure):** show **what’s inside** a smartphone — not magic, but boards, battery, chips, **billions of tiny switches** (link to Part B). The teaching goal matches the old “multi-machine tour,” but the **hands-on focus** is the phone.

!!! tip "Playbook variant"
    If you prefer **not** to open a phone, use a **dummy model** or **approved teardown** photos/video only — or keep an **open desktop** on the table for scale and observe phones from the outside.

### Materials

- Lab **smartphone**: **non-working**, **wiped**, battery **not swollen** or damaged; common model helps (standard screws)
- Small Phillips / Torx drivers (phone repair kit), suction cup if needed, **plastic** pry tools, screw trays
- **Anti-static mat** or dry surface; labels or small whiteboard to name parts
- Optional: magnifier or USB microscope
- Optional **quick extension** (5–10 min): **desktop** or **laptop** opened *only* to compare visible RAM/CPU with a soldered SoC

### Safety (mandatory)

- **Adults only** open the phone and handle screws, flex cables, and battery; young people **observe** at a safe distance and can **point** or **sketch** what they see.
- **Do not** force tools; if the case won’t open safely, **stop** and use photos/model only.
- **Do not** puncture, bend, or heat the battery; if it is **swollen**, **do not** disassemble — use photos only.
- **Do not** take apart wall chargers or any high-voltage parts.
- Eye protection if prying rigid plastic that might chip.
- No personal data on the device.

### Suggested flow

1. **Intro (5 min)** — *“In binary we talked ON/OFF; here they’re transistors so small they form chips.”*
2. **Clear the table, “before” photo (5 min)** — Adult shows where screws go; young people sketch the closed phone.
3. **Guided opening (25–35 min)** — Typical steps (order varies): **SIM tray**, back screws, separate **back** / **screen** carefully for **flex cables**, **battery** *only if safe for that model* — otherwise **do not force**.
4. **Parts map (15–20 min)** — Name: main **board**, **SoC** (often CPU/GPU/RAM), **camera** module(s), **antennas**, connectors. Link to bits: *“Where are the billions of switches?”*
5. **Close + reflection (10 min)** — Surprises? Repair vs recycling (preview Module 2).

### Group questions

- What is **soldered** vs **replaceable**? Why does that matter for repair?
- Where does the **battery** sit in the phone’s energy path?
- How does this lab connect to **waves** and the **grid** from Part B?

!!! abstract "Key idea"
    A smartphone is a **miniaturized computer**: **processing**, **memory**, **storage**, **power** in a tight space. The **bits** from Part B are the same idea at microscopic scale — hence “Let’s take it apart” to demystify the object.

---

## Operational rules for this module

See also [General rules](../regole-generali.md). In short:

- All facilitating adults present for the **entire** module; whoever is not speaking stays at the back and helps with supervision.
- Photocopies kept to a minimum; **a notebook for each young person**.
- Recap of the previous session on the board (for module 1: introduction to the program).
- **License stamp** at the end of the session.
