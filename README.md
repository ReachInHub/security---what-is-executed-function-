security---what-is-executed-function-
=====================================

         //$(document).ready(function () {         //    $('#LessonSupportPaneDisplayTrigger').hide();         //});          document.domain =         (new function () { //Neat way to prevent creation of a global variable or function.             var domainSlices = document.domain.split(".");             this.results = domainSlices[domainSlices.length - 2] + "." + domainSlices[domainSlices.length - 1];         }).results;         var initialization = {};         initialization.Model = {"AssessmentOverlay":{"Attempts":[{"ActualTimeSpent":{"Ticks":63648740000,"Days":0,"Hours":1,"Milliseconds":874,"Minutes":46,"Seconds":4,"TotalDays":0.073667523148148145,"TotalHours":1.7680205555555555,"TotalMilliseconds":6364874,"TotalMinutes":106.08123333333333,"TotalSeconds":6364.874},"AssessmentID":0,"AttemptID":150957270,"Continue":0,"EndTime":"\/Date(1400539060000)\/","GradeID":763209954,"IsPrescriptiveTest":false,"IsPretest":false,"PassingThreshold":70,"Score":68,"StartTime":"\/Date(1400537742840)\/","Status":0,"Label":"Attempt 1"},{"ActualTimeSpent":{"Ticks":40268660000,"Days":0,"Hours":1,"Milliseconds":866,"Minutes":7,"Seconds":6,"TotalDays":0.046607245370370372,"TotalHours":1.1185738888888888,"TotalMilliseconds":4026866,"TotalMinutes":67.114433333333338,"TotalSeconds":4026.866},"AssessmentID":0,"AttemptID":151496691,"Continue":0,"EndTime":"\/Date(1400543105543)\/","GradeID":763223899,"IsPrescriptiveTest":false,"IsPretest":false,"PassingThreshold":70,"Score":0,"StartTime":"\/Date(1400539078677)\/","Status":0,"Label":"Attempt 2"}],"QuizAttempt":{"AllAttempts":1,"Attempts":1,"ClassType":0,"FailAttempts":3,"MinStatus":1,"Retakes":3},"TimeLimit":{"Ticks":72000000000,"Days":0,"Hours":2,"Milliseconds":0,"Minutes":0,"Seconds":0,"TotalDays":0.083333333333333329,"TotalHours":2,"TotalMilliseconds":7200000,"TotalMinutes":120,"TotalSeconds":7200},"TimeSpentForAllAttempts":{"Ticks":103917400000,"Days":0,"Hours":2,"Milliseconds":740,"Minutes":53,"Seconds":11,"TotalDays":0.12027476851851851,"TotalHours":2.8865944444444445,"TotalMilliseconds":10391740,"TotalMinutes":173.19566666666668,"TotalSeconds":10391.74},"HasObjectives":false,"HasRetakes":true,"IsAssessmentByPassed":false,"IsAttemptActive":true,"IsAutomaticProgressionOn":false,"IsFreeMovementOn":false,"IsPretest":false,"IsPrescriptiveTest":false,"IsReviewAllowed":false,"IsTeacherReviewRequired":false,"ShowNextActivity":false,"SkipOverlay":false},"Navigation":{"LessonName":"Unit Test","ActivityName":"Unit Test","ActivityStatus":"Complete","ActivityOrder":"051110","CourseID":"9744","AttemptID":null,"GlossaryID":"6f9c94f2-6a62-6365-7473-000000000000","ToolsID":"10261746","NotesID":"player_6f9c94f2-6a62-6365-7473-000000000000_14825919","TranscriptID":"6f9c94f3-6a62-6365-7473-000000000000","LearningObjectKey":"6f9c94f3-6a62-6365-7473-000000000000","LessonKey":"6f9c94f2-6a62-6365-7473-000000000000","ResourceLinkID":null,"Progress":81,"PrevActivity":null,"NextActivity":null,"Warning":null,"ShowOverlay":true,"LookupLink":null,"UserID":"5960155","ContextID":"14825919","CEContextID":"14825919","Role":"Learner","ConsumerKey":"v4","NavigationLocked":false,"EssayType":null},"IsPretestResponse":false,"IsResponse":false,"IsError":false,"ErrorMessage":null,"ShowStartTile":true};         //initialization.Services = {};         //initialization.Services.overlay = 'http://local.education2020.com/player/overlay/';      
