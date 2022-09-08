<!--

  DO NOT EDIT.

  This markdown file was autogenerated using a mixture of the following files as the source of truth for its data:
  - ../../src/rules/button-has-type.ts
  - ../../tests/rules/button-has-type/cases.ts

  In order to update this file, it is therefore those files which need to be updated, as well as potentially the generator script:
  - ../../../../tools/scripts/generate-rule-docs.ts

-->

<br>

# `@angular-eslint/template/button-has-type`

Ensures that a button has a valid type specified

- Type: suggestion

<br>

## Rule Options

The rule does not have any configuration options.

<br>

## Usage Examples

> The following examples are generated automatically from the actual unit tests within the plugin, so you can be assured that their behavior is accurate based on the current commit.

<br>

<details>
<summary>❌ - Toggle examples of <strong>incorrect</strong> code for this rule</summary>

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<button></button>
~~~~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<button (click)="onClick()"></button>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<button type="whatever"></button>
        ~~~~~~~~~~~~~~~
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ❌ Invalid Code

```html
<button [attr.type]="'whatever'"></button>
        ~~~~~~~~~~~~~~~~~~~~~~~~
```

</details>

<br>

---

<br>

<details>
<summary>✅ - Toggle examples of <strong>correct</strong> code for this rule</summary>

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button [attr.type]="'button'"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button [attr.type]="'submit'"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button [attr.type]="'reset'"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button type="button"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button type="submit"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button type="reset"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button class="primary" type="submit"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button (click)="onClick()" type="button"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button [class.primary]="true" [attr.type]="'submit'"></button>
```

<br>

---

<br>

#### Default Config

```json
{
  "rules": {
    "@angular-eslint/template/button-has-type": [
      "error"
    ]
  }
}
```

<br>

#### ✅ Valid Code

```html
<button [disabled]="true" [attr.type]="'button'"></button>
```

</details>

<br>