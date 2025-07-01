(window["canvasWebpackJsonp"]=window["canvasWebpackJsonp"]||[]).push([[10],{"4tjX":function(t,e,n){"use strict"
var r=n("TqRt")
var a=n("284h")
Object.defineProperty(e,"__esModule",{value:true})
e.PositionContent=e.PositionTarget=e.default=void 0
var i=r(n("lSNA"))
var o=r(n("MVZn"))
var l=r(n("W8MJ"))
var s=r(n("lwsE"))
var f=r(n("a1gu"))
var u=r(n("Nsbk"))
var c=r(n("7W2i"))
var h=a(n("q1tI"))
var d=r(n("17x9"))
var p=r(n("TSYQ"))
var m=r(n("J2CL"))
var v=n("IzEL")
var g=a(n("q9F9"))
var b=r(n("4hSX"))
var y=r(n("lS51"))
var x=r(n("oxAU"))
var _=r(n("xdG6"))
var w=r(n("eHUd"))
var j=r(n("EbHj"))
var k=r(n("KB5V"))
var D=r(n("Zuoh"))
var T=r(n("K/zI"))
var P=r(n("DfZk"))
var O=r(n("8dII"))
var M=r(n("uwQ2"))
var q,S,A,E,N,R,z,H,L,I,W,X,C
var V={componentId:"bgLNT",template:function(t){return"\n\n.bgLNT_bGBk{box-sizing:border-box;z-index:".concat(t.zIndex||"inherit","}")},root:"bgLNT_bGBk"}
var B=(q=(0,D.default)(),q(S=(E=A=function(t){(0,c.default)(e,t)
function e(){(0,s.default)(this,e)
return(0,f.default)(this,(0,u.default)(e).apply(this,arguments))}return e}(g.default),A.displayName="PositionTarget",A.locatorAttribute="data-position-target",E))||S)
e.PositionTarget=B
var Q=(N=(0,D.default)(),N(R=(H=z=function(t){(0,c.default)(e,t)
function e(){(0,s.default)(this,e)
return(0,f.default)(this,(0,u.default)(e).apply(this,arguments))}return e}(g.default),z.displayName="PositionContent",z.propTypes={children:d.default.node,placement:O.default.placement},z.locatorAttribute="data-position-content",H))||R)
e.PositionContent=Q
var J=(L=(0,D.default)(),I=(0,m.default)(M.default,V),L(W=I(W=(C=X=function(t){(0,c.default)(e,t)
function e(t){var n;(0,s.default)(this,e)
n=(0,f.default)(this,(0,u.default)(e).call(this,t))
n._timeouts=[]
n.handlePortalOpen=function(){n.position()
n.props.trackPosition&&n.startTracking()
n._timeouts.push(setTimeout(function(){n.state.positioned&&"function"===typeof n.props.onPositioned&&n.props.onPositioned({top:n.state.style.top,left:n.state.style.left,placement:n.state.placement})},0))}
n.position=function(){n.setState((0,o.default)({positioned:true},n.calculatePosition(n.props)))}
n.state=(0,o.default)({positioned:false},n.calculatePosition(t))
n.position=(0,w.default)(n.position,0,{leading:false,trailing:true})
n._id=n.props.id||(0,x.default)("Position")
return n}(0,l.default)(e,[{key:"shouldComponentUpdate",value:function(t,e,n){return!(0,j.default)(this.state,e)||!(0,_.default)(this.props,t)||!(0,_.default)(this.context,n)}},{key:"componentDidMount",value:function(){this.toggleLocatorAttributes(true)}},{key:"componentDidUpdate",value:function(t,e){this.position()
this.toggleLocatorAttributes(true)
this.props.trackPosition!==t.trackPosition&&(this.props.trackPosition?this.startTracking():this.stopTracking())
var n=this.state,r=n.style,a=n.placement
r&&e.style&&(a!==e.placement||r.top!==e.style.top||r.left!==e.style.left)&&this.props.onPositionChanged({top:r.top,left:r.left,placement:a})}},{key:"componentWillUnmount",value:function(){this.position.cancel()
this.stopTracking()
this._timeouts.forEach(function(t){return clearTimeout(t)})
this.toggleLocatorAttributes(false)}},{key:"toggleLocatorAttributes",value:function(t){this.toggleLocatorAttribute((0,k.default)(this._content),Q.locatorAttribute,t)
this.toggleLocatorAttribute((0,k.default)(this._target),B.locatorAttribute,t)}},{key:"toggleLocatorAttribute",value:function(t,e,n){if(t&&t.hasAttribute){n&&!t.hasAttribute(e)&&t.setAttribute(e,this._id)
!n&&t.hasAttribute(e)&&t.removeAttribute(e)}}},{key:"calculatePosition",value:function(t){return(0,P.default)(this._content,this._target,{placement:t.placement,offsetX:t.offsetX,offsetY:t.offsetY,constrain:t.constrain,container:t.mountNode,over:t.over})}},{key:"startTracking",value:function(){this._listener=this._listener||(0,y.default)(this._target,this.position)}},{key:"stopTracking",value:function(){if(this._listener){this._listener.remove()
this._listener=null}}},{key:"renderContent",value:function(){var t=this
var n=(0,g.pick)(e.Content,this.props.children)
if(n&&h.default.Children.count(n.props.children)>0){var r
n=(0,b.default)(n,(0,i.default)({ref:function(e){t._content=e},style:(0,o.default)({},n.props.style,this.state.style),className:(0,p.default)((r={},(0,i.default)(r,V.root,true),(0,i.default)(r,n.props.className,n.props.className),r))},Q.locatorAttribute,this._id))
n=h.default.createElement(T.default,{open:true,onOpen:this.handlePortalOpen,mountNode:this.props.mountNode,insertAt:this.props.insertAt},n)}return n}},{key:"renderTarget",value:function(){var t=this
var n=(0,g.pick)(e.Target,this.props.children)
if(n)return(0,b.default)(n,{ref:function(e){t._target=e}})
if(!this.props.target)return null
this._target="function"===typeof this.props.target?this.props.target():this.props.target}},{key:"render",value:function(){var t=(0,i.default)({},e.locatorAttribute,this._id)
return h.default.createElement("span",t,this.renderTarget(),this.renderContent())}}])
e.displayName="Position"
return e}(h.Component),X.Target=B,X.Content=Q,X.locatorAttribute="data-position",X.propTypes={children:d.default.node,target:d.default.oneOfType([v.element,d.default.func]),over:d.default.bool,placement:O.default.placement,offsetX:d.default.oneOfType([d.default.string,d.default.number]),offsetY:d.default.oneOfType([d.default.string,d.default.number]),onPositionChanged:d.default.func,onPositioned:d.default.func,trackPosition:d.default.bool,mountNode:O.default.mountNode,insertAt:d.default.oneOf(["bottom","top"]),constrain:O.default.constrain,id:d.default.string},X.defaultProps={trackPosition:true,placement:"bottom center",offsetX:0,offsetY:0,mountNode:null,target:null,insertAt:"bottom",over:false,onPositioned:function(t){},onPositionChanged:function(t){},constrain:"window",children:null,id:void 0},C))||W)||W)
var Y=J
e.default=Y},"6Rkx":function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=o
e.mirrorHorizontalPlacement=l
e.executeMirrorFunction=s
var a=r(n("J4zp"))
var i={center:"center",start:"end",end:"start",top:"bottom",bottom:"top",stretch:"stretch",offscreen:"offscreen"}
function o(t,e){return s(t,function(t,e){return[i[t],e]},e)}function l(t,e){return s(t,function(t,e){return[t,e].map(function(t){return"start"===t||"end"===t?i[t]:t})},e)}function s(t,e,n){var r=Array.isArray(t)?t:t.split(" "),i=(0,a.default)(r,2),o=i[0],l=i[1]
var s=e(o,l).filter(function(t){return t})
return n?s.join(n):s}},"6eAW":function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=s
var a=r(n("8HMx"))
var i=r(n("GrBK"))
var o=r(n("9Okx"))
var l={}
function s(t,e){if(!a.default)return 16
var n=t||(0,i.default)(t).documentElement
if(!e&&l[n])return l[n]
var r=parseInt((0,o.default)(n).getPropertyValue("font-size"))
l[n]=r
return r}},"6qnL":function(t,e,n){"use strict"
var r=n("284h")
var a=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=void 0
var i=a(n("MVZn"))
var o=a(n("lwsE"))
var l=a(n("W8MJ"))
var s=a(n("a1gu"))
var f=a(n("Nsbk"))
var u=a(n("7W2i"))
var c=r(n("q1tI"))
var h=a(n("q3EI"))
var d=c.default.createElement("path",{d:"M771.548 960.11L319 1412.658l188.562 188.562 452.548-452.548 452.548 452.548 188.562-188.562-452.548-452.548 452.548-452.548L1412.658 319 960.11 771.548 507.562 319 319 507.562z",fillRule:"nonzero",stroke:"none",strokeWidth:"1"})
var p=function(t){(0,u.default)(e,t)
function e(){(0,o.default)(this,e)
return(0,s.default)(this,(0,f.default)(e).apply(this,arguments))}(0,l.default)(e,[{key:"render",value:function(){return c.default.createElement(h.default,Object.assign({},this.props,{name:"IconX",viewBox:"0 0 1920 1920"}),d)}}])
e.displayName="IconX"
return e}(c.Component)
e.default=p
p.glyphName="x"
p.variant="Solid"
p.propTypes=(0,i.default)({},h.default.propTypes)},"8dII":function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=void 0
var a=r(n("17x9"))
var i=n("IzEL")
var o=r(n("pz3X"))
var l={validQuery:function(t,e,n){try{(0,o.default)(t[e])}catch(t){return new Error("Invalid query prop supplied to `".concat(n,"`. ").concat(t.message))}},placement:a.default.oneOf(["top","end","bottom","start","top start","start top","start center","start bottom","bottom start","bottom center","bottom end","end bottom","end center","end top","top end","top center","center end","center start","top stretch","bottom stretch","end stretch","start stretch","offscreen"]),mountNode:a.default.oneOfType([i.element,a.default.func]),constrain:a.default.oneOfType([i.element,a.default.func,a.default.oneOf(["window","scroll-parent","parent","none"])])}
e.default=l},DfZk:function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=m
e.parsePlacement=w
var a=r(n("J4zp"))
var i=r(n("lwsE"))
var o=r(n("W8MJ"))
var l=r(n("SuOk"))
var s=r(n("XLr1"))
var f=r(n("XH5L"))
var u=r(n("8HMx"))
var c=r(n("KB5V"))
var h=r(n("GrBK"))
var d=r(n("TNGd"))
var p=r(n("6Rkx"))
function m(t,e,n){if(!t||"offscreen"===n.placement){var r=!n.container&&t
return{placement:n.placement,style:{left:"-9999em",overflow:"hidden",position:"absolute",top:"0",display:r?"none":null}}}var a=new g(t,e,n)
return{placement:a.placement,style:a.style}}var v=function(){function t(e,n){var r=arguments.length>2&&void 0!==arguments[2]?arguments[2]:{top:0,left:0};(0,i.default)(this,t)
this.node=(0,c.default)(e)
"string"===typeof n?this.placement=w(n):Array.isArray(n)?this.placement=n:this.placement=["bottom","center"]
this.rect=(0,l.default)(this.node)
this._offset=x(r,this.size)}(0,o.default)(t,[{key:"calculateOffset",value:function(t){var e={top:0,start:0,center:"50%",bottom:"100%",end:"100%",stretch:0}
var n=(0,a.default)(t,2),r=n[0],i=n[1]
if(["start","end"].indexOf(r)>=0){var o=[i,r]
r=o[0]
i=o[1]}var l=0
var s=0
"undefined"!==typeof e[r]&&(l=e[r])
"undefined"!==typeof e[i]&&(s=e[i])
return b([x({top:l,left:s},this.size),y(this._offset,this.placement)])}},{key:"normalizeScrollTop",value:function(t){return(0,h.default)(this.node).body===t?0:t.scrollTop}},{key:"width",get:function(){return this.rect.width}},{key:"height",get:function(){return this.rect.height}},{key:"size",get:function(){return{width:this.width,height:this.height}}},{key:"position",get:function(){return{top:this.rect.top,left:this.rect.left}}},{key:"hasVerticalPlacement",get:function(){return["top","bottom"].indexOf(this.placement[0])>=0}},{key:"hasHorizontalPlacement",get:function(){return["start","end"].indexOf(this.placement[0])>=0}},{key:"shouldStretchVertically",get:function(){return"stretch"===this.placement[1]&&this.hasVerticalPlacement}},{key:"shouldStretchHorizontally",get:function(){return"stretch"===this.placement[1]&&this.hasHorizontalPlacement}},{key:"mirroredPlacement",get:function(){return(0,p.default)(this.placement)}},{key:"scrollParentsOffset",get:function(){var t=(0,s.default)(this.node)
var e=0
var n=0
for(var r=1;r<t.length;r++){var a=t[r]
var i=t[r-1]
e+=this.normalizeScrollTop(a)-this.normalizeScrollTop(i)
n+=a.scrollLeft-i.scrollLeft}return{top:e,left:n}}},{key:"positionedParentsOffset",get:function(){var t=(0,f.default)(this.node)
var e=(0,h.default)(this.node)
var n=t.length>1?0:e.documentElement.offsetTop
var r=0
var a=0
for(var i=1;i<t.length;i++){var o=(0,l.default)(t[i])
var s=(0,l.default)(t[i-1])
n+=s.top-o.top
r+=s.left-o.left
if(t[i]===e.body){n+=o.top
r+=o.left}a+=this.normalizeScrollTop(t[i])}n+=a
return{top:n,left:r}}}])
return t}()
var g=function(){function t(e,n,r){(0,i.default)(this,t)
this.options=r||{}
var a=this.options,o=a.container,l=a.constrain,f=a.placement,u=a.over
if(!e||"offscreen"===f)return
this.container=o||(0,h.default)(e).body
this.element=new v(e,f,{top:this.options.offsetY,left:this.options.offsetX})
this.target=new v(n||this.container,u?this.element.placement:this.element.mirroredPlacement)
"window"===l?this.constrainTo((0,d.default)(e)):"scroll-parent"===l?this.constrainTo((0,s.default)(this.target.node)[0]):"parent"===l?this.constrainTo(this.container):"function"===typeof l?this.constrainTo((0,c.default)(l.call(null))):"object"===typeof l&&this.constrainTo((0,c.default)(l))}(0,o.default)(t,[{key:"overflow",value:function(t){var e=(0,d.default)(t)
var n=(0,l.default)(t)
var r=(0,l.default)(e)
var a=b([this.target.position,this.offset])
var i={top:this.element.positionedParentsOffset.top+this.element.scrollParentsOffset.top,left:this.element.positionedParentsOffset.left+this.element.scrollParentsOffset.left}
var o=a.left+i.left
var s=a.left+this.element.width+i.left
var f=a.top+i.top
var u=a.top+this.element.height+i.top
"bottom"===this.element.placement[0]?f-=this.element.height+this.target.height:"top"===this.element.placement[0]&&(u+=this.element.height+this.target.height)
"start"===this.element.placement[1]?o-=this.element.width-this.target.width:"end"===this.element.placement[1]&&(s+=this.element.width-this.target.width)
"top"===this.element.placement[1]?f-=this.element.height-this.target.height:"bottom"===this.element.placement[1]&&(u+=this.element.height-this.target.height)
"end"===this.element.placement[0]?o-=this.element.width+this.target.width:"start"===this.element.placement[0]&&(s+=this.element.width+this.target.width)
var c=t===e?n:{top:r.top+n.top,bottom:n.top+n.height,left:r.left+n.left,right:n.left+n.width}
return{top:f<c.top?c.top-f:0,bottom:u>c.bottom?u-c.bottom:0,left:o<c.left?c.left-o:0,right:s>c.right?s-c.right:0}}},{key:"constrainTo",value:function(t){if(!t)return
var e=this.overflow(t)
var n={top:e.top>0,bottom:e.bottom>0,left:e.left>0,right:e.right>0}
if(this.element.hasVerticalPlacement){if("stretch"!==this.element.placement[1])if(n.left&&n.right){this.element.placement[1]="center"
this.target.placement[1]="center"}else if(n.left){this.element.placement[1]="start"
this.target.placement[1]="start"}else if(n.right){this.element.placement[1]="end"
this.target.placement[1]="end"}if(n.top&&n.bottom){if(e.bottom<e.top){this.element.placement[0]="bottom"
this.target.placement[0]="top"}else if(e.bottom>e.top){this.element.placement[0]="top"
this.target.placement[0]="bottom"}}else if(n.top){this.element.placement[0]="bottom"
this.target.placement[0]="top"}else if(n.bottom){this.element.placement[0]="top"
this.target.placement[0]="bottom"}}else if(this.element.hasHorizontalPlacement){if(n.top&&n.bottom){this.element.placement[1]="center"
this.target.placement[1]="center"}else if(n.top){this.element.placement[1]="top"
this.target.placement[1]="top"}else if(n.bottom){this.element.placement[1]="bottom"
this.target.placement[1]="bottom"}if(n.left&&n.right){if(e.left>e.right){this.element.placement[0]="end"
this.target.placement[0]="start"}else if(e.left<e.right){this.element.placement[0]="start"
this.target.placement[0]="end"}}else if(n.left){this.element.placement[0]="end"
this.target.placement[0]="start"}else if(n.right){this.element.placement[0]="start"
this.target.placement[0]="end"}}}},{key:"offset",get:function(){var t=this.target.calculateOffset(this.element.placement),e=t.top,n=t.left
var r=b([this.element.calculateOffset(this.target.placement),this.element.scrollParentsOffset,this.element.positionedParentsOffset])
return{top:e-r.top,left:n-r.left}}},{key:"placement",get:function(){return j(this.element.placement)}},{key:"minWidth",get:function(){return this.element.shouldStretchVertically?this.target.width:null}},{key:"minHeight",get:function(){return this.element.shouldStretchHorizontally?this.target.height:null}},{key:"position",get:function(){var t=(0,d.default)(this.target.node)
var e=b([this.target.position,this.offset]),n=e.left,r=e.top
if(u.default&&t.matchMedia){var a=t.matchMedia("only screen and (min-resolution: 1.3dppx)").matches||t.matchMedia("only screen and (-webkit-min-device-pixel-ratio: 1.3)").matches
if(!a){n=Math.round(n)
r=Math.round(r)}}return{left:n,top:r}}},{key:"style",get:function(){return{top:0,left:0,minWidth:this.minWidth,minHeight:this.minHeight,position:"absolute",transform:"translateX(".concat(this.position.left,"px) translateY(").concat(this.position.top,"px) translateZ(0)")}}}])
return t}()
function b(t){return t.reduce(function(t,e){return{top:t.top+e.top,left:t.left+e.left}},{top:0,left:0})}function y(t,e){var n=t.top,r=t.left
"bottom"===e[0]&&(n=0-parseFloat(n,10))
"end"===e[0]&&(r=0-parseFloat(r,10))
return{top:n,left:r}}function x(t,e){var n=t.left,r=t.top
n="string"===typeof n&&-1!==n.indexOf("%")?parseFloat(n,10)/100*e.width:parseFloat(n,10)
r="string"===typeof r&&-1!==r.indexOf("%")?parseFloat(r,10)/100*e.height:parseFloat(r,10)
return{top:r,left:n}}function _(t){var e=(0,a.default)(t,2),n=e[0],r=e[1]
if("center"===n||"stretch"===n){var i=[r,n]
n=i[0]
r=i[1]}return[n,r]}function w(t){var e=t.split(" ")
1===e.length&&(e=[t,"center"])
return _(e)}function j(t){return t.join(" ")}},SJAx:function(t,e,n){"use strict"
var r=n("TqRt")
var a=n("284h")
Object.defineProperty(e,"__esModule",{value:true})
e.default=void 0
var i=r(n("lSNA"))
var o=r(n("lwsE"))
var l=r(n("W8MJ"))
var s=r(n("a1gu"))
var f=r(n("Nsbk"))
var u=r(n("7W2i"))
var c=a(n("q1tI"))
var h=r(n("17x9"))
var d=r(n("TSYQ"))
var p=r(n("6qnL"))
var m=r(n("qnOc"))
var v=r(n("Zuoh"))
var g=r(n("J2CL"))
var b=r(n("5WdN"))
var y=n("2lwo")
var x=r(n("VMdx"))
var _=r(n("ZmrP"))
var w,j,k,D,T
var P={componentId:"ejhDx",template:function(t){return"\n\n.ejhDx_bGBk{display:inline-block;z-index:".concat(t.zIndex||"inherit","}\n\n.ejhDx_doBn{position:static}\n\n.ejhDx_bQpq,.ejhDx_bxia{position:absolute}\n\n.ejhDx_coHh{top:").concat(t.offsetXSmall||"inherit","}\n\n.ejhDx_cDib{top:").concat(t.offsetSmall||"inherit","}\n\n.ejhDx_faeR{top:").concat(t.offsetMedium||"inherit","}\n\n.ejhDx_bQpq{inset-inline-end:0;inset-inline-start:auto}\n\n[dir=ltr] .ejhDx_bQpq{left:auto;right:0}\n\n[dir=rtl] .ejhDx_bQpq{left:0;right:auto}\n\n.ejhDx_bQpq.ejhDx_coHh{inset-inline-end:").concat(t.offsetXSmall||"inherit",";inset-inline-start:auto}\n\n[dir=ltr] .ejhDx_bQpq.ejhDx_coHh{left:auto;right:").concat(t.offsetXSmall||"inherit","}\n\n[dir=rtl] .ejhDx_bQpq.ejhDx_coHh{left:").concat(t.offsetXSmall||"inherit",";right:auto}\n\n.ejhDx_bQpq.ejhDx_cDib{inset-inline-end:").concat(t.offsetSmall||"inherit",";inset-inline-start:auto}\n\n[dir=ltr] .ejhDx_bQpq.ejhDx_cDib{left:auto;right:").concat(t.offsetSmall||"inherit","}\n\n[dir=rtl] .ejhDx_bQpq.ejhDx_cDib{left:").concat(t.offsetSmall||"inherit",";right:auto}\n\n.ejhDx_bQpq.ejhDx_faeR{inset-inline-end:").concat(t.offsetMedium||"inherit",";inset-inline-start:auto}\n\n[dir=ltr] .ejhDx_bQpq.ejhDx_faeR{left:auto;right:").concat(t.offsetMedium||"inherit","}\n\n[dir=rtl] .ejhDx_bQpq.ejhDx_faeR{left:").concat(t.offsetMedium||"inherit",";right:auto}\n\n.ejhDx_bxia{inset-inline-end:auto;inset-inline-start:0}\n\n[dir=ltr] .ejhDx_bxia{left:0;right:auto}\n\n[dir=rtl] .ejhDx_bxia{left:auto;right:0}\n\n.ejhDx_bxia.ejhDx_coHh{inset-inline-end:auto;inset-inline-start:").concat(t.offsetXSmall||"inherit","}\n\n[dir=ltr] .ejhDx_bxia.ejhDx_coHh{left:").concat(t.offsetXSmall||"inherit",";right:auto}\n\n[dir=rtl] .ejhDx_bxia.ejhDx_coHh{left:auto;right:").concat(t.offsetXSmall||"inherit","}\n\n.ejhDx_bxia.ejhDx_cDib{inset-inline-end:auto;inset-inline-start:").concat(t.offsetSmall||"inherit","}\n\n[dir=ltr] .ejhDx_bxia.ejhDx_cDib{left:").concat(t.offsetSmall||"inherit",";right:auto}\n\n[dir=rtl] .ejhDx_bxia.ejhDx_cDib{left:auto;right:").concat(t.offsetSmall||"inherit","}\n\n.ejhDx_bxia.ejhDx_faeR{inset-inline-end:auto;inset-inline-start:").concat(t.offsetMedium||"inherit","}\n\n[dir=ltr] .ejhDx_bxia.ejhDx_faeR{left:").concat(t.offsetMedium||"inherit",";right:auto}\n\n[dir=rtl] .ejhDx_bxia.ejhDx_faeR{left:auto;right:").concat(t.offsetMedium||"inherit","}")},root:"ejhDx_bGBk","placement--static":"ejhDx_doBn","placement--end":"ejhDx_bQpq","placement--start":"ejhDx_bxia","offset--x-small":"ejhDx_coHh","offset--small":"ejhDx_cDib","offset--medium":"ejhDx_faeR"}
var O=(w=(0,v.default)(),j=(0,g.default)(_.default,P),w(k=j(k=(T=D=function(t){(0,u.default)(e,t)
function e(){(0,o.default)(this,e)
return(0,s.default)(this,(0,f.default)(e).apply(this,arguments))}(0,l.default)(e,[{key:"render",value:function(){var t
var n=this.props,r=n.placement,a=n.offset
return c.default.createElement("span",Object.assign({},(0,y.omitProps)(this.props,e.propTypes),{className:(0,d.default)((t={},(0,i.default)(t,P.root,true),(0,i.default)(t,P["placement--".concat(r)],r),(0,i.default)(t,P["offset--".concat(a)],a),t))}),c.default.createElement(x.default,Object.assign({},(0,y.pickProps)(this.props,x.default.propTypes),{icon:p.default}),c.default.createElement(m.default,null,this.props.children)))}}])
e.displayName="CloseButton"
return e}(c.Component),D.propTypes={children:h.default.node.isRequired,buttonRef:h.default.func,size:h.default.oneOf(["small","medium","large"]),onClick:h.default.func,margin:b.default.spacing,placement:h.default.oneOf(["start","end","static"]),offset:h.default.oneOf(["none","x-small","small","medium"]),variant:h.default.oneOf(["icon","icon-inverse"])},D.defaultProps={onClick:function(t){},buttonRef:function(t){},variant:"icon",placement:"static",offset:"x-small",size:"small",margin:"0"},T))||k)||k)
var M=O
e.default=M},SuOk:function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=s
var a=r(n("KB5V"))
var i=r(n("8HMx"))
var o=r(n("7TwR"))
var l=r(n("GrBK"))
function s(t){var e={top:0,left:0,height:0,width:0}
if(!i.default)return e
var n=(0,a.default)(t)
if(!n)return e
if(n===window)return{left:window.pageXOffset,top:window.pageYOffset,width:window.innerWidth,height:window.innerHeight,right:window.innerWidth+window.pageXOffset,bottom:window.innerHeight+window.pageYOffset}
var r=t===document?document:(0,l.default)(n)
var f=r&&r.documentElement
if(!f||!(0,o.default)(f,n))return e
var u=n.getBoundingClientRect()
var c
for(c in u)e[c]=u[c]
if(r!==document){var h=r.defaultView.frameElement
if(h){var d=s(h)
e.top+=d.top
e.bottom+=d.top
e.left+=d.left
e.right+=d.left}}return{top:e.top+(window.pageYOffset||f.scrollTop)-(f.clientTop||0),left:e.left+(window.pageXOffset||f.scrollLeft)-(f.clientLeft||0),width:(null==e.width?n.offsetWidth:e.width)||0,height:(null==e.height?n.offsetHeight:e.height)||0,right:r.body.clientWidth-e.width-e.left,bottom:r.body.clientHeight-e.height-e.top}}},XH5L:function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=s
var a=r(n("KB5V"))
var i=r(n("8HMx"))
var o=r(n("9Okx"))
var l=r(n("GrBK"))
function s(t){var e=[]
if(!i.default)return e
var n=(0,a.default)(t)
if(n){var r=n
while((r=r.parentNode)&&r&&1===r.nodeType&&"BODY"!==r.tagName){var s=(0,o.default)(r)
var f=s.getPropertyValue("-webkit-transform")||s.getPropertyValue("-moz-transform")||s.getPropertyValue("-ms-transform")||s.getPropertyValue("-o-transform")||s.getPropertyValue("transform")||"none"
var u="none"===f||"matrix(1, 0, 0, 1, 0, 0)"===f
"static"===s.position&&u||e.push(r)}e.push((0,l.default)(n).body)}return e}},XLr1:function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=l
var a=r(n("KB5V"))
var i=r(n("8HMx"))
var o=r(n("9Okx"))
function l(t){var e=[]
if(!i.default)return e
var n=(0,a.default)(t)
if(n){var r=(0,o.default)(n)||{}
var l=r.position
if("fixed"===l)return[n.ownerDocument]
var s=n
while(s&&1===s.nodeType&&(s=s.parentNode)){var f=void 0
try{f=(0,o.default)(s)}catch(t){}if("undefined"===typeof f||null===f){e.push(s)
return e}var u=f,c=u.overflow,h=u.overflowX,d=u.overflowY;/(auto|scroll|overlay)/.test(c+d+h)&&("absolute"!==l||["relative","absolute","fixed"].indexOf(f.position)>=0)&&e.push(s)}e.push(n.ownerDocument.body)
n.ownerDocument!==document&&e.push(n.ownerDocument.defaultView)}return e}},ZmrP:function(t,e,n){"use strict"
Object.defineProperty(e,"__esModule",{value:true})
e.default=r
function r(t){var e=t.spacing,n=t.stacking
return{offsetMedium:e.medium,offsetSmall:e.small,offsetXSmall:e.xSmall,zIndex:n.above}}},dx2U:function(t,e,n){var r=n("q1tI")
function a(){var t=""
try{t=r.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED.ReactDebugCurrentFrame.getStackAddendum()}catch(t){}return t}function i(t,e,n){if(!e&&false){var r=a()
if("function"!==typeof console[t])throw new Error("'".concat(t,"' is not a valid console method!"))
var i
for(var o=arguments.length,l=new Array(o>3?o-3:0),s=3;s<o;s++)l[s-3]=arguments[s];(i=console)[t].apply(i,["Warning: ".concat(n)].concat(l,[r]))}}e.error=function(){for(var t=arguments.length,e=new Array(t),n=0;n<t;n++)e[n]=arguments[n]
return i.apply(void 0,["error"].concat(e))}
e.warn=function(){for(var t=arguments.length,e=new Array(t),n=0;n<t;n++)e[n]=arguments[n]
return i.apply(void 0,["warn"].concat(e))}
e.info=function(){var t
return(t=console).info.apply(t,arguments)}
e.assert=function(){var t
return(t=console).assert.apply(t,arguments)}
e.debug=function(){var t
return(t=console).debug.apply(t,arguments)}
e.log=function(){var t
return(t=console).log.apply(t,arguments)}},eHUd:function(t,e,n){"use strict"
n.r(e)
n.d(e,"default",function(){return r})
function r(t){var e=arguments.length>1&&void 0!==arguments[1]?arguments[1]:0
var n=arguments.length>2&&void 0!==arguments[2]?arguments[2]:{}
var r,a,i,o
var l=0
var s=[]
var f=false
if("function"!==typeof t)throw new TypeError("Expected a function")
var u=!!n.leading
var c="maxWait"in n
var h=!("trailing"in n)||!!n.trailing
var d=c?Math.max(+n.maxWait||0,e):0
function p(e){var n=r
var o=a
r=a=void 0
l=e
if(true!==f){i=t.apply(o,n)
return i}}function m(t){l=t
s.push(setTimeout(b,e))
return u?p(t):i}function v(t){var n=t-o
var r=t-l
var a=e-n
return c?Math.min(a,d-r):a}function g(t){var n=t-o
var r=t-l
return"undefined"===typeof o||n>=e||n<0||c&&r>=d}function b(){var t=Date.now()
if(g(t))return y(t)
s.push(setTimeout(b,v(t)))}function y(t){w()
if(h&&r)return p(t)
r=a=void 0
return i}function x(){f=true
w()
l=0
r=o=a=void 0}function _(){return 0===s.length?i:y(Date.now())}function w(){s.forEach(function(t){return clearTimeout(t)})
s=[]}function j(){var t=Date.now()
var n=g(t)
for(var l=arguments.length,f=new Array(l),u=0;u<l;u++)f[u]=arguments[u]
r=f
a=this
o=t
if(n){if(0===s.length)return m(o)
if(c){s.push(setTimeout(b,e))
return p(o)}}0===s.length&&s.push(setTimeout(b,e))
return i}j.cancel=x
j.flush=_
return j}},lS51:function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=l
var a=r(n("KB5V"))
var i=r(n("SuOk"))
var o=r(n("cOnk"))
function l(t,e){var n=(0,a.default)(t)
var r=[]
var l=(0,i.default)(n)||{}
var s=false
function f(){if(false===s){var t=(0,i.default)(n)||{}
var a=t.top!==l.top||t.left!==l.left||t.right!==l.right||t.bottom!==l.bottom||t.width!==l.width||t.height!==l.height
a&&"function"===typeof e&&e(t)
l=t
r.push((0,o.default)(f))}}f()
return{remove:function(){s=true
r.forEach(function(t){return t.cancel()})}}}},pz3X:function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=i
var a=r(n("t5Un"))
function i(t,e){var n=Object.keys(t)
if(1!==n.length)throw new Error("Expected exactly one key in query object.")
var r=n[0]
var i=["minHeight","maxHeight","minWidth","maxWidth"]
if(-1===i.indexOf(r))throw new Error("Invalid key `".concat(r,"` in query object. Valid keys should consist of one of the following: ")+"".concat(i.join(", ")," (case sensitive)"))
var l=t[r]
if("string"!==typeof l&&"number"!==typeof l)throw new Error("The value of the query object must be a string or number.")
if(!l)throw new Error("No value supplied for query object")
return"(".concat(o(r.toLowerCase()),": ").concat((0,a.default)(l,e),"px)")}function o(t){return t.slice(0,3)+"-"+t.slice(3)}},q9F9:function(t,e,n){"use strict"
var r=n("284h")
var a=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.pick=v
e.default=void 0
var i=a(n("QILm"))
var o=a(n("lwsE"))
var l=a(n("W8MJ"))
var s=a(n("a1gu"))
var f=a(n("Nsbk"))
var u=a(n("7W2i"))
var c=r(n("q1tI"))
var h=a(n("17x9"))
var d=a(n("+mmM"))
var p=a(n("lGJA"))
var m=function(t){(0,u.default)(e,t)
function e(){(0,o.default)(this,e)
return(0,s.default)(this,(0,f.default)(e).apply(this,arguments))}(0,l.default)(e,[{key:"render",value:function(){var t=this.props,e=t.children,n=(0,i.default)(t,["children"])
return(0,p.default)(e,n)}}])
e.displayName="ComponentIdentifier"
return e}(c.Component)
e.default=m
m.propTypes={children:h.default.node}
m.defaultProps={children:null}
function v(t,e){var n
c.default.Children.forEach(e,function(e){(0,d.default)(e,[t])&&(n=e)})
return n}},t5Un:function(t,e,n){"use strict"
var r=n("TqRt")
Object.defineProperty(e,"__esModule",{value:true})
e.default=l
var a=r(n("J4zp"))
var i=r(n("6eAW"))
var o=r(n("HK1/"))
function l(t,e){var n=e||document.body
if(!t||"number"===typeof t)return t
var r=(0,o.default)(t),l=(0,a.default)(r,2),s=l[0],f=l[1]
return"rem"===f?s*(0,i.default)():"em"===f?s*(0,i.default)(n):s}},uwQ2:function(t,e,n){"use strict"
Object.defineProperty(e,"__esModule",{value:true})
e.default=r
function r(t){var e=t.stacking
return{zIndex:e.topmost}}}}])

//# sourceMappingURL=10-c-d0f420ee62.js.map