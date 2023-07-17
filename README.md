# ResumeAI
## Starting from other PHP webapp
Created prompt for parsing resume and converting text into JSON
``
"Given the following resume, parse the information and organize it into a structured format. Extract the candidate's full name, contact information, education, skills, work experience, certifications, languages, and references.

Structure the parsed data into JSON format as follows:

1. Candidate Information: Full name, contact information (email, phone, LinkedIn, address)
2. Objective: Brief statement of career objectives
3. Education: List of degrees (degree, institution, graduation date, major)
4. Skills: List of skills
5. Experience: List of roles (job title, organization, start date, end date, responsibilities)
6. Certifications: List of certifications (certification name, issuer, date obtained)
7. Languages: List of languages spoken
8. References: List of references (if any)

-- Start of resume
@@Resume@@
-- End of resume"

``
