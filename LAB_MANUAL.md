# FULL STACK FRAMEWORKS LAB MANUAL

## STUDENT INFORMATION

| Field | Details |
|-------|--------|
| **Roll Number** | CB.SC.U4CSE23720 |
| **Student Name** | Guru.D |
| **Course Code** | 23CSE461 |
| **Course Name** | Full Stack Frameworks |
| **GitHub Profile** | https://github.com/Guru006-Dev |
| **Project Repository** | https://github.com/Guru006-Dev/react-math-assignments |
| **Live Application** | https://react-math-assignments.vercel.app/ |
| **Semester/Year** | 2026 |

---

## COURSE INFORMATION

| Category | Details |
|----------|----------|
| **Course Code** | 23CSE461 |
| **Course Name** | FULL STACK FRAMEWORKS |ok
| **Department** | Computer Science and Engineering |
| **Credits** | Lab Course |

### Course Objectives

| No. | Objective |
|-----|----------|
| 1 | Understand how web development has become easier with the introduction of frameworks |
| 2 | Learn full stack web development principles and practices |
| 3 | Develop, optimize and maintain websites using full-stack frameworks |
| 4 | Master important full stack frameworks for modern web development |

### Course Outcomes

| Code | Outcome Description |
|------|--------------------|
| **CO1** | Learn how to develop single page applications (SPAs) efficiently using front-end framework |
| **CO2** | Learn to use backend frameworks to develop web and mobile applications robustly |
| **CO3** | Learn to build highly available and scalable internet applications using document databases |
| **CO4** | Design and develop full stack web projects using front-end, back-end and database frameworks |

---

## SYLLABUS

### Unit I - React JS
Creating and using components, bindings, props, states, events, Working with components, Conditional rendering, Building forms, Getting data from RESTful APIs, Routing, CRUD with Firebase, Redux, React and Redux, Function vs. class based components, Hooks.

### Unit II - Express JS
Node JS – Basics, setup, console, command utilities, modules, events, Express JS – Routing, HTTP methods, CSS, Bootstrap, JavaScript, React, Redux, Node, Express, URL building, Templates, Static files, Form data, Database, Cookies, Sessions, Authentication, RESTful APIs, Scaffolding, Error handling, Debugging.

### Unit III - Mongo DB
Mongo DB ecosystem, Importing and Exporting data, Mongo query language, Updating documents, Aggregation framework, System and user generated variables, Scheme validation, Data modelling, Indexing, Performance.

---

## REFERENCE MATERIALS

| Technology | Documentation URL |
|------------|-------------------|
| ReactJS | https://react.dev/ |
| NodeJS | https://nodejs.org/docs/ |
| MongoDB | https://www.mongodb.com/docs/ |
| ExpressJS | https://expressjs.com/ |
| JavaScript | https://developer.mozilla.org/en-US/docs/Web/JavaScript |
| HTML | https://developer.mozilla.org/en-US/docs/Web/HTML |
| Responsive HTML | https://web.dev/responsive-web-design-basics/ |
| CSS | https://developer.mozilla.org/en-US/docs/Web/CSS |

---

## LIST OF EXPERIMENTS

| Sl.No | Ex.No | Date | Title of the Experiments | Page No. |
|-------|-------|------|--------------------------|----------|
| 1 | 1 | | Mathematical Operations (Factorial, Fibonacci, Prime) - ReactJS | 7 |
| 2 | 2 | | Sum of Digits Calculator - ReactJS | 9 |
| 3 | 3 | | Question Paper Set Selector (Class & Function) - ReactJS | 11 |
| 4 | 4 | | Basic Calculator - ReactJS | 13 |
| 5 | 5 | | Kids Calculator Game - ReactJS | 15 |
| 6 | 6 | | Display First N Natural Numbers - ReactJS | 17 |
| 7 | 7 | | Armstrong Number Checker - ReactJS | 19 |
| 8 | 8 | | Factorial Calculator (Standalone) - ReactJS | 21 |
| 9 | 9 | | Greatest of 3 Numbers - ReactJS | 23 |
| 10 | 10 | | 4-Box Ball Game - ReactJS | 25 |

---

<div style="page-break-after: always;"></div>

## EX.NO: 1 - MATHEMATICAL OPERATIONS (FACTORIAL, FIBONACCI, PRIME)

### AIM
Create a ReactJS application to perform three mathematical operations:
- Calculate factorial of a number
- Generate Fibonacci series
- Check if a number is prime

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-a

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/QuestionA.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| QuestionA.jsx | Main component with all three mathematical operations |
| App.jsx | Routing configuration |
| index.css | Global styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing input and results state | QuestionA.jsx |
| Factorial Algorithm | Iterative multiplication for n! | QuestionA.jsx |
| Fibonacci Algorithm | Generating sequence using iteration | QuestionA.jsx |
| Prime Check Algorithm | Checking divisibility up to √n | QuestionA.jsx |
| Multiple Function Calls | Executing all three operations together | QuestionA.jsx |

### ALGORITHMS

**Factorial:**
```
1. If n < 0: return invalid
2. If n = 0 or 1: return 1
3. result = 1
4. For i from 2 to n: result *= i
5. Return result
```

**Fibonacci:**
```
1. Initialize array with [0, 1]
2. For i from 2 to n:
3.   fib[i] = fib[i-1] + fib[i-2]
4. Return array
```

**Prime Check:**
```
1. If n < 2: return false
2. If n = 2: return true
3. If n is even: return false
4. For i from 3 to √n (step 2):
5.   If n % i = 0: return false
6. Return true
```

### KEY FEATURES
- Single input generates all three results
- Efficient algorithms for each operation
- Clear result display with labels
- Handles edge cases (negative, zero, etc.)

### OUTPUT FORMAT

| Operation | Output Display |
|-----------|----------------|
| **Factorial** | n! = result (e.g., 5! = 120) |
| **Fibonacci** | First n terms as comma-separated values |
| **Prime Check** | Boolean result with ✓ (Prime) or ✗ (Not Prime) |

### TEST CASES

| Input | Factorial | Fibonacci (First n) | Is Prime? |
|-------|-----------|---------------------|----------|
| 5 | 120 | 0, 1, 1, 2, 3 | ✓ Yes |
| 7 | 5040 | 0, 1, 1, 2, 3, 5, 8 | ✓ Yes |
| 10 | 3628800 | 0, 1, 1, 2, 3, 5, 8, 13, 21, 34 | ✗ No |

### RESULT
Successfully implemented a comprehensive mathematical operations component in ReactJS demonstrating factorial, Fibonacci, and prime number algorithms.

---

<div style="page-break-after: always;"></div>

## EX.NO: 2 - SUM OF DIGITS CALCULATOR

### AIM
Read a number and provide the sum of all its digits.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-b

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/QuestionB.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| QuestionB.jsx | Component for sum of digits calculation |
| App.jsx | Routing configuration |
| index.css | Global styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing input number and result | QuestionB.jsx |
| String Manipulation | Converting number to string for digit extraction | QuestionB.jsx |
| Array Methods | Iterating through digits | QuestionB.jsx |
| parseInt() Function | Converting string digits to numbers | QuestionB.jsx |
| Math.abs() | Handling negative numbers | QuestionB.jsx |

### ALGORITHM
```
1. Accept number from user
2. Convert to absolute value (handle negatives)
3. Convert number to string
4. Initialize sum = 0
5. For each character in string:
6.   Convert to integer
7.   Add to sum
8. Display individual digits and sum
```

### EXAMPLE CALCULATION
```
Input: 12345
Digits: 1, 2, 3, 4, 5
Calculation: 1 + 2 + 3 + 4 + 5 = 15
Result: 15
```

### KEY FEATURES

| Feature | Description |
|---------|------------|
| **Input Support** | Accepts any integer (positive or negative) |
| **Digit Breakdown** | Shows individual digits separated by + |
| **Formula Display** | Visual calculation formula |
| **Examples** | Reference cards with sample calculations |
| **Visual Addition** | Clear step-by-step addition representation |

### TEST CASES

| Input Number | Digits | Sum |
|--------------|--------|-----|
| 123 | 1 + 2 + 3 | 6 |
| 9876 | 9 + 8 + 7 + 6 | 30 |
| 555 | 5 + 5 + 5 | 15 |
| 12345 | 1 + 2 + 3 + 4 + 5 | 15 |
| -456 | 4 + 5 + 6 | 15 |

### OUTPUT FORMAT
```
Original Number: 12345
Digits: 1 + 2 + 3 + 4 + 5
Sum of Digits: 15
Calculation: 1 + 2 + 3 + 4 + 5 = 15
```

### RESULT
Successfully created a sum of digits calculator with visual breakdown and clear presentation of the calculation process.

---

<div style="page-break-after: always;"></div>

## EX.NO: 3 - QUESTION PAPER SET SELECTOR

### AIM
Create a ReactJS application to determine question paper set based on roll number:
- Odd roll number → Set 1
- Even roll number → Set 2

Implement using both **Class Component** and **Function Component**.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-c

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/QuestionC.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| QuestionC.jsx | Main component containing both implementations |
| App.jsx | Routing configuration |
| index.css | Global styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React Function Component | Modern approach with hooks | QuestionC.jsx (QuestionCFunction) |
| React Class Component | Traditional approach with class syntax | QuestionC.jsx (QuestionCClass) |
| useState Hook | State management in function component | QuestionCFunction |
| this.state | State management in class component | QuestionCClass |
| Modulo Operator (%) | Determining odd/even | Both components |
| Event Handling | Button clicks and input changes | Both components |

### ALGORITHM
```
1. Accept roll number from user
2. Validate input (must be positive integer)
3. Calculate rollNumber % 2
4. If result = 0: Set = 2 (Even)
5. If result = 1: Set = 1 (Odd)
6. Display assigned set
```

### FUNCTION COMPONENT IMPLEMENTATION
```jsx
function QuestionCFunction() {
  const [rollNumber, setRollNumber] = useState('');
  const [result, setResult] = useState(null);
  
  const determineSet = () => {
    const roll = parseInt(rollNumber);
    const set = roll % 2 === 0 ? 2 : 1;
    setResult({ rollNumber: roll, set, isEven: roll % 2 === 0 });
  };
}
```

### CLASS COMPONENT IMPLEMENTATION
```jsx
class QuestionCClass extends React.Component {
  constructor(props) {
    super(props);
    this.state = { rollNumber: '', result: null };
  }
  
  determineSet = () => {
    const roll = parseInt(this.state.rollNumber);
    const set = roll % 2 === 0 ? 2 : 1;
    this.setState({ result: { rollNumber: roll, set, isEven: roll % 2 === 0 } });
  }
}
```

### KEY FEATURES

| Feature | Description |
|---------|------------|
| **Dual Implementation** | Side-by-side comparison of function and class components |
| **Identical Logic** | Same functionality with different syntax approaches |
| **Visual Distinction** | Different color schemes for each component type |
| **Set Assignment** | Clear display of assigned question paper set |
| **Input Validation** | Ensures valid roll number entry |

### TEST CASES

| Roll Number | Type | Assigned Set |
|-------------|------|-------------|
| 1 | Odd | Set 1 |
| 2 | Even | Set 2 |
| 7 | Odd | Set 1 |
| 10 | Even | Set 2 |
| 23 | Odd | Set 1 |
| 48 | Even | Set 2 |

### COMPARISON: FUNCTION VS CLASS COMPONENTS

| Aspect | Function Component | Class Component |
|--------|-------------------|-----------------|
| **Syntax** | Simple, concise | More verbose |
| **State Management** | useState Hook | this.state, this.setState() |
| **Lifecycle** | useEffect Hook | componentDidMount, etc. |
| **this Binding** | ❌ Not needed | ✅ Required for methods |
| **Code Length** | Shorter | Longer |
| **Modern Standard** | ✅ Recommended (2023+) | ⚠️ Legacy support |
| **Performance** | Slightly Better | Standard |
| **Learning Curve** | Easier | Moderate |

### RESULT
Successfully demonstrated both function and class component implementations for the same functionality, highlighting the evolution of React development patterns.

---

<div style="page-break-after: always;"></div>

## EX.NO: 4 - BASIC CALCULATOR

### AIM
Create a fully functional calculator program using ReactJS with all basic arithmetic operations.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-d

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/QuestionD.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| QuestionD.jsx | Calculator component with all operations |
| App.jsx | Routing configuration |
| index.css | Calculator grid and button styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing calculator state and operations | QuestionD.jsx |
| Multiple State Variables | Display, previousValue, operation, waitingForOperand | QuestionD.jsx |
| Event Handling | Button click handlers | QuestionD.jsx |
| CSS Grid Layout | Calculator button layout | index.css |
| Switch Statement | Operation execution | QuestionD.jsx |

### STATE MANAGEMENT
```jsx
const [display, setDisplay] = useState('0');
const [previousValue, setPreviousValue] = useState(null);
const [operation, setOperation] = useState(null);
const [waitingForOperand, setWaitingForOperand] = useState(false);
```

### CALCULATOR OPERATIONS

| Operation | Symbol | Function |
|-----------|--------|----------|
| Addition | + | a + b |
| Subtraction | − | a - b |
| Multiplication | × | a * b |
| Division | ÷ | a / b |
| Modulo | % | a % b |
| Sign Toggle | +/- | value * -1 |
| Clear | AC | Reset all |
| Decimal | . | Add decimal point |

### ALGORITHM
```
1. User inputs first number via digit buttons
2. User selects operation (+, -, ×, ÷, %)
3. Store first value and operation
4. User inputs second number
5. On pressing '=', calculate result
6. Display result
7. Support chaining operations
```

### CALCULATOR LAYOUT
```
┌─────────────────────────┐
│      Display (0)        │
├──────┬──────┬──────┬────┤
│  AC  │ +/-  │  %   │ ÷  │
├──────┼──────┼──────┼────┤
│  7   │  8   │  9   │ ×  │
├──────┼──────┼──────┼────┤
│  4   │  5   │  6   │ -  │
├──────┼──────┼──────┼────┤
│  1   │  2   │  3   │ +  │
├──────┴──────┼──────┼────┤
│      0      │  .   │ =  │
└─────────────┴──────┴────┘
```

### KEY FEATURES

| Category | Features |
|----------|----------|
| **Operations** | Addition, Subtraction, Multiplication, Division, Modulo |
| **Number Support** | Integers, Decimals, Negative numbers |
| **Special Functions** | Clear (AC), Sign Toggle (+/-) |
| **Advanced** | Chain calculations, Operation chaining |
| **UI/UX** | Responsive grid layout, Professional design |

### TEST CASES

| Calculation | Expected Result |
|-------------|----------------|
| 5 + 3 | 8 |
| 10 - 7 | 3 |
| 6 × 4 | 24 |
| 15 ÷ 3 | 5 |
| 17 % 5 | 2 |
| 2.5 + 3.7 | 6.2 |
| 8 ÷ 0 | Error (prevented) |

### EDGE CASES HANDLED

| Case | Handling |
|------|----------|
| Division by Zero | ✅ Prevents operation, returns 0 |
| Multiple Decimals | ✅ Ignores additional decimal points |
| Operation Chaining | ✅ Continues calculation with result |
| Display Overflow | ✅ Handles large numbers |
| Invalid Input | ✅ Resets to valid state |

### RESULT
Successfully implemented a fully functional calculator in ReactJS with professional UI and comprehensive operation support.

---

<div style="page-break-after: always;"></div>

## EX.NO: 5 - KIDS CALCULATOR GAME

### AIM
Create a calculator program with the addition of game concepts for kids, making math learning fun and engaging through gamification.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-ef

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/QuestionEF.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| QuestionEF.jsx | Kids calculator game component |
| App.jsx | Routing configuration |
| index.css | Game-specific styling and animations |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing calculator and game state | QuestionEF.jsx |
| Game State Management | Score, streak, total calculations | QuestionEF.jsx |
| useEffect Hook | Handling celebration animations | QuestionEF.jsx |
| Conditional Rendering | Dynamic emoji and messages | QuestionEF.jsx |
| CSS Animations | Pulse and fade effects | index.css |
| Random Selection | Encouragement messages | QuestionEF.jsx |

### GAME STATE VARIABLES
```jsx
const [score, setScore] = useState(0);
const [streak, setStreak] = useState(0);
const [totalCalculations, setTotalCalculations] = useState(0);
const [showCelebration, setShowCelebration] = useState(false);
const [currentEmoji, setCurrentEmoji] = useState('🧮');
```

### GAMIFICATION ELEMENTS

#### 1. Score System
- Points awarded for each calculation
- Formula: `points = floor(abs(result) / 10) + 10`
- Cumulative score tracking

#### 2. Streak Counter
- Increments with each successful calculation
- Resets on game reset
- Triggers emoji upgrades

#### 3. Emoji Progression

| Streak Level | Emoji | Description |
|--------------|-------|-------------|
| Start | 🧮 | Initial state |
| 1-3 | 🎉 | Correct calculation |
| 4-6 | 🌟 | Milestone achieved |
| 7-9 | 🚀 | Super performance |
| 10+ | 🧠 | Genius level |

#### 4. Encouragement Messages
Random selection from:
- "Great job!"
- "You're a math star!"
- "Amazing!"
- "Keep going!"
- "Fantastic!"
- "You're on fire!"
- "Brilliant!"
- "Superb!"

### ALGORITHM
```
1. User performs a calculation
2. On pressing '=':
   a. Calculate result
   b. Award points based on result magnitude
   c. Increment streak counter
   d. Update total calculations
   e. Determine emoji based on streak
   f. Show random encouragement
   g. Trigger celebration animation
3. Display updated score, streak, total
4. Reset game option available
```

### SCORE CALCULATION EXAMPLE
```
Calculation: 50 + 30 = 80
Points = floor(80 / 10) + 10 = 8 + 10 = 18 points
New Score = Previous Score + 18
Streak = Streak + 1
```

### KEY FEATURES

| Category | Features |
|----------|----------|
| **Calculator** | All arithmetic operations, Decimal support, Clear & Reset |
| **Scoring** | Real-time score tracking, Points based on calculation magnitude |
| **Progression** | Streak counter, Progressive emoji rewards, Total calculations |
| **Feedback** | Celebration animations, Random encouragement messages |
| **Education** | Fun math practice, Positive reinforcement, Confidence building |

### EDUCATIONAL BENEFITS

| Benefit | How It Helps |
|---------|-------------|
| **Engagement** | Makes math practice fun and interactive |
| **Motivation** | Positive reinforcement through rewards |
| **Progress** | Visual tracking of improvements |
| **Practice** | Encourages repeated calculations |
| **Confidence** | Builds self-esteem through achievements |

### GAME MECHANICS SUMMARY

| Mechanic | Purpose | Implementation |
|----------|---------|----------------|
| **Score** | Track performance | +10-50 points per calculation |
| **Streak** | Encourage consistency | Increments with each = press |
| **Emojis** | Visual rewards | Changes based on streak level |
| **Messages** | Positive feedback | Random selection from 8 options |
| **Animation** | Celebration | 1.5s pulse effect |

### GAME INTERFACE LAYOUT
```
┌─────────────────────────────────┐
│  Score: 120  │ Streak: 5🔥 │ Total: 8  │
├─────────────────────────────────┤
│          🌟 (Emoji)            │
│      "You're Amazing!"         │
├─────────────────────────────────┤
│      Calculator Display        │
│     [Calculator Buttons]       │
│     [AC] [Reset Game] [÷]      │
│      [7] [8] [9] [×]          │
│      [4] [5] [6] [-]          │
│      [1] [2] [3] [+]          │
│      [  0   ] [.] [=✨]       │
└─────────────────────────────────┘
```

### CELEBRATION ANIMATION

| Property | Value |
|----------|-------|
| **Trigger** | On calculation completion (= button) |
| **Duration** | 1.5 seconds |
| **Effect** | Pulse animation on emoji |
| **Message** | Random encouragement phrase |
| **Transition** | Smooth fade-in / fade-out |

### RESULT
Successfully created an educational kids calculator game that combines mathematical operations with engaging game mechanics, making learning fun and rewarding for children.

---

<div style="page-break-after: always;"></div>

## EX.NO: 6 - DISPLAY FIRST N NATURAL NUMBERS

### AIM
Design a ReactJS application to display the first N natural numbers in a grid layout.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-6

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/Question6.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| Question6.jsx | Component to generate and display natural numbers |
| App.jsx | Routing configuration |
| index.css | Global styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing input value and generated numbers | Question6.jsx |
| Array.from() Method | Creating array of sequential numbers | Question6.jsx |
| Array Mapping | Rendering each number in grid | Question6.jsx |
| CSS Grid Layout | Displaying numbers in responsive grid | Question6.jsx (inline styles) |
| Conditional Rendering | Showing results only when generated | Question6.jsx |

### ALGORITHM
```
1. Accept input N from user
2. Validate N is a positive integer
3. Create array using Array.from({length: N}, (_, i) => i + 1)
4. Display numbers in a grid layout
5. Show count and range information
```

### KEY FEATURES

| Feature | Description |
|---------|-------------|
| **Grid Display** | Numbers shown in auto-filling grid layout |
| **Visual Cards** | Each number in styled card with gradient |
| **Scrollable** | Large number sets in scrollable container |
| **Clear Function** | Reset and clear functionality |
| **Input Validation** | Ensures positive integer input |

### TEST CASES

| Input (N) | Output | Number Count |
|-----------|--------|--------------|
| 5 | 1, 2, 3, 4, 5 | 5 numbers |
| 10 | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 | 10 numbers |
| 20 | 1-20 in grid | 20 numbers |
| 50 | 1-50 in scrollable grid | 50 numbers |

### OUTPUT FORMAT
- Grid of numbered cards with gradient background
- Each card displays one natural number
- Shows range (1 to N) and total count
- Formula display: Natural numbers = {1, 2, 3, ..., n}

### RESULT
Successfully implemented a natural numbers generator with responsive grid layout and visual card display for each number.

---

<div style="page-break-after: always;"></div>

## EX.NO: 7 - ARMSTRONG NUMBER CHECKER

### AIM
Implement a ReactJS program to check whether a given number is an Armstrong number (Narcissistic number).

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-7

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/Question7.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| Question7.jsx | Armstrong number checker component |
| App.jsx | Routing configuration |
| index.css | Global styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing number input and result | Question7.jsx |
| String Manipulation | Converting number to array of digits | Question7.jsx |
| Math.pow() Function | Calculating power of each digit | Question7.jsx |
| Array reduce() Method | Summing powers of digits | Question7.jsx |
| Conditional Styling | Different colors for result types | Question7.jsx |

### ALGORITHM
```
1. Accept number from user
2. Convert number to string and extract digits
3. Count number of digits (n)
4. For each digit d:
   Calculate d^n
5. Sum all the powers
6. Compare sum with original number
7. If equal: Armstrong Number
   Else: Not Armstrong Number
```

### ARMSTRONG NUMBER DEFINITION
A number is called Armstrong number if:
**sum of (each digit)^(number of digits) = original number**

### EXAMPLES

| Number | Calculation | Result |
|--------|-------------|--------|
| 153 | 1³ + 5³ + 3³ = 1 + 125 + 27 = 153 | ✓ Armstrong |
| 370 | 3³ + 7³ + 0³ = 27 + 343 + 0 = 370 | ✓ Armstrong |
| 9474 | 9⁴ + 4⁴ + 7⁴ + 4⁴ = 6561 + 256 + 2401 + 256 = 9474 | ✓ Armstrong |
| 123 | 1³ + 2³ + 3³ = 1 + 8 + 27 = 36 | ✗ Not Armstrong |

### KEY FEATURES

| Feature | Description |
|---------|-------------|
| **Detailed Breakdown** | Shows calculation step-by-step |
| **Visual Result** | Color-coded result (blue for Armstrong, pink for not) |
| **Examples Section** | Common Armstrong numbers shown |
| **Calculation Display** | Powers and sum clearly displayed |
| **Definition Box** | Educational information included |

### TEST CASES

| Input | Digits | Calculation | Is Armstrong? |
|-------|--------|-------------|---------------|
| 0 | 1 digit | 0¹ = 0 | ✓ Yes |
| 9 | 1 digit | 9¹ = 9 | ✓ Yes |
| 153 | 3 digits | 1³ + 5³ + 3³ = 153 | ✓ Yes |
| 1634 | 4 digits | 1⁴ + 6⁴ + 3⁴ + 4⁴ = 1634 | ✓ Yes |
| 123 | 3 digits | 1³ + 2³ + 3³ = 36 ≠ 123 | ✗ No |

### RESULT
Successfully created an Armstrong number checker with detailed calculation breakdown and visual result indication.

---

<div style="page-break-after: always;"></div>

## EX.NO: 8 - FACTORIAL CALCULATOR (STANDALONE)

### AIM
Implement a ReactJS program to calculate the factorial of any non-negative integer.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-8

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/Question8.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| Question8.jsx | Standalone factorial calculator component |
| App.jsx | Routing configuration |
| index.css | Global styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing input and factorial result | Question8.jsx |
| Iterative Algorithm | Calculating factorial efficiently | Question8.jsx |
| Number Formatting | Displaying large numbers with commas | Question8.jsx |
| Input Validation | Preventing negative and very large inputs | Question8.jsx |
| Calculation Steps | Showing multiplication sequence | Question8.jsx |

### ALGORITHM
```
1. Accept non-negative integer n from user
2. Validate input (n ≥ 0 and n ≤ 170)
3. If n = 0 or n = 1, return 1
4. Initialize factorial = 1
5. For i from n down to 1:
   a. factorial = factorial × i
   b. Store i in steps array
6. Display factorial and steps
```

**Formula:** n! = n × (n-1) × (n-2) × ... × 2 × 1

### KEY FEATURES

| Feature | Description |
|---------|-------------|
| **Large Number Support** | Handles factorials up to 170! |
| **Step Display** | Shows multiplication sequence |
| **Formatted Output** | Numbers with comma separators |
| **Validation** | Prevents overflow and invalid input |
| **Reference Section** | Common factorial examples |

### TEST CASES

| Input | Factorial | Number of Digits |
|-------|-----------|------------------|
| 0 | 1 | 1 |
| 1 | 1 | 1 |
| 5 | 120 | 3 |
| 10 | 3,628,800 | 7 |
| 20 | 2,432,902,008,176,640,000 | 19 |
| 50 | 3.04×10⁶⁴ | 65 |

### SPECIAL CASES

| Case | Handling |
|------|----------|
| n = 0 | Returns 1 (0! = 1 by definition) |
| n = 1 | Returns 1 |
| n > 170 | Alert: Number too large |
| n < 0 | Alert: Not defined for negatives |

### OUTPUT FEATURES
- Large display of result with comma formatting
- Calculation steps showing full multiplication sequence
- Number of digits in the result
- Reference table with common factorials

### RESULT
Successfully implemented a robust factorial calculator with support for large numbers and comprehensive step display.

---

<div style="page-break-after: always;"></div>

## EX.NO: 9 - GREATEST OF 3 NUMBERS

### AIM
Create a ReactJS application to find the maximum value among three numbers.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-9

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/Question9.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| Question9.jsx | Component to find greatest of 3 numbers |
| App.jsx | Routing configuration |
| index.css | Global styling |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing three number inputs and result | Question9.jsx |
| Math.max() Method | Finding maximum value | Question9.jsx |
| Visual Comparison | Highlighting greatest number | Question9.jsx |
| Multiple Inputs | Handling three separate input fields | Question9.jsx |
| Conditional Styling | Scaling up greatest number card | Question9.jsx |

### ALGORITHM

**Method 1: Using Math.max()**
```
1. Accept three numbers: a, b, c
2. Find greatest = Math.max(a, b, c)
3. Highlight the greatest number
4. Display result
```

**Method 2: Using Conditional Statements**
```
1. Accept three numbers: a, b, c
2. If a ≥ b AND a ≥ c:
     greatest = a
3. Else if b ≥ c:
     greatest = b
4. Else:
     greatest = c
5. Display result
```

### KEY FEATURES

| Feature | Description |
|---------|-------------|
| **Visual Comparison** | Three cards side-by-side with scaling |
| **Highlight Winner** | Greatest number card highlighted and scaled |
| **Decimal Support** | Works with integers and decimals |
| **Equal Handling** | Detects when all numbers are equal |
| **Method Comparison** | Shows both if-else and Math.max() approaches |

### TEST CASES

| Number 1 | Number 2 | Number 3 | Greatest |
|----------|----------|----------|----------|
| 5 | 3 | 8 | 8 |
| 10 | 15 | 7 | 15 |
| 20 | 20 | 20 | 20 (all equal) |
| -5 | -2 | -10 | -2 |
| 3.5 | 7.2 | 4.8 | 7.2 |

### VISUAL PRESENTATION

| Element | Styling |
|---------|---------|
| Winner Card | Blue gradient, 105% scale, border |
| Other Cards | Subtle background, normal scale |
| Result Display | Large purple gradient box |
| Star Indicator | "★ GREATEST ★" badge on winner |

### COMPARISON LOGIC METHODS

| Method | Pros | Cons |
|--------|------|------|
| **Math.max()** | Simple, one line, efficient | Built-in function |
| **If-Else Ladder** | Educational, shows logic | More verbose |

*This component uses Math.max() for simplicity*

### RESULT
Successfully created a greatest of 3 numbers finder with visual comparison and highlighting of the maximum value.

---

<div style="page-break-after: always;"></div>

## EX.NO: 10 - 4-BOX BALL GAME

### AIM
Implement an interactive game with 4 colored boxes containing balls, with three strategic move choices for ball distribution.

### GITHUB REPOSITORY
https://github.com/Guru006-Dev/react-math-assignments

### DEPLOYED URL
https://react-math-assignments.vercel.app/question-10

### PROJECT LOCATION
`c:\Users\Guru\Desktop\Full Stack\React_project`

### COMPONENT FILE
`src/components/Question10.jsx`

### LIST OF FILE NAMES WITH PURPOSE

| FileName | Purpose |
|----------|---------|
| Question10.jsx | 4-Box Ball Game component with game logic |
| App.jsx | Routing configuration |
| index.css | Global styling and animations |

### CONCEPTS USED IN THE APPLICATION

| Concept Name | General Purpose | Code File Where Used |
|--------------|-----------------|---------------------|
| React useState Hook | Managing game state (boxes, history) | Question10.jsx |
| State Management | Complex state for multiple boxes | Question10.jsx |
| Game History | Tracking all moves in array | Question10.jsx |
| Conditional Rendering | Different UI for game start vs playing | Question10.jsx |
| CSS Gradients | Unique colors for each box | Question10.jsx |

### GAME RULES

#### Initial Setup
```
Box A (Violet):  n balls
Box B (Orange):  2n balls
Box C (Green):   4n balls
Box D (White):   8n balls

Total balls = 15n (where n is initial value)
```

#### Three Choices

| Choice | Name | Action | Effect |
|--------|------|--------|--------|
| **1** | Double All | Multiply each box by 2 | A×2, B×2, C×2, D×2 |
| **2** | All to Last | Move all balls to Box D | A=0, B=0, C=0, D=total |
| **3** | Odd to Even | Move odd boxes to even boxes | B=B+A, D=D+C, A=0, C=0 |

### ALGORITHM

**Initialization:**
```
1. Accept initial value n from user
2. Set Box A = n
3. Set Box B = 2n
4. Set Box C = 4n
5. Set Box D = 8n
6. Add to history
```

**Choice 1: Double All Boxes**
```
For each box:
  box = box × 2
```

**Choice 2: All to Last Box**
```
total = A + B + C + D
A = 0
B = 0
C = 0
D = total
```

**Choice 3: Odd to Even**
```
B = B + A
D = D + C
A = 0
C = 0
```

### KEY FEATURES

| Category | Features |
|----------|----------|
| **Visual Design** | 4 colored boxes with gradient backgrounds |
| **Game State** | Real-time ball count display per box |
| **Move History** | Complete history of all moves |
| **Total Counter** | Shows total balls (conservation check) |
| **Reset Function** | Start new game anytime |

### BOX COLOR SCHEME

| Box | Color | Gradient |
|-----|-------|----------|
| **A** | Violet | Purple to Magenta |
| **B** | Orange | Pink to Red |
| **C** | Green | Blue to Cyan |
| **D** | White | Green to Teal |

### TEST CASE WALKTHROUGH

**Initial Value: n = 10**

| Step | Action | Box A | Box B | Box C | Box D | Total |
|------|--------|-------|-------|-------|-------|-------|
| 0 | Start | 10 | 20 | 40 | 80 | 150 |
| 1 | Choice 1 | 20 | 40 | 80 | 160 | 300 |
| 2 | Choice 3 | 0 | 60 | 0 | 240 | 300 |
| 3 | Choice 2 | 0 | 0 | 0 | 300 | 300 |

### GAME MECHANICS

| Feature | Implementation |
|---------|----------------|
| **History Tracking** | Array of all game states |
| **Ball Conservation** | Total always displayed |
| **Visual Feedback** | Cards with gradients and shadows |
| **Strategic Choices** | Three different ball distributions |
| **Undo/Reset** | Can restart game anytime |

### EDUCATIONAL VALUE

| Aspect | Learning Outcome |
|--------|------------------|
| **Math** | Multiplication, addition patterns |
| **Logic** | Strategic thinking and planning |
| **Patterns** | Recognizing number sequences |
| **State** | Understanding state changes |

### RESULT
Successfully implemented an interactive 4-box ball game with three strategic move choices, complete move history tracking, and visual ball distribution display.

---

<div style="page-break-after: always;"></div>

## CONCLUSION

This lab manual documents **10 comprehensive ReactJS experiments** demonstrating advanced React concepts and practical applications:

### ReactJS Experiments (All 10)
1. Mathematical operations (Factorial, Fibonacci, Prime checking)
2. Sum of digits calculator
3. Question paper selector (Function & Class components)
4. Basic calculator
5. Kids calculator game (with gamification)
6. Display first N natural numbers (grid layout)
7. Armstrong number checker
8. Factorial calculator (standalone with large number support)
9. Greatest of 3 numbers (visual comparison)
10. 4-Box ball game (strategic moves with history)

### Skills Demonstrated
✅ **React Concepts:** Components, Hooks, State Management, Props, Event Handling  
✅ **Component Types:** Both Function Components (modern) and Class Components (traditional)  
✅ **JavaScript:** ES6+ syntax, Array methods, Mathematical algorithms  
✅ **CSS:** Responsive design, Animations, Glassmorphism, Grid layouts  
✅ **Problem Solving:** Algorithms for factorial, Fibonacci, prime checking, Armstrong numbers  
✅ **UI/UX Design:** Modern interfaces, User experience, Gamification  
✅ **Game Development:** Interactive 4-box ball game with move history
✅ **Deployment:** GitHub version control, Vercel hosting

### Technologies Mastered
- React 18.2 with Hooks
- React Router for navigation (10 routes)
- Vite build tool
- Modern CSS3 with animations and gradients
- Component architecture
- State management patterns
- Array manipulation and transformations
- Mathematical computations
- Game state management

### Project Deployment
- **GitHub Repository:** https://github.com/Guru006-Dev/react-math-assignments
- **Live Application:** https://react-math-assignments.vercel.app/
- All 10 components deployed and accessible online
- Automatic deployment from main branch

### Experiment Categories

| Category | Experiments | Count |
|----------|-------------|-------|
| **Mathematical Operations** | Factorial, Fibonacci, Prime, Armstrong, Sum of Digits | 5 |
| **Comparison/Logic** | Greatest of 3, Question Paper Selector | 2 |
| **Calculators** | Basic Calculator, Kids Calculator Game | 2 |
| **Interactive Games** | 4-Box Ball Game | 1 |
| **Arrays/Sequences** | Natural Numbers Display | 1 |

---

**Submitted By:**  
**Name:** Guru.D  
**Roll No:** CB.SC.U4CSE23720  
**Course:** Full Stack Frameworks (23CSE461)  
**GitHub:** https://github.com/Guru006-Dev

---

**Date:** January 2026

**Instructor Signature:** ________________
