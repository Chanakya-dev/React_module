```json
{
  "title": "React Programming Basics",
  "description": "Master React through hands-on coding exercises",
  "difficulty": "beginner",
  "estimatedHours": 40,
  "status": "active",
  "tags": ["programming", "react", "frontend"],
  "prerequisites": [],
  "createdBy": "admin@example.com",
  "createdAt": "{{datetime.now(UTC)}}",
  "modules": [
    {
      "title": "Getting Started with React",
      "description": "Learn the basics of React setup and components",
      "order": 1,
      "questions": [
        {
          "title": "React Import Statement",
          "text": "Write the correct import statement to import React from the 'react' package.",
          "type": "code",
          "language": "javascript",
          "difficulty": "easy",
          "order": 1,
          "code_starter": "// Write your import statement here",
          "test_cases": [
            {
              "input": "import statement",
              "expected": "import React from 'react';"
            }
          ],
          "expected_solution": "import React from 'react';",
          "expected_behavior": "Should correctly import React from the react package",
          "evaluation_criteria": {
            "functionality": "Import statement should be syntactically correct",
            "efficiency": "Direct import statement",
            "style": "Follow JavaScript conventions"
          }
        },
        {
          "title": "Create React Component",
          "text": "Create a functional component named 'HelloWorld' that displays 'Hello, React!' in an h1 tag.",
          "type": "code",
          "language": "javascript",
          "difficulty": "easy",
          "order": 2,
          "code_starter": "// Create your HelloWorld component here\nfunction HelloWorld() {\n  // Your code here\n}",
          "test_cases": [
            {
              "input": "component render",
              "expected": "<h1>Hello, React!</h1>"
            }
          ],
          "expected_solution": "function HelloWorld() {\n  return <h1>Hello, React!</h1>;\n}",
          "expected_behavior": "Component should render an h1 tag with 'Hello, React!'",
          "evaluation_criteria": {
            "functionality": "Component renders correct output",
            "efficiency": "Simple implementation",
            "style": "Follow React conventions"
          }
        }
      ]
    },
    {
      "title": "React State and Props",
      "description": "Understanding component state and props",
      "order": 2,
      "questions": [
        {
          "title": "Understanding Props",
          "text": "What are props in React?",
          "type": "multiple_choice",
          "difficulty": "easy",
          "order": 1,
          "options": [
            "Internal component data that can change",
            "Properties passed to a component from its parent",
            "CSS properties for styling",
            "JavaScript properties for event handling"
          ],
          "correct_answer": "Properties passed to a component from its parent"
        },
        {
          "title": "Create Counter Component",
          "text": "Create a Counter component that maintains a count state and displays it.",
          "type": "code",
          "language": "javascript",
          "difficulty": "medium",
          "order": 2,
          "code_starter": "import React, { useState } from 'react';\n\nfunction Counter() {\n  // Your code here\n}",
          "test_cases": [
            {
              "input": "initial render",
              "expected": "Count: 0"
            }
          ],
          "expected_solution": "import React, { useState } from 'react';\n\nfunction Counter() {\n  const [count, setCount] = useState(0);\n  return (\n    <div>\n      <p>Count: {count}</p>\n      <button onClick={() => setCount(count + 1)}>Increment</button>\n    </div>\n  );\n}",
          "expected_behavior": "Component should display count and increment button",
          "evaluation_criteria": {
            "functionality": "Counter works correctly",
            "efficiency": "Uses useState hook properly",
            "style": "Follows React best practices"
          }
        }
      ]
    }
  ]
}
```
