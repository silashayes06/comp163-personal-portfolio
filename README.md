# comp163-personal-portfolio
student_name = "Silas Hayes"
student_email = "sdhayes@aggies.ncat.edu"
hometown = "Greensboro, NC"
graduation = "Summer 2029"
major = "Computer Science"

current_semester_credits = 14
courses = 5
cumulative_gpa = 3.45
study_time_weekly = 15
academic_investment = 5.0

current_courses = ["MATH 110","COMP 163", "GEEN 111", "HIST 216", "SPCH 250"]
credits = [3, 3, 3, 3]
professors = ["Dr. Johnson", "Prof. Rhodes", "Dr. Parrish", "Dr. Ndege", "Prof. Silverthorne"]
professor_locations = ["Marteena 216", "Gibbs 337", "McNair 240", "ONLINE", "ONLINE"]

current_skills = {"Time management", "Photography", "Problem solving", "HTML", "Python basics"}
learning_goals = {"Software development", "Python", "GitHub"}
career_interests = {"Software development", "Game development", "Information Technology", "Data science"} 

monthly_budget = 250
food_budget = 100
entertainment_budget = 75 
books_budget = 0
transportation_budget = 0
annual_projection = monthly_budget * 12

emergency_contact = "Kiki Hayes (Mom) - 111-111-1112"
home_address = "1111 Somewhere Road, Mcleansville, NC 27301"
social_media_presence = "572 followers across 2 platforms"
key_contacts = "3 people in directory"

courses_completed = 7
current_academic_load = 22
entertainment_backlog = 3
current_hobbies = 5

print("================================================================")
print("              PERSONAL ACADEMIC & LIFE PORTFOLIO")
print("================================================================")
print(f"Student: {student_name} | Email: {student_email}")
print(f"From: {hometown} | Graduating: {graduation}")
print(f"Major: {major}\n")

print("=== ACADEMIC PROFILE ===")
print(f"Current Semester: {current_semester_credits} credits across {courses} courses")
print(f"Cumulative GPA: {cumulative_gpa}")
print(f"Weekly Study Time: {study_time_weekly} hours")
print(f"Academic Investment: ${academic_investment:.1f} per study hour\n")

print("Current Courses:")
print("MATH 110 - 4   credits - Dr. Johnson - Marteena 216")
print("COMP 163 - 3 credits - Prof. Rhodes - Gibbs 337")
print("GEEN 111 - 1 credits - Dr. Parrish - McNair 240")
print("HIST 216 - 3 credits - Dr. Ndege - ONLINE")
print("SPCH 250 - 3 credits - Dr. Silverthorne - ONLINE")

print("=== PERSONAL DEVELOPMENT ===")
print(f"Current Skills: {current_skills}")
print(f"Learning Goals: {learning_goals}")
print(f"Career Interests: {career_interests}")
print(f"Skills Currently Have: {len(current_skills)}")
print(f"Skills Want to Learn: {len(learning_goals)}")

print("=== FINANCIAL OVERVIEW ===")
print(f"Monthly Budget: ${monthly_budget}")
print(f"Food: ${food_budget} ($15.0/day)")
print(f"Entertainment: ${entertainment_budget}")
print(f"Books: ${books_budget}")
print(f"Transportation: ${transportation_budget}")
print(f"Annual Projection: ${annual_projection}")

print("=== CONNECTIONS & CONTACTS ===")
print(f"Emergency Contact: {emergency_contact}")
print(f"Home Address: {home_address}")
print(f"Social Media Presence: {social_media_presence}")
print(f"Key Contacts: {key_contacts}")

print("=== LIFE STATISTICS ===")
print(f"Total Courses Completed: {courses_completed}")
print(f"Current Academic Load: {current_academic_load} weekly commitments")
print(f"Entertainment Backlog: {entertainment_backlog} items")
print(f"Current Hobbies: {current_hobbies} activities")
print("================================================================")