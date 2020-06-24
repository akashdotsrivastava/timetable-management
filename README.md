# Assumptions/Requirements

- There is a school
- The school has uniquely named standards (Nursery, KG, 1, 2, 3 ....)
- Each standard has sections named A, B, C ... (total number ranging from 1 to x)
- There are uniquely named subjects (English, Hindi, Maths ...) Lets also keep subjects like English-I and English-II separate, and not related anyway. Later we can group them, but don't see the need now, for simplicity.
- So every subject has finite number of standards it is taught in. For eg Art, SUPW may be taught to everyone from standards 1 to 8. Physics is taught only in standards 11 and 12
- There are teachers/lecturers
- Each teacher can teach p(>=1) subjects. But it is not assumed that a teacher can teach a unique subject across all standards it is taught in. Lets not assume teacher Akash can teach Maths from class 1 to 12. He might be skilled only to teach Maths from standards 4 to 8. So it should be specific
- There are working days (Monday, Tuesday, Wednesday ...)
- Each working day has different number of lecture periods (can be same too, but lets not assume, because few days can be half days)
- Each teacher can have N consecutive lectures per day (Additional constraints, can have M total lectures per day or per week (one of the two)? Don't want a single teacher to get fatigued with small breaks and classes most of time)
- Number of lectures per week per subject per standard+section is pre-decided. Eg. 6th A has to have 10 lectures of Mathematics per week. (Question: Shouldn't it be per week per subject per standard? All sections should be taught the same number of lectures, right?)
- Continuing from last point, there should be some limit on how many lectures for a particular subject a standard+section is taught in 1 day, for eg we cannot teach 6th A 5 lectures of Maths in 1 day, and then teach the rest 5 lectures on remaining 6 days by spreading out, i.e there should be evenness?
- There should be a some margin given for rightly skilled teachers available to take classes in case of emergency/absence of teacher.
- The workload should be evenly spread to teachers of the same skill level. For eg. there should be not much workload(total time spent) difference between Professor Aman and Professor Akash who can both teach Maths and Physics to classes 9 to 12
- A standard + section will have a single teacher teaching a subject (So 11th A can have only Prof. Akash teaching Physics throughout the year, except the emergency situation. Its not like both Prof. Akash and Prof. Aman teach Physics to 11th A)
- Add more here

# Advanced Problems to include
- A teacher has preferences. For eg he/she has the skill to teach both Maths and Physics from classes 9 to 12, but he has superior skills in Maths for class 9th and 10th and average skills in other standards + subjects. Should we factor that he gets more classes where he has better skills, but still be available for emergency cases where he has to teach something he has lesser skills in
- Add more here