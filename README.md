# Primary-schedule


<!DOCTYPE html>
<html>
<head>
<title>Primary Digital Classes</title>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
 
<script type="text/javascript">
function schedule(){

var dt = new Date(document.getElementById("edate").value);
var sdt = document.getElementById("sday");

var dd = dt.getDate();
var mm = dt.getMonth()+1;
var yy = dt.getFullYear();
if(isNaN(dd))
alert("please select a date");


var cls = Number(document.getElementById("eclass").value);

var cls1 = document.getElementById("class1");

var clss = document.getElementById("hdcls");

var tm1 = document.getElementById("time1");
var tm2 = document.getElementById("time2");
var sb1 = document.getElementById("subj1");
var sb2 = document.getElementById("subj2");
var ls1 = document.getElementById("lesn1");
var ls2 = document.getElementById("lesn2");

sdt.value = dd+"/"+mm+"/"+yy;

switch(cls){
case 0:
alert("Please select a class");
break;
case 3:
clss.value= "Digital Classes for 3rd Class on "+ sdt.value;
break;
case 4:
clss.value=" Digital Classes for 4th Class on "+ sdt.value;
break;
case 5:
clss.value=" Digital Classes for 5th Class on "+ sdt.value;
break;
}


switch(cls){
case 3:
tm1.value = "09:00 am - 09:30 am";
tm2.value = "10:30 am - 11:00 am";
switch(dd){
case 13:
sb1.value = "English";
sb2.value = "EVS";
ls1.value = "Swamy and the Magic Beans, A Reading";
ls2.value = "జంతువులు, వాటి నివాసాలు "
break;
case 14:
sb1.value = "EVS";
sb2.value = "--";
ls1.value = "జంతువులు వాటి నివాసాలు";
ls2.value = "No classes today"
break;
case 15:
sb1.value = "--";
sb2.value = "Telugu";
ls1.value = "No classes today";
ls2.value = "బాల భీముడు - III";
break;
case 16:
sb1.value = "Telugu";
sb2.value = "Maths";
ls1.value = "బాల భీముడు - III";
ls2.value = "999 వరకు సంఖ్యలను పోల్చడం";
break;
case 17:
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
case 18:
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
case 19:
sb1.value = "Maths";
sb2.value = "--";
ls1.value = "999 వరకు సంఖ్యలను పోల్చడం";
ls2.value = "No classes today";
break;
case 20:
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
case 21:
sb1.value = "--";
sb2.value = "EVS";
ls1.value = "No classes today";
ls2.value = "వలస పక్షులు, కిటకాలు";
break;
case 22:
sb1.value = "EVS";
sb2.value = "English";
ls1.value = "వలస పక్షులు, కిటకాలు";
ls2.value = "Swamy and the Magic Beans, B Reading";
break;
case 23:
sb1.value = "English";
sb2.value = "--";
ls1.value = "Swamy and the Magic Beans, B Reading";
ls2.value = "No classes today";
break;
case 24:
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
case 25:
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
case 26:
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
}
break;
case 4:
tm1.value = "09:30 am - 10:00 am";
tm2.value = "11:00 am - 11:30 am";
switch(dd){
case 13:
sb1.value = "Telugu";
ls1.value = "పరమానందయ్య శిష్యుల కథ - II";
sb2.value = "--";
ls2.value = "No classes today";
break;
case 14:
sb1.value = "--";
ls1.value = "No classes today";
sb2.value = "Maths";
ls2.value = "రెండంకెల సంఖ్యలు - సంఖ్యారేఖ";
break;
case 15:
sb1.value = "Maths";
ls1.value = "రెండంకెల సంఖ్యలు - సంఖ్యారేఖ";
sb2.value = "Maths";
ls2.value = "మూడంకెల సంఖ్యలు - సంఖ్యారేఖ";
break;
case 16:
sb1.value = "Maths";
ls1.value = "మూడంకెల సంఖ్యలు - సంఖ్యారేఖ";
sb2.value = "--";
ls2.value = "No classes today";
break;
case 17:
sb1.value = "--";
ls1.value = "No classes today";
sb2.value = "--";
ls2.value = "No classes today";
break;
case 18:
sb1.value = "--";
ls1.value = "No classes today";
sb2.value = "--";
ls2.value = "No classes today";
break;
case 19:
sb1.value = "--";
ls1.value = "No classes today";
sb2.value = "Maths";
ls2.value = "పెద్ద సంఖ్యలు - విస్తరణ, సంక్షిప్త రూపం - పోల్చడం ";
break;
case 20:
sb1.value = "Maths";
ls1.value = "పెద్ద సంఖ్యలు - విస్తరణ, సంక్షిప్త రూపం - పోల్చడం ";
sb2.value = "Telugu";
ls2.value = "పరమానందయ్య శిష్యులు - III";
break;
case 21:
sb1.value = "Telugu";
ls1.value = "పరమానందయ్య శిష్యులు - III";
sb2.value = "--";
ls2.value = "No classes today";
break;
case 22:
sb1.value = "--";
ls1.value = "No classes today";
sb2.value = "EVS";
ls2.value = "మొక్కల రకాలు - వాటి వర్గీకరణ ";
break;
case 23:
sb1.value = "EVS";
ls1.value = "మొక్కల రకాలు - వాటి వర్గీకరణ ";
sb2.value = "English";
ls2.value = "The Pancake - B Reading";
break;
case 24:
sb1.value = "--";
ls1.value = "No classes today";
sb2.value = "--";
ls2.value = "No classes today";
break;
case 25:
sb1.value = "--";
ls1.value = "";
sb2.value = "--";
ls2.value = "";
break;
case 26:
sb1.value = "English";
ls1.value = "The Pancake - B Reading";
sb2.value = "Maths";
ls2.value = "పెద్ద సంఖ్యలు - సంఖ్యా భావనతో కూడిన సమస్యల సాధన";
break;
}
break;
case 5:
switch(dd){
case 13:
tm1.value = "--";
tm2.value = "11:00 am - 11:30 am";
sb1.value = "--";
sb2.value = "Maths";
ls1.value = "No classes today";
ls2.value = "2, 3 అంకెల సంఖ్యలను 2 అంకెల సంఖ్యలతో గుణించడం ";
break;
case 14:
tm1.value = "09:30 am - 10:00 am";
tm2.value = "10:30 am - 11:00 am";
sb1.value = "Maths";
sb2.value = "English";
ls1.value = "2, 3 అంకెల సంఖ్యలను 2 అంకెల సంఖ్యలతో గుణించడం ";
ls2.value = "Karate Kitten - B Reading";
break;
case 15:
tm1.value = "09:00 am - 09:30 am";
tm2.value = "--";
sb1.value = "English";
sb2.value = "--";
ls1.value = "Karate Kitten - B Reading";
ls2.value = "No classes today";
break;
case 16:
tm1.value = "--";
tm2.value = "11:00 am - 11:30 am";
sb1.value = "--";
sb2.value = "EVS";
ls1.value = "No classes today";
ls2.value = "రకరకాల ఆహార పదార్థాలు";
break;
case 17:
tm1.value = "--";
tm2.value = "--";
sb1.value = "--";
sb2.value = "--";
ls1.value = "";
ls2.value = "";
break;
case 18:
tm1.value = "--";
tm2.value = "--";
sb1.value = "--";
sb2.value = "--";
ls1.value = "";
ls2.value = "";
break;
case 19:
tm1.value = "09:30 am - 10:00 am";
tm2.value = "10:30 am - 11:00 am";
sb1.value = "EVS";
sb2.value = "Telugu";
ls1.value = "రకరకాల ఆహార పదార్థాలు";
ls2.value = "యాదగిరి గుట్ట - III ";
break;
case 20:
tm1.value = "09:00 am - 09:30 am";
tm2.value = "10:30 am - 11:00 am";
sb1.value = "Telugu";
sb2.value = "Maths";
ls1.value = "యాదగిర ిగుట్ట - III ";
ls2.value = "వివిధ సందర్భాలలో గుణకారం";
break;
case 21:
tm1.value = "09:00 am - 09:30 am";
tm2.value = "11:00 am - 11:30 am";
sb1.value = "Maths";
sb2.value = "Maths";
ls1.value = "వివిధ సందర్భాలలో గుణకారం";
ls2.value = "3 అంకెల సంఖ్యలను 2 అంకెల సంఖ్యలతో భాగించడం";
break;
case 22:
tm1.value = "09:30 am - 10:00 am";
tm2.value = "--";
sb1.value = "Maths";
sb2.value = "--";
ls1.value = "3 అంకెల సంఖ్యలను 2 అంకెల సంఖ్యలతో భాగించడం";
ls2.value = "No classes today";
break;
case 23:
tm1.value = "--";
tm2.value = "10: 30 am - 11:00 am";
sb1.value = "--";
sb2.value = "Maths";
ls1.value = "No classes today";
ls2.value = "భాగహారం, గుణకారాల మధ్య సంబంధం";
break;
case 24:
tm1.value = "--";
tm2.value = "--";
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
case 25:
tm1.value = "--";
tm2.value = "--";
sb1.value = "--";
sb2.value = "--";
ls1.value = "No classes today";
ls2.value = "No classes today";
break;
case 26:
tm1.value = "09:00 am - 09:30 am";
tm2.value = "10:30 am - 11:00 am";
sb1.value = "Maths";
sb2.value = "Maths";
ls1.value = "భాగహారం, గుణకారాల మధ్య సంబంధం";
ls2.value = "దత్తాంశ పట్టికలు - సమాచార విశ్లేషణ";
break;
}
break;
}

}

</script>

<style>
td{
padding:5px;
text-align:center;
}
th{
padding:10px;
}
.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  background-color: purple;
  color: white;
  text-align:center;
  width: 100%;
  padding: 5px;

}

</style>

<body>
<center>
<h3 style="color:green"  >Digital Classes Schedule for Primary Classes (3rd, 4th, 5th)</h3>

<h3 style="color:brown" >(From 13/10/2020 to 26/10/2020)</h3>

<table>
<tr>
	<th align="right">Select Date :</th>
	<td align="left" ><input type="date" id="edate" min="2020-10-13" max="2020-10-26"></td>
</tr>

<tr>
	<th align="right">Select Class :</th>
	<td align="left" ><select type="select" Id ="eclass">
	<option value="0">--- Select class ---</option>
	<option value="3">Class 3</option>
	<option value="4">Class 4</option>
	<option value="5">Class 5</option>	
	</td>
</tr>
<tr>
<td colspan="2" align="center"><button Id ="go" onclick="javascript: schedule();" >Submit</button>
</tr>
</table>

<h3 style="color:blue" ><output Id="hdcls"></output><output id="day"></output></h3>

<table border="1px" >
	<tr>
		<th>Date</th>
		<th>Time</th>
		<th>Channel</th>
		<th>Subject</th>
		<th>Lesson / Topic</th>
	</tr>
	<tr>
	<td rowspan="2" ><output Id="sday"></output></td>
	<td><output Id="time1"></output></td>
	<td><output> T - SAT (విద్య)</output></td>
	<td><output Id="subj1"></output></td>
	<td><output Id="lesn1"></output></td>			
	</tr>
	<tr>
	<td><output Id="time2"></output></td>
	<td><output> DD (యాదగిరి)</output></td>
	<td><output Id="subj2"></output></td>
	<td><output Id="lesn2"></output></td>
	</tr>


</table>
<br>
<h3 style="color:red">Holidays for Digital Lessons</h3>
<table border="1" >
<tr><th>Date</th><th>Description</th></tr>
<tr><td>17/10/2020</td><td>Saturday / Bathukamma starting day </td></tr>
<tr><td>18/10/2020</td><td>Sunday</td</tr>
<tr><td>24/10/2020</td><td>Saturday / Durgashtami</td></tr>
<tr><td>25/10/2020</td><td>Sunday / Vijayadashami</td</tr>

</table>
<br><br>

<div class="footer">Prepared by : Vardhan Brahmanapally</div>

</center>
</body>
</html>
