# Soft Skills Tip
## Burnout
Burnout is a state of emotional, physical, and mental exhaustion caused by excessive and prolonged stress. It occurs when you feel overwhelmed, emotionally drained, and unable to meet constant demands. As the stress continues, you begin to lose the interest and motivation that led you to take on a certain role in the first place.

## How to prevent burnout?
1- Set boundaries: Set clear boundaries between work and personal life. Make sure to have time for yourself and your family.

2- Take breaks: Take short breaks during work hours. Go for a walk, stretch, or meditate.

3- Exercise: Regular exercise can help reduce stress and anxiety.

4- Sleep: Make sure to get enough sleep. Lack of sleep can affect your mood and productivity.

5- Eat well: A healthy diet can help improve your mood and energy levels.

6- Talk to someone: If you're feeling overwhelmed, talk to a friend, family member, or therapist.

7- Practice mindfulness: Mindfulness meditation can help reduce stress and improve your mental well-being.

8- Learn to say no: Don't take on more than you can handle. Learn to say no to extra work or commitments.

9- Take time off: If you're feeling burnt out, take some time off to rest and recharge.

10- Seek help: If you're feeling overwhelmed, seek help from a mental health professional.

## Signs of burnout
1- Exhaustion: Feeling tired all the time, both physically and emotionally.

2- Cynicism: Feeling detached from work and colleagues, and having a negative attitude.

3- Ineffectiveness: Feeling like you're not accomplishing anything, and that your work doesn't matter.

4- Health problems: Burnout can lead to physical health problems, such as headaches, stomach issues, and insomnia.

5- Irritability: Feeling irritable, angry, or frustrated with colleagues or clients.

6- Lack of motivation: Feeling unmotivated and uninterested in your work.

## What do to when you feel burnt out?
Being in burnout is different from being tired. It's a state of emotional, physical, and mental exhaustion that can have serious consequences if not addressed. If you're feeling burnt out, it's important to take steps to address the issue and prevent it from getting worse.

Also being in the burnout state, needs a lot of work than preventing it from happening in the first place because you need first to stop the bleeding before you can start healing.

So here are the steps to take when you're feeling burnt out:

   1- Acknowledge the problem: Recognize that you're feeling burnt out and that it's affecting your work and well-being.

   2- Identify the cause: Try to identify the root cause of your burnout. Is it work-related, personal, or a combination of both?

   3- Take a break: If possible, take some time off to rest and recharge. This can help you gain perspective and come back refreshed.

   4- Talk to someone: Reach out to a friend, family member, or therapist for support. Talking about your feelings can help you feel less alone.

   5- Seek help: If you're feeling overwhelmed, seek help from a mental health professional. They can provide you with tools and strategies to cope with burnout.

   6- Make a plan: Once you've identified the cause of your burnout, make a plan to address it. This may involve setting boundaries, delegating tasks, or seeking a new job.

   7- Practice self-care: Take care of yourself by eating well, exercising, and getting enough sleep. Self-care is essential for managing stress and preventing burnout.

   8- Set boundaries: Set clear boundaries between work and personal life. Make sure to have time for yourself and your family.

   9- Learn to say no: Don't take on more than you can handle. Learn to say no to extra work or commitments.

   10- Focus on what's important: Prioritize your tasks and focus on what's most important. Let go of tasks that are not essential.

# Tips & Tricks for React best practices
1- Props

   - Use destructuring for props in functional components.

   - Use children prop for components that wrap other components.

   - Use ...rest for passing props to child components.

  - DO NOT Use defaultProps for default values, use destructuring instead.

2- Wrap Logic in Hooks

   - Wrap logic in hooks and use hooks in components.

   - Use hooks for state management.

   - Use hooks for side effects.

3- Avoid re-rendering stateless components

   - Use React.memo for stateless components.

   - Use useMemo for memoizing values.

4- Use a state management most of the time for managing state to enhance the performance of the application, this will reduce number of re-renders.

5- Use tailwind all the time for styling.

6- Create small components, this will make the code more readable and maintainable.

7- DO NOT install a library if you can write the code yourself.

8- DO NOT use any type as much as possible.

9- Create reusable functions, hooks, and components.

10 -Wrap the repeated code in functions, objects and classes, i.e if you're using localStorage in multiple places, wrap it in a an object with set, get, remove, clear methods.

11- Always handle errors and failures specially with side effects like API calls.

12- Prepare and list the entire project pages and layouts before starting the project.

13- Define the design system from colors, components, typography, and layout before starting the project.

14- Declare guarded routes, Reverse routes, and public routes before starting the project.

15- Common Modals should be called in layout components and managed by a state management, this will reduce time of renders for the modals specially if they are rarely called, i.e product quick view modal, login modal and so on.

16- Most of the time the project will be multilingual, so DO NOT write any text in the code, use a translation library like @mongez/localization.

17- Use YAGIN concept, You Ain't Gonna Need It, in other words, DO NOT write code that you may need in the future, write the code that you need now.

18- Use Storybook for developing components, this will make the development process faster.

19- If possible, write tests for the projects using Cypress for E2E tests and Jest for unit tests.
