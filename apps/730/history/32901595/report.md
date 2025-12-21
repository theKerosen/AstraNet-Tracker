# Update 32901595

**Build ID**: `21248816`  
**Date**: 2025-12-20 07:25:12 UTC  

## 🔴 Impact Analysis

- **Score**: 70154/100
- **Severity**: CRITICAL
- **Type**: Patch (Forced Analysis)

### 📦 Changed Depots

| ID | Name |
| :--- | :--- |
| `2347773` | CS2 Workshop |
| `2347775` | Unknown Depot |
| `228990` | Unknown Depot |
| `736` | Binaries Linux |
| `228988` | Unknown Depot |
| `733` | Public (Debug) |
| `738` | Binaries Mac ARM |
| `2347770` | CS2 Content |
| `2347774` | CS2 Workshop Linux |
| `2347777` | Unknown Depot |
| `730` | Unknown Depot |
| `732` | Public (Beta) |
| `731` | Public |
| `2347772` | CS2 Content Asia |
| `2347776` | Unknown Depot |
| `2347778` | Unknown Depot |
| `2347779` | CS2 Dedicated Server |
| `734` | Binaries |
| `735` | Binaries Win64 |
| `737` | Binaries Mac |
| `2347771` | CS2 Content (Low Violence) |

### 🆕 New Strings (1457599)

> [!TIP]
> [Click here to view the full list of strings](https://github.com/theKerosen/AstraNet-Tracker/blob/main/diffs/32901595_strings.txt)

#### weapons
```
DebugUnlockZoom
?drawPixmap@QPainter@@QEAAXAEBVQRect@@AEBVQPixmap@@0@Z
?drawPixmap@QPainter@@QEAAXAEBVQPoint@@AEBVQPixmap@@@Z
?drawPath@QPainter@@QEAAXAEBVQPainterPath@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQPointF@@AEBVQPixmap@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQRect@@AEBVQPixmap@@@Z
?drawPoints@QPainter@@QEAAXAEBVQPolygonF@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQRectF@@AEBVQPixmap@@0@Z
?drawPixmap@QPainter@@QEAAXHHHHAEBVQPixmap@@@Z
?drawPolygon@QPainter@@QEAAXPEBVQPointF@@HW4FillRule@Qt@@@Z
?drawPolygon@QPainter@@QEAAXAEBVQPolygon@@W4FillRule@Qt@@@Z
drawPoints
MeshDrawPrimitiveFlags_t
gun_grunge.psd
?drawPath@QPainter@@QEAAXAEBVQPainterPath@@@Z
_Gunsmith
_GunsmithExtended
_GunsmithCaseHardening
AE_NPC_WEAPON_FIRE
MeshDrawPrimitiveFlags_t
AE_STRIDER_SHOOTMINIGUN
AE_NPC_WEAPON_DROP
AE_WEAPON_MELEE_HIT
AE_WEAPON_SMG1
AE_WEAPON_MELEE_SWISH
AE_WEAPON_SHOTGUN_FIRE
AE_WEAPON_THROW
AE_WEAPON_AR1
AE_WEAPON_AR2
AE_WEAPON_HMG1
AE_WEAPON_SMG2
AE_WEAPON_MISSILE_FIRE
AE_WEAPON_SNIPER_RIFLE_FIRE
AE_WEAPON_AR2_GRENADE
AE_WEAPON_THROW2
AE_WEAPON_PISTOL_FIRE
AE_WEAPON_RELOAD
AE_WEAPON_THROW3
AE_WEAPON_RELOAD_SOUND
AE_WEAPON_RELOAD_FILL_CLIP
AE_WEAPON_SMG1_BURST1
AE_WEAPON_SMG1_BURSTN
AE_WEAPON_AR2_ALTFIRE
AE_WEAPON_SEQUENCE_FINISHED
    -write_weapon_anim_prefab  : Write sequences & weighlists into a prefab. 
    -weapon_anim_prefab <path> : Path to a prefab to be included. Path relative to 'output path'.
-write_weapon_anim_prefab
-weapon_anim_prefab
Expected argument for -weapon_anim_prefab
?drawPolyline@QPainter@@QEAAXAEBVQPolygon@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQPointF@@AEBVQPixmap@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQRect@@AEBVQPixmap@@@Z
AE_NPC_WEAPON_FIRE
AE_NPC_WEAPON_DROP
AE_STRIDER_SHOOTMINIGUN
MeshDrawPrimitiveFlags_t
physgun_interactions
m_physgunInteractions
drawPoints
ATTN_GUNFIRE
SNDLVL_GUNFIRE
valueOf:!1,WeakMap:!1,WeakSet:!1},es5:{Array:!1,Boolean:!1,constructor:!1,Date:!1,decodeURI:!1,decodeURIComponent:!1,encodeURI:!1,encodeURIComponent:!1,Error:!1,escape:!1,eval:!1,EvalError:!1,Function:!1,hasOwnProperty:!1,Infinity:!1,isFinite:!1,isNaN:!1,isPrototypeOf:!1,JSON:!1,Math:!1,NaN:!1,Number:!1,Object:!1,parseFloat:!1,parseInt:!1,propertyIsEnumerable:!1,RangeError:!1,ReferenceError:!1,RegExp:!1,String:!1,SyntaxError:!1,toLocaleString:!1,toString:!1,TypeError:!1,undefined:!1,unescape:!1,URIError:!1,valueOf:!1},es6:{Array:!1,ArrayBuffer:!1,Boolean:!1,constructor:!1,DataView:!1,Date:!1,decodeURI:!1,decodeURIComponent:!1,encodeURI:!1,encodeURIComponent:!1,Error:!1,escape:!1,eval:!1,EvalError:!1,Float32Array:!1,Float64Array:!1,Function:!1,hasOwnProperty:!1,Infinity:!1,Int16Array:!1,Int32Array:!1,Int8Array:!1,isFinite:!1,isNaN:!1,isPrototypeOf:!1,JSON:!1,Map:!1,Math:!1,NaN:!1,Number:!1,Object:!1,parseFloat:!1,parseInt:!1,Promise:!1,propertyIsEnumerable:!1,Proxy:!1,RangeError:!1,ReferenceError:!1,Reflect:!1,RegExp:!1,Set:!1,String:!1,Symbol:!1,SyntaxError:!1,System:!1,toLocaleString:!1,toString:!1,TypeError:!1,Uint16Array:!1,Uint32Array:!1,Uint8Array:!1,Uint8ClampedArray:!1,undefined:!1,unescape:!1,URIError:!1,valueOf:!1,WeakMap:!1,WeakSet:!1},browser:{addEventListener:!1,alert:!1,AnalyserNode:!1,Animation:!1,AnimationEffectReadOnly:!1,AnimationEffectTiming:!1,AnimationEffectTimingReadOnly:!1,AnimationEvent:!1,AnimationPlaybackEvent:!1,AnimationTimeline:!1,applicationCache:!1,ApplicationCache:!1,ApplicationCacheErrorEvent:!1,atob:!1,Attr:!1,Audio:!1,AudioBuffer:!1,AudioBufferSourceNode:!1,AudioContext:!1,AudioDestinationNode:!1,AudioListener:!1,AudioNode:!1,AudioParam:!1,AudioProcessingEvent:!1,AutocompleteErrorEvent:!1,BarProp:!1,BatteryManager:!1,BeforeUnloadEvent:!1,BiquadFilterNode:!1,Blob:!1,blur:!1,btoa:!1,Cache:!1,caches:!1,CacheStorage:!1,cancelAnimationFrame:!1,cancelIdleCallback:!1,CanvasGradient:!1,CanvasPattern:!1,CanvasRenderingContext2D:!1,CDATASection:!1,ChannelMergerNode:!1,ChannelSplitterNode:!1,CharacterData:!1,clearInterval:!1,clearTimeout:!1,clientInformation:!1,ClientRect:!1,ClientRectList:!1,ClipboardEvent:!1,close:!1,closed:!1,CloseEvent:!1,Comment:!1,CompositionEvent:!1,confirm:!1,console:!1,ConvolverNode:!1,createImageBitmap:!1,Credential:!1,CredentialsContainer:!1,crypto:!1,Crypto:!1,CryptoKey:!1,CSS:!1,CSSAnimation:!1,CSSFontFaceRule:!1,CSSImportRule:!1,CSSKeyframeRule:!1,CSSKeyframesRule:!1,CSSMediaRule:!1,CSSPageRule:!1,CSSRule:!1,CSSRuleList:!1,CSSStyleDeclaration:!1,CSSStyleRule:!1,CSSStyleSheet:!1,CSSSupportsRule:!1,CSSTransition:!1,CSSUnknownRule:!1,CSSViewportRule:!1,customElements:!1,CustomEvent:!1,DataTransfer:!1,DataTransferItem:!1,DataTransferItemList:!1,Debug:!1,defaultStatus:!1,defaultstatus:!1,DelayNode:!1,DeviceMotionEvent:!1,DeviceOrientationEvent:!1,devicePixelRatio:!1,dispatchEvent:!1,document:!1,Document:!1,DocumentFragment:!1,DocumentTimeline:!1,DocumentType:!1,DOMError:!1,DOMException:!1,DOMImplementation:!1,DOMParser:!1,DOMSettableTokenList:!1,DOMStringList:!1,DOMStringMap:!1,DOMTokenList:!1,DragEvent:!1,DynamicsCompressorNode:!1,Element:!1,ElementTimeControl:!1,ErrorEvent:!1,event:!1,Event:!1,EventSource:!1,EventTarget:!1,external:!1,FederatedCredential:!1,fetch:!1,File:!1,FileError:!1,FileList:!1,FileReader:!1,find:!1,focus:!1,FocusEvent:!1,FontFace:!1,FormData:!1,frameElement:!1,frames:!1,GainNode:!1,Gamepad:!1,GamepadButton:!1,GamepadEvent:!1,getComputedStyle:!1,getSelection:!1,HashChangeEvent:!1,Headers:!1,history:!1,History:!1,HTMLAllCollection:!1,HTMLAnchorElement:!1,HTMLAppletElement:!1,HTMLAreaElement:!1,HTMLAudioElement:!1,HTMLBaseElement:!1,HTMLBlockquoteElement:!1,HTMLBodyElement:!1,HTMLBRElement:!1,HTMLButtonElement:!1,HTMLCanvasElement:!1,HTMLCollection:!1,HTMLContentElement:!1,HTMLDataListElement:!1,HTMLDetailsElement:!1,HTMLDialogElement:!1,HTMLDirectoryElement:!1,HTMLDivElement:!1,HTMLDListElement:!1,HTMLDocument:!1,HTMLElement:!1,HTMLEmbedElement:!1,HTMLFieldSetElement:!1,HTMLFontElement:!1,HTMLFormControlsCollection:!1,HTMLFormElement:!1,HTMLFrameElement:!1,HTMLFrameSetElement:!1,HTMLHeadElement:!1,HTMLHeadingElement:!1,HTMLHRElement:!1,HTMLHtmlElement:!1,HTMLIFrameElement:!1,HTMLImageElement:!1,HTMLInputElement:!1,HTMLIsIndexElement:!1,HTMLKeygenElement:!1,HTMLLabelElement:!1,HTMLLayerElement:!1,HTMLLegendElement:!1,HTMLLIElement:!1,HTMLLinkElement:!1,HTMLMapElement:!1,HTMLMarqueeElement:!1,HTMLMediaElement:!1,HTMLMenuElement:!1,HTMLMetaElement:!1,HTMLMeterElement:!1,HTMLModElement:!1,HTMLObjectElement:!1,HTMLOListElement:!1,HTMLOptGroupElement:!1,HTMLOptionElement:!1,HTMLOptionsCollection:!1,HTMLOutputElement:!1,HTMLParagraphElement:!1,HTMLParamElement:!1,HTMLPictureElement:!1,HTMLPreElement:!1,HTMLProgressElement:!1,HTMLQuoteElement:!1,HTMLScriptElement:!1,HTMLSelectElement:!1,HTMLShadowElement:!1,HTMLSourceElement:!1,HTMLSpanElement:!1,HTMLStyleElement:!1,HTMLTableCaptionElement:!1,HTMLTableCellElement:!1,HTMLTableColElement:!1,HTMLTableElement:!1,HTMLTableRowElement:!1,HTMLTableSectionElement:!1,HTMLTemplateElement:!1,HTMLTextAreaElement:!1,HTMLTitleElement:!1,HTMLTrackElement:!1,HTMLUListElement:!1,HTMLUnknownElement:!1,HTMLVideoElement:!1,IDBCursor:!1,IDBCursorWithValue:!1,IDBDatabase:!1,IDBEnvironment:!1,IDBFactory:!1,IDBIndex:!1,IDBKeyRange:!1,IDBObjectStore:!1,IDBOpenDBRequest:!1,IDBRequest:!1,IDBTransaction:!1,IDBVersionChangeEvent:!1,Image:!1,ImageBitmap:!1,ImageData:!1,indexedDB:!1,innerHeight:!1,innerWidth:!1,InputEvent:!1,InputMethodContext:!1,IntersectionObserver:!1,IntersectionObserverEntry:!1,Intl:!1,KeyboardEvent:!1,KeyframeEffect:!1,KeyframeEffectReadOnly:!1,length:!1,localStorage:!1,location:!1,Location:!1,locationbar:!1,matchMedia:!1,MediaElementAudioSourceNode:!1,MediaEncryptedEvent:!1,MediaError:!1,MediaKeyError:!1,MediaKeyEvent:!1,MediaKeyMessageEvent:!1,MediaKeys:!1,MediaKeySession:!1,MediaKeyStatusMap:!1,MediaKeySystemAccess:!1,MediaList:!1,MediaQueryList:!1,MediaQueryListEvent:!1,MediaSource:!1,MediaRecorder:!1,MediaStream:!1,MediaStreamAudioDestinationNode:!1,MediaStreamAudioSourceNode:!1,MediaStreamEvent:!1,MediaStreamTrack:!1,menubar:!1,MessageChannel:!1,MessageEvent:!1,MessagePort:!1,MIDIAccess:!1,MIDIConnectionEvent:!1,MIDIInput:!1,MIDIInputMap:!1,MIDIMessageEvent:!1,MIDIOutput:!1,MIDIOutputMap:!1,MIDIPort:!1,MimeType:!1,MimeTypeArray:!1,MouseEvent:!1,moveBy:!1,moveTo:!1,MutationEvent:!1,MutationObserver:!1,MutationRecord:!1,name:!1,NamedNodeMap:!1,navigator:!1,Navigator:!1,Node:!1,NodeFilter:!1,NodeIterator:!1,NodeList:!1,Notification:!1,OfflineAudioCompletionEvent:!1,OfflineAudioContext:!1,offscreenBuffering:!1,onbeforeunload:!0,onblur:!0,onerror:!0,onfocus:!0,onload:!0,onresize:!0,onunload:!0,open:!1,openDatabase:!1,opener:!1,opera:!1,Option:!1,OscillatorNode:!1,outerHeight:!1,outerWidth:!1,PageTransitionEvent:!1,pageXOffset:!1,pageYOffset:!1,parent:!1,PasswordCredential:!1,Path2D:!1,performance:!1,Performance:!1,PerformanceEntry:!1,PerformanceMark:!1,PerformanceMeasure:!1,PerformanceNavigation:!1,PerformanceResourceTiming:!1,PerformanceTiming:!1,PeriodicWave:!1,Permissions:!1,PermissionStatus:!1,personalbar:!1,Plugin:!1,PluginArray:!1,PopStateEvent:!1,postMessage:!1,print:!1,ProcessingInstruction:!1,ProgressEvent:!1,PromiseRejectionEvent:!1,prompt:!1,PushManager:!1,PushSubscription:!1,RadioNodeList:!1,Range:!1,ReadableByteStream:!1,ReadableStream:!1,removeEventListener:!1,Request:!1,requestAnimationFrame:!1,requestIdleCallback:!1,resizeBy:!1,resizeTo:!1,Response:!1,RTCIceCandidate:!1,RTCSessionDescription:!1,RTCPeerConnection:!1,screen:!1,Screen:!1,screenLeft:!1,ScreenOrientation:!1,screenTop:!1,screenX:!1,screenY:!1,ScriptProcessorNode:!1,scroll:!1,scrollbars:!1,scrollBy:!1,scrollTo:!1,scrollX:!1,scrollY:!1,SecurityPolicyViolationEvent:!1,Selection:!1,self:!1,ServiceWorker:!1,ServiceWorkerContainer:!1,ServiceWorkerRegistration:!1,sessionStorage:!1,setInterval:!1,setTimeout:!1,ShadowRoot:!1,SharedKeyframeList:!1,SharedWorker:!1,showModalDialog:!1,SiteBoundCredential:!1,speechSynthesis:!1,SpeechSynthesisEvent:!1,SpeechSynthesisUtterance:!1,status:!1,statusbar:!1,stop:!1,Storage:!1,StorageEvent:!1,styleMedia:!1,StyleSheet:!1,StyleSheetList:!1,SubtleCrypto:!1,SVGAElement:!1,SVGAltGlyphDefElement:!1,SVGAltGlyphElement:!1,SVGAltGlyphItemElement:!1,SVGAngle:!1,SVGAnimateColorElement:!1,SVGAnimatedAngle:!1,SVGAnimatedBoolean:!1,SVGAnimatedEnumeration:!1,SVGAnimatedInteger:!1,SVGAnimatedLength:!1,SVGAnimatedLengthList:!1,SVGAnimatedNumber:!1,SVGAnimatedNumberList:!1,SVGAnimatedPathData:!1,SVGAnimatedPoints:!1,SVGAnimatedPreserveAspectRatio:!1,SVGAnimatedRect:!1,SVGAnimatedString:!1,SVGAnimatedTransformList:!1,SVGAnimateElement:!1,SVGAnimateMotionElement:!1,SVGAnimateTransformElement:!1,SVGAnimationElement:!1,SVGCircleElement:!1,SVGClipPathElement:!1,SVGColor:!1,SVGColorProfileElement:!1,SVGColorProfileRule:!1,SVGComponentTransferFunctionElement:!1,SVGCSSRule:!1,SVGCursorElement:!1,SVGDefsElement:!1,SVGDescElement:!1,SVGDiscardElement:!1,SVGDocument:!1,SVGElement:!1,SVGElementInstance:!1,SVGElementInstanceList:!1,SVGEllipseElement:!1,SVGEvent:!1,SVGExternalResourcesRequired:!1,SVGFEBlendElement:!1,SVGFEColorMatrixElement:!1,SVGFEComponentTransferElement:!1,SVGFECompositeElement:!1,SVGFEConvolveMatrixElement:!1,SVGFEDiffuseLightingElement:!1,SVGFEDisplacementMapElement:!1,SVGFEDistantLightElement:!1,SVGFEDropShadowElement:!1,SVGFEFloodElement:!1,SVGFEFuncAElement:!1,SVGFEFuncBElement:!1,SVGFEFuncGElement:!1,SVGFEFuncRElement:!1,SVGFEGaussianBlurElement:!1,SVGFEImageElement:!1,SVGFEMergeElement:!1,SVGFEMergeNodeElement:!1,SVGFEMorphologyElement:!1,SVGFEOffsetElement:!1,SVGFEPointLightElement:!1,SVGFESpecularLightingElement:!1,SVGFESpotLightElement:!1,SVGFETileElement:!1,SVGFETurbulenceElement:!1,SVGFilterElement:!1,SVGFilterPrimitiveStandardAttributes:!1,SVGFitToViewBox:!1,SVGFontElement:!1,SVGFontFaceElement:!1,SVGFontFaceFormatElement:!1,SVGFontFaceNameElement:!1,SVGFontFaceSrcElement:!1,SVGFontFaceUriElement:!1,SVGForeignObjectElement:!1,SVGGElement:!1,SVGGeometryElement:!1,SVGGlyphElement:!1,SVGGlyphRefElement:!1,SVGGradientElement:!1,SVGGraphicsElement:!1,SVGHKernElement:!1,SVGICCColor:!1,SVGImageElement:!1,SVGLangSpace:!1,SVGLength:!1,SVGLengthList:!1,SVGLinearGradientElement:!1,SVGLineElement:!1,SVGLocatable:!1,SVGMarkerElement:!1,SVGMaskElement:!1,SVGMatrix:!1,SVGMetadataElement:!1,SVGMissingGlyphElement:!1,SVGMPathElement:!1,SVGNumber:!1,SVGNumberList:!1,SVGPaint:!1,SVGPathElement:!1,SVGPathSeg:!1,SVGPathSegArcAbs:!1,SVGPathSegArcRel:!1,SVGPathSegClosePath:!1,SVGPathSegCurvetoCubicAbs:!1,SVGPathSegCurvetoCubicRel:!1,SVGPathSegCurvetoCubicSmoothAbs:!1,SVGPathSegCurvetoCubicSmoothRel:!1,SVGPathSegCurvetoQuadraticAbs:!1,SVGPathSegCurvetoQuadraticRel:!1,SVGPathSegCurvetoQuadraticSmoothAbs:!1,SVGPathSegCurvetoQuadraticSmoothRel:!1,SVGPathSegLinetoAbs:!1,SVGPathSegLinetoHorizontalAbs:!1,SVGPathSegLinetoHorizontalRel:!1,SVGPathSegLinetoRel:!1,SVGPathSegLinetoVerticalAbs:!1,SVGPathSegLinetoVerticalRel:!1,SVGPathSegList:!1,SVGPathSegMovetoAbs:!1,SVGPathSegMovetoRel:!1,SVGPatternElement:!1,SVGPoint:!1,SVGPointList:!1,SVGPolygonElement:!1,SVGPolylineElement:!1,SVGPreserveAspectRatio:!1,SVGRadialGradientElement:!1,SVGRect:!1,SVGRectElement:!1,SVGRenderingIntent:!1,SVGScriptElement:!1,SVGSetElement:!1,SVGStopElement:!1,SVGStringList:!1,SVGStylable:!1,SVGStyleElement:!1,SVGSVGElement:!1,SVGSwitchElement:!1,SVGSymbolElement:!1,SVGTests:!1,SVGTextContentElement:!1,SVGTextElement:!1,SVGTextPathElement:!1,SVGTextPositioningElement:!1,SVGTitleElement:!1,SVGTransform:!1,SVGTransformable:!1,SVGTransformList:!1,SVGTRefElement:!1,SVGTSpanElement:!1,SVGUnitTypes:!1,SVGURIReference:!1,SVGUseElement:!1,SVGViewElement:!1,SVGViewSpec:!1,SVGVKernElement:!1,SVGZoomAndPan:!1,SVGZoomEvent:!1,Text:!1,TextDecoder:!1,TextEncoder:!1,TextEvent:!1,TextMetrics:!1,TextTrack:!1,TextTrackCue:!1,TextTrackCueList:!1,TextTrackList:!1,TimeEvent:!1,TimeRanges:!1,toolbar:!1,top:!1,Touch:!1,TouchEvent:!1,TouchList:!1,TrackEvent:!1,TransitionEvent:!1,TreeWalker:!1,UIEvent:!1,URL:!1,URLSearchParams:!1,ValidityState:!1,VTTCue:!1,WaveShaperNode:!1,WebGLActiveInfo:!1,WebGLBuffer:!1,WebGLContextEvent:!1,WebGLFramebuffer:!1,WebGLProgram:!1,WebGLRenderbuffer:!1,WebGLRenderingContext:!1,WebGLShader:!1,WebGLShaderPrecisionFormat:!1,WebGLTexture:!1,WebGLUniformLocation:!1,WebSocket:!1,WheelEvent:!1,window:!1,Window:!1,Worker:!1,XDomainRequest:!1,XMLDocument:!1,XMLHttpRequest:!1,XMLHttpRequestEventTarget:!1,XMLHttpRequestProgressEvent:!1,XMLHttpRequestUpload:!1,XMLSerializer:!1,XPathEvaluator:!1,XPathException:!1,XPathExpression:!1,XPathNamespace:!1,XPathNSResolver:!1,XPathResult:!1,XSLTProcessor:!1},worker:{applicationCache:!1,atob:!1,Blob:!1,BroadcastChannel:!1,btoa:!1,Cache:!1,caches:!1,clearInterval:!1,clearTimeout:!1,close:!0,console:!1,fetch:!1,FileReaderSync:!1,FormData:!1,Headers:!1,IDBCursor:!1,IDBCursorWithValue:!1,IDBDatabase:!1,IDBFactory:!1,IDBIndex:!1,IDBKeyRange:!1,IDBObjectStore:!1,IDBOpenDBRequest:!1,IDBRequest:!1,IDBTransaction:!1,IDBVersionChangeEvent:!1,ImageData:!1,importScripts:!0,indexedDB:!1,location:!1,MessageChannel:!1,MessagePort:!1,name:!1,navigator:!1,Notification:!1,onclose:!0,onconnect:!0,onerror:!0,onlanguagechange:!0,onmessage:!0,onoffline:!0,ononline:!0,onrejectionhandled:!0,onunhandledrejection:!0,performance:!1,Performance:!1,PerformanceEntry:!1,PerformanceMark:!1,PerformanceMeasure:!1,PerformanceNavigation:!1,PerformanceResourceTiming:!1,PerformanceTiming:!1,postMessage:!0,Promise:!1,Request:!1,Response:!1,self:!0,ServiceWorkerRegistration:!1,setInterval:!1,setTimeout:!1,TextDecoder:!1,TextEncoder:!1,URL:!1,URLSearchParams:!1,WebSocket:!1,Worker:!1,XMLHttpRequest:!1},node:{__dirname:!1,__filename:!1,arguments:!1,Buffer:!1,clearImmediate:!1,clearInterval:!1,clearTimeout:!1,console:!1,exports:!0,GLOBAL:!1,global:!1,Intl:!1,module:!1,process:!1,require:!1,root:!1,setImmediate:!1,setInterval:!1,setTimeout:!1},commonjs:{exports:!0,module:!1,require:!1,global:!1},amd:{define:!1,require:!1},mocha:{after:!1,afterEach:!1,before:!1,beforeEach:!1,context:!1,describe:!1,it:!1,mocha:!1,run:!1,setup:!1,specify:!1,suite:!1,suiteSetup:!1,suiteTeardown:!1,teardown:!1,test:!1,xcontext:!1,xdescribe:!1,xit:!1,xspecify:!1},jasmine:{afterAll:!1,afterEach:!1,beforeAll:!1,beforeEach:!1,describe:!1,expect:!1,fail:!1,fdescribe:!1,fit:!1,it:!1,jasmine:!1,pending:!1,runs:!1,spyOn:!1,spyOnProperty:!1,waits:!1,waitsFor:!1,xdescribe:!1,xit:!1},jest:{afterAll:!1,afterEach:!1,beforeAll:!1,beforeEach:!1,check:!1,describe:!1,expect:!1,gen:!1,it:!1,fdescribe:!1,fit:!1,jest:!1,pit:!1,require:!1,test:!1,xdescribe:!1,xit:!1,xtest:!1},qunit:{asyncTest:!1,deepEqual:!1,equal:!1,expect:!1,module:!1,notDeepEqual:!1,notEqual:!1,notOk:!1,notPropEqual:!1,notStrictEqual:!1,ok:!1,propEqual:!1,QUnit:!1,raises:!1,start:!1,stop:!1,strictEqual:!1,test:!1,throws:!1},phantomjs:{console:!0,exports:!0,phantom:!0,require:!0,WebPage:!0},couch:{emit:!1,exports:!1,getRow:!1,log:!1,module:!1,provides:!1,require:!1,respond:!1,send:!1,start:!1,sum:!1},rhino:{defineClass:!1,deserialize:!1,gc:!1,help:!1,importClass:!1,importPackage:!1,java:!1,load:!1,loadClass:!1,Packages:!1,print:!1,quit:!1,readFile:!1,readUrl:!1,runCommand:!1,seal:!1,serialize:!1,spawn:!1,sync:!1,toint32:!1,version:!1},nashorn:{__DIR__:!1,__FILE__:!1,__LINE__:!1,com:!1,edu:!1,exit:!1,Java:!1,java:!1,javafx:!1,JavaImporter:!1,javax:!1,JSAdapter:!1,load:!1,loadWithNewGlobal:!1,org:!1,Packages:!1,print:!1,quit:!1},wsh:{ActiveXObject:!0,Enumerator:!0,GetObject:!0,ScriptEngine:!0,ScriptEngineBuildVersion:!0,ScriptEngineMajorVersion:!0,ScriptEngineMinorVersion:!0,VBArray:!0,WScript:!0,WSH:!0,XDomainRequest:!0},jquery:{$:!1,jQuery:!1},yui:{Y:!1,YUI:!1,YUI_config:!1},shelljs:{cat:!1,cd:!1,chmod:!1,config:!1,cp:!1,dirs:!1,echo:!1,env:!1,error:!1,exec:!1,exit:!1,find:!1,grep:!1,ls:!1,ln:!1,mkdir:!1,mv:!1,popd:!1,pushd:!1,pwd:!1,rm:!1,sed:!1,set:!1,target:!1,tempdir:!1,test:!1,touch:!1,which:!1},prototypejs:{$:!1,$$:!1,$A:!1,$break:!1,$continue:!1,$F:!1,$H:!1,$R:!1,$w:!1,Abstract:!1,Ajax:!1,Autocompleter:!1,Builder:!1,Class:!1,Control:!1,Draggable:!1,Draggables:!1,Droppables:!1,Effect:!1,Element:!1,Enumerable:!1,Event:!1,Field:!1,Form:!1,Hash:!1,Insertion:!1,ObjectRange:!1,PeriodicalExecuter:!1,Position:!1,Prototype:!1,Scriptaculous:!1,Selector:!1,Sortable:!1,SortableObserver:!1,Sound:!1,Template:!1,Toggle:!1,Try:!1},meteor:{$:!1,_:!1,Accounts:!1,AccountsClient:!1,AccountsServer:!1,AccountsCommon:!1,App:!1,Assets:!1,Blaze:!1,check:!1,Cordova:!1,DDP:!1,DDPServer:!1,DDPRateLimiter:!1,Deps:!1,EJSON:!1,Email:!1,HTTP:!1,Log:!1,Match:!1,Meteor:!1,Mongo:!1,MongoInternals:!1,Npm:!1,Package:!1,Plugin:!1,process:!1,Random:!1,ReactiveDict:!1,ReactiveVar:!1,Router:!1,ServiceConfiguration:!1,Session:!1,share:!1,Spacebars:!1,Template:!1,Tinytest:!1,Tracker:!1,UI:!1,Utils:!1,WebApp:!1,WebAppInternals:!1},mongo:{_isWindows:!1,_rand:!1,BulkWriteResult:!1,cat:!1,cd:!1,connect:!1,db:!1,getHostName:!1,getMemInfo:!1,hostname:!1,ISODate:!1,listFiles:!1,load:!1,ls:!1,md5sumFile:!1,mkdir:!1,Mongo:!1,NumberInt:!1,NumberLong:!1,ObjectId:!1,PlanCache:!1,print:!1,printjson:!1,pwd:!1,quit:!1,removeFile:!1,rs:!1,sh:!1,UUID:!1,version:!1,WriteResult:!1},applescript:{$:!1,Application:!1,Automation:!1,console:!1,delay:!1,Library:!1,ObjC:!1,ObjectSpecifier:!1,Path:!1,Progress:!1,Ref:!1},serviceworker:{caches:!1,Cache:!1,CacheStorage:!1,Client:!1,clients:!1,Clients:!1,ExtendableEvent:!1,ExtendableMessageEvent:!1,FetchEvent:!1,importScripts:!1,registration:!1,self:!1,ServiceWorker:!1,ServiceWorkerContainer:!1,ServiceWorkerGlobalScope:!1,ServiceWorkerMessageEvent:!1,ServiceWorkerRegistration:!1,skipWaiting:!1,WindowClient:!1},atomtest:{advanceClock:!1,fakeClearInterval:!1,fakeClearTimeout:!1,fakeSetInterval:!1,fakeSetTimeout:!1,resetTimeouts:!1,waitsForPromise:!1},embertest:{andThen:!1,click:!1,currentPath:!1,currentRouteName:!1,currentURL:!1,fillIn:!1,find:!1,findWithAssert:!1,keyEvent:!1,pauseTest:!1,resumeTest:!1,triggerEvent:!1,visit:!1},protractor:{$:!1,$$:!1,browser:!1,By:!1,by:!1,DartObject:!1,element:!1,protractor:!1},"shared-node-browser":{clearInterval:!1,clearTimeout:!1,console:!1,setInterval:!1,setTimeout:!1},webextensions:{browser:!1,chrome:!1,opr:!1},greasemonkey:{GM_addStyle:!1,GM_deleteValue:!1,GM_getResourceText:!1,GM_getResourceURL:!1,GM_getValue:!1,GM_info:!1,GM_listValues:!1,GM_log:!1,GM_openInTab:!1,GM_registerMenuCommand:!1,GM_setClipboard:!1,GM_setValue:!1,GM_xmlhttpRequest:!1,unsafeWindow:!1}}},function(e,t){e.exports={75:8490,83:383,107:8490,115:383,181:924,197:8491,383:83,452:453,453:452,455:456,456:455,458:459,459:458,497:498,498:497,837:8126,914:976,917:1013,920:1012,921:8126,922:1008,924:181,928:982,929:1009,931:962,934:981,937:8486,962:931,976:914,977:1012,981:934,982:928,1008:922,1009:929,1012:[920,977],1013:917,7776:7835,7835:7776,8126:[837,921],8486:937,8490:75,8491:197,66560:66600,66561:66601,66562:66602,66563:66603,66564:66604,66565:66605,66566:66606,66567:66607,66568:66608,66569:66609,66570:66610,66571:66611,66572:66612,66573:66613,66574:66614,66575:66615,66576:66616,66577:66617,66578:66618,66579:66619,66580:66620,66581:66621,66582:66622,66583:66623,66584:66624,66585:66625,66586:66626,66587:66627,66588:66628,66589:66629,66590:66630,66591:66631,66592:66632,66593:66633,66594:66634,66595:66635,66596:66636,66597:66637,66598:66638,66599:66639,66600:66560,66601:66561,66602:66562,66603:66563,66604:66564,66605:66565,66606:66566,66607:66567,66608:66568,66609:66569,66610:66570,66611:66571,66612:66572,66613:66573,66614:66574,66615:66575,66616:66576,66617:66577,66618:66578,66619:66579,66620:66580,66621:66581,66622:66582,66623:66583,66624:66584,66625:66585,66626:66586,66627:66587,66628:66588,66629:66589,66630:66590,66631:66591,66632:66592,66633:66593,66634:66594,66635:66595,66636:66596,66637:66597,66638:66598,66639:66599,68736:68800,68737:68801,68738:68802,68739:68803,68740:68804,68741:68805,68742:68806,68743:68807,68744:68808,68745:68809,68746:68810,68747:68811,68748:68812,68749:68813,68750:68814,68751:68815,68752:68816,68753:68817,68754:68818,68755:68819,68756:68820,68757:68821,68758:68822,68759:68823,68760:68824,68761:68825,68762:68826,68763:68827,68764:68828,68765:68829,68766:68830,68767:68831,68768:68832,68769:68833,68770:68834,68771:68835,68772:68836,68773:68837,68774:68838,68775:68839,68776:68840,68777:68841,68778:68842,68779:68843,68780:68844,68781:68845,68782:68846,68783:68847,68784:68848,68785:68849,68786:68850,68800:68736,68801:68737,68802:68738,68803:68739,68804:68740,68805:68741,68806:68742,68807:68743,68808:68744,68809:68745,68810:68746,68811:68747,68812:68748,68813:68749,68814:68750,68815:68751,68816:68752,68817:68753,68818:68754,68819:68755,68820:68756,68821:68757,68822:68758,68823:68759,68824:68760,68825:68761,68826:68762,68827:68763,68828:68764,68829:68765,68830:68766,68831:68767,68832:68768,68833:68769,68834:68770,68835:68771,68836:68772,68837:68773,68838:68774,68839:68775,68840:68776,68841:68777,68842:68778,68843:68779,68844:68780,68845:68781,68846:68782,68847:68783,68848:68784,68849:68785,68850:68786,71840:71872,71841:71873,71842:71874,71843:71875,71844:71876,71845:71877,71846:71878,71847:71879,71848:71880,71849:71881,71850:71882,71851:71883,71852:71884,71853:71885,71854:71886,71855:71887,71856:71888,71857:71889,71858:71890,71859:71891,71860:71892,71861:71893,71862:71894,71863:71895,71864:71896,71865:71897,71866:71898,71867:71899,71868:71900,71869:71901,71870:71902,71871:71903,71872:71840,71873:71841,71874:71842,71875:71843,71876:71844,71877:71845,71878:71846,71879:71847,71880:71848,71881:71849,71882:71850,71883:71851,71884:71852,71885:71853,71886:71854,71887:71855,71888:71856,71889:71857,71890:71858,71891:71859,71892:71860,71893:71861,71894:71862,71895:71863,71896:71864,71897:71865,71898:71866,71899:71867,71900:71868,71901:71869,71902:71870,71903:71871}}]))});
gungameprogressive
gungametrbomb
weapon_
ignore_weapon_size_scale
weapon_case_key
file://{images}/econ/weapon_cases/crate_%s.png
file://{images}/econ/weapon_cases/crate_musickit_%s_capsule.png
file://{images}/econ/weapon_cases/crate_musickit_%s_stattrak_capsule.png
weapon_ak47
PaintKit_Gunsmith
Gunsmith
PaintKit_GunsmithExtended
Gunsmith Extended
PaintKit_GunsmithCaseHardening
Gunsmith Case Hardening
file://{images}/econ/weapon_cases/crate_sticker_pack_%s.png
weapon_knife
weapon_case
preview_weapon_loc_token
?drawPath@QPainter@@QEAAXAEBVQPainterPath@@@Z
?drawPolygon@QPainter@@QEAAXAEBVQPolygon@@W4FillRule@Qt@@@Z
?drawPixmap@QPainter@@QEAAXHHHHAEBVQPixmap@@@Z
?drawPixmap@QPainter@@QEAAXAEBVQRect@@AEBVQPixmap@@@Z
#SFUI_WPNHUD_AK47
#SFUI_WPNHUD_AWP
#SFUI_WPNHUD_M4A1_silencer
M4A1-S
#SFUI_WPNHUD_M4A1
Sawed-Off Shotgun
preview_weapon_loc_token
?drawPixmap@QPainter@@QEAAXAEBVQRectF@@AEBVQPixmap@@0@Z
drawPoints
MeshDrawPrimitiveFlags_t
DebugUnlockZoom
MappingUnwrapQuads
MappingUnwrapSquare
MappingUnwrapConforming
?drawPixmap@QPainter@@QEAAXHHHHAEBVQPixmap@@@Z
... and 116 more
```
#### maps
```
m_AssetType = "map_asset"
m_FixType = "VMAP_MANUAL_RECOMPILE"
physics_collision = 
m_IconLg = "game:tools/images/assettypes/physics_lg.png"
m_IconSm = "game:tools/images/assettypes/physics_sm.png"
worldnode_asset = 
resource_remap_table = 
map_asset = 
m_IconLg = "game:tools/images/assettypes/map_lg.png"
m_IconSm = "game:tools/images/assettypes/map_sm.png"
m_IconLg = "game:tools/images/assettypes/speech_graphics_lg.png"
m_IconSm = "game:tools/images/assettypes/speech_graphics_sm.png"
"map_asset",
??5oidn@@YAAEAV?$basic_istream@DU?$char_traits@D@std@@@std@@AEAV12@AEAW4DeviceType@0@@Z
?load@ModuleLoader@oidn@@QEAA_NAEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@Z
?newFilter@Device@oidn@@QEAA?AV?$Ref@VFilter@oidn@@@2@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@Z
?setError@Device@oidn@@SAXPEAV12@W4Error@2@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@Z
??0?$basic_streambuf@DU?$char_traits@D@std@@@std@@IEAA@XZ
??1?$basic_streambuf@DU?$char_traits@D@std@@@std@@UEAA@XZ
??5?$basic_istream@DU?$char_traits@D@std@@@std@@QEAAAEAV01@AEAH@Z
?_Lock@?$basic_streambuf@DU?$char_traits@D@std@@@std@@UEAAXXZ
?_Unlock@?$basic_streambuf@DU?$char_traits@D@std@@@std@@UEAAXXZ
?imbue@?$basic_streambuf@DU?$char_traits@D@std@@@std@@MEAAXAEBVlocale@2@@Z
?init@?$basic_ios@DU?$char_traits@D@std@@@std@@IEAAXPEAV?$basic_streambuf@DU?$char_traits@D@std@@@2@_N@Z
?setbuf@?$basic_streambuf@DU?$char_traits@D@std@@@std@@MEAAPEAV12@PEAD_J@Z
?showmanyc@?$basic_streambuf@DU?$char_traits@D@std@@@std@@MEAA_JXZ
?sync@?$basic_streambuf@DU?$char_traits@D@std@@@std@@MEAAHXZ
?uflow@?$basic_streambuf@DU?$char_traits@D@std@@@std@@MEAAHXZ
?xsgetn@?$basic_streambuf@DU?$char_traits@D@std@@@std@@MEAA_JPEAD_J@Z
?xsputn@?$basic_streambuf@DU?$char_traits@D@std@@@std@@MEAA_JPEBD_J@Z
.?AV?$_Ref_count_obj2@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@std@@
.?AV?$basic_stringstream@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@
.?AV?$basic_iostream@DU?$char_traits@D@std@@@std@@
.?AV?$basic_istream@DU?$char_traits@D@std@@@std@@
.?AV?$basic_ios@DU?$char_traits@D@std@@@std@@
.?AV?$basic_ostream@DU?$char_traits@D@std@@@std@@
.?AV?$basic_stringbuf@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@
.?AV?$basic_streambuf@DU?$char_traits@D@std@@@std@@
         <requestedExecutionLevel level='asInvoker' uiAccess='false'/>
??$?0AEAV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAV?$Ref@VHostTensor@oidn@@@oidn@@@?$_List_node_emplace_op2@V?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@@std@@@std@@QEAA@AEAV?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@@1@AEAV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@1@AEAV?$Ref@VHostTensor@oidn@@@oidn@@@Z
??$?0AEBUpiecewise_construct_t@std@@V?$tuple@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@1@V?$tuple@$$V@1@@?$_List_node_emplace_op2@V?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@@std@@@std@@QEAA@AEAV?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@@1@AEBUpiecewise_construct_t@1@$$QEAV?$tuple@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@1@$$QEAV?$tuple@$$V@1@@Z
??$?0AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@?$_List_node_emplace_op2@V?$allocator@U?$_List_node@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@PEAX@std@@@std@@@std@@QEAA@AEAV?$allocator@U?$_List_node@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@PEAX@std@@@1@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@1@@Z
??$?0V?$tuple@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@std@@V?$tuple@$$V@1@$0A@$$Z$S@?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@@std@@QEAA@AEAV?$tuple@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@1@AEAV?$tuple@$$V@1@U?$integer_sequence@_K$0A@@1@U?$integer_sequence@_K$S@1@@Z
??$?5DU?$char_traits@D@std@@V?$allocator@D@1@@std@@YAAEAV?$basic_istream@DU?$char_traits@D@std@@@0@AEAV10@AEAV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@0@@Z
??$?6U?$char_traits@D@std@@@std@@YAAEAV?$basic_ostream@DU?$char_traits@D@std@@@0@AEAV10@PEBD@Z
??$?8DU?$char_traits@D@std@@V?$allocator@D@1@@std@@YA_NAEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@0@QEBD@Z
??$?HDU?$char_traits@D@std@@V?$allocator@D@1@@std@@YA?AV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@0@$$QEAV10@QEBD@Z
??$?HDU?$char_traits@D@std@@V?$allocator@D@1@@std@@YA?AV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@0@QEBD$$QEAV10@@Z
??$?HDU?$char_traits@D@std@@V?$allocator@D@1@@std@@YA?AV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@0@QEBDAEBV10@@Z
??$_Free_non_head@V?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@@std@@@?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@SAXAEAV?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@@1@PEAU01@@Z
??$_Getvals@_W@?$time_get@DV?$istreambuf_iterator@DU?$char_traits@D@std@@@std@@@std@@IEAAX_WAEBV_Locinfo@1@@Z
??$_Getvals@_W@?$time_get@_WV?$istreambuf_iterator@_WU?$char_traits@_W@std@@@std@@@std@@IEAAX_WAEBV_Locinfo@1@@Z
??$_Insert_string@DU?$char_traits@D@std@@_K@std@@YAAEAV?$basic_ostream@DU?$char_traits@D@std@@@0@AEAV10@QEBD_K@Z
??$_Reallocate_for@V<lambda_1>@?0??assign@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@QEAAAEAV34@QEBD_K@Z@PEBD@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAAAEAV01@_KV<lambda_1>@?0??assign@01@QEAAAEAV01@QEBD0@Z@PEBD@Z
??$_Reallocate_grow_by@V<lambda_1>@?0??append@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@QEAAAEAV34@QEBD_K@Z@PEBD_K@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAAAEAV01@_KV<lambda_1>@?0??append@01@QEAAAEAV01@QEBD0@Z@PEBD_K@Z
??$_Reallocate_grow_by@V<lambda_1>@?0??insert@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@QEAAAEAV34@_KQEBD0@Z@_KPEBD_K@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAAAEAV01@_KV<lambda_1>@?0??insert@01@QEAAAEAV01@0QEBD0@Z@_KPEBD3@Z
??$_Reallocate_grow_by@V<lambda_1>@?0??insert@?$basic_string@_WU?$char_traits@_W@std@@V?$allocator@_W@2@@std@@QEAAAEAV34@_KQEB_W0@Z@_KPEB_W_K@?$basic_string@_WU?$char_traits@_W@std@@V?$allocator@_W@2@@std@@AEAAAEAV01@_KV<lambda_1>@?0??insert@01@QEAAAEAV01@0QEB_W0@Z@_KPEB_W3@Z
??$_Reallocate_grow_by@V<lambda_1>@?0??push_back@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@QEAAXD@Z@D@?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAAAEAV01@_KV<lambda_1>@?0??push_back@01@QEAAXD@Z@D@Z
??$_Try_emplace@AEBQEBX$$V@?$_Hash@V?$_Umap_traits@PEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@V?$_Uhash_compare@PEBXU?$hash@PEBX@std@@U?$equal_to@PEBX@2@@2@V?$allocator@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@@2@$0A@@std@@@std@@IEAA?AU?$pair@PEAU?$_List_node@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@PEAX@std@@_N@1@AEBQEBX@Z
??$_Try_emplace@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@$$V@?$_Hash@V?$_Umap_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@@std@@@2@$0A@@std@@@std@@IEAA?AU?$pair@PEAU?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@@std@@PEAX@std@@_N@1@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@1@@Z
??$_Try_emplace@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@$$V@?$_Hash@V?$_Umap_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@$0A@@std@@@std@@IEAA?AU?$pair@PEAU?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@_N@1@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@1@@Z
??$emplace@AEAV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAV?$Ref@VHostTensor@oidn@@@oidn@@@?$_Hash@V?$_Umap_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@$0A@@std@@@std@@QEAA?AU?$pair@V?$_List_iterator@V?$_List_val@U?$_List_simple_types@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@std@@@std@@@std@@_N@1@AEAV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@1@AEAV?$Ref@VHostTensor@oidn@@@oidn@@@Z
??$emplace@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@?$_Hash@V?$_Uset_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@$0A@@std@@@std@@QEAA?AU?$pair@V?$_List_const_iterator@V?$_List_val@U?$_List_simple_types@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@std@@@std@@@std@@_N@1@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@1@@Z
??$fromString@H@oidn@@YAHAEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@Z
??$getEnvVar@H@oidn@@YA_NAEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAH@Z
??$make_shared@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEAPEBD@std@@YA?AV?$shared_ptr@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@0@AEAPEBD@Z
??$make_shared@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEBV12@@std@@YA?AV?$shared_ptr@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@0@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@0@@Z
??$toString@H@oidn@@YA?AV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEBH@Z
??$toString@W4DeviceType@oidn@@@oidn@@YA?AV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@AEBW4DeviceType@0@@Z
??0?$_Hash@V?$_Umap_traits@PEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@V?$_Uhash_compare@PEBXU?$hash@PEBX@std@@U?$equal_to@PEBX@2@@2@V?$allocator@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@@2@$0A@@std@@@std@@IEAA@AEBV?$_Uhash_compare@PEBXU?$hash@PEBX@std@@U?$equal_to@PEBX@2@@1@AEBV?$allocator@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@@1@@Z
??0?$_Hash@V?$_Umap_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@@std@@@2@$0A@@std@@@std@@IEAA@AEBV?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@1@AEBV?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@@std@@@1@@Z
??0?$_Hash@V?$_Umap_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@$0A@@std@@@std@@IEAA@AEBV?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@1@AEBV?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@1@@Z
??0?$_Hash@V?$_Uset_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@$0A@@std@@@std@@IEAA@AEBV?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@1@AEBV?$allocator@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@1@@Z
??0?$basic_stringstream@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@QEAA@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@1@H@Z
??0?$basic_stringstream@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@QEAA@XZ
??0Exception@oidn@@QEAA@W4Error@1@AEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@Z
??0Graph@oidn@@QEAA@PEAVEngine@1@AEBV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@1_N@Z
??0ScratchArena@oidn@@QEAA@PEAVScratchArenaManager@1@_KAEBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@Z
??1?$_Hash@V?$_Umap_traits@PEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@V?$_Uhash_compare@PEBXU?$hash@PEBX@std@@U?$equal_to@PEBX@2@@2@V?$allocator@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@@2@$0A@@std@@@std@@QEAA@XZ
??1?$_Hash@V?$_Uset_traits@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$_Uhash_compare@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@@2@V?$allocator@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@$0A@@std@@@std@@QEAA@XZ
??1?$_Hash_vec@V?$allocator@V?$_List_unchecked_const_iterator@V?$_List_val@U?$_List_simple_types@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@std@@@std@@U_Iterator_base0@2@@std@@@std@@@std@@QEAA@XZ
??1?$_Hash_vec@V?$allocator@V?$_List_unchecked_iterator@V?$_List_val@U?$_List_simple_types@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@@std@@@std@@@std@@@std@@@std@@@std@@QEAA@XZ
??1?$_Hash_vec@V?$allocator@V?$_List_unchecked_iterator@V?$_List_val@U?$_List_simple_types@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@std@@@std@@@std@@@std@@@std@@QEAA@XZ
??1?$_Hash_vec@V?$allocator@V?$_List_unchecked_iterator@V?$_List_val@U?$_List_simple_types@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@@std@@@std@@@std@@@std@@@std@@QEAA@XZ
??1?$_List_node_emplace_op2@V?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@UAlloc@ScratchArenaManager@oidn@@@std@@PEAX@std@@@std@@@std@@QEAA@XZ
??1?$_List_node_emplace_op2@V?$allocator@U?$_List_node@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@PEAX@std@@@std@@@std@@QEAA@XZ
??1?$_List_node_emplace_op2@V?$allocator@U?$_List_node@U?$pair@QEAVOp@oidn@@V?$shared_ptr@UTensorAlloc@Graph@oidn@@@std@@@std@@PEAX@std@@@std@@@std@@QEAA@XZ
??1?$_List_node_emplace_op2@V?$allocator@U?$_List_node@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@PEAX@std@@@std@@@std@@QEAA@XZ
??1?$_List_node_emplace_op2@V?$allocator@U?$_List_node@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@PEAX@std@@@std@@@std@@QEAA@XZ
??1?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@QEAA@XZ
??1?$basic_string@_WU?$char_traits@_W@std@@V?$allocator@_W@2@@std@@QEAA@XZ
??1?$list@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@QEAA@XZ
??1?$list@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@V?$allocator@U?$pair@QEBXV?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@@std@@@2@@std@@QEAA@XZ
??1?$shared_ptr@V?$unordered_map@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@U?$hash@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@U?$equal_to@V?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@@2@V?$allocator@U?$pair@$$CBV?$basic_string@DU?$char_traits@D@std@@V?$allocator@D@2@@std@@V?$Ref@VTensor@oidn@@@oidn@@@std@@@2@@std@@@std@@QEAA@XZ
??1_Sentry_base@?$basic_istream@DU?$char_traits@D@std@@@std@@QEAA@XZ
??1_Sentry_base@?$basic_ostream@DU?$char_traits@D@std@@@std@@QEAA@XZ
??1sentry@?$basic_ostream@DU?$char_traits@D@std@@@std@@QEAA@XZ
??5oidn@@YAAEAV?$basic_istream@DU?$char_traits@D@std@@@std@@AEAV12@AEAW4DeviceType@0@@Z
??6oidn@@YAAEAV?$basic_ostream@DU?$char_traits@D@std@@@std@@AEAV12@AEBULUID@0@@Z
??6oidn@@YAAEAV?$basic_ostream@DU?$char_traits@D@std@@@std@@AEAV12@AEBUUUID@0@@Z
... and 7427 more
```
#### items
```
m_IconLg = "game:tools/images/assettypes/cs2_econ_item_lg.png"
m_IconSm = "game:tools/images/assettypes/cs2_econ_item_sm.png"
m_Name = "cs2_item_editor"
m_Library = "tools/cs2_item_editor.dll"
m_ToolIcon = "game:tools/cs2_item_editor/appicon.png"
  Tasking   :
darkmagenta
magenta
graphcanvas_hover_item_info
graphcanvas_cache_item_pixmap
LayoutState_t::PARTIAL (LayoutSystem_HideItem_R)
HANDLED in LayoutSystem_HideItem_R
C:\buildworker\csgo_rel_win64\build\src\qcontrols\graphcanvas_item_text.cpp
CUtlDict<struct CQInputBindEditor::BindingContextInfo_t *,class CDefFastCaselessStringLess>::Insert
C:\buildworker\csgo_rel_win64\build\src\qcontrols\graphcanvas_item_simpletooltip.cpp
??0QRegExp@@QEAA@AEBVQString@@W4CaseSensitivity@Qt@@W4PatternSyntax@0@@Z
?compare@QString@@QEBAHAEBV1@W4CaseSensitivity@Qt@@@Z
?replace@QString@@QEAAAEAV1@AEBV1@0W4CaseSensitivity@Qt@@@Z
?indexOf@QString@@QEBAHAEBV1@HW4CaseSensitivity@Qt@@@Z
?filterCaseSensitivity@QSortFilterProxyModel@@QEBA?AW4CaseSensitivity@Qt@@XZ
?setFilterCaseSensitivity@QSortFilterProxyModel@@QEAAXW4CaseSensitivity@Qt@@@Z
?startsWith@QString@@QEBA_NAEBV1@W4CaseSensitivity@Qt@@@Z
?endsWith@QString@@QEBA_NVQChar@@W4CaseSensitivity@Qt@@@Z
?dragEnterEvent@QWidget@@MEAAXPEAVQDragEnterEvent@@@Z
?dragEnterEvent@QLineEdit@@MEAAXPEAVQDragEnterEvent@@@Z
?dragEnterEvent@QAbstractItemView@@MEAAXPEAVQDragEnterEvent@@@Z
?dragEnterEvent@QAbstractScrollArea@@MEAAXPEAVQDragEnterEvent@@@Z
?setCaseSensitivity@QCompleter@@QEAAXW4CaseSensitivity@Qt@@@Z
?dragEnterEvent@QPlainTextEdit@@MEAAXPEAVQDragEnterEvent@@@Z
?dragEnterEvent@QTextEdit@@MEAAXPEAVQDragEnterEvent@@@Z
?IsEqual_FastCaseInsensitive@CUtlString@@QEBA_NPEBD@Z
_MakeGlobalSymbolCaseSensitive
_V_StringAfterPrefixCaseSensitive
?indexOf@QString@@QEBAHVQChar@@HW4CaseSensitivity@Qt@@@Z
?QStringList_sort@QtPrivate@@YAXPEAVQStringList@@W4CaseSensitivity@Qt@@@Z
?IsEqual_CaseSensitive@CUtlString@@QEBA_NPEBD@Z
.?AVCGraphCanvasItem_Curve@@
.?AVCGraphCanvasItem_TooltipAnchor@@
.?AVCGraphCanvasItem_SimpleTooltip@@
.?AVCAssetGraphItem_Port@@
.?AVCGraphCanvasItem_Image@@
.?AVCGraphCanvasItem_Text@@
Reached impossible case in HasBit().
The JSON camel-case name of field "
m_nBoneMaskIndex
BlendItem_t
CUtlDict<class IParamLookupHelper const *,class CDefFastCaselessStringLess>::Insert
CUtlDict<class CDmElementFactoryHelper *,class CDefFastCaselessStringLess>::Insert
CUtlDict<class CDmElement *,class CDefFastCaselessStringLess>::Insert
item_item_crate
CUtlDict<class CMapEntity *,class CDefFastCaselessStringLess>::Insert
ComputeShaderSkinning
SceneSystem/ComputeShaderSkinning
A list of mutually-exclusive materials (skins) that the game can dynamically select between.
If set, considers failure cases to be errors. Failures are warnings by default.
<th align="left">Removes any bones which are not skinned or referenced</th>
<th align="left">Removes any bones which are not skinned or referenced that have no children</th>
skin_parented_transforms
Skin Parented Transforms
skin_to_bones
cull_unskinned_verts
skin_threshold
multibone_skinning
Skin To Bones
Cull Unskinned Verts
+Skinning Options
Skin Threshold
Multi-Bone Skinning
CModelDocMeshModifier_SkinToSingleBone
Discards all skeleton information (bones and vertex skinning data) from the parent node
RemoveUnskinnedBones
tools/images/modeldoc_editor/outliner_icon_removeunskinnedbones.png
Removes all bones from the parent node that do not have any verticies skinned to them
LowercaseBoneNames
tools/images/modeldoc_editor/outliner_icon_lowercasebonenames.png
Renames all bone names to lowercase versions of themselves
SkinToSingleBone
tools/images/modeldoc_editor/outliner_icon_skin_to_single_bone.png
Skin all the geometry in this mesh to a single bone.
ConvertSkinBindToPivotPaint
__autoskinned
Unexpected skinning defined on mesh %s
skin%d
Warning! Particle Snapshot - Cannot find skinned bone %s in model
The name of the unskinned child mesh of this transform in the source geometry file.
CModelDocModelModifier_CopyMeshSkinning
CopyMeshSkinning
Copy skinning information from one rendermesh to another, based on a simple heuristic.
CModelDocClothEffectSkinnedCollider
ClothEffectSkinnedCollider
game:tools/images/modeldoc_editor/outliner_icon_cloth_effect_skinned_collider.png
Cloth Skinned Collision Effect node.
CModelDocStickerMarkup
CModelDocStickerMarkupLocator
CModelDocStickerMarkupPolygonNode
StickerMarkup
tools/images/modeldoc_editor/outliner_icon_sticker_markup.png
Sticker Markup Preview
StickerMarkup [%s]
sticker_markup_preview
... and 2072 more
```
#### network
```
?observe@r1@detail@tbb@@YAXAEAVtask_scheduler_observer@d1@23@_N@Z
.?AV?$_Ref_count_obj2@VPinningObserver@oidn@@@std@@
.?AVPinningObserver@oidn@@
.?AVtask_scheduler_observer@d1@detail@tbb@@
Unknown protocol.
PanoramaUIClient001
Source2Client002
Source2ClientUI001
Source2ClientPrediction001
Source2Server001
Source2GameClients001
NetworkClientService_001
NetworkServerService_001
GameResourceServiceClientV001
GameResourceServiceServerV001
Source2EngineToClient001
Source2EngineToServer001
Source2EngineToServerStringTable001
Source2EngineToClientStringTable001
ServerToolsInfo_001
ClientToolsInfo_001
VNotify Abandoned (ActiveProtocolIsNewer)
no protocol option
protocol error
protocol not supported
wrong protocol type
Client Exclusions Active: %s
Can't connect to perforce server.
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\io\coded_stream.cc
A protocol message was rejected because it was too big (more than 
 bytes).  To increase the limit (or to disable these warnings), see CodedInputStream::SetTotalBytesLimit() in third_party/protobuf/io/coded_stream.h.
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google/protobuf/descriptor.h
Protocol Buffer map usage error:
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\generated_message_reflection.cc
Protocol Buffer reflection usage error:
  Method      : google::protobuf::Reflection::
[libprotobuf %s %s:%d] %s
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google/protobuf/parse_context.h
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google/protobuf/dynamic_message.h
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\wire_format.cc
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\arena.cc
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\wire_format_lite.cc
 a protocol buffer. Use the 'bytes' type if you intend to send raw bytes. 
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\message_lite.cc
 exceeded maximum protobuf size of 2GB: 
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google/protobuf/reflection_internal.h
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\message.cc
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\extension_set.cc
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google/protobuf/extension_set_inl.h
 google/protobuf/descriptor.proto
google.protobuf"G
2$.google.protobuf.FileDescriptorProto"
FileDescriptorProto
2 .google.protobuf.DescriptorProto
2$.google.protobuf.EnumDescriptorProto
2'.google.protobuf.ServiceDescriptorProto
2%.google.protobuf.FieldDescriptorProto
.google.protobuf.FileOptions
.google.protobuf.SourceCodeInfo
DescriptorProto
2/.google.protobuf.DescriptorProto.ExtensionRange
2%.google.protobuf.OneofDescriptorProto
.google.protobuf.MessageOptions
2..google.protobuf.DescriptorProto.ReservedRange
2&.google.protobuf.ExtensionRangeOptions
2$.google.protobuf.UninterpretedOption*
FieldDescriptorProto
2*.google.protobuf.FieldDescriptorProto.Type
.google.protobuf.FieldOptions
proto3_optional
OneofDescriptorProto
.google.protobuf.OneofOptions"
EnumDescriptorProto
2).google.protobuf.EnumValueDescriptorProto
.google.protobuf.EnumOptions
26.google.protobuf.EnumDescriptorProto.EnumReservedRange
EnumValueDescriptorProto
2!.google.protobuf.EnumValueOptions"
ServiceDescriptorProto
2&.google.protobuf.MethodDescriptorProto
.google.protobuf.ServiceOptions"
MethodDescriptorProto
.google.protobuf.MethodOptions
client_streaming
server_streaming
2).google.protobuf.FileOptions.OptimizeMode:
2$.google.protobuf.UninterpretedOption":
2#.google.protobuf.FieldOptions.CType:
2$.google.protobuf.FieldOptions.JSType:
2$.google.protobuf.UninterpretedOption"/
2$.google.protobuf.UninterpretedOption"P
2-.google.protobuf.UninterpretedOption.NamePart
2(.google.protobuf.SourceCodeInfo.Location
2-.google.protobuf.GeneratedCodeInfo.Annotation
com.google.protobufB
DescriptorProtosH
Z-google.golang.org/protobuf/types/descriptorpb
Google.Protobuf.Reflection
google/protobuf/descriptor.proto
U:\thirdpartycode\nonredist\protobuf\protobuf-3.21.8\src\google\protobuf\text_format.cc
... and 4617 more
```
#### security
```
m_RequireSearchableIntKey = "model_is_modeldoc"
m_RequireSearchableIntKey = "WorldModelDocAll"
keyvalues_asset = 
  <trustInfo>
  </trustInfo>
AAA Certificate Services0
2http://crl.comodoca.com/AAACertificateServices.crl04
#Sectigo RSA Time Stamping Signer #4
Sectigo RSA Time Stamping CA0
#Sectigo RSA Time Stamping Signer #40
3http://crl.sectigo.com/SectigoRSATimeStampingCA.crl0t
3http://crt.sectigo.com/SectigoRSATimeStampingCA.crt0#
The USERTRUST Network1.0,
%USERTrust RSA Certification Authority0
?http://crl.usertrust.com/USERTrustRSACertificationAuthority.crl0v
3http://crt.usertrust.com/USERTrustRSAAddTrustCA.crt0%
http://ocsp.usertrust.com0
Sectigo RSA Time Stamping CA
%USERTrust RSA Certification Authority
?getWorkAmount@Graph@oidn@@QEBANXZ
  <trustInfo>
  </trustInfo>
AAA Certificate Services0
2http://crl.comodoca.com/AAACertificateServices.crl04
#Sectigo RSA Time Stamping Signer #4
Sectigo RSA Time Stamping CA0
#Sectigo RSA Time Stamping Signer #40
3http://crl.sectigo.com/SectigoRSATimeStampingCA.crl0t
3http://crt.sectigo.com/SectigoRSATimeStampingCA.crt0#
The USERTRUST Network1.0,
%USERTrust RSA Certification Authority0
?http://crl.usertrust.com/USERTrustRSACertificationAuthority.crl0v
3http://crt.usertrust.com/USERTrustRSAAddTrustCA.crt0%
http://ocsp.usertrust.com0
Sectigo RSA Time Stamping CA
%USERTrust RSA Certification Authority
  <trustInfo>
  </trustInfo>
AAA Certificate Services0
2http://crl.comodoca.com/AAACertificateServices.crl04
#Sectigo RSA Time Stamping Signer #4
Sectigo RSA Time Stamping CA0
#Sectigo RSA Time Stamping Signer #40
3http://crl.sectigo.com/SectigoRSATimeStampingCA.crl0t
3http://crt.sectigo.com/SectigoRSATimeStampingCA.crt0#
The USERTRUST Network1.0,
%USERTrust RSA Certification Authority0
?http://crl.usertrust.com/USERTrustRSACertificationAuthority.crl0v
3http://crt.usertrust.com/USERTrustRSAAddTrustCA.crt0%
http://ocsp.usertrust.com0
Sectigo RSA Time Stamping CA
%USERTrust RSA Certification Authority
  <trustInfo>
  </trustInfo>
AAA Certificate Services0
2http://crl.comodoca.com/AAACertificateServices.crl04
#Sectigo RSA Time Stamping Signer #4
Sectigo RSA Time Stamping CA0
#Sectigo RSA Time Stamping Signer #40
3http://crl.sectigo.com/SectigoRSATimeStampingCA.crl0t
3http://crt.sectigo.com/SectigoRSATimeStampingCA.crt0#
The USERTRUST Network1.0,
%USERTrust RSA Certification Authority0
?http://crl.usertrust.com/USERTrustRSACertificationAuthority.crl0v
3http://crt.usertrust.com/USERTrustRSAAddTrustCA.crt0%
http://ocsp.usertrust.com0
Sectigo RSA Time Stamping CA
%USERTrust RSA Certification Authority
  <trustInfo>
  </trustInfo>
AAA Certificate Services0
2http://crl.comodoca.com/AAACertificateServices.crl04
#Sectigo RSA Time Stamping Signer #4
Sectigo RSA Time Stamping CA0
#Sectigo RSA Time Stamping Signer #40
3http://crl.sectigo.com/SectigoRSATimeStampingCA.crl0t
3http://crt.sectigo.com/SectigoRSATimeStampingCA.crt0#
The USERTRUST Network1.0,
%USERTrust RSA Certification Authority0
?http://crl.usertrust.com/USERTrustRSACertificationAuthority.crl0v
3http://crt.usertrust.com/USERTrustRSAAddTrustCA.crt0%
http://ocsp.usertrust.com0
Sectigo RSA Time Stamping CA
%USERTrust RSA Certification Authority
  <trustInfo>
  </trustInfo>
AAA Certificate Services0
2http://crl.comodoca.com/AAACertificateServices.crl04
#Sectigo RSA Time Stamping Signer #4
Sectigo RSA Time Stamping CA0
#Sectigo RSA Time Stamping Signer #40
3http://crl.sectigo.com/SectigoRSATimeStampingCA.crl0t
3http://crt.sectigo.com/SectigoRSATimeStampingCA.crt0#
The USERTRUST Network1.0,
%USERTrust RSA Certification Authority0
?http://crl.usertrust.com/USERTrustRSACertificationAuthority.crl0v
3http://crt.usertrust.com/USERTrustRSAAddTrustCA.crt0%
http://ocsp.usertrust.com0
Sectigo RSA Time Stamping CA
%USERTrust RSA Certification Authority
... and 10570 more
```
#### ui
```
m_bShowInRevisionSubMenu = true
1UpdateButtonStatusFromAction()
1OpenMenuForParentsOfAsset()
1OpenMenuForChildrenOfAsset()
ShowContextMenu
CQBindableCommandToolButton
CQBindableCommandPushButton
QLabel
QMenu
QRadioButton
QPushButton
QToolButton
QMenuBar
menu
menus
horizontal_header_labels
MENU
BUTTON
menuAction
1UpdateMenu()
2buttonClicked( QAbstractButton* )
1OnToolSpecificUIButton( QAbstractButton* )
materials/tools/ui_material_preview_on_model.vmat
filter_label
game:tools/images/common/tools_shared_menu_button.png
toolhud_enable
QPushButton { border:none; } QPushButton::hover { background-color:rgb(246,146,30); }
1EnableOkButton( const QString & )
1EnableRenameButton( const QString & )
is_cqbasegridview_panel
1OnAssetPanelDoubleClicked(int)
2PanelDoubleClicked(int)
AssetGridPanel
decrease_depth_button
increase_depth_button
navigate_forward_button
navigate_back_button
AssetLabel
ToolsMenu
1OnAboutToShowThumbnailMenu()
Preview Menu Enabled
Enable a menu for asset preview types that support (eg. models)
game:tools/images/valve_style/dropdown_menu_open.png
1OpenMenuForSelectedAssets()
game:tools/images/assetbrowser/select_mod_button_partial.png
game:tools/images/assetbrowser/select_mod_button_full.png
game:tools/images/assetbrowser/select_mod_button_none.png
game:tools/images/assetbrowser/select_button_partial.png
game:tools/images/assetbrowser/select_button_full.png
game:tools/images/assetbrowser/select_button_none.png
1OnConfirmRenameButtonClicked()
2customContextMenuRequested(const QPoint &)
1OnTableContextMenuRequested(const QPoint &)
1OnTableContextMenuRequested()
_AssetMenuHelper
CQAssetMenuHelper*
AssetMenu
1OpenRevisionSubMenuTool( int )
game:tools/images/common/dropdown_menu.png
Show Asset Menu
1OnMenu()
CQSubassetMenuHelper*
Valve_SubassetMenuHelper
2ButtonClicked( QVariant )
QToolButton { 
QToolButton:hover:!pressed { 
background-position: center center; } QToolButton:hover:!pressed { 
border-radius: %3px; } QLabel { 
Y?setHorizontalHeaderLabels@QStandardItemModel@@QEAAXAEBVQStringList@@@Z
?exec@QMenu@@QEAAPEAVQAction@@XZ
?contextMenuEvent@QWidget@@MEAAXPEAVQContextMenuEvent@@@Z
?information@QMessageBox@@SA?AW4StandardButton@1@PEAVQWidget@@AEBVQString@@1W421@2@Z
?contextMenuEvent@QLineEdit@@MEAAXPEAVQContextMenuEvent@@@Z
?contextMenuEvent@QAbstractScrollArea@@MEAAXPEAVQContextMenuEvent@@@Z
?nextCheckState@QToolButton@@MEAAXXZ
?hitButton@QToolButton@@MEBA_NAEBVQPoint@@@Z
?changeEvent@QToolButton@@MEAAXPEAVQEvent@@@Z
+ ?timerEvent@QToolButton@@MEAAXPEAVQTimerEvent@@@Z
?leaveEvent@QToolButton@@MEAAXPEAVQEvent@@@Z
?enterEvent@QToolButton@@MEAAXPEAVQEvent@@@Z
?actionEvent@QToolButton@@MEAAXPEAVQActionEvent@@@Z
?paintEvent@QToolButton@@MEAAXPEAVQPaintEvent@@@Z
?mouseReleaseEvent@QToolButton@@MEAAXPEAVQMouseEvent@@@Z
?mousePressEvent@QToolButton@@MEAAXPEAVQMouseEvent@@@Z
?event@QToolButton@@MEAA_NPEAVQEvent@@@Z
?minimumSizeHint@QToolButton@@UEBA?AVQSize@@XZ
?sizeHint@QToolButton@@UEBA?AVQSize@@XZ
??1QToolButton@@UEAA@XZ
??0QToolButton@@QEAA@PEAVQWidget@@@Z
?qt_metacall@QToolButton@@UEAAHW4Call@QMetaObject@@HPEAPEAX@Z
?qt_metacast@QToolButton@@UEAAPEAXPEBD@Z
?metaObject@QToolButton@@UEBAPEBUQMetaObject@@XZ
?hitButton@QPushButton@@MEBA_NAEBVQPoint@@@Z
?focusOutEvent@QPushButton@@MEAAXPEAVQFocusEvent@@@Z
?focusInEvent@QPushButton@@MEAAXPEAVQFocusEvent@@@Z
?keyPressEvent@QPushButton@@MEAAXPEAVQKeyEvent@@@Z
?paintEvent@QPushButton@@MEAAXPEAVQPaintEvent@@@Z
?event@QPushButton@@MEAA_NPEAVQEvent@@@Z
?setDefault@QPushButton@@QEAAX_N@Z
?minimumSizeHint@QPushButton@@UEBA?AVQSize@@XZ
... and 5054 more
```
#### audio
```
sound_asset = 
m_FriendlyName = "Sound"
m_CompilerIdentifier = "CompileSound"
m_Description = "Play Sound"
sound_event_script = 
m_FriendlyName = "Sound Event Script"
m_CompilerIdentifier = "CompileSoundEventScript"
m_RequiredSpecialDependency = "Sound Event Script Version"
sound_stack_script = 
m_FriendlyName = "Sound Stack Script"
m_CompilerIdentifier = "CompileSoundStackScript"
SoundSystem001
SoundOpSystemEdit001
SoundOpSystem001
SteamAudio001
SoundService_001
Tools audio currently muted
Game audio muted while tools are active
IToolFrameworkAudioSettingsListener
Play Sound Asset When Selected In Asset Browsers
.?AVIToolFrameworkAudioSettingsListener@@
FOOTSOUND_Left
FOOTSOUND_Right
FOOTSOUND_UseOverrideSound
FootstepLandedFootSoundType_t
CAudioAnimTag
Sound Event
SoundPicker()
Audio Tag
Element.CAudioAnimTag
Override Sound
Sound
m_OverrideSoundName
const char *__cdecl Reflection::Internal::GetFuncName<class IAudioAnimTag>(void)
const char *__cdecl Reflection::Internal::GetFuncName<class CAudioAnimTag>(void)
audioTarget
sound
BuildSteamAudioReverb
BuildSteamAudioPaths
BuildSteamAudioCustomData
SteamAudioEnabled
soundevent
Steam Audio/Probe Boxes
CSteamAudioProbeBoxNode
Steam Audio/Probes
CSteamAudioProbeNode
Steam Audio/Imported Probes
CSteamAudioImportedProbeBoxNode
Steam Audio/Acoustic Geometry
CSteamAudioData
mapbuilder.blocksound
blocksound
Render Steam Audio Probes even when probes are unselected.
snd_steamaudio_hammer_probes_always_render
Audio Probe
Steam Audio Probe
Steam Audio Data
Steam Audio Imported Probe Box
CSteamAudioImportedProbeNode
CSteamAudioAmbisonicValues
CSteamAudioMaterialValues
CSteamAudioSignal
Steam Audio Imported Probe
CSteamAudioProbeGenerationVolume
CSteamAudioProbeExclusionVolume
Steam Audio Probe Generation Volume
Steam Audio Probe Exclusion Volume
A game event occurring at a particular frame in an animation (Footstep, sound, particle effect, etc.)
What material this object is made of. Used for mass calculations, impact effects, surface decals, sounds, etc.
CModelDocDrivenSoundEvent
SoundeventList
AttachedSoundEvent
Sound event attached to an attach point, and driven off of physical parameters.
sound_event
attached_soundevents
audioreflectivity
audiohardnessfactor
audioroughnessfactor
audioHardMinVelocity
audiosounds
audioparams
m_audioSounds
m_audioParams
CPhysSurfacePropertiesAudio
CPhysSurfacePropertiesSoundNames
DmeSoundClip
DmeSound
DmeGameSound
DmeSoundEvent
soundname
gameSoundName
soundEventScript
replacedSoundEvents
SoundEvent Instance Handle
SoundEvent
SoundSystem001
SoundOpSystemEdit001
SoundOpSystem001
SteamAudio001
SoundService_001
... and 1680 more
```
#### other
```
"settings"
"maxres"
"settings"
"settings"
"clampu"
"clampv"
"clampw"
"nocompress"
"settings"
"clampu"
"clampv"
"clampw"
"nocompress"
"settings"
"maxres"
"nomip"
"settings"
"legacy_source1_inverted_normal"
"settings"
"legacy_source1_inverted_normal"
In order for tools like material editor to function externally,
we need to ship the CONTENT sources for default texture inputs.
This means we should expect pre-compiled CONTENT in this 
directory will ship to external users.
"settings"
"settings"
"maxres"
"settings"
"maxres"
"settings"
"maxres"
"settings"
"maxres"
"settings"
"maxres"
"settings"
"maxres"
asset_warnings =
old_model_serialization =
m_Title = "Legacy Compiled Data"
m_Checks =
m_AssetType = "model_asset"
m_RequireSearchableIntValue = 1
m_bOnlyWarnIfContentFilePresent = true
m_bOnlyWarnIfGameFilePresent = true
m_ExcludeAddonNames = [ "dota_addons/workshop_testbed" ]
m_FixType = "VMDL_CONVERT_TO_MODELDOC"
m_bOnlyWarnAddons = true
m_FixDescription = "{count} map(s) will not be changed. You must manually recompile maps."
assettypes =
vdata_asset = 
_class = "CResourceAssetTypeInfo"
m_FriendlyName = "VData"
m_Ext = "vdata"
m_IconLg = "game:tools/images/assettypes/vdata_lg.png"
m_IconSm = "game:tools/images/assettypes/vdata_sm.png"
m_CompilerIdentifier = "CompileVData"
m_Blocks = 
m_BlockID = "DATA"
m_Encoding = "RESOURCE_ENCODING_KV3"
m_HideForRetailMods = 
vdata_inc_asset = 
_class = "CSimpleAssetTypeInfo"
m_FriendlyName = "VData Include"
m_Ext = "vdata_inc"
m_bContentFileIsText = true
animation_asset = 
m_FriendlyName = "Animation"
m_Ext = "vanim"
m_IconLg = "game:tools/images/assettypes/animation_lg.png"
m_IconSm = "game:tools/images/assettypes/animation_sm.png"
m_bHideTypeByDefault = true
m_ResourceVersion = 0
m_Encoding = "RESOURCE_ENCODING_INTROSPECTED"
m_ResourceVersion = 1
"csgo",
animgroup_asset = 
m_FriendlyName = "Animation Group"
m_Ext = "vagrp"
m_IconLg = "game:tools/images/assettypes/animation_group_lg.png"
m_IconSm = "game:tools/images/assettypes/animation_group_sm.png"
m_BlockID = "CTRL"
m_BlockID = "ANIM"
sequence_asset = 
m_FriendlyName = "Sequence Group"
m_Ext = "vseq"
particle_asset = 
m_FriendlyName = "Particle System"
m_Ext = "vpcf"
m_IconLg = "game:tools/images/assettypes/particles_lg.png"
m_IconSm = "game:tools/images/assettypes/particles_sm.png"
m_CompilerIdentifier = "CompileParticle"
m_bPrefersLivePreview = true
m_bUnrecognizedReferencesAreErrors = true
material_asset = 
m_FriendlyName = "Material"
m_Ext = "vmat"
m_IconLg = "game:tools/images/assettypes/material_lg.png"
m_IconSm = "game:tools/images/assettypes/material_sm.png"
m_CompilerIdentifier = "CompileMaterial"
... and 1425263 more
```

### Raw VDF Diff

<details>
<summary>Click to expand</summary>

```diff
--- /dev/null
+++ new
@@ -0,0 +1,1592 @@
+WARNING: setlocale('en_US.UTF-8') failed, using locale: 'C'. International characters may not work.
+Redirecting stderr to '/home/user/Steam/logs/stderr.txt'
+Logging directory: '/home/user/Steam/logs'
+[  0%] Checking for available updates...
+[----] Verifying installation...
+UpdateUI: skip show logo
+Steam Console Client (c) Valve Corporation - version 1766091153
+-- type 'quit' to exit --
+Loading Steam API...[0mOK
+[0m
+Connecting anonymously to Steam Public...[0mOK
+[0mWaiting for client config...[0mOK
+[0mWaiting for user info...[0mOK
+[0mAppID : 730, change number : 32901595/32901595, last change : Sat Dec 20 07:23:51 2025 
+"730"
+{
+	"common"
+	{
+		"clienticon"		"324b323045b09bace182f928f4104dfcd93cb7f3"
+		"clienttga"		"c52076783b94290949b1ab5ac44a84c036c4c313"
+		"name"		"Counter-Strike 2"
+		"languages"
+		{
+			"english"		"1"
+			"german"		"1"
+			"french"		"1"
+			"italian"		"1"
+			"koreana"		"1"
+			"spanish"		"1"
+			"schinese"		"1"
+			"tchinese"		"1"
+			"russian"		"1"
+			"thai"		"1"
+			"japanese"		"1"
+			"portuguese"		"1"
+			"polish"		"1"
+			"danish"		"1"
+			"dutch"		"1"
+			"finnish"		"1"
+			"norwegian"		"1"
+			"swedish"		"1"
+			"hungarian"		"1"
+			"czech"		"1"
+			"romanian"		"1"
+			"turkish"		"1"
+			"brazilian"		"1"
+			"bulgarian"		"1"
+			"greek"		"1"
+			"ukrainian"		"1"
+			"vietnamese"		"1"
+			"latam"		"1"
+			"indonesian"		"1"
+		}
+		"logo"		"d0595ff02f5c79fd19b06f4d6165c3fda2372820"
+		"logo_small"		"d0595ff02f5c79fd19b06f4d6165c3fda2372820_thumb"
+		"icon"		"8dbc71957312bbd3baea65848b545be9eae2a355"
+		"metacritic_url"		""
+		"clienticns"		"a42c6010effb3f108ae59f1b08843d08386e6b2a"
+		"oslist"		"windows,linux"
+		"type"		"Game"
+		"linuxclienticon"		"ff52d4cc462d49c0297b9bc0558b4ef4c3bdd9ae"
+		"exfgls"		"1"
+		"osarch"		""
+		"osextended"		""
+		"steamchinaapproved"		"1"
+		"name_localized"
+		{
+			"sc_schinese"		"反恐精英：全球攻势"
+		}
+		"releasestatesteamchina"		"released"
+		"timeline_marker_updated"		"1766184528"
+		"timeline_marker_svg"		"0eeacc724c77e1f5abeeba4fb542f45bad894470/markers.svg"
+		"market_presence"		"1"
+		"content_descriptors"
+		{
+			"0"		"2"
+			"1"		"5"
+		}
+		"steam_deck_compatibility"
+		{
+			"category"		"2"
+			"steamos_compatibility"		"2"
+			"test_timestamp"		"1708732800"
+			"tested_build_id"		"13439412"
+			"tests"
+			{
+				"0"
+				{
+					"display"		"3"
+					"token"		"#SteamDeckVerified_TestResult_ControllerGlyphsDoNotMatchDeckDevice"
+				}
+				"1"
+				{
+					"display"		"3"
+					"token"		"#SteamDeckVerified_TestResult_InterfaceTextIsNotLegible"
+				}
+				"2"
+				{
+					"display"		"4"
+					"token"		"#SteamDeckVerified_TestResult_DefaultControllerConfigFullyFunctional"
+				}
+				"3"
+				{
+					"display"		"4"
+					"token"		"#SteamDeckVerified_TestResult_DefaultConfigurationIsPerformant"
+				}
+			}
+			"steamos_tests"
+			{
+				"0"
+				{
+					"display"		"3"
+					"token"		"#SteamOS_TestResult_GameStartupFunctional"
+				}
+			}
+			"configuration"
+			{
+				"supported_input"		"gamepad"
+				"requires_manual_keyboard_invoke"		"0"
+				"requires_non_controller_launcher_nav"		"0"
+				"primary_player_is_controller_slot_0"		"0"
+				"non_deck_display_glyphs"		"1"
+				"small_text"		"1"
+				"requires_internet_for_setup"		"0"
+				"requires_internet_for_singleplayer"		"0"
+				"recommended_runtime"		"native"
+				"requires_h264"		"0"
+				"requires_voice_files"		"0"
+				"gamescope_frame_limiter_not_supported"		"0"
+				"hdr_support"		"0"
+			}
+		}
+		"controllertagwizard"		"1"
+		"small_capsule"
+		{
+			"english"		"capsule_231x87.jpg"
+			"sc_schinese"		"capsule_231x87_sc_schinese.jpg"
+			"schinese"		"capsule_231x87_schinese.jpg"
+		}
+		"header_image"
+		{
+			"english"		"header.jpg"
+			"sc_schinese"		"header_sc_schinese.jpg"
+			"schinese"		"header_schinese.jpg"
+		}
+		"library_assets"
+		{
+			"library_capsule"		"en,zh-cn"
+			"library_hero"		"en,zh-cn"
+			"library_logo"		"en,zh-cn"
+			"logo_position"
+			{
+				"pinned_position"		"BottomLeft"
+				"width_pct"		"50.512393149848585"
+				"height_pct"		"99.65280290557178"
+			}
+		}
+		"library_assets_full"
+		{
+			"library_capsule"
+			{
+				"image"
+				{
+					"english"		"library_600x900.jpg"
+					"schinese"		"library_600x900_schinese.jpg"
+				}
+				"image2x"
+				{
+					"english"		"library_600x900_2x.jpg"
+					"schinese"		"library_600x900_schinese_2x.jpg"
+				}
+			}
+			"library_hero"
+			{
+				"image"
+				{
+					"english"		"library_hero.jpg"
+					"schinese"		"library_hero_schinese.jpg"
+				}
+				"image2x"
+				{
+					"english"		"library_hero_2x.jpg"
+					"schinese"		"library_hero_schinese_2x.jpg"
+				}
+			}
+			"library_logo"
+			{
+				"logo_position"
+				{
+					"pinned_position"		"BottomLeft"
+					"width_pct"		"50.512393149848585"
+					"height_pct"		"99.65280290557178"
+				}
+				"image"
+				{
+					"english"		"logo.png"
+					"schinese"		"logo_schinese.png"

... (truncated)
```

</details>
