# IT373 Week 1 Setup Reflection

## Challenges During Setup and Solutions

Setting up the Django development environment for IT373 Week 1 presented several learning opportunities and challenges that helped deepen my understanding of web development workflows.

**Virtual Environment Configuration:**
At first, I encountered confusion about properly activating the virtual environment. The challenge was ensuring that Django was installed in the isolated environment rather than globally. I solved this by carefully following the `python -m venv .venv` command and ensuring proper activation before installing packages.

**Template Inheritance Understanding:**
The concept of extending base templates was initially confusing. I struggled with understanding how `{% block %}` tags work and how child templates override parent content. Through experimentation and recalling my professors advice and demo, I learned that template inheritance creates a hierarchy where child templates can customize specific sections while maintaining overall structure.

**URL Pattern Routing:**
Connecting URLs to views required understanding Django's URL dispatcher system. I initially had duplicate URL patterns and incorrect path configurations. Debugging this taught me the importance of unique URL names and proper import statements.

**Git Integration:**
Managing version control while developing required learning proper Git workflows for web projects, including appropriate `.gitignore` configurations for Python environments.

These challenges enhanced my problem-solving skills and provided practical experience with Django's MVT architecture.
