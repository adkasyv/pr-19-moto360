////////////////////////////////////////
// Media query
////////////////////////////////////////

/* grid and site dimensions */
// grid-increment-desktop = 80px
// grid-increment-tablet = 60px
// grid-increment-mobile = grid-increment-tablet

// grid-start-desktop = 60px
// grid-start-tablet = 40px
// grid-start-mobile = grid-start-tablet

// grid-end-desktop = 940px
// grid-end-tablet = 700px
// grid-end-mobile = 280px
// grid-end-mobile-wide = 400px

// site-width-desktop = 1000px
// site-width-tablet = 760px
// site-width-mobile = 320px
// site-width-wide = 480px

// /* media query dimensions */
// /* obviously the default view doesn't require a media query */
// media-query-tablet = 'only screen and (min-width: 760px) and (max-width: 1000px)'
// media-query-mobile = 'only screen and (max-width: 760px)'
// media-query-mobile-wide = 'only screen and (min-width: 480px) and (max-width: 760px)'



// /* The grid widths will be need to be modified based on media query (device width) 
// so we'll generate a general grid and then a media query-specific grid: */
// /* Ширину сетки необходимо будет изменить в зависимости от медиа-запроса (ширины устройства), 
// поэтому мы сгенерируем общую сетку, а затем сетку для медиа-запроса: */


// generate-grid(increment, start, end)
// 	total = start
// 	for n, x in 0..((end - start) / increment)
// 		.column-{x+1}
// 			width total
// 		total = total + increment


// /* and now to generate the grids... */


// /* Desktop Layout (default) */
// generate-grid(grid-increment-desktop, grid-start-desktop, grid-end-desktop)


// /* Tablet Layout - 760px */
// @media media-query-tablet
// 	generate-grid(grid-increment-tablet, grid-start-tablet, grid-end-tablet)

//  /* Wide Mobile Layout - 480px */
// @media media-query-mobile-wide
// 	generate-grid(grid-increment-mobile, grid-start-mobile, grid-end-mobile-wide)

// /* Mobile Layout - 320px */
// @media media-query-mobile
// 	generate-grid(grid-increment-mobile, grid-start-mobile, grid-end-mobile)


////////////////////////////////////////
// Media query
////////////////////////////////////////







////////////////////////////////////////
// Media query - new mode-0
////////////////////////////////////////

// больше чем
// widerthan(var)
//   condition = 'screen and (min-width: %s)' % var
//   @media condition
//     {block}

// ниже чем
// narrowerthan(var)
//   condition = 'screen ands (max-width: %s)' % var
//   @media condition
//     {block}

// extra_small = 600px   // widerthan     // больше чем
// small       = 600px   // narrowerthan  // ниже чем
// medium      = 768px   // narrowerthan  // ниже чем
// large       = 992px   // narrowerthan  // ниже чем
// extra_large = 1200px  // narrowerthan  // ниже чем

// site-width-desktop = 1000px
// site-width-tablet = 760px
// site-width-mobile = 320px
// site-width-wide = 480px

////////////////////////////////////////
// Media query - new mode
////////////////////////////////////////




////////////////////////////////////////
// Media query - new mode-1
////////////////////////////////////////

// ExtraSmallWidth = 748px
// SmallWidth = 748px
// MediumWidth = 748px
// LargeWidth = 748px
// ExtraLargeWidth = 748px

// mqExtraSmall  =  "only screen and (min-width: 320px) and (max-width: 480px)"
// mqSmall       =  "only screen and (min-width: 481px) and (max-width: 768px)"
// mqMedium      =  "only screen and (min-width: 769px) and (max-width: 1024px)"
// mqLarge       =  "only screen and (min-width: 1025px) and (max-width: 1200px)"
// mqExtraLarge  =  "only screen and (min-width: 1201px)"


mqExtraSmall  =  "only screen and (min-width: 320px) and (max-width: 480px)"
mqSmall       =  "only screen and (max-width: 768px)"
mqMedium      =  "only screen and (max-width: 1024px)"
mqLarge       =  "only screen and (max-width: 1200px)"
mqExtraLarge  =  "only screen and (min-width: 1201px)"


// @media mqSmartphone
    // Styles go here

// @media mqTablet
    // Styles go here


// --------------------------------------------------------------------------
// @media only screen and (min-width: 320px) and (max-width: 480px)
// @media only screen and (min-width: 481px) and (max-width: 768px)
// @media only screen and (min-width: 769px) and (max-width: 1024px)
// @media only screen and (min-width: 1025px) and (max-width: 1200px)
// @media only screen and (min-width: 1201px) and up
// --------------------------------------------------------------------------

// --------------------------------------------------------------------------
// 320px — 480px: Mobile devices
// 481px — 768px: iPads, Tablets
// 769px — 1024px: Small screens, laptops
// 1025px — 1200px: Desktops, large screens
// 1201px and more —  Extra large screens, TV
// --------------------------------------------------------------------------


////////////////////////////////////////
// Media query - new mode-1
////////////////////////////////////////