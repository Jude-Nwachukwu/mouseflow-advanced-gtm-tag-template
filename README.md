# Mouseflow GTM Tag Template (UNOFFICIAL)

An **unofficial** Google Tag Manager tag template for **Mouseflow**. This template allows you to easily integrate Mouseflow tracking, install the tracking script, apply tags, identify users, customize sessions, track custom user friction, monitor 404 errors, and measure form interactions.

Developed by **Jude Nwachukwu Onyejekwe** from **DumbData**, a measurement resource hub. Learn more at [DumbData](https://dumbdata.co).

## Features
This template supports the following Mouseflow tracking features:
- **Install Tracking Code**: Automatically installs the Mouseflow tracking script.
- **Tags**: Apply Mouseflow tags to categorize sessions.
- **Custom Variables**: Define and store custom session variables.
- **User Identification**: Identify users by unique identifiers.
- **404 Friction Tracking**: Detect and log 404 error pages.
- **Custom Friction Tracking**: Monitor specific friction points in a user’s session.
- **Form Interaction Tracking**: Measure form interactions, including submissions, successes, and failures.

## How to Use the Template

### 1. **Select the Tag Type**
Choose a tag type in the **Tag Configuration** section of GTM:

- **Install Mouseflow Tracking** → Installs the Mouseflow tracking script.
- **Tags** → Assigns Mouseflow tags to sessions.
- **Custom Variable** → Stores custom session-level variables.
- **User Identification** → Identifies users with a unique ID.
- **404 Friction** → Tracks user interactions on 404 error pages.
- **Custom Friction** → Logs specific user friction points.
- **Track Form Events** → Monitors form interactions.

### 2. **Configure the Selected Tag Type**
Each tag type has specific configuration fields:

#### **Install Mouseflow Tracking**
- **Enter The Mouseflow Site ID** → Provide the unique site ID associated with your Mouseflow project.

#### **Tags**
- **Insert Tag Value** → Enter the tag name to categorize user sessions in Mouseflow.

#### **Custom Variable**
- **Insert Custom Variable Key** → Define the key name for the variable.
- **Insert Custom Variable Value** → Define the value for the variable.
- **Session Scope** → Enable to apply the variable across all sessions.

#### **User Identification**
- **Enter the User ID** → Specify the unique identifier for the user.

#### **404 Friction**
- No additional configuration is required.

#### **Custom Friction**
- **Insert Custom Friction Point** → Define the friction level (e.g., 1-10 scale).
- **Insert Custom Friction Name** → Provide a name for the friction event (optional).

#### **Form Interaction Tracking**
- **Select Form Interaction Type** → Choose between:
  - **Form Submit** → Track form submission attempts.
  - **Form Submit Success** → Track successful form submissions.
  - **Form Failure** → Track failed form submissions.
- **Enter The Form ID** → Specify the form’s unique identifier.

## Installation & Setup
1. **Import the Template**: Upload the tag template into GTM.
2. **Configure the Tag**: Select the appropriate tag type and fill in the required fields.
3. **Test & Publish**: Use GTM’s preview mode to test your setup before publishing.

## About DumbData
This template was developed by **Jude Nwachukwu Onyejekwe** from **DumbData**, a measurement resource hub offering tracking and analytics solutions. Visit [DumbData](https://dumbdata.co) for more resources.

---

**Note:** This is an **unofficial** GTM template and is not affiliated with Mouseflow.
