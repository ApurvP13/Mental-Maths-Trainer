# Mental Math Trainer

A simple, interactive web application to practice mental arithmetic skills. The app provides a clean interface for practicing addition, subtraction, and multiplication in a traditional vertical format, similar to how these operations are taught in schools.


## Features

- **Three Operation Modes:**
  - Addition (3-digit + 2-digit numbers) (can customise)
  - Subtraction (3-digit - 2-digit numbers) (can customise)
  - Multiplication (2-digit × 1-digit numbers) (can customise)

- **User-Friendly Interface:**
  - Clean, minimalist design
  - Traditional vertical format display
  - Responsive layout works on both desktop and mobile devices

- **Interactive Features:**
  - Immediate feedback on answers
  - Shake animation for incorrect answers
  - Automatic problem generation
  - Input validation
  - Quick mode switching with back button


## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ApurvP13/Mental-Maths-Trainer.git
```

2. Open `index.html` in your web browser

That's it! No additional setup or dependencies required.

## OR (without cloning)
1. Download the zip file
2. Extract and click open on the `index.hmtl` file to run it.

## How to Use

1. Select a mode (Addition, Subtraction, or Multiplication)
2. A problem will appear in vertical format
3. Type your answer in the input box
4. Press Enter to submit
5. If correct: A new problem will appear
6. If incorrect: The input box will shake, and you can try again
7. Use the back button to switch modes

## How to customise the number of digits for problems
1. open the `index.html` file in any text editor
2. scorll down to the `generateProblem()` function (around line 126)
3. change the `90` and `10` in `Math.floor(Math.random() * 90) + 10;` to match the number of digits you need.
4. for ex: (90 and 10) for 2 digit, and (900 and 100) for 3 digit
5. save and reload the website.

## Technical Details

Built using:
- HTML5
- CSS3
- Vanilla JavaScript

Features implemented:
- CSS Grid for layout
- CSS Animations for feedback
- Responsive design principles
- Event handling for keyboard input

## Contributing

Contributions are welcome! Here are ways you can contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Add difficulty levels
- [ ] Include division problems
- [ ] Add a score tracking system
- [ ] Implement a timer mode
- [ ] Add sound effects for feedback
- [ ] Create a statistics dashboard


## Acknowledgments

- Inspired by my will to improve my mental maths skills for aptitude tests.
- Built for students and anyone wanting to improve their mental math skills

## Contact

Your Name - [apurvwork13@gmail.com](mailto:apurvwork13@example.com)

Project Link: [https://github.com/Apurvp13/Mental-Maths-Trainer](https://github.com/Apurvp13/Mental-Maths-Trainer)
