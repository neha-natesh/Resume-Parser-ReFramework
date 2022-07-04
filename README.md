# ResumeParserReFramework
ReFramework - Resume Parser Project for Advanced Course

Input is taken via UiPath Apps : Job ID and Skills.
Submit button starts the process.
Resumes are downloaded from the drive folder and details extracted using ML Skill.
ML Skill is trained using document understanding ML retrainable package(over two weeks
with different sets of resumes and validated run training done as and when the test runs were done).
Extracted details are updated to the google sheets and compared with the input skills. The resumes
with matching skills are shortlisted and moved to a different folder in google drive. This folder
link and google sheet link is emailed to the HR.
