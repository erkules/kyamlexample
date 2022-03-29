
# kustomize macht yaml-check


~~~
kustimize build . 
~~~


expected:

~~~
Error: map[string]interface {}(nil): yaml: unmarshal errors:
  line 7: mapping key "labels" already defined at line 5
~~~
