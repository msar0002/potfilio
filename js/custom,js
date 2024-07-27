const scrollToTopButton = document.getElementById("scrollToTopBtn");
  
// Show the button when the user scrolls down 20px from the top
window.onscroll = function() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    scrollToTopButton.style.display = "block";
  } else {
    scrollToTopButton.style.display = "none";
  }
};

// Scroll to the top of the page when the button is clicked
scrollToTopButton.addEventListener("click", () => {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
});