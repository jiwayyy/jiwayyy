<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ohm's Law and Resistors</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
        }
        .container {
            padding: 20px;
        }
        .content {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #4CAF50;
        }
        .illustration {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ohm's Law and Resistors</h1>
    </header>
    <nav>
        <a href="#ohms-law">Ohm's Law</a>
        <a href="#resistors">Resistors</a>
    </nav>
    <div class="container">
        <div id="ohms-law" class="content">
            <h2>Ohm's Law</h2>
            <h3>Definition</h3>
            <p>Ohm's Law states that the current through a conductor between two points is directly proportional to the voltage across the two points. The formula is given by V = IR, where V is the voltage, I is the current, and R is the resistance.</p>
            <h3>Circuit Picture</h3>
            <img src="ohms-law-circuit.jpg" alt="Ohm's Law Circuit" class="illustration">
            <h3>Applications</h3>
            <p>Ohm's Law is used in various electrical and electronic applications, including the design of electrical circuits, troubleshooting electrical issues, and understanding the relationship between voltage, current, and resistance in a circuit.</p>
            <h3>History</h3>
            <p>Ohm's Law was formulated by German physicist Georg Simon Ohm in 1827. It was a significant milestone in the field of electrical engineering, providing a mathematical model to explain the behavior of electrical circuits.</p>
            <h3>Circuit Analysis</h3>
            <p>Using Ohm's Law, one can analyze circuits to find unknown values of voltage, current, or resistance. This is essential in designing and troubleshooting electrical circuits.</p>
            <h3>Series and Parallel Circuits</h3>
            <p>In series circuits, resistances add up: R_total = R1 + R2 + ... + Rn. In parallel circuits, the reciprocals of the resistances add up: 1/R_total = 1/R1 + 1/R2 + ... + 1/Rn.</p>
            <h3>Examples</h3>
            <ul>
                <li>Series: Three resistors of 2Ω, 3Ω, and 5Ω in series have a total resistance of 10Ω.</li>
                <li>Parallel: Two resistors of 4Ω and 6Ω in parallel have a total resistance of 2.4Ω.</li>
                <li>Calculating voltage in a series circuit with a total resistance of 10Ω and a current of 2A: V = IR = 10Ω * 2A = 20V.</li>
                <li>Calculating current in a parallel circuit with a total resistance of 2.4Ω and a voltage of 12V: I = V/R = 12V / 2.4Ω = 5A.</li>
                <li>Finding resistance with a voltage of 15V and current of 3A: R = V/I = 15V / 3A = 5Ω.</li>
            </ul>
            <h3>References</h3>
            <p>APA Style references go here.</p>
        </div>
        <div id="resistors" class="content">
            <h2>Resistors</h2>
            <h3>Definition</h3>
            <p>A resistor is a passive electrical component that provides resistance to the flow of current in an electrical circuit. It is used to control the current and voltage within the circuit.</p>
            <h3>Picture</h3>
            <img src="resistor.jpg" alt="Resistor" class="illustration">
            <h3>How it Works and Applications</h3>
            <p>Resistors work by converting electrical energy into heat, thus reducing the current flow. They are used in various applications such as voltage regulation, signal conditioning, and as part of complex electronic circuits.</p>
            <h3>History</h3>
            <p>The concept of resistance was first identified by Georg Simon Ohm in the early 19th century. Since then, resistors have become an essential component in electronic circuits.</p>
            <h3>Electronic Symbol and Notation</h3>
            <p>The symbol for a resistor in circuit diagrams is a zigzag line (or a rectangle in some regions). It is denoted by the letter 'R'.</p>
            <h3>Different Types</h3>
            <ul>
                <li>Carbon Composition Resistors</li>
                <li>Metal Film Resistors</li>
                <li>Wirewound Resistors</li>
                <li>Variable Resistors</li>
            </ul>
            <h3>How to Read Resistor Values</h3>
            <p>Resistor values are indicated by colored bands. Each color corresponds to a specific number, and the arrangement of these colors determines the resistance value.</p>
            <img src="resistor-color-code.jpg" alt="Resistor Color Code" class="illustration">
            <h3>Examples</h3>
            <ul>
                <li>Brown-Black-Red-Gold: 1kΩ with ±5% tolerance</li>
                <li>Red-Violet-Orange-Gold: 27kΩ with ±5% tolerance</li>
                <li>Green-Blue-Brown-Silver: 560Ω with ±10% tolerance</li>
                <li>Yellow-Violet-Red-Gold: 4.7kΩ with ±5% tolerance</li>
                <li>Orange-Orange-Black-Gold: 33Ω with ±5% tolerance</li>
            </ul>
            <h3>References</h3>
            <p>APA Style references go here.</p>
        </div>
    </div>
</body>
</html>
