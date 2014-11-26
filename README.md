Format
======
/**
 * @param {Integer|String} c If set to 0 or a string replace the current block 
 *     with c in the playing field array, otherwise check for collision
 * @return {Integer} returns 1 if a collision is detected and 'undefined' otherwise
 */

String.prototype.trim = function(e) {
    if(e === true){        
        return this.replace(/\s/g,'');
    } else {
        return this.replace(/(^\s*)|(\s*$)/g,'');
    }
}

var html = 
      '<div class="control">'
    + '  <ul>'
    + '    <li class="cur"></li>'
    + '    <li></li>'
    + '  </ul>'
    + '</div>'
    ;
;
