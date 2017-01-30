$(document).ready(function() {
  $("#topBar").hide();
  $("#topBar").fadeIn(4000);

  $(".name").hide();
  $(".name").fadeIn(4000);

  $(window).scroll(function() {
    var nameTop = $("#name").height();
    if ($(this).scrollTop() >= nameTop) {
      $("#name").slideUp();
    }
    else if ($(this).scrollTop() < nameTop) {
      $("#name").show("slow");
    }
  });
});
