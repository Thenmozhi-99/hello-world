<!DOCTYPE html>
<html>
<body>

<h2>Login Forms</h2>

<form action="/action_page.php">
  <label for="fname">Customer name:</label><br><br>
  <input type="text" id="fname" name="fname"><br><br>
<button onclick="myFunction()">Submit</button>
<input type="submit" value="Cancel">
</form>
<script>
function myFunction() {
  alert("Information saved successfully");
}
</script>
</body>
</html>
