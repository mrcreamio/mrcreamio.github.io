<?php
$msg = '';
$msgClass = '';
// check for the Submit
if (filter_has_var(INPUT_POST, 'submit')) {
    //echo "Submited";
    //getting form data
    $name = $_POST['name'];
    $email = $_POST['email'];
    $message = $_POST['message'];

    //check required fields
    if (!empty($name) && !empty($email) && !empty($message)) {
      //echo "passed";
      if (filter_var($email, FILTER_VALIDATE_EMAIL) === false) {
        //failed
        $msg = 'please enter a valid email';
        $msgClass = 'alert-danger';
      }else {
        //passed
        echo "passed";
      }
    }
    else {
      $msg = 'please fill all the fields';
      $msgClass = 'alert-danger';
    }
}
 ?>

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Contact Us</title>
  <link rel="stylesheet" href="https://bootswatch.com/4/cosmo/bootstrap.min.css">

  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
          <div class="navbar-header">
            <a class="navbar-brand" href="index.php">My Website</a>
          </div>
        </div>
      </nav>
      <div class="container">
        <?php  if ($msg != ''):  ?>
          <div class="alert <?php echo $msgClass; ?>">
            <?php echo $msg ; ?>
          </div>
      <?php endif;?>
        <form class="" action="<?php echo $_SERVER['PHP_SELF']; ?>" method="post">
          <div class="form-group">
              <label>Name</label>
              <input type="text" name="name" value="<?php echo isset($_POST['name']) ? $name : ''; ?>" class="form-control">
          </div>
          <div class="form-group">
              <label>Email</label>
              <input type="text" name="email" value="<?php echo isset($_POST['email']) ? $email : ''; ?>" class="form-control">
          </div>
          <div class="form-group">
              <label>Message</label>
              <textarea name="message" class="form control"><?php echo isset($_POST['message']) ? $message : ''; ?></textarea>
          </div>
          <br>
          <button type="submit" name="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
  </body>
</html>
