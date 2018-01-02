maxima implementation of smith normal form

how to use:
put the _smith_normal_form.mac_ in a folder that's in your _file_search_maxima_ path, or extend _file_search_maxima_ with the path where you have put the .mac file.
```
(%i1) load(smith_normal_form);
(%o1)     smith_normal_form.mac

(%i2) smith_normal_form(matrix([1,2,3,4],[5,6,7,8]));

                                           [ 1  - 1   0    0  ]
                                           [                  ]
               [ 1   0  ]  [ 1  0  0  0 ]  [ 2  - 1  - 1  - 1 ]
(%o2)         [[        ], [            ], [                  ]]
               [ 1  - 1 ]  [ 0  4  0  0 ]  [ 3  - 1  - 1  - 1 ]
                                           [                  ]
                                           [ 4  - 1  - 1   0  ]

```

