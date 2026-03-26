---
agent: agent
description: Create a new programming homework assignment
argument-hint: Provide assignment details
---

# Create New Programming Assignment

Your goal is to generate a new homework assignment for the Mergington High School students.

## Step 1: Gather Assignment Information

If not already provided by th user, ask what the assignment will be about.

## Step 2: Create Assignment Structure

 - Create a new directory in the `assignments` folder with a descriptive name based on the assignment topic
 - Create a new file in the new directory namesd `README.md` with the structure from the [`assignment-template.md`](../../templates/assignment-template.md) file
 - Fill out the assignment details in the new README.md file
 - (Optional) Add started code or attachments if the assignment needs them - add these files to the same assignment folder

## Step 3: Update Website Configuration

Update the assignments list in [`config.json`](../../config.json) website configuration file to include the new assignments. For the dueDate field, use the curren date plus 7 days unless otherwise specified by the user.