# Moodle Quiz Configuration and Troubleshooting Guide

**Document Type:** LMS Technical Support and Administration  
**Prepared by:** Damaris  
**Organisation:** TEKTAGOGY Group  
**Platform:** Moodle LMS

## 1. Introduction

This guide provides practical guidance for configuring Moodle quizzes, managing student attempts, and troubleshooting common assessment problems.

It is intended for Moodle administrators, lecturers, e-learning officers, and technical support teams.

## 2. Quiz Configuration Checklist

Before making a quiz available:

- [ ] Confirm the quiz name and description.
- [ ] Set the opening and closing dates.
- [ ] Configure the time limit.
- [ ] Set the permitted number of attempts.
- [ ] Configure the grading method.
- [ ] Review question behaviour.
- [ ] Configure question pagination.
- [ ] Review navigation method.
- [ ] Configure review options.
- [ ] Verify password and access restrictions where applicable.
- [ ] Preview the quiz before student access.

## 3. Understanding Quiz Navigation

Moodle provides two important navigation methods.

### Free Navigation

- Students can move between questions.
- Students can revisit previous questions.
- Students can change answers before submitting.
- Suitable for assessments where flexible navigation is preferred.

### Sequential Navigation

- Students must answer questions in the configured sequence.
- Students cannot return to previous questions.
- Students cannot skip ahead to later questions.
- Suitable where the lecturer requires a fixed question sequence.

**Important:** A student who opens a quiz using sequential navigation cannot freely move backwards through the questions.

## 4. Managing Saved Quiz Attempts

Moodle may retain an attempt when a student leaves a quiz without submitting it.

Depending on the quiz settings, the student may be able to resume the saved attempt.

### Recommended support procedure

1. Open the relevant Moodle course.
2. Locate the quiz.
3. Open the quiz and select Results or Attempts.
4. Identify the affected student's attempt.
5. Check the attempt status.
6. Establish whether the attempt is still in progress, overdue, or already submitted.
7. Check the quiz availability and time-limit settings.
8. Consult the lecturer before making changes that affect the student's assessment.

### Important considerations

- Do not delete an attempt simply because a student reports a problem.
- Preserve existing answers and attempt records.
- Check whether the attempt can be resumed.
- Where necessary, obtain lecturer approval before allowing another attempt.
- Document any intervention.

## 5. Common Moodle Quiz Problems

### Problem 1: Student Opens the Quiz and Lands on a Later Question

**Possible causes:**
- The student is resuming an existing attempt.
- The attempt has already progressed to a later question.
- Sequential navigation is enabled.
- The student previously attempted the quiz.

**Recommended action:**
1. Check the student's attempt history.
2. Confirm whether an attempt is already in progress.
3. Check the navigation method.
4. Establish whether the student is resuming an earlier attempt.
5. Refer the case to the lecturer if an assessment reset or additional attempt is necessary.

### Problem 2: Student Cannot Return to Previous Questions

**Possible cause:** Sequential navigation is enabled.

**Recommended action:**

The lecturer should review the quiz settings and determine whether Free Navigation is more appropriate.

Changing the navigation method should be done carefully, especially when students have already started attempts.

### Problem 3: Student Cannot Resume a Saved Attempt

**Possible causes:**
- The quiz closing date has passed.
- The attempt is no longer eligible for continuation.
- The time limit has expired.
- The attempt has already been submitted.
- Access restrictions prevent continuation.

**Recommended action:**
1. Review the attempt status.
2. Check the quiz availability dates.
3. Review time-limit and overdue-attempt settings.
4. Consult the lecturer.
5. Determine whether an authorised additional attempt is appropriate.

### Problem 4: Student Cannot See All Questions

**Possible causes:**
- Question pagination settings.
- Sequential navigation.
- An existing attempt.
- Quiz configuration or display issues.

**Recommended action:**
1. Check the number of questions in the quiz.
2. Review questions per page.
3. Inspect the student's attempt.
4. Preview the quiz using an appropriate test account.

## 6. Troubleshooting and Escalation Workflow

1. Receive the student's complaint.
2. Record the course and quiz details.
3. Identify the affected student and attempt.
4. Review quiz configuration.
5. Inspect attempt status.
6. Identify the likely cause.
7. Consult the lecturer where academic decisions are required.
8. Apply an authorised technical correction.
9. Test the solution.
10. Document the resolution.

## 7. Quiz Support Incident Record

| Field | Information |
|---|---|
| Course name | |
| Quiz name | |
| Student identifier | |
| Date reported | |
| Problem description | |
| Attempt status | |
| Identified cause | |
| Action taken | |
| Lecturer consulted | |
| Resolution status | |

## 8. Good Practice for Moodle Support Teams

- Protect the integrity of student assessment records.
- Avoid deleting existing attempts without authorisation.
- Document all technical interventions.
- Involve lecturers in academic assessment decisions.
- Test quiz configurations before publication.
- Maintain clear communication with affected students.
- Follow institutional assessment policies.

## 9. Conclusion

Effective Moodle quiz administration requires proper configuration, careful monitoring of student attempts, and timely technical support.

This guide supports consistent troubleshooting practices and promotes reliable online assessment delivery.

---

**Developed by:** Damaris  
**TEKTAGOGY Group**  
*Transforming Learning Through Technology.*
