# ÕIS to iCal Converter - Convert calendar from student.taltech.ee to iCal

> Last updated 01.2024

Recently, the feature that allowed students to create and export their own calendars from TalTech ÕIS was removed. The removal of this feature complicates life for many students and should never have been removed without a sufficient replacement. This workaround was created to extract your custom calendar from student.taltech.ee as an iCal file, so it can be added to other calendar applications like Google Calendar.

### Requirements
- Working and set up student.taltech.ee
- PC with Firefox Web Browser

### Tutorial
- Go to student.taltech.ee in Firefox Web Browser and Log In
- Right-click anywhere on the page and click "Inspect (Q)" This will open up a panel below
- Click on the network tab and then reload
![](https://github.com/Ingmar05/OIS2ICAL/blob/main/docs/1.png?raw=true)
- After the page reloads move the calendar to a month, where you want to start the calendar from. The month should already have some lectures
- Then from the network tab find an item with File name "studentCourses" with type "POST" that has some lectures in the Response tab
![](https://github.com/Ingmar05/OIS2ICAL/blob/main/docs/2.png?raw=true)
- On the right Click to see the RAW response and copy that (Ctrl+C)
![](https://github.com/Ingmar05/OIS2ICAL/blob/main/docs/4.png?raw=true)
- Use the Õis2Ical tool at https://ois2ical.ingmarsell.com/ (Or index.html in this project)
- Paste the previously copied data to the tool
- Click convert to iCal and then Downlaod the iCal file
![](https://github.com/Ingmar05/OIS2ICAL/blob/main/docs/5.png?raw=true)
- Your are Done! Now you can import the iCal file other calendar applications like Google Calendar.

