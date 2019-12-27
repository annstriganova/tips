# Python Tips

* [Compare To `None`](#compare-to-none)
* [Update `dict`](#update-dict)
* [Create `dict` or `list`](#create-dict-or-list)
* [String Concatenation](#string-concatenation)

## Compare To `None`

Use **is None** instead of `==None`.

## Update `dict`

Use `d[k]=v` instead of `d.update({k:v})`.

[SO question](https://stackoverflow.com/questions/15456158/python-dict-update-vs-subscript-to-add-a-single-key-value-pair)

## Create `dict` or `list`

Use `{}` and `[]` instead of `dict()` and `list()`.

[SO question](https://stackoverflow.com/questions/5790860/and-vs-list-and-dict-which-is-better)

## String Concatenation

Use `"{}.png".format(arr[0]) instead of `arr[0] + ".png"`.
 
[Performance Tips](https://wiki.python.org/moin/PythonSpeed/PerformanceTips#head-c849d5d5d94bc3eacbff9d5746af4083443cf2ca)
