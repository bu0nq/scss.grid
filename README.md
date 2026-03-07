# SCSS.Mixin.Grids

Package for integrating `SCSS.Mixin.Girds` in a web environment.

![npm](https://img.shields.io/npm/v/@bu0nq/scss.mixin.grids?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/scss.mixin.grids?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @bu0nq/scss.mixin.grids
```

## Usage

```scss
@use "@bu0nq/scss.mixin.grids/grids";
```

or

```scss
@use "@bu0nq/scss.mixin.grids/variables" with (
    $is-class: true,
    $is-class-columns: $is-class,
    $is-class-rows: $is-class,
    $is-class-gap: $is-class,
    $is-class-column-start: $is-class,
    $is-class-column-end: $is-class,
    $is-class-column-gap: $is-class,
    $is-class-row-start: $is-class,
    $is-class-row-end: $is-class,
    $is-class-row-gap: $is-class,
    $is-data: true,
    $is-data-columns: $is-data,
    $is-data-rows: $is-data,
    $is-data-gap: $is-data,
    $is-data-column-start: $is-data,
    $is-data-column-end: $is-data,
    $is-data-column-gap: $is-data,
    $is-data-row-start: $is-data,
    $is-data-row-end: $is-data,
    $is-data-row-gap: $is-data,
);

@use "@bu0nq/scss.mixin.grids/grids";
```

### Columns

Mixins for changing the `columns` of a block or element.

| Mixin Name | Additional mixins                    | Class            | Data                   |
|------------|--------------------------------------|------------------|------------------------|
| columns-1  | class-columns-1<br/>data-columns-1   | .grid-columns-1  | data-grid-columns="1"  |
| columns-2  | class-columns-2<br/>data-columns-2   | .grid-columns-2  | data-grid-columns="2"  |
| columns-3  | class-columns-3<br/>data-columns-3   | .grid-columns-3  | data-grid-columns="3"  |
| columns-4  | class-columns-4<br/>data-columns-4   | .grid-columns-4  | data-grid-columns="4"  |
| columns-5  | class-columns-5<br/>data-columns-5   | .grid-columns-5  | data-grid-columns="5"  |
| columns-6  | class-columns-6<br/>data-columns-6   | .grid-columns-6  | data-grid-columns="6"  |
| columns-7  | class-columns-7<br/>data-columns-7   | .grid-columns-7  | data-grid-columns="7"  |
| columns-8  | class-columns-8<br/>data-columns-8   | .grid-columns-8  | data-grid-columns="8"  |
| columns-9  | class-columns-9<br/>data-columns-9   | .grid-columns-9  | data-grid-columns="9"  |
| columns-10 | class-columns-10<br/>data-columns-10 | .grid-columns-10 | data-grid-columns="10" |
| columns-11 | class-columns-11<br/>data-columns-11 | .grid-columns-11 | data-grid-columns="11" |
| columns-12 | class-columns-12<br/>data-columns-12 | .grid-columns-12 | data-grid-columns="12" |

### Rows

Mixins for changing the `rows` of a block or element.

| Mixin Name | Additional mixins              | Class         | Data                |
|------------|--------------------------------|---------------|---------------------|
| rows-1     | class-rows-1<br/>data-rows-1   | .grid-rows-1  | data-grid-rows="1"  |
| rows-2     | class-rows-2<br/>data-rows-2   | .grid-rows-2  | data-grid-rows="2"  |
| rows-3     | class-rows-3<br/>data-rows-3   | .grid-rows-3  | data-grid-rows="3"  |
| rows-4     | class-rows-4<br/>data-rows-4   | .grid-rows-4  | data-grid-rows="4"  |
| rows-5     | class-rows-5<br/>data-rows-5   | .grid-rows-5  | data-grid-rows="5"  |
| rows-6     | class-rows-6<br/>data-rows-6   | .grid-rows-6  | data-grid-rows="6"  |
| rows-7     | class-rows-7<br/>data-rows-7   | .grid-rows-7  | data-grid-rows="7"  |
| rows-8     | class-rows-8<br/>data-rows-8   | .grid-rows-8  | data-grid-rows="8"  |
| rows-9     | class-rows-9<br/>data-rows-9   | .grid-rows-9  | data-grid-rows="9"  |
| rows-10    | class-rows-10<br/>data-rows-10 | .grid-rows-10 | data-grid-rows="10" |
| rows-11    | class-rows-11<br/>data-rows-11 | .grid-rows-11 | data-grid-rows="11" |
| rows-12    | class-rows-12<br/>data-rows-12 | .grid-rows-12 | data-grid-rows="12" |

### Gap

Mixins for changing the `gap` of a block or element.

| Mixin Name | Additional mixins                | Class          | Data                 |
|------------|----------------------------------|----------------|----------------------|
| gap-xs     | class-gap-xs<br/>data-gap-xs     | .grid-gap-xs   | data-grid-gap="xs"   |
| gap-sm     | class-gap-sm<br/>data-gap-sm     | .grid-gap-sm   | data-grid-gap="sm"   |
| gap-md     | class-gap-md<br/>data-gap-md     | .grid-gap-md   | data-grid-gap="md"   |
| gap-base   | class-gap-base<br/>data-gap-base | .grid-gap-base | data-grid-gap="base" |
| gap-lg     | class-gap-lg<br/>data-gap-lg     | .grid-gap-lg   | data-grid-gap="lg"   |
| gap-xl     | class-gap-xl<br/>data-gap-xl     | .grid-gap-xl   | data-grid-gap="xl"   |
| gap-xxl    | class-gap-xxl<br/>data-gap-xxl   | .grid-gap-xxl  | data-grid-gap="xxl"  |

### Column Start

Mixins for changing the `column-start` of a block or element.

| Mixin Name      | Additional mixins                              | Class                 | Data                        |
|-----------------|------------------------------------------------|-----------------------|-----------------------------|
| column-start-1  | class-column-start-1<br/>data-column-start-1   | .grid-column-start-1  | data-grid-column-start="1"  |
| column-start-2  | class-column-start-2<br/>data-column-start-2   | .grid-column-start-2  | data-grid-column-start="2"  |
| column-start-3  | class-column-start-3<br/>data-column-start-3   | .grid-column-start-3  | data-grid-column-start="3"  |
| column-start-4  | class-column-start-4<br/>data-column-start-4   | .grid-column-start-4  | data-grid-column-start="4"  |
| column-start-5  | class-column-start-5<br/>data-column-start-5   | .grid-column-start-5  | data-grid-column-start="5"  |
| column-start-6  | class-column-start-6<br/>data-column-start-6   | .grid-column-start-6  | data-grid-column-start="6"  |
| column-start-7  | class-column-start-7<br/>data-column-start-7   | .grid-column-start-7  | data-grid-column-start="7"  |
| column-start-8  | class-column-start-8<br/>data-column-start-8   | .grid-column-start-8  | data-grid-column-start="8"  |
| column-start-9  | class-column-start-9<br/>data-column-start-9   | .grid-column-start-9  | data-grid-column-start="9"  |
| column-start-10 | class-column-start-10<br/>data-column-start-10 | .grid-column-start-10 | data-grid-column-start="10" |
| column-start-11 | class-column-start-11<br/>data-column-start-11 | .grid-column-start-11 | data-grid-column-start="11" |
| column-start-12 | class-column-start-12<br/>data-column-start-12 | .grid-column-start-12 | data-grid-column-start="12" |

### Column End

Mixins for changing the `column-end` of a block or element.

| Mixin Name    | Additional mixins                          | Class               | Data                      |
|---------------|--------------------------------------------|---------------------|---------------------------|
| column-end-1  | class-column-end-1<br/>data-column-end-1   | .grid-column-end-1  | data-grid-column-end="1"  |
| column-end-2  | class-column-end-2<br/>data-column-end-2   | .grid-column-end-2  | data-grid-column-end="2"  |
| column-end-3  | class-column-end-3<br/>data-column-end-3   | .grid-column-end-3  | data-grid-column-end="3"  |
| column-end-4  | class-column-end-4<br/>data-column-end-4   | .grid-column-end-4  | data-grid-column-end="4"  |
| column-end-5  | class-column-end-5<br/>data-column-end-5   | .grid-column-end-5  | data-grid-column-end="5"  |
| column-end-6  | class-column-end-6<br/>data-column-end-6   | .grid-column-end-6  | data-grid-column-end="6"  |
| column-end-7  | class-column-end-7<br/>data-column-end-7   | .grid-column-end-7  | data-grid-column-end="7"  |
| column-end-8  | class-column-end-8<br/>data-column-end-8   | .grid-column-end-8  | data-grid-column-end="8"  |
| column-end-9  | class-column-end-9<br/>data-column-end-9   | .grid-column-end-9  | data-grid-column-end="9"  |
| column-end-10 | class-column-end-10<br/>data-column-end-10 | .grid-column-end-10 | data-grid-column-end="10" |
| column-end-11 | class-column-end-11<br/>data-column-end-11 | .grid-column-end-11 | data-grid-column-end="11" |
| column-end-12 | class-column-end-12<br/>data-column-end-12 | .grid-column-end-12 | data-grid-column-end="12" |

### Column Gap

Mixins for changing the `column-gap` of a block or element.

| Mixin Name      | Additional mixins                              | Class                 | Data                        |
|-----------------|------------------------------------------------|-----------------------|-----------------------------|
| column-gap-xs   | class-column-gap-xs<br/>data-column-gap-xs     | .grid-column-gap-xs   | data-grid-column-gap="xs"   |
| column-gap-sm   | class-column-gap-sm<br/>data-column-gap-sm     | .grid-column-gap-sm   | data-grid-column-gap="sm"   |
| column-gap-md   | class-column-gap-md<br/>data-column-gap-md     | .grid-column-gap-md   | data-grid-column-gap="md"   |
| column-gap-base | class-column-gap-base<br/>data-column-gap-base | .grid-column-gap-base | data-grid-column-gap="base" |
| column-gap-lg   | class-column-gap-lg<br/>data-column-gap-lg     | .grid-column-gap-lg   | data-grid-column-gap="lg"   |
| column-gap-xl   | class-column-gap-xl<br/>data-column-gap-xl     | .grid-column-gap-xl   | data-grid-column-gap="xl"   |
| column-gap-xxl  | class-column-gap-xxl<br/>data-column-gap-xxl   | .grid-column-gap-xxl  | data-grid-column-gap="xxl"  |

### Row Start

Mixins for changing the `row-start` of a block or element.

| Mixin Name   | Additional mixins                        | Class              | Data                     |
|--------------|------------------------------------------|--------------------|--------------------------|
| row-start-1  | class-row-start-1<br/>data-row-start-1   | .grid-row-start-1  | data-grid-row-start="1"  |
| row-start-2  | class-row-start-2<br/>data-row-start-2   | .grid-row-start-2  | data-grid-row-start="2"  |
| row-start-3  | class-row-start-3<br/>data-row-start-3   | .grid-row-start-3  | data-grid-row-start="3"  |
| row-start-4  | class-row-start-4<br/>data-row-start-4   | .grid-row-start-4  | data-grid-row-start="4"  |
| row-start-5  | class-row-start-5<br/>data-row-start-5   | .grid-row-start-5  | data-grid-row-start="5"  |
| row-start-6  | class-row-start-6<br/>data-row-start-6   | .grid-row-start-6  | data-grid-row-start="6"  |
| row-start-7  | class-row-start-7<br/>data-row-start-7   | .grid-row-start-7  | data-grid-row-start="7"  |
| row-start-8  | class-row-start-8<br/>data-row-start-8   | .grid-row-start-8  | data-grid-row-start="8"  |
| row-start-9  | class-row-start-9<br/>data-row-start-9   | .grid-row-start-9  | data-grid-row-start="9"  |
| row-start-10 | class-row-start-10<br/>data-row-start-10 | .grid-row-start-10 | data-grid-row-start="10" |
| row-start-11 | class-row-start-11<br/>data-row-start-11 | .grid-row-start-11 | data-grid-row-start="11" |
| row-start-12 | class-row-start-12<br/>data-row-start-12 | .grid-row-start-12 | data-grid-row-start="12" |

### Row End

Mixins for changing the `row-end` of a block or element.

| Mixin Name | Additional mixins                    | Class            | Data                   |
|------------|--------------------------------------|------------------|------------------------|
| row-end-1  | class-row-end-1<br/>data-row-end-1   | .grid-row-end-1  | data-grid-row-end="1"  |
| row-end-2  | class-row-end-2<br/>data-row-end-2   | .grid-row-end-2  | data-grid-row-end="2"  |
| row-end-3  | class-row-end-3<br/>data-row-end-3   | .grid-row-end-3  | data-grid-row-end="3"  |
| row-end-4  | class-row-end-4<br/>data-row-end-4   | .grid-row-end-4  | data-grid-row-end="4"  |
| row-end-5  | class-row-end-5<br/>data-row-end-5   | .grid-row-end-5  | data-grid-row-end="5"  |
| row-end-6  | class-row-end-6<br/>data-row-end-6   | .grid-row-end-6  | data-grid-row-end="6"  |
| row-end-7  | class-row-end-7<br/>data-row-end-7   | .grid-row-end-7  | data-grid-row-end="7"  |
| row-end-8  | class-row-end-8<br/>data-row-end-8   | .grid-row-end-8  | data-grid-row-end="8"  |
| row-end-9  | class-row-end-9<br/>data-row-end-9   | .grid-row-end-9  | data-grid-row-end="9"  |
| row-end-10 | class-row-end-10<br/>data-row-end-10 | .grid-row-end-10 | data-grid-row-end="10" |
| row-end-11 | class-row-end-11<br/>data-row-end-11 | .grid-row-end-11 | data-grid-row-end="11" |
| row-end-12 | class-row-end-12<br/>data-row-end-12 | .grid-row-end-12 | data-grid-row-end="12" |

### Row Gap

Mixins for changing the `row-gap` of a block or element.

| Mixin Name   | Additional mixins                        | Class              | Data                     |
|--------------|------------------------------------------|--------------------|--------------------------|
| row-gap-xs   | class-row-gap-xs<br/>data-row-gap-xs     | .grid-row-gap-xs   | data-grid-row-gap="xs"   |
| row-gap-sm   | class-row-gap-sm<br/>data-row-gap-sm     | .grid-row-gap-sm   | data-grid-row-gap="sm"   |
| row-gap-md   | class-row-gap-md<br/>data-row-gap-md     | .grid-row-gap-md   | data-grid-row-gap="md"   |
| row-gap-base | class-row-gap-base<br/>data-row-gap-base | .grid-row-gap-base | data-grid-row-gap="base" |
| row-gap-lg   | class-row-gap-lg<br/>data-row-gap-lg     | .grid-row-gap-lg   | data-grid-row-gap="lg"   |
| row-gap-xl   | class-row-gap-xl<br/>data-row-gap-xl     | .grid-row-gap-xl   | data-grid-row-gap="xl"   |
| row-gap-xxl  | class-row-gap-xxl<br/>data-row-gap-xxl   | .grid-row-gap-xxl  | data-grid-row-gap="xxl"  |
