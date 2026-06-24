# Prompt_Library_Shivani_Pattnayak

## Prompt 1: LinkedIn Product Launch Post

### Use Case
Generate a professional LinkedIn post announcing a product launch.

### Techniques Used
- Role Prompting
- Few-Shot Prompting
- Constraint-Based Prompting
- Context Injection

### Prompt Template

You are a senior LinkedIn content strategist whose posts regularly receive high engagement from professionals, founders, recruiters, and industry leaders.

Write a LinkedIn post announcing the launch of {product_name}.

Product Description:
{product_description}

Target Audience:
{target_audience}

Goal:
{goal}

Style Examples:

Example 1:
"We built X to solve Y."

Example 2:
"Small project. Big learning."

Constraints:
- Maximum 120 words
- Use short paragraphs
- Include exactly 1 relevant emoji
- End with a call-to-action (CTA)
- Avoid the words: "excited", "amazing"
- Focus on value delivered to users
- Maintain a professional and authentic tone

### Sample Input

Product Name: WorkSyne

Product Description:
AI-powered job portal matching candidates with suitable jobs.

Target Audience:
Students and job seekers

Goal:
Increase awareness and encourage trial.

### Sample Output

We built WorkSyne to make job searching simpler and smarter. 🚀

Instead of scrolling through hundreds of listings, users receive opportunities tailored to their skills, experience, and interests.

Built with students and job seekers in mind, WorkSyne helps bridge the gap between talent and opportunity.

We'd love your feedback—try WorkSyne and share your thoughts below!

### Screenshot

![Prompt 1 Output](screenshots/prompt1_output.png)

### Iteration

v1 → Write a LinkedIn post announcing {product_name}.

v2 → Added role, audience, examples, and constraints.

## Prompt 2: Blog Introduction Generator

### Use Case
Generate engaging introductions for blog posts.

### Techniques Used
- Role Prompting
- Chain-of-Thought Prompting

### Prompt Template

You are an experienced technical blogger.

Write an introduction paragraph for a blog on:

Topic: {topic}

Target Audience: {audience}

Instructions:
- Start with a strong hook
- Explain why the topic matters
- Preview what readers will learn

Word Limit: 150 words

### Sample Input

Topic: Artificial Intelligence

Target Audience: College Students

### Sample Output

Artificial Intelligence is no longer a futuristic concept—it is already transforming the way we learn, work, and communicate.

From virtual assistants to self-driving cars, AI is becoming an essential part of everyday life. Understanding its fundamentals is increasingly important for students and professionals alike.

In this article, we explore what AI is, how it works, and the exciting opportunities it creates for the future.

### Screenshot

![Prompt 2 Output](screenshots/prompt2_output.png)

## Prompt 3: Cold Outreach Email

### Use Case
Generate professional networking emails.

### Techniques Used
- Role Prompting
- Few-Shot Prompting

### Prompt Template

You are a professional networking coach.

Write a cold outreach email.

Recipient Name: {name}

Role: {role}

Company: {company}

Purpose:
{purpose}

Example:

Hi Sarah,

I admire your work in AI and would love to learn more about your journey.

Would you be open to a short conversation?

Best regards,
John

### Sample Input

Recipient Name: Rahul Sharma

Role: Software Engineer

Company: Infosys

Purpose:
Networking and career guidance.

### Sample Output

Subject: Seeking Career Guidance

Hi Rahul,

I recently came across your profile and was impressed by your journey as a Software Engineer at Infosys.

As a Computer Science student, I am eager to learn more about the industry and gain insights from experienced professionals like you.

Would you be open to a brief conversation at your convenience?

Best regards,
Shivani Pattnayak

### Screenshot

![Prompt 3 Output](screenshots/prompt3_output.png)

### Iteration

v1 → Write a cold outreach email.

v2 → Added recipient details, purpose, role prompting and example.
## Prompt 4: Follow-Up Email

### Use Case
Generate polite follow-up emails.

### Techniques Used
- Role Prompting
- Constraint-Based Prompting

### Prompt Template

You are a professional business communicator.

Write a polite follow-up email.

Context:
{context}

Constraints:
- Under 100 words
- Professional tone
- Include a clear CTA

### Sample Input

Context:
Following up regarding an internship referral request.

### Sample Output

Subject: Following Up

Hi,

I hope you are doing well.

I wanted to follow up regarding my previous message about the internship referral request. I understand you may be busy, but I would appreciate any update when convenient.

Looking forward to hearing from you.

Best regards,
Shivani

### Screenshot

![Prompt 4 Output](screenshots/prompt4_output.png)
## Prompt 5: Product Description Generator

### Use Case
Generate product descriptions for marketing purposes.

### Techniques Used
- Audience Targeting
- Structured Prompting

### Prompt Template

You are a marketing copywriter.

Create a product description.

Product:
{product_name}

Features:
{features}

Target Audience:
{target_audience}

Format:
Description
Benefits
Call To Action

### Sample Input

Product: SmartFit Watch

Features:
Heart Rate Monitoring
Sleep Tracking
7-Day Battery Life

Target Audience:
Fitness Enthusiasts

### Sample Output

Description:
SmartFit Watch is designed to help users monitor their health and stay connected throughout the day.

Benefits:
- Real-time heart rate tracking
- Sleep monitoring insights
- Long-lasting battery life

Call To Action:
Take charge of your fitness journey with SmartFit Watch today.

### Screenshot

![Prompt 5 Output](screenshots/prompt5_output.png)
## Prompt 6: YouTube Title & Description Generator

### Use Case
Generate SEO-friendly YouTube titles and descriptions.

### Techniques Used
- Few-Shot Prompting
- Constraint-Based Prompting

### Prompt Template

Generate:

1. Five YouTube Titles
2. One YouTube Description

Topic:
{topic}

Constraints:
- SEO friendly
- Titles under 60 characters

Example:
Top 10 Python Tricks Every Beginner Should Know

### Sample Input

Topic: Python for Beginners

### Sample Output

Titles:
1. Learn Python in 30 Minutes
2. Python Basics for Absolute Beginners
3. Start Coding with Python Today
4. Python Tutorial for Students
5. Beginner's Guide to Python Programming

Description:
Learn Python from scratch with simple examples and practical demonstrations.

### Screenshot

![Prompt 6 Output](screenshots/prompt6_output.png)
## Prompt 7: Newsletter Section Generator

### Use Case
Generate newsletter content for events and updates.

### Techniques Used
- Context Injection
- Role Prompting

### Prompt Template

You are a newsletter editor.

Write a newsletter section.

Event:
{event}

Audience:
{audience}

Key Updates:
{updates}

Length:
150 words

### Sample Input

Event: ACM Tech Carnival 2026

Audience: Engineering Students

Updates:
300+ Participants
Coding Contest
Workshops

### Sample Output

ACM Tech Carnival 2026 witnessed enthusiastic participation from over 300 students. The event featured coding competitions, technical workshops, and networking opportunities that encouraged innovation and collaboration among participants.

### Screenshot

![Prompt 7 Output](screenshots/prompt7_output.png)
## Prompt 8: Article Summarization Prompt

### Use Case
Generate concise summaries of long articles.

### Techniques Used
- Chain-of-Thought Prompting
- Structured Output

### Prompt Template

Summarize the following article:

{article_text}

Think step-by-step.

Output Format:

Main Topic

Key Points

Important Statistics

Final Summary

### Sample Input

Article:
Artificial Intelligence is transforming industries through automation, predictive analytics, and improved decision-making.

### Sample Output

Main Topic:
Impact of Artificial Intelligence on Industries

Key Points:
- Automates repetitive tasks
- Improves decision-making
- Enhances productivity

Important Statistics:
- AI adoption continues to grow across industries

Final Summary:
Artificial Intelligence is helping organizations improve efficiency, automate processes, and make data-driven decisions.

### Screenshot

![Prompt 8 Output](screenshots/prompt8_output.png)
## Prompt 9: FAQ Generator

### Use Case
Generate Frequently Asked Questions for products and services.

### Techniques Used
- Role Prompting
- Structured Output

### Prompt Template

You are a customer support specialist.

Generate 10 FAQs for:

Product:
{product_name}

Format:

Q1:
A1:

Q2:
A2:

### Sample Input

Product:
Library Management System

### Sample Output

Q1: What is the Library Management System?

A1: It is a software solution used to manage books, members, and transactions efficiently.

Q2: Can users search for books?

A2: Yes, users can quickly search books using keywords and categories.

Q3: Does it track issued books?

A3: Yes, it records issue and return transactions automatically.

### Screenshot

![Prompt 9 Output](screenshots/prompt9_output.png)
## Prompt 10: 7-Day Content Calendar Generator

### Use Case
Generate a weekly content plan for social media.

### Techniques Used
- Chain-of-Thought Prompting
- Structured Output

### Prompt Template

You are a social media strategist.

Business:
{business_type}

Target Audience:
{target_audience}

Goal:
{goal}

Generate a 7-day content calendar.

Format:

Day
Content Type
Topic
Caption Idea

### Sample Input

Business:
School Instagram Page

Target Audience:
Parents

Goal:
Increase engagement

### Sample Output

| Day | Content Type | Topic | Caption Idea |
|------|-------------|--------|--------------|
| Monday | Reel | Welcome Back | First day memories |
| Tuesday | Carousel | Classroom Activities | Learning through fun |
| Wednesday | Story | Poll | Favorite school activity |
| Thursday | Reel | Behind the Scenes | A day at school |
| Friday | Post | Student Achievement | Celebrating success |
| Saturday | Reel | Event Highlights | Moments from the week |
| Sunday | Story | Parent Feedback | Share your thoughts |

### Screenshot

![Prompt 10 Output](screenshots/prompt10_output.png)

### Iteration

v1 → Create a content calendar.

v2 → Added business type, audience, goal, and structured output format.

