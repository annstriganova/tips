1. Compare to `None`

Use **is None** instead of ~==None~.

2. Update `dict`

Use `d[k]=v` instead of ~d.update({k:v})~.

[SO question](https://stackoverflow.com/questions/15456158/python-dict-update-vs-subscript-to-add-a-single-key-value-pair)

3. Create `dict` or `list`

Use `{}` and `[]` instead of `dict()` and `list()`.

[SO question](https://stackoverflow.com/questions/5790860/and-vs-list-and-dict-which-is-better)

4. String concatenation

Use `"{}.png".format(arr[0]) instead of `arr[0] + ".png"`.
 
[Performance Tips](https://wiki.python.org/moin/PythonSpeed/PerformanceTips#head-c849d5d5d94bc3eacbff9d5746af4083443cf2ca)

