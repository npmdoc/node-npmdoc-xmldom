# api documentation for  [xmldom (v0.1.27)](https://github.com/jindw/xmldom)  [![npm package](https://img.shields.io/npm/v/npmdoc-xmldom.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-xmldom) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-xmldom.svg)](https://travis-ci.org/npmdoc/node-npmdoc-xmldom)
#### A W3C Standard XML DOM(Level2 CORE) implementation and parser(DOMParser/XMLSerializer).

[![NPM](https://nodei.co/npm/xmldom.png?downloads=true)](https://www.npmjs.com/package/xmldom)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xmldom/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-xmldom_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xmldom/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-xmldom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-xmldom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "jindw",
        "email": "jindw@xidea.org",
        "url": "http://www.xidea.org"
    },
    "bugs": {
        "url": "http://github.com/jindw/xmldom/issues",
        "email": "jindw@xidea.org"
    },
    "contributors": [
        {
            "name": "Yaron Naveh",
            "email": "yaronn01@gmail.com",
            "url": "http://webservices20.blogspot.com/"
        },
        {
            "name": "Harutyun Amirjanyan",
            "email": "amirjanyan@gmail.com",
            "url": "https://github.com/nightwing"
        },
        {
            "name": "Alan Gutierrez",
            "email": "alan@prettyrobots.com",
            "url": "http://www.prettyrobots.com/"
        }
    ],
    "dependencies": {},
    "description": "A W3C Standard XML DOM(Level2 CORE) implementation and parser(DOMParser/XMLSerializer).",
    "devDependencies": {
        "proof": "0.0.28"
    },
    "directories": {},
    "dist": {
        "shasum": "d501f97b3bdb403af8ef9ecc20573187aadac0e9",
        "tarball": "https://registry.npmjs.org/xmldom/-/xmldom-0.1.27.tgz"
    },
    "engines": {
        "node": ">=0.1"
    },
    "gitHead": "b53aa82a36160d85faab394035dcd1784764537f",
    "homepage": "https://github.com/jindw/xmldom",
    "keywords": [
        "w3c",
        "dom",
        "xml",
        "parser",
        "javascript",
        "DOMParser",
        "XMLSerializer"
    ],
    "licenses": [
        {
            "type": "LGPL",
            "url": "http://www.gnu.org/licenses/lgpl.html",
            "MIT": "http://opensource.org/licenses/MIT"
        }
    ],
    "main": "./dom-parser.js",
    "maintainers": [
        {
            "name": "jindw",
            "email": "jindw@xidea.org"
        },
        {
            "name": "yaron",
            "email": "yaronn01@gmail.com"
        },
        {
            "name": "bigeasy",
            "email": "alan@prettyrobots.com"
        },
        {
            "name": "kethinov",
            "email": "kethinov@gmail.com"
        },
        {
            "name": "jinjinyun",
            "email": "jinyun.jin@gmail.com"
        }
    ],
    "name": "xmldom",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/jindw/xmldom.git"
    },
    "scripts": {
        "test": "proof platform win32 && proof test */*/*.t.js || t/test"
    },
    "version": "0.1.27"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module xmldom](#apidoc.module.xmldom)
1.  [function <span class="apidocSignatureSpan">xmldom.</span>DOMImplementation (features)](#apidoc.element.xmldom.DOMImplementation)
1.  [function <span class="apidocSignatureSpan">xmldom.</span>DOMParser (options)](#apidoc.element.xmldom.DOMParser)
1.  [function <span class="apidocSignatureSpan">xmldom.</span>XMLSerializer ()](#apidoc.element.xmldom.XMLSerializer)
1.  object <span class="apidocSignatureSpan">xmldom.</span>DOMImplementation.prototype
1.  object <span class="apidocSignatureSpan">xmldom.</span>DOMParser.prototype
1.  object <span class="apidocSignatureSpan">xmldom.</span>XMLSerializer.prototype
1.  object <span class="apidocSignatureSpan">xmldom.</span>dom
1.  object <span class="apidocSignatureSpan">xmldom.</span>sax

#### [module xmldom.DOMImplementation](#apidoc.module.xmldom.DOMImplementation)
1.  [function <span class="apidocSignatureSpan">xmldom.</span>DOMImplementation (features)](#apidoc.element.xmldom.DOMImplementation.DOMImplementation)

#### [module xmldom.DOMImplementation.prototype](#apidoc.module.xmldom.DOMImplementation.prototype)
1.  [function <span class="apidocSignatureSpan">xmldom.DOMImplementation.prototype.</span>createDocument (namespaceURI, qualifiedName, doctype)](#apidoc.element.xmldom.DOMImplementation.prototype.createDocument)
1.  [function <span class="apidocSignatureSpan">xmldom.DOMImplementation.prototype.</span>createDocumentType (qualifiedName, publicId, systemId)](#apidoc.element.xmldom.DOMImplementation.prototype.createDocumentType)
1.  [function <span class="apidocSignatureSpan">xmldom.DOMImplementation.prototype.</span>hasFeature (feature, version)](#apidoc.element.xmldom.DOMImplementation.prototype.hasFeature)

#### [module xmldom.DOMParser](#apidoc.module.xmldom.DOMParser)
1.  [function <span class="apidocSignatureSpan">xmldom.</span>DOMParser (options)](#apidoc.element.xmldom.DOMParser.DOMParser)

#### [module xmldom.DOMParser.prototype](#apidoc.module.xmldom.DOMParser.prototype)
1.  [function <span class="apidocSignatureSpan">xmldom.DOMParser.prototype.</span>parseFromString (source, mimeType)](#apidoc.element.xmldom.DOMParser.prototype.parseFromString)

#### [module xmldom.XMLSerializer](#apidoc.module.xmldom.XMLSerializer)
1.  [function <span class="apidocSignatureSpan">xmldom.</span>XMLSerializer ()](#apidoc.element.xmldom.XMLSerializer.XMLSerializer)

#### [module xmldom.XMLSerializer.prototype](#apidoc.module.xmldom.XMLSerializer.prototype)
1.  [function <span class="apidocSignatureSpan">xmldom.XMLSerializer.prototype.</span>serializeToString (node, isHtml, nodeFilter)](#apidoc.element.xmldom.XMLSerializer.prototype.serializeToString)

#### [module xmldom.dom](#apidoc.module.xmldom.dom)
1.  [function <span class="apidocSignatureSpan">xmldom.dom.</span>DOMImplementation (features)](#apidoc.element.xmldom.dom.DOMImplementation)
1.  [function <span class="apidocSignatureSpan">xmldom.dom.</span>XMLSerializer ()](#apidoc.element.xmldom.dom.XMLSerializer)

#### [module xmldom.sax](#apidoc.module.xmldom.sax)
1.  [function <span class="apidocSignatureSpan">xmldom.sax.</span>XMLReader ()](#apidoc.element.xmldom.sax.XMLReader)



# <a name="apidoc.module.xmldom"></a>[module xmldom](#apidoc.module.xmldom)

#### <a name="apidoc.element.xmldom.DOMImplementation"></a>[function <span class="apidocSignatureSpan">xmldom.</span>DOMImplementation (features)](#apidoc.element.xmldom.DOMImplementation)
- description and source-code
```javascript
function DOMImplementation(features) {
	this._features = {};
	if (features) {
		for (var feature in features) {
			 this._features = features[feature];
		}
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.xmldom.DOMParser"></a>[function <span class="apidocSignatureSpan">xmldom.</span>DOMParser (options)](#apidoc.element.xmldom.DOMParser)
- description and source-code
```javascript
function DOMParser(options){
	this.options = options ||{locator:{}};
	
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.xmldom.XMLSerializer"></a>[function <span class="apidocSignatureSpan">xmldom.</span>XMLSerializer ()](#apidoc.element.xmldom.XMLSerializer)
- description and source-code
```javascript
function XMLSerializer(){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.xmldom.DOMImplementation"></a>[module xmldom.DOMImplementation](#apidoc.module.xmldom.DOMImplementation)

#### <a name="apidoc.element.xmldom.DOMImplementation.DOMImplementation"></a>[function <span class="apidocSignatureSpan">xmldom.</span>DOMImplementation (features)](#apidoc.element.xmldom.DOMImplementation.DOMImplementation)
- description and source-code
```javascript
function DOMImplementation(features) {
	this._features = {};
	if (features) {
		for (var feature in features) {
			 this._features = features[feature];
		}
	}
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.xmldom.DOMImplementation.prototype"></a>[module xmldom.DOMImplementation.prototype](#apidoc.module.xmldom.DOMImplementation.prototype)

#### <a name="apidoc.element.xmldom.DOMImplementation.prototype.createDocument"></a>[function <span class="apidocSignatureSpan">xmldom.DOMImplementation.prototype.</span>createDocument (namespaceURI, qualifiedName, doctype)](#apidoc.element.xmldom.DOMImplementation.prototype.createDocument)
- description and source-code
```javascript
createDocument = function (namespaceURI, qualifiedName, doctype){// raises:INVALID_CHARACTER_ERR,NAMESPACE_ERR,WRONG_DOCUMENT_ERR
		var doc = new Document();
		doc.implementation = this;
		doc.childNodes = new NodeList();
		doc.doctype = doctype;
		if(doctype){
			doc.appendChild(doctype);
		}
		if(qualifiedName){
			var root = doc.createElementNS(namespaceURI,qualifiedName);
			doc.appendChild(root);
		}
		return doc;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.xmldom.DOMImplementation.prototype.createDocumentType"></a>[function <span class="apidocSignatureSpan">xmldom.DOMImplementation.prototype.</span>createDocumentType (qualifiedName, publicId, systemId)](#apidoc.element.xmldom.DOMImplementation.prototype.createDocumentType)
- description and source-code
```javascript
createDocumentType = function (qualifiedName, publicId, systemId){// raises:INVALID_CHARACTER_ERR,NAMESPACE_ERR
		var node = new DocumentType();
		node.name = qualifiedName;
		node.nodeName = qualifiedName;
		node.publicId = publicId;
		node.systemId = systemId;
		// Introduced in DOM Level 2:
		//readonly attribute DOMString        internalSubset;
		
		//TODO:..
		//  readonly attribute NamedNodeMap     entities;
		//  readonly attribute NamedNodeMap     notations;
		return node;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.xmldom.DOMImplementation.prototype.hasFeature"></a>[function <span class="apidocSignatureSpan">xmldom.DOMImplementation.prototype.</span>hasFeature (feature, version)](#apidoc.element.xmldom.DOMImplementation.prototype.hasFeature)
- description and source-code
```javascript
hasFeature = function (feature, version) {
		var versions = this._features[feature.toLowerCase()];
		if (versions && (!version || version in versions)) {
			return true;
		} else {
			return false;
		}
	}
```
- example usage
```shell
...
				child.normalize();
				child = next;
			}
		}
	},
  	// Introduced in DOM Level 2:
	isSupported:function(feature, version){
		return this.ownerDocument.implementation.hasFeature(feature,version);
	},
// Introduced in DOM Level 2:
hasAttributes:function(){
	return this.attributes.length>0;
},
lookupPrefix:function(namespaceURI){
	var el = this;
...
```



# <a name="apidoc.module.xmldom.DOMParser"></a>[module xmldom.DOMParser](#apidoc.module.xmldom.DOMParser)

#### <a name="apidoc.element.xmldom.DOMParser.DOMParser"></a>[function <span class="apidocSignatureSpan">xmldom.</span>DOMParser (options)](#apidoc.element.xmldom.DOMParser.DOMParser)
- description and source-code
```javascript
function DOMParser(options){
	this.options = options ||{locator:{}};
	
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.xmldom.DOMParser.prototype"></a>[module xmldom.DOMParser.prototype](#apidoc.module.xmldom.DOMParser.prototype)

#### <a name="apidoc.element.xmldom.DOMParser.prototype.parseFromString"></a>[function <span class="apidocSignatureSpan">xmldom.DOMParser.prototype.</span>parseFromString (source, mimeType)](#apidoc.element.xmldom.DOMParser.prototype.parseFromString)
- description and source-code
```javascript
parseFromString = function (source, mimeType){
	var options = this.options;
	var sax =  new XMLReader();
	var domBuilder = options.domBuilder || new DOMHandler();//contentHandler and LexicalHandler
	var errorHandler = options.errorHandler;
	var locator = options.locator;
	var defaultNSMap = options.xmlns||{};
	var entityMap = {'lt':'<','gt':'>','amp':'&','quot':'"','apos':"'"}
	if(locator){
		domBuilder.setDocumentLocator(locator)
	}
	
	sax.errorHandler = buildErrorHandler(errorHandler,domBuilder,locator);
	sax.domBuilder = options.domBuilder || domBuilder;
	if(/\/x?html?$/.test(mimeType)){
		entityMap.nbsp = '\xa0';
		entityMap.copy = '\xa9';
		defaultNSMap['']= 'http://www.w3.org/1999/xhtml';
	}
	defaultNSMap.xml = defaultNSMap.xml || 'http://www.w3.org/XML/1998/namespace';
	if(source){
		sax.parse(source,defaultNSMap,entityMap);
	}else{
		sax.errorHandler.error("invalid doc source");
	}
	return domBuilder.doc;
}
```
- example usage
```shell
...
-------
>npm install xmldom

Example:
====
'''javascript
var DOMParser = require('xmldom').DOMParser;
var doc = new DOMParser().parseFromString(
    '<xml xmlns="a" xmlns:c="./lite">\n'+
        '\t<child>test</child>\n'+
        '\t<child></child>\n'+
        '\t<child/>\n'+
    '</xml>'
    ,'text/xml');
doc.documentElement.setAttribute('x','y');
...
```



# <a name="apidoc.module.xmldom.XMLSerializer"></a>[module xmldom.XMLSerializer](#apidoc.module.xmldom.XMLSerializer)

#### <a name="apidoc.element.xmldom.XMLSerializer.XMLSerializer"></a>[function <span class="apidocSignatureSpan">xmldom.</span>XMLSerializer ()](#apidoc.element.xmldom.XMLSerializer.XMLSerializer)
- description and source-code
```javascript
function XMLSerializer(){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.xmldom.XMLSerializer.prototype"></a>[module xmldom.XMLSerializer.prototype](#apidoc.module.xmldom.XMLSerializer.prototype)

#### <a name="apidoc.element.xmldom.XMLSerializer.prototype.serializeToString"></a>[function <span class="apidocSignatureSpan">xmldom.XMLSerializer.prototype.</span>serializeToString (node, isHtml, nodeFilter)](#apidoc.element.xmldom.XMLSerializer.prototype.serializeToString)
- description and source-code
```javascript
serializeToString = function (node, isHtml, nodeFilter){
	return nodeSerializeToString.call(node,isHtml,nodeFilter);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.xmldom.dom"></a>[module xmldom.dom](#apidoc.module.xmldom.dom)

#### <a name="apidoc.element.xmldom.dom.DOMImplementation"></a>[function <span class="apidocSignatureSpan">xmldom.dom.</span>DOMImplementation (features)](#apidoc.element.xmldom.dom.DOMImplementation)
- description and source-code
```javascript
function DOMImplementation(features) {
	this._features = {};
	if (features) {
		for (var feature in features) {
			 this._features = features[feature];
		}
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.xmldom.dom.XMLSerializer"></a>[function <span class="apidocSignatureSpan">xmldom.dom.</span>XMLSerializer ()](#apidoc.element.xmldom.dom.XMLSerializer)
- description and source-code
```javascript
function XMLSerializer(){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.xmldom.sax"></a>[module xmldom.sax](#apidoc.module.xmldom.sax)

#### <a name="apidoc.element.xmldom.sax.XMLReader"></a>[function <span class="apidocSignatureSpan">xmldom.sax.</span>XMLReader ()](#apidoc.element.xmldom.sax.XMLReader)
- description and source-code
```javascript
function XMLReader(){
	
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
