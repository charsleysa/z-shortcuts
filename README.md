z-shortcuts
===============

Z Shortcuts enable the ability to bind to shortcuts entered from the keyboard
Available for both Zero and Zepto

Usage: $(\<identifier\>).shortcut(\<shortcut\>, \<function\>)

Example usage:

$(document).shortcut("ctrl+shift+x", function(){
    alert("ctrl+shift+x was pressed");
});
