# api documentation for  [joi (v10.3.0)](https://github.com/hapijs/joi)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-joi.svg)](https://travis-ci.org/npmdoc/node-npmdoc-joi)
#### Object schema validation

[![NPM](https://nodei.co/npm/joi.png?downloads=true)](https://www.npmjs.com/package/joi)

[![apidoc](https://npmdoc.github.io/node-npmdoc-joi/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-joi_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-joi/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-joi/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/joi/issues"
    },
    "dependencies": {
        "hoek": "4.x.x",
        "isemail": "2.x.x",
        "items": "2.x.x",
        "topo": "2.x.x"
    },
    "description": "Object schema validation",
    "devDependencies": {
        "code": "4.x.x",
        "hapitoc": "1.x.x",
        "lab": "13.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "f4ec11ace532fdef6ba780297ce8399268551c2e",
        "tarball": "https://registry.npmjs.org/joi/-/joi-10.3.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "5d484b77f0c32eef40ad7580af7eefbedc1a418b",
    "homepage": "https://github.com/hapijs/joi",
    "keywords": [
        "hapi",
        "schema",
        "validation"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse",
            "email": "eran@hueniverse.com"
        },
        {
            "name": "marsup",
            "email": "marsup@gmail.com"
        }
    ],
    "name": "joi",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/joi.git"
    },
    "scripts": {
        "test": "lab -t 100 -a code -L",
        "test-cov-html": "lab -r html -o coverage.html -a code",
        "test-debug": "lab -a code",
        "toc": "hapitoc",
        "version": "npm run toc && git add API.md README.md"
    },
    "version": "10.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module joi](#apidoc.module.joi)
1.  boolean <span class="apidocSignatureSpan">joi.</span>isJoi
1.  [function <span class="apidocSignatureSpan">joi.</span>alt ()](#apidoc.element.joi.alt)
1.  [function <span class="apidocSignatureSpan">joi.</span>alternatives ()](#apidoc.element.joi.alternatives)
1.  [function <span class="apidocSignatureSpan">joi.</span>any ()](#apidoc.element.joi.any)
1.  [function <span class="apidocSignatureSpan">joi.</span>array ()](#apidoc.element.joi.array)
1.  [function <span class="apidocSignatureSpan">joi.</span>assert (value, schema, message)](#apidoc.element.joi.assert)
1.  [function <span class="apidocSignatureSpan">joi.</span>attempt (value, schema, message)](#apidoc.element.joi.attempt)
1.  [function <span class="apidocSignatureSpan">joi.</span>binary ()](#apidoc.element.joi.binary)
1.  [function <span class="apidocSignatureSpan">joi.</span>bool ()](#apidoc.element.joi.bool)
1.  [function <span class="apidocSignatureSpan">joi.</span>boolean ()](#apidoc.element.joi.boolean)
1.  [function <span class="apidocSignatureSpan">joi.</span>compile (schema)](#apidoc.element.joi.compile)
1.  [function <span class="apidocSignatureSpan">joi.</span>date ()](#apidoc.element.joi.date)
1.  [function <span class="apidocSignatureSpan">joi.</span>describe ()](#apidoc.element.joi.describe)
1.  [function <span class="apidocSignatureSpan">joi.</span>extend ()](#apidoc.element.joi.extend)
1.  [function <span class="apidocSignatureSpan">joi.</span>func ()](#apidoc.element.joi.func)
1.  [function <span class="apidocSignatureSpan">joi.</span>isRef (ref)](#apidoc.element.joi.isRef)
1.  [function <span class="apidocSignatureSpan">joi.</span>lazy (fn)](#apidoc.element.joi.lazy)
1.  [function <span class="apidocSignatureSpan">joi.</span>number ()](#apidoc.element.joi.number)
1.  [function <span class="apidocSignatureSpan">joi.</span>object ()](#apidoc.element.joi.object)
1.  [function <span class="apidocSignatureSpan">joi.</span>reach (schema, path)](#apidoc.element.joi.reach)
1.  [function <span class="apidocSignatureSpan">joi.</span>ref ()](#apidoc.element.joi.ref)
1.  [function <span class="apidocSignatureSpan">joi.</span>string ()](#apidoc.element.joi.string)
1.  [function <span class="apidocSignatureSpan">joi.</span>validate (value)](#apidoc.element.joi.validate)
1.  object <span class="apidocSignatureSpan">joi.</span>_description
1.  object <span class="apidocSignatureSpan">joi.</span>_examples
1.  object <span class="apidocSignatureSpan">joi.</span>_flags
1.  object <span class="apidocSignatureSpan">joi.</span>_inner
1.  object <span class="apidocSignatureSpan">joi.</span>_invalids
1.  object <span class="apidocSignatureSpan">joi.</span>_meta
1.  object <span class="apidocSignatureSpan">joi.</span>_notes
1.  object <span class="apidocSignatureSpan">joi.</span>_refs
1.  object <span class="apidocSignatureSpan">joi.</span>_settings
1.  object <span class="apidocSignatureSpan">joi.</span>_tags
1.  object <span class="apidocSignatureSpan">joi.</span>_tests
1.  object <span class="apidocSignatureSpan">joi.</span>_unit
1.  object <span class="apidocSignatureSpan">joi.</span>_valids
1.  object <span class="apidocSignatureSpan">joi.</span>any.prototype
1.  object <span class="apidocSignatureSpan">joi.</span>cast
1.  object <span class="apidocSignatureSpan">joi.</span>errors
1.  object <span class="apidocSignatureSpan">joi.</span>extensionSchema
1.  object <span class="apidocSignatureSpan">joi.</span>extensionsSchema
1.  string <span class="apidocSignatureSpan">joi.</span>_type
1.  string <span class="apidocSignatureSpan">joi.</span>version

#### [module joi.any](#apidoc.module.joi.any)
1.  [function <span class="apidocSignatureSpan">joi.</span>any ()](#apidoc.element.joi.any.any)

#### [module joi.any.prototype](#apidoc.module.joi.any.prototype)
1.  boolean <span class="apidocSignatureSpan">joi.any.prototype.</span>isImmutable
1.  [function <span class="apidocSignatureSpan">joi.any.prototype.</span>disallow (value)](#apidoc.element.joi.any.prototype.disallow)
1.  [function <span class="apidocSignatureSpan">joi.any.prototype.</span>equal ()](#apidoc.element.joi.any.prototype.equal)
1.  [function <span class="apidocSignatureSpan">joi.any.prototype.</span>exist ()](#apidoc.element.joi.any.prototype.exist)
1.  [function <span class="apidocSignatureSpan">joi.any.prototype.</span>not (value)](#apidoc.element.joi.any.prototype.not)
1.  [function <span class="apidocSignatureSpan">joi.any.prototype.</span>only ()](#apidoc.element.joi.any.prototype.only)

#### [module joi.cast](#apidoc.module.joi.cast)
1.  [function <span class="apidocSignatureSpan">joi.cast.</span>ref (id)](#apidoc.element.joi.cast.ref)
1.  [function <span class="apidocSignatureSpan">joi.cast.</span>schema (config)](#apidoc.element.joi.cast.schema)

#### [module joi.errors](#apidoc.module.joi.errors)
1.  [function <span class="apidocSignatureSpan">joi.errors.</span>Err (type, context, state, options, flags)](#apidoc.element.joi.errors.Err)
1.  [function <span class="apidocSignatureSpan">joi.errors.</span>create (type, context, state, options, flags)](#apidoc.element.joi.errors.create)
1.  [function <span class="apidocSignatureSpan">joi.errors.</span>process (errors, object)](#apidoc.element.joi.errors.process)

#### [module joi.ref](#apidoc.module.joi.ref)
1.  [function <span class="apidocSignatureSpan">joi.ref.</span>create (key, options)](#apidoc.element.joi.ref.create)
1.  [function <span class="apidocSignatureSpan">joi.ref.</span>isRef (ref)](#apidoc.element.joi.ref.isRef)
1.  [function <span class="apidocSignatureSpan">joi.ref.</span>push (array, ref)](#apidoc.element.joi.ref.push)



# <a name="apidoc.module.joi"></a>[module joi](#apidoc.module.joi)

#### <a name="apidoc.element.joi.alt"></a>[function <span class="apidocSignatureSpan">joi.</span>alt ()](#apidoc.element.joi.alt)
- description and source-code
```javascript
alt = function () {

    return arguments.length ? internals.alternatives.try.apply(internals.alternatives, arguments) : internals.alternatives;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.alternatives"></a>[function <span class="apidocSignatureSpan">joi.</span>alternatives ()](#apidoc.element.joi.alternatives)
- description and source-code
```javascript
alternatives = function () {

    return arguments.length ? internals.alternatives.try.apply(internals.alternatives, arguments) : internals.alternatives;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.any"></a>[function <span class="apidocSignatureSpan">joi.</span>any ()](#apidoc.element.joi.any)
- description and source-code
```javascript
any = function () {

    Hoek.assert(arguments.length === 0, 'Joi.any() does not allow arguments.');

    return any;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.array"></a>[function <span class="apidocSignatureSpan">joi.</span>array ()](#apidoc.element.joi.array)
- description and source-code
```javascript
array = function () {

    Hoek.assert(arguments.length === 0, 'Joi.array() does not allow arguments.');

    return internals.array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.assert"></a>[function <span class="apidocSignatureSpan">joi.</span>assert (value, schema, message)](#apidoc.element.joi.assert)
- description and source-code
```javascript
assert = function (value, schema, message) {

    root.attempt(value, schema, message);
}
```
- example usage
```shell
...

return { errors: errors.length ? errors : this.createError('alternatives.base', null, state, options) };
    }

    try(/* schemas */) {

const schemas = Hoek.flatten(Array.prototype.slice.call(arguments));
Hoek.assert(schemas.length, 'Cannot add other alternatives without at least one schema');

const obj = this.clone();

for (let i = 0; i < schemas.length; ++i) {
    const cast = Cast.schema(schemas[i]);
    if (cast._refs.length) {
        obj._refs = obj._refs.concat(cast._refs);
...
```

#### <a name="apidoc.element.joi.attempt"></a>[function <span class="apidocSignatureSpan">joi.</span>attempt (value, schema, message)](#apidoc.element.joi.attempt)
- description and source-code
```javascript
attempt = function (value, schema, message) {

    const result = root.validate(value, schema);
    const error = result.error;
    if (error) {
        if (!message) {
            error.message = error.annotate();
            throw error;
        }

        if (!(message instanceof Error)) {
            error.message = message + ' ' + error.annotate();
            throw error;
        }

        throw message;
    }

    return result.value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.binary"></a>[function <span class="apidocSignatureSpan">joi.</span>binary ()](#apidoc.element.joi.binary)
- description and source-code
```javascript
binary = function () {

    Hoek.assert(arguments.length === 0, 'Joi.binary() does not allow arguments.');

    return internals.binary;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.bool"></a>[function <span class="apidocSignatureSpan">joi.</span>bool ()](#apidoc.element.joi.bool)
- description and source-code
```javascript
bool = function () {

    Hoek.assert(arguments.length === 0, 'Joi.boolean() does not allow arguments.');

    return internals.boolean;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.boolean"></a>[function <span class="apidocSignatureSpan">joi.</span>boolean ()](#apidoc.element.joi.boolean)
- description and source-code
```javascript
boolean = function () {

    Hoek.assert(arguments.length === 0, 'Joi.boolean() does not allow arguments.');

    return internals.boolean;
}
```
- example usage
```shell
...


// Declare internals

const internals = {};

exports.options = Joi.object({
abortEarly: Joi.boolean(),
convert: Joi.boolean(),
allowUnknown: Joi.boolean(),
skipFunctions: Joi.boolean(),
stripUnknown: [Joi.boolean(), Joi.object({ arrays: Joi.boolean(), objects: Joi.boolean() }).or('arrays', 'objects')],
language: Joi.object(),
presence: Joi.string().only('required', 'optional', 'forbidden', 'ignore'),
raw: Joi.boolean(),
...
```

#### <a name="apidoc.element.joi.compile"></a>[function <span class="apidocSignatureSpan">joi.</span>compile (schema)](#apidoc.element.joi.compile)
- description and source-code
```javascript
compile = function (schema) {

    try {
        return Cast.schema(schema);
    }
    catch (err) {
        if (err.hasOwnProperty('path')) {
            err.message = err.message + '(' + err.path + ')';
        }
        throw err;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.date"></a>[function <span class="apidocSignatureSpan">joi.</span>date ()](#apidoc.element.joi.date)
- description and source-code
```javascript
date = function () {

    Hoek.assert(arguments.length === 0, 'Joi.date() does not allow arguments.');

    return internals.date;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.describe"></a>[function <span class="apidocSignatureSpan">joi.</span>describe ()](#apidoc.element.joi.describe)
- description and source-code
```javascript
describe = function () {

    const schema = arguments.length ? root.compile(arguments[0]) : any;
    return schema.describe();
}
```
- example usage
```shell
...
        const alternatives = [];
        for (let i = 0; i < this._inner.matches.length; ++i) {
            const item = this._inner.matches[i];
            if (item.schema) {

// try()

alternatives.push(item.schema.describe());
            }
            else {

// when()

const when = {
    ref: item.ref.toString(),
...
```

#### <a name="apidoc.element.joi.extend"></a>[function <span class="apidocSignatureSpan">joi.</span>extend ()](#apidoc.element.joi.extend)
- description and source-code
```javascript
extend = function () {

    const extensions = Hoek.flatten(Array.prototype.slice.call(arguments));
    Hoek.assert(extensions.length > 0, 'You need to provide at least one extension');

    this.assert(extensions, root.extensionsSchema);

    const joi = Object.create(this.any());
    Object.assign(joi, this);

    for (let i = 0; i < extensions.length; ++i) {
        let extension = extensions[i];

        if (typeof extension === 'function') {
            extension = extension(joi);
        }

        this.assert(extension, root.extensionSchema);

        const base = (extension.base || this.any()).clone(); // Cloning because we're going to override language afterwards
        const ctor = base.constructor;
        const type = class extends ctor { // eslint-disable-line no-loop-func

            constructor() {

                super();
                if (extension.base) {
                    Object.assign(this, base);
                }

                this._type = extension.name;

                if (extension.language) {
                    this._settings = this._settings || { language: {} };
                    this._settings.language = Hoek.applyToDefaults(this._settings.language, {
                        [extension.name]: extension.language
                    });
                }
            }

        };

        if (extension.coerce) {
            type.prototype._coerce = function (value, state, options) {

                if (ctor.prototype._coerce) {
                    const baseRet = ctor.prototype._coerce.call(this, value, state, options);

                    if (baseRet.errors) {
                        return baseRet;
                    }

                    value = baseRet.value;
                }

                const ret = extension.coerce.call(this, value, state, options);
                if (ret instanceof Errors.Err) {
                    return { value, errors: ret };
                }

                return { value: ret };
            };
        }
        if (extension.pre) {
            type.prototype._base = function (value, state, options) {

                if (ctor.prototype._base) {
                    const baseRet = ctor.prototype._base.call(this, value, state, options);

                    if (baseRet.errors) {
                        return baseRet;
                    }

                    value = baseRet.value;
                }

                const ret = extension.pre.call(this, value, state, options);
                if (ret instanceof Errors.Err) {
                    return { value, errors: ret };
                }

                return { value: ret };
            };
        }

        if (extension.rules) {
            for (let j = 0; j < extension.rules.length; ++j) {
                const rule = extension.rules[j];
                const ruleArgs = rule.params ?
                    (rule.params instanceof Any ? rule.params._inner.children.map((k) => k.key) : Object.keys(rule.params)) :
                    [];
                const validateArgs = rule.params ? Cast.schema(rule.params) : null;

                type.prototype[rule.name] = function () { // eslint-disable-line no-loop-func

                    if (arguments.length > ruleArgs.length) {
                        throw new Error('Unexpected number of arguments');
                    }

                    const args = Array.prototype.slice.call(arguments);
                    let hasRef = false;
                    let arg = {};

                    for (let k = 0; k < ruleArgs.length; ++k) {
                        arg[ruleArgs[k]] = args[k];
                        if (!hasRef && Ref.isRef(args[k])) {
                            hasRef = true;
                        }
                    }

                    if (validateArgs) {
                        arg = joi.attempt(arg, validateArgs);
                    }

                    let schema;
                    if (rule.validate) {
                        const validate = function (value, state, options) {

                            return rule.validate.ca ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.func"></a>[function <span class="apidocSignatureSpan">joi.</span>func ()](#apidoc.element.joi.func)
- description and source-code
```javascript
func = function () {

    Hoek.assert(arguments.length === 0, 'Joi.func() does not allow arguments.');

    return internals.object._func();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.isRef"></a>[function <span class="apidocSignatureSpan">joi.</span>isRef (ref)](#apidoc.element.joi.isRef)
- description and source-code
```javascript
isRef = function (ref) {

    return Ref.isRef(ref);
}
```
- example usage
```shell
...
}

return obj;
    }

    when(ref, options) {

Hoek.assert(Ref.isRef(ref) || typeof ref === 'string', 'Invalid reference:', ref);
Hoek.assert(options, 'Missing options');
Hoek.assert(typeof options === 'object', 'Invalid options');
Hoek.assert(options.hasOwnProperty('is'), 'Missing "is" directive');
Hoek.assert(options.then !== undefined || options.otherwise !== undefined, 'options must have at least one of "then" or "otherwise
"');

const obj = this.clone();
let is = Cast.schema(options.is);
...
```

#### <a name="apidoc.element.joi.lazy"></a>[function <span class="apidocSignatureSpan">joi.</span>lazy (fn)](#apidoc.element.joi.lazy)
- description and source-code
```javascript
lazy = function (fn) {

    return Lazy.set(fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.number"></a>[function <span class="apidocSignatureSpan">joi.</span>number ()](#apidoc.element.joi.number)
- description and source-code
```javascript
number = function () {

    Hoek.assert(arguments.length === 0, 'Joi.number() does not allow arguments.');

    return internals.number;
}
```
- example usage
```shell
...

'''javascript
const Joi = require('joi');

const schema = Joi.object().keys({
    username: Joi.string().alphanum().min(3).max(30).required(),
    password: Joi.string().regex(/^[a-zA-Z0-9]{3,30}$/),
    access_token: [Joi.string(), Joi.number()],
    birthyear: Joi.number().integer().min(1900).max(2013),
    email: Joi.string().email()
}).with('username', 'birthyear').without('password', 'access_token');

// Return result.
const result = Joi.validate({ username: 'abc', birthyear: 1994 }, schema);
// result.error === null -> valid
...
```

#### <a name="apidoc.element.joi.object"></a>[function <span class="apidocSignatureSpan">joi.</span>object ()](#apidoc.element.joi.object)
- description and source-code
```javascript
object = function () {

    return arguments.length ? internals.object.keys.apply(internals.object, arguments) : internals.object;
}
```
- example usage
```shell
...


# Example

'''javascript
const Joi = require('joi');

const schema = Joi.object().keys({
    username: Joi.string().alphanum().min(3).max(30).required(),
    password: Joi.string().regex(/^[a-zA-Z0-9]{3,30}$/),
    access_token: [Joi.string(), Joi.number()],
    birthyear: Joi.number().integer().min(1900).max(2013),
    email: Joi.string().email()
}).with('username', 'birthyear').without('password', 'access_token');
...
```

#### <a name="apidoc.element.joi.reach"></a>[function <span class="apidocSignatureSpan">joi.</span>reach (schema, path)](#apidoc.element.joi.reach)
- description and source-code
```javascript
reach = function (schema, path) {

    Hoek.assert(schema && schema instanceof Any, 'you must provide a joi schema');
    Hoek.assert(typeof path === 'string', 'path must be a string');

    if (path === '') {
        return schema;
    }

    const parts = path.split('.');
    const children = schema._inner.children;
    if (!children) {
        return;
    }

    const key = parts[0];
    for (let i = 0; i < children.length; ++i) {
        const child = children[i];
        if (child.key === key) {
            return this.reach(child.schema, path.substr(key.length + 1));
        }
    }
}
```
- example usage
```shell
...
function: new Map(),
custom: new Map()
            };

            const compare = settings.comparator || Hoek.deepEqual;

            for (let i = 0; i < value.length; ++i) {
const item = settings.path ? Hoek.reach(value[i], settings.path) : value[i];
const records = settings.comparator ? found.custom : found[typeof item];

// All available types are supported, so it's not possible to reach 100% coverage without ignoring this line.
// I still want to keep the test for future js versions with new types (eg. Symbol).
if (/* $lab:coverage:off$ */ records /* $lab:coverage:on$ */) {
    if (records instanceof Map) {
        const entries = records.entries();
...
```

#### <a name="apidoc.element.joi.ref"></a>[function <span class="apidocSignatureSpan">joi.</span>ref ()](#apidoc.element.joi.ref)
- description and source-code
```javascript
ref = function () {

    return Ref.create.apply(null, arguments);
}
```
- example usage
```shell
...
        const il = this._inner.matches.length;
        const baseType = this._settings && this._settings.baseType;

        for (let i = 0; i < il; ++i) {
            const item = this._inner.matches[i];
            const schema = item.schema;
            if (!schema) {
const failed = item.is._validate(item.ref(state.reference || state.parent, options), null, options, state.parent).errors;

if (failed) {
    if (item.otherwise) {
        return item.otherwise._validate(value, state, options);
    }
    else if (baseType && i  === (il - 1)) {
        return baseType._validate(value, state, options);
...
```

#### <a name="apidoc.element.joi.string"></a>[function <span class="apidocSignatureSpan">joi.</span>string ()](#apidoc.element.joi.string)
- description and source-code
```javascript
string = function () {

    Hoek.assert(arguments.length === 0, 'Joi.string() does not allow arguments.');

    return internals.string;
}
```
- example usage
```shell
...

# Example

'''javascript
const Joi = require('joi');

const schema = Joi.object().keys({
    username: Joi.string().alphanum().min(3).max(30).required(),
    password: Joi.string().regex(/^[a-zA-Z0-9]{3,30}$/),
    access_token: [Joi.string(), Joi.number()],
    birthyear: Joi.number().integer().min(1900).max(2013),
    email: Joi.string().email()
}).with('username', 'birthyear').without('password', 'access_token');

// Return result.
...
```

#### <a name="apidoc.element.joi.validate"></a>[function <span class="apidocSignatureSpan">joi.</span>validate (value)](#apidoc.element.joi.validate)
- description and source-code
```javascript
validate = function (value) {

    const last = arguments[arguments.length - 1];
    const callback = typeof last === 'function' ? last : null;

    const count = arguments.length - (callback ? 1 : 0);
    if (count === 1) {
        return any.validate(value, callback);
    }

    const options = count === 3 ? arguments[2] : {};
    const schema = root.compile(arguments[1]);

    return schema._validateWithOptions(value, options, callback);
}
```
- example usage
```shell
...
    password: Joi.string().regex(/^[a-zA-Z0-9]{3,30}$/),
    access_token: [Joi.string(), Joi.number()],
    birthyear: Joi.number().integer().min(1900).max(2013),
    email: Joi.string().email()
}).with('username', 'birthyear').without('password', 'access_token');

// Return result.
const result = Joi.validate({ username: 'abc', birthyear: 1994 }, schema);
// result.error === null -> valid

// You can also pass a callback which will be called synchronously with the validation result.
Joi.validate({ username: 'abc', birthyear: 1994 }, schema, function (err, value) { });  // err === null -> valid

'''
...
```



# <a name="apidoc.module.joi.any"></a>[module joi.any](#apidoc.module.joi.any)

#### <a name="apidoc.element.joi.any.any"></a>[function <span class="apidocSignatureSpan">joi.</span>any ()](#apidoc.element.joi.any.any)
- description and source-code
```javascript
class {

    constructor() {

        Cast = Cast || require('./cast');

        this.isJoi = true;
        this._type = 'any';
        this._settings = null;
        this._valids = new internals.Set();
        this._invalids = new internals.Set();
        this._tests = [];
        this._refs = [];
        this._flags = {
<span class="apidocCodeCommentSpan">            /*
             presence: 'optional',                   // optional, required, forbidden, ignore
             allowOnly: false,
             allowUnknown: undefined,
             default: undefined,
             forbidden: false,
             encoding: undefined,
             insensitive: false,
             trim: false,
             case: undefined,                        // upper, lower
             empty: undefined,
             func: false,
             raw: false
             */
</span>        };

        this._description = null;
        this._unit = null;
        this._notes = [];
        this._tags = [];
        this._examples = [];
        this._meta = [];

        this._inner = {};                           // Hash of arrays of immutable objects
    }

    createError(type, context, state, options) {

        return Errors.create(type, context, state, options, this._flags);
    }

    checkOptions(options) {

        const Schemas = require('./schemas');
        const result = Schemas.options.validate(options);
        if (result.error) {
            throw new Error(result.error.details[0].message);
        }
    }

    clone() {

        const obj = Object.create(Object.getPrototypeOf(this));

        obj.isJoi = true;
        obj._type = this._type;
        obj._settings = internals.concatSettings(this._settings);
        obj._valids = Hoek.clone(this._valids);
        obj._invalids = Hoek.clone(this._invalids);
        obj._tests = this._tests.slice();
        obj._refs = this._refs.slice();
        obj._flags = Hoek.clone(this._flags);

        obj._description = this._description;
        obj._unit = this._unit;
        obj._notes = this._notes.slice();
        obj._tags = this._tags.slice();
        obj._examples = this._examples.slice();
        obj._meta = this._meta.slice();

        obj._inner = {};
        const inners = Object.keys(this._inner);
        for (let i = 0; i < inners.length; ++i) {
            const key = inners[i];
            obj._inner[key] = this._inner[key] ? this._inner[key].slice() : null;
        }

        return obj;
    }

    concat(schema) {

        Hoek.assert(schema instanceof internals.Any, 'Invalid schema object');
        Hoek.assert(this._type === 'any' || schema._type === 'any' || schema._type === this._type, 'Cannot merge type', this._type
, 'with another type:', schema._type);

        let obj = this.clone();

        if (this._type === 'any' && schema._type !== 'any') {

            // Reset values as if we were "this"
            const tmpObj = schema.clone();
            const keysToRestore = ['_settings', '_valids', '_invalids', '_tests', '_refs', '_flags', '_description', '_unit',
                '_notes', '_tags', '_examples', '_meta', '_inner'];

            for (let i = 0; i < keysToRestore.length; ++i) {
                tmpObj[keysToRestore[i]] = obj[keysToRestore[i]];
            }

            obj = tmpObj;
        }

        obj._settings = obj._settings ? internals.concatSettings(obj._settings, schema._settings) : schema._settings;
        obj._valids.merge(schema._valids, schema._invalids);
        obj._invalids.merge(schema._invalids, schema._valids);
        obj._tests = obj._tests.concat(schema._tests);
        obj._refs = obj._refs.concat(schema._refs);
        Hoek.merge(obj._flags, schema._flags);

        obj._description = schema._description || obj._description;
        obj._unit = schema._unit || obj._unit;
        obj._notes = obj._notes.concat(schema._notes);
        obj._tags = obj._tags.concat(schema._tags);
        obj._examples = obj._examples.concat(schema._examples);
        obj._meta = obj._meta.concat(schema._meta);

        const inners = Object.keys(schema._inner);
        const isObject = obj._type === 'o ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.joi.any.prototype"></a>[module joi.any.prototype](#apidoc.module.joi.any.prototype)

#### <a name="apidoc.element.joi.any.prototype.disallow"></a>[function <span class="apidocSignatureSpan">joi.any.prototype.</span>disallow (value)](#apidoc.element.joi.any.prototype.disallow)
- description and source-code
```javascript
invalid(value) {

    const obj = this.clone();
    const values = Hoek.flatten(Array.prototype.slice.call(arguments));
    for (let i = 0; i < values.length; ++i) {
        value = values[i];

        Hoek.assert(value !== undefined, 'Cannot call allow/valid/invalid with undefined');
        obj._valids.remove(value);
        obj._invalids.add(value, this._refs);
    }

    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.any.prototype.equal"></a>[function <span class="apidocSignatureSpan">joi.any.prototype.</span>equal ()](#apidoc.element.joi.any.prototype.equal)
- description and source-code
```javascript
valid() {

    const obj = this.allow.apply(this, arguments);
    obj._flags.allowOnly = true;
    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.any.prototype.exist"></a>[function <span class="apidocSignatureSpan">joi.any.prototype.</span>exist ()](#apidoc.element.joi.any.prototype.exist)
- description and source-code
```javascript
required() {

    if (this._flags.presence === 'required') {
        return this;
    }

    const obj = this.clone();
    obj._flags.presence = 'required';
    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.any.prototype.not"></a>[function <span class="apidocSignatureSpan">joi.any.prototype.</span>not (value)](#apidoc.element.joi.any.prototype.not)
- description and source-code
```javascript
invalid(value) {

    const obj = this.clone();
    const values = Hoek.flatten(Array.prototype.slice.call(arguments));
    for (let i = 0; i < values.length; ++i) {
        value = values[i];

        Hoek.assert(value !== undefined, 'Cannot call allow/valid/invalid with undefined');
        obj._valids.remove(value);
        obj._invalids.add(value, this._refs);
    }

    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.joi.any.prototype.only"></a>[function <span class="apidocSignatureSpan">joi.any.prototype.</span>only ()](#apidoc.element.joi.any.prototype.only)
- description and source-code
```javascript
valid() {

    const obj = this.allow.apply(this, arguments);
    obj._flags.allowOnly = true;
    return obj;
}
```
- example usage
```shell
...
exports.options = Joi.object({
    abortEarly: Joi.boolean(),
    convert: Joi.boolean(),
    allowUnknown: Joi.boolean(),
    skipFunctions: Joi.boolean(),
    stripUnknown: [Joi.boolean(), Joi.object({ arrays: Joi.boolean(), objects: Joi.boolean() }).or('arrays', 'objects')],
    language: Joi.object(),
    presence: Joi.string().only('required', 'optional', 'forbidden', 'ignore'),
    raw: Joi.boolean(),
    context: Joi.object(),
    strip: Joi.boolean(),
    noDefaults: Joi.boolean()
}).strict();
...
```



# <a name="apidoc.module.joi.cast"></a>[module joi.cast](#apidoc.module.joi.cast)

#### <a name="apidoc.element.joi.cast.ref"></a>[function <span class="apidocSignatureSpan">joi.cast.</span>ref (id)](#apidoc.element.joi.cast.ref)
- description and source-code
```javascript
ref = function (id) {

    return Ref.isRef(id) ? id : Ref.create(id);
}
```
- example usage
```shell
...
        const il = this._inner.matches.length;
        const baseType = this._settings && this._settings.baseType;

        for (let i = 0; i < il; ++i) {
            const item = this._inner.matches[i];
            const schema = item.schema;
            if (!schema) {
const failed = item.is._validate(item.ref(state.reference || state.parent, options), null, options, state.parent).errors;

if (failed) {
    if (item.otherwise) {
        return item.otherwise._validate(value, state, options);
    }
    else if (baseType && i  === (il - 1)) {
        return baseType._validate(value, state, options);
...
```

#### <a name="apidoc.element.joi.cast.schema"></a>[function <span class="apidocSignatureSpan">joi.cast.</span>schema (config)](#apidoc.element.joi.cast.schema)
- description and source-code
```javascript
schema = function (config) {

    internals.any = internals.any || new (require('./any'))();
    internals.alt = internals.alt || require('./alternatives');
    internals.object = internals.object || require('./object');

    if (config !== undefined && config !== null && typeof config === 'object') {

        if (config.isJoi) {
            return config;
        }

        if (Array.isArray(config)) {
            return internals.alt.try(config);
        }

        if (config instanceof RegExp) {
            return internals.string.regex(config);
        }

        if (config instanceof Date) {
            return internals.date.valid(config);
        }

        return internals.object.keys(config);
    }

    if (typeof config === 'string') {
        return internals.string.valid(config);
    }

    if (typeof config === 'number') {
        return internals.number.valid(config);
    }

    if (typeof config === 'boolean') {
        return internals.boolean.valid(config);
    }

    if (Ref.isRef(config)) {
        return internals.any.valid(config);
    }

    Hoek.assert(config === null, 'Invalid schema content:', config);

    return internals.any.valid(null);
}
```
- example usage
```shell
...

const schemas = Hoek.flatten(Array.prototype.slice.call(arguments));
Hoek.assert(schemas.length, 'Cannot add other alternatives without at least one schema');

const obj = this.clone();

for (let i = 0; i < schemas.length; ++i) {
    const cast = Cast.schema(schemas[i]);
    if (cast._refs.length) {
        obj._refs = obj._refs.concat(cast._refs);
    }
    obj._inner.matches.push({ schema: cast });
}

return obj;
...
```



# <a name="apidoc.module.joi.errors"></a>[module joi.errors](#apidoc.module.joi.errors)

#### <a name="apidoc.element.joi.errors.Err"></a>[function <span class="apidocSignatureSpan">joi.errors.</span>Err (type, context, state, options, flags)](#apidoc.element.joi.errors.Err)
- description and source-code
```javascript
class {

    constructor(type, context, state, options, flags) {

        this.isJoi = true;
        this.type = type;
        this.context = context || {};
        this.context.key = state.key;
        this.path = state.path;
        this.options = options;
        this.flags = flags;
    }

    toString() {

        const localized = this.options.language;

        if (this.flags.label) {
            this.context.key = this.flags.label;
        }
        else if (this.context.key === '' || this.context.key === null) {
            this.context.key = localized.root || Language.errors.root;
        }

        let format = Hoek.reach(localized, this.type) || Hoek.reach(Language.errors, this.type);
        const hasKey = /\{\{\!?key\}\}/.test(format);
        const skipKey = format.length > 2 && format[0] === '!' && format[1] === '!';

        if (skipKey) {
            format = format.slice(2);
        }

        if (!hasKey && !skipKey) {
            format = (Hoek.reach(localized, 'key') || Hoek.reach(Language.errors, 'key')) + format;
        }

        let wrapArrays = Hoek.reach(localized, 'messages.wrapArrays');
        if (typeof wrapArrays !== 'boolean') {
            wrapArrays = Language.errors.messages.wrapArrays;
        }

        return format.replace(/\{\{(\!?)([^}]+)\}\}/g, ($0, isSecure, name) => {

            const value = Hoek.reach(this.context, name);
            const normalized = internals.stringify(value, wrapArrays);
            return (isSecure ? Hoek.escapeHtml(normalized) : normalized);
        });
    }

}
```
- example usage
```shell
...
}

};


exports.create = function (type, context, state, options, flags) {

return new exports.Err(type, context, state, options, flags);
};


exports.process = function (errors, object) {

if (!errors || !errors.length) {
    return null;
...
```

#### <a name="apidoc.element.joi.errors.create"></a>[function <span class="apidocSignatureSpan">joi.errors.</span>create (type, context, state, options, flags)](#apidoc.element.joi.errors.create)
- description and source-code
```javascript
create = function (type, context, state, options, flags) {

    return new exports.Err(type, context, state, options, flags);
}
```
- example usage
```shell
...
this._meta = [];

this._inner = {};                           // Hash of arrays of immutable objects
    }

    createError(type, context, state, options) {

return Errors.create(type, context, state, options, this._flags);
    }

    checkOptions(options) {

const Schemas = require('./schemas');
const result = Schemas.options.validate(options);
if (result.error) {
...
```

#### <a name="apidoc.element.joi.errors.process"></a>[function <span class="apidocSignatureSpan">joi.errors.</span>process (errors, object)](#apidoc.element.joi.errors.process)
- description and source-code
```javascript
process = function (errors, object) {

    if (!errors || !errors.length) {
        return null;
    }

    // Construct error

    let message = '';
    const details = [];

    const processErrors = function (localErrors, parent) {

        for (let i = 0; i < localErrors.length; ++i) {
            const item = localErrors[i];

            if (item.flags.error) {
                return item.flags.error;
            }

            let itemMessage;
            if (parent === undefined) {
                itemMessage = item.toString();
                message = message + (message ? '. ' : '') + itemMessage;
            }

            // Do not push intermediate errors, we're only interested in leafs

            if (item.context.reason && item.context.reason.length) {
                const override = processErrors(item.context.reason, item.path);
                if (override) {
                    return override;
                }
            }
            else {
                details.push({
                    message: itemMessage || item.toString(),
                    path: internals.getPath(item),
                    type: item.type,
                    context: item.context
                });
            }
        }
    };

    const override = processErrors(errors);
    if (override) {
        return override;
    }

    const error = new Error(message);
    error.isJoi = true;
    error.name = 'ValidationError';
    error.details = details;
    error._object = object;
    error.annotate = internals.annotate;
    return error;
}
```
- example usage
```shell
...
    return obj;
}

example(value) {

    Hoek.assert(arguments.length, 'Missing example');
    const result = this._validate(value, null, internals.defaults);
    Hoek.assert(!result.errors, 'Bad example:', result.errors && Errors.process(result.errors, value));

    const obj = this.clone();
    obj._examples.push(value);
    return obj;
}

unit(name) {
...
```



# <a name="apidoc.module.joi.ref"></a>[module joi.ref](#apidoc.module.joi.ref)

#### <a name="apidoc.element.joi.ref.create"></a>[function <span class="apidocSignatureSpan">joi.ref.</span>create (key, options)](#apidoc.element.joi.ref.create)
- description and source-code
```javascript
create = function (key, options) {

    Hoek.assert(typeof key === 'string', 'Invalid reference key:', key);

    const settings = Hoek.clone(options);         // options can be reused and modified

    const ref = function (value, validationOptions) {

        return Hoek.reach(ref.isContext ? validationOptions.context : value, ref.key, settings);
    };

    ref.isContext = (key[0] === ((settings && settings.contextPrefix) || '$'));
    ref.key = (ref.isContext ? key.slice(1) : key);
    ref.path = ref.key.split((settings && settings.separator) || '.');
    ref.depth = ref.path.length;
    ref.root = ref.path[0];
    ref.isJoi = true;

    ref.toString = function () {

        return (ref.isContext ? 'context:' : 'ref:') + ref.key;
    };

    return ref;
}
```
- example usage
```shell
...
this._meta = [];

this._inner = {};                           // Hash of arrays of immutable objects
    }

    createError(type, context, state, options) {

return Errors.create(type, context, state, options, this._flags);
    }

    checkOptions(options) {

const Schemas = require('./schemas');
const result = Schemas.options.validate(options);
if (result.error) {
...
```

#### <a name="apidoc.element.joi.ref.isRef"></a>[function <span class="apidocSignatureSpan">joi.ref.</span>isRef (ref)](#apidoc.element.joi.ref.isRef)
- description and source-code
```javascript
isRef = function (ref) {

    return typeof ref === 'function' && ref.isJoi;
}
```
- example usage
```shell
...
}

return obj;
    }

    when(ref, options) {

Hoek.assert(Ref.isRef(ref) || typeof ref === 'string', 'Invalid reference:', ref);
Hoek.assert(options, 'Missing options');
Hoek.assert(typeof options === 'object', 'Invalid options');
Hoek.assert(options.hasOwnProperty('is'), 'Missing "is" directive');
Hoek.assert(options.then !== undefined || options.otherwise !== undefined, 'options must have at least one of "then" or "otherwise
"');

const obj = this.clone();
let is = Cast.schema(options.is);
...
```

#### <a name="apidoc.element.joi.ref.push"></a>[function <span class="apidocSignatureSpan">joi.ref.</span>push (array, ref)](#apidoc.element.joi.ref.push)
- description and source-code
```javascript
push = function (array, ref) {

    if (exports.isRef(ref) &&
        !ref.isContext) {

        array.push(ref.root);
    }
}
```
- example usage
```shell
...
    const obj = this.clone();

    for (let i = 0; i < schemas.length; ++i) {
        const cast = Cast.schema(schemas[i]);
        if (cast._refs.length) {
            obj._refs = obj._refs.concat(cast._refs);
        }
        obj._inner.matches.push({ schema: cast });
    }

    return obj;
}

when(ref, options) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
