(window["canvasWebpackJsonp"]=window["canvasWebpackJsonp"]||[]).push([[4],{"+mmM":function(e,t,r){"use strict"
var n=r("TqRt")
Object.defineProperty(t,"__esModule",{value:true})
t.default=i
var a=n(r("sk10"))
function i(e){var t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:[]
if(e&&e.type){var r=t.map(function(e){return(0,a.default)(e)})
return r.indexOf((0,a.default)(e.type))>=0}return false}},"24wD":function(e,t,r){"use strict"
var n=r("TqRt")
Object.defineProperty(t,"__esModule",{value:true})
t.default=o
var a=n(r("KB5V"))
var i=n(r("fsaM"))
function o(e){var t=e&&(0,a.default)(e)
return t&&(0,i.default)()===t}},"3zPy":function(e,t){function r(e){if(e&&"object"===typeof e){var t=e.which||e.keyCode||e.charCode
t&&(e=t)}if("number"===typeof e)return o[e]
var r=String(e)
var i=n[r.toLowerCase()]
if(i)return i
i=a[r.toLowerCase()]
if(i)return i
if(1===r.length)return r.charCodeAt(0)
return}r.isEventKey=function(e,t){if(e&&"object"===typeof e){var r=e.which||e.keyCode||e.charCode
if(null===r||void 0===r)return false
if("string"===typeof t){var i=n[t.toLowerCase()]
if(i)return i===r
i=a[t.toLowerCase()]
if(i)return i===r}else if("number"===typeof t)return t===r
return false}}
t=e.exports=r
var n=t.code=t.codes={backspace:8,tab:9,enter:13,shift:16,ctrl:17,alt:18,"pause/break":19,"caps lock":20,esc:27,space:32,"page up":33,"page down":34,end:35,home:36,left:37,up:38,right:39,down:40,insert:45,delete:46,command:91,"left command":91,"right command":93,"numpad *":106,"numpad +":107,"numpad -":109,"numpad .":110,"numpad /":111,"num lock":144,"scroll lock":145,"my computer":182,"my calculator":183,";":186,"=":187,",":188,"-":189,".":190,"/":191,"`":192,"[":219,"\\":220,"]":221,"'":222}
var a=t.aliases={windows:91,"⇧":16,"⌥":18,"⌃":17,"⌘":91,ctl:17,control:17,option:18,pause:19,break:19,caps:20,return:13,escape:27,spc:32,spacebar:32,pgup:33,pgdn:34,ins:45,del:46,cmd:91}
for(i=97;i<123;i++)n[String.fromCharCode(i)]=i-32
for(var i=48;i<58;i++)n[i-48]=i
for(i=1;i<13;i++)n["f"+i]=i+111
for(i=0;i<10;i++)n["numpad "+i]=i+96
var o=t.names=t.title={}
for(i in n)o[n[i]]=i
for(var s in a)n[s]=a[s]},"8OQS":function(e,t){function r(e,t){if(null==e)return{}
var r={}
var n=Object.keys(e)
var a,i
for(i=0;i<n.length;i++){a=n[i]
if(t.indexOf(a)>=0)continue
r[a]=e[a]}return r}e.exports=r},QILm:function(e,t,r){var n=r("8OQS")
function a(e,t){if(null==e)return{}
var r=n(e,t)
var a,i
if(Object.getOwnPropertySymbols){var o=Object.getOwnPropertySymbols(e)
for(i=0;i<o.length;i++){a=o[i]
if(t.indexOf(a)>=0)continue
if(!Object.prototype.propertyIsEnumerable.call(e,a))continue
r[a]=e[a]}}return r}e.exports=a},VaOI:function(e,t,r){"use strict"
var n=r("TqRt")
Object.defineProperty(t,"__esModule",{value:true})
t.default=s
var a=n(r("q1tI"))
var i=n(r("+mmM"))
var o=n(r("qnOc"))
function s(e){var t=false
a.default.Children.forEach(e,function(e){e&&!(0,i.default)(e,[o.default])&&(t=true)})
return t}},Z8qc:function(e,t,r){"use strict"
Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(){return{sizeXSmall:"1.125rem",sizeSmall:"2rem",sizeMedium:"3rem",sizeLarge:"5rem",sizeXLarge:"10rem"}}},Zss7:function(e,t,r){var n;(function(a){var i=/^\s+/,o=/\s+$/,s=0,l=a.round,f=a.min,u=a.max,c=a.random
function d(e,t){e=e||""
t=t||{}
if(e instanceof d)return e
if(!(this instanceof d))return new d(e,t)
var r=h(e)
this._originalInput=e,this._r=r.r,this._g=r.g,this._b=r.b,this._a=r.a,this._roundA=l(100*this._a)/100,this._format=t.format||r.format
this._gradientType=t.gradientType
this._r<1&&(this._r=l(this._r))
this._g<1&&(this._g=l(this._g))
this._b<1&&(this._b=l(this._b))
this._ok=r.ok
this._tc_id=s++}d.prototype={isDark:function(){return this.getBrightness()<128},isLight:function(){return!this.isDark()},isValid:function(){return this._ok},getOriginalInput:function(){return this._originalInput},getFormat:function(){return this._format},getAlpha:function(){return this._a},getBrightness:function(){var e=this.toRgb()
return(299*e.r+587*e.g+114*e.b)/1e3},getLuminance:function(){var e=this.toRgb()
var t,r,n,i,o,s
t=e.r/255
r=e.g/255
n=e.b/255
i=t<=.03928?t/12.92:a.pow((t+.055)/1.055,2.4)
o=r<=.03928?r/12.92:a.pow((r+.055)/1.055,2.4)
s=n<=.03928?n/12.92:a.pow((n+.055)/1.055,2.4)
return.2126*i+.7152*o+.0722*s},setAlpha:function(e){this._a=P(e)
this._roundA=l(100*this._a)/100
return this},toHsv:function(){var e=p(this._r,this._g,this._b)
return{h:360*e.h,s:e.s,v:e.v,a:this._a}},toHsvString:function(){var e=p(this._r,this._g,this._b)
var t=l(360*e.h),r=l(100*e.s),n=l(100*e.v)
return 1==this._a?"hsv("+t+", "+r+"%, "+n+"%)":"hsva("+t+", "+r+"%, "+n+"%, "+this._roundA+")"},toHsl:function(){var e=g(this._r,this._g,this._b)
return{h:360*e.h,s:e.s,l:e.l,a:this._a}},toHslString:function(){var e=g(this._r,this._g,this._b)
var t=l(360*e.h),r=l(100*e.s),n=l(100*e.l)
return 1==this._a?"hsl("+t+", "+r+"%, "+n+"%)":"hsla("+t+", "+r+"%, "+n+"%, "+this._roundA+")"},toHex:function(e){return _(this._r,this._g,this._b,e)},toHexString:function(e){return"#"+this.toHex(e)},toHex8:function(e){return y(this._r,this._g,this._b,this._a,e)},toHex8String:function(e){return"#"+this.toHex8(e)},toRgb:function(){return{r:l(this._r),g:l(this._g),b:l(this._b),a:this._a}},toRgbString:function(){return 1==this._a?"rgb("+l(this._r)+", "+l(this._g)+", "+l(this._b)+")":"rgba("+l(this._r)+", "+l(this._g)+", "+l(this._b)+", "+this._roundA+")"},toPercentageRgb:function(){return{r:l(100*j(this._r,255))+"%",g:l(100*j(this._g,255))+"%",b:l(100*j(this._b,255))+"%",a:this._a}},toPercentageRgbString:function(){return 1==this._a?"rgb("+l(100*j(this._r,255))+"%, "+l(100*j(this._g,255))+"%, "+l(100*j(this._b,255))+"%)":"rgba("+l(100*j(this._r,255))+"%, "+l(100*j(this._g,255))+"%, "+l(100*j(this._b,255))+"%, "+this._roundA+")"},toName:function(){if(0===this._a)return"transparent"
if(this._a<1)return false
return K[_(this._r,this._g,this._b,true)]||false},toFilter:function(e){var t="#"+k(this._r,this._g,this._b,this._a)
var r=t
var n=this._gradientType?"GradientType = 1, ":""
if(e){var a=d(e)
r="#"+k(a._r,a._g,a._b,a._a)}return"progid:DXImageTransform.Microsoft.gradient("+n+"startColorstr="+t+",endColorstr="+r+")"},toString:function(e){var t=!!e
e=e||this._format
var r=false
var n=this._a<1&&this._a>=0
var a=!t&&n&&("hex"===e||"hex6"===e||"hex3"===e||"hex4"===e||"hex8"===e||"name"===e)
if(a){if("name"===e&&0===this._a)return this.toName()
return this.toRgbString()}"rgb"===e&&(r=this.toRgbString())
"prgb"===e&&(r=this.toPercentageRgbString())
"hex"!==e&&"hex6"!==e||(r=this.toHexString())
"hex3"===e&&(r=this.toHexString(true))
"hex4"===e&&(r=this.toHex8String(true))
"hex8"===e&&(r=this.toHex8String())
"name"===e&&(r=this.toName())
"hsl"===e&&(r=this.toHslString())
"hsv"===e&&(r=this.toHsvString())
return r||this.toHexString()},clone:function(){return d(this.toString())},_applyModification:function(e,t){var r=e.apply(null,[this].concat([].slice.call(t)))
this._r=r._r
this._g=r._g
this._b=r._b
this.setAlpha(r._a)
return this},lighten:function(){return this._applyModification(S,arguments)},brighten:function(){return this._applyModification(C,arguments)},darken:function(){return this._applyModification(H,arguments)},desaturate:function(){return this._applyModification(x,arguments)},saturate:function(){return this._applyModification(w,arguments)},greyscale:function(){return this._applyModification(A,arguments)},spin:function(){return this._applyModification(T,arguments)},_applyCombination:function(e,t){return e.apply(null,[this].concat([].slice.call(t)))},analogous:function(){return this._applyCombination(z,arguments)},complement:function(){return this._applyCombination(J,arguments)},monochromatic:function(){return this._applyCombination(M,arguments)},splitcomplement:function(){return this._applyCombination(I,arguments)},triad:function(){return this._applyCombination(R,arguments)},tetrad:function(){return this._applyCombination(O,arguments)}}
d.fromRatio=function(e,t){if("object"==typeof e){var r={}
for(var n in e)e.hasOwnProperty(n)&&(r[n]="a"===n?e[n]:V(e[n]))
e=r}return d(e,t)}
function h(e){var t={r:0,g:0,b:0}
var r=1
var n=null
var a=null
var i=null
var o=false
var s=false
"string"==typeof e&&(e=te(e))
if("object"==typeof e){if(ee(e.r)&&ee(e.g)&&ee(e.b)){t=b(e.r,e.g,e.b)
o=true
s="%"===String(e.r).substr(-1)?"prgb":"rgb"}else if(ee(e.h)&&ee(e.s)&&ee(e.v)){n=V(e.s)
a=V(e.v)
t=m(e.h,n,a)
o=true
s="hsv"}else if(ee(e.h)&&ee(e.s)&&ee(e.l)){n=V(e.s)
i=V(e.l)
t=v(e.h,n,i)
o=true
s="hsl"}e.hasOwnProperty("a")&&(r=e.a)}r=P(r)
return{ok:o,format:e.format||s,r:f(255,u(t.r,0)),g:f(255,u(t.g,0)),b:f(255,u(t.b,0)),a:r}}function b(e,t,r){return{r:255*j(e,255),g:255*j(t,255),b:255*j(r,255)}}function g(e,t,r){e=j(e,255)
t=j(t,255)
r=j(r,255)
var n=u(e,t,r),a=f(e,t,r)
var i,o,s=(n+a)/2
if(n==a)i=o=0
else{var l=n-a
o=s>.5?l/(2-n-a):l/(n+a)
switch(n){case e:i=(t-r)/l+(t<r?6:0)
break
case t:i=(r-e)/l+2
break
case r:i=(e-t)/l+4}i/=6}return{h:i,s:o,l:s}}function v(e,t,r){var n,a,i
e=j(e,360)
t=j(t,100)
r=j(r,100)
function o(e,t,r){r<0&&(r+=1)
r>1&&(r-=1)
if(r<1/6)return e+6*(t-e)*r
if(r<.5)return t
if(r<2/3)return e+(t-e)*(2/3-r)*6
return e}if(0===t)n=a=i=r
else{var s=r<.5?r*(1+t):r+t-r*t
var l=2*r-s
n=o(l,s,e+1/3)
a=o(l,s,e)
i=o(l,s,e-1/3)}return{r:255*n,g:255*a,b:255*i}}function p(e,t,r){e=j(e,255)
t=j(t,255)
r=j(r,255)
var n=u(e,t,r),a=f(e,t,r)
var i,o,s=n
var l=n-a
o=0===n?0:l/n
if(n==a)i=0
else{switch(n){case e:i=(t-r)/l+(t<r?6:0)
break
case t:i=(r-e)/l+2
break
case r:i=(e-t)/l+4}i/=6}return{h:i,s:o,v:s}}function m(e,t,r){e=6*j(e,360)
t=j(t,100)
r=j(r,100)
var n=a.floor(e),i=e-n,o=r*(1-t),s=r*(1-i*t),l=r*(1-(1-i)*t),f=n%6,u=[r,s,o,o,l,r][f],c=[l,r,r,s,o,o][f],d=[o,o,l,r,r,s][f]
return{r:255*u,g:255*c,b:255*d}}function _(e,t,r,n){var a=[D(l(e).toString(16)),D(l(t).toString(16)),D(l(r).toString(16))]
if(n&&a[0].charAt(0)==a[0].charAt(1)&&a[1].charAt(0)==a[1].charAt(1)&&a[2].charAt(0)==a[2].charAt(1))return a[0].charAt(0)+a[1].charAt(0)+a[2].charAt(0)
return a.join("")}function y(e,t,r,n,a){var i=[D(l(e).toString(16)),D(l(t).toString(16)),D(l(r).toString(16)),D(G(n))]
if(a&&i[0].charAt(0)==i[0].charAt(1)&&i[1].charAt(0)==i[1].charAt(1)&&i[2].charAt(0)==i[2].charAt(1)&&i[3].charAt(0)==i[3].charAt(1))return i[0].charAt(0)+i[1].charAt(0)+i[2].charAt(0)+i[3].charAt(0)
return i.join("")}function k(e,t,r,n){var a=[D(G(n)),D(l(e).toString(16)),D(l(t).toString(16)),D(l(r).toString(16))]
return a.join("")}d.equals=function(e,t){if(!e||!t)return false
return d(e).toRgbString()==d(t).toRgbString()}
d.random=function(){return d.fromRatio({r:c(),g:c(),b:c()})}
function x(e,t){t=0===t?0:t||10
var r=d(e).toHsl()
r.s-=t/100
r.s=q(r.s)
return d(r)}function w(e,t){t=0===t?0:t||10
var r=d(e).toHsl()
r.s+=t/100
r.s=q(r.s)
return d(r)}function A(e){return d(e).desaturate(100)}function S(e,t){t=0===t?0:t||10
var r=d(e).toHsl()
r.l+=t/100
r.l=q(r.l)
return d(r)}function C(e,t){t=0===t?0:t||10
var r=d(e).toRgb()
r.r=u(0,f(255,r.r-l(-t/100*255)))
r.g=u(0,f(255,r.g-l(-t/100*255)))
r.b=u(0,f(255,r.b-l(-t/100*255)))
return d(r)}function H(e,t){t=0===t?0:t||10
var r=d(e).toHsl()
r.l-=t/100
r.l=q(r.l)
return d(r)}function T(e,t){var r=d(e).toHsl()
var n=(r.h+t)%360
r.h=n<0?360+n:n
return d(r)}function J(e){var t=d(e).toHsl()
t.h=(t.h+180)%360
return d(t)}function R(e){var t=d(e).toHsl()
var r=t.h
return[d(e),d({h:(r+120)%360,s:t.s,l:t.l}),d({h:(r+240)%360,s:t.s,l:t.l})]}function O(e){var t=d(e).toHsl()
var r=t.h
return[d(e),d({h:(r+90)%360,s:t.s,l:t.l}),d({h:(r+180)%360,s:t.s,l:t.l}),d({h:(r+270)%360,s:t.s,l:t.l})]}function I(e){var t=d(e).toHsl()
var r=t.h
return[d(e),d({h:(r+72)%360,s:t.s,l:t.l}),d({h:(r+216)%360,s:t.s,l:t.l})]}function z(e,t,r){t=t||6
r=r||30
var n=d(e).toHsl()
var a=360/r
var i=[d(e)]
for(n.h=(n.h-(a*t>>1)+720)%360;--t;){n.h=(n.h+a)%360
i.push(d(n))}return i}function M(e,t){t=t||6
var r=d(e).toHsv()
var n=r.h,a=r.s,i=r.v
var o=[]
var s=1/t
while(t--){o.push(d({h:n,s:a,v:i}))
i=(i+s)%1}return o}d.mix=function(e,t,r){r=0===r?0:r||50
var n=d(e).toRgb()
var a=d(t).toRgb()
var i=r/100
var o={r:(a.r-n.r)*i+n.r,g:(a.g-n.g)*i+n.g,b:(a.b-n.b)*i+n.b,a:(a.a-n.a)*i+n.a}
return d(o)}
d.readability=function(e,t){var r=d(e)
var n=d(t)
return(a.max(r.getLuminance(),n.getLuminance())+.05)/(a.min(r.getLuminance(),n.getLuminance())+.05)}
d.isReadable=function(e,t,r){var n=d.readability(e,t)
var a,i
i=false
a=re(r)
switch(a.level+a.size){case"AAsmall":case"AAAlarge":i=n>=4.5
break
case"AAlarge":i=n>=3
break
case"AAAsmall":i=n>=7}return i}
d.mostReadable=function(e,t,r){var n=null
var a=0
var i
var o,s,l
r=r||{}
o=r.includeFallbackColors
s=r.level
l=r.size
for(var f=0;f<t.length;f++){i=d.readability(e,t[f])
if(i>a){a=i
n=d(t[f])}}if(d.isReadable(e,n,{level:s,size:l})||!o)return n
r.includeFallbackColors=false
return d.mostReadable(e,["#fff","#000"],r)}
var F=d.names={aliceblue:"f0f8ff",antiquewhite:"faebd7",aqua:"0ff",aquamarine:"7fffd4",azure:"f0ffff",beige:"f5f5dc",bisque:"ffe4c4",black:"000",blanchedalmond:"ffebcd",blue:"00f",blueviolet:"8a2be2",brown:"a52a2a",burlywood:"deb887",burntsienna:"ea7e5d",cadetblue:"5f9ea0",chartreuse:"7fff00",chocolate:"d2691e",coral:"ff7f50",cornflowerblue:"6495ed",cornsilk:"fff8dc",crimson:"dc143c",cyan:"0ff",darkblue:"00008b",darkcyan:"008b8b",darkgoldenrod:"b8860b",darkgray:"a9a9a9",darkgreen:"006400",darkgrey:"a9a9a9",darkkhaki:"bdb76b",darkmagenta:"8b008b",darkolivegreen:"556b2f",darkorange:"ff8c00",darkorchid:"9932cc",darkred:"8b0000",darksalmon:"e9967a",darkseagreen:"8fbc8f",darkslateblue:"483d8b",darkslategray:"2f4f4f",darkslategrey:"2f4f4f",darkturquoise:"00ced1",darkviolet:"9400d3",deeppink:"ff1493",deepskyblue:"00bfff",dimgray:"696969",dimgrey:"696969",dodgerblue:"1e90ff",firebrick:"b22222",floralwhite:"fffaf0",forestgreen:"228b22",fuchsia:"f0f",gainsboro:"dcdcdc",ghostwhite:"f8f8ff",gold:"ffd700",goldenrod:"daa520",gray:"808080",green:"008000",greenyellow:"adff2f",grey:"808080",honeydew:"f0fff0",hotpink:"ff69b4",indianred:"cd5c5c",indigo:"4b0082",ivory:"fffff0",khaki:"f0e68c",lavender:"e6e6fa",lavenderblush:"fff0f5",lawngreen:"7cfc00",lemonchiffon:"fffacd",lightblue:"add8e6",lightcoral:"f08080",lightcyan:"e0ffff",lightgoldenrodyellow:"fafad2",lightgray:"d3d3d3",lightgreen:"90ee90",lightgrey:"d3d3d3",lightpink:"ffb6c1",lightsalmon:"ffa07a",lightseagreen:"20b2aa",lightskyblue:"87cefa",lightslategray:"789",lightslategrey:"789",lightsteelblue:"b0c4de",lightyellow:"ffffe0",lime:"0f0",limegreen:"32cd32",linen:"faf0e6",magenta:"f0f",maroon:"800000",mediumaquamarine:"66cdaa",mediumblue:"0000cd",mediumorchid:"ba55d3",mediumpurple:"9370db",mediumseagreen:"3cb371",mediumslateblue:"7b68ee",mediumspringgreen:"00fa9a",mediumturquoise:"48d1cc",mediumvioletred:"c71585",midnightblue:"191970",mintcream:"f5fffa",mistyrose:"ffe4e1",moccasin:"ffe4b5",navajowhite:"ffdead",navy:"000080",oldlace:"fdf5e6",olive:"808000",olivedrab:"6b8e23",orange:"ffa500",orangered:"ff4500",orchid:"da70d6",palegoldenrod:"eee8aa",palegreen:"98fb98",paleturquoise:"afeeee",palevioletred:"db7093",papayawhip:"ffefd5",peachpuff:"ffdab9",peru:"cd853f",pink:"ffc0cb",plum:"dda0dd",powderblue:"b0e0e6",purple:"800080",rebeccapurple:"663399",red:"f00",rosybrown:"bc8f8f",royalblue:"4169e1",saddlebrown:"8b4513",salmon:"fa8072",sandybrown:"f4a460",seagreen:"2e8b57",seashell:"fff5ee",sienna:"a0522d",silver:"c0c0c0",skyblue:"87ceeb",slateblue:"6a5acd",slategray:"708090",slategrey:"708090",snow:"fffafa",springgreen:"00ff7f",steelblue:"4682b4",tan:"d2b48c",teal:"008080",thistle:"d8bfd8",tomato:"ff6347",turquoise:"40e0d0",violet:"ee82ee",wheat:"f5deb3",white:"fff",whitesmoke:"f5f5f5",yellow:"ff0",yellowgreen:"9acd32"}
var K=d.hexNames=N(F)
function N(e){var t={}
for(var r in e)e.hasOwnProperty(r)&&(t[e[r]]=r)
return t}function P(e){e=parseFloat(e);(isNaN(e)||e<0||e>1)&&(e=1)
return e}function j(e,t){E(e)&&(e="100%")
var r=B(e)
e=f(t,u(0,parseFloat(e)))
r&&(e=parseInt(e*t,10)/100)
if(a.abs(e-t)<1e-6)return 1
return e%t/parseFloat(t)}function q(e){return f(1,u(0,e))}function L(e){return parseInt(e,16)}function E(e){return"string"==typeof e&&-1!=e.indexOf(".")&&1===parseFloat(e)}function B(e){return"string"===typeof e&&-1!=e.indexOf("%")}function D(e){return 1==e.length?"0"+e:""+e}function V(e){e<=1&&(e=100*e+"%")
return e}function G(e){return a.round(255*parseFloat(e)).toString(16)}function X(e){return L(e)/255}var Z=(Q="[-\\+]?\\d+%?",W="[-\\+]?\\d*\\.\\d+%?",U="(?:"+W+")|(?:"+Q+")",Y="[\\s|\\(]+("+U+")[,|\\s]+("+U+")[,|\\s]+("+U+")\\s*\\)?",$="[\\s|\\(]+("+U+")[,|\\s]+("+U+")[,|\\s]+("+U+")[,|\\s]+("+U+")\\s*\\)?",{CSS_UNIT:new RegExp(U),rgb:new RegExp("rgb"+Y),rgba:new RegExp("rgba"+$),hsl:new RegExp("hsl"+Y),hsla:new RegExp("hsla"+$),hsv:new RegExp("hsv"+Y),hsva:new RegExp("hsva"+$),hex3:/^#?([0-9a-fA-F]{1})([0-9a-fA-F]{1})([0-9a-fA-F]{1})$/,hex6:/^#?([0-9a-fA-F]{2})([0-9a-fA-F]{2})([0-9a-fA-F]{2})$/,hex4:/^#?([0-9a-fA-F]{1})([0-9a-fA-F]{1})([0-9a-fA-F]{1})([0-9a-fA-F]{1})$/,hex8:/^#?([0-9a-fA-F]{2})([0-9a-fA-F]{2})([0-9a-fA-F]{2})([0-9a-fA-F]{2})$/})
var Q,W,U,Y,$
function ee(e){return!!Z.CSS_UNIT.exec(e)}function te(e){e=e.replace(i,"").replace(o,"").toLowerCase()
var t=false
if(F[e]){e=F[e]
t=true}else if("transparent"==e)return{r:0,g:0,b:0,a:0,format:"name"}
var r
if(r=Z.rgb.exec(e))return{r:r[1],g:r[2],b:r[3]}
if(r=Z.rgba.exec(e))return{r:r[1],g:r[2],b:r[3],a:r[4]}
if(r=Z.hsl.exec(e))return{h:r[1],s:r[2],l:r[3]}
if(r=Z.hsla.exec(e))return{h:r[1],s:r[2],l:r[3],a:r[4]}
if(r=Z.hsv.exec(e))return{h:r[1],s:r[2],v:r[3]}
if(r=Z.hsva.exec(e))return{h:r[1],s:r[2],v:r[3],a:r[4]}
if(r=Z.hex8.exec(e))return{r:L(r[1]),g:L(r[2]),b:L(r[3]),a:X(r[4]),format:t?"name":"hex8"}
if(r=Z.hex6.exec(e))return{r:L(r[1]),g:L(r[2]),b:L(r[3]),format:t?"name":"hex"}
if(r=Z.hex4.exec(e))return{r:L(r[1]+""+r[1]),g:L(r[2]+""+r[2]),b:L(r[3]+""+r[3]),a:X(r[4]+""+r[4]),format:t?"name":"hex8"}
if(r=Z.hex3.exec(e))return{r:L(r[1]+""+r[1]),g:L(r[2]+""+r[2]),b:L(r[3]+""+r[3]),format:t?"name":"hex"}
return false}function re(e){var t,r
e=e||{level:"AA",size:"small"}
t=(e.level||"AA").toUpperCase()
r=(e.size||"small").toLowerCase()
"AA"!==t&&"AAA"!==t&&(t="AA")
"small"!==r&&"large"!==r&&(r="small")
return{level:t,size:r}}if(e.exports)e.exports=d
else{n=function(){return d}.call(t,r,t,e),void 0!==n&&(e.exports=n)}})(Math)},fsaM:function(e,t,r){"use strict"
Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e){try{return(e||document).activeElement}catch(e){}}},lfZU:function(e,t,r){"use strict"
Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e){var t=e.colors
return{primaryInverseColor:t.textLightest,primaryColor:t.textDarkest,secondaryColor:t.textDark,secondaryInverseColor:t.textLight,warningColor:t.textWarning,brandColor:t.textBrand,errorColor:t.textDanger,successColor:t.textSuccess}}n.canvas=function(e){return{primaryColor:e["ic-brand-font-color-dark"],brandColor:e["ic-brand-primary"]}}},q3EI:function(e,t,r){"use strict"
var n=r("TqRt")
var a=r("284h")
Object.defineProperty(t,"__esModule",{value:true})
t.default=void 0
var i=n(r("MVZn"))
var o=n(r("lSNA"))
var s=n(r("QILm"))
var l=n(r("lwsE"))
var f=n(r("W8MJ"))
var u=n(r("a1gu"))
var c=n(r("Nsbk"))
var d=n(r("7W2i"))
var h=a(r("q1tI"))
var b=n(r("17x9"))
var g=n(r("TSYQ"))
var v=n(r("J2CL"))
var p=n(r("ZJ40"))
var m=n(r("x6kn"))
var _=n(r("Zuoh"))
var y=n(r("Z8qc"))
var k,x,w,A,S,C
var H={componentId:"bHbtJ",template:function(e){return"\n\n.bHbtJ_bGBk{color:inherit;fill:currentColor;height:1em;line-height:1;vertical-align:middle;width:1em}\n\n.bHbtJ_cwgF{transform:rotate(90deg)}\n\n.bHbtJ_exaY{transform:rotate(180deg)}\n\n.bHbtJ_dTDN{transform:rotate(270deg)}\n\n[dir=rtl] .bHbtJ_owrh{transform:scaleX(-1)}\n\n[dir=rtl] .bHbtJ_owrh.bHbtJ_cwgF{transform:scaleX(-1) rotate(90deg)}\n\n[dir=rtl] .bHbtJ_owrh .bHbtJ_exaY{transform:scaleX(-1) rotate(180deg)}\n\n[dir=rtl] .bHbtJ_owrh .bHbtJ_dTDN{transform:scaleX(-1) rotate(270deg)}\n\n.bHbtJ_dIzR{font-size:".concat(e.sizeXSmall||"inherit","}\n\n.bHbtJ_VCXp{font-size:").concat(e.sizeSmall||"inherit","}\n\n.bHbtJ_fKcQ{font-size:").concat(e.sizeMedium||"inherit","}\n\n.bHbtJ_cnhd{font-size:").concat(e.sizeLarge||"inherit","}\n\n.bHbtJ_fWMB{font-size:").concat(e.sizeXLarge||"inherit","}")},root:"bHbtJ_bGBk","rotate--90":"bHbtJ_cwgF","rotate--180":"bHbtJ_exaY","rotate--270":"bHbtJ_dTDN",bidirectional:"bHbtJ_owrh","size--x-small":"bHbtJ_dIzR","size--small":"bHbtJ_VCXp","size--medium":"bHbtJ_fKcQ","size--large":"bHbtJ_cnhd","size--x-large":"bHbtJ_fWMB"}
var T=(k=(0,_.default)(),x=(0,v.default)(y.default,H),w=(0,p.default)("5.0.0",{width:"size",height:"size"}),k(A=x(A=w(A=(C=S=function(e){(0,d.default)(t,e)
function t(){(0,l.default)(this,t)
return(0,u.default)(this,(0,c.default)(t).apply(this,arguments))}(0,f.default)(t,[{key:"render",value:function(){var e
var t=this.props,r=t.rotate,n=t.className,a=t.size,i=t.bidirectional,l=(0,s.default)(t,["rotate","className","size","bidirectional"])
return h.default.createElement(m.default,Object.assign({},l,{rotate:r,className:(0,g.default)((e={},(0,o.default)(e,H.root,true),(0,o.default)(e,H["rotate--".concat(r)],r&&"0"!==r),(0,o.default)(e,H["size--".concat(a)],a),(0,o.default)(e,H.bidirectional,i),(0,o.default)(e,n,n),e))}))}}])
t.displayName="SVGIcon"
return t}(h.Component),S.propTypes=(0,i.default)({},m.default.propTypes,{width:b.default.oneOfType([b.default.string,b.default.number]),height:b.default.oneOfType([b.default.string,b.default.number]),rotate:b.default.oneOf(["0","90","180","270"]),size:b.default.oneOf(["x-small","small","medium","large","x-large"]),bidirectional:b.default.bool}),S.defaultProps={rotate:"0",bidirectional:false,width:void 0,height:void 0,size:void 0},C))||A)||A)||A)
var J=T
t.default=J},qnOc:function(e,t,r){"use strict"
var n=r("TqRt")
var a=r("284h")
Object.defineProperty(t,"__esModule",{value:true})
t.default=void 0
var i=n(r("MVZn"))
var o=n(r("lwsE"))
var s=n(r("W8MJ"))
var l=n(r("a1gu"))
var f=n(r("Nsbk"))
var u=n(r("7W2i"))
var c=a(r("q1tI"))
var d=n(r("17x9"))
var h=n(r("J2CL"))
var b=n(r("kibL"))
var g=r("2lwo")
var v,p,m,_
var y={componentId:"fdaJD",template:function(e){return"\n\n.fdaJD_bGBk{border:0;clip:rect(0 0 0 0);height:0.0625rem;inset-inline-start:0;margin:-0.0625rem;overflow:hidden;padding:0;position:absolute;top:0;width:0.0625rem}\n\n[dir=ltr] .fdaJD_bGBk{left:0}\n\n[dir=rtl] .fdaJD_bGBk{right:0}"},root:"fdaJD_bGBk"}
var k=(v=(0,h.default)(null,y),v(p=(_=m=function(e){(0,u.default)(t,e)
function t(){(0,o.default)(this,t)
return(0,l.default)(this,(0,f.default)(t).apply(this,arguments))}(0,s.default)(t,[{key:"render",value:function(){var e=(0,i.default)({},(0,g.omitProps)(this.props,t.propTypes),{className:y.root})
var r=(0,b.default)(t,this.props)
return c.default.createElement(r,e,this.props.children)}}])
t.displayName="ScreenReaderContent"
return t}(c.Component),m.propTypes={as:d.default.elementType,children:d.default.node},m.defaultProps={as:"span",children:null},_))||p)
var x=k
t.default=x},sk10:function(e,t,r){"use strict"
Object.defineProperty(t,"__esModule",{value:true})
t.default=n
function n(e){return"string"===typeof e?e:e.displayName||e.name}},"v+mX":function(e,t,r){"use strict"
var n=r("TqRt")
Object.defineProperty(t,"__esModule",{value:true})
t.alpha=i
t.darken=o
t.lighten=s
t.contrast=l
t.isValid=f
var a=n(r("Zss7"))
function i(e,t){return(0,a.default)(e).setAlpha(t/100).toRgbString()}function o(e,t){return(0,a.default)(e).darken(t).toRgbString()}function s(e,t){return(0,a.default)(e).lighten(t).toRgbString()}function l(e,t){return a.default.readability(e,t)}function f(e){return(0,a.default)(e).isValid()}},x6kn:function(e,t,r){"use strict"
var n=r("TqRt")
var a=r("284h")
Object.defineProperty(t,"__esModule",{value:true})
t.default=void 0
var i=n(r("lSNA"))
var o=n(r("MVZn"))
var s=n(r("QILm"))
var l=n(r("lwsE"))
var f=n(r("W8MJ"))
var u=n(r("a1gu"))
var c=n(r("Nsbk"))
var d=n(r("7W2i"))
var h=a(r("q1tI"))
var b=n(r("17x9"))
var g=n(r("TSYQ"))
var v=n(r("J2CL"))
var p=n(r("oxAU"))
var m=r("2lwo")
var _=n(r("Zuoh"))
var y=n(r("lfZU"))
var k,x,w,A,S
var C={componentId:"fTsnK",template:function(e){return"\n\n.fTsnK_bGBk{color:inherit;fill:currentColor}\n\n.fTsnK_eXrk{display:inline-block}\n\n.fTsnK_cRbP{display:block}\n\n.fTsnK_eCSh{color:".concat(e.primaryColor||"inherit","}\n\n.fTsnK_buuG{color:").concat(e.secondaryColor||"inherit","}\n\n.fTsnK_bFtJ{color:").concat(e.primaryInverseColor||"inherit","}\n\n.fTsnK_dsSB{color:").concat(e.secondaryInverseColor||"inherit","}\n\n.fTsnK_eZal{color:").concat(e.successColor||"inherit","}\n\n.fTsnK_cVUo{color:").concat(e.brandColor||"inherit","}\n\n.fTsnK_eScd{color:").concat(e.warningColor||"inherit","}\n\n.fTsnK_cpQl{color:").concat(e.errorColor||"inherit","}")},root:"fTsnK_bGBk",inline:"fTsnK_eXrk",block:"fTsnK_cRbP","color--primary":"fTsnK_eCSh","color--secondary":"fTsnK_buuG","color--primary-inverse":"fTsnK_bFtJ","color--secondary-inverse":"fTsnK_dsSB","color--success":"fTsnK_eZal","color--brand":"fTsnK_cVUo","color--warning":"fTsnK_eScd","color--error":"fTsnK_cpQl"}
var H=(k=(0,_.default)(),x=(0,v.default)(y.default,C),k(w=x(w=(S=A=function(e){(0,d.default)(t,e)
function t(){var e;(0,l.default)(this,t)
e=(0,u.default)(this,(0,c.default)(t).call(this))
e.titleId=(0,p.default)("InlineSVG-title")
e.descId=(0,p.default)("InlineSVG-desc")
return e}(0,f.default)(t,[{key:"renderTitle",value:function(){var e=this.props.title
return e?h.default.createElement("title",{id:this.titleId},e):null}},{key:"renderDesc",value:function(e){return e?h.default.createElement("desc",{id:this.descId},e):null}},{key:"renderContent",value:function(){if(this.props.src){var e=t.prepareSrc(this.props.src)
return h.default.createElement("g",{role:"presentation",dangerouslySetInnerHTML:{__html:e}})}return h.default.createElement("g",{role:"presentation"},this.props.children)}},{key:"render",value:function(){var e
var r=this.props,n=r.style,a=r.width,l=r.height,f=r.title,u=r.description,c=r.focusable,d=(r.children,r.src,r.color),b=(0,s.default)(r,["style","width","height","title","description","focusable","children","src","color"])
return h.default.createElement("svg",Object.assign({},T(this.props.src),(0,m.omitProps)(this.props,t.propTypes,["inline"]),{style:(0,o.default)({},n,{width:a,height:l}),width:a||"1em",height:l||"1em","aria-hidden":f?null:"true","aria-labelledby":this.labelledBy,role:this.role,focusable:c?"true":"false",className:(0,g.default)((e={},(0,i.default)(e,C.root,true),(0,i.default)(e,C.inline,this.props.inline),(0,i.default)(e,C.block,!this.props.inline),(0,i.default)(e,b.className,b.className),(0,i.default)(e,C["color--".concat(d)],"inherit"!==d),e))}),this.renderTitle(),this.renderDesc(u),this.renderContent())}},{key:"role",get:function(){return this.props.title?"img":"presentation"}},{key:"labelledBy",get:function(){var e=[]
this.props.title&&e.push(this.titleId)
this.props.description&&e.push(this.descId)
return e.length>0?e.join(" "):null}}])
t.displayName="InlineSVG"
return t}(h.Component),A.propTypes={children:b.default.node,src:b.default.string,title:b.default.string,description:b.default.string,focusable:b.default.bool,width:b.default.oneOfType([b.default.string,b.default.number]),height:b.default.oneOfType([b.default.string,b.default.number]),inline:b.default.bool,color:b.default.oneOf(["inherit","primary","secondary","primary-inverse","secondary-inverse","success","error","warning","brand"])},A.defaultProps={focusable:false,src:"",title:"",description:"",inline:true,children:null,width:void 0,height:void 0,color:"inherit"},A.prepareSrc=function(e){var t=/<svg[^>]*>((.|[\n\r])*)<\/svg>/
var r=t.exec(e)
return r?r[1]:e},S))||w)||w)
t.default=H
function T(e){var t={}
var r=/<svg\s+([^>]*)\s*>/
var n=/(\S+)=["']?((?:.(?!["']?\s+(?:\S+)=|[>"']))+.)["']?/g
if("string"===typeof e){var a=r.exec(e)
var i=a?a[1]:""
var o=["xmlns","xmlns:xlink","version"]
var s=n.exec(i)
while(null!=s){-1===o.indexOf(s[1])&&(t[s[1]]=s[2]||(s[3]?s[3]:s[4]?s[4]:s[5])||s[1])
s=n.exec(i)}}return t}}}])

//# sourceMappingURL=4-c-0de4e47220.js.map