Download Link: https://assignmentchef.com/product/solved-mscc-_mscbd-assignment2-building-a-room-scheduler
<br>



<h1>1           Assignment Information</h1>

<table width="372">

 <tbody>

  <tr>

   <td width="156">Course:</td>

   <td width="215">MSCC / MSCBD</td>

  </tr>

  <tr>

   <td width="156">Stage / Year:</td>

   <td width="215">1</td>

  </tr>

  <tr>

   <td width="156">Module:</td>

   <td width="215">Cloud Platforms &amp; Applications</td>

  </tr>

  <tr>

   <td width="156">Semester:</td>

   <td width="215">1</td>

  </tr>

  <tr>

   <td width="156">Assignment:</td>

   <td width="215">2 of 3</td>

  </tr>

  <tr>

   <td width="156">Date of Issue:</td>

   <td width="215">2021-03-04</td>

  </tr>

  <tr>

   <td width="156">Assignment Deadline:</td>

   <td width="215">2021-05-09 @ 23:55 (End of week 10)</td>

  </tr>

  <tr>

   <td width="156">Assignment Submission:</td>

   <td width="215">Upload to Moodle</td>

  </tr>

  <tr>

   <td width="156">Assignment Weighting:</td>

   <td width="215">16% of Module</td>

  </tr>

 </tbody>

</table>

<h1>2           Introduction</h1>

<strong>NOTE: read the whole assignment brief first before implementing it contains very important information</strong>

In this assignment you will be tasked with building an application that will schedule rooms for use. Your application will support a multitude of rooms and users. As there is potential for overlap in room bookings you will be expected to do validation here to prevent double bookings of rooms. Your application must be capable of the following

<ul>

 <li>The ability to add and delete rooms. You should not be able to add the same room twice nor should you be able to delete a room that currently has bookings.</li>

 <li>The ability to add and delete bookings for a room. A booking can only be made if it doesn’t clash or overlap with other bookings for that room. It should be possible to view all the bookings for a given day on a room. They should be listed in order of time. When a room is viewed there should be a facility to delete that booking. (but only by the user who made the booking)</li>

</ul>

The score for your application will depend on:

<ol>

 <li>How fully featured, complete, and robust your code is. Along with howwell your UI is thought out (80%)</li>

 <li>How well documented is your code</li>

</ol>

<h1>5           Coding Brackets</h1>

<ol>

 <li>Bracket 1

  <ul>

   <li>Get a working login and logout shell up and running</li>

   <li>Create appropriate models for a User, Room, and Booking</li>

  </ul></li>

 <li>Bracket 2

  <ul>

   <li>Build a UI that permits a user to add in a new room. <strong>Bracket Failure if the same room can be added twice</strong></li>

   <li>When a user logs in they should see the list of rooms that are available to book. <strong>Bracket Failure if not all rooms are shown</strong></li>

  </ul></li>

 <li>Bracket 3  Add in facilities for adding a booking to a room.

  <ul>

   <li>Bookings should be done on a seperate page <strong>Bracket Failure if not on a seperate page</strong></li>

   <li>Room bookings should be validated before they are accepted <strong>Bracket Failure if overlap is permitted or a booking can be made in the past</strong></li>

  </ul></li>

 <li>Bracket 4  Update the main UI to permit a user to query all rooms or a specific room for their own list of bookings.

  <ul>

   <li>Update the main UI to permit a user to query all bookings on a room.</li>

  </ul></li>

 <li>Bracket 5  When the list of bookings for a user is shown there should be a delete button shown beside the booking.

  <ul>

   <li>When the delete button is clicked it should delete that booking <strong>Bracket Failure if the wrong booking is deleted </strong> When the list of bookings for a user is shown there should also be an edit button shown beside the booking.</li>

  </ul></li>

 <li>Bracket 6  Editing should take place on a seperate page and the form should be prepopulated with the current data about the booking <strong>Bracket failure if neither attempted C</strong>lashes and past dates/times must be checked for when editing a booking.</li>

 <li>Bracket 7  In the list of bookings on a room show the delete and edit buttons but only on the bookings owned by a user.

  <ul>

   <li>Modify the room listing facility to include a filter by date. It should only show the room bookings for all rooms that fall in that time range.</li>

  </ul></li>

 <li>Bracket 8

  <ul>

   <li>UI design: well thought out UI that is easy and intuitive to use.</li>

  </ul></li>

</ol>