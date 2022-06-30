
<html>
<head>
<script>
function search() {
    let input = document.getElementById('searchbar').value
    input=input.toLowerCase();
    let x = document.getElementsByClassName('indexvals');
      
    for (i = 0; i < x.length; i++) { 
        if (!x[i].innerHTML.toLowerCase().includes(input)) {
            x[i].style.display="none";
        }
        else {
            x[i].style.display="list-item";                 
        }
    }
}
</script>



<style>

  #searchbar{
     margin-left: 0%;
     padding:15px;
     border-radius: 10px;
   }
 
   input[type=text] {
      width: 90%;
      -webkit-transition: width 0.15s ease-in-out;
      transition: width 0.15s ease-in-out;
   }
 
   /* When the input field gets focus,
        change its width to 100% */
   input[type=text]:focus {
     width: 90%;
   }

</style>

</head>
</html>


# The Linux Cheat Sheet



# INDEX:
<ol>
    <li class="indexvals"><a href="#bash-cheats">Networking</a></li> 
        <ul id="myUL">
            <li class="indexvals"><a href="#bash-keybinds">Bash Keybinds</a></li>
        </ul>
    <li class="indexvals"><a href="#operating-system-security">Security in Operating Systems</a></li>
        <ul id="myUL">
        </ul>
</ol>