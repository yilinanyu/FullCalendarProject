# FullCalendarProject
FullCalender 
FullCalendar can be utilized to project development,it can achieve add, edit and delete calendar events in FullCalendar by Jquery, Php
HTML
We add a file called cal_opt.html and add the CSS,JS。
<link rel="stylesheet" type="text/css" href="css/fullcalendar.css"> 
<link rel="stylesheet" type="text/css" href="css/fancybox.css"> 
<script src='js/jquery-1.9.1.min.js'></script> 
<script src='js/jquery-ui-1.10.3.custom.min.js'></script> 
<script src='js/fullcalendar.min.js'></script> 
<script src='js/jquery.fancybox-1.3.1.pack.js'></script> 
in my body: <div id="calendar"></div>
We call fullCalendar calendar api, calendar events from the event data source in json.php, which is read by PHP mysql data and then generate returns JSON data format to fullCalendar render event.
Fancybox through ajax call event.php contents. event.php by acquiring parameters, showing the form of a new event in the pop-up layer.
do.php to handle the form submission, including the back will explain the changes and delete operations calendar events. By processing form data, and then writes the data to MySQL data table, and returns the result.
