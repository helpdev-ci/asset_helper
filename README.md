# asset_helper
// Load a css file from the main asset css folder
css_asset('filename.css');

// Load a image from the modulename. Images has a 3rd optional param for attributes
image_asset('filename.jpg', 'modulename', array('alt'=>'Image name!', 'width'=>50));

// Load a javascript from the main folder, BUT we only want the url and not the entire HTML tag.
js_asset_url('filename.js', 'modulename');

// Want something other than a image, css or js?
// The third param here tells us what the type is, typename being the folder its kept in.
other_asset_url('banner.swf', '', 'flash');
