Scifi Box v.1.17.03.22 is library to style div like sici-fi style

#Documentation:

HTML structure:

*For node style:
<div class="scifi_box node"><div class="corner"><div class="top left"></div>
<div class="top right"></div><div class="bottom left"></div><div class="bottom right"></div></div>
<div class="content">

</div></div>

*For inner edge style:
<div class="scifi_box edge inner"><div class="corner"><div class="top left"></div>
<div class="top right"></div><div class="bottom left"></div><div class="bottom right"></div></div>
<div class="content">

</div></div>

*For outer edge style:
<div class="scifi_box edge outer"><div class="corner"><div class="top left"></div>
<div class="top right"></div><div class="bottom left"></div><div class="bottom right"></div></div>
<div class="content">

</div></div>

*For cross edge style:
<div class="scifi_box edge cross"><div class="corner"><div class="top left"></div>
<div class="top right"></div><div class="bottom left"></div><div class="bottom right"></div></div>
<div class="content">

</div></div>


*Default theme(light/dark):
-light:
<div class="scifi_box light"><div class="corner"><div class="top left"></div>
<div class="top right"></div><div class="bottom left"></div><div class="bottom right"></div></div>
<div class="content">

</div></div>
-dark:
<div class="scifi_box dark"><div class="corner"><div class="top left"></div>
<div class="top right"></div><div class="bottom left"></div><div class="bottom right"></div></div>
<div class="content">

</div></div>

Custom configuration:
.scifi_box{
	background-color:custom;
	border-color:custom;
}
*For node:
.scifi_box.node>.corner>div{
	background:white;
}
*For edge:
.scifi_box.edge>.corner>div{
	border-color:white;
}

***Note: In simplex version inner edge need extra adjustment:
.scifi_box.edge.inner>.corner{
	padding:custom;
}
