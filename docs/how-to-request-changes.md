# How to Request Changes

This guide helps teachers and administrators request changes to the Mergington High School system without needing to modify code directly.

## Overview

We've created easy-to-use issue templates that guide you through requesting changes. Each template asks for specific information that helps Copilot coding agent understand and implement your request automatically.

## Available Issue Templates

### 🎯 Add New Activity

Use this template when you want to add a new extracurricular activity to the system.

**What you'll need to provide:**
- Activity name
- Description
- Meeting days and times
- Maximum number of participants
- Any students already signed up (optional)

**Example use case:** Adding a new "Photography Club" that meets on Wednesdays from 3:30 PM to 5:00 PM.

[Create an "Add New Activity" request →](../../issues/new?template=add-new-activity.yml)

---

### ✏️ Modify Activity Details

Use this template to update information about an existing activity.

**What you'll need to provide:**
- Name of the activity to modify
- What you want to change (description, schedule, capacity, etc.)
- The new values
- Reason for the change

**Example use case:** Changing "Chess Club" meeting time from Fridays to Thursdays, or increasing "Drama Club" capacity from 20 to 25 students.

[Create a "Modify Activity" request →](../../issues/new?template=modify-activity.yml)

---

### 🐛 Bug Report

Use this template to report problems or errors with the system.

**What you'll need to provide:**
- Description of the bug
- What you expected to happen
- Steps to reproduce the problem
- Which part of the system is affected
- Severity level

**Example use case:** Students can't sign up for an activity, error messages appear, or data displays incorrectly.

[Create a "Bug Report" →](../../issues/new?template=bug-report.yml)

---

### 🎨 UI/UX Enhancement

Use this template to suggest improvements to how the application looks or functions.

**What you'll need to provide:**
- Type of enhancement (visual design, layout, interaction, etc.)
- Which page or component to improve
- Current state vs. proposed improvement
- How it benefits users

**Example use case:** Making the activity cards larger, adding a search feature, improving mobile display, or adding color coding by activity type.

[Create a "UI/UX Enhancement" request →](../../issues/new?template=ui-enhancement.yml)

---

### ✨ Feature Request

Use this template to propose entirely new functionality.

**What you'll need to provide:**
- Feature description
- Problem it solves
- How it should work
- Who would use it
- Acceptance criteria (how to know it's complete)

**Example use case:** Adding the ability to filter activities by day of the week, exporting student lists, sending email notifications, or creating a waitlist feature.

[Create a "Feature Request" →](../../issues/new?template=feature-request.yml)

---

## How to Submit a Request

1. **Choose the Right Template**: Click one of the links above based on what you need
2. **Fill Out the Form**: Provide as much detail as possible in each field
3. **Review**: Make sure all required fields (marked with *) are completed
4. **Submit**: Click "Submit new issue"
5. **Assign to Copilot** (Optional): Add the `@copilot` mention or assign the issue to Copilot to have it automatically implemented

## Tips for Better Requests

✅ **Be Specific**: The more details you provide, the better Copilot can help
✅ **Include Examples**: If suggesting a change, show examples of what you want
✅ **Explain Why**: Help us understand the reason behind your request
✅ **Use Clear Language**: Write as if explaining to someone who isn't familiar with the system

## What Happens Next?

1. Your request is submitted as a GitHub issue
2. If assigned to Copilot, it will analyze your request
3. Copilot will implement the changes based on your specifications
4. A pull request will be created with the changes
5. You'll be notified when the changes are ready for review

## Need Help?

- **Documentation**: Check the [Development Guide](./how-to-develop.md) for technical details
- **Questions**: Open a blank issue or discussion if the templates don't fit your needs
- **Support**: Contact the system administrator for urgent issues

## Labels Explained

Issues created from these templates automatically get helpful labels:

- `copilot-ready`: This issue has enough detail for Copilot to work on it
- `enhancement`: Suggests an improvement or new feature
- `bug`: Reports a problem that needs fixing
- `activity`: Related to activity management
- `ui/ux`: Related to user interface or experience

These labels help organize and prioritize work on the system.
