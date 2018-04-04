$(document).ready((function()
{
  $("#warningMessage").slideDown('slow');
}))

$('#warningButton').click(function()
 {
    document.getElementById('warningMessage').style.display = "none";
})

$('#successButton').click(function()
 {
})
 

$('#signInButton').click(function()
{
  var email = $('#username').val();
  var password = $('#password').val();
  
  if((email != '') && (password != ''))
  {
    document.getElementById("signInButton").style.background='#18AA48';
    alert("Successful!");
  }
  else
  {
    alert("Must enter a username and password!");
  }
})


$('#warningMessage').click(function()
                     {
  document.getElementById('warningMessage').style.display = "none";
})
