# PlanSmart-AI-Daily-Planner

PlanSmart AI – Daily Planner
An AI-powered smart scheduling system that automates daily planning, prioritizes tasks, and improves productivity using workflow automation and generative AI.

Problem Statemen-Most people suck at managing their time effectively — and my project directly targets that:

1.Poor task planning reduces productivity
2.Manual scheduling wastes time
3.No intelligent prioritization
4. Lack of structured daily routines

Objective-Build a system that actually thinks instead of just listing tasks:
Generate AI-based daily schedules
Create time-blocked plans automatically
Prioritize tasks intelligently
*rovide productivity suggestions

Key Features:
1.AI-generated daily schedules
2.Task prioritization
3.Automated workflow execution
4.Email delivery of schedules
5.Structured outputs (JSON/CSV)

Tech Stack:
1.n8n
Handles automation and workflow orchestration
2.Google Gemini API
Used for intelligent task analysis and schedule generation
3.Email Integration
Sends generated schedules directly to users
4.JSON Parsing
Converts AI output into structured usable data

Workflow:
User Input → Trigger → Gemini API → Schedule Generation → Email Delivery

Step-by-step:
1.User inputs tasks
2.Workflow is triggered in n8n
3.Tasks are sent to Gemini API
4.AI generates a structured schedule
5.Output is formatted
6.Final schedule is sent via email

System Architecture:

1.User Input → Collects tasks
2.n8n Workflow → Handles automation & processing
3.Gemini API → Generates intelligent schedules
4.Structured Output → JSON/CSV formatting
5.Email Service → Sends results

Output:

1.Time-blocked daily schedule
2.Prioritized task list
3.AI-based productivity suggestions

Outcome:

1.Fully functional AI planner built
2.Automated scheduling achieved
3.Improved productivity use-case validated
4.Real-world integration of AI + APIs + automation

Future Enhancements:

1.Google Calendar integration
2.WhatsApp / Telegram reminders
3.Weekly planning system
4.Personalized AI recommendations
