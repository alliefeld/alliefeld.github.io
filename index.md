<a href="javascript:openSite()">Click to go to form</a>
<script>
function openSite() {
var links = [
              "https://forms.gle/y7ZCYTBoQXMmQTXw5",
              "https://forms.gle/hok5Y4XkqZgi9fte9"]

            openSite = function() {
              // get a random number between 0 and the number of links
              var randIdx = Math.random() * links.length;
              // round it, so it can be used as array index
              randIdx = parseInt(randIdx, 10);
              // construct the link to be opened
              var link = 'http://' + links[randIdx];
              };
              
    return link;
    
    document.getElementById("link").innerHTML = openSite();
}
</script>
