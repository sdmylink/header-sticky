# header-sticky
sticky header
$(window).on('scroll',function() {    
   var scroll = $(window).scrollTop();
   if (scroll < 245) {
    $(".header-middle").removeClass("scroll-header");
   }else{
    $(".header-middle").addClass("scroll-header");
   }
  });
