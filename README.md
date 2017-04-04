# api documentation for  [hbs (v4.0.1)](https://github.com/pillarjs/hbs)  [![npm package](https://img.shields.io/npm/v/npmdoc-hbs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hbs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hbs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hbs)
#### Express.js template engine plugin for Handlebars

[![NPM](https://nodei.co/npm/hbs.png?downloads=true)](https://www.npmjs.com/package/hbs)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hbs/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-hbs_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hbs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hbs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hbs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Don Park",
        "email": "donpark@docuverse.com",
        "url": "http://blog.docuverse.com"
    },
    "bugs": {
        "url": "https://github.com/pillarjs/hbs/issues"
    },
    "dependencies": {
        "handlebars": "4.0.5",
        "walk": "2.3.9"
    },
    "description": "Express.js template engine plugin for Handlebars",
    "devDependencies": {
        "mocha": "1.6.0",
        "npm": "3.10.6",
        "request": "2.74.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "4bfd98650dc8c9dac44b3ca9adf9c098e8bc33b6",
        "tarball": "https://registry.npmjs.org/hbs/-/hbs-4.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "1047eb2cd67efbf1f50786f143853a37653ff7fb",
    "homepage": "https://github.com/pillarjs/hbs",
    "license": "MIT",
    "main": "lib/hbs.js",
    "maintainers": [
        {
            "name": "donpark",
            "email": "donpark@docuverse.com"
        },
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        }
    ],
    "name": "hbs",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/pillarjs/hbs.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "4.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module hbs](#apidoc.module.hbs)
1.  [function <span class="apidocSignatureSpan">hbs.</span>SafeString (string)](#apidoc.element.hbs.SafeString)
1.  [function <span class="apidocSignatureSpan">hbs.</span>__express ()](#apidoc.element.hbs.__express)
1.  [function <span class="apidocSignatureSpan">hbs.</span>create (handlebars)](#apidoc.element.hbs.create)
1.  [function <span class="apidocSignatureSpan">hbs.</span>handlebars.Compiler ()](#apidoc.element.hbs.handlebars.Compiler)
1.  [function <span class="apidocSignatureSpan">hbs.</span>handlebars.HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment)
1.  [function <span class="apidocSignatureSpan">hbs.</span>handlebars.JavaScriptCompiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler)
1.  object <span class="apidocSignatureSpan">hbs.</span>SafeString.prototype
1.  object <span class="apidocSignatureSpan">hbs.</span>Utils
1.  object <span class="apidocSignatureSpan">hbs.</span>cache
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars.Compiler.prototype
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars.HandlebarsEnvironment.prototype
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars.JavaScriptCompiler.prototype
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars.VM
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars.decorators
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars.helpers
1.  object <span class="apidocSignatureSpan">hbs.</span>handlebars.logger

#### [module hbs.SafeString](#apidoc.module.hbs.SafeString)
1.  [function <span class="apidocSignatureSpan">hbs.</span>SafeString (string)](#apidoc.element.hbs.SafeString.SafeString)

#### [module hbs.SafeString.prototype](#apidoc.module.hbs.SafeString.prototype)
1.  [function <span class="apidocSignatureSpan">hbs.SafeString.prototype.</span>toHTML ()](#apidoc.element.hbs.SafeString.prototype.toHTML)
1.  [function <span class="apidocSignatureSpan">hbs.SafeString.prototype.</span>toString ()](#apidoc.element.hbs.SafeString.prototype.toString)

#### [module hbs.Utils](#apidoc.module.hbs.Utils)
1.  boolean <span class="apidocSignatureSpan">hbs.Utils.</span>__esModule
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>appendContextPath (contextPath, id)](#apidoc.element.hbs.Utils.appendContextPath)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>blockParams (params, ids)](#apidoc.element.hbs.Utils.blockParams)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>createFrame (object)](#apidoc.element.hbs.Utils.createFrame)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>escapeExpression (string)](#apidoc.element.hbs.Utils.escapeExpression)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>extend (obj)](#apidoc.element.hbs.Utils.extend)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>indexOf (array, value)](#apidoc.element.hbs.Utils.indexOf)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>isArray ()](#apidoc.element.hbs.Utils.isArray)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>isEmpty (value)](#apidoc.element.hbs.Utils.isEmpty)
1.  [function <span class="apidocSignatureSpan">hbs.Utils.</span>isFunction (value)](#apidoc.element.hbs.Utils.isFunction)

#### [module hbs.handlebars](#apidoc.module.hbs.handlebars)
1.  boolean <span class="apidocSignatureSpan">hbs.handlebars.</span>__esModule
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>Compiler ()](#apidoc.element.hbs.handlebars.Compiler)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>Exception (message, node)](#apidoc.element.hbs.handlebars.Exception)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>JavaScriptCompiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>SafeString (string)](#apidoc.element.hbs.handlebars.SafeString)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>compile (input, options)](#apidoc.element.hbs.handlebars.compile)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>createFrame (object)](#apidoc.element.hbs.handlebars.createFrame)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>escapeExpression (string)](#apidoc.element.hbs.handlebars.escapeExpression)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>log (level)](#apidoc.element.hbs.handlebars.log)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>parse (input, options)](#apidoc.element.hbs.handlebars.parse)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>precompile (input, options)](#apidoc.element.hbs.handlebars.precompile)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>template (spec)](#apidoc.element.hbs.handlebars.template)
1.  number <span class="apidocSignatureSpan">hbs.handlebars.</span>COMPILER_REVISION
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>AST
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>Parser
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>REVISION_CHANGES
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>Utils
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>VM
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>decorators
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>helpers
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>logger
1.  object <span class="apidocSignatureSpan">hbs.handlebars.</span>partials
1.  string <span class="apidocSignatureSpan">hbs.handlebars.</span>VERSION

#### [module hbs.handlebars.Compiler](#apidoc.module.hbs.handlebars.Compiler)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>Compiler ()](#apidoc.element.hbs.handlebars.Compiler.Compiler)

#### [module hbs.handlebars.Compiler.prototype](#apidoc.module.hbs.handlebars.Compiler.prototype)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>BlockStatement (block)](#apidoc.element.hbs.handlebars.Compiler.prototype.BlockStatement)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>BooleanLiteral (bool)](#apidoc.element.hbs.handlebars.Compiler.prototype.BooleanLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>CommentStatement ()](#apidoc.element.hbs.handlebars.Compiler.prototype.CommentStatement)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>ContentStatement (content)](#apidoc.element.hbs.handlebars.Compiler.prototype.ContentStatement)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>Decorator (decorator)](#apidoc.element.hbs.handlebars.Compiler.prototype.Decorator)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>DecoratorBlock (decorator)](#apidoc.element.hbs.handlebars.Compiler.prototype.DecoratorBlock)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>Hash (hash)](#apidoc.element.hbs.handlebars.Compiler.prototype.Hash)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>MustacheStatement (mustache)](#apidoc.element.hbs.handlebars.Compiler.prototype.MustacheStatement)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>NullLiteral ()](#apidoc.element.hbs.handlebars.Compiler.prototype.NullLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>NumberLiteral (number)](#apidoc.element.hbs.handlebars.Compiler.prototype.NumberLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>PartialBlockStatement (partialBlock)](#apidoc.element.hbs.handlebars.Compiler.prototype.PartialBlockStatement)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>PartialStatement (partial)](#apidoc.element.hbs.handlebars.Compiler.prototype.PartialStatement)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>PathExpression (path)](#apidoc.element.hbs.handlebars.Compiler.prototype.PathExpression)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>Program (program)](#apidoc.element.hbs.handlebars.Compiler.prototype.Program)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>StringLiteral (string)](#apidoc.element.hbs.handlebars.Compiler.prototype.StringLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>SubExpression (sexpr)](#apidoc.element.hbs.handlebars.Compiler.prototype.SubExpression)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>UndefinedLiteral ()](#apidoc.element.hbs.handlebars.Compiler.prototype.UndefinedLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>accept (node)](#apidoc.element.hbs.handlebars.Compiler.prototype.accept)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>addDepth (depth)](#apidoc.element.hbs.handlebars.Compiler.prototype.addDepth)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>ambiguousSexpr (sexpr, program, inverse)](#apidoc.element.hbs.handlebars.Compiler.prototype.ambiguousSexpr)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>blockParamIndex (name)](#apidoc.element.hbs.handlebars.Compiler.prototype.blockParamIndex)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>classifySexpr (sexpr)](#apidoc.element.hbs.handlebars.Compiler.prototype.classifySexpr)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>compile (program, options)](#apidoc.element.hbs.handlebars.Compiler.prototype.compile)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>compileProgram (program)](#apidoc.element.hbs.handlebars.Compiler.prototype.compileProgram)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>compiler ()](#apidoc.element.hbs.handlebars.Compiler.prototype.compiler)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>equals (other)](#apidoc.element.hbs.handlebars.Compiler.prototype.equals)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>helperSexpr (sexpr, program, inverse)](#apidoc.element.hbs.handlebars.Compiler.prototype.helperSexpr)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>opcode (name)](#apidoc.element.hbs.handlebars.Compiler.prototype.opcode)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>pushParam (val)](#apidoc.element.hbs.handlebars.Compiler.prototype.pushParam)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>pushParams (params)](#apidoc.element.hbs.handlebars.Compiler.prototype.pushParams)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>setupFullMustacheParams (sexpr, program, inverse, omitEmpty)](#apidoc.element.hbs.handlebars.Compiler.prototype.setupFullMustacheParams)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>simpleSexpr (sexpr)](#apidoc.element.hbs.handlebars.Compiler.prototype.simpleSexpr)
1.  number <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>guid

#### [module hbs.handlebars.HandlebarsEnvironment](#apidoc.module.hbs.handlebars.HandlebarsEnvironment)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.HandlebarsEnvironment)

#### [module hbs.handlebars.HandlebarsEnvironment.prototype](#apidoc.module.hbs.handlebars.HandlebarsEnvironment.prototype)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>constructor (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>log (level)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.log)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>registerDecorator (name, fn)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerDecorator)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>registerHelper (name, fn)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerHelper)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>registerPartial (name, partial)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerPartial)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>unregisterDecorator (name)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterDecorator)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>unregisterHelper (name)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterHelper)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>unregisterPartial (name)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterPartial)
1.  object <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>logger

#### [module hbs.handlebars.JavaScriptCompiler](#apidoc.module.hbs.handlebars.JavaScriptCompiler)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.</span>JavaScriptCompiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.JavaScriptCompiler)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.</span>isValidJavaScriptVariableName (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.isValidJavaScriptVariableName)
1.  object <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.</span>RESERVED_WORDS

#### [module hbs.handlebars.JavaScriptCompiler.prototype](#apidoc.module.hbs.handlebars.JavaScriptCompiler.prototype)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>aliasable (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.aliasable)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>ambiguousBlockValue ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.ambiguousBlockValue)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>append ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.append)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>appendContent (content)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendContent)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>appendEscaped ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendEscaped)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>appendToBuffer (source, location, explicit)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendToBuffer)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>assignToHash (key)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.assignToHash)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>blockValue (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.blockValue)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compile (environment, options, context, asObject)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compile)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compileChildren (environment, options)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compileChildren)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compiler)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compilerInfo ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compilerInfo)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>contextName (context)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.contextName)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>createFunctionContext (asObject)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.createFunctionContext)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>depthedLookup (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.depthedLookup)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>emptyHash (omitEmpty)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.emptyHash)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>flushInline ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.flushInline)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>getContext (depth)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.getContext)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>incrStack ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.incrStack)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>initializeBuffer ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.initializeBuffer)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokeAmbiguous (name, helperCall)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeAmbiguous)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokeHelper (paramSize, name, isSimple)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeHelper)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokeKnownHelper (paramSize, name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeKnownHelper)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokePartial (isDynamic, name, indent)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokePartial)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>isInline ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.isInline)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>lookupBlockParam (blockParamId, parts)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupBlockParam)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>lookupData (depth, parts, strict)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupData)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>lookupOnContext (parts, falsy, strict, scoped)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupOnContext)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>matchExistingProgram (child)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.matchExistingProgram)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>mergeSource (varDeclarations)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.mergeSource)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>nameLookup (parent, name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.nameLookup)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>objectLiteral (obj)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.objectLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>popHash ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.popHash)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>popStack (wrapped)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.popStack)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>preamble ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.preamble)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>programExpression (guid)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.programExpression)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>push (expr)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.push)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushContext ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushContext)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushHash ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushHash)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushId (type, name, child)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushId)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushLiteral (value)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushProgram (guid)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushProgram)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushSource (source)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushSource)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushStackLiteral (item)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushStackLiteral)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushString (string)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushString)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushStringParam (string, type)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushStringParam)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>quotedString (str)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.quotedString)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>registerDecorator (paramSize, name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.registerDecorator)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>replaceStack (callback)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.replaceStack)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>resolvePath (type, parts, i, falsy, strict)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.resolvePath)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>resolvePossibleLambda ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.resolvePossibleLambda)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>setupHelper (paramSize, name, blockHelper)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupHelper)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>setupHelperArgs (helper, paramSize, params, useRegister)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupHelperArgs)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>setupParams (helper, paramSize, params)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupParams)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>topStack ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.topStack)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>topStackName ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.topStackName)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>useRegister (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.useRegister)

#### [module hbs.handlebars.VM](#apidoc.module.hbs.handlebars.VM)
1.  boolean <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>__esModule
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>checkRevision (compilerInfo)](#apidoc.element.hbs.handlebars.VM.checkRevision)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>invokePartial (partial, context, options)](#apidoc.element.hbs.handlebars.VM.invokePartial)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>noop ()](#apidoc.element.hbs.handlebars.VM.noop)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>resolvePartial (partial, context, options)](#apidoc.element.hbs.handlebars.VM.resolvePartial)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>template (templateSpec, env)](#apidoc.element.hbs.handlebars.VM.template)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>wrapProgram (container, i, fn, data, declaredBlockParams, blockParams, depths)](#apidoc.element.hbs.handlebars.VM.wrapProgram)

#### [module hbs.handlebars.decorators](#apidoc.module.hbs.handlebars.decorators)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.decorators.</span>inline (fn, props, container, options)](#apidoc.element.hbs.handlebars.decorators.inline)

#### [module hbs.handlebars.helpers](#apidoc.module.hbs.handlebars.helpers)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>blockHelperMissing (context, options)](#apidoc.element.hbs.handlebars.helpers.blockHelperMissing)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>each (context, options)](#apidoc.element.hbs.handlebars.helpers.each)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>helperMissing ()](#apidoc.element.hbs.handlebars.helpers.helperMissing)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>if (conditional, options)](#apidoc.element.hbs.handlebars.helpers.if)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>log ()](#apidoc.element.hbs.handlebars.helpers.log)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>lookup (obj, field)](#apidoc.element.hbs.handlebars.helpers.lookup)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>unless (conditional, options)](#apidoc.element.hbs.handlebars.helpers.unless)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>with (context, options)](#apidoc.element.hbs.handlebars.helpers.with)

#### [module hbs.handlebars.logger](#apidoc.module.hbs.handlebars.logger)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.logger.</span>log (level)](#apidoc.element.hbs.handlebars.logger.log)
1.  [function <span class="apidocSignatureSpan">hbs.handlebars.logger.</span>lookupLevel (level)](#apidoc.element.hbs.handlebars.logger.lookupLevel)
1.  object <span class="apidocSignatureSpan">hbs.handlebars.logger.</span>methodMap
1.  string <span class="apidocSignatureSpan">hbs.handlebars.logger.</span>level



# <a name="apidoc.module.hbs"></a>[module hbs](#apidoc.module.hbs)

#### <a name="apidoc.element.hbs.SafeString"></a>[function <span class="apidocSignatureSpan">hbs.</span>SafeString (string)](#apidoc.element.hbs.SafeString)
- description and source-code
```javascript
function SafeString(string) {
  this.string = string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.__express"></a>[function <span class="apidocSignatureSpan">hbs.</span>__express ()](#apidoc.element.hbs.__express)
- description and source-code
```javascript
__express = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.create"></a>[function <span class="apidocSignatureSpan">hbs.</span>create (handlebars)](#apidoc.element.hbs.create)
- description and source-code
```javascript
create = function (handlebars) {
  return new Instance(handlebars);
}
```
- example usage
```shell
...

### more than one instance ###
You can create isolated instances of hbs using the 'create()' function on the module object.

'''
var hbs = require('hbs');

var instance1 = hbs.create();
var instance2 = hbs.create();

app.engine('html', instance1.__express);
app.engine('hbs', instance2.__express);
'''

Each instance has the same methods/properties as the 'hbs' module object. The module object is actually just an instance created
 for you automatically.
...
```

#### <a name="apidoc.element.hbs.handlebars.Compiler"></a>[function <span class="apidocSignatureSpan">hbs.</span>handlebars.Compiler ()](#apidoc.element.hbs.handlebars.Compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment"></a>[function <span class="apidocSignatureSpan">hbs.</span>handlebars.HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler"></a>[function <span class="apidocSignatureSpan">hbs.</span>handlebars.JavaScriptCompiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.SafeString"></a>[module hbs.SafeString](#apidoc.module.hbs.SafeString)

#### <a name="apidoc.element.hbs.SafeString.SafeString"></a>[function <span class="apidocSignatureSpan">hbs.</span>SafeString (string)](#apidoc.element.hbs.SafeString.SafeString)
- description and source-code
```javascript
function SafeString(string) {
  this.string = string;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.SafeString.prototype"></a>[module hbs.SafeString.prototype](#apidoc.module.hbs.SafeString.prototype)

#### <a name="apidoc.element.hbs.SafeString.prototype.toHTML"></a>[function <span class="apidocSignatureSpan">hbs.SafeString.prototype.</span>toHTML ()](#apidoc.element.hbs.SafeString.prototype.toHTML)
- description and source-code
```javascript
toHTML = function () {
  return '' + this.string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.SafeString.prototype.toString"></a>[function <span class="apidocSignatureSpan">hbs.SafeString.prototype.</span>toString ()](#apidoc.element.hbs.SafeString.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return '' + this.string;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.Utils"></a>[module hbs.Utils](#apidoc.module.hbs.Utils)

#### <a name="apidoc.element.hbs.Utils.appendContextPath"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>appendContextPath (contextPath, id)](#apidoc.element.hbs.Utils.appendContextPath)
- description and source-code
```javascript
function appendContextPath(contextPath, id) {
  return (contextPath ? contextPath + '.' : '') + id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.blockParams"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>blockParams (params, ids)](#apidoc.element.hbs.Utils.blockParams)
- description and source-code
```javascript
function blockParams(params, ids) {
  params.path = ids;
  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.createFrame"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>createFrame (object)](#apidoc.element.hbs.Utils.createFrame)
- description and source-code
```javascript
function createFrame(object) {
  var frame = extend({}, object);
  frame._parent = object;
  return frame;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.escapeExpression"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>escapeExpression (string)](#apidoc.element.hbs.Utils.escapeExpression)
- description and source-code
```javascript
function escapeExpression(string) {
  if (typeof string !== 'string') {
    // don't escape SafeStrings, since they're already safe
    if (string && string.toHTML) {
      return string.toHTML();
    } else if (string == null) {
      return '';
    } else if (!string) {
      return string + '';
    }

    // Force a string conversion as this will be done by the append regardless and
    // the regex test will do this transparently behind the scenes, causing issues if
    // an object's to string has escaped characters in it.
    string = '' + string;
  }

  if (!possible.test(string)) {
    return string;
  }
  return string.replace(badChars, escapeChar);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.extend"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>extend (obj)](#apidoc.element.hbs.Utils.extend)
- description and source-code
```javascript
function extend(obj) {
  for (var i = 1; i < arguments.length; i++) {
    for (var key in arguments[i]) {
      if (Object.prototype.hasOwnProperty.call(arguments[i], key)) {
        obj[key] = arguments[i][key];
      }
    }
  }

  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.indexOf"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>indexOf (array, value)](#apidoc.element.hbs.Utils.indexOf)
- description and source-code
```javascript
function indexOf(array, value) {
  for (var i = 0, len = array.length; i < len; i++) {
    if (array[i] === value) {
      return i;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.isArray"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>isArray ()](#apidoc.element.hbs.Utils.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.isEmpty"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>isEmpty (value)](#apidoc.element.hbs.Utils.isEmpty)
- description and source-code
```javascript
function isEmpty(value) {
  if (!value && value !== 0) {
    return true;
  } else if (isArray(value) && value.length === 0) {
    return true;
  } else {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.Utils.isFunction"></a>[function <span class="apidocSignatureSpan">hbs.Utils.</span>isFunction (value)](#apidoc.element.hbs.Utils.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  return typeof value === 'function';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars"></a>[module hbs.handlebars](#apidoc.module.hbs.handlebars)

#### <a name="apidoc.element.hbs.handlebars.Compiler"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>Compiler ()](#apidoc.element.hbs.handlebars.Compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Exception"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>Exception (message, node)](#apidoc.element.hbs.handlebars.Exception)
- description and source-code
```javascript
function Exception(message, node) {
  var loc = node && node.loc,
      line = undefined,
      column = undefined;
  if (loc) {
    line = loc.start.line;
    column = loc.start.column;

    message += ' - ' + line + ':' + column;
  }

  var tmp = Error.prototype.constructor.call(this, message);

  // Unfortunately errors are not enumerable in Chrome (at least), so 'for prop in tmp' doesn't work.
  for (var idx = 0; idx < errorProps.length; idx++) {
    this[errorProps[idx]] = tmp[errorProps[idx]];
  }

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (Error.captureStackTrace) {
    Error.captureStackTrace(this, Exception);
  }

  if (loc) {
    this.lineNumber = line;
    this.column = column;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>JavaScriptCompiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.SafeString"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>SafeString (string)](#apidoc.element.hbs.handlebars.SafeString)
- description and source-code
```javascript
function SafeString(string) {
  this.string = string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.compile"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>compile (input, options)](#apidoc.element.hbs.handlebars.compile)
- description and source-code
```javascript
compile = function (input, options) {
  return _handlebarsCompilerCompiler.compile(input, options, hb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.createFrame"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>createFrame (object)](#apidoc.element.hbs.handlebars.createFrame)
- description and source-code
```javascript
function createFrame(object) {
  var frame = extend({}, object);
  frame._parent = object;
  return frame;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.escapeExpression"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>escapeExpression (string)](#apidoc.element.hbs.handlebars.escapeExpression)
- description and source-code
```javascript
function escapeExpression(string) {
  if (typeof string !== 'string') {
    // don't escape SafeStrings, since they're already safe
    if (string && string.toHTML) {
      return string.toHTML();
    } else if (string == null) {
      return '';
    } else if (!string) {
      return string + '';
    }

    // Force a string conversion as this will be done by the append regardless and
    // the regex test will do this transparently behind the scenes, causing issues if
    // an object's to string has escaped characters in it.
    string = '' + string;
  }

  if (!possible.test(string)) {
    return string;
  }
  return string.replace(badChars, escapeChar);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.log"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>log (level)](#apidoc.element.hbs.handlebars.log)
- description and source-code
```javascript
function log(level) {
  level = logger.lookupLevel(level);

  if (typeof console !== 'undefined' && logger.lookupLevel(logger.level) <= level) {
    var method = logger.methodMap[level];
    if (!console[method]) {
      // eslint-disable-line no-console
      method = 'log';
    }

    for (var _len = arguments.length, message = Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
      message[_key - 1] = arguments[_key];
    }

    console[method].apply(console, message); // eslint-disable-line no-console
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.parse"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>parse (input, options)](#apidoc.element.hbs.handlebars.parse)
- description and source-code
```javascript
function parse(input, options) {
  // Just return if an already-compiled AST was passed in.
  if (input.type === 'Program') {
    return input;
  }

  _parser2['default'].yy = yy;

  // Altering the shared object here, but this is ok as parser is a sync operation
  yy.locInfo = function (locInfo) {
    return new yy.SourceLocation(options && options.srcName, locInfo);
  };

  var strip = new _whitespaceControl2['default'](options);
  return strip.accept(_parser2['default'].parse(input));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.precompile"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>precompile (input, options)](#apidoc.element.hbs.handlebars.precompile)
- description and source-code
```javascript
precompile = function (input, options) {
  return _handlebarsCompilerCompiler.precompile(input, options, hb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.template"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>template (spec)](#apidoc.element.hbs.handlebars.template)
- description and source-code
```javascript
template = function (spec) {
  return runtime.template(spec, hb);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.Compiler"></a>[module hbs.handlebars.Compiler](#apidoc.module.hbs.handlebars.Compiler)

#### <a name="apidoc.element.hbs.handlebars.Compiler.Compiler"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>Compiler ()](#apidoc.element.hbs.handlebars.Compiler.Compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.Compiler.prototype"></a>[module hbs.handlebars.Compiler.prototype](#apidoc.module.hbs.handlebars.Compiler.prototype)

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.BlockStatement"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>BlockStatement (block)](#apidoc.element.hbs.handlebars.Compiler.prototype.BlockStatement)
- description and source-code
```javascript
function BlockStatement(block) {
  transformLiteralToPath(block);

  var program = block.program,
      inverse = block.inverse;

  program = program && this.compileProgram(program);
  inverse = inverse && this.compileProgram(inverse);

  var type = this.classifySexpr(block);

  if (type === 'helper') {
    this.helperSexpr(block, program, inverse);
  } else if (type === 'simple') {
    this.simpleSexpr(block);

    // now that the simple mustache is resolved, we need to
    // evaluate it by executing 'blockHelperMissing'
    this.opcode('pushProgram', program);
    this.opcode('pushProgram', inverse);
    this.opcode('emptyHash');
    this.opcode('blockValue', block.path.original);
  } else {
    this.ambiguousSexpr(block, program, inverse);

    // now that the simple mustache is resolved, we need to
    // evaluate it by executing 'blockHelperMissing'
    this.opcode('pushProgram', program);
    this.opcode('pushProgram', inverse);
    this.opcode('emptyHash');
    this.opcode('ambiguousBlockValue');
  }

  this.opcode('append');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.BooleanLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>BooleanLiteral (bool)](#apidoc.element.hbs.handlebars.Compiler.prototype.BooleanLiteral)
- description and source-code
```javascript
function BooleanLiteral(bool) {
  this.opcode('pushLiteral', bool.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.CommentStatement"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>CommentStatement ()](#apidoc.element.hbs.handlebars.Compiler.prototype.CommentStatement)
- description and source-code
```javascript
function CommentStatement() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.ContentStatement"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>ContentStatement (content)](#apidoc.element.hbs.handlebars.Compiler.prototype.ContentStatement)
- description and source-code
```javascript
function ContentStatement(content) {
  if (content.value) {
    this.opcode('appendContent', content.value);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.Decorator"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>Decorator (decorator)](#apidoc.element.hbs.handlebars.Compiler.prototype.Decorator)
- description and source-code
```javascript
function Decorator(decorator) {
  this.DecoratorBlock(decorator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.DecoratorBlock"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>DecoratorBlock (decorator)](#apidoc.element.hbs.handlebars.Compiler.prototype.DecoratorBlock)
- description and source-code
```javascript
function DecoratorBlock(decorator) {
  var program = decorator.program && this.compileProgram(decorator.program);
  var params = this.setupFullMustacheParams(decorator, program, undefined),
      path = decorator.path;

  this.useDecorators = true;
  this.opcode('registerDecorator', params.length, path.original);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.Hash"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>Hash (hash)](#apidoc.element.hbs.handlebars.Compiler.prototype.Hash)
- description and source-code
```javascript
function Hash(hash) {
  var pairs = hash.pairs,
      i = 0,
      l = pairs.length;

  this.opcode('pushHash');

  for (; i < l; i++) {
    this.pushParam(pairs[i].value);
  }
  while (i--) {
    this.opcode('assignToHash', pairs[i].key);
  }
  this.opcode('popHash');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.MustacheStatement"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>MustacheStatement (mustache)](#apidoc.element.hbs.handlebars.Compiler.prototype.MustacheStatement)
- description and source-code
```javascript
function MustacheStatement(mustache) {
  this.SubExpression(mustache);

  if (mustache.escaped && !this.options.noEscape) {
    this.opcode('appendEscaped');
  } else {
    this.opcode('append');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.NullLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>NullLiteral ()](#apidoc.element.hbs.handlebars.Compiler.prototype.NullLiteral)
- description and source-code
```javascript
function NullLiteral() {
  this.opcode('pushLiteral', 'null');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.NumberLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>NumberLiteral (number)](#apidoc.element.hbs.handlebars.Compiler.prototype.NumberLiteral)
- description and source-code
```javascript
function NumberLiteral(number) {
  this.opcode('pushLiteral', number.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.PartialBlockStatement"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>PartialBlockStatement (partialBlock)](#apidoc.element.hbs.handlebars.Compiler.prototype.PartialBlockStatement)
- description and source-code
```javascript
function PartialBlockStatement(partialBlock) {
  this.PartialStatement(partialBlock);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.PartialStatement"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>PartialStatement (partial)](#apidoc.element.hbs.handlebars.Compiler.prototype.PartialStatement)
- description and source-code
```javascript
function PartialStatement(partial) {
  this.usePartial = true;

  var program = partial.program;
  if (program) {
    program = this.compileProgram(partial.program);
  }

  var params = partial.params;
  if (params.length > 1) {
    throw new _exception2['default']('Unsupported number of partial arguments: ' + params.length, partial);
  } else if (!params.length) {
    if (this.options.explicitPartialContext) {
      this.opcode('pushLiteral', 'undefined');
    } else {
      params.push({ type: 'PathExpression', parts: [], depth: 0 });
    }
  }

  var partialName = partial.name.original,
      isDynamic = partial.name.type === 'SubExpression';
  if (isDynamic) {
    this.accept(partial.name);
  }

  this.setupFullMustacheParams(partial, program, undefined, true);

  var indent = partial.indent || '';
  if (this.options.preventIndent && indent) {
    this.opcode('appendContent', indent);
    indent = '';
  }

  this.opcode('invokePartial', isDynamic, partialName, indent);
  this.opcode('append');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.PathExpression"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>PathExpression (path)](#apidoc.element.hbs.handlebars.Compiler.prototype.PathExpression)
- description and source-code
```javascript
function PathExpression(path) {
  this.addDepth(path.depth);
  this.opcode('getContext', path.depth);

  var name = path.parts[0],
      scoped = _ast2['default'].helpers.scopedId(path),
      blockParamId = !path.depth && !scoped && this.blockParamIndex(name);

  if (blockParamId) {
    this.opcode('lookupBlockParam', blockParamId, path.parts);
  } else if (!name) {
    // Context reference, i.e. '{{foo .}}' or '{{foo ..}}'
    this.opcode('pushContext');
  } else if (path.data) {
    this.options.data = true;
    this.opcode('lookupData', path.depth, path.parts, path.strict);
  } else {
    this.opcode('lookupOnContext', path.parts, path.falsy, path.strict, scoped);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.Program"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>Program (program)](#apidoc.element.hbs.handlebars.Compiler.prototype.Program)
- description and source-code
```javascript
function Program(program) {
  this.options.blockParams.unshift(program.blockParams);

  var body = program.body,
      bodyLength = body.length;
  for (var i = 0; i < bodyLength; i++) {
    this.accept(body[i]);
  }

  this.options.blockParams.shift();

  this.isSimple = bodyLength === 1;
  this.blockParams = program.blockParams ? program.blockParams.length : 0;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.StringLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>StringLiteral (string)](#apidoc.element.hbs.handlebars.Compiler.prototype.StringLiteral)
- description and source-code
```javascript
function StringLiteral(string) {
  this.opcode('pushString', string.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.SubExpression"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>SubExpression (sexpr)](#apidoc.element.hbs.handlebars.Compiler.prototype.SubExpression)
- description and source-code
```javascript
function SubExpression(sexpr) {
  transformLiteralToPath(sexpr);
  var type = this.classifySexpr(sexpr);

  if (type === 'simple') {
    this.simpleSexpr(sexpr);
  } else if (type === 'helper') {
    this.helperSexpr(sexpr);
  } else {
    this.ambiguousSexpr(sexpr);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.UndefinedLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>UndefinedLiteral ()](#apidoc.element.hbs.handlebars.Compiler.prototype.UndefinedLiteral)
- description and source-code
```javascript
function UndefinedLiteral() {
  this.opcode('pushLiteral', 'undefined');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.accept"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>accept (node)](#apidoc.element.hbs.handlebars.Compiler.prototype.accept)
- description and source-code
```javascript
function accept(node) {
<span class="apidocCodeCommentSpan">  /* istanbul ignore next: Sanity code */
</span>  if (!this[node.type]) {
    throw new _exception2['default']('Unknown type: ' + node.type, node);
  }

  this.sourceNode.unshift(node);
  var ret = this[node.type](node);
  this.sourceNode.shift();
  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.addDepth"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>addDepth (depth)](#apidoc.element.hbs.handlebars.Compiler.prototype.addDepth)
- description and source-code
```javascript
function addDepth(depth) {
  if (!depth) {
    return;
  }

  this.useDepths = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.ambiguousSexpr"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>ambiguousSexpr (sexpr, program, inverse)](#apidoc.element.hbs.handlebars.Compiler.prototype.ambiguousSexpr)
- description and source-code
```javascript
function ambiguousSexpr(sexpr, program, inverse) {
  var path = sexpr.path,
      name = path.parts[0],
      isBlock = program != null || inverse != null;

  this.opcode('getContext', path.depth);

  this.opcode('pushProgram', program);
  this.opcode('pushProgram', inverse);

  path.strict = true;
  this.accept(path);

  this.opcode('invokeAmbiguous', name, isBlock);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.blockParamIndex"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>blockParamIndex (name)](#apidoc.element.hbs.handlebars.Compiler.prototype.blockParamIndex)
- description and source-code
```javascript
function blockParamIndex(name) {
  for (var depth = 0, len = this.options.blockParams.length; depth < len; depth++) {
    var blockParams = this.options.blockParams[depth],
        param = blockParams && _utils.indexOf(blockParams, name);
    if (blockParams && param >= 0) {
      return [depth, param];
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.classifySexpr"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>classifySexpr (sexpr)](#apidoc.element.hbs.handlebars.Compiler.prototype.classifySexpr)
- description and source-code
```javascript
function classifySexpr(sexpr) {
  var isSimple = _ast2['default'].helpers.simpleId(sexpr.path);

  var isBlockParam = isSimple && !!this.blockParamIndex(sexpr.path.parts[0]);

  // a mustache is an eligible helper if:
  // * its id is simple (a single part, not 'this' or '..')
  var isHelper = !isBlockParam && _ast2['default'].helpers.helperExpression(sexpr);

  // if a mustache is an eligible helper but not a definite
  // helper, it is ambiguous, and will be resolved in a later
  // pass or at runtime.
  var isEligible = !isBlockParam && (isHelper || isSimple);

  // if ambiguous, we can possibly resolve the ambiguity now
  // An eligible helper is one that does not have a complex path, i.e. 'this.foo', '../foo' etc.
  if (isEligible && !isHelper) {
    var _name2 = sexpr.path.parts[0],
        options = this.options;

    if (options.knownHelpers[_name2]) {
      isHelper = true;
    } else if (options.knownHelpersOnly) {
      isEligible = false;
    }
  }

  if (isHelper) {
    return 'helper';
  } else if (isEligible) {
    return 'ambiguous';
  } else {
    return 'simple';
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.compile"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>compile (program, options)](#apidoc.element.hbs.handlebars.Compiler.prototype.compile)
- description and source-code
```javascript
function compile(program, options) {
  this.sourceNode = [];
  this.opcodes = [];
  this.children = [];
  this.options = options;
  this.stringParams = options.stringParams;
  this.trackIds = options.trackIds;

  options.blockParams = options.blockParams || [];

  // These changes will propagate to the other compiler components
  var knownHelpers = options.knownHelpers;
  options.knownHelpers = {
    'helperMissing': true,
    'blockHelperMissing': true,
    'each': true,
    'if': true,
    'unless': true,
    'with': true,
    'log': true,
    'lookup': true
  };
  if (knownHelpers) {
    for (var _name in knownHelpers) {
<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (_name in knownHelpers) {
        options.knownHelpers[_name] = knownHelpers[_name];
      }
    }
  }

  return this.accept(program);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.compileProgram"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>compileProgram (program)](#apidoc.element.hbs.handlebars.Compiler.prototype.compileProgram)
- description and source-code
```javascript
function compileProgram(program) {
  var childCompiler = new this.compiler(),
      // eslint-disable-line new-cap
  result = childCompiler.compile(program, this.options),
      guid = this.guid++;

  this.usePartial = this.usePartial || result.usePartial;

  this.children[guid] = result;
  this.useDepths = this.useDepths || result.useDepths;

  return guid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.compiler"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>compiler ()](#apidoc.element.hbs.handlebars.Compiler.prototype.compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.equals"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>equals (other)](#apidoc.element.hbs.handlebars.Compiler.prototype.equals)
- description and source-code
```javascript
function equals(other) {
  var len = this.opcodes.length;
  if (other.opcodes.length !== len) {
    return false;
  }

  for (var i = 0; i < len; i++) {
    var opcode = this.opcodes[i],
        otherOpcode = other.opcodes[i];
    if (opcode.opcode !== otherOpcode.opcode || !argEquals(opcode.args, otherOpcode.args)) {
      return false;
    }
  }

  // We know that length is the same between the two arrays because they are directly tied
  // to the opcode behavior above.
  len = this.children.length;
  for (var i = 0; i < len; i++) {
    if (!this.children[i].equals(other.children[i])) {
      return false;
    }
  }

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.helperSexpr"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>helperSexpr (sexpr, program, inverse)](#apidoc.element.hbs.handlebars.Compiler.prototype.helperSexpr)
- description and source-code
```javascript
function helperSexpr(sexpr, program, inverse) {
  var params = this.setupFullMustacheParams(sexpr, program, inverse),
      path = sexpr.path,
      name = path.parts[0];

  if (this.options.knownHelpers[name]) {
    this.opcode('invokeKnownHelper', params.length, name);
  } else if (this.options.knownHelpersOnly) {
    throw new _exception2['default']('You specified knownHelpersOnly, but used the unknown helper ' + name, sexpr);
  } else {
    path.strict = true;
    path.falsy = true;

    this.accept(path);
    this.opcode('invokeHelper', params.length, path.original, _ast2['default'].helpers.simpleId(path));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.opcode"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>opcode (name)](#apidoc.element.hbs.handlebars.Compiler.prototype.opcode)
- description and source-code
```javascript
function opcode(name) {
  this.opcodes.push({ opcode: name, args: slice.call(arguments, 1), loc: this.sourceNode[0].loc });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.pushParam"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>pushParam (val)](#apidoc.element.hbs.handlebars.Compiler.prototype.pushParam)
- description and source-code
```javascript
function pushParam(val) {
  var value = val.value != null ? val.value : val.original || '';

  if (this.stringParams) {
    if (value.replace) {
      value = value.replace(/^(\.?\.\/)*/g, '').replace(/\//g, '.');
    }

    if (val.depth) {
      this.addDepth(val.depth);
    }
    this.opcode('getContext', val.depth || 0);
    this.opcode('pushStringParam', value, val.type);

    if (val.type === 'SubExpression') {
      // SubExpressions get evaluated and passed in
      // in string params mode.
      this.accept(val);
    }
  } else {
    if (this.trackIds) {
      var blockParamIndex = undefined;
      if (val.parts && !_ast2['default'].helpers.scopedId(val) && !val.depth) {
        blockParamIndex = this.blockParamIndex(val.parts[0]);
      }
      if (blockParamIndex) {
        var blockParamChild = val.parts.slice(1).join('.');
        this.opcode('pushId', 'BlockParam', blockParamIndex, blockParamChild);
      } else {
        value = val.original || value;
        if (value.replace) {
          value = value.replace(/^this(?:\.|$)/, '').replace(/^\.\//, '').replace(/^\.$/, '');
        }

        this.opcode('pushId', val.type, value);
      }
    }
    this.accept(val);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.pushParams"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>pushParams (params)](#apidoc.element.hbs.handlebars.Compiler.prototype.pushParams)
- description and source-code
```javascript
function pushParams(params) {
  for (var i = 0, l = params.length; i < l; i++) {
    this.pushParam(params[i]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.setupFullMustacheParams"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>setupFullMustacheParams (sexpr, program, inverse, omitEmpty)](#apidoc.element.hbs.handlebars.Compiler.prototype.setupFullMustacheParams)
- description and source-code
```javascript
function setupFullMustacheParams(sexpr, program, inverse, omitEmpty) {
  var params = sexpr.params;
  this.pushParams(params);

  this.opcode('pushProgram', program);
  this.opcode('pushProgram', inverse);

  if (sexpr.hash) {
    this.accept(sexpr.hash);
  } else {
    this.opcode('emptyHash', omitEmpty);
  }

  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.Compiler.prototype.simpleSexpr"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.Compiler.prototype.</span>simpleSexpr (sexpr)](#apidoc.element.hbs.handlebars.Compiler.prototype.simpleSexpr)
- description and source-code
```javascript
function simpleSexpr(sexpr) {
  var path = sexpr.path;
  path.strict = true;
  this.accept(path);
  this.opcode('resolvePossibleLambda');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.HandlebarsEnvironment"></a>[module hbs.handlebars.HandlebarsEnvironment](#apidoc.module.hbs.handlebars.HandlebarsEnvironment)

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.HandlebarsEnvironment"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.HandlebarsEnvironment)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.HandlebarsEnvironment.prototype"></a>[module hbs.handlebars.HandlebarsEnvironment.prototype](#apidoc.module.hbs.handlebars.HandlebarsEnvironment.prototype)

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>constructor (helpers, partials, decorators)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.constructor)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.log"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>log (level)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.log)
- description and source-code
```javascript
function log(level) {
  level = logger.lookupLevel(level);

  if (typeof console !== 'undefined' && logger.lookupLevel(logger.level) <= level) {
    var method = logger.methodMap[level];
    if (!console[method]) {
      // eslint-disable-line no-console
      method = 'log';
    }

    for (var _len = arguments.length, message = Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
      message[_key - 1] = arguments[_key];
    }

    console[method].apply(console, message); // eslint-disable-line no-console
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerDecorator"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>registerDecorator (name, fn)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerDecorator)
- description and source-code
```javascript
function registerDecorator(name, fn) {
  if (_utils.toString.call(name) === objectType) {
    if (fn) {
      throw new _exception2['default']('Arg not supported with multiple decorators');
    }
    _utils.extend(this.decorators, name);
  } else {
    this.decorators[name] = fn;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerHelper"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>registerHelper (name, fn)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerHelper)
- description and source-code
```javascript
function registerHelper(name, fn) {
  if (_utils.toString.call(name) === objectType) {
    if (fn) {
      throw new _exception2['default']('Arg not supported with multiple helpers');
    }
    _utils.extend(this.helpers, name);
  } else {
    this.helpers[name] = fn;
  }
}
```
- example usage
```shell
...
## Helpers and Partials ##

hbs exposes the 'registerHelper' and 'registerPartial' method from handlebars.

'''javascript
var hbs = require('hbs');

hbs.registerHelper('helper_name', function(...) { ... });
hbs.registerPartial('partial_name', 'partial value');
'''

For convenience, 'registerPartials' provides a quick way to load all partials from a specific directory:

'''javascript
var hbs = require('hbs');
...
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerPartial"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>registerPartial (name, partial)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.registerPartial)
- description and source-code
```javascript
function registerPartial(name, partial) {
  if (_utils.toString.call(name) === objectType) {
    _utils.extend(this.partials, name);
  } else {
    if (typeof partial === 'undefined') {
      throw new _exception2['default']('Attempting to register a partial called "' + name + '" as undefined');
    }
    this.partials[name] = partial;
  }
}
```
- example usage
```shell
...

hbs exposes the 'registerHelper' and 'registerPartial' method from handlebars.

'''javascript
var hbs = require('hbs');

hbs.registerHelper('helper_name', function(...) { ... });
hbs.registerPartial('partial_name', 'partial value');
'''

For convenience, 'registerPartials' provides a quick way to load all partials from a specific directory:

'''javascript
var hbs = require('hbs');
...
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterDecorator"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>unregisterDecorator (name)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterDecorator)
- description and source-code
```javascript
function unregisterDecorator(name) {
  delete this.decorators[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterHelper"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>unregisterHelper (name)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterHelper)
- description and source-code
```javascript
function unregisterHelper(name) {
  delete this.helpers[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterPartial"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.HandlebarsEnvironment.prototype.</span>unregisterPartial (name)](#apidoc.element.hbs.handlebars.HandlebarsEnvironment.prototype.unregisterPartial)
- description and source-code
```javascript
function unregisterPartial(name) {
  delete this.partials[name];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.JavaScriptCompiler"></a>[module hbs.handlebars.JavaScriptCompiler](#apidoc.module.hbs.handlebars.JavaScriptCompiler)

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.JavaScriptCompiler"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.</span>JavaScriptCompiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.JavaScriptCompiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.isValidJavaScriptVariableName"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.</span>isValidJavaScriptVariableName (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.isValidJavaScriptVariableName)
- description and source-code
```javascript
isValidJavaScriptVariableName = function (name) {
  return !JavaScriptCompiler.RESERVED_WORDS[name] && /^[a-zA-Z_$][0-9a-zA-Z_$]*$/.test(name);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.JavaScriptCompiler.prototype"></a>[module hbs.handlebars.JavaScriptCompiler.prototype](#apidoc.module.hbs.handlebars.JavaScriptCompiler.prototype)

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.aliasable"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>aliasable (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.aliasable)
- description and source-code
```javascript
function aliasable(name) {
  var ret = this.aliases[name];
  if (ret) {
    ret.referenceCount++;
    return ret;
  }

  ret = this.aliases[name] = this.source.wrap(name);
  ret.aliasable = true;
  ret.referenceCount = 1;

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.ambiguousBlockValue"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>ambiguousBlockValue ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.ambiguousBlockValue)
- description and source-code
```javascript
function ambiguousBlockValue() {
  // We're being a bit cheeky and reusing the options value from the prior exec
  var blockHelperMissing = this.aliasable('helpers.blockHelperMissing'),
      params = [this.contextName(0)];
  this.setupHelperArgs('', 0, params, true);

  this.flushInline();

  var current = this.topStack();
  params.splice(1, 0, current);

  this.pushSource(['if (!', this.lastHelper, ') { ', current, ' = ', this.source.functionCall(blockHelperMissing, 'call', params
), '}']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.append"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>append ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.append)
- description and source-code
```javascript
function append() {
  if (this.isInline()) {
    this.replaceStack(function (current) {
      return [' != null ? ', current, ' : ""'];
    });

    this.pushSource(this.appendToBuffer(this.popStack()));
  } else {
    var local = this.popStack();
    this.pushSource(['if (', local, ' != null) { ', this.appendToBuffer(local, undefined, true), ' }']);
    if (this.environment.isSimple) {
      this.pushSource(['else { ', this.appendToBuffer("''", undefined, true), ' }']);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendContent"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>appendContent (content)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendContent)
- description and source-code
```javascript
function appendContent(content) {
  if (this.pendingContent) {
    content = this.pendingContent + content;
  } else {
    this.pendingLocation = this.source.currentLocation;
  }

  this.pendingContent = content;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendEscaped"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>appendEscaped ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendEscaped)
- description and source-code
```javascript
function appendEscaped() {
  this.pushSource(this.appendToBuffer([this.aliasable('container.escapeExpression'), '(', this.popStack(), ')']));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendToBuffer"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>appendToBuffer (source, location, explicit)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.appendToBuffer)
- description and source-code
```javascript
function appendToBuffer(source, location, explicit) {
  // Force a source as this simplifies the merge logic.
  if (!_utils.isArray(source)) {
    source = [source];
  }
  source = this.source.wrap(source, location);

  if (this.environment.isSimple) {
    return ['return ', source, ';'];
  } else if (explicit) {
    // This is a case where the buffer operation occurs as a child of another
    // construct, generally braces. We have to explicitly output these buffer
    // operations to ensure that the emitted code goes in the correct location.
    return ['buffer += ', source, ';'];
  } else {
    source.appendToBuffer = true;
    return source;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.assignToHash"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>assignToHash (key)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.assignToHash)
- description and source-code
```javascript
function assignToHash(key) {
  var value = this.popStack(),
      context = undefined,
      type = undefined,
      id = undefined;

  if (this.trackIds) {
    id = this.popStack();
  }
  if (this.stringParams) {
    type = this.popStack();
    context = this.popStack();
  }

  var hash = this.hash;
  if (context) {
    hash.contexts[key] = context;
  }
  if (type) {
    hash.types[key] = type;
  }
  if (id) {
    hash.ids[key] = id;
  }
  hash.values[key] = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.blockValue"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>blockValue (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.blockValue)
- description and source-code
```javascript
function blockValue(name) {
  var blockHelperMissing = this.aliasable('helpers.blockHelperMissing'),
      params = [this.contextName(0)];
  this.setupHelperArgs(name, 0, params);

  var blockName = this.popStack();
  params.splice(1, 0, blockName);

  this.push(this.source.functionCall(blockHelperMissing, 'call', params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compile"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compile (environment, options, context, asObject)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compile)
- description and source-code
```javascript
function compile(environment, options, context, asObject) {
  this.environment = environment;
  this.options = options;
  this.stringParams = this.options.stringParams;
  this.trackIds = this.options.trackIds;
  this.precompile = !asObject;

  this.name = this.environment.name;
  this.isChild = !!context;
  this.context = context || {
    decorators: [],
    programs: [],
    environments: []
  };

  this.preamble();

  this.stackSlot = 0;
  this.stackVars = [];
  this.aliases = {};
  this.registers = { list: [] };
  this.hashes = [];
  this.compileStack = [];
  this.inlineStack = [];
  this.blockParams = [];

  this.compileChildren(environment, options);

  this.useDepths = this.useDepths || environment.useDepths || environment.useDecorators || this.options.compat;
  this.useBlockParams = this.useBlockParams || environment.useBlockParams;

  var opcodes = environment.opcodes,
      opcode = undefined,
      firstLoc = undefined,
      i = undefined,
      l = undefined;

  for (i = 0, l = opcodes.length; i < l; i++) {
    opcode = opcodes[i];

    this.source.currentLocation = opcode.loc;
    firstLoc = firstLoc || opcode.loc;
    this[opcode.opcode].apply(this, opcode.args);
  }

  // Flush any trailing content that might be pending.
  this.source.currentLocation = firstLoc;
  this.pushSource('');

<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  if (this.stackSlot || this.inlineStack.length || this.compileStack.length) {
    throw new _exception2['default']('Compile completed with content left on stack');
  }

  if (!this.decorators.isEmpty()) {
    this.useDecorators = true;

    this.decorators.prepend('var decorators = container.decorators;\n');
    this.decorators.push('return fn;');

    if (asObject) {
      this.decorators = Function.apply(this, ['fn', 'props', 'container', 'depth0', 'data', 'blockParams', 'depths', this.decorators
.merge()]);
    } else {
      this.decorators.prepend('function(fn, props, container, depth0, data, blockParams, depths) {\n');
      this.decorators.push('}\n');
      this.decorators = this.decorators.merge();
    }
  } else {
    this.decorators = undefined;
  }

  var fn = this.createFunctionContext(asObject);
  if (!this.isChild) {
    var ret = {
      compiler: this.compilerInfo(),
      main: fn
    };

    if (this.decorators) {
      ret.main_d = this.decorators; // eslint-disable-line camelcase
      ret.useDecorators = true;
    }

    var _context = this.context;
    var programs = _context.programs;
    var decorators = _context.decorators;

    for (i = 0, l = programs.length; i < l; i++) {
      if (programs[i]) {
        ret[i] = programs[i];
        if (decorators[i]) {
          ret[i + '_d'] = decorators[i];
          ret.useDecorators = true;
        }
      }
    }

    if (this.environment.usePartial) {
      ret.usePartial = true;
    }
    if (this.options.data) {
      ret.useData = true;
    }
    if (this.useDepths) {
      ret.useDepths = true;
    }
    if (this.useBlockParams) {
      ret.useBlockParams = true;
    }
    if (this.options.compat) {
      ret.compat = true;
    }

    if (!asObject) {
      ret.compiler = JSON.stringify(ret.compiler);

      this.source.currentLocation = { start: { line: 1, column: 0 } };
      ret = this.objectLiteral(ret);

      if (options.srcName) {
        ret = ret.toStringWithSourceMap({ file: options.destName });
        ret.map = ret.map && ret.map.toString();
      } else {
        ret = ret.toString();
      }
    } else {
      ret.compilerOptions = this.options;
    }

    return ret;
  } else {
    return fn;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compileChildren"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compileChildren (environment, options)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compileChildren)
- description and source-code
```javascript
function compileChildren(environment, options) {
  var children = environment.children,
      child = undefined,
      compiler = undefined;

  for (var i = 0, l = children.length; i < l; i++) {
    child = children[i];
    compiler = new this.compiler(); // eslint-disable-line new-cap

    var index = this.matchExistingProgram(child);

    if (index == null) {
      this.context.programs.push(''); // Placeholder to prevent name conflicts for nested children
      index = this.context.programs.length;
      child.index = index;
      child.name = 'program' + index;
      this.context.programs[index] = compiler.compile(child, options, this.context, !this.precompile);
      this.context.decorators[index] = compiler.decorators;
      this.context.environments[index] = child;

      this.useDepths = this.useDepths || compiler.useDepths;
      this.useBlockParams = this.useBlockParams || compiler.useBlockParams;
    } else {
      child.index = index;
      child.name = 'program' + index;

      this.useDepths = this.useDepths || child.useDepths;
      this.useBlockParams = this.useBlockParams || child.useBlockParams;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compiler"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compiler ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compilerInfo"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>compilerInfo ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.compilerInfo)
- description and source-code
```javascript
function compilerInfo() {
  var revision = _base.COMPILER_REVISION,
      versions = _base.REVISION_CHANGES[revision];
  return [revision, versions];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.contextName"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>contextName (context)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.contextName)
- description and source-code
```javascript
function contextName(context) {
  if (this.useDepths && context) {
    return 'depths[' + context + ']';
  } else {
    return 'depth' + context;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.createFunctionContext"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>createFunctionContext (asObject)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.createFunctionContext)
- description and source-code
```javascript
function createFunctionContext(asObject) {
  var varDeclarations = '';

  var locals = this.stackVars.concat(this.registers.list);
  if (locals.length > 0) {
    varDeclarations += ', ' + locals.join(', ');
  }

  // Generate minimizer alias mappings
  //
  // When using true SourceNodes, this will update all references to the given alias
  // as the source nodes are reused in situ. For the non-source node compilation mode,
  // aliases will not be used, but this case is already being run on the client and
  // we aren't concern about minimizing the template size.
  var aliasCount = 0;
  for (var alias in this.aliases) {
    // eslint-disable-line guard-for-in
    var node = this.aliases[alias];

    if (this.aliases.hasOwnProperty(alias) && node.children && node.referenceCount > 1) {
      varDeclarations += ', alias' + ++aliasCount + '=' + alias;
      node.children[0] = 'alias' + aliasCount;
    }
  }

  var params = ['container', 'depth0', 'helpers', 'partials', 'data'];

  if (this.useBlockParams || this.useDepths) {
    params.push('blockParams');
  }
  if (this.useDepths) {
    params.push('depths');
  }

  // Perform a second pass over the output to merge content when possible
  var source = this.mergeSource(varDeclarations);

  if (asObject) {
    params.push(source);

    return Function.apply(this, params);
  } else {
    return this.source.wrap(['function(', params.join(','), ') {\n  ', source, '}']);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.depthedLookup"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>depthedLookup (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.depthedLookup)
- description and source-code
```javascript
function depthedLookup(name) {
  return [this.aliasable('container.lookup'), '(depths, "', name, '")'];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.emptyHash"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>emptyHash (omitEmpty)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.emptyHash)
- description and source-code
```javascript
function emptyHash(omitEmpty) {
  if (this.trackIds) {
    this.push('{}'); // hashIds
  }
  if (this.stringParams) {
    this.push('{}'); // hashContexts
    this.push('{}'); // hashTypes
  }
  this.pushStackLiteral(omitEmpty ? 'undefined' : '{}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.flushInline"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>flushInline ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.flushInline)
- description and source-code
```javascript
function flushInline() {
  var inlineStack = this.inlineStack;
  this.inlineStack = [];
  for (var i = 0, len = inlineStack.length; i < len; i++) {
    var entry = inlineStack[i];
<span class="apidocCodeCommentSpan">    /* istanbul ignore if */
</span>    if (entry instanceof Literal) {
      this.compileStack.push(entry);
    } else {
      var stack = this.incrStack();
      this.pushSource([stack, ' = ', entry, ';']);
      this.compileStack.push(stack);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.getContext"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>getContext (depth)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.getContext)
- description and source-code
```javascript
function getContext(depth) {
  this.lastContext = depth;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.incrStack"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>incrStack ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.incrStack)
- description and source-code
```javascript
function incrStack() {
  this.stackSlot++;
  if (this.stackSlot > this.stackVars.length) {
    this.stackVars.push('stack' + this.stackSlot);
  }
  return this.topStackName();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.initializeBuffer"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>initializeBuffer ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.initializeBuffer)
- description and source-code
```javascript
function initializeBuffer() {
  return this.quotedString('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeAmbiguous"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokeAmbiguous (name, helperCall)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeAmbiguous)
- description and source-code
```javascript
function invokeAmbiguous(name, helperCall) {
  this.useRegister('helper');

  var nonHelper = this.popStack();

  this.emptyHash();
  var helper = this.setupHelper(0, name, helperCall);

  var helperName = this.lastHelper = this.nameLookup('helpers', name, 'helper');

  var lookup = ['(', '(helper = ', helperName, ' || ', nonHelper, ')'];
  if (!this.options.strict) {
    lookup[0] = '(helper = ';
    lookup.push(' != null ? helper : ', this.aliasable('helpers.helperMissing'));
  }

  this.push(['(', lookup, helper.paramsInit ? ['),(', helper.paramsInit] : [], '),', '(typeof helper === ', this.aliasable('"function
"'), ' ? ', this.source.functionCall('helper', 'call', helper.callParams), ' : helper))']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeHelper"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokeHelper (paramSize, name, isSimple)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeHelper)
- description and source-code
```javascript
function invokeHelper(paramSize, name, isSimple) {
  var nonHelper = this.popStack(),
      helper = this.setupHelper(paramSize, name),
      simple = isSimple ? [helper.name, ' || '] : '';

  var lookup = ['('].concat(simple, nonHelper);
  if (!this.options.strict) {
    lookup.push(' || ', this.aliasable('helpers.helperMissing'));
  }
  lookup.push(')');

  this.push(this.source.functionCall(lookup, 'call', helper.callParams));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeKnownHelper"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokeKnownHelper (paramSize, name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokeKnownHelper)
- description and source-code
```javascript
function invokeKnownHelper(paramSize, name) {
  var helper = this.setupHelper(paramSize, name);
  this.push(this.source.functionCall(helper.name, 'call', helper.callParams));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokePartial"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>invokePartial (isDynamic, name, indent)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.invokePartial)
- description and source-code
```javascript
function invokePartial(isDynamic, name, indent) {
  var params = [],
      options = this.setupParams(name, 1, params);

  if (isDynamic) {
    name = this.popStack();
    delete options.name;
  }

  if (indent) {
    options.indent = JSON.stringify(indent);
  }
  options.helpers = 'helpers';
  options.partials = 'partials';
  options.decorators = 'container.decorators';

  if (!isDynamic) {
    params.unshift(this.nameLookup('partials', name, 'partial'));
  } else {
    params.unshift(name);
  }

  if (this.options.compat) {
    options.depths = 'depths';
  }
  options = this.objectLiteral(options);
  params.push(options);

  this.push(this.source.functionCall('container.invokePartial', '', params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.isInline"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>isInline ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.isInline)
- description and source-code
```javascript
function isInline() {
  return this.inlineStack.length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupBlockParam"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>lookupBlockParam (blockParamId, parts)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupBlockParam)
- description and source-code
```javascript
function lookupBlockParam(blockParamId, parts) {
  this.useBlockParams = true;

  this.push(['blockParams[', blockParamId[0], '][', blockParamId[1], ']']);
  this.resolvePath('context', parts, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupData"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>lookupData (depth, parts, strict)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupData)
- description and source-code
```javascript
function lookupData(depth, parts, strict) {
  if (!depth) {
    this.pushStackLiteral('data');
  } else {
    this.pushStackLiteral('container.data(data, ' + depth + ')');
  }

  this.resolvePath('data', parts, 0, true, strict);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupOnContext"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>lookupOnContext (parts, falsy, strict, scoped)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.lookupOnContext)
- description and source-code
```javascript
function lookupOnContext(parts, falsy, strict, scoped) {
  var i = 0;

  if (!scoped && this.options.compat && !this.lastContext) {
    // The depthed query is expected to handle the undefined logic for the root level that
    // is implemented below, so we evaluate that directly in compat mode
    this.push(this.depthedLookup(parts[i++]));
  } else {
    this.pushContext();
  }

  this.resolvePath('context', parts, i, falsy, strict);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.matchExistingProgram"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>matchExistingProgram (child)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.matchExistingProgram)
- description and source-code
```javascript
function matchExistingProgram(child) {
  for (var i = 0, len = this.context.environments.length; i < len; i++) {
    var environment = this.context.environments[i];
    if (environment && environment.equals(child)) {
      return i;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.mergeSource"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>mergeSource (varDeclarations)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.mergeSource)
- description and source-code
```javascript
function mergeSource(varDeclarations) {
  var isSimple = this.environment.isSimple,
      appendOnly = !this.forceBuffer,
      appendFirst = undefined,
      sourceSeen = undefined,
      bufferStart = undefined,
      bufferEnd = undefined;
  this.source.each(function (line) {
    if (line.appendToBuffer) {
      if (bufferStart) {
        line.prepend('  + ');
      } else {
        bufferStart = line;
      }
      bufferEnd = line;
    } else {
      if (bufferStart) {
        if (!sourceSeen) {
          appendFirst = true;
        } else {
          bufferStart.prepend('buffer += ');
        }
        bufferEnd.add(';');
        bufferStart = bufferEnd = undefined;
      }

      sourceSeen = true;
      if (!isSimple) {
        appendOnly = false;
      }
    }
  });

  if (appendOnly) {
    if (bufferStart) {
      bufferStart.prepend('return ');
      bufferEnd.add(';');
    } else if (!sourceSeen) {
      this.source.push('return "";');
    }
  } else {
    varDeclarations += ', buffer = ' + (appendFirst ? '' : this.initializeBuffer());

    if (bufferStart) {
      bufferStart.prepend('return buffer + ');
      bufferEnd.add(';');
    } else {
      this.source.push('return buffer;');
    }
  }

  if (varDeclarations) {
    this.source.prepend('var ' + varDeclarations.substring(2) + (appendFirst ? '' : ';\n'));
  }

  return this.source.merge();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.nameLookup"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>nameLookup (parent, name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.nameLookup)
- description and source-code
```javascript
function nameLookup(parent, name) {
  if (JavaScriptCompiler.isValidJavaScriptVariableName(name)) {
    return [parent, '.', name];
  } else {
    return [parent, '[', JSON.stringify(name), ']'];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.objectLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>objectLiteral (obj)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.objectLiteral)
- description and source-code
```javascript
function objectLiteral(obj) {
  return this.source.objectLiteral(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.popHash"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>popHash ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.popHash)
- description and source-code
```javascript
function popHash() {
  var hash = this.hash;
  this.hash = this.hashes.pop();

  if (this.trackIds) {
    this.push(this.objectLiteral(hash.ids));
  }
  if (this.stringParams) {
    this.push(this.objectLiteral(hash.contexts));
    this.push(this.objectLiteral(hash.types));
  }

  this.push(this.objectLiteral(hash.values));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.popStack"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>popStack (wrapped)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.popStack)
- description and source-code
```javascript
function popStack(wrapped) {
  var inline = this.isInline(),
      item = (inline ? this.inlineStack : this.compileStack).pop();

  if (!wrapped && item instanceof Literal) {
    return item.value;
  } else {
    if (!inline) {
<span class="apidocCodeCommentSpan">      /* istanbul ignore next */
</span>      if (!this.stackSlot) {
        throw new _exception2['default']('Invalid stack pop');
      }
      this.stackSlot--;
    }
    return item;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.preamble"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>preamble ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.preamble)
- description and source-code
```javascript
function preamble() {
  // track the last context pushed into place to allow skipping the
  // getContext opcode when it would be a noop
  this.lastContext = 0;
  this.source = new _codeGen2['default'](this.options.srcName);
  this.decorators = new _codeGen2['default'](this.options.srcName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.programExpression"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>programExpression (guid)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.programExpression)
- description and source-code
```javascript
function programExpression(guid) {
  var child = this.environment.children[guid],
      programParams = [child.index, 'data', child.blockParams];

  if (this.useBlockParams || this.useDepths) {
    programParams.push('blockParams');
  }
  if (this.useDepths) {
    programParams.push('depths');
  }

  return 'container.program(' + programParams.join(', ') + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.push"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>push (expr)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.push)
- description and source-code
```javascript
function push(expr) {
  if (!(expr instanceof Literal)) {
    expr = this.source.wrap(expr);
  }

  this.inlineStack.push(expr);
  return expr;
}
```
- example usage
```shell
...

var id = '__' + gen_id() + '__';

var cur_waiter = waiter;
waiter.wait();

args = [].slice.call(args);
args.push(function(res) {
    cur_waiter.resolve(id, res);
})

fn.apply(null, args);

// return the id placeholder
// this will be replaced later
...
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushContext"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushContext ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushContext)
- description and source-code
```javascript
function pushContext() {
  this.pushStackLiteral(this.contextName(this.lastContext));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushHash"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushHash ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushHash)
- description and source-code
```javascript
function pushHash() {
  if (this.hash) {
    this.hashes.push(this.hash);
  }
  this.hash = { values: [], types: [], contexts: [], ids: [] };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushId"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushId (type, name, child)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushId)
- description and source-code
```javascript
function pushId(type, name, child) {
  if (type === 'BlockParam') {
    this.pushStackLiteral('blockParams[' + name[0] + '].path[' + name[1] + ']' + (child ? ' + ' + JSON.stringify('.' + child) : ''));
  } else if (type === 'PathExpression') {
    this.pushString(name);
  } else if (type === 'SubExpression') {
    this.pushStackLiteral('true');
  } else {
    this.pushStackLiteral('null');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushLiteral (value)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushLiteral)
- description and source-code
```javascript
function pushLiteral(value) {
  this.pushStackLiteral(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushProgram"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushProgram (guid)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushProgram)
- description and source-code
```javascript
function pushProgram(guid) {
  if (guid != null) {
    this.pushStackLiteral(this.programExpression(guid));
  } else {
    this.pushStackLiteral(null);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushSource"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushSource (source)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushSource)
- description and source-code
```javascript
function pushSource(source) {
  if (this.pendingContent) {
    this.source.push(this.appendToBuffer(this.source.quotedString(this.pendingContent), this.pendingLocation));
    this.pendingContent = undefined;
  }

  if (source) {
    this.source.push(source);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushStackLiteral"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushStackLiteral (item)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushStackLiteral)
- description and source-code
```javascript
function pushStackLiteral(item) {
  this.push(new Literal(item));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushString"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushString (string)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushString)
- description and source-code
```javascript
function pushString(string) {
  this.pushStackLiteral(this.quotedString(string));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushStringParam"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>pushStringParam (string, type)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.pushStringParam)
- description and source-code
```javascript
function pushStringParam(string, type) {
  this.pushContext();
  this.pushString(type);

  // If it's a subexpression, the string result
  // will be pushed after this opcode.
  if (type !== 'SubExpression') {
    if (typeof string === 'string') {
      this.pushString(string);
    } else {
      this.pushStackLiteral(string);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.quotedString"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>quotedString (str)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.quotedString)
- description and source-code
```javascript
function quotedString(str) {
  return this.source.quotedString(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.registerDecorator"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>registerDecorator (paramSize, name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.registerDecorator)
- description and source-code
```javascript
function registerDecorator(paramSize, name) {
  var foundDecorator = this.nameLookup('decorators', name, 'decorator'),
      options = this.setupHelperArgs(name, paramSize);

  this.decorators.push(['fn = ', this.decorators.functionCall(foundDecorator, '', ['fn', 'props', 'container', options]), ' || fn
;']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.replaceStack"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>replaceStack (callback)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.replaceStack)
- description and source-code
```javascript
function replaceStack(callback) {
  var prefix = ['('],
      stack = undefined,
      createdStack = undefined,
      usedLiteral = undefined;

<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  if (!this.isInline()) {
    throw new _exception2['default']('replaceStack on non-inline');
  }

  // We want to merge the inline statement into the replacement statement via ','
  var top = this.popStack(true);

  if (top instanceof Literal) {
    // Literals do not need to be inlined
    stack = [top.value];
    prefix = ['(', stack];
    usedLiteral = true;
  } else {
    // Get or create the current stack name for use by the inline
    createdStack = true;
    var _name = this.incrStack();

    prefix = ['((', this.push(_name), ' = ', top, ')'];
    stack = this.topStack();
  }

  var item = callback.call(this, stack);

  if (!usedLiteral) {
    this.popStack();
  }
  if (createdStack) {
    this.stackSlot--;
  }
  this.push(prefix.concat(item, ')'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.resolvePath"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>resolvePath (type, parts, i, falsy, strict)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.resolvePath)
- description and source-code
```javascript
function resolvePath(type, parts, i, falsy, strict) {
  // istanbul ignore next

  var _this = this;

  if (this.options.strict || this.options.assumeObjects) {
    this.push(strictLookup(this.options.strict && strict, this, parts, type));
    return;
  }

  var len = parts.length;
  for (; i < len; i++) {
<span class="apidocCodeCommentSpan">    /* eslint-disable no-loop-func */
</span>    this.replaceStack(function (current) {
      var lookup = _this.nameLookup(current, parts[i], type);
      // We want to ensure that zero and false are handled properly if the context (falsy flag)
      // needs to have the special handling for these values.
      if (!falsy) {
        return [' != null ? ', lookup, ' : ', current];
      } else {
        // Otherwise we can use generic falsy handling
        return [' && ', lookup];
      }
    });
    /* eslint-enable no-loop-func */
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.resolvePossibleLambda"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>resolvePossibleLambda ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.resolvePossibleLambda)
- description and source-code
```javascript
function resolvePossibleLambda() {
  this.push([this.aliasable('container.lambda'), '(', this.popStack(), ', ', this.contextName(0), ')']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupHelper"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>setupHelper (paramSize, name, blockHelper)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupHelper)
- description and source-code
```javascript
function setupHelper(paramSize, name, blockHelper) {
  var params = [],
      paramsInit = this.setupHelperArgs(name, paramSize, params, blockHelper);
  var foundHelper = this.nameLookup('helpers', name, 'helper'),
      callContext = this.aliasable(this.contextName(0) + ' != null ? ' + this.contextName(0) + ' : {}');

  return {
    params: params,
    paramsInit: paramsInit,
    name: foundHelper,
    callParams: [callContext].concat(params)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupHelperArgs"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>setupHelperArgs (helper, paramSize, params, useRegister)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupHelperArgs)
- description and source-code
```javascript
function setupHelperArgs(helper, paramSize, params, useRegister) {
  var options = this.setupParams(helper, paramSize, params);
  options = this.objectLiteral(options);
  if (useRegister) {
    this.useRegister('options');
    params.push('options');
    return ['options=', options];
  } else if (params) {
    params.push(options);
    return '';
  } else {
    return options;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupParams"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>setupParams (helper, paramSize, params)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.setupParams)
- description and source-code
```javascript
function setupParams(helper, paramSize, params) {
  var options = {},
      contexts = [],
      types = [],
      ids = [],
      objectArgs = !params,
      param = undefined;

  if (objectArgs) {
    params = [];
  }

  options.name = this.quotedString(helper);
  options.hash = this.popStack();

  if (this.trackIds) {
    options.hashIds = this.popStack();
  }
  if (this.stringParams) {
    options.hashTypes = this.popStack();
    options.hashContexts = this.popStack();
  }

  var inverse = this.popStack(),
      program = this.popStack();

  // Avoid setting fn and inverse if neither are set. This allows
  // helpers to do a check for 'if (options.fn)'
  if (program || inverse) {
    options.fn = program || 'container.noop';
    options.inverse = inverse || 'container.noop';
  }

  // The parameters go on to the stack in order (making sure that they are evaluated in order)
  // so we need to pop them off the stack in reverse order
  var i = paramSize;
  while (i--) {
    param = this.popStack();
    params[i] = param;

    if (this.trackIds) {
      ids[i] = this.popStack();
    }
    if (this.stringParams) {
      types[i] = this.popStack();
      contexts[i] = this.popStack();
    }
  }

  if (objectArgs) {
    options.args = this.source.generateArray(params);
  }

  if (this.trackIds) {
    options.ids = this.source.generateArray(ids);
  }
  if (this.stringParams) {
    options.types = this.source.generateArray(types);
    options.contexts = this.source.generateArray(contexts);
  }

  if (this.options.data) {
    options.data = 'data';
  }
  if (this.useBlockParams) {
    options.blockParams = 'blockParams';
  }
  return options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.topStack"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>topStack ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.topStack)
- description and source-code
```javascript
function topStack() {
  var stack = this.isInline() ? this.inlineStack : this.compileStack,
      item = stack[stack.length - 1];

<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (item instanceof Literal) {
    return item.value;
  } else {
    return item;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.topStackName"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>topStackName ()](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.topStackName)
- description and source-code
```javascript
function topStackName() {
  return 'stack' + this.stackSlot;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.useRegister"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.JavaScriptCompiler.prototype.</span>useRegister (name)](#apidoc.element.hbs.handlebars.JavaScriptCompiler.prototype.useRegister)
- description and source-code
```javascript
function useRegister(name) {
  if (!this.registers[name]) {
    this.registers[name] = true;
    this.registers.list.push(name);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.VM"></a>[module hbs.handlebars.VM](#apidoc.module.hbs.handlebars.VM)

#### <a name="apidoc.element.hbs.handlebars.VM.checkRevision"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>checkRevision (compilerInfo)](#apidoc.element.hbs.handlebars.VM.checkRevision)
- description and source-code
```javascript
function checkRevision(compilerInfo) {
  var compilerRevision = compilerInfo && compilerInfo[0] || 1,
      currentRevision = _base.COMPILER_REVISION;

  if (compilerRevision !== currentRevision) {
    if (compilerRevision < currentRevision) {
      var runtimeVersions = _base.REVISION_CHANGES[currentRevision],
          compilerVersions = _base.REVISION_CHANGES[compilerRevision];
      throw new _exception2['default']('Template was precompiled with an older version of Handlebars than the current runtime. ' + '
Please update your precompiler to a newer version (' + runtimeVersions + ') or downgrade your runtime to an older version (' + compilerVersions
 + ').');
    } else {
      // Use the embedded version info since the runtime doesn't know about this revision yet
      throw new _exception2['default']('Template was precompiled with a newer version of Handlebars than the current runtime. ' + '
Please update your runtime to a newer version (' + compilerInfo[1] + ').');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.VM.invokePartial"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>invokePartial (partial, context, options)](#apidoc.element.hbs.handlebars.VM.invokePartial)
- description and source-code
```javascript
function invokePartial(partial, context, options) {
  options.partial = true;
  if (options.ids) {
    options.data.contextPath = options.ids[0] || options.data.contextPath;
  }

  var partialBlock = undefined;
  if (options.fn && options.fn !== noop) {
    options.data = _base.createFrame(options.data);
    partialBlock = options.data['partial-block'] = options.fn;

    if (partialBlock.partials) {
      options.partials = Utils.extend({}, options.partials, partialBlock.partials);
    }
  }

  if (partial === undefined && partialBlock) {
    partial = partialBlock;
  }

  if (partial === undefined) {
    throw new _exception2['default']('The partial ' + options.name + ' could not be found');
  } else if (partial instanceof Function) {
    return partial(context, options);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.VM.noop"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>noop ()](#apidoc.element.hbs.handlebars.VM.noop)
- description and source-code
```javascript
function noop() {
  return '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.VM.resolvePartial"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>resolvePartial (partial, context, options)](#apidoc.element.hbs.handlebars.VM.resolvePartial)
- description and source-code
```javascript
function resolvePartial(partial, context, options) {
  if (!partial) {
    if (options.name === '@partial-block') {
      partial = options.data['partial-block'];
    } else {
      partial = options.partials[options.name];
    }
  } else if (!partial.call && !options.name) {
    // This is a dynamic partial that returned a string
    options.name = partial;
    partial = options.partials[partial];
  }
  return partial;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.VM.template"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>template (templateSpec, env)](#apidoc.element.hbs.handlebars.VM.template)
- description and source-code
```javascript
function template(templateSpec, env) {
<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  if (!env) {
    throw new _exception2['default']('No environment passed to template');
  }
  if (!templateSpec || !templateSpec.main) {
    throw new _exception2['default']('Unknown template object: ' + typeof templateSpec);
  }

  templateSpec.main.decorator = templateSpec.main_d;

  // Note: Using env.VM references rather than local var references throughout this section to allow
  // for external users to override these as psuedo-supported APIs.
  env.VM.checkRevision(templateSpec.compiler);

  function invokePartialWrapper(partial, context, options) {
    if (options.hash) {
      context = Utils.extend({}, context, options.hash);
      if (options.ids) {
        options.ids[0] = true;
      }
    }

    partial = env.VM.resolvePartial.call(this, partial, context, options);
    var result = env.VM.invokePartial.call(this, partial, context, options);

    if (result == null && env.compile) {
      options.partials[options.name] = env.compile(partial, templateSpec.compilerOptions, env);
      result = options.partials[options.name](context, options);
    }
    if (result != null) {
      if (options.indent) {
        var lines = result.split('\n');
        for (var i = 0, l = lines.length; i < l; i++) {
          if (!lines[i] && i + 1 === l) {
            break;
          }

          lines[i] = options.indent + lines[i];
        }
        result = lines.join('\n');
      }
      return result;
    } else {
      throw new _exception2['default']('The partial ' + options.name + ' could not be compiled when running in runtime-only mode
');
    }
  }

  // Just add water
  var container = {
    strict: function strict(obj, name) {
      if (!(name in obj)) {
        throw new _exception2['default']('"' + name + '" not defined in ' + obj);
      }
      return obj[name];
    },
    lookup: function lookup(depths, name) {
      var len = depths.length;
      for (var i = 0; i < len; i++) {
        if (depths[i] && depths[i][name] != null) {
          return depths[i][name];
        }
      }
    },
    lambda: function lambda(current, context) {
      return typeof current === 'function' ? current.call(context) : current;
    },

    escapeExpression: Utils.escapeExpression,
    invokePartial: invokePartialWrapper,

    fn: function fn(i) {
      var ret = templateSpec[i];
      ret.decorator = templateSpec[i + '_d'];
      return ret;
    },

    programs: [],
    program: function program(i, data, declaredBlockParams, blockParams, depths) {
      var programWrapper = this.programs[i],
          fn = this.fn(i);
      if (data || depths || blockParams || declaredBlockParams) {
        programWrapper = wrapProgram(this, i, fn, data, declaredBlockParams, blockParams, depths);
      } else if (!programWrapper) {
        programWrapper = this.programs[i] = wrapProgram(this, i, fn);
      }
      return programWrapper;
    },

    data: function data(value, depth) {
      while (value && depth--) {
        value = value._parent;
      }
      return value;
    },
    merge: function merge(param, common) {
      var obj = param || common;

      if (param && common && param !== common) {
        obj = Utils.extend({}, common, param);
      }

      return obj;
    },

    noop: env.VM.noop,
    compilerInfo: templateSpec.compiler
  };

  function ret(context) {
    var options = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

    var data = options.data;

    ret._setup(options);
    if (!options.partial && templateSpec.useData) {
      data = initData(context, data);
    }
    var depths = undefined,
        blockParams = templateSpec.useBlockParams ? [] : undefined;
    if (templateSpec.useDepths) {
      if (options.depths) {
        depths = context !== options.depths[0] ? [context].concat(options.depths) : options.depths;
      } else {
        depths = [context];
      }
    }

    function main(context /*, options*/) {
      return '' + templateSpec.main(container, context, container.helpers, container.partials, data, blockPar ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.VM.wrapProgram"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.VM.</span>wrapProgram (container, i, fn, data, declaredBlockParams, blockParams, depths)](#apidoc.element.hbs.handlebars.VM.wrapProgram)
- description and source-code
```javascript
function wrapProgram(container, i, fn, data, declaredBlockParams, blockParams, depths) {
  function prog(context) {
    var options = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

    var currentDepths = depths;
    if (depths && context !== depths[0]) {
      currentDepths = [context].concat(depths);
    }

    return fn(container, context, container.helpers, container.partials, options.data || data, blockParams && [options.blockParams
].concat(blockParams), currentDepths);
  }

  prog = executeDecorators(fn, prog, container, depths, data, blockParams);

  prog.program = i;
  prog.depth = depths ? depths.length : 0;
  prog.blockParams = declaredBlockParams || 0;
  return prog;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.decorators"></a>[module hbs.handlebars.decorators](#apidoc.module.hbs.handlebars.decorators)

#### <a name="apidoc.element.hbs.handlebars.decorators.inline"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.decorators.</span>inline (fn, props, container, options)](#apidoc.element.hbs.handlebars.decorators.inline)
- description and source-code
```javascript
inline = function (fn, props, container, options) {
  var ret = fn;
  if (!props.partials) {
    props.partials = {};
    ret = function (context, options) {
      // Create a new partials stack frame prior to exec.
      var original = container.partials;
      container.partials = _utils.extend({}, original, props.partials);
      var ret = fn(context, options);
      container.partials = original;
      return ret;
    };
  }

  props.partials[options.args[0]] = options.fn;

  return ret;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.helpers"></a>[module hbs.handlebars.helpers](#apidoc.module.hbs.handlebars.helpers)

#### <a name="apidoc.element.hbs.handlebars.helpers.blockHelperMissing"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>blockHelperMissing (context, options)](#apidoc.element.hbs.handlebars.helpers.blockHelperMissing)
- description and source-code
```javascript
blockHelperMissing = function (context, options) {
  var inverse = options.inverse,
      fn = options.fn;

  if (context === true) {
    return fn(this);
  } else if (context === false || context == null) {
    return inverse(this);
  } else if (_utils.isArray(context)) {
    if (context.length > 0) {
      if (options.ids) {
        options.ids = [options.name];
      }

      return instance.helpers.each(context, options);
    } else {
      return inverse(this);
    }
  } else {
    if (options.data && options.ids) {
      var data = _utils.createFrame(options.data);
      data.contextPath = _utils.appendContextPath(options.data.contextPath, options.name);
      options = { data: data };
    }

    return fn(context, options);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.helpers.each"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>each (context, options)](#apidoc.element.hbs.handlebars.helpers.each)
- description and source-code
```javascript
each = function (context, options) {
  if (!options) {
    throw new _exception2['default']('Must pass iterator to #each');
  }

  var fn = options.fn,
      inverse = options.inverse,
      i = 0,
      ret = '',
      data = undefined,
      contextPath = undefined;

  if (options.data && options.ids) {
    contextPath = _utils.appendContextPath(options.data.contextPath, options.ids[0]) + '.';
  }

  if (_utils.isFunction(context)) {
    context = context.call(this);
  }

  if (options.data) {
    data = _utils.createFrame(options.data);
  }

  function execIteration(field, index, last) {
    if (data) {
      data.key = field;
      data.index = index;
      data.first = index === 0;
      data.last = !!last;

      if (contextPath) {
        data.contextPath = contextPath + field;
      }
    }

    ret = ret + fn(context[field], {
      data: data,
      blockParams: _utils.blockParams([context[field], field], [contextPath + field, null])
    });
  }

  if (context && typeof context === 'object') {
    if (_utils.isArray(context)) {
      for (var j = context.length; i < j; i++) {
        if (i in context) {
          execIteration(i, i, i === context.length - 1);
        }
      }
    } else {
      var priorKey = undefined;

      for (var key in context) {
        if (context.hasOwnProperty(key)) {
          // We're running the iterations one step out of sync so we can detect
          // the last iteration without have to scan the object twice and create
          // an itermediate keys array.
          if (priorKey !== undefined) {
            execIteration(priorKey, i - 1);
          }
          priorKey = key;
          i++;
        }
      }
      if (priorKey !== undefined) {
        execIteration(priorKey, i - 1, true);
      }
    }
  }

  if (i === 0) {
    ret = inverse(this);
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.helpers.helperMissing"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>helperMissing ()](#apidoc.element.hbs.handlebars.helpers.helperMissing)
- description and source-code
```javascript
helperMissing = function () /* [args, ]options */{
  if (arguments.length === 1) {
    // A missing field in a {{foo}} construct.
    return undefined;
  } else {
    // Someone is actually trying to call something, blow up.
    throw new _exception2['default']('Missing helper: "' + arguments[arguments.length - 1].name + '"');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.helpers.if"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>if (conditional, options)](#apidoc.element.hbs.handlebars.helpers.if)
- description and source-code
```javascript
if = function (conditional, options) {
  if (_utils.isFunction(conditional)) {
    conditional = conditional.call(this);
  }

  // Default behavior is to render the positive path if the value is truthy and not empty.
  // The 'includeZero' option may be set to treat the condtional as purely not empty based on the
  // behavior of isEmpty. Effectively this determines if 0 is handled by the positive path or negative.
  if (!options.hash.includeZero && !conditional || _utils.isEmpty(conditional)) {
    return options.inverse(this);
  } else {
    return options.fn(this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.helpers.log"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>log ()](#apidoc.element.hbs.handlebars.helpers.log)
- description and source-code
```javascript
log = function () /* message, options */{
  var args = [undefined],
      options = arguments[arguments.length - 1];
  for (var i = 0; i < arguments.length - 1; i++) {
    args.push(arguments[i]);
  }

  var level = 1;
  if (options.hash.level != null) {
    level = options.hash.level;
  } else if (options.data && options.data.level != null) {
    level = options.data.level;
  }
  args[0] = level;

  instance.log.apply(instance, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.helpers.lookup"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>lookup (obj, field)](#apidoc.element.hbs.handlebars.helpers.lookup)
- description and source-code
```javascript
lookup = function (obj, field) {
  return obj && obj[field];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.helpers.unless"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>unless (conditional, options)](#apidoc.element.hbs.handlebars.helpers.unless)
- description and source-code
```javascript
unless = function (conditional, options) {
  return instance.helpers['if'].call(this, conditional, { fn: options.inverse, inverse: options.fn, hash: options.hash });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.helpers.with"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.helpers.</span>with (context, options)](#apidoc.element.hbs.handlebars.helpers.with)
- description and source-code
```javascript
with = function (context, options) {
  if (_utils.isFunction(context)) {
    context = context.call(this);
  }

  var fn = options.fn;

  if (!_utils.isEmpty(context)) {
    var data = options.data;
    if (options.data && options.ids) {
      data = _utils.createFrame(options.data);
      data.contextPath = _utils.appendContextPath(options.data.contextPath, options.ids[0]);
    }

    return fn(context, {
      data: data,
      blockParams: _utils.blockParams([context], [data && data.contextPath])
    });
  } else {
    return options.inverse(this);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hbs.handlebars.logger"></a>[module hbs.handlebars.logger](#apidoc.module.hbs.handlebars.logger)

#### <a name="apidoc.element.hbs.handlebars.logger.log"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.logger.</span>log (level)](#apidoc.element.hbs.handlebars.logger.log)
- description and source-code
```javascript
function log(level) {
  level = logger.lookupLevel(level);

  if (typeof console !== 'undefined' && logger.lookupLevel(logger.level) <= level) {
    var method = logger.methodMap[level];
    if (!console[method]) {
      // eslint-disable-line no-console
      method = 'log';
    }

    for (var _len = arguments.length, message = Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
      message[_key - 1] = arguments[_key];
    }

    console[method].apply(console, message); // eslint-disable-line no-console
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hbs.handlebars.logger.lookupLevel"></a>[function <span class="apidocSignatureSpan">hbs.handlebars.logger.</span>lookupLevel (level)](#apidoc.element.hbs.handlebars.logger.lookupLevel)
- description and source-code
```javascript
function lookupLevel(level) {
  if (typeof level === 'string') {
    var levelMap = _utils.indexOf(logger.methodMap, level.toLowerCase());
    if (levelMap >= 0) {
      level = levelMap;
    } else {
      level = parseInt(level, 10);
    }
  }

  return level;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
