# SCRUBS - Let's Prepare The Operation

Scrubs is a little documentation tool written in POSIX-Shell. It should make easier to work in teams in a suckless way.

## Features

There are two kinds of tags which are displayed in scrubs, `DOC` and `TODO`.

`DOC` is used to document your functions or classes. It has the following structur:

``` c++
/** DOC
 * @type function
 * @name some_random_function
 *
 * @param input * data
 * the input data for processing
 *
 * @return output
 *
 * @description
 * Here you have the function description.
 * It is allowed to have multiple lines.
 * Isn't that cool?
 */
```

The `TODO` tag has the following structur:

``` c++
/** TODO
 * @category some_bug
 *
 * @description
 * Some weird bug lol
 * what is this???
 */
```

*For more examples see `example.cpp`*

## Install

There is a *Makefile* so you are able to install `scrubs` with:

``` bash
sudo make install
```

To uninstall

``` bash
sudo make uninstall
```
