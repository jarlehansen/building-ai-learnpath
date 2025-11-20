# LearnPath - AI-Powered Personalized Learning Assistant

Final project for the Building AI course

## Summary

LearnPath is an AI-driven mobile application that creates personalized learning plans for any topic. Users input what they want to learn (like programming in a specific language), and the app generates a structured plan with tasks, informational content, and a todo list, leveraging AI foundation models to create an adaptive learning experience.


## Background

Learning new skills can be overwhelming without a clear roadmap. Common problems include:
* Difficulty knowing where to start when learning something new
* Lack of structured, personalized learning paths
* Information overload from scattered resources
* No clear milestones or progress tracking

My own motivation comes from experiencing these challenges, for example when I want to learn a new programming language. I want to quickly jump in, get a set of tasks and some really good resources to learn.


## How is it used?

The solution is designed for anyone wanting to learn a new skill, from students to professionals pursuing career development. 

### The process is:
1. User enters a learning topic (e.g., "I want to learn Rust programming")
2. The app uses Apple Foundation Model (or an open source model) to analyze the topic and generate a customized learning plan
3. The plan includes:
   - A structured todo list with progressive milestones
   - Informational content explaining key concepts
   - Practical tasks and exercises
4. Users can add their own links and resources, which the AI incorporates into the learning experience
5. Progress is tracked as users complete tasks and milestones

The app is particularly useful for:
- Self-directed learners wanting structure
- Professionals learning new skills for career advancement
- Students supplementing formal education
- Anyone with limited time who needs efficient learning paths

Considerations for different users include varying learning speeds, prior knowledge levels, and preferred learning styles (visual, practical, theoretical).


## Data sources and AI methods

The app primarily uses:
* **On-device models (such as the Apple foundation model)** - On-device AI for generating learning plans and processing user inputs
* **User-provided resources** - Links and materials that users add are analyzed and integrated into the learning plan
* **Structured prompting** - The app uses carefully designed prompts to guide the AI in creating effective and sound learning plans

No external data collection is required for core functionality, except if the user provides some external links. All processing happens on-device.


## Challenges

This project does not solve:
* **Quality of external resources** - The app cannot verify the accuracy of user-provided links
* **Motivation and discipline** - Technology cannot replace intrinsic motivation needed for learning
* **Deep expertise** - AI-generated plans may lack nuance that human expert mentors provide
* **Hands-on practice environments** - The app suggests tasks but doesn't provide interactive coding environments or labs
* **Lack of knowledge** - there will be topics that the models do not know well enough to create a learning plan for

Ethical considerations:
* Over-reliance on AI for educational guidance
* Potential bias in AI-generated content
* Privacy concerns if user learning data is stored or shared
* Ensuring accessibility for users with different learning needs


## What next?

Potential growth directions:
* **Community features** - Allow users to share successful learning paths
* **Progress analytics** - Detailed insights into learning patterns and effectiveness
* **Integration with learning platforms** - Connect with Coursera, Udemy, GitHub, etc.
* **Adaptive difficulty** - AI adjusts plan complexity based on user progress

Skills and assistance needed:
* iOS development expertise for polished UI/UX
* Educational psychology consultation for pedagogically sound plans
* Backend infrastructure for optional cloud sync features
* User testing with diverse learners to refine the experience


## Acknowledgments

* Inspired by the need for accessible, personalized education
* Building AI course by Reaktor Innovations and University of Helsinki
* Apple Foundation Models documentation and capabilities
* The open-source learning community and their shared resources
