1. registration.html (Assignment 4.1 Updated)

<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Step 1: Character encoding -->
  <meta charset="UTF-8">

  <!-- Step 2: Responsive viewport -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Step 3: Descriptive page title -->
  <title>Student Portal — Registration Form</title>

  <!-- Step 4: Meta description -->
  <meta name="description" content="Official student enrollment and account registration form.">
  <meta name="author" content="Academic Administration">

  <!-- Step 5: Favicon (Graduation cap icon) -->
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🎓</text></svg>">

  <!-- Step 6: Embedded styles -->
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }
    body {
      background-color: #f3f4f6;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }
    .form-container {
      background-color: #ffffff;
      padding: 32px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 440px;
    }
    h2 {
      margin-bottom: 8px;
      color: #1f2937;
      text-align: center;
    }
    p.subtitle {
      margin-bottom: 24px;
      color: #6b7280;
      font-size: 14px;
      text-align: center;
    }
    .form-group {
      margin-bottom: 18px;
    }
    label {
      display: block;
      margin-bottom: 6px;
      font-size: 14px;
      font-weight: 600;
      color: #374151;
    }
    input {
      width: 100%;
      padding: 10px 14px;
      font-size: 15px;
      border: 1px solid #d1d5db;
      border-radius: 6px;
      outline: none;
      transition: border-color 0.2s, box-shadow 0.2s;
    }
    input:focus {
      border-color: #2563eb;
      box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.2);
    }
    .btn-submit {
      width: 100%;
      padding: 12px;
      background-color: #2563eb;
      color: #ffffff;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: background-color 0.2s ease;
      margin-top: 8px;
    }
    .btn-submit:hover {
      background-color: #1d4ed8;
    }
  </style>
</head>
<body>

  <div class="form-container">
    <h2>Student Registration</h2>
    <p class="subtitle">Please fill out all the fields below to register.</p>

    <form action="#" method="POST">
      <div class="form-group">
        <label for="fullName">Full Name</label>
        <input type="text" id="fullName" name="fullName" placeholder="e.g. Jane Doe" required>
      </div>

      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="e.g. jane.doe@example.com" required>
      </div>

      <div class="form-group">
        <label for="password">Password</label>
        <input type="password" id="password" name="password" placeholder="Create a strong password" required>
      </div>

      <div class="form-group">
        <label for="phoneNumber">Phone Number</label>
        <input type="tel" id="phoneNumber" name="phoneNumber" placeholder="e.g. +1 555-019-2834" required>
      </div>

      <div class="form-group">
        <label for="age">Age</label>
        <input type="number" id="age" name="age" min="1" max="120" placeholder="e.g. 20" required>
      </div>

      <button type="submit" class="btn-submit">Register</button>
    </form>
  </div>

</body>
</html>

2. job_application.html (Assignment 4.2 Updated)

<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Step 1: Character encoding -->
  <meta charset="UTF-8">

  <!-- Step 2: Responsive viewport -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Step 3: Descriptive page title -->
  <title>Careers — Job Application Form</title>

  <!-- Step 4: Meta description -->
  <meta name="description" content="Apply for open engineering and design positions by submitting your resume, portfolio, and skills.">
  <meta name="author" content="Human Resources">

  <!-- Step 5: Favicon (Briefcase icon) -->
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>💼</text></svg>">

  <!-- Step 6: Embedded styles -->
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }
    body {
      background-color: #f1f5f9;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 40px 16px;
    }
    .form-card {
      background: #ffffff;
      padding: 36px 32px;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
      max-width: 620px;
      width: 100%;
    }
    h2 {
      color: #0f172a;
      font-size: 24px;
      margin-bottom: 6px;
      text-align: center;
    }
    .subtitle {
      color: #64748b;
      font-size: 14px;
      text-align: center;
      margin-bottom: 28px;
    }
    .form-group {
      margin-bottom: 18px;
    }
    label.field-label {
      display: block;
      margin-bottom: 6px;
      font-size: 14px;
      font-weight: 600;
      color: #334155;
    }
    .required-star {
      color: #ef4444;
    }
    input[type="text"],
    input[type="email"],
    input[type="tel"],
    input[type="date"],
    input[type="url"],
    select,
    textarea {
      width: 100%;
      padding: 10px 14px;
      font-size: 15px;
      border: 1px solid #cbd5e1;
      border-radius: 6px;
      outline: none;
      background-color: #ffffff;
      color: #1e293b;
      transition: border-color 0.2s, box-shadow 0.2s;
    }
    input:focus,
    select:focus,
    textarea:focus {
      border-color: #2563eb;
      box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.15);
    }
    input:disabled {
      background-color: #f1f5f9;
      color: #94a3b8;
      cursor: not-allowed;
      border-style: dashed;
    }
    .options-group {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      margin-top: 6px;
    }
    .inline-option {
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 14px;
      color: #334155;
      cursor: pointer;
    }
    .inline-option input {
      cursor: pointer;
      width: 16px;
      height: 16px;
      accent-color: #2563eb;
    }
    textarea {
      resize: vertical;
      min-height: 110px;
    }
    .btn-submit {
      width: 100%;
      padding: 12px;
      background-color: #2563eb;
      color: #ffffff;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      margin-top: 12px;
      transition: background-color 0.2s ease;
    }
    .btn-submit:hover {
      background-color: #1d4ed8;
    }
  </style>
</head>
<body>

  <div class="form-card">
    <h2>Job Application Form</h2>
    <p class="subtitle">Please complete the form below to apply for the position.</p>

    <form action="#" method="POST">
      <div class="form-group">
        <label for="appId" class="field-label">Application ID (Auto-Generated)</label>
        <input type="text" id="appId" name="appId" value="APP-2026-0941" disabled>
      </div>

      <div class="form-group">
        <label for="fullName" class="field-label">Full Name <span class="required-star">*</span></label>
        <input type="text" id="fullName" name="fullName" placeholder="e.g. John Doe" required>
      </div>

      <div class="form-group">
        <label for="email" class="field-label">Email Address <span class="required-star">*</span></label>
        <input type="email" id="email" name="email" placeholder="e.g. john.doe@example.com" required>
      </div>

      <div class="form-group">
        <label for="phone" class="field-label">Phone Number <span class="required-star">*</span></label>
        <input type="tel" id="phone" name="phone" placeholder="e.g. +1 555-012-3456" required>
      </div>

      <div class="form-group">
        <label for="dob" class="field-label">Date of Birth <span class="required-star">*</span></label>
        <input type="date" id="dob" name="dob" required>
      </div>

      <div class="form-group">
        <label for="portfolioUrl" class="field-label">Portfolio URL <span class="required-star">*</span></label>
        <input type="url" id="portfolioUrl" name="portfolioUrl" placeholder="https://yourportfolio.com" required>
      </div>

      <div class="form-group">
        <label class="field-label">Preferred Shift <span class="required-star">*</span></label>
        <div class="options-group">
          <label class="inline-option" for="shiftDay">
            <input type="radio" id="shiftDay" name="preferredShift" value="day" required>
            Day Shift
          </label>
          <label class="inline-option" for="shiftNight">
            <input type="radio" id="shiftNight" name="preferredShift" value="night">
            Night Shift
          </label>
          <label class="inline-option" for="shiftFlexible">
            <input type="radio" id="shiftFlexible" name="preferredShift" value="flexible">
            Flexible
          </label>
        </div>
      </div>

      <div class="form-group">
        <label class="field-label">Key Technical Skills</label>
        <div class="options-group">
          <label class="inline-option" for="skillHtml">
            <input type="checkbox" id="skillHtml" name="skills" value="html">
            HTML5
          </label>
          <label class="inline-option" for="skillCss">
            <input type="checkbox" id="skillCss" name="skills" value="css">
            CSS3
          </label>
          <label class="inline-option" for="skillJs">
            <input type="checkbox" id="skillJs" name="skills" value="javascript">
            JavaScript
          </label>
          <label class="inline-option" for="skillGit">
            <input type="checkbox" id="skillGit" name="skills" value="git">
            Git & GitHub
          </label>
        </div>
      </div>

      <div class="form-group">
        <label for="jobRole" class="field-label">Applying for Position <span class="required-star">*</span></label>
        <select id="jobRole" name="jobRole" required>
          <option value="" disabled selected>-- Select a Job Role --</option>
          <option value="frontend-dev">Frontend Developer</option>
          <option value="backend-dev">Backend Developer</option>
          <option value="fullstack-dev">Full Stack Developer</option>
          <option value="ui-ux-designer">UI/UX Designer</option>
          <option value="qa-engineer">QA Engineer</option>
        </select>
      </div>

      <div class="form-group">
        <label for="coverLetter" class="field-label">Cover Letter <span class="required-star">*</span></label>
        <textarea id="coverLetter" name="coverLetter" rows="4" placeholder="Tell us why you are a great fit for this position..." required></textarea>
      </div>

      <button type="submit" class="btn-submit">Submit Application</button>
    </form>
  </div>

</body>
</html>

3. marksheet.html (Assignment 4.3 Updated)

<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Step 1: Character encoding -->
  <meta charset="UTF-8">

  <!-- Step 2: Responsive viewport -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Step 3: Descriptive page title -->
  <title>Examination Results — Student Marksheet (2025–2026)</title>

  <!-- Step 4: Meta description -->
  <meta name="description" content="Official annual examination score sheet and aggregate marks for Grade 10 students.">
  <meta name="author" content="Department of Examinations">

  <!-- Step 5: Favicon (Bar chart / Scoreboard icon) -->
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>📊</text></svg>">

  <!-- Step 6: Embedded styles -->
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }
    body {
      background-color: #f8fafc;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 30px 16px;
    }
    .table-container {
      background: #ffffff;
      padding: 28px;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
      overflow-x: auto;
      max-width: 800px;
      width: 100%;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      text-align: center;
      font-size: 15px;
    }
    caption {
      font-size: 20px;
      font-weight: 700;
      color: #1e293b;
      margin-bottom: 16px;
      text-align: center;
      letter-spacing: -0.02em;
    }
    th, td {
      border: 1px solid #e2e8f0;
      padding: 12px 14px;
    }
    thead tr:first-child th {
      background-color: #1e3a8a;
      color: #ffffff;
      font-weight: 600;
    }
    thead tr:nth-child(2) th {
      background-color: #2563eb;
      color: #ffffff;
      font-weight: 500;
      font-size: 14px;
    }
    tbody tr:nth-child(even) {
      background-color: #f8fafc;
    }
    tbody tr:hover {
      background-color: #f1f5f9;
    }
    tbody td:nth-child(2) {
      text-align: left;
      font-weight: 500;
    }
    .score-total {
      font-weight: 600;
      color: #1e3a8a;
    }
    tfoot tr {
      background-color: #e2e8f0;
      font-weight: 700;
      color: #0f172a;
    }
    tfoot td {
      border-top: 2px solid #94a3b8;
    }
  </style>
</head>
<body>

  <div class="table-container">
    <table>
      <caption>Annual Academic Examination Marksheet (2025–2026)</caption>
      <thead>
        <tr>
          <th rowspan="2">Roll No.</th>
          <th rowspan="2">Student Name</th>
          <th colspan="3">Subjects (Marks out of 100)</th>
          <th rowspan="2">Total Marks (300)</th>
        </tr>
        <tr>
          <th>Mathematics</th>
          <th>Science</th>
          <th>English</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>101</td>
          <td>Aarav Sharma</td>
          <td>92</td>
          <td>88</td>
          <td>85</td>
          <td class="score-total">265</td>
        </tr>
        <tr>
          <td>102</td>
          <td>Diya Patel</td>
          <td>78</td>
          <td>82</td>
          <td>90</td>
          <td class="score-total">250</td>
        </tr>
        <tr>
          <td>103</td>
          <td>Rohan Verma</td>
          <td>65</td>
          <td>74</td>
          <td>70</td>
          <td class="score-total">209</td>
        </tr>
        <tr>
          <td>104</td>
          <td>Ananya Iyer</td>
          <td>95</td>
          <td>91</td>
          <td>94</td>
          <td class="score-total">280</td>
        </tr>
        <tr>
          <td>105</td>
          <td>Kabir Singh</td>
          <td>84</td>
          <td>79</td>
          <td>81</td>
          <td class="score-total">244</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td colspan="2">Class Average</td>
          <td>82.8</td>
          <td>82.8</td>
          <td>84.2</td>
          <td class="score-total">249.6</td>
        </tr>
      </tfoot>
    </table>
  </div>

</body>
</html>