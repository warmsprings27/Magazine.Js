# Magazine.Js
This is online website for viewing a magazine. Built with HTML 5 with lots of interesting feature.

Magazine.js is a website that adds a beautiful transition similar to real pages in a book or magazine. It works in all modern browsers including touch devices.

What's in this?

New addPage for creating pages dynamically.

New display for single and double pages.

Gradients for non-webkit browsers.

Usage

CSS code:

#magazine{
    width: 800px;
    height: 400px;
}
#magazine .turn-page{
    background-color:#ccc;
}
HTML code:

<div id="magazine">
    <div><span class="text">Page 1</span></div>
    <div><span class="text">Page 2</span></div>
    <div><span class="text">Page 3</span></div>
</div>
JavaScript code:

$('#magazine').turn({gradients: true, acceleration: true});
Requirements

jQuery 1.7 or later

Browser support

Chrome 12, Safari 5, Firefox 10, IE 9
