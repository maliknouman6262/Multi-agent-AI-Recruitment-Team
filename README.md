# Multi-agent-AI-Recruitment-Team :)

This Streamlit app is a sophisticated recruitment system that can take a candidate's resume, analyze their skills against job requirements, automatically schedule interviews for qualified candidates, and handle all the email communications - while recruiters just monitor the process through a simple dashboard.

When a recruiter uploads a candidate's resume, our system automatically evaluates their technical skills, sends personalized feedback emails, and for qualified candidates, even sets up Zoom interviews - all without manual intervention.

Our multi-agent recruitment system includes three agents: a Resume Analyzer, an Interview Scheduler, and an Email Communication agent.

This Streamlit app is a sophisticated recruitment system that can take a candidate's resume, analyze their skills against job requirements, automatically schedule interviews for qualified candidates, and handle all the email communications - while recruiters just monitor the process through a simple dashboard.

When a recruiter uploads a candidate's resume, our system automatically evaluates their technical skills, sends personalized feedback emails, and for qualified candidates, even sets up Zoom interviews - all without manual intervention.

Our multi-agent recruitment system includes three agents: a Resume Analyzer, an Interview Scheduler, and an Email Communication agent.

**Features:
**
Intelligent resume analysis with skill matching and experience assessment

Automated interview scheduling with Zoom integration

Professional email communications for acceptances, rejections, and interview coordination

Multi-agent architecture with specialized roles

User-friendly Streamlit interface

Secure API integration with OpenAI, Zoom, and email services



Intelligent resume analysis with skill matching and experience assessment

Automated interview scheduling with Zoom integration

Professional email communications for acceptances, rejections, and interview coordination

Multi-agent architecture with specialized roles

User-friendly Streamlit interface

Secure API integration with OpenAI, Zoom, and email services

**How the App Works
**
he system operates through a coordinated team of specialized AI agents:

Resume Analyzer Agent:

Processes uploaded PDF resumes using PyPDF2

Matches candidate skills against role requirements

Evaluates technical experience and project work

Makes data-driven selection decisions using a 70% match threshold

Interview Scheduler Agent:

Handles Zoom meeting creation and coordination

Manages timezone conversions with pytz

Creates professional meeting invites

Ensures business hours scheduling (9 AM - 5 PM IST)

Email Communication Agent:

Drafts and sends professional emails using Gmail

Handles acceptance notifications with interview details

Provides constructive feedback in rejection emails

Maintains consistent branding and tone

Workflow:

Recruiter/user uploads candidate's resume and enters email

Resume Analyzer assesses the application against role requirements

If selected:

Email agent sends acceptance notification

Scheduler creates Zoom interview

Email agent sends interview details

If not selected:

Email agent sends constructive feedback with improvement suggestions

**Prerequisites
**
**Before we begin, make sure you have the following:
**
Python installed on your machine (version 3.10 or higher is recommended)

OpenAI API key for GPT-4o

Zoom account with API credentials (Account ID, Client ID, Client Secret)

Gmail account with App Password for automated emails

A code editor of your choice (we recommend VS Code or PyCharm for their excellent Python support)

Basic familiarity with Python programming
**
Things to do before running the application:**

Create/Use a new Gmail account for the recruiter

Enable 2-step verification and generate an App Password for the Gmail account

The App Password is a 16-digit code (use without spaces) that should be generated here - Google App Password Please go through the steps to generate the password. Format - 'afec wejf awoj fwrv' (remove the spaces and enter it in the Streamlit app).

Create/ Use a Zoom account and go to the Zoom App Marketplace to get the API credentials : Zoom Marketplace

Go to Developer Dashboard and create a new app - Select Server to Server OAuth and get the credentials, you’ll see 3 credentials - Client ID, Client Secret, and Account ID.

After that, you need to add a few scopes to the app - so that the Zoom link of the candidate is sent and created through the mail.

