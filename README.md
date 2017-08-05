Following are the CSV Data sets are as follows:

<ol>
  <li> UsersDumpForCodeTest.csv </li>
    <ol>
      <li> Fields: UserID, country, certifications </li>
      <li>Description: This data set contains information on countries and certifications associated with the user. UserId uniquely identifies the user.</li>
    </ol>

  <li> AssessmentScoreForCodeTest.csv </li>
    <ol>
      <li>Fields: TestId, UserId, assessment_name, score</li>
      <li>Description: This data set contains scores for assessments(tests) that the user has taken. TestID uniquely identifies the test that the user has taken.</li>
    </ol>

  

  <li> UserSurveyResultsForCodeTest.csv </li>
    <ol> 
      <li> Fields: TestID, question, answer </li>
      <li>Description: Surveys are presented to users after they finish taking the test. A survey consists of a collection of questions and answers. And a survey is tied to a TestID.</li>
    </ol>
  
  

  <li>AssessmentRealTimeEventsForCodeTest.csv</li>
    <ol> 
      <li> Fields: TestID, assessmentname, eventcode, timestamp </li>
      <li> Description: While the user is taking an assessment(test) , real time events are collected which represent the various stages of a test. Following are the event codes: </li>
      <ol>
        <li> STRASMNT: When the user chooses to start the assessment </li> 
        <li> RDYASMNT: When the assessment environment is loaded and ready for the student to work on it </li> 
        <li> GRDDOM: Grades a domain (sub-section) of an assessment </li>
        <li> GRDASMNT: Grades the entire assessment </li>
        <li> VIEWASMTDIAG: When the student views a diagram-hint on the assessment </li>
        <li> VIEWASMTGRADINGHINT: When the student views a grading-hint </li>
        <li> CANCASMNT: When the user selected to cancel the assessment </li>
        <li> ABNDNASMNT: When the user never completes the assessment or walks out/abandons the assessment. </li>
        <li> CMPLASMNT: When the assessment is complete </li>
      </ol>
    </ol>
</ol>
My tasks were:

<ol>
  <li> Analyze these data sets and present your analysis. This is an open ended task to exercise your creativity. </li>
  <li> Find the average time taken to complete an assessment, group by assessment name. </li>
  <li> Generate a list of users that fit the following criteria: </li>
  <ol> 
    <li> Got 80% or above on an assessment. </li>
    <li> Had a 100% chance of referring  a friend. </li>
    <li> Is based in the USA. </li>
    <li> Has received AWS certifications. </li>
    <li> Sort by test scores and most taken assessments first.
  </ol>
</ol>
