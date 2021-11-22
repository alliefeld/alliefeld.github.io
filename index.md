<script>
<!--
/*
Random link button- By JavaScript Kit (http://javascriptkit.com)
Over 300+ free scripts!
This credit MUST stay intact for use
*/

//specify random links below. You can have as many as you want
var randomlinks=new Array()

randomlinks[0]="https://forms.gle/y7ZCYTBoQXMmQTXw5"
randomlinks[1]="https://forms.gle/hok5Y4XkqZgi9fte9"

function randomlink(){
window.location=randomlinks[Math.floor(Math.random()*randomlinks.length)]
}
</script>
