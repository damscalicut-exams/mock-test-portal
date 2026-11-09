# DAMS Calicut - Mock Test Portal

A lightweight, front-end exam engine built with HTML, Tailwind CSS, and Vanilla JavaScript. Features a negative marking system (+4 / -1) and detailed post-exam explanations.

## 🚀 Live Demo
[Insert your GitHub Pages link here once deployed]

## 🛠️ How to Add Questions
Open `index.html` and scroll to the bottom `<script>` tag. Locate the `examQuestions` array. 

Format your questions like this:
```javascript
{
    question: "Your question text here?",
    options: ["Option A", "Option B", "Option C", "Option D"],
    correctAnswerIndex: 1, // 0 = A, 1 = B, 2 = C, 3 = D
    explanation: "Explanation text goes here."
}
